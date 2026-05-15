# react-query-cursorrules-prompt-file

> Cursor rules for React development with React Query integration.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/react-query-cursorrules-prompt-file/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

// React + React Query .cursorrules

// Prefer functional components with hooks

const preferFunctionalComponents = true;

// React Query best practices

const reactQueryBestPractices = [
  "Use QueryClient and QueryClientProvider at the root of your app",
  "Implement custom hooks for queries and mutations",
  "Utilize query keys for effective caching",
  "Use prefetching for improved performance",
  "Implement proper error and loading states",
];

// Folder structure

const folderStructure = `
src/
  components/
  hooks/
    useQueries/
    useMutations/
  pages/
  utils/
  api/
`;

// Additional instructions

const additionalInstructions = `
1. Use TypeScript for type safety with React Query
2. Implement proper error boundaries for query errors
3. Utilize React Query DevTools for debugging
4. Use stale-while-revalidate strategy for data freshness
5. Implement optimistic updates for mutations
6. Use query invalidation for data refetching
7. Follow React Query naming conventions for consistency
`;

---
> Source: [XD3an/awesome-ai-coding-all-in-one](https://github.com/XD3an/awesome-ai-coding-all-in-one) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-14 -->
