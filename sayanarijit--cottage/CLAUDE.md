# cottage

> - **Command Safety**: AI agents are strictly forbidden from running `ctg` or `ctgx` commands under any circumstances.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cottage/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Workspace Instructions for AI agents

- **Command Safety**: AI agents are strictly forbidden from running `ctg` or `ctgx` commands under any circumstances.
- **Secret Files**: AI agents must never view, read, edit, create, or otherwise access:
  - Anything inside a `.cottage/` directory (identities, recipients, project state).
  - Any file matching `*.cott.*` (e.g. `*.cott.age` encrypted blobs, `*.cott.toml` redacted previews).
  - Any decrypted file `{file}` that has a corresponding `{file}.cott.age` encrypted counterpart on disk.

---
> Source: [sayanarijit/cottage](https://github.com/sayanarijit/cottage) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-16 -->
