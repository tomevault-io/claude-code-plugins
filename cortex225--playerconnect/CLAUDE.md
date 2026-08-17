# 300-refactor-ref-react-19

> PLAN to refactor React 19 Ref

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/300-refactor-ref-react-19/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Context
React 19 is out and `forwardRef` is now longer needed to use `ref` in any React components. We can now just pass `ref` props :

```tsx
const MyButton = ({ ref, ...props }: ComponentProps<"button">) => {
  return <button ref={ref} {...props} />;
};
```

## Goal

You need to refactor a component **that was using `forwardRef`** to use the new `ref` props.


## Example

BEFORE :

```tsx
type SomeCustomProps = {
  color: "red" | "blue";
} & ComponentPropsWithoutRef<"div">;

export const MyCustomComponent = forwardRef<HTMLDivElement, SomeCustomProps>(
  ({ color, ...props }, ref) => {
    return <div ref={ref} {...props} />;
  },
);
```

AFTER :

```tsx
type SomeCustomProps = {
  color: "red" | "blue";
} & ComponentProps<"div">;

export const MyCustomComponent = ({
  color,
  ref,
  ...props
}: SomeCustomProps) => {
  return <div ref={ref} {...props} />;
};
```

---
> Source: [cortex225/playerConnect](https://github.com/cortex225/playerConnect) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-17 -->
