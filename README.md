# Pódio · Radar do financiamento público ao desporto

Base de dados do financiamento público ao desporto em Portugal e o painel que a apresenta.

## Conteúdo

- `db.json` — base de dados (JSON), gerada em 2026-11-22:
  - `mun` — 308 municípios
  - `rec` — 2.700 registos de financiamento
  - `cov` — cobertura das fontes (20)
  - `ent` — entidades financiadoras (6)
  - `elig` — critérios de elegibilidade (18)
  - `opps` — oportunidades de financiamento (23)
  - `gerado` — data de geração
- `index.html` — painel "Radar Pódio" que lê a base.
- `analise.html` — "Pesquisa de mercado": quem financia, quem recebe, valores, personas de beneficiário e hubs geográficos, calculados a partir de `db.json`.
