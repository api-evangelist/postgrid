# PostGrid (postgrid)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
