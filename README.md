# BIS

BIS is a home for reusable data-processing and data-analysis assets maintained
by the MRD JE team. It brings SQL, Tableau, and Elixir work together while
keeping each technology's files in a clear, reviewable location.

## Repository layout

- `sql/` — database schemas, transformations, and analysis queries.
- `tableau/` — Tableau workbooks and data-source documentation.
- `elixir/` — the Elixir application for data-processing code.

See each directory's README for conventions and guidance on adding assets.

## Getting started

- SQL: check the target database and required source tables before running a
  script; scripts should state their purpose and any assumptions.
- Tableau: open a workbook from `tableau/workbooks/` in Tableau Desktop and
  configure its documented data source.
- Elixir: from `elixir/`, run `mix compile` to compile the starter application.

Do not commit credentials, private keys, or extracts containing sensitive
production data. Document required connection settings without including
secret values.
