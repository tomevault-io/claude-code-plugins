# gplugins

> We use [tbump](https://github.com/your-tools/tbump) with [towncrier](https://towncrier.readthedocs.io/) to manage version bumps and releases.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gplugins/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agents

## Releasing

We use [tbump](https://github.com/your-tools/tbump) with [towncrier](https://towncrier.readthedocs.io/) to manage version bumps and releases.

### Workflow

1. Add towncrier fragments to `.changelog.d/` named `<PR#>.<type>` where type is one of: `added`, `changed`, `fixed`, `removed`, `deprecated`, `security`
2. Run tbump which automatically: updates the version in `pyproject.toml`, `gplugins/__init__.py`, and `README.md`, runs towncrier to build the changelog, commits, and tags

```bash
tbump <version> --no-push
```

Use `--no-push` to review before pushing, or omit it to push automatically.

### Configuration

- tbump config: `pyproject.toml` under `[tool.tbump]`
- towncrier config: `pyproject.toml` under `[tool.towncrier]`
- changelog template: `.changelog.d/changelog_template.jinja`

---
> Source: [gdsfactory/gplugins](https://github.com/gdsfactory/gplugins) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
