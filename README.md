# 🧠 AI 决策五步法 Skill

> 用五个 AI 工具，完成一次价值百万的业务决策分析。

---

## 这是什么？

这是一个 **Claude Skill**，帮你用分层结构完成高质量决策分析。

不是让 AI 给你答案——而是用 AI 做**路径推演**，把每条路的代价和收益摊在桌面上，判断权始终在你自己手里。

配套视频教程：**[👉 点这里看完整视频演示](#)**（B站/小红书链接）

---

## 工具分工

每个工具只做它最擅长的事：

| 步骤 | 层次 | 工具 | 做什么 |
|------|------|------|--------|
| Step 1 | 信息层 | **Perplexity** | 建立行业事实池，每条结论附来源 |
| Step 2 | 结构层 | **Claude** | 结构化梳理内外部数据，找出信息盲区 |
| Step 3 | 推理层 | **GPT** | 三路径博弈推演，展开风险地图 |
| Step 4 | 系统层 | **GPT → Notion** | 决策工程化，生成可迭代的决策数据库 |
| Step 5 | 表达层 | **GPT → Gamma** | 生成汇报大纲，一键 PPT |

---

## 适用场景

**企业/业务决策**
- 是否裁撤某条业务线
- 是否进入新市场/新赛道
- 是否启动 AI 化转型

**个人重大决策**
- 读博 vs 找工作
- 要不要做副业/成为超级个体
- 下一步职业方向怎么选

---

## 快速开始

### 方法一：安装 Skill（推荐）

1. 下载 [`ai-decision-5steps.skill`](./ai-decision-5steps.skill)
2. 在 Claude.ai → Settings → Skills → Upload 安装
3. 对 Claude 说："**帮我用 AI 决策5步法分析 [你的决策问题]**"

> 💡 同系列工具：[ai-ppt-toolkit](https://github.com/wilingna/ai-ppt-toolkit) · [ai-ppt-web](https://github.com/wilingna/ai-ppt-web)

### 方法二：直接使用 Prompt

直接把 [`SKILL.md`](./SKILL.md) 的内容粘贴进 Claude 对话框即可使用。

---

## 文件结构

```
ai-decision-5steps/
├── SKILL.md                    # Skill 主文件（Claude 的完整指令）
├── ai-decision-5steps.skill    # 打包好的 Skill 安装文件
├── README.md                   # 本文件
└── references/
    └── demo-case.md            # 示范案例：B端SaaS业务裁撤决策（含完整示例输出）
```

---

## 示范案例

Skill 内置了一个完整的演示案例：

> 某 B 端 SaaS 业务，年亏损 1800 万，增速从 18% 跌至 2%，是否裁撤？

五步走完，从行业数据采集到三路径推演，再到 Notion 决策数据库 + 高管汇报 PPT，全流程示范。详见 [`references/demo-case.md`](./references/demo-case.md)

---

## 核心理念

```
信息层：只建事实池，不做判断
结构层：把散装信息变成思维骨架
推理层：展开路径风险地图，不给唯一答案
系统层：决策工程化，可迭代、可复盘
表达层：让你的思考"看起来很贵"
```

判断力的本质，不是选对，而是**权衡你能不能承担对应的代价**。

---

## 配套 Prompt 包

评论区 / Issues 里留言「**决策**」，获取完整 Prompt 包（含所有步骤的 Prompt 模板）。

---

## 关于作者

> 如果这个 Skill 对你有帮助，欢迎 ⭐ Star 支持！

同系列项目：
- 📊 [ai-ppt-toolkit](https://github.com/wilingna/ai-ppt-toolkit) — AI 做 PPT 三件套 Skill
- 🌐 [ai-ppt-web](https://github.com/wilingna/ai-ppt-web) — AI 做 PPT 网页版工具

- 视频主页：[链接]
- 小红书：[链接]
- B站：[链接]
