# aid-console-noise

> When observing browser console output (via Playwright MCP or any browser tool), **ignore these known AI Dungeon errors** — they are always present on aidungeon.com and are NOT caused by MCA:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/aid-console-noise/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AI Dungeon Console Noise

When observing browser console output (via Playwright MCP or any browser tool), **ignore these known AI Dungeon errors** — they are always present on aidungeon.com and are NOT caused by MCA:

## Always Ignore
- `CORS policy: No 'Access-Control-Allow-Origin'` from `api.aidungeon.com/graphql`
- `Failed to load resource: net::ERR_FAILED` on `api.aidungeon.com/graphql`
- `TypeError: Failed to fetch` from `_app-*.js` (Apollo GraphQL client retries)
- `ApolloError: Failed to fetch` stack traces
- `useNativeDriver is not supported` (React Native Reanimated warning, harmless)

## What To Pay Attention To
- Console messages prefixed with `[MCA]` — these are from our extension
- Network errors on endpoints our extension calls directly
- Errors in `chrome-extension://` URLs
- Any new error patterns that appear AFTER loading or reloading MCA

---
> Source: [LewdLeah/Multiple-Choice-Assistant](https://github.com/LewdLeah/Multiple-Choice-Assistant) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
