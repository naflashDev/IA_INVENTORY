# 📏 Plantilla y Guía: Reglas de Entorno (`.cursorrules` / `.windsurfrules`)

Los archivos de reglas de entorno permiten fijar directrices globales, estándares de codificación y restricciones operativas para los asistentes de Inteligencia Artificial integrados directamente en IDEs como **Cursor**, **Windsurf** o **Copilot Workspace**.

---

## ⚙️ ¿Cómo Funciona?

- El asistente lee este archivo al principio de cada interacción o generación de código, usándolo como directiva de contexto permanente para ese repositorio.
- Permite definir el rol preferido, las tecnologías centrales, el estilo de código y las restricciones de uso de la terminal.

---

## 📋 Plantilla Estándar (`.cursorrules`)

```text
# Contexto y Rol
Actúa como un desarrollador Senior en TypeScript y Python. El foco de este proyecto es la modularidad y el rendimiento.

# Reglas de Código
- Siempre tipar estrictamente los parámetros y retornos de funciones.
- No utilizar 'any' en TypeScript salvo justificación explícita.
- Preferir programación funcional pura y funciones inmutables donde sea posible.

# Manejo de Terminal y Herramientas
- No instalar librerías pesadas sin consultar.
- Asegúrate de ejecutar el linter después de refactorizaciones grandes.
- Los comentarios en el código deben explicar el "por qué", no el "qué".
```

---

## 🚀 Implementación

1. Crea un archivo llamado `.cursorrules` (o `.windsurfrules` según tu editor) en la raíz del proyecto.
2. Copia y adapta las directrices para que coincidan con la arquitectura y el stack de tu equipo.
