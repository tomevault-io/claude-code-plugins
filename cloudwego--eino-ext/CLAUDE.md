# eino-ext

> import "github.com/cloudwego/eino-ext/components/model/gemini"

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/eino-ext/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Gemini ChatModel

```
import "github.com/cloudwego/eino-ext/components/model/gemini"
```

## Configuration

```go
client, _ := genai.NewClient(ctx, &genai.ClientConfig{APIKey: "your-key"})

chatModel, err := gemini.NewChatModel(ctx, &gemini.Config{
    Client: client,             // Required: *genai.Client
    Model:  "gemini-2.5-flash", // Required
    ThinkingConfig: &genai.ThinkingConfig{
        IncludeThoughts: true,
    },
})
```

---
> Source: [cloudwego/eino-ext](https://github.com/cloudwego/eino-ext) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
