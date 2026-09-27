# ada-03-context-engineering

> - Inspect the repository before editing.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ada-03-context-engineering/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions
- Inspect the repository before editing.
- Prefer the smallest safe change.
- Do not modify tests unless explicitly requested.
- Preserve public interfaces unless necessary.
- Do not add dependencies unless necessary.
- Preserve customer identity and audit information.
## Validation
- Run pytest before implementation.
- Run pytest after implementation.
- Diagnose failures before making additional changes.
- Report what changed and what was verified.
## Quality Gate
The task is complete only when relevant tests pass and SPEC.md is satisfied.

---
> Source: [XxCharlyRuzxX/ada-03-context-engineering](https://github.com/XxCharlyRuzxX/ada-03-context-engineering) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-24 -->
