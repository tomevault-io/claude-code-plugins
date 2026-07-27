# difftest

> Before working under `difftest/`, determine whether the task is a potentially complex, multi-file change or requires iterative testing/debugging. If so, review the relevant files in `difftest/docs/` as needed before proceeding.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/difftest/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Difftest Working Guidelines

Before working under `difftest/`, determine whether the task is a potentially complex, multi-file change or requires iterative testing/debugging. If so, review the relevant files in `difftest/docs/` as needed before proceeding.

For complex tasks, follow the plan/progress workflow defined in [`difftest/docs/workflow.md`](docs/workflow.md): create a plan, create a progress log, execute in phases, and use `askQuestions` to confirm ambiguities and end-of-conversation next steps.

---
> Source: [OpenXiangShan/difftest](https://github.com/OpenXiangShan/difftest) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
