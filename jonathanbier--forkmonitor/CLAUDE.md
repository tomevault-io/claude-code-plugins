# forkmonitor

> - Trailer for commit messages:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/forkmonitor/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidelines

- Trailer for commit messages:
  - Assisted-by: GitHub Copilot
  - Assisted-by: OpenAI GPT-5-Codex
- When making changes to Ruby files, run `bundle exec rubocop` before committing.
- Review additional project practices in `DEVELOPMENT.md`.
- `bundle exec rake` (full Rails test suite) takes a long time; prefer running the smallest relevant spec(s). If you truly need the full suite, use the parallel workflow from `DEVELOPMENT.md` (`bundle exec rake parallel:create parallel:prepare parallel:spec`).

---
> Source: [jonathanbier/forkmonitor](https://github.com/jonathanbier/forkmonitor) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
