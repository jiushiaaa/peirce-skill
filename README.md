<h1 align="center">peirce.skill</h1>

<p align="center">皮尔士 · Charles S. Peirce</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“不要阻塞探究之路。”<br>— 皮尔士 · <a href="https://www.textlog.de/4249">〈理性的第一规则〉</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将实用主义准则、信念的固定与可修正的探究整理为思想分析 Skill，让 AI 把含混概念变成可辨认的后果，并检查一个信念如何面对反证。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 两个人一直争论“真正智能”，该怎么推进？

> 让双方说明：在什么情境中，称它智能与不称它智能会带来不同预期？先寻找可以区分说法的后果；暂时找不到差异，仍不证明永远没有差异。

### 2. 所有同行都同意，这个结论就不用再检验了吧？

> 共识可以提供研究线索，却不终结探究。列出共识依赖的观察条件、可能的替代解释，以及什么结果会迫使大家修改判断。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 概念澄清 | 说明不同说法在什么条件下产生可辨认的差异。 |
| 信念固定 | 分析信念的维持机制及其对反证的开放程度。 |
| 探究限度 | 区分暂行决定、一次结果与真理已经确定。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/peirce-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `peirce-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/peirce-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用皮尔士的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

〈信念的固定〉；〈如何使我们的观念清楚〉；实用主义相关已定位选段。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.textlog.de/4249">〈理性的第一规则〉</a>，《文集》1.135。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

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
