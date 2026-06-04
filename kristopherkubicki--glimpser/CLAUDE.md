# glimpser

> Keep commits small and focused.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/glimpser/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Keep commits small and focused.
Use conventional commit messages.
Format code with `black` and/or `prettier`
Run `flake8` for lint checks.
Run `pre-commit run --all-files`.
Run tests with `pytest`.
Use `pyproject.toml` for dependencies; do not use requirements files.
Use `npm test` for JavaScript changes.
Document major changes in `docs/`.
Summaries must cite changed files.
PR description must mention test results.
Explain complex logic in comments.
Each PR should have a single purpose.
Subdirectory `AGENTS.md` files must be no more than 10 lines.

---
> Source: [KristopherKubicki/glimpser](https://github.com/KristopherKubicki/glimpser) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-04 -->
