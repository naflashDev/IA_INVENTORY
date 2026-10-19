# Directrices de Proyecto - CLAUDE.md

## Visión General del Proyecto
- **Nombre**: [Nombre del Proyecto]
- **Descripción**: [Resumen de 1-2 párrafos del propósito y arquitectura principal]
- **Stack Tecnológico**: [ej: Python 3.11, FastAPI, React 18, TypeScript, Docker]

## Comandos de Uso Frecuente
- **Instalación de dependencias**: `npm install` o `poetry install`
- **Compilación / Build**: `npm run build`
- **Servidor de Desarrollo**: `npm run dev` o `uvicorn app.main:app --reload`
- **Ejecutar Pruebas**: `pytest -v` o `npm test`
- **Linter y Formato**: `ruff check . --fix` o `npm run lint`

## Convenciones de Código y Arquitectura
- **Estructura de Directorios**:
  - `src/core/`: Lógica central desacoplada.
  - `src/services/`: Capas de integración y servicios de terceros.
  - `tests/`: Pruebas unitarias e integración espejadas con `src/`.
- **Estilo**:
  - Nombres descriptivos para funciones y variables.
  - Manejo explícito de excepciones; no silenciar errores sin registrar logs.
  - Documentación de funciones públicas y tipos explícitos (Type Hints / TypeScript interfaces).

## Reglas de Comportamiento para el Asistente
1. Nunca realices commits directos a `main` ni push sin autorización.
2. Realiza cambios incrementales y verifica las pruebas antes de dar por cerrada una tarea.
3. Si un comando falla, analiza la causa raíz antes de reintentar a ciegas.
