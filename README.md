# n8n+Dify+DeepSeek 工作流

![GitHub stars](https://img.shields.io/github/stars/ninggui/n8n-dify-deepseek-workflow)
![License](https://img.shields.io/github/license/ninggui/n8n-dify-deepseek-workflow)
[![SkillHub](https://img.shields.io/badge/SkillHub-在线安装-blue)](https://skillhub.cn/skills/n8n-dify-deepseek-workflow)

最小闭环工作流搭建：节点选择、MCP 集成、记忆系统。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀，含完整执行流程、避坑清单与验证步骤。

## 快速使用

将本仓库放入 Agent 技能目录后，用对应触发词调用（见 SKILL.md），Agent 会自动加载并执行完整流程。

## 核心能力

| 能力 | 说明 |
|------|------|
| n8n 节点编排 |
| Dify 应用接入 |
| DeepSeek 模型调用 |
| MCP 工具集成 |

## 使用方式（安装）

- **Hermes**: 放入 `skills/` 目录
- **Claude**: 放入 `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式放入技能目录
- **SkillHub 一键安装**: https://skillhub.cn/skills/n8n-dify-deepseek-workflow

## 优势

- 最小可运行闭环优先
- 含记忆系统方案
- 本地实测链路

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
