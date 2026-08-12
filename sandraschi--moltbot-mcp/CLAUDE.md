# moltbot-mcp

> You have access to the Moltbot (ClawdBot) Gateway via MCP tools.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/moltbot-mcp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Session Context (Moltbot MCP)

You have access to the Moltbot (ClawdBot) Gateway via MCP tools.

**Before starting work:**
1. Check gateway status: `moltbot_ops(operation="status")`
2. List available operations: `help(level="basic")`

**At end of work:**
- Send any pending messages via the gateway.

---
> Source: [sandraschi/moltbot-mcp](https://github.com/sandraschi/moltbot-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-12 -->
