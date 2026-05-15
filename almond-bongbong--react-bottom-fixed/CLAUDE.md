# no-unchecked-indexed-access

> If the user has this rule enabled in their `tsconfig.json`, indexing into objects and arrays will behave differently from how you expect.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/no-unchecked-indexed-access/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

If the user has this rule enabled in their `tsconfig.json`, indexing into objects and arrays will behave differently from how you expect.

```ts
const obj: Record<string, string> = {};

// With noUncheckedIndexedAccess, value will
// be `string | undefined`
// Without it, value will be `string`
const value = obj.key;
```

```ts
const arr: string[] = [];

// With noUncheckedIndexedAccess, value will
// be `string | undefined`
// Without it, value will be `string`
const value = arr[0];
```

---
> Source: [almond-bongbong/react-bottom-fixed](https://github.com/almond-bongbong/react-bottom-fixed) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-14 -->
