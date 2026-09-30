# uikit

> - Use [Conventional Commits](https://www.conventionalcommits.org/) format for commit messages.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/uikit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

- Use [Conventional Commits](https://www.conventionalcommits.org/) format for commit messages.
- Follow [Keep a Changelog 1.1.0](https://keepachangelog.com/en/1.1.0/). Maintain a topmost
  `## WIP` section in `CHANGELOG.md`, before the latest versioned release.
  Add entries under non-empty `### Added`, `### Changed`, `### Deprecated`, `### Removed`,
  `### Fixed`, or `### Security` categories.
- Never commit generated `dist` files.
- Do not modify SCSS files; they are generated from the LESS source files. Make stylesheet changes in the corresponding LESS files instead.

---
> Source: [uikit/uikit](https://github.com/uikit/uikit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
