# Awesome Happy Horse

[English](README.md) | [Español](README.es.md) | [Português](README.pt.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md) | Русский

Публичный репозиторий с интеллектом, открытыми сигналами и переиспользуемыми ресурсами вокруг [Happy Horse AI](https://tryhappyhorse.com/). Его задача — не просто собрать ссылки, а помочь различать:

- что сейчас подтверждается напрямую,
- что выглядит вероятным, но ещё не окончательно подтверждено,
- что остаётся на уровне rumor,
- и что быстро распространяется, но не должно автоматически становиться “фактом”.

## Почему этот репозиторий важен

[Happy Horse 1.0](https://tryhappyhorse.com/) стал заметен потому, что одновременно выросли две разные линии внимания:

- продуктовая: сильное позиционирование вокруг cinematic video generation
- benchmark-линия: очень высокая видимость в публичных рейтингах

Из-за этого интерес растёт быстрее, чем официальная ясность.

## Что произошло к текущему моменту

1. `2026-04-08`
   - Публичный репозиторий [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) появился на GitHub.
   - Его публичный README выглядел как продуктовая страница, а не как технический релиз.

2. `2026-04-08` — `2026-04-09`
   - Сообщество быстро расширило тему через prompt-репозитории, benchmark-сводки, rumor tracking и карты источников.

3. `2026-04-13`
   - Публичные benchmark-страницы показывают [Happy Horse 1.0](https://tryhappyhorse.com/) очень высоко в нескольких категориях.
   - При этом официальный публичный GitHub-репозиторий по-прежнему не показывает веса или inference-код.

## Текущее состояние

- **[Verified]** Публичный репозиторий [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) существует.
- **[Verified]** Публичное описание подаёт Happy Horse AI как продукт с акцентом на `1080p cinematic video` и `advanced motion synthesis`.
- **[Verified]** Текущий README ориентирован скорее на маркетинг, чем на техническую публикацию.
- **[Verified]** По состоянию на `2026-04-13`, HappyHorse-1.0 лидирует в `Text to Video (No Audio)` и `Image to Video (No Audio)`.
- **[Verified]** В `Text to Video (With Audio)` он также находится в лидирующей позиции.
- **[Verified]** В `Image to Video (With Audio)` лидирует Seedance, а HappyHorse-1.0 занимает второе место.
- **[Rumor]** Нет официально поддержанной публичной базы для утверждения, что open weights уже опубликованы.

## Быстрая навигация

| Раздел | Документ | Основная польза |
| --- | --- | --- |
| Фактический слой | [Verified Facts](./docs/verified-facts.md) | Читать только прямо поддерживаемые факты |
| Реестр claims | [Claims Ledger](./docs/claims-ledger.md) | Видеть статус, доверие и источники каждого claim |
| Таймлайн | [Timeline](./docs/timeline.md) | Понять, как тема набрала скорость |
| Benchmark snapshot | [Benchmarks](./docs/benchmarks.md) | Смотреть Elo, rank и sample count с датой |
| Карта сигналов | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | Понимать связь между benchmark, официальным repo, сообществом и site claims |
| Сравнительное чтение | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | Читать главный head-to-head |
| Prompt-кейсы | [Prompt Library](./docs/prompts/prompt-library.md) | Понимать, что тестировать |
| Failure Cases | [Failure Cases](./docs/prompts/failure-cases.md) | Видеть, где проще всего ошибиться |

## FAQ

### Что такое Happy Horse?

Согласно текущему публичному описанию продукта, [Happy Horse AI](https://tryhappyhorse.com/) подаётся как text-to-video / image-to-video продукт с сильным cinematic-позиционированием.

### Happy Horse уже open source?

В текущем публичном GitHub-репозитории не видно опубликованных весов или inference-кода. См. [Claims Ledger](./docs/claims-ledger.md).

### Можно ли запускать Happy Horse локально?

По текущей публичной информации это нельзя подтвердить. Публичного локального пакета не видно.

### Как выглядит benchmark-картина?

На `2026-04-13` [Happy Horse 1.0](https://tryhappyhorse.com/) находится очень высоко в нескольких публичных категориях Artificial Analysis. Эти данные нужно читать как датированные snapshot-значения. См. [Benchmarks](./docs/benchmarks.md).

### Он лучше Seedance?

Самый безопасный ответ не бинарный. [Happy Horse 1.0](https://tryhappyhorse.com/) лидирует в нескольких категориях, но в `Image to Video (With Audio)` впереди остаётся Seedance. См. [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md).

### Какой сайт использовать?

Этот репозиторий унифицирует пользовательский входной URL как [Happy Horse](https://tryhappyhorse.com/). Остальные домены рассматриваются только как аналитический контекст.

## Многоязычное примечание

Репозиторий уже предлагает README на английском, упрощённом китайском, японском, корейском, испанском, португальском, немецком, французском, турецком, традиционном китайском и русском языках. Более глубокие доказательные документы пока поддерживаются в основном на английском.
