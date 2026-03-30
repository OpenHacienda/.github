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
3. **Project table** — three columns per language block:

   **Spanish block:**

   | Proyecto | Descripción | Estado |
   |----------|-------------|--------|
   | llave | Implementación open-source de Cl@ve PIN / Cl@ve Móvil | En desarrollo |
   | puntoBOE | Validador de ficheros BOE — 100% en el navegador | En desarrollo |
   | website | Documentación y página del proyecto | En desarrollo |

   **English block:**

   | Project | Description | Status |
   |---------|-------------|--------|
   | llave | Open-source implementation of Spain's Cl@ve PIN / Cl@ve Móvil | In development |
   | puntoBOE | Browser-based BOE tax filing validator — runs entirely in WebAssembly | In development |
   | website | Project documentation and landing page | In development |

4. **"Why" section** — Two paragraphs per language block:

   **Spanish (Por qué):**
   - "Firmar con certificado digital, autenticarse con Cl@ve, validar ficheros tributarios — todo esto debería ser sencillo. En la práctica, la documentación es ininteligible y obsoleta, las herramientas son opacas, y los desarrolladores acaban descifrando PDFs de diseños de registro. OpenHacienda construye alternativas abiertas para que no tengas que hacerlo tú solo."
   - "La administración digital es un servicio público. Sus herramientas, formatos y protocolos deberían ser abiertos, documentados y auditables. Cuando no lo son, es responsabilidad de los ciudadanos exigirlo — y de proyectos como este demostrarlo."

   **English (Why):**
   - "Signing with digital certificates, authenticating with Cl@ve, validating tax filings — all of this should be straightforward. In practice, documentation is unintelligible and outdated, tools are opaque, and developers end up deciphering record-layout PDFs. OpenHacienda builds open alternatives so you don't have to figure it out alone."
   - "Digital administration is a public service. Its tools, formats, and protocols should be open, documented, and auditable. When they're not, it's on citizens to demand it — and on projects like this to prove it's possible."

5. **"Contributing" section**
   - ES: "Las contribuciones son bienvenidas. Abre un issue para reportar errores o proponer mejoras, o envía un PR directamente."
   - EN: "Contributions are welcome. Open an issue to report bugs or suggest improvements, or send a PR directly."

6. **"Support" section** (Apóyanos / Support)
   - Content: TBW (placeholder in both languages)

### Excluded sections

- License (each project has its own)
- "How it works" with code examples (projects too diverse)

## File

`profile/README.md` in the `.github` repository.

## Bilingual approach

Full duplication separated by a horizontal rule (`---`). Spanish first, English second.
