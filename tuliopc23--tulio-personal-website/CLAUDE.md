# tulio-personal-website

> This repo may also have `AGENTS.md` or other repo-local guidance. Follow those stronger repo-specific rules first.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tulio-personal-website/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# context-mode routing

This repo may also have `AGENTS.md` or other repo-local guidance. Follow those stronger repo-specific rules first.

When `context-mode` MCP tools are available in Gemini or Antigravity, use them for large-output analysis and indexed retrieval.

- Prefer `mcp__context-mode__ctx_batch_execute`, `mcp__context-mode__ctx_search`, `mcp__context-mode__ctx_execute`, and `mcp__context-mode__ctx_execute_file`.
- Avoid `curl`, `wget`, long raw shell output, and direct large web fetches when `context-mode` can keep data in the sandbox.
- Keep native editor tools for file writes. Do not use `context-mode` execution tools to write files.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/tuliopc23)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/tuliopc23)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
