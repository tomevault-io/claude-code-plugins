# app-struct

> - The [src/app.rs](mdc:src/app.rs) file defines the `App` struct, which represents an installed Android application.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/app-struct/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# App Struct Reference

- The [src/app.rs](mdc:src/app.rs) file defines the `App` struct, which represents an installed Android application.
- Fields:
  - `package_name`: The unique package identifier of the app
  - `app_name`: The display name of the app
- The `App` struct is used throughout [src/adb_client.rs](mdc:src/adb_client.rs) for listing, selecting, and operating on installed apps.

---
> Source: [cesarferreira/dab](https://github.com/cesarferreira/dab) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
