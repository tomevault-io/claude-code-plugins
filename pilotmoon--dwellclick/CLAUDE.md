# dwellclick

> For sandboxed verification builds, use:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dwellclick/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

For sandboxed verification builds, use:

```sh
xcodebuild -project dc.xcodeproj -scheme "DwellClick SA" -configuration Debug -destination 'platform=macOS' -derivedDataPath /tmp/DwellClickDerivedData CODE_SIGNING_ALLOWED=NO build
```

`CODE_SIGNING_ALLOWED=NO` avoids local certificate/keychain failures; this is for build verification only.

---
> Source: [pilotmoon/DwellClick](https://github.com/pilotmoon/DwellClick) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-30 -->
