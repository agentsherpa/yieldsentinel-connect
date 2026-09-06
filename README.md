# yieldsentinel-connect

Public front door for [yieldsentinel.eth](https://app.ens.domains/yieldsentinel.eth).

Policy check on one described position. Research only. Not a deposit or exit order. ERC-8004 on Base: **63771**.

The full agent stays in a private repo. This repo only points at the live service.

## Sibling

Ranks first via [yieldhunter-connect](https://github.com/agentsherpa/yieldhunter-connect) / [yieldhunter.eth](https://app.ens.domains/yieldhunter.eth) (Base **61006**, not RNWY Ethereum 12099).

No auto-sync between the two.

## Live URLs

- Front door: https://yieldsentinel-agent-production.up.railway.app/
- MCP: https://yieldsentinel-agent-production.up.railway.app/mcp
- Live agent card: https://yieldsentinel-agent-production.up.railway.app/.well-known/agent-card.json

## Connect snippet

See `connect.json`. Paste that block into an MCP client that accepts a remote URL.

## Agent Plugin (Cursor / Grok marketplace)

This repo is also an [Agent Plugins](https://agent-plugins.org/) package:

- `plugin.json` — manifest
- `mcp.json` — remote Streamable HTTP MCP
- `LICENSE` — MIT

**Marketplace note (approval risk):** this is DeFi / stablecoin **research** policy checking for agents. It never custodies funds, never executes, never auto-exits. Curated marketplaces may still reject or delay listings that touch yield/DeFi topics. Research only — not a deposit or exit order.

One-liner: Risk-adjusted ranks, then a policy check. Research only.

## Files

- `connect.json` — MCP connect snippet
- `agent-card.json` — thin pointer (not the live tool list)
- `plugin.json` — Agent Plugins manifest
- `mcp.json` — Agent Plugins MCP config
- `LICENSE` — MIT
- `README.md` — this file
