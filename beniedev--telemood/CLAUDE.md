# telemood

> - Preserve the repository user's existing Git identity. Do not change it

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/telemood/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Public repository instructions

- Preserve the repository user's existing Git identity. Do not change it
  unless that user explicitly requests the change.
- Do not push, publish a release, create tags, or change repository
  visibility without explicit human authorization.
- Keep code, tests, examples, and documentation topology-neutral and
  content-free: use logical names only. Do not add private deployment names,
  local paths, endpoints, credentials, cookies, raw private messages, or
  runtime state.
- Keep transport/provider integrations in host adapters; the package owns
  public interaction contracts and callback state only.

---
> Source: [beniedev/telemood](https://github.com/beniedev/telemood) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
