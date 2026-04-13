# Methodology

Last checked: `2026-04-13`

This repository aims to be useful without pretending to know more than the public evidence supports.

## Status Labels

- `Verified`
  - Directly supported by a public source reviewed for this repository.
- `Likely`
  - Repeated across credible public aggregators or strongly implied by available evidence, but not directly re-validated here.
- `Rumor`
  - Publicly circulated but not sufficiently supported.
- `Outdated`
  - Once plausible, but contradicted by the current reviewed evidence.

## Confidence Labels

- `high`
  - Direct source support and low ambiguity.
- `medium`
  - Good signal, but some dependency on interpretation or second-order aggregation.
- `low`
  - Weakly supported or highly unstable.

## Source Weighting

1. **Artificial Analysis leaderboard pages**
   - Highest weight for current public benchmark claims.

2. **X / Reddit primary-source discussion**
   - Useful for tracing amplification, skepticism, and attribution narratives.

3. **Public product-facing surfaces**
   - Useful for current positioning, language, and user-facing access cues.

## Update Rules

- Every page shows a `Last checked` date.
- Snapshot claims must include the date context.
- Other Happy Horse domains may be discussed as text when needed for analysis, but are not surfaced as trusted reader-facing destination links by default.
- Failure cases remain in scope because they prevent false confidence.

## Correction Rules

- If a stronger source contradicts an existing claim, the claim should be downgraded or marked `Outdated`.
- If a community claim is later supported directly by an official source, it can be upgraded.
- Status changes should be reflected in both Markdown and JSON files.
