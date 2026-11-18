# dbt + Snowflake Dimensional Modeling — Star Schema & SCD Type 2

A modular dbt project that models investment, portfolio, financial reporting and healthcare data in Snowflake as dimensional star schemas with SCD Type 2 history. Incremental materializations and CDC-based loads keep large tables fast, while dbt tests, documentation and lineage make every mart trusted and auditable. Includes migration patterns from legacy Informatica workflows to modern dbt models, on synthetic data only.

**Tech stack:** dbt • Snowflake • SQL • Redshift • Azure Synapse

## Architecture Overview
Staging (source-aligned, light cleaning) → Intermediate (business logic) → Marts (star schema facts/dimensions, SCD Type 2 snapshots) — all tested with dbt schema and data tests.

## Project Structure
`models/ (staging, intermediate, marts), snapshots/, tests/, macros/`

## How to Run
Configure a Snowflake (or DuckDB) profile, run `dbt build` to execute models, snapshots and tests end to end.

## Skills Demonstrated
dbt, Snowflake, SQL, Dimensional Modeling, Star Schema, Fact & Dimension Tables, SCD Type 2, Incremental Materializations, CDC, Stored Procedures, Data Testing, Amazon Redshift, Azure Synapse Analytics, Informatica Migration

## Notes
Portfolio project built on **synthetic data only** — real production engineering patterns from healthcare and financial services data engineering, with no real patient, customer, or market data, and no employer-confidential code or data.

---
*By Sreya Peddu — Senior Data Engineer, Dallas–Fort Worth, TX • peddusreya02@gmail.com • [LinkedIn](https://www.linkedin.com/in/sreyapeddu)*
