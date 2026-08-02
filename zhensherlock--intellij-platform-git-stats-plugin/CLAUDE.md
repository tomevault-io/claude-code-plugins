# intellij-platform-git-stats-plugin

> Use `AGENTS.md` as the primary project instruction file.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/intellij-platform-git-stats-plugin/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# CLAUDE.md - GitStats IntelliJ Plugin

Use `AGENTS.md` as the primary project instruction file.

When working in a subdirectory, also follow the nearest nested `AGENTS.md` before making changes.

## Claude-Specific Behavior

- Prefer small, reviewable changes.
- Before large refactors, summarize the impact and likely touched IntelliJ plugin areas.
- After code changes, run the most relevant Gradle checks from `AGENTS.md`; default to `./gradlew check`.
- Keep shared repo guidance in `AGENTS.md`; keep this file as a lightweight Claude entrypoint.

---
> Source: [zhensherlock/intellij-platform-git-stats-plugin](https://github.com/zhensherlock/intellij-platform-git-stats-plugin) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-23 -->
