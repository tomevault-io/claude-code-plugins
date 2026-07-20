# andy

> When asked to regenerate Andy's desktop visual baselines, run:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/andy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Screenshot action

When asked to regenerate Andy's desktop visual baselines, run:

```sh
./gradlew recordRoborazziDesktop
```

This records only the current operating system's renderer-specific baseline
directory under `src/screenshotTest/roborazzi/`. Review and commit only the
intentional PNG changes.

---
> Source: [j-roskopf/Andy](https://github.com/j-roskopf/Andy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
