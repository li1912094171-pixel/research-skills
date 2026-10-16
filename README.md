# 科研 Skills 精选
为 SCI 论文管线精选的 4 个 AI Skill（Claude Code / Codex / OpenCode 等 Agent 可直接调用）。

## Skills

| Skill | 来源 | 用途 |
|---|---|---|
| `idea-evaluator` | Supervisor-Skills（HKUSTDial） | 选题评估：五维框架打分、致命缺陷审查 |
| `pre-submission-reviewer` | Supervisor-Skills（HKUSTDial） | 投稿前自查：章节逻辑、LaTeX 规范、语法 |
| `paper-polish` | Supervisor-Skills（HKUSTDial） | 论文润色：学术短语库、AI 腔调 guardrails |
| `nature-figure` | nature-skills（Yuan1z0825） | 科研绘图：Nature 风格图表模板、版式审计脚本 |

## 来源与协议

- `idea-evaluator` / `pre-submission-reviewer` / `paper-polish` 取自 HKUSTDial/Supervisor-Skills，遵循 CC BY-NC-SA 4.0（仅非商业使用），协议文本见 LICENSE-supervisor-skills-CC-BY-NC-SA-4.0.txt。
- `nature-figure` 取自 Yuan1z0825/nature-skills，遵循 Apache-2.0，协议文本见 LICENSE-nature-skills-Apache-2.0.txt。

本仓库仅做精选搬运，未修改 skill 原内容；版权归原作者所有。

Skills 位于 `.agents/skills/`，Codex 可自动发现调用。
