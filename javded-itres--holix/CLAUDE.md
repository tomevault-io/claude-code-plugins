# holix

> - **Production** installs of Holix Studio stack: **GitHub Actions only**, **branch `main` only** (Helix + holix-studio + holix-license).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/holix/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent notes (Helix workspace)

## Production / remote policy (Studio and related)

- **Production** installs of Holix Studio stack: **GitHub Actions only**, **branch `main` only** (Helix + holix-studio + holix-license).
- **Never** without explicit user approval in the **current** turn:
  - rsync/scp/patch application files on prod (or test)
  - manual code checkout on VDS outside Actions
  - “quick hotfix” edits on the server
- Do not treat past deploys as blanket permission.
- Local verification only by default (tests; local Studio restart if needed).

---
> Source: [javded-itres/Holix](https://github.com/javded-itres/Holix) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-06 -->
