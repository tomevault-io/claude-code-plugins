# remix-conventions

> Frontend conventions (optional) for TypeScript/React portals

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/remix-conventions/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Frontend Conventions (Optional)

Only apply these rules if the project has a TypeScript/React frontend under `portal/`.

## General

- Keep routes/pages thin; move logic into `portal/src/lib` or `portal/src/services`.
- Prefer explicit typing at API boundaries.
- Centralize network calls in a small API client module (do not scatter `fetch()`).
- Treat UI state changes as data-flow: inputs -> validation -> action -> result.

## Testing

- Unit tests for pure functions and components with complex logic.
- E2E tests only for critical user journeys (few, stable).

## Error Handling

- Show user-safe errors in UI.
- Log developer-facing details in console only for dev builds.

---
> Source: [c9r-io/orchestrator](https://github.com/c9r-io/orchestrator) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
