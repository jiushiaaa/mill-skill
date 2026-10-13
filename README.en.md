<h1 align="center">mill.skill</h1>

<p align="center">穆勒 · John Stuart Mill</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Over himself, over his own body and mind, the individual is sovereign.”<br>— John Stuart Mill · <a href="https://www.gutenberg.org/cache/epub/34901/pg34901-images.html">On Liberty</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for liberty, dissent, and comparisons of happiness: distinguish harm from dislike, engage the strongest objection, and examine the grounds for interference.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. May I demand a ban on a neighbour’s lifestyle because I dislike it?

> Identify a defensible harm to others rather than treating dislike as sufficient. Even where harm exists, examine proportionality and less intrusive alternatives. The harm principle is not an automatic verdict.

### 2. Does respecting dissent mean giving disproven claims equal weight?

> Opportunities to speak differ from evidential weight. Take objections seriously and acknowledge fallibility while rejecting claims contradicted by evidence. Open discussion does not require false balance.

## What is distilled

| Method | What it helps examine |
|---|---|
| Liberty and intervention | Distinguish harm to others, personal welfare, and mere disapproval. |
| Testing dissent | State the strongest objection and what would change the judgment. |
| Comparing happiness | Consider experience and developed capacities without ranking people’s worth. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/mill-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `mill-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/mill-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use John Stuart Mill’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selections from On Liberty and Utilitarianism; relevant passages from the Autobiography and writings on representative government.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.gutenberg.org/cache/epub/34901/pg34901-images.html">On Liberty</a>, chapter I. English wording is translated where the source is not English; Chinese quotations are repository translations.

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
