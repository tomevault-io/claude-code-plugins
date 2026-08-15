# nexflow-os

> - [PRODUCT.md](./PRODUCT.md) — product scope

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/nexflow-os/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# NexFlow — Agent guide

## Docs bắt buộc khi sửa UI hoặc feature UX

- [PRODUCT.md](./PRODUCT.md) — product scope
- [DESIGN.md](./DESIGN.md) — bold brand, tokens, anti-patterns
- [docs/impeccable-feature-playbook.md](./docs/impeccable-feature-playbook.md) — feature workflow

## Feature mới hoặc nâng cấp lớn

1. **`/impeccable shape <tên>`** — wireframe flow + states
2. Đối chiếu PRODUCT.md
3. Implement với `@/components/ui/*` + Tailwind
4. **`/impeccable harden`** + **`/impeccable clarify`**
5. `npm run design:audit` + `npm test`

## Stack UI

- Tailwind CSS v4 (`@tailwindcss/vite`)
- shadcn/ui primitives: `src/components/ui/`
- Toast: sonner (`showToast` trong AppContext)
- Legacy `.glass-card` → migrate sang `<GlassCard>` hoặc `<Card>`

## Design audit

```bash
npm run design:audit
```

## Impeccable skill

Cài local (nếu `npx impeccable skills install` lỗi trên Windows): dùng CLI `impeccable detect` và tham chiếu https://github.com/pbakaus/impeccable

---
> Source: [bogggrim-ui/nexflow-os](https://github.com/bogggrim-ui/nexflow-os) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-14 -->
