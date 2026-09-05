# AgentDailyNote

从参与 Agent 开发，到能解释机制、验证设计和定位问题。以当前基于 AgentScope 的 Java 项目为学习背景，每次学习留下可复查的证据。

## 学习方式

采用轻量 SDD（Specification-Driven Development，规格驱动开发）：先写“要学会什么、怎样证明学会”，再学习和练习，最后用验收标准检查结果。本仓库将这一方法用于学习；文档发布完成不等于学习验收通过。

每次迭代：目标与验收 → 概念学习 → 项目映射 → 练习与验证 → 复盘与下一步。

## 开始学习

- [Day 01：Agent = LLM + Harness](daily/day-01-agent-harness/README.md)
- [练习与参考要点](daily/day-01-agent-harness/exercises.md)
- [复盘记录](daily/day-01-agent-harness/retrospective.md)
- [学习路线](docs/learning-roadmap.md)
- [SDD 规格与交付记录](docs/sdd-spec.md)

## 目录结构

```text
docs/
  sdd-spec.md
  learning-roadmap.md
daily/
  day-01-agent-harness/
    README.md
    exercises.md
    retrospective.md
```

## 证据约定

正文区分“官方资料支持”“教学抽象”“用户提供背景”“待源码验证”。项目事实必须记录版本、提交及代码位置或运行证据。历史对话中的模型判断不直接作为事实，也不公开内部代码、系统地址和面试附件。

## 提交约定

- 新课程：`docs(day-02): add runtime lifecycle lesson`
- 概念纠错：`docs(day-01): correct session and memory boundaries`
- 练习记录：`learn(day-01): record answers and evidence`

一个提交围绕一个学习主题；修正结论时写明原理解、证据和新结论。Day 编号代表学习单元，不要求每天完成一章。

## 当前进度

2026-09-06：Day 01 教材已整理。个人练习、项目源码核对和学习验收尚未完成。
