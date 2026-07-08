# 小红书关键词设计 Skill

这是一个给小红书 / RedNote 创作者用的开源轻量 Skill：当你已经有一篇内容、标题、封面或口播稿时，它帮你设计最终发布用的 10 个关键词，并检查这些关键词有没有自然地出现在标题、封面、前三行、正文和关键词栏里。

很多小红书内容不是没有价值，而是关键词太散：

- 标题写的是一个词，正文讲的是另一个词。
- 关键词栏堆了热门词，但内容里没有自然出现。
- 只写了大词，比如“AI”“职场”“自媒体”，没有场景词和长尾词。
- 用户真正会搜的词，没有被放到封面、开头或正文里。

这个 Skill 解决的是发布前最后一公里：让内容的搜索词、用户场景和正文表达对齐。

## 你下载后可以用它做什么

- 为一条准备发布的小红书内容设计最终 10 个发布关键词。
- 区分核心词、行业词、人群词、痛点词、结果词和场景长尾词。
- 检查关键词有没有自然出现在标题、封面、前三行、正文和关键词栏。
- 删除和内容不匹配、过泛、过热但没承接的词。
- 提供更自然的关键词埋入建议。
- 帮你判断这条内容到底应该被什么人搜到。

## 适合谁

- 已经写好小红书内容，但不知道关键词怎么填的人。
- 想做小红书 SEO、搜索流量、长尾内容的人。
- 标题和正文都有了，但关键词一填就很别扭的创作者。
- 做本地生活、AI 工具、职场、旅行、知识类内容的人。
- 给客户做发布检查，希望有一套稳定关键词判断流程的人。

## 为什么这个 Skill 值得单独装

普通关键词建议容易变成“热门词列表”。但热门词不一定适合你的内容。

这个 Skill 会按 5 层来组织关键词：

1. 核心搜索词：这条内容最应该被哪个词搜到。
2. 行业/赛道词：内容属于哪个领域。
3. 人群词：谁最需要这条内容。
4. 痛点/结果词：用户为什么要点进来。
5. 场景长尾词：用户在什么具体场景下会搜。

最后它只保留 10 个最适合发布的词，避免关键词栏变成杂货铺。

## 3 分钟上手

把这个仓库里的 `SKILL.md` 放到你的 Agent Skill 目录，然后这样问：

```text
用 xhs-keyword-design 帮我设计最终 10 个小红书关键词。
标题：收藏了 20 个 AI 工具，为什么还是发不出来？
封面：你缺的不是工具，是内容流程
前三行：很多人不是不会用 AI，而是没有把工具接进自己的发布流程。
正文概要：讲一个从选题、写稿到复盘的 3 步流程。
目标读者：想稳定更新的创作者
```

## 你会拿到什么结果

默认输出会包括：

- 最终 10 个关键词。
- 每个关键词的类型标签。
- 哪些词应该放在标题、封面、前三行、正文、关键词栏。
- 哪些词不适合这条内容。
- 更自然的关键词嵌入建议。
- 发布前关键词一致性提醒。

## 公开版边界

这个开源版不登录平台，不读取私密后台，不承诺搜索排名。它只基于你提供的标题、封面、正文和目标人群，帮你把关键词设计得更清楚、更自然、更适合发布。

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
