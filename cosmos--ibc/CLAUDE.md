# ibc

> <!-- SPDX-License-Identifier: Apache-2.0 -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ibc/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<!-- SPDX-License-Identifier: Apache-2.0 -->

# IBC CLI Development Guide for AI Agents

- Use `make lint-fix` to auto-format and lint code before finishing work.
- Don't add verbose comments. Be concise.
- `gen/` at the repository root holds generated code only, and its layout is fixed by an ADR — don't
  move it or put anything handwritten there. Generator scripts belong in the root `scripts/`
  directory, not beside their output. The one exception is `gen/README.md`, which documents the tree.
- Repository-wide black-box e2e lives in `../e2e`, with its harness in
  `../e2e/internal/harness` as a separate Go module. The real relayer submits packets through
  ICS26Router with attestation proofs signed by harness-managed attestors. Keep
  `make -C e2e test` green when changing that transport contract.

---
> Source: [cosmos/ibc](https://github.com/cosmos/ibc) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-09 -->
