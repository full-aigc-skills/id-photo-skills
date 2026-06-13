<div align="center">

# id-photo-skills

**证件照 (ID Photo) AIGC skills — smart cutout, background replacement, preset sizes**

[![GitHub](https://img.shields.io/badge/github-full--aigc--skills%2Fid-photo-skills-green.svg)](https://github.com/full-aigc-skills/id-photo-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-purple.svg)](https://agentskills.io)

English | [简体中文](./README.zh-CN.md)

[Introduction](#-introduction) · [Install](#-install) · [Skills](#-skills) · [Supported Agents](#-supported-agents) · [Ecosystem](#-ecosystem)

</div>

---

## 📖 Introduction

**id-photo-skills** is a curated collection of Agent Skills for AI coding agents, part of the [Full AIGC Skills](https://github.com/full-aigc-skills) ecosystem.

This package includes **1 skills**. Each skill is a self-contained `SKILL.md` file that AI agents load on-demand.

## 📦 Install

```bash
npx skills add full-aigc-skills/id-photo-skills
```

Or install specific skills: `npx skills add full-aigc-skills/id-photo-skills --skill <skill-name>`

## 🎯 Skills (1)

| Skill | Description |
|-------|-------------|
| `id-photo` |  "生成合规证件照。两步流程：抠图裁切→换底，基于 HivisionIDPhotos API。支持一寸/二寸/小一寸/小二寸/护照/港澳通行证等预设尺寸，白底/蓝底/红底及自定义 HEX 背景色，30 |

## 🤖 Supported Agents

Works with [Claude Code](https://code.claude.com), [Codex](https://developers.openai.com/codex), [Cursor](https://cursor.com), [OpenCode](https://opencode.ai), [Gemini CLI](https://geminicli.com), [GitHub Copilot](https://github.com/features/copilot), [Windsurf](https://codeium.com/windsurf), and [70+ others](https://agentskills.io/clients).

### Claude Code Installation

**Option 1: npx skills CLI (Recommended)**

```bash
npx skills add full-aigc-skills/id-photo-skills
```

**Option 2: Manual Installation**

```bash
git clone https://github.com/full-aigc-skills/id-photo-skills.git
cp -r id-photo-skills/skills/* .claude/skills/
```

For more details, see the [Claude Code Skills Guide](https://code.claude.com/docs/en/skills) and [Agent Skills Spec](https://agentskills.io/).

## 🌐 Ecosystem

| Resource | Link |
|----------|------|
| **Full AIGC Skills** | [github.com/full-aigc-skills](https://github.com/full-aigc-skills) |
| **Agent Skills Spec** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 License

Apache 2.0 — see [LICENSE](LICENSE).
