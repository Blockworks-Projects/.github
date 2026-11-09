<p align="center">
  <a href="https://blockworks.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="blockworks-dark.svg">
      <img alt="Blockworks" src="blockworks-light.svg" width="360">
    </picture>
  </a>
</p>

<h3 align="center">The data layer for onchain finance.</h3>

<p align="center">
  Market data, onchain metrics, and research for businesses that build on crypto.<br>
  One dataset, delivered as an API, an MCP server, a Snowflake share, and spreadsheet plugins.
</p>

<p align="center">
  <a href="https://docs.blockworks.com">Docs</a>
  &nbsp;·&nbsp;
  <a href="https://app.blockworks.com/account/api">Get an API key</a>
  &nbsp;·&nbsp;
  <a href="https://mcp.blockworks.com/mcp">MCP server</a>
  &nbsp;·&nbsp;
  <a href="https://blockworks.com/contact">Talk to us</a>
</p>

<br>

## What we build

| Surface | What it is for |
| --- | --- |
| **Data API** | REST access to prices, TVL, fees, revenue, fundraising, token unlocks, and thousands of metric timeseries. |
| **Monitoring API** | Event feeds for the things your product needs to react to. |
| **MCP server** | A hosted Model Context Protocol server. Give Claude, Cursor, ChatGPT, or your own agents direct access to Blockworks data. |
| **Snowflake Datashare** | The full dataset, live in your warehouse. No pipelines to maintain. |
| **Spreadsheets** | Blockworks data as formulas in Excel and Google Sheets. |
| **Research** | Institutional-grade reports, diligence, and quarterly reviews from the Blockworks research team. |

## Thirty seconds to data

```bash
curl https://api.blockworks.com/v1/metrics/active-address-total \
  -H "X-Blockworks-API-Key: $BLOCKWORKS_API_KEY"
```

Or skip the code entirely. Add the MCP server to any client that speaks remote MCP and start asking questions:

```
https://mcp.blockworks.com/mcp
```

Everything you need to go further is at [docs.blockworks.com](https://docs.blockworks.com).

## Open source

The repositories here are the pieces we think are worth sharing: SDKs, agent skills, plugins, and tooling built around the Blockworks platform. Issues and pull requests are welcome.

<br>

<p align="center">
  <sub>Blockworks · New York · <a href="https://blockworks.com">blockworks.com</a></sub>
</p>
