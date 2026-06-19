# 04. Governance and Review

## 变更前

- 是否有 PRD？
- 是否有 ARCHITECTURE？
- 是否有 Task ID？
- 是否在任务分支？
- 是否输出 Plan？
- 是否有人类确认？

## 变更后

- 是否跑了测试？
- 是否更新 AI_CHANGELOG？
- 是否说明风险？
- 是否创建 PR？
- 是否需要人工审查？

## AI 不应自动执行

- merge main
- push production
- 删除数据库
- 执行不可逆迁移
- 修改密钥
- 绕过 review
