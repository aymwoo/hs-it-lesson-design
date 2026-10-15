# hs-it-lesson-design

符合 Agent Skills 开放标准（agentskills.io）的 skill，供中国高中信息技术教师备课使用。目录结构参照 anthropics/k12-teacher-skills。

```
hs-it-lesson-design/
├── SKILL.md                     # 元数据和工作流程
├── references/
│   ├── curriculum-hs-it.md      # 课标要点（模块、核心素养、必修内容要求原文）
│   ├── lesson-plan-template.md  # 教学设计模板
│   ├── differentiation-guide.md # 分层教学指南
│   ├── compliance.md            # 依据教育部 2025 年使用指南的合规规则
│   └── worksheet-template.md    # 学生任务单模板（v1.1）
└── evals/rubric.csv             # 16 项量规（v1.1）
├── CHANGELOG.md
```

**安装方法**：把整个文件夹放入支持 skills 的智能体的 skills 目录，例如 Claude Code 的 `~/.claude/skills/`。
