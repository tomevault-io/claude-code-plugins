# swift-build

> Swift build verification instructions for osaurus

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/swift-build/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Building OsaurusCore

The xcode workspace has pre-existing build failures in external dependencies (`mlx-swift-lm`, `IkigaJSON`). Never use `xcodebuild` to verify changes — it will always fail on those deps and waste tokens.

Instead, compile only the OsaurusCore package sources (no linking) to verify your changes:

```bash
cd /Users/tpae/dev/osaurus/Packages/OsaurusCore && swift build 2>&1 | grep -E "error:" | grep -v "IkigaJSON"
```

If the filtered output is empty, your code compiles cleanly.

---
> Source: [osaurus-ai/osaurus](https://github.com/osaurus-ai/osaurus) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
