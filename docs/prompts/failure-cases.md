# Failure Cases

Last checked: `2026-04-13`

Trust comes from keeping misleading or weak evidence visible.

## 1. “Official” link inflation

- **Problem:** Community repos may surface domains or try-it pages that feel official but are not directly supported by the current public repo state reviewed here.
- **Why it matters:** Readers may confuse a keyword-optimized landing page with a confirmed product entry point.
- **Current handling:** This repository uses one canonical surfaced site link, [tryhappyhorse.com](https://tryhappyhorse.com/), and keeps other domains in caution context only.
- **Related page:** [Official Links and Fakes](../official-links-and-fakes.md)

## 2. Open-source overclaiming

- **Problem:** Some community framing suggests or implies that model weights or full open-source release are already available.
- **Why it matters:** Users may waste time searching for code or weights that are not present in the current official public GitHub repo.
- **Current handling:** Any claim of currently available open weights is downgraded unless directly supported by the current official public repo.
- **Supporting source:** [brooks376/Happy-Horse-1.0](https://github.com/brooks376/Happy-Horse-1.0)

## 3. Comparison clip ambiguity

- **Problem:** Community comparison narratives can move faster than attribution clarity.
- **Why it matters:** A strong-looking clip does not prove the label, prompt, or benchmark framing is correct.
- **Current handling:** Comparison pages in this repo keep an explicit uncertainty section and avoid absolute performance language.
- **Supporting sources:** [robert-2-j/HappyHorse-1.0](https://github.com/robert-2-j/HappyHorse-1.0), [EvoLinkAI/happyhorse-1.0](https://github.com/EvoLinkAI/happyhorse-1.0)

## 4. README-only authority bias

- **Problem:** A polished README can feel like a product truth source even when it is only a marketing page.
- **Why it matters:** Readers may assume missing code is hidden rather than absent.
- **Current handling:** This repo separates `marketing claims` from `release artifacts`.
- **Supporting source:** [Official public README](https://raw.githubusercontent.com/happyhorseai/happyhorse/main/README.md)

## 5. Undated leaderboard quoting

- **Problem:** People often repeat leaderboard positions without a date, as if the ranking were stable.
- **Why it matters:** Elo-based leaderboards can shift as more votes come in, so stale numbers travel quickly.
- **Current handling:** This repo records `Last checked` dates and treats benchmark values as snapshots.
- **Supporting sources:** [Artificial Analysis Text to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/text-to-video), [Artificial Analysis Image to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/image-to-video)

## 6. “Leads everything” compression

- **Problem:** Summary posts can collapse nuanced benchmark results into a blanket statement that Happy Horse wins every category.
- **Why it matters:** That hides important nuance. As checked on `2026-04-13`, HappyHorse-1.0 leads the no-audio leaderboards and Text-to-Video with audio, but sits behind Seedance in Image-to-Video with audio.
- **Current handling:** This repo records benchmark wins and benchmark exceptions separately.
- **Supporting sources:** [Artificial Analysis Text to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/text-to-video), [Artificial Analysis Image to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/image-to-video)

## 7. Prompt success bias

- **Problem:** Public prompt collections often show only striking wins and hide prompts that expose weak continuity, identity drift, or awkward lip movement.
- **Why it matters:** Readers may overestimate model consistency if they only see “winner” clips.
- **Current handling:** This repo keeps prompt cases tied to specific stress goals such as identity retention, direct-to-camera speech, and multi-beat continuity.
- **Related pages:** [Prompt Library](./prompt-library.md), [Happy Horse vs Seedance](../comparisons/happy-horse-vs-seedance.md)
