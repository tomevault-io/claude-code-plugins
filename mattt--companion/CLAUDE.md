# companion

> - **Build**: `xcodebuild -scheme Companion -workspace Companion.xcodeproj/project.xcworkspace build`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/companion/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# MCP Companion App - Agent Guidelines

## Build & Test Commands

- **Build**: `xcodebuild -scheme Companion -workspace Companion.xcodeproj/project.xcworkspace build`
- **Test All**: `xcodebuild -scheme Companion -workspace Companion.xcodeproj/project.xcworkspace test`
- **Single Test**: `xcodebuild -scheme Companion -workspace Companion.xcodeproj/project.xcworkspace test -only-testing:CompanionTests/TestClassName/testMethodName`
- **UI Tests**: `xcodebuild -scheme Companion -workspace Companion.xcodeproj/project.xcworkspace test -only-testing:CompanionUITests`

* Ignore SourceKit warnings about missing types/modules - assume they exist

---
> Source: [mattt/Companion](https://github.com/mattt/Companion) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
