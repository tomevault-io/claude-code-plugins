# expo-gpt-live

> Read https://docs.expo.dev/versions/v57.0.0/ before changing Expo code.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/expo-gpt-live/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Development

Read https://docs.expo.dev/versions/v57.0.0/ before changing Expo code.

## Voice implementation

- Use GPT-Live 1 and the Live API event protocol at `/v1/live/sessions`.
- Keep microphone audio active during replies and while iOS is backgrounded or locked.
- Preserve mute acknowledgments, explicit End, unmount cleanup, and the ten-minute call limit.
- Lock voice selection while connecting, connected, or ending. The voice is fixed at session creation.
- Keep the OpenAI key in the server environment. Never put it in an `EXPO_PUBLIC_` variable.

## Checks

Run `npm run check`. For build-script changes, also run `python3 -m unittest discover -s scripts/tests`.

## Commit and PR conventions

- Commit messages must be one line, begin lowercase, and describe the change plainly without conventional commit prefixes.
- Never add AI or Codex co-author credits.
- PR titles use the user's area format, for example `[web] ...` or `[be] ...`.

---
> Source: [davidmokos/expo-gpt-live](https://github.com/davidmokos/expo-gpt-live) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-16 -->
