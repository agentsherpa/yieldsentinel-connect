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

## Files

- `connect.json` — MCP connect snippet
- `agent-card.json` — thin pointer (not the live tool list)
- `README.md` — this file
