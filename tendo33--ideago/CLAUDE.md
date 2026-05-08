# python-tooling-standards

> Standards for using modern Python tooling including uv, ruff, and pre-commit hooks.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/python-tooling-standards/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- Use uv for package management and dependency resolution (faster than pip).
- Run uv sync to install dependencies; use uv add/remove for package management.
- Use ruff for both linting and formatting (replaces black, flake8, isort).
- Configure ruff in pyproject.toml with appropriate rules enabled.
- Run ruff format for code formatting; run ruff check for linting.
- Enable automatic fixes with ruff check --fix when appropriate.
- Use pre-commit hooks to enforce code quality before commits.
- Configure pre-commit with ruff, type checking, and other quality checks.
- Run pre-commit install after cloning the project.
- Keep pyproject.toml as the single source of configuration.
- Use hatchling as the build backend for package distribution.
- Define all dependencies in pyproject.toml [project.dependencies].
- Use optional dependencies for dev, test, docs groups.
- Keep uv.lock in version control for reproducible builds.
- Update dependencies regularly with uv lock --upgrade.

---
> Source: [Tendo33/IdeaGo](https://github.com/Tendo33/IdeaGo) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
