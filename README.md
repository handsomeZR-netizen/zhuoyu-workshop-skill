# Zhuoyu Workshop Skill

<!-- PORTFOLIO-SNAPSHOT:START -->
<p align="left">
  <img src="https://img.shields.io/badge/category-AI--assisted%20workflow%20tooling-blue" alt="Category" />
  <img src="https://img.shields.io/badge/status-Public%20portfolio%20artifact-2ea44f" alt="Status" />
</p>

> Codex skill for student project delivery: reports, defense decks, academic writing, and reusable AI-assisted engineering workflows.

## Project Snapshot

- Category: AI-assisted workflow tooling
- Stack: ai-workflow, chinese, codex-skill, student-projects, defense-ppt
- Status: Public portfolio artifact

## What This Demonstrates

- Presents the project with a clear purpose, technology stack, and review path.
- Shows applied AI workflow design in a concrete product or learning scenario.
- Keeps implementation details and usage notes close to the code for easier reuse.

## Quick Start

```bash
Start from README.md
```

<!-- PORTFOLIO-SNAPSHOT:END -->

## Original Documentation

> 玉不琢，不成器；项目不理，不成章。

**琢玉工坊** 是一个面向中国大学生项目交付场景的 Codex Skill，帮助把课程设计、大创、竞赛、毕设、科研小项目从零散材料打磨成可答辩、可展示、可归档的交付成果。

它不负责“编故事”，而是帮助你把真实项目讲清楚：项目价值是什么、技术路线是否完整、成果证据在哪里、答辩怎么组织、README 和结题报告如何写得可信。

## 适合谁

- 需要准备大创、互联网+、挑战杯、课程设计、毕设答辩的学生。
- 有代码或报告雏形，但不知道如何包装项目成果的团队。
- 想用 Codex 做项目诊断、README 优化、报错定位、最小代码修改的开发者。
- 需要把论文、课程报告、结题材料改得更规范、更能验收的人。

## 能做什么

- **项目诊断**：梳理项目定位、用户场景、技术路线、创新点和短板。
- **成果包装**：生成结题报告结构、成果矩阵、GitHub README、软著材料草稿。
- **答辩展示**：输出 PPT 大纲、讲稿、演示路线、评委问答和时间分配。
- **论文报告**：优化摘要、章节结构、参考文献说明、格式检查清单。
- **AI 编程辅助**：让 Codex 按“先分析、再修改、最后验收”的方式处理报错、功能开发和代码审查。

## 仓库结构

```text
zhuoyu-workshop-skill/
├── zhuoyu-workshop/
│   ├── SKILL.md
│   ├── agents/openai.yaml
│   └── references/
├── docs/
├── examples/
└── README.md
```

`zhuoyu-workshop/` 是真正的 Skill 目录。`docs/` 和 `examples/` 是给人看的使用说明，不会在 Skill 触发时默认加载。

## 安装

把 `zhuoyu-workshop/` 复制到 Codex skills 目录：

```powershell
Copy-Item -Recurse .\zhuoyu-workshop $env:USERPROFILE\.codex\skills\
```

如果你使用 Git 克隆：

```powershell
git clone https://github.com/handsomeZR-netizen/zhuoyu-workshop-skill.git
Copy-Item -Recurse .\zhuoyu-workshop-skill\zhuoyu-workshop $env:USERPROFILE\.codex\skills\
```

安装后，在 Codex 中直接描述学生项目交付任务即可触发，例如：

```text
使用琢玉工坊帮我把这个课程设计项目整理成答辩材料，需要包含项目亮点、PPT 大纲、演示脚本和评委可能问的问题。
```

## 快速示例

```text
我的项目是一个基于 Next.js + Supabase 的实验预约系统，现在有代码和简单 README。
请用琢玉工坊帮我：
1. 诊断项目目前能包装成哪些成果；
2. 重写 GitHub README 结构；
3. 生成 8 页答辩 PPT 大纲；
4. 列出还缺哪些截图、测试记录和演示材料。
限制：不能虚构用户量、上线结果和获奖信息。
```

## 使用原则

- 只包装真实存在或可补充验证的内容。
- 不虚构数据、奖项、软著、论文录用、用户规模。
- 不把普通学生项目强行包装成商业项目。
- 代码任务必须有修改边界、验证命令和回滚思路。
- 答辩材料必须能被截图、日志、实验表格、提交记录或演示视频支撑。

## 详细文档

- [使用指南](docs/usage-guide.md)
- [场景配方](docs/scenario-recipes.md)
- [提示词模式](docs/prompt-patterns.md)

## 示例

- [大创项目包装](examples/student-innovation-project.md)
- [答辩 PPT 生成](examples/defense-ppt.md)
- [结题报告整理](examples/closing-report.md)
- [GitHub README 优化](examples/github-readme.md)
- [Codex 报错诊断](examples/codex-debugging.md)
