# Spec-Kit Project Constitution

## Core Principles

### I. Inviolable Technology Stack
El proyecto debe utilizar estrictamente las siguientes tecnologías. No se permiten desviaciones sin una enmienda formal a esta constitución:
- **Lenguaje:** TypeScript (Strict Mode).
- **Framework Backend:** Next.js (App Router / API Routes).
- **Arquitectura:** Arquitectura Hexagonal (Puertos y Adaptadores).

### II. Hexagonal Architecture
Toda la lógica de negocio debe estar aislada de las dependencias externas (bases de datos, frameworks, APIs de terceros).
- **Domain:** Contiene las entidades y reglas de negocio puras.
- **Application:** Contiene los casos de uso y las interfaces de los puertos.
- **Infrastructure:** Contiene las implementaciones de los adaptadores (Next.js, DB, etc.).

### III. Type Safety
El uso de TypeScript es obligatorio en todo el proyecto. Se debe evitar el uso de `any` y priorizar la definición de interfaces y tipos robustos para garantizar la integridad de los datos.

## Additional Constraints

### Quality Gates
- Todo nuevo desarrollo debe seguir la metodología SDD (Spec-Driven Development).
- Las especificaciones deben ser aprobadas antes de iniciar el diseño técnico o la implementación.

## Governance
Esta constitución es inviolable y prevalece sobre cualquier otra práctica de desarrollo. Cualquier cambio requiere una revisión y aprobación formal.

**Version**: 1.0.0 | **Ratified**: 2024-05-22 | **Last Amended**: 2024-05-22
