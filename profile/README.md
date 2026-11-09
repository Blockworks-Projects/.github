<p align="center">
  <a href="https://blockworks.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="blockworks-dark.svg">
      <img alt="Blockworks" src="blockworks-light.svg" width="360">
    </picture>
  </a>
</p>

<h3 align="center">Crypto intelligence, built for agents.</h3>

<p align="center">
  Market data, onchain metrics, and institutional research covering tens of thousands of assets.<br>
  Delivered wherever your AI already works: MCP, plugins, skills, and an API underneath it all.
</p>

<p align="center">
  <a href="https://docs.blockworks.com/mcp/quickstart">MCP quickstart</a>
  &nbsp;·&nbsp;
  <a href="https://docs.blockworks.com">Docs</a>
  &nbsp;·&nbsp;
  <a href="https://app.blockworks.com/account/api">Get an API key</a>
  &nbsp;·&nbsp;
  <a href="https://blockworks.com/contact">Talk to us</a>
</p>

<br>

## Plug Blockworks into your agent

One dataset, one hosted MCP server, packaged for every client that matters. Nothing to install or run.

| Where | How |
| --- | --- |
| **Any MCP client** | Add `https://mcp.blockworks.com/mcp`, authorize with your API key, start asking. Works with Claude, Claude Code, Cursor, ChatGPT, and any agent framework that speaks remote MCP. |
| **Claude** | [Blockworks plugin for Claude](https://github.com/Blockworks-Projects/claude-plugin): the MCP connection plus a research skill, a `/blockworks:research` command, and a `crypto-analyst` agent. |
| **ChatGPT** | [Blockworks plugin](https://docs.blockworks.com/mcp/plugins/chatgpt) in the ChatGPT plugin directory. Install, authorize once, done. |
| **Grok and Cursor** | [Blockworks plugin for Grok](https://github.com/Blockworks-Projects/grok-plugin): the same skill, command, and agent for Grok Build, Grok Bot, and Cursor. |
| **Autonomous agents** | Pay-per-call access over x402, so an agent with a wallet can pull Blockworks data without an account. |

Five tools cover the whole surface: document search over research and news, plus catalog-and-read pairs for tabular datasets and metric timeseries. The agent discovers what exists, then reads exactly what it needs.

## The data underneath

Delivery is the product. The data is the moat.

- **Markets**: prices, volumes, and market caps across tens of thousands of assets and hundreds of exchanges.
- **Onchain**: TVL, fees, revenue, active addresses, and transaction activity for major networks and protocols.
- **Capital**: funding rounds, M&A, investors, fund data, and token unlock schedules.
- **Research**: Blockworks reports, diligence, quarterly reviews, and aggregated news, searchable with citations.

Every surface above reads from the same warehouse-modeled datasets, so an answer in ChatGPT matches the row in your API response.

## Building a product on it

For teams that need Blockworks data inside their own systems rather than inside an assistant:

| Surface | What it is for |
| --- | --- |
| **Data API** | REST access to every dataset and metric series. The foundation under the MCP server. |
| **Monitoring API** | Event streams, webhooks, and Telegram alerts for the things your product reacts to. |
| **Snowflake Datashare** | The full dataset shared live into your warehouse. No ETL, nothing to sync. |

```bash
curl https://api.blockworks.com/v1/metrics/active-address-total \
  -H "X-Blockworks-API-Key: $BLOCKWORKS_API_KEY"
```

Spreadsheet plugins for Excel and Google Sheets are available too, for the analysts who prefer a formula to a prompt.

## Open source

The plugins, skills, and tooling that connect agents to Blockworks live here. Issues and pull requests are welcome.

<br>

<p align="center">
  <sub><a href="https://blockworks.com">blockworks.com</a> · <a href="https://docs.blockworks.com">docs.blockworks.com</a></sub>
</p>
