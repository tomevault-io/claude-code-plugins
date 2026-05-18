# mujoco-lidar

> - Use `uv run <command>` for all Python execution. Never use `python` or `python3` directly.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mujoco-lidar/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# MuJoCo-LiDAR Project Instructions

## Commands

- Use `uv run <command>` for all Python execution. Never use `python` or `python3` directly.

## Code Rules

- Write minimum code. No extra features, no "nice-to-haves"
- Delete unused code immediately. Never comment out — delete
- Fix poor design before adding features
- No defensive code for impossible scenarios
- No abstractions for single-use cases
- No error handling for internal code paths
- Prefer testability over debuggability

Performance matters: this is GPU-intensive research code.

## Git

Conventional Commits: `feat:` / `fix:` / `docs:` / `style:` / `refactor:` / `test:` / `chore:`

- Commit often, keep history clean
- Never commit to main — always work on feature branches
- Delete feature branches after PR merge

---
> Source: [discoverse-dev/MuJoCo-LiDAR](https://github.com/discoverse-dev/MuJoCo-LiDAR) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
