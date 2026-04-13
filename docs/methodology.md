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

1. **Official public repository and product links referenced by it**
   - Highest weight for current public product claims.

2. **Public GitHub API snapshots**
   - Highest weight for repository metadata and structure.

3. **Community GitHub intelligence repos**
   - Useful for mapping public narrative, but not treated as primary truth for product internals.

4. **Benchmark claims cited by community repos**
   - Useful for understanding public narrative momentum; lower weight unless independently re-checked.

## Update Rules

- Every page shows a `Last checked` date.
- Snapshot claims must include the date context.
- User-facing Happy Horse website links in this repository are standardized to [tryhappyhorse.com](https://tryhappyhorse.com/).
- Other Happy Horse domains may be discussed as text when needed for analysis, but are not surfaced as reader-facing destination links by default.
- Links that cannot be tied back to the official public repo are never presented as official by default.
- Failure cases remain in scope because they prevent false confidence.

## Correction Rules

- If a stronger source contradicts an existing claim, the claim should be downgraded or marked `Outdated`.
- If a community claim is later supported directly by an official source, it can be upgraded.
- Status changes should be reflected in both Markdown and JSON files.
