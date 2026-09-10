# mincho

> React bindings; styled() is a macro rewritten by Babel into runtime calls.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mincho/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# @mincho-js/react

## OVERVIEW

React bindings; styled() is a macro rewritten by Babel into runtime calls.

## STRUCTURE

packages/react/
├── src/index.ts # public types + placeholder styled
├── src/runtime.ts # $$styled runtime implementation
└── runtime/ # proxy package.json for subpath export

## WHERE TO LOOK

| Task             | Location                              | Notes                    |
| ---------------- | ------------------------------------- | ------------------------ |
| Public API types | `packages/react/src/index.ts`         | styled overloads         |
| Runtime behavior | `packages/react/src/runtime.ts`       | $$styled implementation  |
| Subpath export   | `packages/react/runtime/package.json` | @mincho-js/react/runtime |

## CONVENTIONS

- styled in index.ts is a placeholder; Babel rewrites it to $$styled.
- Keep runtime lean; most logic should compile away.
- Tests are colocated in source.

## ANTI-PATTERNS

- Do not call styled() without the Babel transform in the toolchain.
- Avoid heavy runtime dependencies here.

---
> Source: [mincho-js/mincho](https://github.com/mincho-js/mincho) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-09 -->
