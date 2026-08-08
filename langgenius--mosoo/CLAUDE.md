# mosoo

> - Follow `CONTRIBUTING.md` for setup, development, verification, generated files, Git/PR, migrations, and deployment.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mosoo/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

- Follow `CONTRIBUTING.md` for setup, development, verification, generated files, Git/PR, migrations, and deployment.
- For product behavior or module-boundary changes, read only the relevant PRD and architecture sections before editing.
- Production D1 is append-only: never reset production or rewrite an applied migration; follow `CONTRIBUTING.md#database-and-migrations` and `docs/production-deploy-verification.md`.
- Destructive or data-rewrite migrations require explicit user approval plus a backup and rollback plan.

---
> Source: [langgenius/mosoo](https://github.com/langgenius/mosoo) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-08 -->
