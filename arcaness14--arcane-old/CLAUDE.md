# arcane-old

> <!-- SPDX-License-Identifier: LicenseRef-OpenSpace-AgentPrompts-Restricted -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/arcane-old/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<!-- SPDX-License-Identifier: LicenseRef-OpenSpace-AgentPrompts-Restricted -->

# Gemini Repo Instructions

Follow [AGENTS.md](AGENTS.md) as the primary repository instruction file for this SS14 fork.

Before editing:

- Read `.agents/rules/`
- Read every relevant skill under `.agents/skills/`
- Prefer the nearest subtree `AGENTS.md` when one exists for the touched files

Core expectations:

- Keep components data-only and behavior in systems.
- Use `On... -> Try... -> Can... -> Do...` for gameplay actions.
- Prefer `Entity<T?>`, `ProtoId<T>`, `EntProtoId`, and localized strings.
- Avoid `RobustToolbox/` edits unless engine work is explicitly required.
- Use prediction and localization as first-pass design constraints, not cleanup.

---
> Source: [ArcaneSS14/arcane-old](https://github.com/ArcaneSS14/arcane-old) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-06 -->
