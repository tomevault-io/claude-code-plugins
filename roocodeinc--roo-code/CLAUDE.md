# roo-code

> This file provides guidance to agents when working with code in this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/roo-code/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

This file provides guidance to agents when working with code in this repository.

- Settings View Pattern: When working on `SettingsView`, inputs must bind to the local `cachedState`, NOT the live `useExtensionState()`. The `cachedState` acts as a buffer for user edits, isolating them from the `ContextProxy` source-of-truth until the user explicitly clicks "Save". Wiring inputs directly to the live state causes race conditions.

---
> Source: [RooCodeInc/Roo-Code](https://github.com/RooCodeInc/Roo-Code) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-31 -->
