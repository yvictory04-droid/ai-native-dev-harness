# Stepwise Builder

## Description

Implement the approved plan one small, testable step at a time.

## When to Use

Use this skill during the Agentic Product Engineering Harness workflow when its stage is reached.


## Procedure

1. Read all approved artifacts.
2. Pick the next smallest implementation step.
3. Modify only necessary files.
4. Run relevant checks.
5. Record what changed.
6. Stop before broad or risky changes.

## Output

Update code and maintain `07_STEPWISE_COMMITS.md` with:

- step name
- files changed
- rationale
- tests run
- result
- next step

## Anti-Patterns

- Do not perform large rewrites.
- Do not skip tests.
- Do not silently change existing behavior.


## 中文说明

本 Skill 是 Agentic Product Engineering Harness 的一个阶段。  
它的目标是让 AI 在正确的阶段产出正确的文档或代码，而不是自由发挥。
