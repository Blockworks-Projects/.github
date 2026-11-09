<p align="center">
  <a href="https://blockworks.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="blockworks-dark.svg">
      <img alt="Blockworks" src="blockworks-light.svg" width="360">
    </picture>
  </a>
</p>

<h3 align="center">Institutional-grade crypto data. Built to be queried by agents.</h3>

<p align="center">
  Market data, onchain metrics, fundraising, and research across tens of thousands of assets, maintained by the Blockworks research team and delivered wherever your product or your AI already works.
</p>

<p align="center">
  Messari is now part of Blockworks. Messari data continues here, unified in the Blockworks API and MCP. <a href="https://blockworks.com/insights/blockworks-acquires-messari">Announcement</a>
</p>

<p align="center">
  <a href="https://docs.blockworks.com">Docs</a>
  &nbsp;·&nbsp;
  <a href="https://docs.blockworks.com/mcp/quickstart">MCP quickstart</a>
  &nbsp;·&nbsp;
  <a href="https://app.blockworks.com/account/api">Get an API key</a>
  &nbsp;·&nbsp;
  <a href="https://blockworks.com/contact">Talk to us</a>
</p>

<br>

## The data

More than 70 datasets and 170 endpoints, tabular and timeseries, with the same curated metrics Blockworks analysts use in production.

- **Market data**: assets, markets, exchanges, derivatives
- **Projects and protocols**: revenue, lending, spot and perp DEXes, vaults, launchpads
- **Fundraising**: rounds, investors, funds, M&A
- **Institutional**: ETFs, digital asset treasuries
- **Real world assets**: stablecoins, tokenized equities and commodities
- **News and research**: Blockworks reports, diligence, and aggregated news

The full catalog, with every model, column, and metric, is in the [API reference](https://docs.blockworks.com/api-reference/data-api/market-data).

## In your agent

One hosted MCP server over the whole catalog. Nothing to install or run.

| Where | How |
| --- | --- |
| **Any MCP client** | Add `https://mcp.blockworks.com/mcp`, authorize with your API key or Blockworks login, start asking. Works with Claude, Claude Code, Cursor, and any agent framework that speaks remote MCP. |
| **ChatGPT** | Install the [Blockworks plugin](https://docs.blockworks.com/mcp/plugins/chatgpt) from the ChatGPT plugin directory and authorize it once. |

## In your product

| Surface | What it is for |
| --- | --- |
| **Data API** | REST access to every dataset and metric series. The same data the MCP server reads. |
| **Monitoring API** | Events, webhooks, and Telegram alerts for the things your product reacts to. |

```bash
curl 'https://api.blockworks.com/query/tabular/assets?pageSize=5' \
  -H "X-Blockworks-API-Key: $BLOCKWORKS_API_KEY"
```

## For AI agents and crawlers

Machine-readable entry points, kept current with the docs:

| File | Use it for |
| --- | --- |
| [`llms.txt`](https://docs.blockworks.com/llms.txt) | Index of every docs page with a one-line summary. Start here. |
| [`llms-full.txt`](https://docs.blockworks.com/llms-full.txt) | The full documentation in one file, for agents that want everything in context. |
| [MCP tools reference](https://docs.blockworks.com/mcp/tools/overview) | Every tool the hosted MCP server exposes, with inputs and outputs. |

<br>

<p align="center">
  <sub><a href="https://blockworks.com">blockworks.com</a> · <a href="https://docs.blockworks.com">docs.blockworks.com</a></sub>
</p>
