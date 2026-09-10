<img src="https://raw.githubusercontent.com/fletch-now/fletch-mcp/main/docs/fletch-logo.png" alt="Fletch" width="120">

# Fletch

Fletch turns a prompt into an app for Robinhood Chain (mainnet 4663, testnet 46630).
Builds save project files and conversation progress, run generated code in Docker,
and report compiler/test results and actual hosting or deployment outcomes.
Choose a platform model or connect an OpenAI, Anthropic or Kimi account. Own-key
model usage is billed by that provider. Text and native image references are
supported when the selected connection exposes those capabilities; availability
and limits are shown in the app.

The registry publishes observed token identity, trust, prices, pools and activity
through a public API. Its jobs and historical scans have different coverage. Check
[live status](https://fletch.now/api/v1/status), each observation timestamp and
`stateCurrent` before using a price. A timely job does not mean every token is
verified or every figure is current. Watchers deliver supported events through
Telegram or signed webhooks.

| Repository | Contents |
| --- | --- |
| [fletch-mcp](https://github.com/fletch-now/fletch-mcp) | Explicit registry reads for MCP clients, with bounded queries and trust/freshness guidance. |
| [fletch-api](https://github.com/fletch-now/fletch-api) | Dated public OpenAPI snapshots, generated TypeScript types, API/freshness guides and webhook verifiers. |
| [fletch-registry-data](https://github.com/fletch-now/fletch-registry-data) | Daily asset, lookalike and event snapshots with provenance; snapshot timestamps are not live observation times. |

Markets exposes a [shared filter catalog](https://fletch.now/api/v1/chains/4663/markets/filters)
for the website, API and agent clients. Read one token page with combined filters,
then inspect each reading's source, time and unavailable reason.

Start with [fletch.now](https://fletch.now), [Developers](https://fletch.now/developers),
[API docs](https://fletch.now/api/v1/docs), [Registry](https://fletch.now/registry),
[agent skill](https://fletch.now/skill.md), [agent overview](https://fletch.now/llms.txt) or the
[full agent reference](https://fletch.now/llms-full.txt).
The MCP package can be run from GitHub with `npx -y github:fletch-now/fletch-mcp`;
npm publication remains pending as of 8 September 2026.

Fletch is not affiliated with Robinhood Markets, Inc.
