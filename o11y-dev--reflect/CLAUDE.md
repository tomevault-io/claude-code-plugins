# reflect

> - During every merge request / pull request review, verify whether the change should update `CHANGELOG.md`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/reflect/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot instructions

- During every merge request / pull request review, verify whether the change should update `CHANGELOG.md`.
- For any user-visible feature, fix, dependency, or behavior change, require an entry in the active unreleased section.
- Keep the unreleased heading in release-ready format: `## <current-version> (unreleased)`.
- Group changelog entries under `### Added`, `### Fixed`, `### Changed`, or `### Dependencies`.

---
> Source: [o11y-dev/reflect](https://github.com/o11y-dev/reflect) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-19 -->
