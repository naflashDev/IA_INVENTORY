# Segunda búsqueda: repositorios públicos de agentes, skills, hooks y MCP con más estrellas

**Fecha de consulta:** 19 de octubre de 2026  
**Criterio de ordenación:** estrellas visibles en GitHub, de mayor a menor, en la fecha de consulta.  
**Alcance:** 40 repositorios nuevos respecto al primer catálogo, priorizando proyectos populares y útiles para el ecosistema de agentes. No es una clasificación universal: algunos repos son herramientas adyacentes (editores, memoria, conversión de documentos o sandboxes) que amplían las capacidades de los agentes.  
**Cómo leer las estrellas:** cifras redondeadas según la interfaz de GitHub; cambian continuamente. Los repositorios marcados como **ARCHIVADO** siguen siendo públicos, pero no deben tratarse como proyectos con mantenimiento activo.

> La clasificación por estrellas mide popularidad, no seguridad, calidad, vigencia, licencias compatibles ni idoneidad para producción. Revisa permisos, scripts de instalación, acceso a secretos y actividad reciente antes de instalar hooks, skills o servidores MCP.

---

## Repositorios añadidos, ordenados por estrellas

### [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)
- **Tipo**: `Agente`
- **Descripción**: Agente personal de propósito general con CLI, memoria, herramientas, skills, automatizaciones y conectores; sirve como entorno extensible para ejecutar tareas de varios pasos.
- **Stack / Protocolo**: Python; LLMs, herramientas, MCP y skills
- **Estrellas**: `~255,1k` (19-10-2026)

### [Anomalyco/opencode](https://github.com/Anomalyco/opencode)
- **Tipo**: `Agente`
- **Descripción**: Agente de programación open source para trabajar desde terminal o interfaces compatibles, explorar repositorios, editar código y ejecutar tareas de desarrollo.
- **Stack / Protocolo**: TypeScript; Node/Bun, proveedores LLM y MCP
- **Estrellas**: `~217k` (19-10-2026)

### [microsoft/markitdown](https://github.com/microsoft/markitdown)
- **Tipo**: `MCP Server`
- **Descripción**: Convierte documentos y ficheros (incluidos formatos de Office) a Markdown, útil para dar contenido estructurado a agentes y pipelines RAG. Incluye el paquete `markitdown-mcp`.
- **Stack / Protocolo**: Python; CLI, librería de conversión y paquete MCP
- **Estrellas**: `~191k` (19-10-2026)

### [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)
- **Tipo**: `Framework`
- **Descripción**: Plataforma para crear y ejecutar agentes y automatizaciones con distintos grados de autonomía; útil para prototipos de flujos de trabajo basados en objetivos.
- **Stack / Protocolo**: Python, TypeScript/web; LLM APIs y herramientas
- **Estrellas**: `~188k` (19-10-2026)

### [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)
- **Tipo**: `Skill`
- **Descripción**: Skill especializada en diseño de interfaces: sugiere sistemas visuales, tipografía, paletas y patrones UX para generar aplicaciones y sitios más coherentes.
- **Stack / Protocolo**: SKILL.md, scripts y datos de diseño; Claude Code y otros agentes compatibles
- **Estrellas**: `~137k` (19-10-2026)

### [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **Tipo**: `Skill`
- **Descripción**: Memoria persistente entre sesiones para agentes de programación; resume observaciones y permite recuperar contexto relevante. Incluye hooks de ciclo de vida y herramientas MCP de búsqueda de memoria.
- **Stack / Protocolo**: TypeScript/JavaScript, Bun, SQLite, embeddings/Chroma; hooks de Claude Code y MCP
- **Estrellas**: `~102k` (19-10-2026)

### [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)
- **Tipo**: `Framework`
- **Descripción**: CLI para dar a agentes acceso de búsqueda y lectura a múltiples fuentes de Internet y comunidades, como GitHub, Reddit, YouTube y redes sociales.
- **Stack / Protocolo**: Python, CLI, scraping e integraciones de herramientas/MCP
- **Estrellas**: `~99,4k` (19-10-2026)

### [zed-industries/zed](https://github.com/zed-industries/zed)
- **Tipo**: `Framework`
- **Descripción**: Editor de código open source con capacidades de asistencia y agentes para desarrollo. Es una herramienta de entorno de trabajo, no un framework de agentes independiente.
- **Stack / Protocolo**: Rust; editor nativo, integraciones de IA y MCP
- **Estrellas**: `~91,9k` (19-10-2026)

### [bytedance/deer-flow](https://github.com/bytedance/deer-flow)
- **Tipo**: `Multi-Agente`
- **Descripción**: Harness de SuperAgent para investigación, programación y creación de entregables de larga duración; combina subagentes, memoria, sandboxes, herramientas y skills extensibles.
- **Stack / Protocolo**: Python, TypeScript; LangGraph, subagentes, MCP, skills y sandboxes
- **Estrellas**: `~84,1k` (19-10-2026)

### [daytonaio/daytona](https://github.com/daytonaio/daytona)
- **Tipo**: `Framework`
- **Descripción**: Infraestructura para crear entornos aislados donde los agentes ejecutan código generado, útil para tareas de programación que requieren terminal, ficheros y dependencias.
- **Stack / Protocolo**: TypeScript, Go y Python; APIs de sandboxes y ejecución de código
- **Estrellas**: `~71,5k` (19-10-2026) — **ARCHIVADO en el repositorio consultado**

### [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks)
- **Tipo**: `Skill`
- **Descripción**: Recetas y notebooks que muestran patrones de uso de Claude, herramientas, análisis y flujos de trabajo; útil como base de ejemplos para diseñar capacidades de agente.
- **Stack / Protocolo**: Python, Jupyter, APIs de Claude y ejemplos de tool use
- **Estrellas**: `~53,6k` (19-10-2026)

### [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- **Tipo**: `Skill`
- **Descripción**: Biblioteca de skills científicas para investigación, análisis y trabajo con bases de datos de ciencia y medicina; orientada a flujos técnicos reproducibles.
- **Stack / Protocolo**: Markdown (SKILL.md), Python y conectores a bases de datos; estándar Agent Skills
- **Estrellas**: `~52,8k` (19-10-2026)

### [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio)
- **Tipo**: `Agente`
- **Descripción**: Aplicación de escritorio para usar modelos, asistentes y agentes desde una sola interfaz; útil para probar proveedores y flujos de trabajo sin construir un cliente propio.
- **Stack / Protocolo**: TypeScript, Vue/Electron; proveedores LLM y extensiones/integraciones
- **Estrellas**: `~52,7k` (19-10-2026)

### [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills)
- **Tipo**: `Skill`
- **Descripción**: Skills para que agentes trabajen con Obsidian, su CLI y formatos abiertos como Markdown, Bases y JSON Canvas.
- **Stack / Protocolo**: Markdown (SKILL.md), CLI de Obsidian; Claude Code, Codex y agentes compatibles con Agent Skills
- **Estrellas**: `~49,8k` (19-10-2026)

### [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp)
- **Tipo**: `MCP Server`
- **Descripción**: Servidor MCP oficial de Playwright para que agentes naveguen e interactúen con páginas web mediante controles de navegador estructurados.
- **Stack / Protocolo**: TypeScript; Playwright, navegador y MCP
- **Estrellas**: `~38,4k` (19-10-2026)

### [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit)
- **Tipo**: `Framework`
- **Descripción**: Componentes y protocolos para integrar agentes en interfaces de producto, chats y aplicaciones con UI generativa.
- **Stack / Protocolo**: TypeScript, React y Angular; AG-UI y ecosistema de agentes
- **Estrellas**: `~38,1k` (19-10-2026)

### [getzep/graphiti](https://github.com/getzep/graphiti)
- **Tipo**: `Framework`
- **Descripción**: Capa de memoria basada en grafos de conocimiento que se actualizan en tiempo real; ayuda a agentes a mantener relaciones y contexto temporal entre sesiones.
- **Stack / Protocolo**: Python; grafos de conocimiento, bases de datos de grafos y conectores para agentes
- **Estrellas**: `~32k` (19-10-2026)

### [googleworkspace/cli](https://github.com/googleworkspace/cli)
- **Tipo**: `Skill`
- **Descripción**: CLI unificada para Google Drive, Gmail, Calendar, Sheets, Docs, Chat y administración, con skills para que agentes automaticen acciones de Workspace.
- **Stack / Protocolo**: Rust, OAuth 2.0 y Google Discovery APIs; CLI y Agent Skills
- **Estrellas**: `~31,7k` (19-10-2026)

### [mksglu/context-mode](https://github.com/mksglu/context-mode)
- **Tipo**: `MCP Server`
- **Descripción**: Optimiza el contexto de agentes de programación reduciendo y aislando salidas de herramientas, persistiendo memoria y gestionando el enrutamiento mediante MCP y hooks.
- **Stack / Protocolo**: TypeScript; MCP, hooks y múltiples agentes de código
- **Estrellas**: `~30,9k` (19-10-2026)

### [ComposioHQ/composio](https://github.com/ComposioHQ/composio)
- **Tipo**: `Framework`
- **Descripción**: Capa de herramientas e integraciones para conectar agentes a aplicaciones externas, gestionar autenticación y seleccionar herramientas relevantes para cada tarea.
- **Stack / Protocolo**: Python y TypeScript; SDKs, APIs, tool calling y conectores
- **Estrellas**: `~30,6k` (19-10-2026)

### [langchain-ai/deepagents](https://github.com/langchain-ai/deepagents)
- **Tipo**: `Framework`
- **Descripción**: Harness de agentes con planificación, herramientas y gestión de tareas largas, pensado para construir agentes que descomponen objetivos complejos en subtareas.
- **Stack / Protocolo**: Python; LangGraph y ecosistema LangChain
- **Estrellas**: `~30,4k` (19-10-2026)

### [oraios/serena](https://github.com/oraios/serena)
- **Tipo**: `MCP Server`
- **Descripción**: Herramienta para agentes de programación con recuperación semántica y edición de código consciente de la estructura del proyecto; funciona como una especie de IDE para el agente.
- **Stack / Protocolo**: Python; análisis semántico de código y MCP
- **Estrellas**: `~30,4k` (19-10-2026)

### [openai/openai-agents-python](https://github.com/openai/openai-agents-python)
- **Tipo**: `Multi-Agente`
- **Descripción**: SDK para agentes y workflows con herramientas, handoffs, guardrails, sesiones, trazas y participación humana; útil para aplicaciones de producción con varios agentes.
- **Stack / Protocolo**: Python; OpenAI APIs, tool calling y MCP
- **Estrellas**: `~30,1k` (19-10-2026)

### [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp)
- **Tipo**: `Framework`
- **Descripción**: Framework Python para crear servidores y clientes MCP de forma concisa; útil para exponer funciones, datos y servicios como herramientas accesibles a los agentes.
- **Stack / Protocolo**: Python; Model Context Protocol (MCP)
- **Estrellas**: `~28,1k` (19-10-2026)

### [e2b-dev/E2B](https://github.com/e2b-dev/E2B)
- **Tipo**: `Framework`
- **Descripción**: Sandboxes seguros para ejecutar código y herramientas generadas por agentes, con separación del entorno de desarrollo y el host.
- **Stack / Protocolo**: TypeScript, Python y APIs de sandbox; integración con SDKs de agentes
- **Estrellas**: `~14,4k` (19-10-2026)

### [Portkey-AI/gateway](https://github.com/Portkey-AI/gateway)
- **Tipo**: `Framework`
- **Descripción**: Gateway de IA para enrutar peticiones entre proveedores de modelos, aplicar guardrails y centralizar observabilidad y políticas en sistemas de agentes.
- **Stack / Protocolo**: TypeScript; API gateway, SDKs LLM, guardrails y MCP
- **Estrellas**: `~13,2k` (19-10-2026)

### [langchain-ai/open_deep_research](https://github.com/langchain-ai/open_deep_research)
- **Tipo**: `Multi-Agente`
- **Descripción**: Implementación de referencia para agentes de investigación que buscan, sintetizan fuentes y producen informes con workflows de LangGraph.
- **Stack / Protocolo**: Python; LangGraph, LangChain y proveedores LLM
- **Estrellas**: `~12,7k` (19-10-2026) — **ARCHIVADO en el repositorio consultado**

### [assistant-ui/assistant-ui](https://github.com/assistant-ui/assistant-ui)
- **Tipo**: `Framework`
- **Descripción**: Librería de interfaz para construir chats y experiencias de asistentes/agents dentro de aplicaciones, con componentes personalizables y streaming.
- **Stack / Protocolo**: TypeScript, React; integración con SDKs y backends de IA
- **Estrellas**: `~12,6k` (19-10-2026)

### [OpenBMB/XAgent](https://github.com/OpenBMB/XAgent)
- **Tipo**: `Agente`
- **Descripción**: Proyecto de agente autónomo orientado a resolver tareas complejas dividiéndolas en pasos y utilizando herramientas externas.
- **Stack / Protocolo**: Python; LLMs y ejecución de herramientas
- **Estrellas**: `~8,6k` (19-10-2026)

### [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server)
- **Tipo**: `MCP Server`
- **Descripción**: Expone scraping, extracción y búsqueda web de Firecrawl a clientes MCP; útil para agentes que necesitan convertir páginas en contenido estructurado.
- **Stack / Protocolo**: TypeScript; Firecrawl API y MCP
- **Estrellas**: `~7,6k` (19-10-2026)

### [microsoft/TaskWeaver](https://github.com/microsoft/TaskWeaver)
- **Tipo**: `Framework`
- **Descripción**: Framework orientado a agentes que planifican y ejecutan tareas de análisis de datos mediante código; interesante como referencia de arquitectura.
- **Stack / Protocolo**: Python; planificación, ejecución de código y plugins
- **Estrellas**: `~6,2k` (19-10-2026) — **ARCHIVADO en el repositorio consultado**

### [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian)
- **Tipo**: `MCP Server`
- **Descripción**: Conecta agentes con Jira y Confluence para consultar incidencias, proyectos y documentación de equipos.
- **Stack / Protocolo**: Python; APIs de Atlassian y MCP
- **Estrellas**: `~6k` (19-10-2026)

### [cloudflare/agents](https://github.com/cloudflare/agents)
- **Tipo**: `Framework`
- **Descripción**: SDK para crear y desplegar agentes en la plataforma de Cloudflare, con estado, comunicaciones y ejecución en infraestructura distribuida.
- **Stack / Protocolo**: TypeScript; Cloudflare Workers, Durable Objects y APIs de IA
- **Estrellas**: `~5,8k` (19-10-2026)

### [openai/openai-agents-js](https://github.com/openai/openai-agents-js)
- **Tipo**: `Multi-Agente`
- **Descripción**: SDK JavaScript/TypeScript para agentes, handoffs, guardrails, sesiones, trazas, herramientas y experiencias de voz en tiempo real.
- **Stack / Protocolo**: TypeScript; Node.js, Deno, Bun, OpenAI APIs y MCP
- **Estrellas**: `~3,9k` (19-10-2026)

### [jordan-gibbs/hyperresearch](https://github.com/jordan-gibbs/hyperresearch)
- **Tipo**: `Agente`
- **Descripción**: Convierte agentes de Claude Code o Codex en un flujo de investigación profunda que recopila fuentes y construye una wiki de investigación persistente y consultable.
- **Stack / Protocolo**: Python; MCP, plugins/skills para Codex y Claude Code, búsqueda web y citas
- **Estrellas**: `~3,9k` (19-10-2026)

### [modelcontextprotocol/java-sdk](https://github.com/modelcontextprotocol/java-sdk)
- **Tipo**: `Framework`
- **Descripción**: SDK oficial de Java para construir clientes y servidores MCP, útil para integrar herramientas y datos en aplicaciones JVM.
- **Stack / Protocolo**: Java; MCP y ecosistema Spring AI
- **Estrellas**: `~3,7k` (19-10-2026)

### [modelcontextprotocol/ext-apps](https://github.com/modelcontextprotocol/ext-apps)
- **Tipo**: `Framework`
- **Descripción**: Especificación y SDK para MCP Apps: interfaces de usuario embebidas en clientes de IA y servidas por servidores MCP.
- **Stack / Protocolo**: TypeScript; MCP Apps y Model Context Protocol
- **Estrellas**: `~3k` (19-10-2026)

### [nitrocloudofficial/nitrostack](https://github.com/nitrocloudofficial/nitrostack)
- **Tipo**: `Framework`
- **Descripción**: Framework full-stack para crear, probar y desplegar servidores MCP y aplicaciones nativas de IA.
- **Stack / Protocolo**: TypeScript; MCP, aplicaciones web y herramientas de desarrollo
- **Estrellas**: `~2,5k` (19-10-2026)

### [stacklok/toolhive](https://github.com/stacklok/toolhive)
- **Tipo**: `Framework`
- **Descripción**: Plataforma para ejecutar y administrar servidores MCP, con foco en operaciones empresariales, aislamiento y seguridad.
- **Stack / Protocolo**: Go, Kubernetes y contenedores; MCP y políticas de seguridad
- **Estrellas**: `~2,3k` (19-10-2026)

### [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant)
- **Tipo**: `MCP Server`
- **Descripción**: Servidor MCP oficial de Qdrant que permite a los agentes almacenar y recuperar información mediante una base de datos vectorial.
- **Stack / Protocolo**: Python; Qdrant, embeddings y MCP
- **Estrellas**: `~1,6k` (19-10-2026)

---

## Fuentes para continuar ampliando el barrido

- [GitHub Topic: AI Agents, ordenado por estrellas](https://github.com/topics/ai-agents?o=desc&s=stars)
- [GitHub Topic: Agent Skills, ordenado por estrellas](https://github.com/topics/agent-skills?o=desc&s=stars)
- [GitHub Topic: MCP Server, ordenado por estrellas](https://github.com/topics/mcp-server?o=desc&s=stars)
- [GitHub Topic: MCP Servers, ordenado por estrellas](https://github.com/topics/mcp-servers?o=desc&s=stars)
- [GitHub Topic: Claude Code Plugins, ordenado por estrellas](https://github.com/topics/claude-code-plugin?o=desc&s=stars)

**Nota de mantenimiento:** las etiquetas de GitHub son incompletas y los repos pueden cambiar de propietario, archivarse o dejar de mantenerse. Usa estas páginas para actualizar el catálogo y compara fecha del último commit, releases y política de seguridad antes de adoptar un proyecto.
