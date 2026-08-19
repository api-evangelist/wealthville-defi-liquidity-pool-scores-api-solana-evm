# WealthVille — DeFi Liquidity Pool Scores API (Solana & EVM) (wealthville-defi-liquidity-pool-scores-api-solana-evm)

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
