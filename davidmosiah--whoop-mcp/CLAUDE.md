# whoop-mcp

> This repo is the unofficial WHOOP MCP connector for local recovery, sleep, strain and HRV agents.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/whoop-mcp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Development Notes

## Scope

This repo is the unofficial WHOOP MCP connector for local recovery, sleep, strain and HRV agents.

## Commands

- Install: `npm ci`
- Typecheck: `npm run typecheck`
- Build: `npm run build`
- Fast smoke: `npm run smoke`
- HTTP smoke: `npm run smoke:http`
- Full gate: `npm test`

## Rules

- Never commit OAuth client secrets, access tokens, refresh tokens, personal WHOOP data, or local config.
- Keep read-only behavior and privacy-safe summaries as the default.
- Preserve agent-ready surfaces: manifest, connection status, privacy audit, CLI UX, Hermes agent manifest, and metadata checks.
- Keep recovery/coaching language clearly non-medical.

---
> Source: [davidmosiah/whoop-mcp](https://github.com/davidmosiah/whoop-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-17 -->
