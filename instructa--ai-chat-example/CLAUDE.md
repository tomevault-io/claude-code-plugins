# compoents

> - Always use the typed `<Link>` from `@tanstack/react-router`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/compoents/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


## Links and Navigation
- Always use the typed `<Link>` from `@tanstack/react-router`.
- Pass `to`, `params`, `activeProps`, and Tailwind classes, mirroring:  
  ```tsx
  <Link
    to="/posts/$postId"
    params={{ postId: post.id }}
    activeProps={{ className: 'text-black ...' }}
    className="block ..."
  >
    {post.title}
  </Link>
  ```

---
> Source: [instructa/ai-chat-example](https://github.com/instructa/ai-chat-example) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
