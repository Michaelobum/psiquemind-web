# PsiqueMind Web

Sitio web para PsiqueMind — consulta de neuropsicología de Londres Mora. Objetivo:
presencia digital que genere confianza y convierta visitas en consultas.

> **Estado**: fase de documentación y diseño. Todavía NO hay código fuente
> (`07_TECHNICAL.md` está vacío — el stack no se decidió). No inventes estructura
> de código: si una tarea requiere código y el stack no está definido, resolvé eso primero.

## Contexto obligatorio — leer antes de trabajar

El contexto del proyecto NO vive en este archivo, vive en `.agent/` y `docs/`.
Claude Code no los carga solo — leelos según la tarea:

| Archivo | Qué es | Cuándo leerlo |
|---------|--------|---------------|
| `.agent/AGENT.md` | Rol y flujo de trabajo (equipo multidisciplinario, orden de lectura) | Siempre, al empezar |
| `.agent/RULES.md` | Reglas inquebrantables (diseño, UX, copy, SEO, a11y, performance) | Siempre, al empezar |
| `.agent/DECISIONS.md` | Decisiones de diseño y negocio ya tomadas | Antes de proponer algo nuevo |
| `.agent/MEMORY.md` | Preferencias permanentes del dueño | Antes de proponer algo nuevo |
| `docs/00_PROJECT` → `10_CHECKLIST` | Negocio, marca, producto, UX, UI, copy, SEO, técnico, assets, tareas | El que corresponda a la tarea |

Orden de lectura canónico (definido en `AGENT.md`): PROJECT → BRAND → PRODUCT →
DECISIONS → MEMORY → TASKS → pensar → diseñar → desarrollar → revisar.

## Reglas de oro (resumen — el detalle está en `.agent/RULES.md`)

- Nada de templates ni interfaces genéricas; fotos reales sobre stock (hay fotos en `Fotos/`).
- Copy humano, empático, profesional — sin lenguaje comercial agresivo ni miedo.
- WCAG AA, HTML semántico, SEO completo (OG, Schema.org, sitemap, canonical).
- Calidad sobre velocidad: mejor rehacer que entregar mediocre.

## Convención de registro

- Decisiones nuevas → `.agent/DECISIONS.md`
- Preferencias del dueño → `.agent/MEMORY.md`
- Tareas → `docs/09_TASKS.md`

No dupliques nada de eso acá: este archivo es solo el índice de entrada.
