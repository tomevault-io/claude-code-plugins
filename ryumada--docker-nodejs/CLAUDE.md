# docker-nodejs

> Instructions for Cline agents to read and follow all .agents repository content

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/docker-nodejs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Agent Instructions

## Required Protocol
1. **Identify Task Layer**: Determine if the task is **Infrastructure** (Docker, Bash) or **Application** (React, Next.js).
2. **Load Targeted Context**: Read only the maps and rules relevant to your active layer (see `.agents/rules/how-to-scan-repository.md`).
3. **Follow Standard Rules**: All active instructions reside in the `.agents/rules/` directory.

## Core Checklist
- [ ] 5-Line Signatures mandatory for all files.
- [ ] No browser testing (use logs and build status).
- [ ] Use `./scripts/bootstraping/run.sh` for npm commands.
- [ ] For design rules see `.agents/skills/frontend-design/SKILL.md`.

Refer to `.agents/rules/` for detailed protocol enforcement.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/ryumada)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/ryumada)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
