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
  Delivered wherever your AI already works, with an API underneath.
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

One hosted MCP server. Nothing to install or run.

| Where | How |
| --- | --- |
| **Any MCP client** | Add `https://mcp.blockworks.com/mcp`, authorize with your API key, start asking. Works with Claude, Claude Code, Cursor, and any agent framework that speaks remote MCP. |
| **ChatGPT** | Install the [Blockworks plugin](https://docs.blockworks.com/mcp/plugins/chatgpt) from the ChatGPT plugin directory and authorize it once. |

The tools cover document search over research and news, catalog-and-read access to tabular datasets and metric timeseries, monitoring developments and events, and the user's watchlists. All read-only.

## The datasets

- **Market data**: assets, markets, exchanges, derivatives
- **Projects and protocols**: revenue, lending, spot and perp DEXes, vaults, launchpads
- **Fundraising**: rounds, investors, funds, M&A
- **Institutional**: ETFs, digital asset treasuries
- **Real world assets**: stablecoins, tokenized equities and commodities
- **News and research**: Blockworks reports, diligence, and aggregated news

The full catalog, with every model, column, and metric, is in the [API reference](https://docs.blockworks.com/api-reference/data-api/market-data).

## Building on the API

| Surface | What it is for |
| --- | --- |
| **Data API** | REST access to every dataset and metric series. The same data the MCP server reads. |
| **Monitoring API** | Events, webhooks, and Telegram alerts for the things your product reacts to. |

```bash
curl 'https://api.blockworks.com/query/tabular/assets?pageSize=5' \
  -H "X-Blockworks-API-Key: $BLOCKWORKS_API_KEY"
```

## Open source

Tooling that connects agents to Blockworks lives here. Issues and pull requests are welcome.

<br>

<p align="center">
  <sub><a href="https://blockworks.com">blockworks.com</a> · <a href="https://docs.blockworks.com">docs.blockworks.com</a></sub>
</p>
