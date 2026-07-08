# XHS Keyword Design Skill

Open Skill for designing final Xiaohongshu / RedNote publishing keywords and checking natural keyword placement in title, cover copy, opening, body, and keyword field.

中文一句话：为一条准备发布的小红书 / RedNote 内容设计最终 10 个发布关键词，并检查关键词是否自然埋入。

## Search Keywords

English keywords:

`Xiaohongshu keyword research`, `RedNote SEO keywords`, `XHS SEO`, `keyword placement`, `social media SEO`, `creator keyword workflow`, `publishing keywords`, `content discoverability`, `AI skill for creators`.

中文关键词：

`小红书关键词`, `小红书 SEO`, `关键词埋点`, `发布关键词`, `行业词`, `大众词`, `场景词`, `关键词布局`, `小红书搜索优化`.

## Why This Exists


Many posts have a topic and draft, but the keywords are either too broad, too trendy, or not actually present in the content.
This Skill turns keyword design into a final publish check: core word, industry words, audience words, pain/result words, long-tail scenario words, and natural placement.

## What It Can Do

- final 10 keywords
- keyword type labels
- where each keyword should appear
- natural embedding suggestions
- warning if keywords do not match the content
- optional revised title or opening keyword placement

## Best Inputs

- title
- cover copy
- first 3 lines or first 3 seconds
- body copy, script, or page text
- intended audience and track
- existing keyword list, if any

## Workflow

- Identify the core search word.
- Add industry and category words.
- Add audience or life-stage words.
- Add pain, result, and scenario words.
- Limit the final keyword field to 10.
- Check whether keywords appear naturally in title, cover, opening, body, and keyword field.

## Output Contract

Default output:

1. Scope and assumptions
2. Input reading
3. Main judgment
4. Structured table or checklist
5. Recommended next action
6. Boundary notes

For detailed rules, see `references/workflow-rules.md`.

## Example Prompt

```text
Use $xhs-keyword-design for this task:
Title: AI 工具收藏了很多，为什么还是发不出来？
Cover: 你缺的不是工具，是内容流程
Audience: solo creators using AI for content
Body summary: a 3-step workflow for idea, draft, and review
```

## Example Output Shape

See `examples/sample-output.md` for a short sample.

## Open-Source Boundary

This standalone open version includes:

- reusable creator workflow instructions
- input and output contracts
- workflow rules
- example output
- Agent metadata
- MIT license

This standalone open version does not include:

- private platform credentials
- automatic publishing
- private analytics connectors
- scraping or monitoring
- guaranteed traffic, growth, sales, or viral outcomes
- copying another creator's content
- internal operating notes or private project context

## Repository Map

- `SKILL.md`: Agent entrypoint and workflow rules
- `agents/openai.yaml`: Agent display metadata
- `references/workflow-rules.md`: detailed workflow and quality rules
- `examples/sample-output.md`: sample input and output shape
- `LICENSE`: MIT license

## Recommended GitHub Description

> Open Skill for designing final Xiaohongshu / RedNote publishing keywords and checking natural keyword placement in title, cover copy, opening, body, and keyword field.

## Suggested GitHub Topics

`xhs-seo`, `keyword-research`, `xiaohongshu`, `rednote`, `creator-tools`, `content-workflow`, `social-media`, `ai-skill`, `open-source`

## License

MIT
