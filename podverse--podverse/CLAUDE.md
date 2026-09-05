# llm-cursor-source

> AI guidance source of truth is under .cursor and .cursorrules

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/llm-cursor-source/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# LLM / Cursor source of truth

Committed **authoring** guidance for this repo lives only in:

- `.cursor/skills/**`
- `.cursor/rules/**`
- `.cursor/prompts/**`
- `.cursor/hooks/**` and `.cursor/hooks.json` (when present)
- `.cursorrules`
- `.cursorignore`

When you change AI guidance, commit and push only those **source** paths.

Contributor policy: [docs/development/llm/DOCS-DEVELOPMENT-LLM.md](docs/development/llm/DOCS-DEVELOPMENT-LLM.md).

---
> Source: [podverse/podverse](https://github.com/podverse/podverse) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-05 -->
