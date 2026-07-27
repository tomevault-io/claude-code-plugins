# wize-shard-doc

> core skill: Shard Doc

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wize-shard-doc/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Shard Doc

# Shard Doc

Splits large markdown (PRD, architecture, etc.) into addressable shards under `{doc-name}.shards/`.

## Why
Agents quote shards by id (`prd.shards/AC-5.md`) instead of pulling the whole document.

## Behavior
- Splits at headings (`##` by default; configurable).
- Each shard gets `id` from heading slug + frontmatter.
- Original doc becomes the index.

---
> Source: [qwize-br/wize-development-kit](https://github.com/qwize-br/wize-development-kit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
