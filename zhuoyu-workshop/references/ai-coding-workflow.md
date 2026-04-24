# AI 编程辅助

Use this reference when the student project needs Codex help for debugging, feature implementation, review, refactoring, tests, README repair, or project cleanup.

## Safety Workflow

1. Inspect first: read errors, relevant files, configs, package scripts, and git status.
2. State the likely cause before editing.
3. Choose the smallest change that can solve the issue.
4. Avoid broad rewrites, dependency churn, and formatting-only changes mixed with logic changes.
5. Run targeted validation.
6. Explain what changed and what remains risky.

## Required Boundaries

For every code task, identify:

- Allowed files or modules.
- Forbidden files or modules.
- Data or credentials that must not be touched.
- Existing user changes that must not be overwritten.
- Rollback path.

## Debugging Template

```markdown
## 问题判断
- 报错现象：
- 复现路径：
- 最可能原因：
- 需要确认：

## 最小修改方案
- 修改范围：
- 修改逻辑：
- 不改的内容：

## 验证
- 命令：
- 手动步骤：
- 期望结果：

## 回滚
- 回滚文件：
- 回滚方式：
```

## Code Review Template

```markdown
## Findings
| 严重级别 | 文件/位置 | 问题 | 影响 | 建议 |
|---|---|---|---|---|

## Missing Tests
- 

## Residual Risks
-
```

## Student Project Bias

For student projects, prefer improvements that make the project easier to defend:

- Clear error handling.
- Reproducible setup.
- Seed data or demo account, if safe.
- Screenshots and documented demo route.
- README instructions that a teacher can follow.
- Tests or manual verification records.

## Avoid

- Rewriting the whole stack to look more advanced.
- Adding unused AI/blockchain/microservice components for packaging value.
- Hiding limitations in code or documentation.
- Changing data or evaluation scripts to improve claimed results.
