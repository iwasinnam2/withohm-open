# cursor-agent-with-web

**Compliant fetch for agents** — clone this, set one key, Cursor can pull public docs into context.

No sales call. Steal the skeleton.

## Clone → set key → fetch

```bash
git clone https://github.com/iwasinnam2/ohm.git
cd ohm/templates/cursor-agent-with-web
```

1. Get a free Intermediate seat (card on file, $0 membership): https://www.withohm.dev/subscriptions  
   Or open the one-liner install: https://www.withohm.dev/i
2. Copy `.cursor/mcp.json.example` → your Cursor MCP config (or merge into project `.cursor/mcp.json`).
3. Set `OHM_API_KEY` to your `sk-at-…` key. Optional: `OHM_UPSTREAM_KEY` for BYOK model calls.
4. In Cursor chat: ask the agent to fetch a public docs URL.

Paste this to a teammate:

```text
Add withOhm MCP from https://www.withohm.dev/i
```

## What’s inside

| Path | Role |
|------|------|
| `.cursor/mcp.json.example` | Ohm MCP (`ohm_fetch_web`, `ohm_chat`, `ohm_usage`) |
| `.cursor/skills/ohm-fetch-web/SKILL.md` | Skill: compliant fetch for agents |
| `AGENTS.md` | One-screen agent instructions |

## Show your savings

Once cache hits accrue, ask the agent for `ohm_receipt` — it mints a public
savings receipt and returns badge markdown like:

```markdown
[![withOhm savings](https://img.shields.io/endpoint?url=https%3A%2F%2Fapi.withohm.dev%2Fv1%2Fpublic%2Freceipts%2F<token>%2Fbadge)](https://www.withohm.dev/r/<token>)
```

Paste it here (or in any repo on the pipe). Sharing a receipt qualifies for
the [$100 artifact bounty](https://www.withohm.dev/bounty) (post your receipt
publicly, then email the social post URL).

Powered by [withOhm](https://www.withohm.dev) — pipe rent, not token wholesale. BYOK.
