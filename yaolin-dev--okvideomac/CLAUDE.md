# okvideomac

> - After completing a user-requested implementation change, build and verify the Release package with `OKVideoMac/macOS/OKVideoMac/Scripts/package-app.sh`, then replace the local user's `Desktop/OKVideoMac.app` with the verified packaged app unless the user explicitly asks not to.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/okvideomac/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project workflow

- After completing a user-requested implementation change, build and verify the Release package with `OKVideoMac/macOS/OKVideoMac/Scripts/package-app.sh`, then replace the local user's `Desktop/OKVideoMac.app` with the verified packaged app unless the user explicitly asks not to.
- Only deliver and install the verified Release app. A Debug build may be used for a quick compile check, but it must never replace the Desktop app or be presented as the deliverable.
- Never replace the Desktop app when packaging or bundle verification fails.

---
> Source: [yaolin-dev/OKVideoMac](https://github.com/yaolin-dev/OKVideoMac) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-17 -->
