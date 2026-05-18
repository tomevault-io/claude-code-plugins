# spacetimedb-config

> Locked SpacetimeDB versions for this project; never upgrade/downgrade automatically

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/spacetimedb-config/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# SpacetimeDB Configuration

## Required Versions (IMMUTABLE)

**NEVER change these versions under any circumstances.** These are locked for project compatibility.

| Component | Version |
|-----------|---------|
| SpacetimeDB CLI | 2.0.x |
| SpacetimeDB Rust Crate | 2.0 |
| SpacetimeDB TypeScript SDK | spacetimedb@2.0.1 (npm package) |

When editing `Cargo.toml`, `package.json`, lockfiles, Dockerfiles, CI, or deployment commands, preserve these exact versions. Do not upgrade, downgrade, or suggest alternative versions unless explicitly requested by the user.

## Applies To

- `server/Cargo.toml` and Rust module dependencies
- `client/package.json` and npm dependencies
- Any scripts/automation that installs or validates SpacetimeDB tooling

---
> Source: [SeloSlav/2d-multiplayer-survival-mmorpg](https://github.com/SeloSlav/2d-multiplayer-survival-mmorpg) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
