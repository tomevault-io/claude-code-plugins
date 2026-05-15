# interface-extends

> ALWAYS prefer interfaces when modelling inheritance.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/interface-extends/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

ALWAYS prefer interfaces when modelling inheritance.

The `&` operator has terrible performance in TypeScript. Only use it where `interface extends` is not possible.

```ts
// BAD

type A = {
  a: string;
};

type B = {
  b: string;
};

type C = A & B;
```

```ts
// GOOD

interface A {
  a: string;
}

interface B {
  b: string;
}

interface C extends A, B {
  // Additional properties can be added here
}
```

---
> Source: [almond-bongbong/react-bottom-fixed](https://github.com/almond-bongbong/react-bottom-fixed) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-14 -->
