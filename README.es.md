# Awesome Happy Horse

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | Español | [Português](README.pt.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [Русский](README.ru.md)

Repositorio público de inteligencia y recursos sobre [Happy Horse AI](https://tryhappyhorse.com/). No intenta solo acumular enlaces: intenta separar con claridad hechos, señales, rumores y riesgos de interpretación.

## Por qué este repositorio importa

[Happy Horse 1.0](https://tryhappyhorse.com/) se volvió visible porque dos narrativas explotaron al mismo tiempo:

- la narrativa de producto: video generation con posicionamiento cinematográfico
- la narrativa de benchmark: una presencia muy fuerte en rankings públicos

Cuando eso ocurre, las preguntas llegan antes que la claridad oficial:

- ¿Está ya open source?
- ¿Se puede correr localmente?
- ¿Tiene API?
- ¿Es realmente mejor que Seedance?
- ¿Qué sitio conviene abrir?

Este repositorio existe para responder esas preguntas con más estructura.

## Qué ha pasado hasta ahora

1. `2026-04-08`
   - Aparece el repositorio público [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) en GitHub.
   - El README público se presenta como una página de producto, no como un release técnico.

2. `2026-04-08` a `2026-04-09`
   - Repositorios comunitarios amplían el tema en varias direcciones: prompts, benchmarks, rumor tracking y source mapping.

3. `2026-04-13`
   - Las páginas públicas de benchmark muestran a [Happy Horse 1.0](https://tryhappyhorse.com/) en posiciones muy fuertes en varias categorías.
   - A la vez, el repositorio oficial público sigue sin exponer pesos ni código de inferencia.

## Estado actual

- **[Verified]** Existe un repositorio público llamado [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse).
- **[Verified]** La descripción pública lo presenta como un producto de `1080p cinematic video` con `advanced motion synthesis`.
- **[Verified]** El README público actual es más una página de marketing que una publicación técnica.
- **[Verified]** A fecha de `2026-04-13`, HappyHorse-1.0 lidera `Text to Video (No Audio)` y `Image to Video (No Audio)` en las páginas públicas revisadas aquí.
- **[Verified]** A fecha de `2026-04-13`, también aparece líder en `Text to Video (With Audio)`.
- **[Verified]** En `Image to Video (With Audio)`, Seedance sigue por delante y HappyHorse-1.0 queda segundo.
- **[Rumor]** No hay evidencia oficial pública de que ya existan open weights publicados.

## Navegación rápida

| Sección | Documento | Uso principal |
| --- | --- | --- |
| Base factual | [Verified Facts](./docs/verified-facts.md) | Leer solo hechos directamente sostenibles |
| Registro de claims | [Claims Ledger](./docs/claims-ledger.md) | Ver estados, confianza y fuentes |
| Línea temporal | [Timeline](./docs/timeline.md) | Entender cómo creció el tema |
| Snapshot de benchmark | [Benchmarks](./docs/benchmarks.md) | Consultar Elo, rank y samples con fecha |
| Mapa de señales | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | Entender la relación entre benchmark, repo oficial, comunidad y claims de sitio |
| Lectura comparativa | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | Interpretar el principal head-to-head |
| Casos de prompt | [Prompt Library](./docs/prompts/prompt-library.md) | Saber qué probar |
| Casos de fallo | [Failure Cases](./docs/prompts/failure-cases.md) | Detectar dónde es más fácil equivocarse |

## FAQ

### ¿Qué es Happy Horse?

Según la descripción pública actual, [Happy Horse AI](https://tryhappyhorse.com/) se presenta como un producto de text-to-video e image-to-video con una narrativa centrada en resultados cinematográficos.

### ¿Happy Horse es open source?

No hay evidencia en el repositorio público actual de publicación de pesos ni de código de inferencia. Consulta [Claims Ledger](./docs/claims-ledger.md).

### ¿Se puede ejecutar Happy Horse localmente?

Con la información pública actual, no puede afirmarse eso. No aparece un paquete público para ejecución local.

### ¿Cuál es su situación en benchmarks?

A fecha de `2026-04-13`, [Happy Horse 1.0](https://tryhappyhorse.com/) está muy arriba en varias categorías públicas de Artificial Analysis. Esos datos deben leerse como snapshots fechados. Consulta [Benchmarks](./docs/benchmarks.md).

### ¿Es mejor que Seedance?

La respuesta segura no es binaria. [Happy Horse 1.0](https://tryhappyhorse.com/) lidera varias categorías, pero Seedance sigue liderando `Image to Video (With Audio)`. Consulta [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md).

### ¿Qué sitio debo usar?

Este repositorio unifica el enlace principal orientado a usuarios hacia [Happy Horse](https://tryhappyhorse.com/). Los demás dominios se tratan como contexto analítico.

## Nota multilingüe

Este repositorio ya ofrece README en inglés, chino simplificado, japonés, coreano, español, portugués, alemán, francés, turco, chino tradicional y ruso. Los documentos de evidencia profunda siguen manteniéndose principalmente en inglés.
