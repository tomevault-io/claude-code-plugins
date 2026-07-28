# 21st-sdk

> Next.js integration for AN agent chat — server-side token handler so your API key never reaches the browser.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/21st-sdk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# @an-sdk/nextjs

Next.js integration for AN agent chat — server-side token handler so your API key never reaches the browser.

## Docs

Full documentation: `./docs/` directory (8 guides covering the entire AN platform).

## Source

Source code: `./src/` directory.

## Key Entry Points

- `src/index.ts` — Re-exports everything from `@an-sdk/react`
- `src/server.ts` — `exchangeToken()` and `createAnTokenHandler()` for Next.js API routes

## Two Entry Points

- `@an-sdk/nextjs` — Client-side: all React components from `@an-sdk/react`
- `@an-sdk/nextjs/server` — Server-side: token exchange (Node.js only)

---
> Source: [21st-dev/21st-sdk](https://github.com/21st-dev/21st-sdk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
