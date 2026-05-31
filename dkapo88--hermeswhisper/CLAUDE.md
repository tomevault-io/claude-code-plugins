# 003-build-and-test

> Build, Test, and Development commands for HermesWhisper

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/003-build-and-test/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Build, Test, and Development

- **Open in Xcode**:
  - `open "HermesWhisper.xcodeproj"` (use `.xcworkspace` if present).
- **Build (Debug)**:
  - ```bash
    xcodebuild -project "HermesWhisper.xcodeproj" -scheme "HermesWhisper" -configuration Debug build
    ```
- **Test (macOS)**:
  - ```bash
    xcodebuild -project "HermesWhisper.xcodeproj" -scheme "HermesWhisper" -destination 'platform=macOS' test
    ```
- **Run locally**:
  - Use Xcode, or `./Scripts/build-and-run.sh` for a script-built Debug app.

Prefer absolute paths in commands within this workspace.

---
> Source: [dkapo88/hermeswhisper](https://github.com/dkapo88/hermeswhisper) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-31 -->
