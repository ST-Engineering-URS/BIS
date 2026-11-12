# SQL

Store database-specific, reviewable SQL assets here. Keep SQL independent of
Tableau workbook files so queries can be reused and reviewed on their own.

## Organization

- `schemas/` — schema definitions and reference DDL.
- `transformations/` — reusable data preparation and transformation scripts.
- `queries/` — analysis and reporting queries.

Use descriptive filenames, for example `orders_by_month.sql`. Start each
script with a brief description and document its target database, required
tables, and any assumptions. Avoid embedding credentials or environment-specific
secrets.
