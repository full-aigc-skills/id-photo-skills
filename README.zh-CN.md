<div align="center">

# id-photo-skills

**证件照 (ID Photo) AIGC 技能 — 智能抠图、背景替换、预设尺寸**

[![GitHub](https://img.shields.io/badge/github-full--aigc--skills%2Fid-photo-skills-green.svg)](https://github.com/full-aigc-skills/id-photo-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-兼容-purple.svg)](https://agentskills.io)

[English](./README.md) | 简体中文

</div>

---

## 📖 简介

**id-photo-skills** 是一组 AI 编码智能体技能，属于 [Full AIGC Skills](https://github.com/full-aigc-skills) 生态。包含 **1 个技能**。

## 📦 安装

```bash
npx skills add full-aigc-skills/id-photo-skills
```

## 🎯 技能列表 (1)

| 技能 | 描述 |
|------|------|
| `id-photo` |  "生成合规证件照。两步流程：抠图裁切→换底，基于 HivisionIDPhotos API。支持一寸/二寸/小一寸/小二寸/护照/港澳通行证等预设尺寸，白底/蓝底/红底及自定义 HEX 背景色，30 |

## 🤖 支持的智能体

适用于 [Claude Code](https://code.claude.com)、[Codex](https://developers.openai.com/codex)、[Cursor](https://cursor.com)、[OpenCode](https://opencode.ai)、[Gemini CLI](https://geminicli.com)、[GitHub Copilot](https://github.com/features/copilot)、[Windsurf](https://codeium.com/windsurf) 及 [70+ 其他](https://agentskills.io/clients)。

### Claude Code 安装

**方式一：npx skills CLI（推荐）**

```bash
npx skills add full-aigc-skills/id-photo-skills
```

**方式二：手动安装**

```bash
git clone https://github.com/full-aigc-skills/id-photo-skills.git
cp -r id-photo-skills/skills/* .claude/skills/
```

## 📄 License

Apache 2.0
