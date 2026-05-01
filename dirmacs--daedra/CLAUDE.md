# daedra

> Daedra is a web search MCP server. It provides search tools to AI agents via MCP (Model Context Protocol). Multiple backends with automatic fallback ensure search always works.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/daedra/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# daedra — Agent Guidelines

## What This Is

Daedra is a web search MCP server. It provides search tools to AI agents via MCP (Model Context Protocol). Multiple backends with automatic fallback ensure search always works.

## For Agents

- Run `cargo test` before any changes
- The search fallback chain is the core value — don't break backend ordering
- Each backend is independent — adding a new one shouldn't affect others
- MCP tools are defined in `src/tools/` — follow the existing pattern
- Caching is transparent — backends don't know about the cache layer
- No hardcoded paths or API keys in source code

---
> Source: [dirmacs/daedra](https://github.com/dirmacs/daedra) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-25 -->
