# videoedit

> "description": "Never rewrite test invariants; fix implementation instead.",

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/videoedit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

{
  "version": 1,
  "rules": [
    {
      "description": "Never rewrite test invariants; fix implementation instead.",
      "alwaysApply": true,
      "globs": ["app/src/test/**", "app/src/androidTest/**"],
      "editsAllowed": false
    },
    {
      "description": "When touching WhisperEngine, WhisperBridge, AsrFileScanWorker, or AsrTranscribeWorker, run instrumented tests.",
      "alwaysApply": true,
      "commands": ["./gradlew :app:connectedDebugAndroidTest"]
    }
  ]
}

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/dolphinDoReMi) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
