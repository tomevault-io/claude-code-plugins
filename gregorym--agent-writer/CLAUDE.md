# agent-writer

> - Do not use console.log

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent-writer/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project coding standards

## General guidelines

- Do not use console.log
- Do not add comments unless explicitly asked

# TRPC React guidelines

- Never use query and mutation callbacks (onSuccess , onError)
- Handle success and error states inside a handle where the mutation is called from

---
> Source: [gregorym/agent-writer](https://github.com/gregorym/agent-writer) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-31 -->
