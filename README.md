# Galileo Financial Technologies (galileo-fs)

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
