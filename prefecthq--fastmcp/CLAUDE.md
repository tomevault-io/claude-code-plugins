# core-mcp-objects

> There are four major MCP object types:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/core-mcp-objects/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

There are four major MCP object types:

- Tools (src/tools/)
- Resources (src/resources/)
- Resource Templates (src/resources/)
- Prompts (src/prompts)

While these have slightly different semantics and implementations, in general changes that affect interactions with any one (like adding tags, importing, etc.) will need to be adopted, applied, and tested on all others. Note that while resources and resource templates are different objects, they are both in `src/resources/`.

---
> Source: [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
