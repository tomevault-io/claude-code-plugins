# speq-skill

> @CLAUDE.md contains the shared local development rules for both Claude Code and Codex contributors.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/speq-skill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project
Read @CLAUDE.md

@CLAUDE.md contains the shared local development rules for both Claude Code and Codex contributors.

# Commit Conventions

The commit message SHALL be structured like this:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

Use conventional commits types:

- `feat:` for new features (correlates with MINOR in Semantic Versioning)
- `fix:` for bug fixes (correlates with PATCH in Semantic Versioning)
- `perf:` for performance improvements
- `refactor:` for code restructuring
- `test:` for test additions/changes
- `docs:` for documentation
- `spec:` for spec changes
- `chore:` for maintenance tasks

BREAKING CHANGE: a commit that has a footer BREAKING CHANGE:, or appends a ! after the type/scope, introduces a breaking API change (correlating with MAJOR in Semantic Versioning). A BREAKING CHANGE can be part of commits of any type.

---
> Source: [marconae/speq-skill](https://github.com/marconae/speq-skill) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-09 -->
