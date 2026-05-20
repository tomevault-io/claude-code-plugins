# jottr

> Before doing substantial work, use MemPalace MCP to retrieve relevant memory for:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/jottr/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Codex instructions for this repo

Before doing substantial work, use MemPalace MCP to retrieve relevant memory for:
- project architecture
- coding conventions
- setup and test commands
- previous decisions
- known bugs and TODOs

Do not rely only on memory. After retrieving MemPalace context, verify it against the current repository files.

For implementation tasks:
1. Query MemPalace for relevant context.
2. Inspect the current code.
3. Explain the plan briefly.
4. Make minimal changes.
5. Run relevant tests or explain why they were not run.

---
> Source: [mfat/jottr](https://github.com/mfat/jottr) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
