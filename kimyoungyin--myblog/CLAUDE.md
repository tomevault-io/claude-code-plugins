# project-architecture

> - **Entry Point**: [src/app/layout.tsx](mdc:src/app/layout.tsx) is the root layout

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project-architecture/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Project Architecture Rules

## 🏗️ **Directory Structure (MUST FOLLOW)**

- **Entry Point**: [src/app/layout.tsx](mdc:src/app/layout.tsx) is the root layout
- **Pages**: All pages go in [src/app/](mdc:src/app) following Next.js 14 App Router
- **Components**: Reusable components in [src/components/](mdc:src/components)
- **Business Logic**: Core logic in [src/lib/](mdc:src/lib)
- **Custom Hooks**: React hooks in [src/hooks/](mdc:src/hooks)
- **State Management**: Zustand stores in [src/stores/](mdc:src/stores)
- **Type Definitions**: TypeScript types in [src/types/](mdc:src/types)

## 📁 **File Organization (CRITICAL)**

- **NEVER** create files outside the established directory structure
- **ALWAYS** use `@/*` path alias for imports from `src/`
- **MUST** follow the existing naming conventions:
    - Components: PascalCase (e.g., `MarkdownEditor.tsx`)
    - Files: kebab-case (e.g., `file-upload.ts`)
    - Functions: camelCase (e.g., `createPostAction`)
    - Types: PascalCase (e.g., `CreatePostData`)

## 🚫 **FORBIDDEN Practices**

- **NEVER** create components in the wrong directory
- **NEVER** use relative imports when `@/*` alias is available
- **NEVER** mix different naming conventions in the same file
- **NEVER** create utility functions outside [src/lib/](mdc:src/lib) or [src/utils/](mdc:src/utils)

---
> Source: [kimyoungyin/myblog](https://github.com/kimyoungyin/myblog) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
