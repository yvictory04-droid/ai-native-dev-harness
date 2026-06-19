# Agent Operating Instructions

This repository uses the Agentic Product Engineering Harness.

## Prime Directive

Do not start from code.

Start from context, product intent, boundaries, implementation planning, and verification.

## Required Workflow

For every non-trivial feature, follow this order:

1. Produce `01_CONTEXT.md`
2. Produce `02_PRD.md`
3. Produce `03_PRD_REVIEW.md`
4. Produce `04_UI_FRD.md`
5. Produce `05_IMPLEMENTATION_PLAN.md`
6. Produce `06_TEST_PLAN.md`
7. Implement one small step at a time
8. Run relevant tests after each step
9. Produce `08_REVIEW_REPORT.md`
10. Produce `09_ACCEPTANCE_REPORT.md`

## Rules

- Do not write code before context is clear.
- Do not implement before PRD is approved.
- Do not make large uncontrolled edits.
- Do not skip tests.
- Do not merge or claim completion without acceptance criteria.
- Prefer small, reversible commits.
- When requirements are ambiguous, stop and ask for clarification.
- When changing behavior, update tests.
- When changing UI, include empty, loading, error, success, and permission states.

## 中文说明

本项目使用 Agentic Product Engineering Harness。

核心规则：

- 不要直接从代码开始。
- 先做上下文分析。
- 再写 PRD。
- 再写 UI / FRD。
- 再写实现方案。
- 再写测试计划。
- 最后才分步骤写代码。
- 每一步都要可审查、可测试、可回滚。
