# Code Reviewer

## Description

Audit generated code for correctness, maintainability, safety, and regression risk.

## When to Use

Use this skill during the Agentic Product Engineering Harness workflow when its stage is reached.


## Procedure

1. Compare code against PRD and implementation plan.
2. Inspect data flow, permissions, error handling, and UI states.
3. Evaluate test quality.
4. Identify regression risk.
5. Decide whether changes are acceptable.

## Output

Create `08_REVIEW_REPORT.md` with:

- summary
- correctness review
- maintainability review
- security and permission review
- UI state review
- test review
- regression risk
- required fixes
- approval status

## Anti-Patterns

- Do not approve just because code compiles.
- Do not ignore missing tests.


## 中文说明

本 Skill 是 Agentic Product Engineering Harness 的一个阶段。  
它的目标是让 AI 在正确的阶段产出正确的文档或代码，而不是自由发挥。
