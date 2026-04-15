# ts-dedup

> Use `readonly` properties for object types by default. This will prevent accidental mutation at runtime.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ts-dedup/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Use `readonly` properties for object types by default. This will prevent accidental mutation at runtime.

Omit `readonly` only when the property is genuinely mutable.

```ts
// BAD
type User = {
  id: string;
};

const user: User = {
  id: "1",
};

user.id = "2";
```

```ts
// GOOD
type User = {
  readonly id: string;
};

const user: User = {
  id: "1",
};

user.id = "2"; // Error
```

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/amit-t) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
