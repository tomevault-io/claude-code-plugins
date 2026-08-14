# enduragent

> - Prioritize correctness, privacy, security, and user-visible behavior regressions over style-only feedback.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/enduragent/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Guidance

## Review guidelines

- Prioritize correctness, privacy, security, and user-visible behavior regressions over style-only feedback.
- Treat missing tests or missing verification for changed behavior as review findings when the change is not obviously mechanical.
- For athlete-facing changes, verify that a changeset exists and includes a `User-facing:` line when users should see the release note.
- Watch fixtures, logs, and test data for real athlete identifiers or current-era dates that could expose private training data.
- In public prose and identifiers, prefer project-owned language for the Reference layer and avoid upstream-implementation branding unless it is the explicit subject.
- Use intervals.icu plain-English metric names in user-visible text.

---
> Source: [yerzhansa/enduragent](https://github.com/yerzhansa/enduragent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
