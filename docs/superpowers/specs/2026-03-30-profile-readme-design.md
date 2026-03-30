# OpenHacienda GitHub Profile README — Design Spec

## Overview

Redesign the `.github/profile/README.md` to be an expanded, bilingual (Spanish-first) organization profile inspired by [legalize-dev/legalize](https://github.com/legalize-dev/legalize).

## Structure

Full duplication: Spanish block first, horizontal rule, English block with the same structure translated.

### Sections (per language block)

1. **Heading** — `## OpenHacienda`
2. **Tagline**
   - ES: "Las herramientas que la administración digital debería ofrecer, pero no ofrece."
   - EN: "The tools digital government should offer, but doesn't."
3. **Project table** — three columns: Project/Proyecto, Description/Descripción, Status/Estado

   | Project | Description (ES) | Description (EN) | Status |
   |---------|-------------------|-------------------|--------|
   | llave | Implementación open-source de Cl@ve PIN / Cl@ve Móvil | Open-source implementation of Spain's Cl@ve PIN / Cl@ve Móvil | En desarrollo / In development |
   | puntoBOE | Validador de ficheros BOE — 100% en el navegador | Browser-based BOE tax filing validator — runs entirely in WebAssembly | En desarrollo / In development |
   | website | Documentación y página del proyecto | Project documentation and landing page | En desarrollo / In development |

4. **"Why" section** (Por qué / Why) — Two paragraphs:
   - Paragraph 1: "Firmar con certificado digital, autenticarse con Cl@ve, validar ficheros tributarios — todo esto debería ser sencillo. En la práctica, la documentación es ininteligible y obsoleta, las herramientas son opacas, y los desarrolladores acaban descifrando PDFs de diseños de registro. OpenHacienda construye alternativas abiertas para que no tengas que hacerlo tú solo."
   - Paragraph 2: "La administración digital es un servicio público. Sus herramientas, formatos y protocolos deberían ser abiertos, documentados y auditables. Cuando no lo son, es responsabilidad de los ciudadanos exigirlo — y de proyectos como este demostrarlo."
   - English translations of both paragraphs.

5. **"Contributing" section** (Contribuir / Contributing)
   - ES: "Las contribuciones son bienvenidas. Abre un issue para reportar errores o proponer mejoras, o envía un PR directamente."
   - EN: equivalent translation.

6. **"Support" section** (Apóyanos / Support)
   - Content: TBW (placeholder in both languages)

### Excluded sections

- License (each project has its own)
- "How it works" with code examples (projects too diverse)

## File

`profile/README.md` in the `.github` repository.

## Bilingual approach

Full duplication separated by a horizontal rule (`---`). Spanish first, English second.
