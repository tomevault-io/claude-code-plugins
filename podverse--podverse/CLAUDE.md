# plan-lifecycle

> Plan lifecycle management - moving completed plans

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/plan-lifecycle/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Plan Lifecycle

When you finish executing a plan in `active/`, move it to `completed/` automatically (no prompt).
See **Plan Completion** skill for: single-file move vs. moving the whole set when it's the last plan.

1. Move the file (or whole set) from `active/` to `completed/` (preserving subdirectory structure)
2. Update any references in `00-master-plan.md`, a project `00-SUMMARY.md`, or `.llm/LLM.md` if needed

Example:

```bash
mv .llm/plans/active/monorepo-migration/02-packages-outline.md \
   .llm/plans/completed/monorepo-migration/
```

---
> Source: [podverse/podverse](https://github.com/podverse/podverse) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-05 -->
