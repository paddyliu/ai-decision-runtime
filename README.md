# AI Decision Runtime

一个面向企业级场景的 AI 决策运行体系架构。

本项目并不是一个简单的：

- LLM Demo
- Agent Playground
- RAG 示例
- Workflow 拼装平台

而是尝试回答一个更实际的问题：

> 当 AI 真正进入企业日常运营后，
> 如何让 AI 的决策、执行、审计、回放与持续优化，
> 成为一个可治理、可持续运行的系统？

---

# 项目目标

在大规模企业运营场景下，AI 不应直接替代现有业务系统。

企业真正需要的是：

- AI 能理解业务上下文
- AI 能基于证据生成候选决策
- AI 能在治理约束下执行
- AI 的所有行为可追踪、可审计、可回放
- AI 能持续学习并优化运行策略

因此，本项目提出：

# AI Decision Runtime

即：

> 一个围绕“企业决策执行闭环”构建的 AI 运行体系。

---

# 核心理念

## 1. AI 不拥有企业主数据

企业系统（ERP / CRM / DMS / WMS / MES / SFA / Data Platform / Business Middle Platform）仍然是：

- System of Record
- 主数据来源
- 业务对象来源
- 业务关系来源
- 业务事实来源
- 业务规则来源

AI Runtime：

- 不替代业务系统
- 不复制业务系统
- 不成为新的主数据中心

AI 只负责：

- 理解上下文
- 生成候选行动
- 编排执行
- 治理决策过程
- 持续优化运行结果

---

## 2. 所有决策必须可治理

AI 输出不能直接成为最终动作。

系统需要：

- Policy Validation
- Confidence Threshold
- HITL（Human-in-the-loop）
- Approval Workflow
- Escalation
- Failure Control

---

## 3. 所有执行必须可回放

企业 AI 必须支持：

- Evidence Trace
- Decision Ledger
- Replay Timeline
- Knowledge Version
- Audit Chain

即：

> 所有重要决策都应可复现。

---

## 4. Runtime 是长期运行系统

企业 AI Runtime 不只是一次请求。

而是：

- 长时间运行
- 可暂停
- 可恢复
- 可等待事件
- 可等待人工
- 可跨系统持续执行

因此系统需要：

- Durable Execution
- Checkpoint
- Event Resume
- Session Continuation
- Stateful Runtime

---

# 架构核心

当前架构主要包含：

## 1. Decision Execution Loop

企业 AI 的核心运行闭环：

```text
Observe
→ Understand
→ Decide
→ Execute
→ Learn
```

---

## 2. AI Runtime

包括：

- Context Runtime
- Capability Routing
- Tool Registry
- Policy Runtime
- Prompt Registry
- Model Router
- Execution Runtime
- Session Runtime

---

## 3. Governance Layer

包括：

- Audit
- Replay
- Evidence Trace
- Policy Version
- Decision Ledger
- Release Guard

---

## 4. Learning Layer

包括：

- Feedback Evaluation
- Policy Tuning
- Capability Scoring
- Routing Optimization
- Runtime Evolution

---

# 适用场景

本架构更适用于：

- 快消
- 零售
- 连锁运营
- 制造
- 企业运营管理
- 企业决策闭环
- 大规模执行体系

而不是：

- 单用户 AI Assistant
- ChatBot Demo
- 简单 Agent Playground

---

# 当前状态

当前仓库主要包含：

- 架构设计
- Runtime 模型
- 治理体系
- Decision State Machine
- 企业 AI Operating Model

后续可能逐步补充：

- Reference Architecture
- Runtime Prototype
- Event Model
- Capability Contract
- Replay Mechanism
- Evaluation Framework

---

# 设计原则

## Evidence First

所有重要决策都应基于证据。

---

## Replayable Decision

所有重要决策都应可回放。

---

## Governed Execution

所有执行都必须受到治理约束。

---

## Durable Runtime

Runtime 必须支持长期运行。

---

## AI Assists Operations, Not Replace Systems

AI 参与企业运行，
但不替代企业系统。

---

# License

Apache 2.0 License

---

# Disclaimer

本项目当前主要用于：

- 企业 AI 架构探索
- AI Runtime 设计研究
- 企业治理体系实践

并不代表完整生产实现。
