<div align="center">

# 🧠 AI Decision 5-Steps

### Five AI tools, five layers, one high-stakes decision.
### 五个 AI 工具、五个层次、一次高风险决策。

**AI doesn't make the call. It shows you the price tag of every path.**
**AI 不替你做决定，它把每条路的代价摊在桌面上。**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-orange.svg)](https://claude.ai/)
[![Video Walkthrough](https://img.shields.io/badge/视频教程-小红书-red.svg)](http://xhslink.com/o/16HdIA98CmB)
[![Stars](https://img.shields.io/github/stars/wilingna/ai-decision-5steps?style=social)](https://github.com/wilingna/ai-decision-5steps)

[**🎬 Video Walkthrough**](http://xhslink.com/o/16HdIA98CmB) · [English](#english) · [中文](#中文) · [Quick Start](#-quick-start) · [Demo Case](#-demo-case--示范案例)

</div>

---

## 🎯 TL;DR

**EN** — A Claude Skill for high-stakes decisions. Instead of asking one AI for an answer, you route the work through **five specialized layers** — Perplexity for facts, Claude for structure, GPT for path simulation, GPT→Notion for systematization, GPT→Gamma for communication. The output isn't "what to do." It's a risk map across three paths so you can see what each one costs before you commit.

**中文** — 一个用于高风险决策的 Claude Skill。不再让一个 AI 给你答案，而是把决策分到**五个层次**——Perplexity 建事实池、Claude 搭结构、GPT 跑三路径推演、GPT→Notion 工程化、GPT→Gamma 出汇报。产出不是"该怎么做"，而是三条路径的风险地图，让你在做决定前看清每条路的代价。

```
Perplexity  →  Claude   →   GPT     →  Notion  →  Gamma
   facts        spine      paths      system     story
   事实池        骨架       路径推演    决策库      汇报
```

---

<a name="english"></a>
## 🌍 English

### Why a single AI fails at high-stakes decisions

Ask GPT "should we shut down this business line?" and you'll get a confident, balanced, useless answer. That's because real decisions don't fail at the *answer* — they fail at the layers underneath:

- **Bad facts** → biased answer
- **No structure** → blind spots you don't see
- **One path imagined** → no real comparison
- **No system** → you can't update when reality shifts
- **No story** → you can't get buy-in

`ai-decision-5steps` separates these five layers and assigns each to the AI tool best suited for it. You stay in the seat — the tools surface the tradeoffs.

### What you actually get

A **risk map across three paths** (e.g., shut down / restructure / hold) with:

- Sourced industry facts (Perplexity-grade citations)
- Structured internal vs. external diagnostic
- Cost, payoff, and failure mode for each path
- Notion database for ongoing decision tracking
- Executive-ready slide deck

### The principle

> **Judgment isn't picking right. Judgment is knowing whether you can afford the cost of being wrong.**

---

<a name="中文"></a>
## 🇨🇳 中文

### 为什么单一 AI 搞不定高风险决策

你问 GPT "这条业务线要不要砍掉？"，会拿到一个自信、平衡、没用的答案。因为真正的决策不会输在**答案**那一层，而是输在底下五层：

- **事实不准** → 偏见从源头就进来了
- **缺乏结构** → 你看不见自己的盲区
- **只想象了一条路** → 根本没法比较
- **没有系统** → 形势变了就重头再来
- **没有故事** → 推不动决策落地

ai-decision-5steps 把这五层拆开，每层交给最擅长的 AI 工具。判断权一直在你手里，工具只负责把权衡摊出来。

### 你能拿到的产出

一份覆盖**三条路径**（比如：裁撤 / 重组 / 持有）的风险地图，包含：

- 带来源的行业事实（Perplexity 级别引用）
- 结构化的内外部诊断
- 每条路径的代价、收益、失败模式
- 用于持续追踪决策的 Notion 数据库
- 高管级汇报 PPT

### 核心理念

> **判断力的本质，不是选对，而是权衡你能不能承担对应的代价。**

---

## 🧩 The 5 Layers · 五层架构

| Step | Layer · 层次 | Tool · 工具 | Job · 职责 |
|---|---|---|---|
| **1** | 📡 Information · 信息层 | **Perplexity** | Build a fact pool, every claim cited · 建立行业事实池，每条结论附来源 |
| **2** | 🧱 Structure · 结构层 | **Claude** | Map internal vs. external data, surface blind spots · 结构化内外部数据，找出盲区 |
| **3** | 🌐 Reasoning · 推理层 | **GPT** | Simulate 3 paths, expose the risk map · 三路径博弈推演，展开风险地图 |
| **4** | ⚙️ System · 系统层 | **GPT → Notion** | Engineer the decision into a re-runnable database · 决策工程化，可迭代复盘 |
| **5** | 🎤 Expression · 表达层 | **GPT → Gamma** | Turn it into a deck that earns buy-in · 生成让人买单的汇报 |

### 🔑 Each layer has one job — that's the point

Most "AI for decision-making" tools dump everything into one prompt. That's why they produce mush. By forcing each layer into its own tool with its own constraint, you get **traceable judgment** — you can see exactly which fact, which path, which assumption is doing the work.

大多数"AI 帮你做决策"的工具把所有事丢进一个 prompt，所以产出是稀的。把每一层强制隔离到独立工具、各自有自己的约束，你拿到的是**可追溯的判断**——清楚知道哪个事实、哪条路径、哪个假设在起作用。

---

## 🚀 Quick Start

### Option A — Install as a Claude Skill · 作为 Claude Skill 安装（推荐）

1. Download [`ai-decision-5steps.skill`](./ai-decision-5steps.skill)
2. [Claude.ai](https://claude.ai/) → Settings → Skills → Upload
3. Say to Claude: **"帮我用 AI 决策五步法分析 [your decision]"** or **"Run the 5-step decision framework on [your decision]"**

### Option B — Use the prompts directly · 直接用 Prompt

Copy the contents of [`SKILL.md`](./SKILL.md) into Claude. Done.
直接把 [`SKILL.md`](./SKILL.md) 的内容粘贴进 Claude 对话框即可。

---

## 🎯 When to Use This · 适用场景

### 🏢 Business decisions · 业务决策

- Shutting down a product line · 是否裁撤某条业务线
- Entering a new market or vertical · 是否进入新市场 / 新赛道
- Launching an AI transformation · 是否启动 AI 化转型
- Pricing model overhauls · 商业模式重构
- Org restructuring · 组织架构调整

### 🧑 Personal decisions · 个人重大决策

- PhD vs. industry job · 读博 vs. 找工作
- Building a side hustle / going solo · 做副业 / 成为超级个体
- Career pivot · 职业方向转换
- Big relocation · 重大搬迁
- Long-term relationship moves · 长期关系决策

### 🚫 When NOT to use it · 什么时候别用

This is **overkill for low-stakes choices**. Don't run a 5-tool pipeline to pick where to eat lunch. Reserve it for decisions where being wrong has a real cost — financial, time, opportunity, or relational.
**低风险选择别用这个**。决定中午吃什么不需要五个工具。这套流程留给"做错了真有代价"的决策——金钱、时间、机会成本、关系。

---

## 📊 Demo Case · 示范案例

The Skill ships with a full worked example:
Skill 内置了完整演示案例：

> **A B2B SaaS line losing $2.6M/year, growth dropped from 18% to 2%. Shut down or not?**
> **某 B 端 SaaS 业务，年亏损 1800 万，增速从 18% 跌至 2%，是否裁撤？**

The case walks through all 5 layers end-to-end: industry fact pool → structured diagnostic → 3-path simulation → Notion decision database → executive slide deck.
完整跑完五层：行业事实采集 → 结构化诊断 → 三路径推演 → Notion 决策数据库 → 高管汇报 PPT。

📖 **See [`references/demo-case.md`](./references/demo-case.md)** for the full example output.
完整示范输出见 [`references/demo-case.md`](./references/demo-case.md)。

---

## 📁 File Structure

```
ai-decision-5steps/
├── SKILL.md                    # Main Skill instructions for Claude
├── ai-decision-5steps.skill    # Packaged Skill installer
├── README.md                   # This file
└── references/
    └── demo-case.md            # Full worked example: SaaS shutdown decision
```

---

## ❓ FAQ

<details>
<summary><b>Q: Can I use just one of the five layers? · 能不能只用其中一层？</b></summary>

Yes — each layer is independently useful. But the magic comes from the chain. Skipping layers (especially Step 1's fact pool or Step 3's path simulation) is where most decisions go wrong.
当然——每一层独立使用都有价值。但威力来自串联。跳过某些层（尤其是 Step 1 的事实池和 Step 3 的路径推演）正是大多数决策出问题的地方。

</details>

<details>
<summary><b>Q: Why three different AI vendors? · 为什么要用三家不同的 AI？</b></summary>

Because they're genuinely best-in-class at different things — Perplexity for citation quality, Claude for structured thinking, GPT for adversarial path generation. Using one model for all five layers gives you that model's specific bias compounded five times.
因为它们各自真有优势——Perplexity 引用质量最好，Claude 最会结构化思考，GPT 最擅长跑对抗性路径。一个模型干完五件事，等于把它的偏见放大五倍。

</details>

<details>
<summary><b>Q: Will it tell me what to do? · 它会告诉我该怎么做吗？</b></summary>

No, by design. It surfaces the cost of each path. The decision stays with you — that's the entire philosophy.
**故意**不告诉你。它把每条路的代价摊出来。决定权一直在你手里——这是整套方法论的核心。

</details>

<details>
<summary><b>Q: How long does a full run take? · 完整跑一次要多久？</b></summary>

For a meaningful business decision: roughly **2–4 hours of focused work**, spread across the five tools. For personal decisions, often less. Compared to spending weeks ruminating without structure, that's a bargain.
正经的业务决策大概 **2–4 小时聚焦工作**，分散在五个工具里。个人决策通常更短。比起没有结构地纠结好几周，这价格挺划算。

</details>

<details>
<summary><b>Q: Is this a tool or a methodology? · 这是工具还是方法论？</b></summary>

A methodology that uses tools. The Skill encodes the methodology so Claude can guide you through it. The tools are interchangeable — what matters is the layer separation.
是一套用工具实现的方法论。Skill 把方法论编码进去让 Claude 引导你走完。工具可以替换，关键是层次的分离。

</details>

---

## 📖 The wilingna Methodology Family · 方法论家族

This is one of several "AI as system, not chatbot" workflows I've published:
这是我发布的"把 AI 当系统而不是聊天机器人"系列工作流之一：

| Repo | Domain · 领域 | Pattern · 模式 |
|---|---|---|
| **ai-decision-5steps** (this repo) | High-stakes decisions · 高风险决策 | 5-layer pipeline · 五层流水线 |
| [ai-ppt-toolkit](https://github.com/wilingna/ai-ppt-toolkit) | Slide-making · 做 PPT | 3-tool methodology · 三件套 |
| [ai-ppt-web](https://github.com/wilingna/ai-ppt-web) | Slide-making (faster) · PPT 加速版 | 1-page web app · 网页版 |
| [PPTFlux](https://github.com/wilingna/PPTFlux) | Slide-making (full loop) · PPT 闭环版 | 4-agent pipeline · 4 Agent 流水线 |
| [ai-content-pipeline](https://github.com/wilingna/ai-content-pipeline) | Content production · 内容生产 | 7-agent pipeline · 7 Agent 流水线 |

**Common thread**: AI works best when each model gets one clear job, with structured handoffs between them. The opposite of "let one model do everything."
**共同点**：AI 用得好的关键是每个模型只做一件事、模型之间有结构化交接。和"让一个模型搞定一切"完全相反。

---

## 🤝 Contributing

Issues and PRs welcome — especially:
- Demo cases for new decision types · 新决策类型的示范案例
- Localization for non-Chinese contexts · 非中文场景的本地化
- Better path-simulation prompts · 更好的路径推演 prompt

---

## 📜 License

MIT — use it, fork it, ship it.

---

## 👋 About

Built by **wilingna** ([@wilingna](https://github.com/wilingna))
Big-tech HR turned AI Systems Architect. Building AI workflows and Chinese-aesthetic digital culture for global audiences.
大厂 HR 出身的 AI Systems Architect，做 AI 工作流 / 中国传统美学数字文化出海。

### Find me · 找我

- 🎬 小红书 (Xiaohongshu): [会灵那](https://xhslink.com/m/9EL7CXk2TP5)
- 📺 B 站 (Bilibili): [会灵那](https://b23.tv/glseBuh)
- 💬 Issues: drop your decision case here, I read every one · 把你的决策案例发到 Issues，我每条都看

---

<div align="center">

### ⭐ If this changed how you think about a hard call, drop a star.
### ⭐ 如果这套方法改变了你思考某个艰难决定的方式，点个 star 吧。

> **Judgment isn't picking right. Judgment is knowing whether you can afford to be wrong.**
> **判断力的本质，不是选对，而是权衡你能不能承担对应的代价。**

</div>
