# drippu

> Workspace instructions for GitHub Copilot to assist with repository automation, GitHub Actions, and agentic workflow setup.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/drippu/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# GitHub Actions and Agentic Workflow Instructions

When editing this repository, use the following conventions for GitHub Actions and agentic workflows:

- Prefer creating or updating workflow files in `.github/workflows/`.
- Use `workflow_dispatch` for workflows that should run manually.
- Use `pull_request` and `push` triggers for CI validation on branches.
- Keep YAML syntax valid and avoid unrelated source changes.
- If asked to set up agentic workflows, create or update `.github/agents/` and `.github/AGENTS.md` to expose available agent definitions.
- When the task mentions `gh aw` or GitHub Actions workflow guidance, focus on workflow file structure, jobs, and steps.

---
> Source: [suyu-emu/drippu](https://github.com/suyu-emu/drippu) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-22 -->
