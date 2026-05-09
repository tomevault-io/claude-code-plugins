# nanotracker-api-sdk

> See [`AGENTS.md`](../AGENTS.md) for the must-know rules and

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/nanotracker-api-sdk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot — nanoTracker API SDK

See [`AGENTS.md`](../AGENTS.md) for the must-know rules and
[`CLAUDE.md`](../CLAUDE.md) for full orientation. The same skill bodies
are mirrored under [`.claude/`](../.claude/), [`.hermes/`](../.hermes/),
and [`.agents/`](../.agents/).

This SDK drives a live [nanoTracker](https://federatedindustrial.com/tracker)
session through a local relay. Read state with `nanotracker_read`, write
with `nanotracker_execute`, manage samples with `nanotracker_assets_*`.
Always pass `opts.undoDescription` on writes.

---
> Source: [savannah-i-g/nanotracker-api-sdk](https://github.com/savannah-i-g/nanotracker-api-sdk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-09 -->
