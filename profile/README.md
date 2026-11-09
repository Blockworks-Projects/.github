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
  <strong>Messari is now part of Blockworks.</strong> Blockworks acquired Messari in June 2026 and the two data platforms are being unified as Blockworks Data.<br>
  <a href="https://blockworks.com/insights/blockworks-acquires-messari">Announcement</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/messari">Messari on GitHub</a>
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
| **Any MCP client** | Add `https://mcp.blockworks.com/mcp`, authorize with your API key or Login Credentials, start asking. Works with Claude, Claude Code, Cursor, and any agent framework that speaks remote MCP. |
| **ChatGPT** | Install the [Blockworks plugin](https://docs.blockworks.com/mcp/plugins/chatgpt) from the ChatGPT plugin directory and authorize it once. |
| **Claude / Claude Code** | Install the [Blockworks plugin for Claude](https://github.com/Blockworks-Projects/claude-plugin). It points Claude at the hosted MCP server and adds a `crypto-research` skill and a `/blockworks:research` command. |
| **Grok / Cursor** | Install the [Blockworks plugin for Grok](https://github.com/Blockworks-Projects/grok-plugin). Same hosted server, packaged for Grok Build, Grok Bot and Cursor-style loaders. |

The tools cover document search over research and news, catalog-and-read access to tabular datasets and metric timeseries, monitoring developments and events, and the user's watchlists. The data tools are read-only.

## The datasets

- **Market data**: assets, markets, exchanges, derivatives
- **Projects and protocols**: revenue, lending, spot and perp DEXes, vaults, launchpads
- **Fundraising**: rounds, investors, funds, M&A
- **Institutional**: ETFs, digital asset treasuries
- **Real world assets**: stablecoins, tokenized equities and commodities
- **News and research**: Blockworks reports, diligence, and aggregated news

The full catalog, with every model, column, and metric, is in the [API reference](https://docs.blockworks.com/api-reference/data-api/market-data).

## For AI agents and crawlers

Machine-readable entry points, kept current with the docs:

| File | Use it for |
| --- | --- |
| [`llms.txt`](https://docs.blockworks.com/llms.txt) | Index of every docs page with a one-line summary. Start here. |
| [`llms-full.txt`](https://docs.blockworks.com/llms-full.txt) | The full documentation in one file, for agents that want everything in context. |
| [MCP tools reference](https://docs.blockworks.com/mcp/tools/overview) | Every tool the hosted MCP server exposes, with inputs and outputs. |
| [Messari agent skill](https://raw.githubusercontent.com/messari/skills/master/SKILL.md) | Self-contained skill file for the Messari REST API: endpoints, auth and routing in one file. |

## Building on the API

| Surface | What it is for |
| --- | --- |
| **Data API** | REST access to every dataset and metric series. The same data the MCP server reads. |
| **Monitoring API** | Events, webhooks, and Telegram alerts for the things your product reacts to. |

```bash
curl 'https://api.blockworks.com/query/tabular/assets?pageSize=5' \
  -H "X-Blockworks-API-Key: $BLOCKWORKS_API_KEY"
```

## Messari repositories

Messari's open-source work is moving into this organization. Until each transfer lands, the existing URLs below keep working and will redirect once a repository moves.

| Repository | What it is |
| --- | --- |
| [messari/subgraphs](https://github.com/messari/subgraphs) | Standardized subgraphs for DeFi protocol data on The Graph. |
| [messari/skills](https://github.com/messari/skills) | Agent-native skill files for the Messari REST API. |
| [messari/cookbooks](https://github.com/messari/cookbooks) | Python examples and guides for the Messari API. |

<br>

<p align="center">
  <sub><a href="https://blockworks.com">blockworks.com</a> · <a href="https://docs.blockworks.com">docs.blockworks.com</a></sub>
</p>
