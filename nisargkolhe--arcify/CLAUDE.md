# 04-helper-modules

> The `ChromeHelper` module encapsulates Chrome API interactions and provides a cleaner interface for:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/04-helper-modules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Helper Modules

## ChromeHelper

The `ChromeHelper` module encapsulates Chrome API interactions and provides a cleaner interface for:
- Creating new tabs
- Creating new tab groups
- Managing tab groups

## LocalStorage

The `LocalStorage` module manages persistent storage using Chrome's bookmarks API:
- `getOrCreateArcifyFolder()` - Gets or creates the root bookmark folder
- `getOrCreateSpaceFolder(name)` - Gets or creates a bookmark folder for a space

## Utils

The `Utils` module provides utility functions for:
- Generating UUIDs
- Getting settings
- Getting favicon URLs
- Managing tab name overrides
- Handling tab archiving and restoration

## Constants

The codebase defines several constants:
- `MouseButton` - Enum for mouse button values
- Default space names and colors
- Global state flags like `isCreatingSpace`, `isOpeningBookmark`

---
> Source: [nisargkolhe/arcify](https://github.com/nisargkolhe/arcify) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
