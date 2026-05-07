# strict-types-lint

> Do not bypass lint/type errors; use real types

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/strict-types-lint/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Strict typing and linting (no bypasses)

- Fix lint/type errors **properly**. Do not “silence” them.
- **Never introduce `any`**. Use the platform/library types (DOM/WebRTC/React/Node) or project types.
- **Do not use double-casts** like `as unknown as X` to force a type.
- **Do not disable rules** (no `eslint-disable`, no “turn off” pragmas) to make lint pass.
- When a type parameter is required (e.g. React module augmentation), reference it via correct `extends` / proper declarations rather than suppressing unused warnings.

## Examples

### Timers

Prefer:

```ts
const t = useRef<ReturnType<typeof window.setTimeout> | null>(null);
```

Avoid:

```ts
const t = useRef<number | null>(null);
t.current = window.setTimeout(fn, 1000) as unknown as number;
```

### WebRTC stats

Prefer:

```ts
const s = stat as RTCIceCandidateStats;
```

Avoid:

```ts
const s = stat as any;
```

---
> Source: [Gryt-chat/gryt](https://github.com/Gryt-chat/gryt) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
