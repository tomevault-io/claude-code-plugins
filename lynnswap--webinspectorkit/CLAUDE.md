# webinspectorkit

> - Package tests can be run from Xcode through the shared `WebInspectorKit` scheme.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/webinspectorkit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Guidelines

## Testing

- Package tests can be run from Xcode through the shared `WebInspectorKit` scheme.
- Default validation command:

```sh
xcodebuild test \
  -workspace WebInspectorKit.xcworkspace \
  -scheme WebInspectorKit \
  -destination 'platform=iOS Simulator,name=iPhone 17,OS=latest'
```

---
> Source: [lynnswap/WebInspectorKit](https://github.com/lynnswap/WebInspectorKit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-03 -->
