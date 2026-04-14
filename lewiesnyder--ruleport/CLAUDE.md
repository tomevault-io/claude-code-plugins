# ruleport

> - This project uses itself to manage its rules.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ruleport/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Workflow Standards

## Dogfooding
- This project uses itself to manage its rules.
- **Source of Truth**: `.cursor/rules/`.
- **Derived Files**: `.agent/`, `.claude/`, `.github/`.
- **NEVER** edit derived files manually. Always edit the Source of Truth and run sync.

## Sync Protocol
- After editing any file in `.cursor/rules/`, you MUST run:
  ```bash
  npm run sync
  ```
- Before committing, ensure the sync output is clean and updated.

## Testing
- When modifying the sync core (`sync-rules-advanced.js`), verify with generic arguments:
  ```bash
  npm run sync -- --target copilot
  ```

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/lewiesnyder) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
