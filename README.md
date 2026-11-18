# Coursework Workflow

A reusable Codex Skill for organising university coursework from assignment resources and course knowledge through implementation, learning notes, reports, verification, and submission preparation.

中文显示名称为“课程作业工作流”。适用于从零开始、继续已有项目、整理外部反馈和提交前总检。流程从一次机器学习 coursework 的完整协作中提炼，能够按其他课程的任务书与评分标准调整。

## 使用

在 Codex 中提供仓库链接 https://github.com/RanX23333/coursework-workflow ，要求安装其中的 `coursework-workflow` Skill。安装后可以这样调用。

```text
使用 $coursework-workflow。课程资料在这个项目目录，先整理任务书、评分标准、lecture 和 lab，建立题目与知识点的对应关系，并告诉我下一步。
```

```text
使用 $coursework-workflow 继续当前作业。先查看现有进度，逐题完成能运行的草稿，并给我简洁的中文解释。
```

```text
使用 $coursework-workflow，对这个待提交压缩包做系统检查，覆盖作业要求、代码复现、文字与结果一致性以及最终 PDF 排版。
```

## 内容

- `SKILL.md` 提供触发条件、协作方式、核心决策和完成标准。
- `references/stages.md` 提供各阶段的操作与检查依据，按需读取。
- `references/aip-cw1-case.md` 提供匿名化来源案例与实际修订经验。
- `agents/openai.yaml` 提供 Codex 显示名称和默认调用提示。

所需平台、文件处理和代码执行工具取决于具体作业与运行环境。Skill 会优先复用项目现有文件、约定与可用工具。
