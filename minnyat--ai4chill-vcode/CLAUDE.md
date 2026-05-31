# ai4chill-vcode

> - **Interaction with user**: Vietnamese

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ai4chill-vcode/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Rules

### Language

- **Interaction with user**: Vietnamese
- **Code, search, inter-agent communication**: English
- **Documentation**:
  - Headings, structure, metadata: English
  - Content/body: Vietnamese

### Core Requirements

### Skill (MUST load when need)

- frontend-design: read_in ".opencode/skill/frontend-design.md"

### Memory

- Gọi agent @memory khi bắt đầu tab và khi hết thúc tab

#### 1. Subagent Delegation

- **BẮT BUỘC** sử dụng subagent cho MỌI tác vụ kỹ thuật
- Main agent chỉ điều phối và trả lời user
- Không tự thực hiện code/search/tools trực tiếp

#### 2. Issue-Only Development

- **CHỈ giải quyết** các vấn đề trong GitHub Issues của project
- Kiểm tra issue trước khi bắt đầu
- Nếu chưa có issue → yêu cầu user tạo issue trước
- Luôn ghi rõ issue number khi làm việc

### Workflow

```
User (VI) → Main Agent → Check Issue → Delegate to Subagent (EN)
                  ↑                              ↓
                  └─────── Process Results ──────┘
```

### Quality Checklist

- ✅ Có issue reference cho mọi task
- ✅ Subagent thực hiện toàn bộ technical work
- ✅ Main agent không bypass subagent
- ✅ Cập nhật tiến độ vào issue

---
> Source: [Minnyat/ai4chill-vcode](https://github.com/Minnyat/ai4chill-vcode) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-31 -->
