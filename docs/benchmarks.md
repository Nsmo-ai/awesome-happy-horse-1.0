# Benchmarks

Last checked: `2026-04-13`

This page records benchmark information that is directly visible in public sources reviewed for this repository. Every number here is a snapshot and should be treated as time-sensitive.

## Reading Guide

- `Verified` means the source page itself is directly visible and the wording or numbers are captured faithfully.
- `Likely` means the framing is repeated across public repos, but not independently re-run by this repository.
- Elo, rank, and sample counts can move as new votes arrive.

## Artificial Analysis Snapshot

Snapshot date used here: `2026-04-13`

### Text to Video

#### No Audio

| Rank | Model | Elo | Samples | Released | API status | Status | Source |
| --- | --- | ---: | ---: | --- | --- | --- | --- |
| 1 | HappyHorse-1.0 | 1384 | 13983 | Apr 2026 | Coming soon | `Verified` | [Artificial Analysis Text to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/text-to-video) |
| 2 | Dreamina Seedance 2.0 720p | 1273 | 4739 | Mar 2026 | No public API | `Verified` | Same source |
| 3 | SkyReels V4 | 1242 | 5246 | Mar 2026 | `$7.20 /min` | `Verified` | Same source |
| 4 | Kling 3.0 1080p (Pro) | 1240 | 5361 | Feb 2026 | `$13.44 /min` | `Verified` | Same source |
| 5 | Kling 3.0 Omni 1080p (Pro) | 1228 | 5962 | Feb 2026 | `$13.44 /min` | `Verified` | Same source |

#### With Audio

As checked on `2026-04-13`, the public FAQ section on the same page states:

- `#1` HappyHorse-1.0 at `Elo 1236`
- `#2` Dreamina Seedance 2.0 720p at `Elo 1224`
- `#3` SkyReels V4 at `Elo 1142`
- `#4` Kling 3.0 Omni 1080p (Pro) at `Elo 1107`
- `#5` Kling 3.0 1080p (Pro) at `Elo 1104`

Source: [Artificial Analysis Text to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/text-to-video)

### Image to Video

#### No Audio

| Rank | Model | Elo | Samples | Released | API status | Status | Source |
| --- | --- | ---: | ---: | --- | --- | --- | --- |
| 1 | HappyHorse-1.0 | 1413 | 14587 | Apr 2026 | Coming soon | `Verified` | [Artificial Analysis Image to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/image-to-video) |
| 2 | Dreamina Seedance 2.0 720p | 1357 | 4675 | Mar 2026 | No public API | `Verified` | Same source |
| 3 | grok-imagine-video | 1331 | 6515 | Jan 2026 | `$4.20 /min` | `Verified` | Same source |
| 4 | PixVerse V6 | 1308 | 15003 | Mar 2026 | `$5.40 /min` | `Verified` | Same source |
| 5 | Kling 3.0 Omni 1080p (Pro) | 1298 | 4920 | Feb 2026 | `$13.44 /min` | `Verified` | Same source |

#### With Audio

As checked on `2026-04-13`, the public FAQ section on the same page states:

- `#1` Dreamina Seedance 2.0 720p at `Elo 1166`
- `#2` HappyHorse-1.0 at `Elo 1162`
- `#3` SkyReels V4 at `Elo 1086`
- `#4` Veo 3.1 Fast at `Elo 1079`
- `#5` Veo 3.1 at `Elo 1076`

Source: [Artificial Analysis Image to Video leaderboard](https://artificialanalysis.ai/video/leaderboard/image-to-video)

## Time-Sensitive Notes

- The leaderboard pages show `HappyHorse-1.0` as added within the last month.
- The `Coming soon` API status shown for HappyHorse-1.0 is a page snapshot, not a promise made by this repository.
- The strongest low-noise benchmark statements are currently:
  - HappyHorse-1.0 leads `Text to Video (No Audio)`
  - HappyHorse-1.0 leads `Image to Video (No Audio)`
  - HappyHorse-1.0 leads `Text to Video (With Audio)`
  - Seedance leads `Image to Video (With Audio)` with HappyHorse-1.0 in second

## Community Reading Layer

Beyond the live leaderboard pages, the reviewed GitHub ecosystem adds a second interpretation layer:

- `Happy Horse vs Seedance` is still the dominant comparison frame.
- `Kling` and `PixVerse` remain important secondary anchors because they are widely recognized and frequently cited.
- Community repos are useful for narrative context, but weaker than direct leaderboard snapshots for time-sensitive numbers.

## Practical Use

Use this page when you need a dated benchmark snapshot with enough detail to cite carefully. If you need a live conclusion, always re-check the linked leaderboard pages before repeating any rank or Elo value elsewhere.
