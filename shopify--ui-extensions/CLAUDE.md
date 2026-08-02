# ui-extensions

> Implement every feature with TDD. See `./tests`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ui-extensions/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Implement every feature with TDD. See `./tests`.

After every change, run the relevant test suites in `examples/testing/*` to verify that example tests still pass.

Keep documentation up to date in both the package README (`packages/ui-extensions-tester/README.md`) and each surface-specific README:

- `packages/ui-extensions-tester/src/admin/README.md`
- `packages/ui-extensions-tester/src/checkout/README.md`
- `packages/ui-extensions-tester/src/customer-account/README.md`
- `packages/ui-extensions-tester/src/point-of-sale/README.md`

Any change to exports, function signatures, or behavior must be reflected in the relevant docs.

Code blocks in README files are formatted at print width 50 via the root `.prettierrc` override. Run `npx prettier --write` on any changed README.

---
> Source: [Shopify/ui-extensions](https://github.com/Shopify/ui-extensions) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
