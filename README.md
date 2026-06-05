# Dune Analytics (dune-analytics)

Dune is a SQL-based crowdsourced blockchain analytics platform. The Dune API exposes Query Execution endpoints (run/poll/results), pre-built Trends endpoints, EVM Transactions API, Echo (real-time multichain wallet data via Sim), a Trino warehouse connector, and dbt integration. Pricing is credit-based: query executions, data exports, and writes consume credits against a plan-tier monthly allowance.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dune-analytics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dune-analytics/refs/heads/main/apis.yml)

## Tags

- Web3
- Analytics
- SQL
- Dashboards
- Blockchain
- Onchain
- Multi-chain

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Dune Query API

REST endpoints for executing pre-saved Dune SQL queries, polling execution status, and paginating results. Powers programmatic access to community and team-built analytics. Authentication via X-Dune-API-Key header.

- **Human URL:** [https://docs.dune.com/api-reference/overview/introduction](https://docs.dune.com/api-reference/overview/introduction)
- **Base URL:** `https://api.dune.com/api/v1`

#### Tags

- SQL
- Query
- Onchain
- Analytics

#### Properties

- [Documentation](https://docs.dune.com/api-reference/overview/introduction)
- [Pricing](https://dune.com/pricing)
- [Postman Collection](collections/dune-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dune-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dune Trends API

Curated, fixed endpoints over Dune's most popular trend datasets without writing SQL.

- **Human URL:** [https://docs.dune.com/api-reference/trends/overview](https://docs.dune.com/api-reference/trends/overview)
- **Base URL:** `https://api.dune.com/api/v1/trends`

#### Tags

- Trends
- Pre-built
- Onchain

#### Properties

- [Documentation](https://docs.dune.com/api-reference/trends/overview)
- [Postman Collection](collections/dune-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dune-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dune Echo (Sim) Multichain API

Real-time multichain wallet, token, and transaction data across EVM and SVM chains via Sim by Dune.

- **Human URL:** [https://docs.sim.dune.com/](https://docs.sim.dune.com/)
- **Base URL:** `https://api.sim.dune.com`

#### Tags

- Multichain
- Wallets
- Real-time
- EVM
- SVM

#### Properties

- [Documentation](https://docs.sim.dune.com/)
- [Postman Collection](collections/dune-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dune-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/dune-analytics)
- [Portal](https://dune.com/)
- [Documentation](https://docs.dune.com/)
- [Pricing](https://dune.com/pricing)
- [Git Hub](https://github.com/duneanalytics)
- [Plans](plans/dune-analytics-plans-pricing.yml)
- [Rate Limits](rate-limits/dune-analytics-rate-limits.yml)
- [Fin Ops](finops/dune-analytics-finops.yml)
- [L L Ms Txt](https://docs.dune.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
