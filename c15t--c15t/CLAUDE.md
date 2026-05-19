# elements-rules

> working on the elements package

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/elements-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Elements Package Guidelines

## Component Architecture
- Use compound components pattern (e.g., `Component.Root`, `Component.Child`)
- Implement React Context for state management
- Support composition through `asChild` prop
- Follow the Radix UI primitives pattern
- Implement error boundaries for component failure isolation
- Provide fallback UI for error states

## Styling
- Use CSS Modules for component styles
- Keep styles scoped to components
- Support className prop for customization
- Use CSS custom properties for theming
- Avoid external styling dependencies like Tailwind

## TypeScript Guidelines
- Implement full TypeScript support
- Export type definitions for public API
- Use proper generic constraints
- Document all props and types

## Accessibility
- Implement ARIA attributes
- Support keyboard navigation
- Handle focus management
- Test with screen readers
- Follow WAI-ARIA guidelines

## Testing
- Write unit tests for components
- Include integration tests
- Test accessibility features
- Test error boundaries
- Use Vitest for testing framework

## Documentation
- Include TSDoc comments for components
- Document props and usage examples
- Provide clear error messages
- Include TypeScript examples 

---
> Source: [c15t/c15t](https://github.com/c15t/c15t) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
