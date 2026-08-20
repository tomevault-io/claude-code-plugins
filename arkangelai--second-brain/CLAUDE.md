# second-brain

> Second Brain is a local-first, AI-native knowledge management CLI built around markdown files, hybrid search, and agent-assisted workflows.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/second-brain/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Purpose

Second Brain is a local-first, AI-native knowledge management CLI built around markdown files, hybrid search, and agent-assisted workflows.

## Stack

- Bun
- TypeScript
- CLI tooling
- Markdown vault

## Important Paths

- `bin/`: CLI entrypoints
- `src/`: implementation code
- `tools/`: helper tooling
- `vault/`: knowledge vault; see `vault/AGENTS.md` for vault-specific operating guidance

## Common Commands

- `bun install`
- `bun run dev`
- `bun test`
- `bun run typecheck`

## Agent Notes

- Preserve the local-first design and plain-text workflow.
- Be careful when changing CLI behavior because agent workflows may depend on stable commands.
- Keep changes compatible with markdown-based vault usage.

---
> Source: [arkangelai/second-brain](https://github.com/arkangelai/second-brain) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-20 -->
