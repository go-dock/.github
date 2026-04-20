<div align="center">

### [trydock.ai →](https://trydock.ai)

<img src="./dock-logo.png" width="180" alt="Dock logo" />

# Dock

**The AI workspace for you, your team, and every agent you run.**

A shared cloud workspace where humans and agents read + write the same state in real time. Tables (typed columns) and rich-text docs, with agents as first-class identities — their own API keys, their own audit trail, no delegated human tokens.

[trydock.ai](https://trydock.ai) · [Docs](https://trydock.ai/docs) · [MCP](https://trydock.ai/docs/mcp) · [Pricing](https://trydock.ai/pricing)

</div>

---

## Open source under this org

| Repo | What it is |
|---|---|
| [`@go-dock/cli`](https://github.com/go-dock/cli) | One-binary CLI that wraps the REST API. Auth via OAuth + PKCE; `dock init` creates a workspace + hands you the MCP endpoint to point Claude / Cursor / Continue at. |
| [`@go-dock/mcp`](https://github.com/go-dock/mcp) | Local stdio MCP bridge to Dock. Drop into Claude Desktop, Cursor, Windsurf, Zed, Cline, or Continue. |
| [`@go-dock/examples`](https://github.com/go-dock/examples) | Reference integrations — deployable glue code for real workflows (row → GitHub issue, doc → CMS, etc). |

## Get started in one command

```bash
npx @go-dock/cli init
```

Browser opens, you sign in, a workspace is created, you get back a URL plus an MCP endpoint you can hand to any agent. That's the whole onboarding.

## Why agents-first

Most workspace tools were built for humans, with agents bolted on as a second-class API integration. Dock inverts that: every agent is a real member of every workspace it touches, with its own role, its own keys, and its own contribution history. The same row updates show up in your dashboard whether a teammate or a Claude run made them — no "[bot]" prefix, no shadow service account.

## License

Each repo carries its own license — most are MIT.

## Company

Built by [Vector Apps Inc.](https://vector.build).
Reach us: [hello@trydock.ai](mailto:hello@trydock.ai)
