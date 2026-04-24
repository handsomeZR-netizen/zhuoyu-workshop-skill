# 项目诊断与定位

Use this reference when the user needs to understand what a student project can credibly become.

## Inputs To Collect

- Project name, project type, target audience, deadline, and grading or judging criteria.
- Existing artifacts: code, screenshots, README, report draft, experiment data, logs, videos, diagrams.
- Current state: completed features, unfinished features, known bugs, deployment status.
- Claims the user wants to make, and evidence currently available.

## Diagnosis Framework

Output the diagnosis in five parts:

1. **一句话定位**: describe the project in one sentence using `target user + problem + method + output`.
2. **真实成果**: list implemented features and available evidence.
3. **可包装亮点**: identify credible highlights from scenario, engineering, integration, data, interaction, or learning value.
4. **薄弱环节**: list gaps that will be challenged in defense or review.
5. **补齐优先级**: rank missing evidence by delivery impact.

## Credible Highlight Types

- Scenario fit: the project solves a specific learning, campus, lab, management, or research workflow problem.
- Engineering completeness: login, database, permissions, API, UI, deployment, tests, documentation.
- Integration value: combines model, front end, data, workflow, hardware, or third-party APIs into a usable prototype.
- Iteration evidence: commits, bug fixes, test records, teacher feedback, demo videos.
- Learning value: explains tradeoffs, limitations, and what the team learned through implementation.

## Anti-Inflation Rules

Replace inflated claims with verifiable wording:

- Do not say "大规模应用"; say "完成原型验证" unless real usage evidence exists.
- Do not say "显著提升"; say "具备辅助提升的应用潜力" unless controlled experiment data exists.
- Do not say "行业领先"; say "针对特定校园/课程场景进行了定制化实现".
- Do not say "已完成商业化"; say "具备后续扩展为实际应用的基础".

## Output Template

```markdown
## 项目诊断
- 一句话定位：
- 当前阶段：
- 目标用途：

## 真实成果
| 成果 | 证据 | 状态 | 可用于材料 |
|---|---|---|---|

## 可包装亮点
1.
2.
3.

## 主要风险
| 风险 | 为什么会被追问 | 建议补齐 |
|---|---|---|

## 下一步
- 先补：
- 再写：
- 最后验证：
```
