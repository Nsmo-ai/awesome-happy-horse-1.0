# Awesome Happy Horse

[English](README.md) | [Español](README.es.md) | [Português](README.pt.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | Français | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md) | [Русский](README.ru.md)

Un dépôt public de veille, de structure et de ressources autour de [Happy Horse AI](https://tryhappyhorse.com/). Son but n’est pas seulement d’agréger des liens, mais d’aider à distinguer :

- ce qui peut être vérifié publiquement maintenant,
- ce qui reste probable mais non confirmé,
- ce qui relève encore du rumor,
- et ce qui circule vite sans devoir être répété comme un fait.

## Pourquoi ce dépôt est utile

[Happy Horse 1.0](https://tryhappyhorse.com/) est devenu visible parce que deux dynamiques se sont renforcées en même temps :

- une dynamique produit, avec une narration très orientée vidéo “cinematic”
- une dynamique benchmark, avec une forte visibilité dans des classements publics

Quand ces deux couches explosent ensemble, la demande d’explication devient plus rapide que la clarté officielle.

## Ce qui s’est passé jusqu’ici

1. `2026-04-08`
   - Le dépôt public [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) apparaît sur GitHub.
   - Le README public ressemble d’abord à une page de positionnement produit plutôt qu’à un release technique.

2. `2026-04-08` à `2026-04-09`
   - Des dépôts communautaires étendent rapidement le sujet vers les prompts, les benchmarks, le rumor tracking et les cartes de sources.

3. `2026-04-13`
   - Les pages publiques de benchmark montrent [Happy Horse 1.0](https://tryhappyhorse.com/) très haut dans plusieurs catégories.
   - En parallèle, le dépôt GitHub public officiel n’expose toujours ni poids ni code d’inférence.

## État actuel

- **[Verified]** Le dépôt public [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) existe.
- **[Verified]** La description publique le présente comme un produit centré sur `1080p cinematic video` et `advanced motion synthesis`.
- **[Verified]** Le README public actuel reste marketing, pas technique.
- **[Verified]** Au `2026-04-13`, HappyHorse-1.0 mène `Text to Video (No Audio)` et `Image to Video (No Audio)` dans les pages publiques revues ici.
- **[Verified]** Il apparaît aussi en tête de `Text to Video (With Audio)`.
- **[Verified]** En `Image to Video (With Audio)`, Seedance reste devant et HappyHorse-1.0 est second.
- **[Rumor]** Rien ne confirme publiquement, au niveau du dépôt officiel, que des open weights soient déjà publiés.

## Navigation rapide

| Section | Document | Utilité principale |
| --- | --- | --- |
| Base factuelle | [Verified Facts](./docs/verified-facts.md) | Lire uniquement les faits directement soutenables |
| Registre des claims | [Claims Ledger](./docs/claims-ledger.md) | Voir l’état, la confiance et les sources de chaque claim |
| Chronologie | [Timeline](./docs/timeline.md) | Comprendre comment le sujet a pris de l’ampleur |
| Snapshot benchmark | [Benchmarks](./docs/benchmarks.md) | Lire Elo, rang et samples avec date |
| Carte des signaux | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | Comprendre la relation entre benchmark, repo officiel, communauté et claims de sites |
| Lecture comparative | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | Interpréter le principal head-to-head |
| Cas de prompt | [Prompt Library](./docs/prompts/prompt-library.md) | Savoir quoi tester |
| Cas d’échec | [Failure Cases](./docs/prompts/failure-cases.md) | Repérer les zones de mauvaise interprétation |

## FAQ

### Qu’est-ce que Happy Horse ?

Sur la base de la description publique actuelle, [Happy Horse AI](https://tryhappyhorse.com/) est présenté comme un produit text-to-video et image-to-video avec un positionnement fortement cinématographique.

### Happy Horse est-il open source ?

Le dépôt public actuel ne montre ni poids publiés ni code d’inférence. Voir [Claims Ledger](./docs/claims-ledger.md).

### Peut-on faire tourner Happy Horse en local ?

Avec les informations publiques actuelles, cela ne peut pas être affirmé. Aucun paquet public d’exécution locale n’est visible.

### Où en est-il dans les benchmarks ?

Au `2026-04-13`, [Happy Horse 1.0](https://tryhappyhorse.com/) est très haut dans plusieurs catégories publiques d’Artificial Analysis. Ces données doivent être lues comme des snapshots datés. Voir [Benchmarks](./docs/benchmarks.md).

### Est-il meilleur que Seedance ?

La réponse la plus sûre n’est pas binaire. [Happy Horse 1.0](https://tryhappyhorse.com/) mène plusieurs catégories, mais Seedance reste devant en `Image to Video (With Audio)`. Voir [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md).

### Quel site faut-il utiliser ?

Ce dépôt normalise l’entrée utilisateur vers [Happy Horse](https://tryhappyhorse.com/). Les autres domaines ne sont traités que comme contexte analytique.

## Note multilingue

Ce dépôt propose maintenant des README en anglais, chinois simplifié, japonais, coréen, espagnol, portugais, allemand, français, turc, chinois traditionnel et russe. Les documents de preuve plus profonds restent maintenus principalement en anglais.
