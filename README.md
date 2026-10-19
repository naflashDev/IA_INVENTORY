# 🧠 AI Skills & Agents Inventory

Un catálogo curado y estructurado de repositorios, herramientas y recursos sobre **Skills**, **Agentes** y **Sistemas Autónomos de Inteligencia Artificial**, clasificados por **Temática**, **Orientación Técnica** y **Sector de Aplicación**.

---

## 📑 Tabla de Contenidos

- [🎯 Estructura de Clasificación](#-estructura-de-clasificación)
- [🗂️ 1. Clasificación por Temática / Capacidades](#️-1-clasificación-por-temática--capacidades)
  - [1.1. Ciberseguridad & Pentesting](#11-ciberseguridad--pentesting)
  - [1.2. Desarrollo de Software & DevOps](#12-desarrollo-de-software--devops)
  - [1.3. Investigación, RAG & Recuperación de Información](#13-investigación-rag--recuperación-de-información)
  - [1.4. Automatización & Productividad](#14-automatización--productividad)
  - [1.5. Datos, Analytics & Business Intelligence](#15-datos-analytics--business-intelligence)
- [🧩 2. Clasificación por Orientación Técnica](#-2-clasificación-por-orientación-técnica)
  - [2.1. Frameworks de Orquestación Multi-Agente](#21-frameworks-de-orquestación-multi-agente)
  - [2.2. Protocolos & Ecosistemas (MCP, Tools & Skills)](#22-protocolos--ecosistemas-mcp-tools--skills)
  - [2.3. Agentes Autónomos / Goal-Driven](#23-agentes-autónomos--goal-driven)
- [🏢 3. Clasificación por Sector Industrial](#-3-clasificación-por-sector-industrial)
  - [3.1. Financiero & Fintech](#31-financiero--fintech)
  - [3.2. Salud & Biotecnología](#32-salud--biotecnología)
  - [3.3. Legal & Compliance](#33-legal--compliance)
  - [3.4. E-Commerce & Retail](#34-e-commerce--retail)
- [📝 Plantilla para Nuevas Entradas](#-plantilla-para-nuevas-entradas)
- [🤝 Contribución](#-contribución)

---

## 🎯 Estructura de Clasificación

Cada repositorio listado contiene la siguiente ficha técnica mínima:
- **Nombre / Enlace**: Nombre del repositorio.
- **Tipo**: `Skill` | `Agente Individual` | `Multi-Agente` | `MCP Server` | `Framework`.
- **Descripción**: Resumen funcional breve.
- **Stack / Modelos**: Tecnologías base o compatibilidad (ej. Python, TypeScript, LangChain, MCP).

---

## 🗂️ 1. Clasificación por Temática / Capacidades

### 1.1. Ciberseguridad & Pentesting
> Agentes y skills enfocados en auditorías de seguridad, pentesting web/API, análisis de vulnerabilidades y detección de amenazas.

| Repositorio | Tipo | Descripción | Stack / Protocolo |
| :--- | :--- | :--- | :--- |
| *Ejemplo: SecAgent* | Agente | Orquestación de escaneos OWASP y análisis de endpoints | Python, Burp API, MCP |

### 1.2. Desarrollo de Software & DevOps
> Agentes de codificación, pair programming, generación de pipelines CI/CD y refactorización asistida.

| Repositorio | Tipo | Descripción | Stack / Protocolo |
| :--- | :--- | :--- | :--- |
| *Ejemplo: CodeCompanion* | Skill | Generación de tests unitarios y flujos GitHub Actions | TypeScript, Git CLI |

### 1.3. Investigación, RAG & Recuperación de Información
> Agentes de búsqueda profunda (Deep Research), síntesis de fuentes académicas o corporativas y motores RAG.

| Repositorio | Tipo | Descripción | Stack / Protocolo |
| :--- | :--- | :--- | :--- |
| *Ejemplo: AcademicSearch* | Agente | Extracción y síntesis de literatura científica | Python, ArXiv API |

### 1.4. Automatización & Productividad
> Tareas recurrentes, interacción con navegador/sistema operativo, gestión de agendas y notas.

| Repositorio | Tipo | Descripción | Stack / Protocolo |
| :--- | :--- | :--- | :--- |
| *Ejemplo: BrowserOps* | Skill | Automatización de flujos de navegación headless | Node.js, Playwright |

### 1.5. Datos, Analytics & Business Intelligence
> Análisis exploratorio de datos, generación de dashboards, consultas SQL y predicciones.

| Repositorio | Tipo | Descripción | Stack / Protocolo |
| :--- | :--- | :--- | :--- |
| *Ejemplo: DataAnalystBot* | Agente | Consulta de bases de datos y visualización con Seaborn | Python, SQL, DuckDB |

---

## 🧩 2. Clasificación por Orientación Técnica

### 2.1. Frameworks de Orquestación Multi-Agente
> Arquitecturas para coordinar flotas de agentes distribuidos y especializados.

- **CrewAI**: Orquestación de agentes con roles definidos y trabajo colaborativo.
- **AutoGen**: Framework conversacional y multi-agente personalizable.
- **LangGraph**: Modelado de agentes mediante grafos de estados y ciclos.

### 2.2. Protocolos & Ecosistemas (MCP, Tools & Skills)
> Estándares de interoperabilidad, servidores de contexto y librerías de habilidades.

- **Model Context Protocol (MCP)**: Estándar abierto para conectar modelos de lenguaje con herramientas y fuentes de contexto.
- **Antigravity Skills Ecosystem**: Paquetes de instrucciones especializadas y workflows para entornos agentic.

### 2.3. Agentes Autónomos / Goal-Driven
> Agentes orientados a objetivos con bucles de autoevaluación, planificación y corrección de errores.

---

## 🏢 3. Clasificación por Sector Industrial

### 3.1. Financiero & Fintech
- Detección de fraude, análisis crediticio y procesamiento de facturas/recibos.

### 3.2. Salud & Biotecnología
- Triage clínico experimental, análisis de historiales anonimizados y asistencia bibliográfica médica.

### 3.3. Legal & Compliance
- Revisión de contratos, análisis de términos y condiciones (ToS) y auditoría de normativas (GDPR/RGPD).

### 3.4. E-Commerce & Retail
- Agentes de atención al cliente, pricing dinámico y asistentes de recomendación de compra.

---

## 📝 Plantilla para Nuevas Entradas

Para sugerir un nuevo repositorio, por favor usa el siguiente formato:

```markdown
### [Nombre del Repositorio](URL)
- **Tipo**: [Skill | Agente | Multi-Agente | MCP Server | Framework]
- **Temática**: [Ciberseguridad | DevOps | RAG | ...]
- **Orientación**: [Autónomo | Asistido | Herramienta/Protocolo]
- **Sector**: [Transversal | Fintech | Salud | Legal | ...]
- **Descripción**: Breve descripción del proyecto y sus capacidades principales.
```

---

## 🤝 Contribución

1. Haz un fork del repositorio.
2. Crea una rama con tu propuesta (`git checkout -b feature/nuevo-repo`).
3. Añade la entrada en la sección correspondiente respetando la plantilla.
4. Realiza un commit con un mensaje descriptivo.
5. Abre un Pull Request.
