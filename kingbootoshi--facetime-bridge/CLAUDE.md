# facetime-bridge

> Read `docs/adr/README.md` before non-trivial changes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/facetime-bridge/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository instructions

Read `docs/adr/README.md` before non-trivial changes.

- Use Bun for TypeScript commands and tests.
- Keep target identity in `~/.config/facetime-bridge/config.json` only.
- Never commit local configuration, credentials, recordings, logs, device identifiers, or personal data.
- Keep FaceTime control semantic and fail closed. Do not add coordinate clicks.
- Keep audio provider-neutral. Do not add a bundled provider, token path, or hosted dependency.
- Preserve the one-session audio lock and verified teardown.

---
> Source: [kingbootoshi/facetime-bridge](https://github.com/kingbootoshi/facetime-bridge) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
