# 🔌 Ecosistema MCP & Tool Calling

Servidores del Model Context Protocol (MCP), catálogos de herramientas, SDKs y protocolos de interoperabilidad para agentes e interfaces de IA.

---

## 📋 Catálogo de Servidores y SDKs MCP

| Repositorio / Servidor | Tipo | Descripción | Protocolo / Stack | Enlace |
| :--- | :--- | :--- | :--- | :--- |
| **MCP Servers (Oficiales)** | MCP Server | Servidores de referencia: Filesystem, Git, Postgres, Fetch, Memory y herramientas de prueba | TypeScript, Python | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) |
| **MCP Registry** | MCP Server | Registro central oficial para metadatos, namespaces y publicación de `server.json` | Go, TypeScript | [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) |
| **MCP Inspector** | Herramienta / UI | Inspector visual para conectar, depurar y probar llamadas a herramientas de servidores MCP | TypeScript, Node.js | [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) |
| **GitHub MCP Server** | MCP Server | Conecta agentes con GitHub para administrar repositorios, issues, pull requests y CI/CD | Go | [github/github-mcp-server](https://github.com/github/github-mcp-server) |
| **Playwright MCP** | MCP Server | Servidor oficial de Playwright para navegación e inspección de páginas mediante árbol de accesibilidad | TypeScript, Node.js | [microsoft/playwright](https://github.com/microsoft/playwright) |
| **Context7** | MCP Server | Documentación actualizada y contextualizada de librerías para mitigar alucinaciones de código | TypeScript | [upstash/context7](https://github.com/upstash/context7) |
| **Cloudflare MCP Server** | MCP Server | Servidores MCP para operar servicios de Cloudflare, DNS, observabilidad e infraestructura | TypeScript | [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) |
| **AWS Labs MCP** | MCP Server | Servidores oficiales de AWS Labs para conectar agentes a la nube y servicios AWS | Python | [awslabs/mcp](https://github.com/awslabs/mcp) |
| **Microsoft MCP** | MCP Server | Integraciones y servidores de referencia de herramientas del ecosistema Microsoft | Políglota | [microsoft/mcp](https://github.com/microsoft/mcp) |
| **GitLab MCP Server** | MCP Server | Integración oficial para gestionar proyectos, repositorios y pipelines de GitLab | Go, TypeScript | [gitlab-org/gitlab-mcp-server](https://github.com/gitlab-org/gitlab-mcp-server) |
| **DesktopCommander MCP** | MCP Server | Herramientas para operar con terminal, procesos locales y gestión de archivos del escritorio | TypeScript, Node.js | [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) |
| **Docker MCP Servers** | MCP Server | Herramientas para empaquetar, aislar y ejecutar servidores MCP dentro de contenedores Docker | Docker, Go | [docker/mcp-servers](https://github.com/docker/mcp-servers) |
| **ExecuteAutomation Playwright** | MCP Server | Servidor MCP alternativo para automatización web, capturas y scraping estructurado con Playwright | TypeScript, Node.js | [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) |
| **MCP TypeScript SDK** | SDK / Framework | SDK oficial TypeScript para construir clientes y servidores MCP (stdio y HTTP SSE) | TypeScript, Node.js | [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) |
| **MCP Python SDK** | SDK / Framework | SDK oficial Python para implementar servidores y herramientas MCP asíncronas | Python | [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) |
| **MCP Go SDK** | SDK / Framework | SDK oficial en Go para integraciones ligeras de clientes y servidores MCP | Go | [modelcontextprotocol/go-sdk](https://github.com/modelcontextprotocol/go-sdk) |
| **mcp-use** | SDK / Framework | SDK para conectar aplicaciones y agentes con múltiples servidores MCP de forma simplificada | Python, TypeScript | [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) |
| **Awesome Remote MCP Servers** | Directorio | Directorio de servidores MCP alojados en la nube accesibles directamente por URL | Markdown | [punkpeye/awesome-remote-mcp-servers](https://github.com/punkpeye/awesome-remote-mcp-servers) |
| **MarkItDown (Microsoft)** | MCP Server / Conversión | Convierte documentos complejos (PDF, Office, imágenes) a Markdown limpio para consumo de agentes y RAG. Incluye paquete MCP | Python, CLI, MCP | [microsoft/markitdown](https://github.com/microsoft/markitdown) |
| **FastMCP (Prefect)** | Framework / SDK | Framework de alto nivel en Python para crear servidores y clientes MCP de forma concisa y declarativa | Python, MCP | [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) |
| **Composio** | Tooling / Integración | Plataforma de conectores e integraciones para vincular agentes a más de 250 herramientas SaaS con autenticación gestionada | Python, TypeScript, MCP | [ComposioHQ/composio](https://github.com/ComposioHQ/composio) |
| **ToolHive** | Plataforma / Seguridad | Plataforma para ejecutar y orquestar servidores MCP empresariales en Kubernetes con aislamiento y seguridad | Go, Kubernetes, Contenedores | [stacklok/toolhive](https://github.com/stacklok/toolhive) |
| **NitroStack** | Framework | Framework full-stack para crear, probar y desplegar servidores MCP y aplicaciones nativas de IA | TypeScript, MCP | [nitrocloudofficial/nitrostack](https://github.com/nitrocloudofficial/nitrostack) |
| **MCP Java SDK** | SDK / Framework | SDK oficial de Java para construir clientes y servidores MCP compatibles con el ecosistema Spring AI | Java, JVM, MCP | [modelcontextprotocol/java-sdk](https://github.com/modelcontextprotocol/java-sdk) |
| **MCP Atlassian** | MCP Server | Conecta agentes con Jira y Confluence para consultar incidencias, proyectos y documentación corporativa | Python, Atlassian APIs | [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) |
| **Cloudflare Agents SDK** | Framework | SDK para desplegar agentes con estado persistente y comunicación en la infraestructura distribuida de Cloudflare Workers | TypeScript, Workers, MCP | [cloudflare/agents](https://github.com/cloudflare/agents) |
| **Portkey Gateway** | Gateway / Guardrails | Gateway de IA para enrutar peticiones multi-proveedor, aplicar guardrails y centralizar observabilidad y MCP | TypeScript, API Gateway | [Portkey-AI/gateway](https://github.com/Portkey-AI/gateway) |
