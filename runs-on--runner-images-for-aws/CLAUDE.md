# runner-images-for-aws

> Use `.github/workflows/reproductions.yml` to capture issue-specific reproductions.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/runner-images-for-aws/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agents Guide

## Reproduction workflows

Use `.github/workflows/reproductions.yml` to capture issue-specific reproductions.

- Create one job per issue.
- Specify the RunsOn runner label in `runs-on`, for example:
  - `runs-on=${{ github.run_id }}/runner=2cpu-linux-arm64` (RunsOn custom runner syntax; see https://runs-on.com)

## Generated releases

- Treat `releases/` as generated output from the build/sync scripts.
- Do not commit `releases/` changes unless the user explicitly asks for them.

---
> Source: [runs-on/runner-images-for-aws](https://github.com/runs-on/runner-images-for-aws) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-01 -->
