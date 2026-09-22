# sparkdiffusion

> This repository ships reusable agent skills under `.agents/skills/`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sparkdiffusion/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Workflow

This repository ships reusable agent skills under `.agents/skills/`.

- Use `sparkdiffusion-setup` for environment, path, dependency, and preflight work.
- Use `sparkdiffusion-finetune` for sparse finetuning.
- Use `sparkdiffusion-distill` for few-step distillation.
- Use `sparkdiffusion-inference` for T2V/I2V generation and checkpoint comparisons.

Read the relevant skill before running a GPU job. Prefer the existing launchers over hand-written commands, use repository-relative paths or environment variables, and do not modify model/data assets in the source tree.

---
> Source: [AlibabaResearch/SparkDiffusion](https://github.com/AlibabaResearch/SparkDiffusion) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-22 -->
