# TutorialSoul 使用方法 · User guide

[中文](#中文) · [English](#english)

## 中文

**普通对话或自定义指令。** 复制 [SKILL.md 的中文说明](SKILL.md#中文)，粘贴到对话或自定义指令中，然后告诉助手你想学会什么。如果手里有单文件 `TutorialSoul.md`，也可以直接粘贴全文。支持附件的工具可上传单文件，并请助手按文件中的方式教学。

**支持 Agent Skills 的工具。** 解压，将整个 `tutorial-soul` 文件夹放入客户端支持的技能目录。安装后应能看到 `技能目录/tutorial-soul/SKILL.md`。能否自动选用由客户端及其设置决定。

| 本地工具 | 技能目录示例 |
|---|---|
| Codex | 个人目录 `~/.codex/skills/` |
| Claude Code | 项目内 `.claude/skills/` |
| GitHub Copilot（支持技能的客户端） | 项目内 `.github/skills/` |
| Cursor | 项目内 `.cursor/skills/` |

可以直接说想学什么。如果心里已有起点，一句话就够，例如“我会＿＿，但卡在＿＿。我想听白话，关键细节请保留。” [教学示例](references/teaching-dialogues.md#中文)收录了折扣、照片、纸桥和日常写作四组对话，可按学习者的回答查找下一步讲法。

格式与目录说明见 [Agent Skills 规范](https://agentskills.io/specification)、[Claude Code](https://code.claude.com/docs/en/skills)、[GitHub Copilot](https://docs.github.com/en/copilot/concepts/customizations/agent-skills) 和 [Cursor](https://cursor.com/docs/skills)。

## English

**In a chat or in custom instructions.** Copy the [English instructions in SKILL.md](SKILL.md#english) into your chat or custom instructions, then tell the assistant what you want to learn. If you have the standalone file `TutorialSoul.md`, you can paste its full text instead. In a chat that accepts attachments, you can upload it and ask the assistant to teach you using the approach in the file.

**In a tool that supports Agent Skills.** If you downloaded an archive, extract it first. Place the entire `tutorial-soul` folder in a skills directory supported by your client. The resulting path should be `<skills-directory>/tutorial-soul/SKILL.md`. Whether the client selects the skill automatically depends on the client and its settings.

| Tool | Example skills directory |
|---|---|
| Codex | `~/.codex/skills/` in your home directory |
| Claude Code | `.claude/skills/` in your project |
| GitHub Copilot (clients that support skills) | `.github/skills/` in your project |
| Cursor | `.cursor/skills/` in your project |

Tell the assistant what you want to learn. If you know where you are getting stuck, one sentence is enough. For example, “I can do ___, but I get stuck at ___. Use plain language and keep the important details.” The four [teaching dialogues](references/teaching-dialogues.md#english) show how a tutor can respond to different answers about discounts, photographs, paper bridges, and everyday writing.

For the file format and client-specific directories, see the [Agent Skills specification](https://agentskills.io/specification), [Claude Code documentation](https://code.claude.com/docs/en/skills), [GitHub Copilot documentation](https://docs.github.com/en/copilot/concepts/customizations/agent-skills), and [Cursor documentation](https://cursor.com/docs/skills).
