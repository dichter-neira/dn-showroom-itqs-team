# 01 — Requisitos del Sistema

> **Última actualización:** 2026-05-14
> **Fuentes:** `README.md`, estructura del repositorio

## Propósito del sistema
Proveer un conjunto de archivos estructurados dentro de `IA/` que sirvan de guía para agentes de IA y equipo humano en el desarrollo, documentación y mantenimiento del proyecto.

## Reglas fundamentales de negocio
- El contenido en `IA/` es la fuente de verdad para agentes de IA.
- `00_context.md` debe leerse siempre al inicio de la sesión.
- Si un archivo en `IA/` está vacío o desactualizado, el agente debe recrearlo según el esquema de este README.
- No se deben borrar los registros históricos de ADRs, tareas completadas ni issues conocidos.

## Flujos principales
### Flujo de inicialización de sesión
**Estado de entrada:** Repositorio clonado y agente listo.
**Estado de salida:** Archivos `IA/*` validados o regenerados.
1. Leer `IA/00_context.md`.
2. Confirmar que `IA/01_requirements.md` refleja el propósito del proyecto.
3. Verificar `IA/02_architecture.md` contra la estructura actual del repositorio.
4. Revisar `IA/03_plan.md` y `IA/04_tasks.md` antes de comenzar código.

### Flujo de creación de tareas
**Estado de entrada:** Se va a implementar una nueva funcionalidad o cambio.
**Estado de salida:** Tarea documentada en `IA/04_tasks.md`.
1. Definir el alcance de la tarea.
2. Crear una entrada en `IA/04_tasks.md` con pasos concretos.
3. Establecer `Expected Output` verificable.
4. Marcar dependencias si aplica.
