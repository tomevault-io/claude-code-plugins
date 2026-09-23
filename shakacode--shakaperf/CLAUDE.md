# shakaperf

> If facing issues in node, run `nvm use` in the repository root to activate the Node.js version specified by the project.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/shakaperf/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

NO-CI

If facing issues in node, run `nvm use` in the repository root to activate the Node.js version specified by the project.

## Agent Workflow Configuration

Portable shared skills resolve this repo's commands and policy through:
- **Commands** — run `.agents/bin/<name>` (`setup`, `validate`, `test`, ...); see `.agents/bin/README.md`. A missing script means that capability is n/a here.
- **Policy / config** — `.agents/agent-workflow.yml`.

---
> Source: [shakacode/shakaperf](https://github.com/shakacode/shakaperf) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
