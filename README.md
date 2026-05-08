# Galileo Financial Technologies (galileo-fs)

Galileo Financial Technologies (a SoFi company) is a card-issuing and banking platform powering many fintechs. Provides Program API (accounts, cards), Config API, Dispute API 3.0, Loan API, Payment Hub API, Risk API, Auth API (authorization controller webhook), Events API webhooks, and External Transactions API.

Galileo does not publish a public OpenAPI spec. API reference is gated behind docs.galileo-ft.com login.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/galileo-fs/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=galileo-fs-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Galileo Program API** - REST API for managing accounts and cards: account creation, KYC/CIP verification, balance/funding, card issuance (physical, digital, virtual, instant-issue), authorization controls.
- **Galileo Config API** - REST API for program configuration including card products, fee schedules, MCC controls, and program parameters.
- **Galileo Dispute API 3.0** - REST API for the dispute lifecycle (chargebacks, representments, network communications).
- **Galileo Loan API** - REST API for credit, lending, BNPL, and secured-credit products including draw, repayment, and balance inquiry.
- **Galileo Payment Hub API** - REST API for ACH, RTP, Bill Pay, and other payments rails.
- **Galileo Risk API** - REST API for risk and fraud screening tools.
- **Galileo Auth API (Authorization Controller)** - Synchronous webhook-style endpoint customers expose for Galileo to call during authorization for approve/decline decisions.
- **Galileo Events API** - Outbound webhook delivery for transactions, account events, card events, and other lifecycle events.
- **Galileo External Transactions API** - REST API to feed third-party transactions into Galileo program ledgers for unified reporting.

## Tags
 - FinTech, BaaS, Card Issuing, Banking, Payments, ACH

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.galileo-ft.com/)
- [Plans](plans/galileo-fs-plans-pricing.yml)
- [RateLimits](rate-limits/galileo-fs-rate-limits.yml)
- [FinOps](finops/galileo-fs-finops.yml)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
