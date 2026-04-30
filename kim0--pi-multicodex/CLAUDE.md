# pi-multicodex

> Only edit files in this directory:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pi-multicodex/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# MultiCodex Extension - Agent Notes

## Scope

Only edit files in this directory:

```
~/.pi/agent/extensions/multicodex/
```

## Goals

- Keep the extension runnable when installed outside the pi monorepo.
- Avoid deep imports that resolve to repo-local paths.
- Keep runtime behavior compatible with pi extension docs.

## Type Safety

- Use public exports from `@mariozechner/pi-ai` and `@mariozechner/pi-coding-agent`.
- The local `pi-coding-agent.d.ts` module augmentation is for TypeScript only and must stay minimal.

## Checks

Run:

```bash
npm run lint
npm run tsgo
npm run test
```

---
> Source: [kim0/pi-multicodex](https://github.com/kim0/pi-multicodex) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-25 -->
