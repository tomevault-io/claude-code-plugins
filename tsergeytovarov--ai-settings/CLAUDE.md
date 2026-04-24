# ai-settings

> <!-- Gemini CLI entry point. Imports AGENTS.md — the source of truth. -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ai-settings/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GEMINI.md

<!-- Gemini CLI entry point. Imports AGENTS.md — the source of truth. -->

@./AGENTS.md

## Gemini CLI-specific notes

- Skills are activated via the `activate_skill` tool (see the platform-adaptation note in `superpowers:using-superpowers`).
- Skill metadata is loaded at session start; full skill content activates on demand.
- Tool-name equivalents: if a skill or doc references Claude tool names (`Skill`, `Agent`, `TodoWrite`), treat them as logical actions and use the Gemini CLI equivalent.

---
> Source: [tsergeytovarov/ai-settings](https://github.com/tsergeytovarov/ai-settings) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-24 -->
