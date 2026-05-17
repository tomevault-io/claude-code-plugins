# unit-tests-todos

> When proposing/writing unit test specs

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/unit-tests-todos/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Stack:
- Vitest

Testing rules:
- Test are colocated as closely as possible to the code they are testing in a `__tests__` directory.
- We only test if/then logic
- A ‘when’ should indicate a describe block, and then we will out the todos.
- Don’t test implementation details, only the public API.

- DO NOT WRITE THE ACTUAL TESTING, ONLY THE TODOS.
- Propose only a spec test of todos:

Example:
```ts
describe(“Todo List”, () => {
    describe(“when a todo is added”, () => {
        it.todo(“adds a todo”);
    });
});
```

---
> Source: [langwatch/better-agents](https://github.com/langwatch/better-agents) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
