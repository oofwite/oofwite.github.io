---
layout: about
title: About
permalink: /
subtitle: LLM agents · Multi-agent systems · Graph learning

profile:
  align: right
  image: yifang-chen.jpg
  image_circular: false # crops the image to make it circular
  more_info:

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi! I am **Yifang (Mark) Chen (陈义方)**, a senior at [New York University Shanghai](https://shanghai.nyu.edu/), majoring in Computer Science with a minor in Mathematics.

I am currently a Research Assistant at the Data Intelligence and Reasoning Lab at NYU Shanghai, advised by Prof. [Qiaoyu Tan](https://qiaoyu-tan.github.io/index.html). I am also fortunate to be co-advised by Prof. [Jinyang Li](https://jinyangli.github.io/) on my research project.

> **I am applying to PhD programs for Fall 2027.** If my interests overlap with your group, I would be glad to hear from you!
>
> [Email](mailto:yc6990@nyu.edu) (yc6990@nyu.edu) · [CV (PDF)]({{ '/assets/pdf/yifang-chen-cv.pdf' | relative_url }})

## Research Interests

- **Long-horizon LLM agents:** Agents that plan, search, and use tools over many steps, and that can tell when a task is harder than it first looked. I am interested in training them, largely with reinforcement learning, to decide when to keep going, change course, or stop.
- **Efficient and trustworthy agents:** An agent that searches twelve times when two would do wastes compute, and one that stops too early gets the answer wrong. I want agents that spend effort where it matters and know when their evidence is enough, along with evaluations that measure cost and reliability, not just accuracy.
- **Multi-agent systems:** How specialized agents should divide work, communicate, and combine their reasoning. In [GraphMAS](https://arxiv.org/abs/2609.39777), choosing the right specialists for each instance gave a better accuracy-cost trade-off than adding more interaction between agents. I want to understand when coordination actually helps.
- **Graphs and structure for agents:** Much of what an agent works with is relational, from retrieved evidence to memory and tool outputs. Building on my graph learning work, including [OMG-VLM](https://arxiv.org/abs/2607.19128), I am interested in using graph structure as context, memory, or a tool that helps agents organize information and reason over it.

## Awards & Honors

- **2026 NYU Shanghai Recognition Award** (Top 88)
- **2025 Baosteel Outstanding Student Scholarship** (Top 2 across all majors and classes, ~0.25%)
- **2025 NYU Shanghai Recognition Award** (Top 75, ~4%)

<style>
  h2 a[href="/news/"],
  h2 a[href="/publications/"] {
    text-transform: capitalize;
  }
</style>
