<h1 align="center">mill.skill</h1>

<p align="center">穆勒 · John Stuart Mill</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“对于他自己，对于他自己的身心，个人拥有主权。”<br>— 穆勒 · <a href="https://www.gutenberg.org/cache/epub/34901/pg34901-images.html">《论自由》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将自由边界、异议检验与幸福比较整理为思想分析 Skill，让 AI 区分伤害与反感，认真处理最强反对意见，并说明干预他人需要什么理由。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 我不喜欢邻居的生活方式，可以要求禁止吗？

> 先看是否有可说明的他人损害，而不把反感直接当理由。即使存在损害，也要检查限制是否适当、有没有较少干预的办法；伤害原则不是一键裁决。

### 2. 既然尊重异议，已被证伪的说法也该得到同样权重吗？

> 表达机会与证据权重不同。可以认真回应反对意见并说明可错之处，同时依据证据拒绝已被推翻的主张；开放讨论不要求制造虚假的平衡。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 自由与干预 | 区分他人损害、本人利益与单纯不赞同。 |
| 异议检验 | 重述最强反对意见，明确什么证据会改变判断。 |
| 幸福比较 | 比较经验与能力发展，不把快乐质量变成人的等级。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/mill-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `mill-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/mill-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用穆勒的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《论自由》选段；《功利主义》幸福质量相关段落；自传及代议制度相关选段。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.gutenberg.org/cache/epub/34901/pg34901-images.html">《论自由》</a>，第一章。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
