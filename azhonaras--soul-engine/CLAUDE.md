# soul-seal

> When the human types SEAL, run Soul memory approval (every harness).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/soul-seal/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Soul SEAL

When the human types `SEAL` (or invokes `/soul-seal` — same interview), follow `skills/soul-seal/SKILL.md`.

That is human memory approval in this chat. Idle, “bye”, and wrap-up do not commit. After `review_packet.json`, they run `soul_host` and type `SEAL` then `COMMIT`. MCP cannot mint `origin_kind=human`.

Do not call `soul_review_stage_decision` / `soul_review_commit` with an MCP host event. Do not run `soul_host seal` yourself.

---
> Source: [Azhonaras/soul-engine](https://github.com/Azhonaras/soul-engine) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
