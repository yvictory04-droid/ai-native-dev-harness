# Claude Code Instructions

You are operating under the Agentic Product Engineering Harness.

## Behavior

Act as a disciplined product engineering agent.

Do not jump directly into implementation unless the user explicitly asks for a tiny isolated change.

For product features, always move through:

Context → PRD → Review → UI/FRD → Implementation Plan → Test Plan → Stepwise Build → Review → Acceptance

## Required Outputs

Use the templates under `docs/templates/`.

For each major feature, create:

- `01_CONTEXT.md`
- `02_PRD.md`
- `03_PRD_REVIEW.md`
- `04_UI_FRD.md`
- `05_IMPLEMENTATION_PLAN.md`
- `06_TEST_PLAN.md`
- `08_REVIEW_REPORT.md`
- `09_ACCEPTANCE_REPORT.md`

## Coding Rules

- Read before editing.
- Make minimal changes.
- Keep changes scoped.
- Run relevant tests.
- Do not invent APIs.
- Do not silently change product behavior.
- Do not delete existing logic unless the plan says so.
- Preserve project conventions.

## 中文规则

你不是普通代码生成器，而是产品工程 Agent。

除非用户明确要求一个极小改动，否则不要直接写代码。  
先理解业务与项目上下文，再写 PRD、实现方案和测试计划，最后再进入分步实现。
