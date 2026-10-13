<h1 align="center">peirce.skill</h1>

<p align="center">皮尔士 · Charles S. Peirce</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Do not block the way of inquiry.”<br>— Charles S. Peirce · <a href="https://www.textlog.de/4249">The First Rule of Reason</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for the pragmatic maxim, the fixation of belief, and revisable inquiry: clarify concepts through conceivable consequences and examine how beliefs respond to counterevidence.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. Two people keep arguing about “real intelligence.” How can the discussion advance?

> Ask what situations would produce different expectations depending on which description is accepted. Seek consequences that distinguish the claims. Failing to find a difference now does not prove that none can exist.

### 2. All my peers agree. Can we stop testing the conclusion?

> Agreement may guide inquiry, but it does not end it. State the observational conditions, alternative explanations, and findings that would require revision.

## What is distilled

| Method | What it helps examine |
|---|---|
| Clarifying concepts | Specify conditions under which competing claims make a difference. |
| Fixation of belief | Examine how a belief is maintained and whether it can change. |
| Limits of inquiry | Distinguish provisional decisions, individual results, and settled truth. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/peirce-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `peirce-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/peirce-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Charles S. Peirce’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

The Fixation of Belief; How to Make Our Ideas Clear; documented selections on pragmatism.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.textlog.de/4249">The First Rule of Reason</a>, CP 1.135. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
