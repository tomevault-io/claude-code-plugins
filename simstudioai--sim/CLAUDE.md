# emcn-components

> EMCN component library patterns

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/emcn-components/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# EMCN Components

Import from `@/components/emcn`, never from subpaths (except CSS files).

## CVA vs Direct Styles

**Use CVA when:** 2+ variants (primary/secondary, sm/md/lg)

```tsx
const buttonVariants = cva('base-classes', {
  variants: { variant: { default: '...', primary: '...' } }
})
export { Button, buttonVariants }
```

**Use direct className when:** Single consistent style, no variations

```tsx
function Label({ className, ...props }) {
  return <Primitive className={cn('style-classes', className)} {...props} />
}
```

## Rules

- Use Radix UI primitives for accessibility
- Export component and variants (if using CVA)
- TSDoc with usage examples
- Consistent tokens: `font-medium`, `text-[12px]`, `rounded-[4px]`
- `transition-colors` for hover states

---
> Source: [simstudioai/sim](https://github.com/simstudioai/sim) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
