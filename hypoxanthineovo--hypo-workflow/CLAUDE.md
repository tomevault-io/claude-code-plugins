# hypo-workflow

> This file is Hypo-Workflow managed. Edit the source Hypo-Workflow rules/config when possible, then regenerate adapters with `hypo-workflow sync --platform opencode`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/hypo-workflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Hypo-Workflow managed OpenCode instructions

This file is Hypo-Workflow managed. Edit the source Hypo-Workflow rules/config when possible, then regenerate adapters with `hypo-workflow sync --platform opencode`.

## Runtime contract

- Hypo-Workflow is not a runner.
- The OpenCode Agent performs the actual work.
- `.pipeline/` remains the source of truth for state, Cycle, Patch, rules, PROGRESS, logs, prompts, and reports.
- Use `question` for required user decisions.
- Use `todowrite` for visible plan discipline, especially in `/hw-plan*` commands.

## Protected files

Treat `.pipeline/state.yaml`, `.pipeline/cycle.yaml`, and `.pipeline/rules.yaml` as protected. Unexpected writes should be blocked or require explicit user confirmation.

---
> Source: [HypoxanthineOvO/Hypo-Workflow](https://github.com/HypoxanthineOvO/Hypo-Workflow) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-30 -->
