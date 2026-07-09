# konfai

> Follow the canonical repository instructions in `AGENTS.md`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/konfai/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# KonfAI — GitHub Copilot Instructions

Follow the canonical repository instructions in `AGENTS.md`.

- Never commit directly to `main`; always use a focused feature branch.
- Keep each diff small and open a pull request for review.
- Do not merge your own pull request.
- Use Conventional Commits.
- Never include Maestro, Claude, Codex, generated-by/generated-with text, or AI co-author branding in commit messages.
- Run `pixi run format`, `pixi run check`, and relevant pre-commit hooks before finalising.
- Do not introduce dependencies silently or load complete medical imaging datasets into RAM.

---
> Source: [fideus-labs/KonfAI](https://github.com/fideus-labs/KonfAI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-09 -->
