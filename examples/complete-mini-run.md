# Complete Mini Run: One Note to One Xiaohongshu Package

This example shows how the free starter is meant to be used. It is not a traffic promise. It is a repeatable packaging flow for creators who already have source material in Obsidian.

## 1. Source Note

```markdown
# Why my Xiaohongshu drafts stay unfinished

I keep saving course notes, meeting notes, book highlights, and half-written opinions in Obsidian.
The hard part is not writing from zero. The hard part is turning one source note into a finished Xiaohongshu package:

- title candidates
- body draft
- carousel page plan
- image prompts
- final publishing text
- archive folder

When I skip the package structure, everything stays in chat history and I cannot reuse the work next week.
```

## 2. Filled Brief

Use `templates/xhs-post-brief.md` and fill only the fields that matter.

```markdown
## Reader

- Target reader: creators who already use Obsidian for notes
- Current pain: many useful notes, few finished Xiaohongshu posts
- What they already tried: asking AI to rewrite one note into one post
- What they misunderstand: the missing part is not only the prompt, but the publishing package

## Core Promise

After reading this post, the reader can split one Obsidian note into a reusable Xiaohongshu publishing package.

## Angle

Tool workflow
```

## 3. Title Candidates

```text
1. Obsidian 笔记很多，但小红书还是发不出来？
2. 我把小红书发布流程固定进 Obsidian 了
3. 一条 Obsidian 素材，怎么变成小红书发布包
4. 别再只让 AI 改文案了，先把发布包建起来
5. 小红书图文卡住，多半不是不会写
```

Recommended title:

```text
一条 Obsidian 素材，怎么变成小红书发布包
```

Reason: it names the input, the output, and the workflow result.

## 4. Body Draft

```text
我之前做小红书最容易卡在这里：

Obsidian 里有很多素材，但每次要发笔记，都要重新想标题、正文、配图、标签和发布顺序。

后来我把流程拆成一个发布包：

1. 原始素材：这篇内容到底从哪来
2. 选题 brief：读者是谁，痛点是什么
3. 标题候选：先写 5 个，再选一个
4. 正文草稿：只解决一个问题
5. 轮播结构：每页只承担一个任务
6. 配图提示词：把文字层级和画面要求写清楚
7. 发布稿：标题、正文、标签、图片顺序放一起
8. 归档目录：以后复盘时能找到当时怎么做的

这个方法不保证爆款，但能解决一个更基础的问题：
不要让每次发小红书都从零开始。

如果你也用 Obsidian 管素材，可以先从一篇笔记试跑一次。
```

## 5. Carousel Page Plan

| Page | Purpose | On-image text | Visual prompt |
| --- | --- | --- | --- |
| P01 | Cover | 一条 Obsidian 素材，怎么变成小红书发布包 | clean editorial cover, Obsidian note card transforming into five Xiaohongshu carousel cards, white background, red accent, 3:4 |
| P02 | Problem | 素材很多，不等于发布完成 | scattered notes, unfinished draft blocks, muted interface, one red marker showing stuck point, 3:4 |
| P03 | Method | 发布包 = 标题 + 正文 + 轮播 + 配图 + 归档 | simple workflow diagram with five labeled columns, tidy workspace, 3:4 |
| P04 | Example | 原始笔记先变成 brief，再变成发布稿 | side-by-side before and after layout, note on left, final package on right, 3:4 |
| P05 | Boundary | 它解决流程，不承诺流量 | clear checklist, suitable and not suitable split, calm professional design, 3:4 |

## 6. Final Archive Folder

```text
发布包/
  2026-06-16_Obsidian素材变发布包_3x4/
    00-source.md
    01-brief.md
    02-title-candidates.md
    03-body-draft.md
    04-carousel-plan.md
    05-image-prompts.md
    06-final-post.md
    07-publish-order.md
    images/
      01-cover.png
      02-problem.png
      03-method.png
      04-example.png
      05-boundary.png
    manifest.json
```

## 7. Manifest Example

```json
{
  "source": "00-source.md",
  "finalTitle": "一条 Obsidian 素材，怎么变成小红书发布包",
  "ratio": "3:4",
  "imageCount": 5,
  "status": "ready_to_publish",
  "reviewNotes": [
    "No traffic promise",
    "No private paths",
    "One clear workflow result"
  ]
}
```

## When the Free Starter Is Enough

The free starter is enough if you only need a manual structure and you are comfortable writing the title, body, prompts, and final package by hand.

The paid pack is for people who want the packaged plugin, install guide, first-run workflow, prompt guide, troubleshooting FAQ, sample post packages, and delivery boundary in one downloadable bundle:

https://ronnie2025.github.io/ai-agent-workbench-starter-pack/xhs-obsidian-workflow-xianyu.html
