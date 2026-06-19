# AI Native Development Harness

A governance-first software engineering harness for AI coding agents.

AI Native Development Harness 是一套面向 AI Coding Agent 的受控软件工程框架。它不是另一个代码生成工具，而是一套把 AI 纳入软件工程生命周期的工程约束层：通过需求、上下文、任务、分支、验证、审查、变更记录和回滚机制，让 AI 参与开发但不失控。

## 一句话

AI Native 软件工程的本质，是把 AI 从“代码生成工具”纳入软件工程生命周期中，通过上下文、任务、分支、验证、审查和变更记录，实现可控的软件生产。

## 六阶段

1. 需求分析
2. 系统设计
3. 编码实现
4. 测试验证
5. 部署发布
6. 运维维护

## 五层模型

1. Requirement Layer：需求层
2. Context Layer：上下文层
3. Task Layer：任务层
4. Agent Execution Layer：执行层
5. Governance Layer：治理层

## 快速开始

```bash
cp templates/CLAUDE.md ./CLAUDE.md
mkdir -p docs
cp templates/PRD.md docs/PRD.md
cp templates/ARCHITECTURE.md docs/ARCHITECTURE.md
cp templates/TASKS.md docs/TASKS.md
cp templates/AI_CHANGELOG.md docs/AI_CHANGELOG.md
cp templates/DEBUG_PLAYBOOK.md docs/DEBUG_PLAYBOOK.md
cp templates/REVIEW_CHECKLIST.md docs/REVIEW_CHECKLIST.md
```

## 核心原则

- AI 修改代码前必须先读上下文。
- AI 修改代码前必须先输出 Plan。
- 不允许直接在 main 上改代码。
- 一个任务对应一个 Task ID、一个分支、一个 PR、一个变更记录。
- 高风险区域必须单独确认。
- AI 必须跑测试或说明不能跑的原因。
- AI 必须更新 AI_CHANGELOG。
- AI 可以创建 PR，但不应该自动 merge 和上线。
