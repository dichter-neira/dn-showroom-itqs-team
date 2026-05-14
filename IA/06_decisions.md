# 06 — Decisiones Arquitectónicas (ADRs)

> **Última actualización:** 2026-05-14

## ADR-01: Uso de `IA/` como fuente de verdad para agentes
**Decisión:** El directorio `IA/` será el repositorio de contexto estructurado para agentes de IA.
**Razón:** Permite estandarizar el inicio de sesión y garantizar que los agentes lean un conjunto común de archivos con esquemas definidos.
**Alternativas descartadas:** Mantener el archivo `IA` como texto libre, lo que no sería compatible con agentes estructurados ni con el esquema definido.
