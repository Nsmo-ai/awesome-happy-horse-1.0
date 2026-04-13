# Claims Ledger

Last checked: `2026-04-13`

This page tracks the main public claims around Happy Horse with explicit status and confidence labels.

## Release and Access Claims

| Claim | Status | Confidence | Source | Last checked | Note |
| --- | --- | --- | --- | --- | --- |
| A public GitHub repository for Happy Horse exists. | `Verified` | `high` | [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) | `2026-04-13` | Directly observable. |
| The current official public repo includes model weights. | `Outdated` | `high` | [Repo contents API](https://api.github.com/repos/happyhorseai/happyhorse/contents) | `2026-04-13` | Current public repo does not expose weights. |
| The current official public repo includes inference code. | `Outdated` | `high` | [Repo contents API](https://api.github.com/repos/happyhorseai/happyhorse/contents) | `2026-04-13` | Current public repo is README-only. |
| The current official public README references the domain `happyhorse.app`. | `Verified` | `high` | [Official public README](https://raw.githubusercontent.com/happyhorseai/happyhorse/main/README.md) | `2026-04-13` | This repo records the reference but does not surface that domain as its canonical user-facing link. |
| This repository uses `tryhappyhorse.com` as its canonical surfaced Happy Horse website link. | `Verified` | `high` | [Methodology](./methodology.md), [Official Links and Fakes](./official-links-and-fakes.md) | `2026-04-13` | Editorial standard for reader-facing consistency. |
| Happy Horse is already released as open weights. | `Rumor` | `medium` | [brooks376 README](https://github.com/brooks376/Happy-Horse-1.0) | `2026-04-13` | Community repos discuss this, but the official public repo does not support it. |

## Product Positioning Claims

| Claim | Status | Confidence | Source | Last checked | Note |
| --- | --- | --- | --- | --- | --- |
| HappyHorse AI is being marketed as text/image to `1080p cinematic video`. | `Verified` | `high` | [GitHub API snapshot](https://api.github.com/repos/happyhorseai/happyhorse) | `2026-04-13` | Taken from the public repo description. |
| The product uses `advanced motion synthesis`, `multi-shot storytelling`, and `seamless transitions`. | `Verified` | `high` | [GitHub API snapshot](https://api.github.com/repos/happyhorseai/happyhorse) | `2026-04-13` | Present in the repo description. |
| The official repo currently frames the product as free online with no sign up required. | `Verified` | `high` | [GitHub API snapshot](https://api.github.com/repos/happyhorseai/happyhorse) | `2026-04-13` | Public repo description statement. |
| HappyHorse is primarily presented as an engineering or research release. | `Outdated` | `high` | [Official public README](https://raw.githubusercontent.com/happyhorseai/happyhorse/main/README.md) | `2026-04-13` | Current public README is marketing-led, not research-led. |

## Benchmark and Comparison Claims

| Claim | Status | Confidence | Source | Last checked | Note |
| --- | --- | --- | --- | --- | --- |
| As checked on `2026-04-13`, Artificial Analysis lists HappyHorse-1.0 as the leader for Text to Video without audio at `Elo 1384`. | `Verified` | `high` | [Artificial Analysis Text to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/text-to-video) | `2026-04-13` | Snapshot claim; values and rank may change. |
| As checked on `2026-04-13`, Artificial Analysis FAQ text lists HappyHorse-1.0 as the leader for Text to Video with audio at `Elo 1236`. | `Verified` | `high` | [Artificial Analysis Text to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/text-to-video) | `2026-04-13` | Captured from the public FAQ block. |
| As checked on `2026-04-13`, Artificial Analysis lists HappyHorse-1.0 as the leader for Image to Video without audio at `Elo 1413`. | `Verified` | `high` | [Artificial Analysis Image to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/image-to-video) | `2026-04-13` | Snapshot claim; values and rank may change. |
| As checked on `2026-04-13`, Artificial Analysis FAQ text lists HappyHorse-1.0 as `#2` for Image to Video with audio at `Elo 1162`, behind Dreamina Seedance 2.0 720p at `Elo 1166`. | `Verified` | `high` | [Artificial Analysis Image to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/image-to-video) | `2026-04-13` | Important nuance that prevents over-compressed benchmark claims. |
| `Happy Horse vs Seedance` is the dominant community comparison frame. | `Likely` | `medium` | [ZeroLu README](https://github.com/ZeroLu/awesome-happy-horse), [EvoLinkAI README](https://github.com/EvoLinkAI/happyhorse-1.0) | `2026-04-13` | Strong community signal, not a controlled benchmark by this repo. |
| Community comparisons contain mislabeled or disputed clips. | `Likely` | `medium` | [robert-2-j README](https://github.com/robert-2-j/HappyHorse-1.0), [EvoLinkAI README](https://github.com/EvoLinkAI/happyhorse-1.0) | `2026-04-13` | Included here to prevent overconfidence. |

## Identity and Source Claims

| Claim | Status | Confidence | Source | Last checked | Note |
| --- | --- | --- | --- | --- | --- |
| The current GitHub competition around Happy Horse is mostly SEO/content repositories rather than code repositories. | `Verified` | `high` | [brooks376 README](https://github.com/brooks376/Happy-Horse-1.0), [robert-2-j README](https://github.com/robert-2-j/HappyHorse-1.0), [ZeroLu README](https://github.com/ZeroLu/awesome-happy-horse), [EvoLinkAI README](https://github.com/EvoLinkAI/happyhorse-1.0) | `2026-04-13` | Directly observable from repo structures and README focus. |
| Community repos should be treated as evidence aggregators, not primary product sources. | `Verified` | `high` | Same sources as above | `2026-04-13` | Important for source hierarchy. |
