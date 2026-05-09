# data-fetching-and-caching

> This is an extremely important rule for client performance.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/data-fetching-and-caching/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


This is an extremely important rule for client performance.

This is an example of how we want data to be fetched:

```tsx
function StatsCard() {
 return <Suspense=fallback{<Skeleton/>}>
          <StatsCardInternal/>
        </Suspense>
};

function StatsCardInternal(){
    const data = await getData();
    return <div>{...data}</div>;
};
```

The reason this format is important is because it allows us to have a fallback UI while the data is loading, and a non-blocking experience for the user.

Use react-query for data fetching and revalidation.

Use the `useQuery` hook to fetch data.

Use the `useMutation` hook to mutate data.

Use the `useQueryClient` hook to get the query client.

Use the `useQueryState` hook to get the query state.

---
> Source: [inboundemail/inbound](https://github.com/inboundemail/inbound) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
