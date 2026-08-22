# WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) (wealthville-defi-liquidity-pool-scores-api-solana-evm)

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

WealthVille provides a public, keyless REST API and agent-native surfaces for DeFi liquidity-pool scoring and signals across Solana and EVM chains. It exposes a composite Wealthville Score (0-100) with Enter/Hold/Exit verdicts, per-protocol confidence, Solana sub-scores (Risk, Scout, Farmer), an outcome-labeled track record, and a signals feed. Coverage includes Solana (Meteora, Orca, Raydium) and EVM chains (Ethereum, Arbitrum, Base, Optimism, Polygon, BNB Chain). The API is anonymous by default at 60 requests/min per IP, CORS-open, and read-only — every published operation is a GET. Alongside the REST contract WealthVille publishes an OpenAPI 3.0.3 document at the API host root, an llms.txt, a hosted Streamable-HTTP MCP server with four ungated tools, and a first-party MIT-licensed connector family (MCP server, ElizaOS plugin, Solana Agent Kit plugin, MCPB bundle, Gemini extension) plus its own Agent Skill.

**APIs.json:** [https://wealthville-defi-liquidity-pool-scores-api-solana-evm.apievangelist.com/apis.yml](https://wealthville-defi-liquidity-pool-scores-api-solana-evm.apievangelist.com/apis.yml)

## Tags

- DeFi
- Liquidity Pools
- Blockchain Analytics
- Solana
- EVM
- Ethereum
- Yield Farming
- Risk Scoring
- MCP
- AI Agents
- Financial Data

## Timestamps

- **Created:** 2026-07-27
- **Modified:** 2026-08-09

## APIs

### WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) Scores API

The Scores API from WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) — 2 operation(s) for scores.

- **Human URL:** [https://wealthville.net/developers](https://wealthville.net/developers)
- **Base URL:** `https://wealthville.net/api/v1`

#### Tags

- Scores

#### Properties

- [OpenAPI](openapi/wealthville-defi-liquidity-pool-scores-api-solana-evm-scores-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wealthville-defi-liquidity-pool-scores-api-solana-evm-scores-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wealthville-defi-liquidity-pool-scores-api-solana-evm-scores-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://wealthville.net/developers)
- [L L M S Txt](https://wealthville.net/llms.txt)
- [Examples](examples/_index.yml)
- [Tool Crosswalk](mcp/wealthville-defi-liquidity-pool-scores-api-solana-evm-tool-crosswalk.yml)

### WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) Signals API

The Signals API from WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) — 2 operation(s) for signals.

- **Human URL:** [https://wealthville.net/developers](https://wealthville.net/developers)
- **Base URL:** `https://wealthville.net/api/v1`

#### Tags

- Signals

#### Properties

- [OpenAPI](openapi/wealthville-defi-liquidity-pool-scores-api-solana-evm-signals-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wealthville-defi-liquidity-pool-scores-api-solana-evm-signals-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wealthville-defi-liquidity-pool-scores-api-solana-evm-signals-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://wealthville.net/developers)
- [L L M S Txt](https://wealthville.net/llms.txt)
- [Examples](examples/_index.yml)
- [Tool Crosswalk](mcp/wealthville-defi-liquidity-pool-scores-api-solana-evm-tool-crosswalk.yml)

### WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) Track Record API

The Track Record API from WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) — 1 operation(s) for track record.

- **Human URL:** [https://wealthville.net/developers](https://wealthville.net/developers)
- **Base URL:** `https://wealthville.net/api/v1`

#### Tags

- Track Record

#### Properties

- [OpenAPI](openapi/wealthville-defi-liquidity-pool-scores-api-solana-evm-track-record-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wealthville-defi-liquidity-pool-scores-api-solana-evm-track-record-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wealthville-defi-liquidity-pool-scores-api-solana-evm-track-record-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://wealthville.net/developers)
- [L L M S Txt](https://wealthville.net/llms.txt)
- [Examples](examples/_index.yml)
- [Tool Crosswalk](mcp/wealthville-defi-liquidity-pool-scores-api-solana-evm-tool-crosswalk.yml)

## Common Properties

- [Overlay](overlays/wealthville-defi-liquidity-pool-scores-api-solana-evm-public-data-overlay.yaml)
- [Vulnerability Disclosure](security/wealthville-defi-liquidity-pool-scores-api-solana-evm-vulnerability-disclosure.yml)
- [Security](https://wealthville.net/security)
- [Domain Security](security/wealthville-defi-liquidity-pool-scores-api-solana-evm-domain-security.yml)
- [Authentication](authentication/wealthville-defi-liquidity-pool-scores-api-solana-evm-authentication.yml)
- [M C P Server](mcp/wealthville-defi-liquidity-pool-scores-api-solana-evm-mcp.yml)
- [Tool Crosswalk](mcp/wealthville-defi-liquidity-pool-scores-api-solana-evm-tool-crosswalk.yml)
- [Agent Skill](skills/_index.yml)
- [Packages](packages/wealthville-defi-liquidity-pool-scores-api-solana-evm-packages.yml)
- [S D Ks](packages/wealthville-defi-liquidity-pool-scores-api-solana-evm-packages.yml)
- [L L Ms Txt](llms/wealthville-defi-liquidity-pool-scores-api-solana-evm-llms.txt)
- [Well Known](well-known/wealthville-defi-liquidity-pool-scores-api-solana-evm-well-known.yml)
- [Conventions](conventions/wealthville-defi-liquidity-pool-scores-api-solana-evm-conventions.yml)
- [Idempotency](conventions/wealthville-defi-liquidity-pool-scores-api-solana-evm-conventions.yml)
- [Rate Limits](rate-limits/wealthville-defi-liquidity-pool-scores-api-solana-evm-rate-limits.yml)
- [Error Catalog](errors/wealthville-defi-liquidity-pool-scores-api-solana-evm-problem-types.yml)
- [Lifecycle](lifecycle/wealthville-defi-liquidity-pool-scores-api-solana-evm-lifecycle.yml)
- [Conformance](conformance/wealthville-defi-liquidity-pool-scores-api-solana-evm-conformance.yml)
- [Data Model](data-model/wealthville-defi-liquidity-pool-scores-api-solana-evm-data-model.yml)
- [Developer Portal](https://wealthville.net/developers)
- [API Reference](https://wealthville.net/developers)
- [GitHub Organization](https://github.com/amitesh-m/wealthville-integrations)
- [Support](https://wealthville.net/contact)
- [Blog](https://blog.wealthville.net/)
- [Pricing](https://wealthville.net/pricing)
- [Terms of Service](https://wealthville.net/terms)
- [Privacy Policy](https://wealthville.net/privacy)

## Maintainers

**FN:** WealthVille
**Email:** support@wealthville.net
**URL:** https://wealthville.net
