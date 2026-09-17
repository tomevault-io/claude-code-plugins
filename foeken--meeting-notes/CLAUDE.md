# meeting-notes

> - Always build and launch the app with `./scripts/stable-build.sh` from the repository root.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/meeting-notes/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Meeting Notes Menu agent instructions

## Building and launching

- Always build and launch the app with `./scripts/stable-build.sh` from the repository root.
- Never launch `Meeting Notes.app` directly with `open`, and never run a binary from `.build`.
- Never restore the app after a UI-test run with a direct `open` command. Run `./scripts/stable-build.sh` again so it stops every old instance, rebuilds, verifies the exact executable, and launches one normal instance.
- Before starting a UI-test mode, confirm no real meeting is active. After UI testing, always finish with `./scripts/stable-build.sh`.
- Keep the runnable app at `Meeting Notes.app` in the repository root.
- If the app process is absent while an active meeting pointer exists, use
  `./scripts/stable-build.sh --recover-running-meeting`. This verifies and launches the existing
  canonical signed app without rebuilding or altering recovery state.

---
> Source: [foeken/meeting-notes](https://github.com/foeken/meeting-notes) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-16 -->
