# data

Raw (unmodified) copies of the datasets used in the **GDBD** and **PDN** Big Data
courses from [obernardocosta/big-data](https://github.com/obernardocosta/big-data).

**Why this exists:** labs never depend on a third-party repository that may
change, move or disappear. Labs always point to this repository.

## Datasets

| Dataset | Path | Source | License |
|---|---|---|---|
| Premier League 2024/25 | [`football/premier-league/2024-25/en.1.json`](football/premier-league/2024-25/en.1.json) | [openfootball](https://github.com/openfootball/football.json) | CC0 1.0 |

## Conventions

- One directory per topic and dataset: `topic/dataset/version/`.
- Every dataset has a `README.md` with source, license, SHA-256 and copy date.
- Raw files are never edited. A new version goes in a new folder (e.g. `2025-26/`).
- Raw URL: `https://raw.githubusercontent.com/obernardocosta/data/main/<path>`
