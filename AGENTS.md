# AGENTS.md

## Objetivo del proyecto

Este repositorio toma un notebook académico de cinemática de un robot MELFA de 6 GDL y lo convierte progresivamente en un proyecto modular, reusable y verificable.

## Reglas de trabajo

- Mantener cambios pequeños y revisables.
- No refactorizar todo el proyecto de una vez.
- No modificar funciones matemáticas sin explicación clara.
- Priorizar modularización incremental.
- Mantener compatibilidad con el notebook original cuando sea posible.
- Agregar pruebas mínimas antes de cambios grandes.
- Evitar dependencias innecesarias.
- No mover múltiples módulos en una sola tarea.

## Estructura actual

- notebooks/: material original y exploración
- src/: código reusable
- tests/: pruebas mínimas
- docs/: documentación del caso de estudio
