# 00 — Contexto del Proyecto

> **Última actualización:** 2026-05-14
> **Scope:** /home/dbenjumea/repo/dn-showroom-itqs-team

## Identidad del proyecto
**Nombre:** dn-showroom-itqs
**Propósito:** Repositorio de capacitación técnica y recursos de aprendizaje para el proveedor de servicios de consultoría ITQS, con enfoque en GitHub Copilot y buenas prácticas de desarrollo.
**Cliente:** ITQS / Dichter & Neira (contexto de formación técnica)

## Stack tecnológico
| Capa | Tecnología |
|------|------------|
| Gestión del repositorio | GitHub |
| Documentación | Markdown |
| Agentes/IA | Archivos estructurados en `IA/` para LLMs |
| Frontend | No definido aún |
| Backend | No definido aún |

## Constantes críticas
- `IA/` es la fuente de verdad para agentes de IA.
- Cada archivo en `IA/` sigue un esquema fijo y debe crearse si está vacío o desactualizado.
- `00_context.md` debe leerse siempre al iniciar una sesión.
- No borrar histórico de ADRs ni tareas completadas.

## Estructura de carpetas clave
- `/` — Raíz del proyecto con `README.md` y el archivo `IA` convertido en carpeta.
- `IA/` — Contiene los archivos de contexto estructurado que los agentes deben usar:
  - `00_context.md`
  - `01_requirements.md`
  - `02_architecture.md`
  - `03_plan.md`
  - `04_tasks.md`
  - `05_progress.md`
  - `06_decisions.md`
  - `07_issues.md`
  - `08_retrospective.md`
