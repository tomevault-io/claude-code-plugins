# llm-council

> <!-- lean-ctx-rules -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/llm-council/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<!-- lean-ctx-rules -->
<!-- version: 1 -->

# lean-ctx

MANDATORY MAPPING:
• Read/cat -> ctx_read(path, mode)
• Glob/find -> ctx_glob(pattern)
• Shell/bash -> ctx_shell(command)
• Grep -> ctx_search(pattern, path)
• ls/find -> ctx_tree(path, depth)

NEVER use native Read/Grep/Shell/Glob when ctx_* equivalents are available.
Full rules: ~/.cursor/rules/lean-ctx.mdc (auto-loaded) — do not duplicate here.
<!-- /lean-ctx-rules -->

---
> Source: [ToolmanData/llm-council](https://github.com/ToolmanData/llm-council) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-20 -->
