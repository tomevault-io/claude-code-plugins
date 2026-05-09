# testing

> Testing conventions for LokalMind v2.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Testing Conventions

Full reference: `docs/development/CONVENTIONS.md` section 7.

## File location - co-located with source

```
SendMessageUseCase.ts
SendMessageUseCase.test.ts   ← same directory
```

## What must be tested

- Every `UseCase` - no exceptions
- Every `ViewModel` - initial state, each action, computed, async success + failure

## Mock at the interface boundary

```typescript
// Good - mock the interface
class MockChatRepository implements IChatRepository {
  saveMessage = jest.fn().mockResolvedValue({ id: '1', text: 'hi' });
}

// Bad - mock the concrete implementation
jest.mock('expo-sqlite');
```

## PR requirements

- New UseCase → must ship with tests
- New ViewModel → must ship with tests
- Bug fix → must include regression test

---
> Source: [Sandipan006/lokalmind-app](https://github.com/Sandipan006/lokalmind-app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
