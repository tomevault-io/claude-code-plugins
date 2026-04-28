# kaamelott-gifs

> When declaring functions on the top-level of a module,

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/kaamelott-gifs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When declaring functions on the top-level of a module,
declare their return types. This will help future AI
assistants understand the function's purpose.

```ts
const myFunc = (): string => {
  return "hello";
};
```

One exception to this is components which return JSX.
No need to declare the return type of a component,
as it is always JSX.

```tsx
const MyComponent = () => {
  return <div>Hello</div>;
};
```

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/MaloLebrin) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
