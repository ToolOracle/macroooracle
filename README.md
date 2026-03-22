# 📊 macrooOracle

**Financial Data MCP Server** — 8 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-8-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/macroo/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "macroooracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/macroo/mcp/"]
    }
  }
}
```

## Tools (8)

| Tool | Description |
|------|-------------|
| `fed_rates` | Federal Reserve interest rates, FOMC meeting calendar, policy outlook. |
| `inflation` | US inflation data: CPI, PCE, core inflation, year-over-year and month-over-month |
| `yield_curve` | US Treasury yield curve: all maturities (1M-30Y), 10Y-2Y spread, inversion signa |
| `labor_market` | US labor market: unemployment rate, nonfarm payrolls, wages, jobless claims, lab |
| `gdp_growth` | US GDP growth: quarterly and yearly, real GDP, consumer spending, recession risk |
| `housing` | US housing market: housing starts, permits, median prices, 30Y mortgage rates, h |
| `macro_dashboard` | Full US economic dashboard — all key indicators at once: Fed, inflation, yields, |
| `health_check` | Server status, API connectivity. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

macrooOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/macroo/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
