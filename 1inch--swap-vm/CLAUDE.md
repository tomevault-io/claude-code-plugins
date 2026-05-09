# foundry-tests

> **NEVER define mock contracts inline.** Use:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/foundry-tests/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Test Rules

## Mocks

**NEVER define mock contracts inline.** Use:
- `TokenMock` (see solidity-style.mdc for import)
- Existing mocks in `test/mocks/`
- New mocks go in `test/mocks/<Name>.sol`

## Inheritance

- **Aqua tests**: `AquaSwapVMTest`
- **Direct tests**: `Test` + `OpcodesDebug`
- **Invariant tests**: `CoreInvariants`

## Error Handling

Specify exact error type:

```solidity
vm.expectRevert(Contract.ErrorName.selector);
// NOT: vm.expectRevert();
```

## Fixing Tests

When asked to fix failing tests:
- **Minimal changes only** - fix the existing test, don't rewrite it
- **Never create new test files** unless explicitly requested
- **Never add new test functions** unless explicitly requested
- Preserve the original test structure and intent
- Update assertions/expectations to match new behavior if needed

---
> Source: [1inch/swap-vm](https://github.com/1inch/swap-vm) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
