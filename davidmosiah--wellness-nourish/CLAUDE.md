# wellness-nourish

> This repo is the local-first Nourish MCP server for nutrition search, barcode lookup, intake logging, hydration and meal summaries.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wellness-nourish/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Development Notes

## Scope

This repo is the local-first Nourish MCP server for nutrition search, barcode lookup, intake logging, hydration and meal summaries.

## Commands

- Install: `npm ci`
- Typecheck: `npm run typecheck`
- Build: `npm run build`
- HTTP smoke: `npm run smoke:http`
- Metadata check: `npm run test:metadata`
- Full gate: `npm test`

## Rules

- Never commit user food logs, photos, generated local stores, API keys, or private health context.
- Keep fixture mode available for CI and agent verification.
- Preserve pt-BR quantity parsing and explicit gram/unit behavior.
- Preserve agent-ready surfaces: manifest, connection status, privacy audit, CLI UX, Hermes agent manifest, and metadata checks.
- Keep nutrition outputs informational, not medical advice.

---
> Source: [davidmosiah/wellness-nourish](https://github.com/davidmosiah/wellness-nourish) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-06 -->
