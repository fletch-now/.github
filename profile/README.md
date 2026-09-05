<img src="https://raw.githubusercontent.com/fletch-now/fletch-mcp/main/docs/fletch-logo.png" alt="Fletch" width="120">

# Fletch

Fletch is a wallet-native app for Robinhood Chain (mainnet 4663, testnet 46630). Describe an app and Fletch writes the contract and the page, compiles and tests it with Foundry, deploys it to testnet and hosts it. Point a watcher at a verified asset and it messages you on Telegram. The registry keeps every Stock Token on the chain verified and live, with a public API.

The repositories here are the parts worth reading and reusing:

| Repository | What it is |
| --- | --- |
| [fletch-mcp](https://github.com/fletch-now/fletch-mcp) | The registry as MCP tools for Claude, Cursor and any other MCP client. |
| [fletch-api](https://github.com/fletch-now/fletch-api) | The OpenAPI spec, the event vocabulary, the freshness guide, webhook verifiers in TypeScript, Python and Go, and a generated TypeScript SDK. |
| [fletch-registry-data](https://github.com/fletch-now/fletch-registry-data) | Daily git snapshots of every asset, lookalike and registry event, pulled from the public API, with provenance. |

Links: [fletch.now](https://fletch.now) · [Developers](https://fletch.now/developers) · [API docs](https://fletch.now/api/v1/docs) · [Registry](https://fletch.now/registry) · [llms.txt](https://fletch.now/llms.txt)

Fletch is not affiliated with Robinhood Markets, Inc.
