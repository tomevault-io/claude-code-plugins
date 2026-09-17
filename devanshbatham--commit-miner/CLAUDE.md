# commit-miner

> Keep the commit-miner binary and viewer package versions at `0.0.1` until the first GitHub publish. Do not bump versions for local changes before that publish. Keep Cargo.toml, Cargo.lock, package.json, and package-lock.json in sync.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/commit-miner/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project instructions

Keep the commit-miner binary and viewer package versions at `0.0.1` until the first GitHub publish. Do not bump versions for local changes before that publish. Keep Cargo.toml, Cargo.lock, package.json, and package-lock.json in sync.

Preserve lightweight Jev coverage of every eligible diff section; optimize deeper review instead of skipping unseen files. Semantic classifications must come from Jev, without regex or source-text matching. Keep API concurrency capped at 8 with adaptive backoff. Optimize cost by batching shared state and reusing valid cache entries; retain category/CWE definitions and classification thresholds.

---
> Source: [devanshbatham/commit-miner](https://github.com/devanshbatham/commit-miner) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-17 -->
