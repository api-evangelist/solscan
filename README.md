# Solscan (solscan)

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

Solscan is a leading Solana block explorer with a Public API (free, basic) and a Pro API (paid, with full account, transaction, token, NFT, and DeFi endpoints). The Pro API serves decoded on-chain data and is the primary commercial product. Authentication uses a token (Bearer or query parameter) and is required for all Pro endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/solscan/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/solscan/refs/heads/main/apis.yml)

## Tags

- Web3
- Solana
- Explorer
- On-Chain
- Tokens
- NFTs

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Solscan Public API

Free, lower-rate-limit public API exposing basic account, transaction, and token endpoints used by the Solscan UI.

- **Human URL:** [https://docs.solscan.io/](https://docs.solscan.io/)
- **Base URL:** `https://public-api.solscan.io`

#### Tags

- Solana
- Explorer
- Free

#### Properties

- [Documentation](https://docs.solscan.io/)

### Solscan Pro API

Commercial Pro API with full account, transaction, token, NFT, DeFi, and analytics endpoints. Higher rate limits, decoded events, and historical depth. Authentication via token header.

- **Human URL:** [https://pro-api.solscan.io/pro-api-docs/v2.0](https://pro-api.solscan.io/pro-api-docs/v2.0)
- **Base URL:** `https://pro-api.solscan.io`

#### Tags

- Solana
- Pro
- Decoded Data
- Tokens
- NFTs
- DeFi

#### Properties

- [Documentation](https://pro-api.solscan.io/pro-api-docs/v2.0)
- [Pricing](https://solscan.io/apis)

## Common Properties

- [GitHub Organization](https://github.com/solscanofficial)
- [Portal](https://solscan.io/)
- [Documentation](https://docs.solscan.io/)
- [Pricing](https://solscan.io/apis)
- [Plans](plans/solscan-plans-pricing.yml)
- [Rate Limits](rate-limits/solscan-rate-limits.yml)
- [Fin Ops](finops/solscan-finops.yml)
- [L L Ms Txt](https://docs.solscan.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
