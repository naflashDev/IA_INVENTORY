# 🪝 Plantilla y Guía: Hooks de Ciclo de Vida

Los **Hooks de Ciclo de Vida** permiten interceptar eventos críticos antes o después de la interacción del usuario, la ejecución de herramientas o la invocación de comandos de terminal, garantizando seguridad, validación y contexto continuo.

---

## ⚙️ ¿Cómo Funcionan los Hooks?

1. **Definición (`hooks.json`)**: Configura el catálogo de eventos que la IA o el entorno monitorea.
2. **Disparadores Admitidos**:
   - `pre_command`: Se ejecuta antes de que un comando de shell o terminal sea procesado. Si el script devuelve un error o código de salida distinto de `0` (y `block_on_failure` es `true`), el comando se cancela.
   - `post_tool_call`: Se ejecuta automáticamente tras usar herramientas de edición (`write_to_file`, `replace_file_content`), ideal para disparar linters o formateadores.
   - `session_start`: Se activa al iniciar la sesión o conversación para inyectar contexto adicional.
3. **Scripts de Ejecución**: Scripts de PowerShell o Shell que reciben argumentos del evento (como el comando a ejecutar) y aplican filtros de seguridad o validaciones de políticas.

---

## 1. Configuración de Hooks (`hooks.json`)

Guarda esta configuración en el directorio de hooks o en la configuración del agente/entorno:

```json
{
  "version": "1.0",
  "hooks": [
    {
      "event": "pre_command",
      "matcher": "git commit|rm -rf|drop database",
      "action": "execute_script",
      "script": "scripts/validate_pre_command.ps1",
      "block_on_failure": true
    },
    {
      "event": "post_tool_call",
      "matcher": "replace_file_content|write_to_file",
      "action": "execute_script",
      "script": "scripts/run_linter.ps1",
      "block_on_failure": false
    },
    {
      "event": "session_start",
      "action": "inject_context",
      "file": "context/project_overview.md"
    }
  ]
}
```

---

## 2. Script de Validación Previa (`hook_pre_command.ps1`)

Este script se encarga de interceptar el comando solicitado antes de su ejecución. Si coincide con algún patrón de la lista negra de comandos peligrosos, aborta inmediatamente con código de salida `1`.

```powershell
param(
    [string]$CommandToRun
)

<#
.SYNOPSIS
    Script de hook para validar comandos antes de ejecutarse en terminal.
.DESCRIPTION
    Inspecciona la cadena del comando entrante y aborta con código de salida 1
    si detecta patrones destructivos o no autorizados.
#>

Write-Host "[HOOK] Validando comando entrante: $CommandToRun"

# Patrones prohibidos o de alto riesgo
$BlockedPatterns = @(
    "rm -rf /",
    "drop database",
    "format ",
    "mkfs",
    "git push --force origin main"
)

foreach ($pattern in $BlockedPatterns) {
    if ($CommandToRun -like "*$pattern*") {
        Write-Error "[ALERTA HOOK] Comando bloqueado por seguridad: Coincidencia con patrón '$pattern'"
        exit 1
    }
}

Write-Host "[HOOK] Comando validado correctamente."
exit 0
```

---

## 🚀 Guía de Implementación y Uso

1. **Instalación**:
   - Guarda el bloque JSON como `hooks.json` en la carpeta de configuración de tu agente o proyecto.
   - Coloca el script `hook_pre_command.ps1` en la ruta especificada (por ejemplo, `scripts/validate_pre_command.ps1`).
2. **Permisos**:
   - Asegúrate de que PowerShell tenga permisos para ejecutar scripts locales (`Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`).
3. **Flujo de Ejecución**:
   - Cuando el agente intente ejecutar un comando en la terminal, el entorno llamará primero al hook pasando el comando como parámetro `$CommandToRun`.
   - Si el comando es seguro, continúa la ejecución normalmente; de lo contrario, el hook emite una advertencia y frena el proceso.
