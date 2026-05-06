# ultimatehtmlviewer

> - Run all Node-based commands for this repository with Node `22.14.0`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ultimatehtmlviewer/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Node Runtime Requirement

- Run all Node-based commands for this repository with Node `22.14.0`.
- Do not use system Node `24.x` for `npm`, `gulp`, lint, test, or build steps.

## Command Wrapper

- Use this wrapper for local and agent execution:
  - `npx -y -p node@22.14.0 -c "<command>"`
- Examples:
  - `npx -y -p node@22.14.0 -c "node -v"`
  - `npx -y -p node@22.14.0 -c "cd spfx/UniversalHtmlViewer && npm test -- --runInBand"`
  - `npx -y -p node@22.14.0 -c "cd spfx/UniversalHtmlViewer && npm run build"`

---
> Source: [EvotecIT/UltimateHtmlViewer](https://github.com/EvotecIT/UltimateHtmlViewer) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
