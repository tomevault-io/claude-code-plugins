# opencode-dotfiles

> Use Perplexity MCP tools for search, research, and reasoning tasks.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/opencode-dotfiles/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## PERPLEXITY-MCP-START

Use Perplexity MCP tools for search, research, and reasoning tasks.

Available tools:
- `perplexity_search` - Quick web search with citations
- `perplexity_ask` - Synthesized answers (mode: concise/copilot)
- `perplexity_reason` - Multi-step reasoning
- `perplexity_research` - Deep research reports
- `perplexity_compute` - Computer/ASI mode for complex computations

Sources: `web` (default), `scholar`, `social`

Examples:
- "Search scholar sources for recent RAG evaluation papers" → `perplexity_search` with `sources: ["scholar"]`
- "What are developers saying about Cursor vs Windsurf?" → `perplexity_ask` with `sources: ["social"]`
- "Deep research on code review automation" → `perplexity_research` with `sources: ["scholar", "web"]`

## PERPLEXITY-MCP-END

---
> Source: [cinicu/opencode-dotfiles](https://github.com/cinicu/opencode-dotfiles) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-13 -->
