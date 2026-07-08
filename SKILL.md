---
name: xhs-keyword-design
description: "Open Skill for designing final Xiaohongshu / RedNote publishing keywords and checking natural keyword placement in title, cover copy, opening, body, and keyword field. Use when the user asks for Xiaohongshu keyword research, RedNote SEO keywords, XHS SEO, keyword placement, 小红书关键词, 小红书 SEO, 关键词埋点, 发布关键词. This Skill uses user-provided material and public-safe reasoning only; it does not publish automatically, scrape private data, copy creators, or promise growth."
---

# Xiaohongshu Keyword Design

## Purpose

为一条准备发布的小红书 / RedNote 内容设计最终 10 个发布关键词，并检查关键词是否自然埋入。

This is a lightweight standalone open Skill. It turns a repeated creator task
into a clear Agent workflow with inputs, checks, output shape, and boundaries.

## Use This For

- final 10 keywords
- keyword type labels
- where each keyword should appear
- natural embedding suggestions
- warning if keywords do not match the content
- optional revised title or opening keyword placement

## Do Not Use This For

- automatic publishing
- private account login
- private data extraction
- guaranteed traffic, growth, sales, or viral outcomes
- copying another creator's exact wording, identity, images, or claims
- making claims that the user's material does not support

## Inputs

- title
- cover copy
- first 3 lines or first 3 seconds
- body copy, script, or page text
- intended audience and track
- existing keyword list, if any

If the input is incomplete, proceed with a first-pass version and mark
assumptions. Ask only the smallest necessary follow-up when the missing detail
would materially change the result.

## Workflow

Read `references/workflow-rules.md` when the task needs the full rule set.

- Identify the core search word.
- Add industry and category words.
- Add audience or life-stage words.
- Add pain, result, and scenario words.
- Limit the final keyword field to 10.
- Check whether keywords appear naturally in title, cover, opening, body, and keyword field.

## Output Contract

```markdown
## 1. Scope And Assumptions

## 2. Input Reading

## 3. Main Judgment

## 4. Working Table Or Checklist

## 5. Recommended Next Action

## 6. Boundaries
```

## Quality Bar

- Be specific and operational.
- Prefer a small usable output over a broad lecture.
- Explain why each recommendation fits the user's material.
- Mark weak evidence instead of pretending certainty.
- Do not promise results.
- Do not copy another creator's protected expression or personal story.

## Tone

Write in the user's language. For Chinese creator tasks, default to clear,
practical Chinese.

## Public Boundary

Keep examples generic. Do not include internal thread IDs, private file paths,
unpublished customer material, private account data, or internal product notes.
