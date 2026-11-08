# Football (openfootball)

Exact copies of [openfootball/football.json](https://github.com/openfootball/football.json) (CC0 1.0), copied on 2026-11-08. Format: `{"name": ..., "matches": [{round, date, time, team1, team2, score:{ht,ft}}]}`.

| File | League/season | Matches | With final score | SHA-256 |
|---|---|---|---|---|
| [`bundesliga/2024-25/de.1.json`](bundesliga/2024-25/de.1.json) | Deutsche Bundesliga 2024/25 | 306 | 306 | `f473d6595e6c29ebedc08b09177aed6a6b2ff0fa8378b82f51dea469139f44c3` |
| [`la-liga/2024-25/es.1.json`](la-liga/2024-25/es.1.json) | Spain Primera División 2024/25 | 380 | 370 | `da5bfa1b3634e1039d9e71aec50bdc847f8761189e3de235a4e730e0dc64ca38` |
| [`ligue-1/2024-25/fr.1.json`](ligue-1/2024-25/fr.1.json) | French Ligue 1 2024/25 | 306 | 306 | `90e9974afe6597452622387ad218f6b0011a5f91f1b426f05152f5b9c105e355` |
| [`premier-league/2018-19/en.1.json`](premier-league/2018-19/en.1.json) | English Premier League 2018/19 | 380 | 380 | `e2224d86f0605a5a1b5b019c845cdecb13aca1d88035686d4159b875250d4730` |
| [`premier-league/2023-24/en.1.json`](premier-league/2023-24/en.1.json) | English Premier League 2023/24 | 380 | 380 | `03e13eafbf78dfe00d7e89dd3bf6643986eb6e8fd86c7664aeb8c5bc0bed88d0` |
| [`premier-league/2024-25/en.1.json`](premier-league/2024-25/en.1.json) | English Premier League 2024/25 | 380 | 380 | `c3d18f552d83382cd4b6b21127adbbfe38e7f8618ddc979fb5404f2df07d0a75` |
| [`serie-a/2024-25/it.1.json`](serie-a/2024-25/it.1.json) | Italian Serie A 2024/25 | 380 | 370 | `7d9bb936de3ccaeec54d57371512a58a5eeb21277e7d5f0882911a834d22b659` |

## Which labs use what

- `premier-league/2024-25/en.1.json`: all GDBD labs that generate the CSV and all PDN labs (main dataset).
- `premier-league/2018-19/en.1.json`: season used in the original course material (Athena and Glue Spark exercises); good for "compare seasons" exercises.
- `premier-league/2023-24/en.1.json`: previous season, for schema evolution / partitioning by season.
- `la-liga`, `bundesliga`, `serie-a`, `ligue-1` (2024-25): alternative datasets for the partitioning lab ("use any dataset you prefer"), e.g. partition by league and month.

Raw URL: `https://raw.githubusercontent.com/obernardocosta/data/main/football/<league>/<season>/<file>`
