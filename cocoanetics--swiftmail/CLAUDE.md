# swiftmail-project

> SwiftMail project-specific coding standards and organization rules

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/swiftmail-project/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

 # SwiftMail Project Rules

## Code Organization

- Protocol conformances for types should always be in a separate file named `Type+Protocol.swift`
- Group extensions next to their model definitions in the file structure
- Move files on the file system rather than generating them unnecessarily
- Maintain a clear directory structure:
  - `Sources/SwiftMail/IMAP/` - Code related to IMAP
  - `Sources/SwiftMail/SMTP/` - Code related to SMTP
  - `Sources/SwiftMail/Core/` - Code common to IMAP and SMTP implementations
  - `Demos` - Demo Apps
  - `Tests` - Test files

---
> Source: [Cocoanetics/SwiftMail](https://github.com/Cocoanetics/SwiftMail) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
