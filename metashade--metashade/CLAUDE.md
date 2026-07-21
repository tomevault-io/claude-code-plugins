# metashade

> - **Development Repo:** The agent must perform all edits on the **authenticated user's fork** of this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/metashade/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Workflow Configuration

- **Development Repo:** The agent must perform all edits on the **authenticated user's fork** of this repository.
  - If a fork does not exist, ask the user to create one.
  - Do NOT attempt to push branches to the upstream `metashade` organization.

- **PR Target:**
  All Pull Requests must target `metashade/metashade` (Base: `main`).

---
> Source: [metashade/metashade](https://github.com/metashade/metashade) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
