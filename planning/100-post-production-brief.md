# 100-Post Literature Production Brief

Owner request: Create 100 detailed, well-written Literature By Edumynt posts.

## Workflow

Two-agent pipeline:

1. **Research / Outline Agent**
   - Inspect existing posts before choosing topics.
   - Create a 100-topic non-duplicate production queue.
   - For each topic, create a detailed outline with research/grounding notes.
   - Output files:
     - `planning/research-outline-queue.md`
     - `planning/outlines/<NNN>-<slug>.md`

2. **Writer / Builder Agent**
   - Consume outlines one by one from `planning/research-outline-queue.md`.
   - Create production MDX posts in `src/content/posts/en/<slug>.mdx`.
   - Run `npx -y bun@1.3.14 run build` after each post.
   - Fix build errors before continuing.
   - Update `planning/continuous-literature-posts-log.md` after each completed post.

## Hard Rules

- Do not repeat existing topics.
- Do not overwrite existing posts unless explicitly asked.
- Do not commit or push.
- Quality over speed: detailed, structured, general-audience literary analysis.
- Style: similar to existing Literature posts, inspired by LitCharts-level depth.
- Not ELI5. Not exam-crammy.
- Pure English SEO-friendly titles.
- Include post-specific outline/research before writing each post.
- Frontmatter format:

```yaml
---
title: "..."
description: "..."
pubDate: 2026-05-17
updatedDate: 2026-05-17
tags:
  - ...
categories:
  - ...
translationKey: <slug>
toc: true
---
```

## Existing Topics to Avoid

Current existing topics include, at minimum:

- allegory in literature
- allusion in literature
- characterization in literature
- conflict in literature
- foreshadowing and flashback
- hyperbole and understatement
- imagery in literature
- irony in literature
- metaphor and simile
- personification and anthropomorphism
- point of view in literature
- setting and atmosphere
- sound devices in literature
- symbolism in literature
- theme in literature
- tone and mood
- plot in literature

Agents must inspect `src/content/posts/en/` directly for the latest list before acting.
