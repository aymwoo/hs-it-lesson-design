# hs-it-lesson-design

符合 [Agent Skills](https://agentskills.io) 开放标准的 skill（v1.1），供中国高中信息技术教师备课使用。依据《普通高中信息技术课程标准（2017年版2020年修订）》，对齐学科核心素养，一次输出教学设计、学生学习任务单、分层任务（基础/达标/拓展）和形成性评价工具。目录结构参照 anthropics/k12-teacher-skills。

本仓库的根目录就是 skill 本身：`SKILL.md` 放在仓库根目录，不再套一层同名文件夹。

```
hs-it-lesson-design/
├── SKILL.md                     # 元数据和工作流程
├── references/
│   ├── curriculum-hs-it.md      # 课标要点（模块、核心素养、必修内容要求原文）
│   ├── lesson-plan-template.md  # 教学设计模板
│   ├── differentiation-guide.md # 分层教学指南
│   ├── compliance.md            # 依据教育部 2025 年使用指南的合规规则
│   └── worksheet-template.md    # 学生任务单模板（v1.1）
├── evals/
│   └── rubric.csv               # 16 项量规（v1.1）
├── CHANGELOG.md
├── LICENSE                      # CC BY 4.0（本 skill 原创内容）
└── README.md
```

## 安装

把整个文件夹复制到支持 skills 的智能体的 skills 目录，文件夹名使用 `hs-it-lesson-design`。例如 Claude Code：

```bash
git clone https://github.com/aymwoo/hs-it-lesson-design.git ~/.claude/skills/hs-it-lesson-design
```

不用 git 时，下载本仓库后，把包含 `SKILL.md` 的文件夹整体复制到智能体的 skills 目录即可。

## 许可

本 skill 原创内容采用 [Creative Commons Attribution 4.0 International（CC BY 4.0）](https://creativecommons.org/licenses/by/4.0/)。课程标准原文版权归教育部及原出版方，不在本许可范围内。全文见 `LICENSE`，说明亦见 `SKILL.md` 的 `license` 字段。
