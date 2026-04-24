# test-code

> Test code rule — JUnit 5, Testcontainers, traceability tagging.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/test-code/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Test code rule

Apply `shared/skills/junit5-testcontainers-patterns/SKILL.md` and `shared/skills/requirements-traceability/SKILL.md`.

## Required

- Tests asserting an AC have BOTH `@Tag("AC-NNN")` and `@DisplayName("AC-NNN: …")`.
- Smallest scope wins: plain JUnit ≺ slice ≺ `@SpringBootTest`.
- Testcontainers IT (with `@ServiceConnection`) is mandatory when the project declares Testcontainers and the change touches a repo / DB-touching controller / migration / message broker.
- Image tags pinned (`postgres:17-alpine`).

## Forbidden

- `@Disabled` without `# DisabledReason: <link>` on the prior line.
- Removing assertions to make a test pass.
- `Thread.sleep` for sync (use Awaitility).
- Hard-coded host ports.
- Mocking the SUT.
- `@MockBean` (deprecated; use `@MockitoBean`).

---
> Source: [loiane/specs-driven-development](https://github.com/loiane/specs-driven-development) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-24 -->
