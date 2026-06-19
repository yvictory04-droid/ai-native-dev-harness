# 02. Five-layer Harness Model

## Requirement Layer

回答：做什么、给谁做、为什么做、第一阶段做哪些、不做哪些、验收标准是什么。  
对应文件：PRD.md。

## Context Layer

回答：AI 应该知道什么、不能做什么、项目结构是什么、技术边界是什么、历史问题是什么。  
对应文件：CLAUDE.md、ARCHITECTURE.md、TASKS.md、AI_CHANGELOG.md、DEBUG_PLAYBOOK.md。

## Task Layer

回答：这次具体做哪一件事、任务边界是什么、不做什么、验收标准是什么。  
核心原则：一个任务、一个 Task ID、一个分支、一个 PR、一个变更记录。

## Agent Execution Layer

AI 先读上下文，输出 Plan，人确认后再实现。  
执行模式：Explore、Plan、Build、Review。

## Governance Layer

回答：AI 改了什么、测了吗、谁审查了、出 Bug 怎么查、怎么回滚。  
机制：Git、AI_CHANGELOG、Review Checklist、PR、CI、Debug Playbook、Rollback。
