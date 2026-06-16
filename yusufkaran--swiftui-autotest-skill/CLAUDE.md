# swiftui-autotest-skill

> AI-powered visual testing and accessibility setup for iOS/SwiftUI apps. Build, launch in Simulator, test with computer use, detect crashes, analyze memory leaks, and add accessibility identifiers — all from the terminal.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/swiftui-autotest-skill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# SwiftUI Autotest Skill

Automated visual testing and accessibility identifier generation for iOS/SwiftUI applications using Claude Code's computer use.

## Included Skills

- **ios-test** — Build, launch in Simulator, visually test with computer use, crash log analysis, state testing (empty/error/loading), performance analysis (RAM/memory leaks)
- **add-accessibility** — Scan SwiftUI views and add missing accessibility identifiers using `{screen}-{type}-{name}` convention, flag Dynamic Type issues

## Quick Start

```bash
npx skills add yusufkaran/swiftui-autotest-skill
```

Then in your SwiftUI project:

```
/ios-test
/add-accessibility
```

See [README.md](README.md) for full documentation.

---
> Source: [yusufkaran/swiftui-autotest-skill](https://github.com/yusufkaran/swiftui-autotest-skill) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
