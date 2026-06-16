# json-no-pretty-print

> Do not pretty-print JSON by default for machine or LLM consumption

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/json-no-pretty-print/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# JSON output (no pretty-print by default)

When emitting JSON for **scripts, tools, MCP, or any path where output is consumed by programs or LLMs** (not a human reading a terminal for debugging):

- Use **`JSON.stringify(value)`** only — do **not** use `JSON.stringify(value, null, 2)` or other spacing/indent by default.
- Extra newlines and indentation are **token cost** for models and add no parsing benefit.

---
> Source: [Jamie-BitFlight/claude_skills](https://github.com/Jamie-BitFlight/claude_skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
