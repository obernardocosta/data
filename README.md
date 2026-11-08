# dados-big-data

Cópia **raw** (sem alterações) dos datasets usados nas disciplinas **GDBD** e
**PDN** do material [obernardocosta/big-data](https://github.com/obernardocosta/big-data).

**Por que existe:** os labs não dependem mais de um repositório de terceiros que
pode mudar, sair do ar ou ser reorganizado. Os labs sempre apontam para este
repositório.

## Datasets

| Dataset | Caminho | Origem | Licença |
|---|---|---|---|
| Premier League 2024/25 | [`futebol/premier-league/2024-25/en.1.json`](futebol/premier-league/2024-25/en.1.json) | [openfootball](https://github.com/openfootball/football.json) | CC0 1.0 |

## Convenções

- Um diretório por tema e por dataset: `tema/dataset/versão/`.
- Cada dataset tem `README.md` com origem, licença, SHA-256 e data da cópia.
- Arquivos raw nunca são editados. Versão nova = nova pasta (ex.: `2025-26/`).
- URL raw: `https://raw.githubusercontent.com/obernardocosta/dados-big-data/main/<caminho>`
