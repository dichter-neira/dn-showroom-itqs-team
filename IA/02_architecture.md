# 02 — Arquitectura del Sistema

> **Última actualización:** 2026-05-14
> **Scope:** dn-showroom-itqs-team

## Pipeline principal
```
[Usuario/Agente] --> Lee IA/00_context.md --> Revisa IA/01_requirements.md
                  --> Valida IA/02_architecture.md --> Planifica en IA/03_plan.md
                  --> Crea tareas en IA/04_tasks.md --> Actualiza progreso en IA/05_progress.md
```

## Componentes clave
| Componente | Responsabilidad | Archivo |
|-----------|-----------------|---------|
| Contexto del proyecto | Documentar identidad y límites del proyecto | `IA/00_context.md` |
| Requisitos | Definir qué debe hacer el sistema | `IA/01_requirements.md` |
| Arquitectura | Describir cómo está construido | `IA/02_architecture.md` |
| Plan | Organizar fases de desarrollo | `IA/03_plan.md` |
| Tareas | Listar trabajos accionables | `IA/04_tasks.md` |
| Progreso | Registrar estado del desarrollo | `IA/05_progress.md` |
| Decisiones | Guardar ADRs históricos | `IA/06_decisions.md` |
| Issues | Documentar bugs y limitaciones | `IA/07_issues.md` |
| Retrospectiva | Aprendizajes y mejoras | `IA/08_retrospective.md` |

## Contratos de interfaces críticas
- `IA/00_context.md` debe contener la identidad del proyecto y el scope.
- `IA/01_requirements.md` debe contener las reglas del sistema y flujos principales.
- `IA/04_tasks.md` debe documentar tareas con pasos y salida esperada verificable.
