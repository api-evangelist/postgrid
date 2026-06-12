# PostGrid (postgrid)

PostGrid is a physical mail automation platform that provides REST APIs for sending printed letters, postcards, checks, and self-mailers at scale. It offers a Print & Mail API that enables developers to programmatically trigger and manage direct mail campaigns with full personalization and tracking support. PostGrid also provides US & Canada Address Verification and International Address Verification APIs covering 245+ countries for real-time autocomplete, standardization, geocoding, and bulk batch verification. The platform supports both test and live API environments, integrates natively with Salesforce, HubSpot, Zapier, and Marketo, and handles postage, printing, and delivery end-to-end.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/postgrid/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=postgrid-api-evangelist&utm_content=repo

## Tags

Direct Mail, Print & Mail, Address Verification, Address Validation, Postcards, Letters, Checks, Physical Mail, Mail Automation, Address Autocomplete, Geocoding

## APIs

### PostGrid Print & Mail API

A REST API for programmatically sending letters, postcards, checks, and self-mailers. Handles printing, postage, and delivery with support for templates, contacts, tracking, webhooks, and both test and live modes. Authenticated via `x-api-key` header.

- **Documentation:** https://docs.postgrid.com/
- **Base URL:** https://api.postgrid.com
- **Python SDK:** https://github.com/postgrid/postgrid-python
- **Node.js SDK:** https://github.com/postgrid/postgrid-node
- **Examples:** https://github.com/postgrid/postgrid-examples

### PostGrid US & Canada Address Verification API

A REST API for real-time address autocomplete, verification, and standardization for US and Canadian addresses. Supports CASS-certified validation, geocoding, freeform address parsing, and batch verification. Default rate limit: 5 requests/second.

- **Documentation:** https://avdocs.postgrid.com/
- **Base URL:** https://api.postgrid.com/addver

### PostGrid International Address Verification API

A REST API for verifying, standardizing, and autocompleting addresses across 245+ countries worldwide. Supports real-time lookups and bulk verification workflows.

- **Documentation:** https://intdocs.postgrid.com/
- **Base URL:** https://api.postgrid.com/addver

## Plans / Rate Limits / FinOps

- **Plans & Pricing:** [plans/postgrid-plans-pricing.yml](plans/postgrid-plans-pricing.yml)
- **Rate Limits:** [rate-limits/postgrid-rate-limits.yml](rate-limits/postgrid-rate-limits.yml)
- **FinOps:** [finops/postgrid-finops.yml](finops/postgrid-finops.yml)

### Pricing Highlights

- **Print & Mail Starter:** Free tier, up to 500 mailings/month. Letters from $1.019, postcards from $0.862, checks at $1.10 per piece.
- **Print & Mail Enterprise:** Unlimited volume, custom lowest-guaranteed rates, dedicated account manager.
- **Address Verification (US & CA):** Essential $18/mo (2k lookups), Business $40/mo (10k), Growth $200/mo (50k), Enterprise custom.
- **International Address Verification:** Essential $20/mo (2k), Business $45/mo (10k), Growth $225/mo (50k).
- **Pay-As-You-Go:** From $0.03–$0.06 per verification with no subscription required.
- Annual billing saves 10% across all address verification plans.

### Rate Limit Highlights

- Address Verification: 5 requests/second default; up to 100 addresses/second via batch endpoints.
- Higher limits available on request via support@postgrid.com.
- HTTP 429 returned when limits are exceeded.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.postgrid.com/ |
| Documentation | https://docs.postgrid.com/ |
| Developers | https://www.postgrid.com/developers/ |
| GitHub Organization | https://github.com/postgrid |
| LinkedIn | https://www.linkedin.com/company/postgrid |
| X (Twitter) | https://x.com/postgridinc |
| Blog | https://www.postgrid.com/blog/ |
| Changelog | https://www.postgrid.com/updates-and-releases/ |
| Pricing | https://www.postgrid.com/pricing/ |
| Status Page | https://status.postgrid.com/ |
| Support | https://www.postgrid.com/help-support/ |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
