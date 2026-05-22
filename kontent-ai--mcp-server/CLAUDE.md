# mcp-tool-naming

> Enforce naming conventions for Kontent.ai MCP tools

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mcp-tool-naming/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When creating or modifying MCP tools, follow these naming conventions:

- Format: `[action]-[entity]`
- Use full entity names: `content-type`, `content-type-snippet`, `content-item`, `content-item-variant`, `taxonomy-group`
- For list tools filtered by another entity: `list-[entity]-by-[filter-entity]` (e.g., `list-content-item-variants-by-collection`)
- Examples: `get-content-type`, `list-content-item-variants`, `patch-content-type-snippet`

---
> Source: [kontent-ai/mcp-server](https://github.com/kontent-ai/mcp-server) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
