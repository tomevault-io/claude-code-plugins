# visible-build-artifacts

> Keep user-facing build artifacts in a visible folder

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/visible-build-artifacts/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Visible Build Artifacts

- Put distributable artifacts such as `MeetingNotes.app` and `.dmg` files in the visible `build/` directory.
- Use `.build/` only for Swift Package Manager caches and temporary staging.
- Update build scripts and documentation to reference `build/` for artifacts users open, test, or distribute.

---
> Source: [Z060049/MeetingNotes](https://github.com/Z060049/MeetingNotes) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-19 -->
