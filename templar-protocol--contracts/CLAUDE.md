# contracts

> See the repository-wide guide in [AGENTS.md](../AGENTS.md).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/contracts/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions

See the repository-wide guide in [AGENTS.md](../AGENTS.md).

Additional guidance for GitHub-hosted coding agents:

- Prefer minimal diffs that preserve the current module structure.
- Run the narrowest relevant Rust tests for the files you change.
- Be careful with event payload changes in `common/src/event.rs` and shared logic in `common/src/borrow.rs` and `common/src/market`.
- Do not assume integration tests can run in restricted environments; note when `near-workspaces` or local port binding is required.

---
> Source: [Templar-Protocol/contracts](https://github.com/Templar-Protocol/contracts) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-12 -->
