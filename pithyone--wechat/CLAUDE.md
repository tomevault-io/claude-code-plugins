# wechat

> $agent = $app->get('agent');

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wechat/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# 应用管理

```php
$agent = $app->get('agent');
```

## 获取应用

```php
$agent->get();
```

## 设置应用

```php
$agent->set([
    'close' => 0
]);
```

## 获取应用列表

```php
$agent->list();
```

---
> Source: [pithyone/wechat](https://github.com/pithyone/wechat) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
