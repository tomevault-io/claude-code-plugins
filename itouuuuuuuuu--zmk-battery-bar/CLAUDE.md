# zmk-battery-bar

> Shared, agent-agnostic instructions live in `AGENTS.md` (also read by Codex).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/zmk-battery-bar/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# CLAUDE.md

Shared, agent-agnostic instructions live in `AGENTS.md` (also read by Codex).
This file imports them and adds Claude-specific instructions.

@AGENTS.md

## Detailed rules

@.claude/rules/ble-domain-knowledge.md
@.claude/rules/review-and-release.md

## Claude-specific

### Verification

- Never claim BLE behaviour was verified on hardware unless the `.app` bundle
  was actually launched (`AGENTS.md` → "Running for manual verification").
  Otherwise state plainly that only `swift test` was run.
- Do not claim a fix works because the code looks correct; BLE recovery paths
  are callback-ordering sensitive (see
  `.claude/rules/review-and-release.md`).

### Reviews

- When asked to have a change confirmed or reviewed by another agent, follow
  `.claude/rules/review-and-release.md`: report each finding's verdict
  separately instead of silently folding it in.

---
> Source: [itouuuuuuuuu/zmk-battery-bar](https://github.com/itouuuuuuuuu/zmk-battery-bar) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-06 -->
