# WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM)

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

**Areas:** DeFi · Liquidity Pools · Blockchain Analytics · Solana · EVM · Ethereum · Yield Farming · Risk Scoring · MCP · AI Agents · Financial Data

## WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) on APIs.io

Everything profiled for WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/wealthville-defi-liquidity-pool-scores-api-solana-evm/](https://apis.io/providers/wealthville-defi-liquidity-pool-scores-api-solana-evm/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) Scores API](https://apis.io/apis/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-scores-api/) — The Scores API from WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) — 2 operation(s) for scores.
- [WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) Signals API](https://apis.io/apis/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-signals-api/) — The Signals API from WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) — 2 operation(s) for signals.
- [WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) Track Record API](https://apis.io/apis/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-track-record-api/) — The Track Record API from WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) — 1 operation(s) for track record.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Wealthville](https://apis.io/servers/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville/)

#### Examples (3)

Example requests and responses.

- [Wealthville Defi Liquidity Pool Scores Api Solana Evm Scores Top](https://apis.io/examples/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-scores-top/)
- [Wealthville Defi Liquidity Pool Scores Api Solana Evm Signals Feed](https://apis.io/examples/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-signals-feed/)
- [Wealthville Defi Liquidity Pool Scores Api Solana Evm Track Record](https://apis.io/examples/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-track-record/)

#### Collections (3)

Postman and Open Collection request collections.

- [Wealthville Public Data Scores API](https://apis.io/collections/wealthville-defi-liquidity-pool-scores-api-solana-evm/open-wealthville-defi-liquidity-pool-scores-api-solana-evm-scores-api/)
- [Wealthville Public Data Signals API](https://apis.io/collections/wealthville-defi-liquidity-pool-scores-api-solana-evm/open-wealthville-defi-liquidity-pool-scores-api-solana-evm-signals-api/)
- [Wealthville Public Data Track Record API](https://apis.io/collections/wealthville-defi-liquidity-pool-scores-api-solana-evm/open-wealthville-defi-liquidity-pool-scores-api-solana-evm-track-record-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Wealthville Defi Liquidity Pool Scores Api Solana Evm Public Data Overlay](https://apis.io/overlays/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-public-data-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Wealthville Defi Liquidity Pool Scores Api Solana Evm Authentication](https://apis.io/security/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-authentication/)
- [Wealthville Defi Liquidity Pool Scores Api Solana Evm Domain Security](https://apis.io/security/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-domain-security/)
- [Wealthville Defi Liquidity Pool Scores Api Solana Evm Vulnerability Disclosure](https://apis.io/security/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-vulnerability-disclosure/)

#### Rate limits (1)

Published request limits.

- [Wealthville Defi Liquidity Pool Scores Api Solana Evm Rate Limits](https://apis.io/rate-limits/wealthville-defi-liquidity-pool-scores-api-solana-evm/wealthville-defi-liquidity-pool-scores-api-solana-evm-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.wealthville.net/)
- [API reference](https://wealthville.net/developers)
- [Pricing](https://wealthville.net/pricing)
- [Support](https://wealthville.net/contact)
- [Blog](https://blog.wealthville.net/)
- [Security](https://wealthville.net/security)
- [Terms of service](https://wealthville.net/terms)
- [Privacy policy](https://wealthville.net/privacy)
- [GitHub](https://github.com/amitesh-m/wealthville-integrations)

## API Evangelist rating

**Kin Score 45.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 50.9 |
| Contract governance | 4.5 |
| Operational transparency | 34.2 |
| Developer ergonomics | 59.5 |
| Access clarity | 31.6 |

**Agent readiness 43.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/wealthville-defi-liquidity-pool-scores-api-solana-evm/](https://apis.io/providers/wealthville-defi-liquidity-pool-scores-api-solana-evm/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM): the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/wealthville-defi-liquidity-pool-scores-api-solana-evm/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
