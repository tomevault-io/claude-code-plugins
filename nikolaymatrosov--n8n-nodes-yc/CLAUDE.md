# testing

> - **Always work from within the package directory** when running tests

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


### Testing Guidelines
- **Always work from within the package directory** when running tests
- **Mock all external dependencies** in unit tests
- **Confirm test cases with user** before writing unit tests
- **Typecheck is critical before committing** - always run `pnpm typecheck`
- **When modifying pinia stores**, check for unused computed properties

What we use for testing and writing tests:
- For testing nodes and other backend components, we use Jest for unit tests. Examples can be found in `packages/nodes-base/nodes/**/*test*`.
- We use `nock` for server mocking
- For frontend we use `vitest`
- For e2e tests we use `Playwright` and `pnpm dev:e2e`. The old Cypress tests
  are being migrated to Playwright, so please use Playwright for new tests.

---
> Source: [nikolaymatrosov/n8n-nodes-yc](https://github.com/nikolaymatrosov/n8n-nodes-yc) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-07 -->
