# 🔌 Plantilla y Guía: Servidores MCP (`mcp.json`)

El protocolo **Model Context Protocol (MCP)** estandariza la conexión entre modelos de lenguaje y fuentes de datos locales, bases de datos o herramientas externas mediante arquitectura cliente-servidor JSON-RPC.

---

## ⚙️ ¿Cómo Funciona la Configuración MCP?

1. **Estructura**: El archivo `mcp.json` (o la clave `"mcpServers"` en clientes como Claude Desktop, Cursor o antigravity) define los ejecutables y argumentos que inicializan cada servidor.
2. **Transportes**:
   - `stdio`: El cliente lanza un proceso local (Node.js, Python, binario) y se comunica a través de entrada y salida estándar.
   - `sse`: Servidor remoto o local mediante Server-Sent Events por HTTP.
3. **Parámetros Clave**:
   - `command`: Binario ejecutable (`npx`, `python`, `node`, `uvx`, `docker`).
   - `args`: Lista de argumentos para iniciar el servidor.
   - `env`: Variables de entorno específicas (claves de API, credenciales, tokens).

---

## 📋 Plantilla Estándar (`mcp.json`)

```json
{
  "mcpServers": {
    "filesystem-server": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-filesystem",
        "/ruta/permitida/proyecto"
      ],
      "env": {}
    },
    "custom-python-mcp": {
      "command": "python",
      "args": [
        "-m",
        "mi_servidor_mcp"
      ],
      "env": {
        "API_KEY": "tu_api_key_aqui",
        "DEBUG": "true"
      }
    },
    "sqlite-server": {
      "command": "uvx",
      "args": [
        "mcp-server-sqlite",
        "--db-path",
        "./data/database.sqlite"
      ]
    }
  }
}
```

---

## 🚀 Cómo Implementarlo

1. **En Claude Desktop**:
   - Guarda el contenido en `%APPDATA%\Claude\claude_desktop_config.json`.
2. **En Antigravity / IDEs**:
   - Regístralo en la carpeta de configuración correspondiente (`mcp_config.json` o settings de la extensión).
3. **Validación**:
   - Comprueba que los binarios (`npx`, `uvx`, `python`) estén disponibles en tu `PATH`.
