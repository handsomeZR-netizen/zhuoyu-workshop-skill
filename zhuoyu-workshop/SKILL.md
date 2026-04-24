---
name: zhuoyu-workshop
description: Student project delivery and packaging workflow for Codex. Use when the user needs help with Chinese university student projects, course projects, innovation training projects, competitions, capstones, graduation projects, project defense decks, closing reports, README/GitHub showcase materials, software copyright materials, paper/report polishing, or AI-assisted coding tasks that must become credible, verifiable student deliverables.
---

# 琢玉工坊

把学生项目从“能跑、能讲一点”打磨成“材料完整、表达可信、答辩可交付”的工作流。

核心原则：**玉不琢，不成器；项目不理，不成章。**

## Operating Rules

- Ground the work in supplied artifacts first: repo files, report drafts, screenshots, logs, datasets, rubrics, competition notices, or teacher requirements.
- Do not invent awards, users, metrics, experiments, patents, software copyright status, deployment results, model accuracy, or paper conclusions.
- Prefer honest enhancement: clarify value, repair structure, expose evidence, improve wording, and add missing verification.
- Use student-appropriate language: credible, specific, not over-commercialized, not inflated with terms like "world-leading" unless evidence exists.
- For code tasks, use minimum viable changes, preserve user work, and define validation before claiming completion.
- If critical inputs are missing, ask only for the missing material that changes the deliverable; otherwise proceed with clearly stated assumptions.

## Route The Task

Classify the user request, then load only the matching reference file:

- **项目诊断与定位**: read `references/project-diagnosis.md` when the user needs to understand project value, current gaps, technical route, innovation points, or how to turn rough materials into a coherent story.
- **成果包装与交付材料**: read `references/delivery-packaging.md` when creating closing reports, achievement matrices, GitHub README, software copyright material drafts, competition submissions, or project portfolios.
- **答辩与展示**: read `references/presentation-defense.md` when generating PPT outlines, speaker notes, demo scripts, judge Q&A, or defense rehearsals.
- **论文与报告**: read `references/paper-report.md` when polishing papers, course reports, abstracts, references, LaTeX/Word structure, formatting checks, or academic wording.
- **AI 编程辅助**: read `references/ai-coding-workflow.md` when using Codex for bug diagnosis, feature implementation, code review, refactoring, tests, or project cleanup.

When a request spans multiple routes, start with project diagnosis, then add the most relevant delivery route. Do not load every reference by default.

## Standard Workflow

1. **Inventory**: identify available materials, missing evidence, target audience, deadline, grading or judging criteria, and forbidden claims.
2. **Diagnose**: separate real achievements from weak assumptions; list gaps that block delivery.
3. **Shape**: choose the deliverable structure and narrative: problem, method, implementation, validation, result, reflection.
4. **Produce**: generate concrete artifacts such as outlines, copy, checklists, prompts, README sections, report sections, or code-change plans.
5. **Verify**: provide an acceptance checklist and mark which claims require screenshots, logs, data, citations, or teacher confirmation.

## Required Output Pattern

For most tasks, respond in this structure unless the user asks for a specific format:

```markdown
## 任务判断
- 场景：
- 目标受众：
- 现有材料：
- 关键风险：

## 交付方案
- 推荐结构：
- 需要补齐的证据：
- 执行步骤：

## 可直接使用的内容
[根据任务生成 PPT 大纲、报告正文、README、答辩讲稿、提示词或代码计划]

## 验收清单
- [ ] 事实可验证
- [ ] 材料可追溯
- [ ] 表达不过度包装
- [ ] 输出符合指定格式
```

For code tasks, add:

```markdown
## 修改边界
- 允许修改：
- 禁止修改：
- 回滚方式：

## 验证命令
- 命令：
- 期望结果：
```

## Packaging Standards

Use these standards for all student-facing deliverables:

- **项目价值**: express as a concrete problem solved for a clear user or learning scenario.
- **技术路线**: explain architecture and implementation choices in plain engineering language.
- **创新点**: state only what is genuinely different in method, integration, scenario, data, or interaction.
- **成果证据**: tie every claim to demo screenshots, commits, test logs, experiment tables, surveys, or teacher/project requirements.
- **不足与展望**: mention limitations honestly, then propose feasible next steps.

## Prompt Generator

When the user asks for "给我一个提示词" or "让 Codex/AI 帮我做", generate a copy-ready prompt with:

- Role: what expert the AI should act as.
- Task: the exact deliverable.
- Inputs: materials, constraints, audience, and target format.
- Process: analyze first, produce second, verify last.
- Boundaries: no fabrication, no unsupported claims, preserve original meaning.
- Output: explicit Markdown, PPT outline, report section, code plan, or checklist.
- Acceptance criteria: what makes the result usable.

## Red Lines

- Never fabricate project history, deployment scale, team contribution, citations, interview results, awards, or generated test outcomes.
- Never disguise unimplemented features as completed features.
- Never claim "已完成软著/论文录用/竞赛获奖" unless the user provides evidence.
- Never recommend changing academic data to make results look better.
- Never turn a small student project into a fake startup pitch unless the user explicitly needs a business-plan framing and the uncertainty is disclosed.
