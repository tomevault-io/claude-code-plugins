# lambda

> Lambda React Native app — core constraints for AI agents

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/lambda/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Lambda (Expo / React Native)

- **Source of truth for colors/spacing:** `lambda/constants/Theme.ts` (`T.*`). No hardcoded hex in components; no Tamagui `$token` strings.
- **Layout:** Tamagui `XStack` / `YStack` / `Text`; avoid `StyleSheet.create` in new UI.
- **Data:** Local-first **SQLite** (`expo-sqlite`); writes go through **`lib/offline/*` stores** and **`queueMutation`** — do not write workout/exercise user data directly to Supabase from screens.
- **Auth:** `lib/AuthContext.tsx`; session + profile cache in SecureStore (see `lambda_onboarded_{userId}` + `lambda_profile_{userId}` keys).
- **Sync:** `lib/sync/useSyncEngine.ts` (mounted in `app/(tabs)/_layout.tsx`); Zustand + React Query used **only** for sync UX / invalidation, not app-wide global state.
- **Sheets / modals:** `SlideUpModal` and `DropdownSelect` must stay **always mounted**; toggle `visible` only (see `CLAUDE.md` “SlideUpModal always-mounted rule”).
- **Tamagui + `T.*`:** Known TS inference noise; do not “fix” by removing `T.*`.
- **Tabs:** Custom bottom bar is the `Tabs` `tabBar` in `app/(tabs)/_layout.tsx`. Switch tabs with the tab navigator’s `navigation.navigate('four' | 'three' | …)` — do not use `router.navigate('/four')` for tab switches (collapses nested Logs stack).
- **Details, routing map, component API:** read `CLAUDE.md` at repo root.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/AristonTheAnalyst) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-12 -->
