# Galileo Financial Technologies (galileo-fs)

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

Galileo Financial Technologies (a SoFi company) is a card-issuing and banking platform powering many fintechs. Provides Program API (accounts, cards), Config API, Dispute API 3.0, Loan API, Payment Hub API, Risk API, Auth API (authorization controller webhook), Events API webhooks, and External Transactions API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/galileo-fs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/galileo-fs/refs/heads/main/apis.yml)

## Tags

- FinTech
- BaaS
- Card Issuing
- Banking
- Payments
- ACH

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Galileo Program API

REST API for managing accounts and cards: account creation, KYC/CIP verification, balance/funding, card issuance (physical, digital, virtual, instant-issue), authorization controls.

- **Human URL:** [https://docs.galileo-ft.com/pro/](https://docs.galileo-ft.com/pro/)
- **Base URL:** `https://api-sandbox.cv.gpsrv.com`

#### Tags

- REST
- Card Issuing
- Banking

#### Properties

- [Documentation](https://docs.galileo-ft.com/pro/)
- [Postman Collection](collections/galileo-fs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-fs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Galileo Config API

REST API for program configuration including card products, fee schedules, MCC controls, and program parameters.

- **Human URL:** [https://docs.galileo-ft.com/pro/reference/config-api](https://docs.galileo-ft.com/pro/reference/config-api)
- **Base URL:** `https://api-sandbox.cv.gpsrv.com`

#### Tags

- REST
- Configuration

#### Properties

- [Documentation](https://docs.galileo-ft.com/pro/reference/config-api)
- [Postman Collection](collections/galileo-fs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-fs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Galileo Dispute API 3.0

REST API for the dispute lifecycle (chargebacks, representments, network communications).

- **Human URL:** [https://docs.galileo-ft.com/pro/reference/dispute-api](https://docs.galileo-ft.com/pro/reference/dispute-api)
- **Base URL:** `https://api-sandbox.cv.gpsrv.com`

#### Tags

- REST
- Disputes

#### Properties

- [Documentation](https://docs.galileo-ft.com/pro/reference/dispute-api)
- [Postman Collection](collections/galileo-fs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-fs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Galileo Loan API

REST API for credit, lending, BNPL, and secured-credit products including draw, repayment, and balance inquiry.

- **Human URL:** [https://docs.galileo-ft.com/pro/reference/loan-api](https://docs.galileo-ft.com/pro/reference/loan-api)
- **Base URL:** `https://api-sandbox.cv.gpsrv.com`

#### Tags

- REST
- Lending

#### Properties

- [Documentation](https://docs.galileo-ft.com/pro/reference/loan-api)
- [Postman Collection](collections/galileo-fs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-fs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Galileo Payment Hub API

REST API for ACH, RTP, Bill Pay, and other payments rails.

- **Human URL:** [https://docs.galileo-ft.com/pro/reference/payment-hub-api](https://docs.galileo-ft.com/pro/reference/payment-hub-api)
- **Base URL:** `https://api-sandbox.cv.gpsrv.com`

#### Tags

- REST
- Payments
- ACH

#### Properties

- [Documentation](https://docs.galileo-ft.com/pro/reference/payment-hub-api)
- [Postman Collection](collections/galileo-fs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-fs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Galileo Risk API

REST API for risk and fraud screening tools.

- **Human URL:** [https://docs.galileo-ft.com/pro/reference/risk-api](https://docs.galileo-ft.com/pro/reference/risk-api)
- **Base URL:** `https://api-sandbox.cv.gpsrv.com`

#### Tags

- REST
- Risk

#### Properties

- [Documentation](https://docs.galileo-ft.com/pro/reference/risk-api)
- [Postman Collection](collections/galileo-fs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-fs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Galileo Auth API (Authorization Controller)

Synchronous webhook-style endpoint customers expose for Galileo to call during authorization for approve/decline decisions.

- **Human URL:** [https://docs.galileo-ft.com/pro/reference/auth-api](https://docs.galileo-ft.com/pro/reference/auth-api)
- **Base URL:** `customer-hosted`

#### Tags

- Webhooks
- Authorization

#### Properties

- [Documentation](https://docs.galileo-ft.com/pro/reference/auth-api)
- [Postman Collection](collections/galileo-fs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-fs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Galileo Events API

Outbound webhook delivery for transactions, account events, card events, and other lifecycle events.

- **Human URL:** [https://docs.galileo-ft.com/pro/reference/events-api](https://docs.galileo-ft.com/pro/reference/events-api)
- **Base URL:** `https://api-sandbox.cv.gpsrv.com`

#### Tags

- Webhooks

#### Properties

- [Documentation](https://docs.galileo-ft.com/pro/reference/events-api)
- [Postman Collection](collections/galileo-fs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-fs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Galileo External Transactions API

REST API to feed third-party transactions into Galileo program ledgers for unified reporting.

- **Human URL:** [https://docs.galileo-ft.com/pro/reference/external-transactions-api](https://docs.galileo-ft.com/pro/reference/external-transactions-api)
- **Base URL:** `https://api-sandbox.cv.gpsrv.com`

#### Tags

- REST
- External

#### Properties

- [Documentation](https://docs.galileo-ft.com/pro/reference/external-transactions-api)
- [Postman Collection](collections/galileo-fs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-fs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/galileo-financial-technologies)
- [Website](https://www.galileo-ft.com/)
- [Plans](plans/galileo-fs-plans-pricing.yml)
- [Rate Limits](rate-limits/galileo-fs-rate-limits.yml)
- [Fin Ops](finops/galileo-fs-finops.yml)
- [L L Ms Txt](https://docs.galileo-ft.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
