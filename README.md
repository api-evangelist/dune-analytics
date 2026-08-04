# Dune Analytics (dune-analytics)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
