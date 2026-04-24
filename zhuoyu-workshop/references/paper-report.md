# 论文与报告

Use this reference for paper/report polishing, abstracts, structure checks, LaTeX or Word formatting guidance, citation sanity checks, and academic wording.

## Academic Integrity Rules

- Do not invent citations, DOI, journal names, experiment results, survey data, or baseline comparisons.
- Do not rewrite results to imply stronger conclusions than the data supports.
- Mark missing evidence explicitly.
- Preserve the user's original technical meaning unless asked to restructure.

## Report Review Checklist

Check:

- Title matches actual scope.
- Abstract includes background, method, result, and conclusion.
- Introduction explains problem and motivation.
- Method section is reproducible enough.
- Experiments or tests describe data, environment, metrics, and results.
- Figures and tables have numbers, titles, and in-text references.
- References are consistently formatted and actually cited.
- Conclusion states limitations and future work.

## Abstract Pattern

Use this pattern:

```text
针对[问题/场景]中存在的[痛点]，本文/本项目设计并实现了[系统/方法]。
系统采用[关键技术路线]，完成了[核心功能/模块]。
通过[测试/实验/演示方式]，验证了[可证明的结果]。
结果表明，该方案在[具体范围]内具有[价值]，但仍存在[限制]，后续可从[方向]进一步改进。
```

## Wording Control

Prefer cautious wording:

- "验证了系统原型的可行性"
- "在测试样例中表现稳定"
- "具备进一步扩展的基础"
- "可作为教学/管理/实验流程的辅助工具"

Avoid unsupported wording:

- "显著提升"
- "完全解决"
- "国内首创"
- "达到工业级"
- "广泛应用"

## LaTeX/Word Formatting Guidance

When asked to fix formatting:

- Inspect the template or school requirement first if available.
- Preserve existing section hierarchy unless clearly broken.
- For LaTeX, prefer minimal changes to packages and class files.
- For Word-style guidance, provide a checklist instead of pretending to edit a `.docx` unless the file is available and editable.

## Output Template

```markdown
## 格式与结构诊断
- 主要问题：
- 高风险问题：
- 可快速修复：

## 修改建议
| 位置 | 问题 | 建议 | 原因 |
|---|---|---|---|

## 可替换文本
[摘要、引言、结论或章节文本]

## 需要用户确认
- 数据：
- 引用：
- 学校格式：
```
