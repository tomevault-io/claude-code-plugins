# 102-create-components

> EXPLAIN how to create a component

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/102-create-components/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Context

* Creating a component must ALWAYS follow this rules.

## Rules

- You always use `export function` without "default".
- You always use an object "props" as the first argument of your component, and add type directly in the object.

## Example

With 2 or less props :

```tsx
export function MyComponent(props: { prop1: string; prop2: number }) {
  return <div>{props.prop1}</div>;
}
```

With more than 2 props :

```tsx
type MyComponentProps = { 
  prop1: string; 
  prop2: number;
  prop3: number;
}

export function MyComponent(props: MyComponentProps) {
  return <div>{props.prop1}</div>;
}
```

---
> Source: [cortex225/playerConnect](https://github.com/cortex225/playerConnect) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-17 -->
