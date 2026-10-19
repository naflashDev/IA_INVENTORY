# 🧠 AI Skills & Agents Inventory

Un catálogo curado y modular de repositorios, herramientas y recursos sobre **Skills**, **Agentes** y **Sistemas Autónomos de Inteligencia Artificial**, organizado por subdirectorios según **Temática**, **Orientación Técnica** y **Sector de Aplicación**.

---

## 📁 Estructura del Repositorio

El inventario está desacoplado en carpetas dedicadas para facilitar la navegación y el mantenimiento independiente:

```text
SKILL_INVENTORY/
├── orientaciones/
│   ├── autonomos/                     # Agentes goal-driven y reflexivos
│   ├── mcp-tools/                     # Servidores MCP, protocolos y herramientas
│   └── multi-agente/                  # Frameworks y arquitecturas multi-agente
├── sectores/
│   ├── ecommerce/                     # Comercio electrónico y retail
│   ├── fintech/                       # Finanzas, contabilidad y fraude
│   ├── legal/                         # Compliance, contratos y normativas
│   └── salud/                         # Sanidad, medicina y biotecnología
└── tematicas/
    ├── automatizacion-productividad/  # Automatización de tareas y browser ops
    ├── ciberseguridad/                # Pentesting, auditorías y detección
    ├── datos-analitica/               # Análisis de datos, SQL y BI
    ├── devops-desarrollo/             # Coding assistants, CI/CD y refactor
    └── investigacion-rag/             # RAG, búsqueda profunda y literatura
```

---

## 📑 Índice Rápido de Categorías

### 🗂️ 1. Por Temática / Capacidades
- [🛡️ Ciberseguridad & Pentesting](tematicas/ciberseguridad/README.md)
- [💻 Desarrollo de Software & DevOps](tematicas/devops-desarrollo/README.md)
- [🔍 Investigación, RAG & Recuperación de Información](tematicas/investigacion-rag/README.md)
- [⚡ Automatización & Productividad](tematicas/automatizacion-productividad/README.md)
- [📊 Datos, Analytics & Business Intelligence](tematicas/datos-analitica/README.md)

### 🧩 2. Por Orientación Técnica
- [🤝 Frameworks Multi-Agente](orientaciones/multi-agente/README.md) (CrewAI, AutoGen, LangGraph, etc.)
- [🔌 Protocolo MCP & Herramientas](orientaciones/mcp-tools/README.md) (Model Context Protocol, Servers oficiales)
- [🤖 Agentes Autónomos / Goal-Driven](orientaciones/autonomos/README.md)

### 🏢 3. Por Sector Industrial
- [💳 Fintech & Servicios Financieros](sectores/fintech/README.md)
- [🏥 Salud & Biotecnología](sectores/salud/README.md)
- [⚖️ Legal & Compliance](sectores/legal/README.md)
- [🛍️ E-Commerce & Retail](sectores/ecommerce/README.md)

---

## 📝 Plantilla para Nuevas Entradas

Para agregar un nuevo repositorio a cualquiera de los subdirectorios, añade una fila o ficha con el formato estándar:

```markdown
### [Nombre del Repositorio](https://github.com/usuario/repo)
- **Tipo**: `Skill` | `Agente` | `Multi-Agente` | `MCP Server` | `Framework`
- **Descripción**: Resumen conciso de la funcionalidad y caso de uso.
- **Stack / Protocolo**: Lenguaje base, frameworks o APIs integradas (ej. Python, TypeScript, MCP, LangGraph).
```

---

## 🤝 Cómo Contribuir

1. Localiza el subdirectorio adecuado (`tematicas/`, `orientaciones/` o `sectores/`).
2. Edita el archivo `README.md` correspondiente.
3. Si el repositorio abarca más de un área, puedes referenciarlo en el subdirectorio primario e indexarlo en el secundario.
4. Realiza tu commit y envía tu Pull Request.
