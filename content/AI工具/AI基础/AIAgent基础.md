---
创建时间: 2026-03-26
标签: #Agent技术 #AI #基础
aliases: [AI Agent, 人工智能代理, 智能体]
---

# AI Agent 基础概念

## 📌 一句话定义

AI Agent (人工智能代理) 是能够自主感知环境、做出决策、执行动作的智能程序，结合大语言模型 (LLM) 实现复杂任务自动化。

## 🎯 核心概念

1. **感知 (Perception)**: Agent 从环境中获取信息（用户输入、API数据、文件等）
2. **推理 (Reasoning)**: LLM 理解上下文，进行逻辑推理和规划
3. **行动 (Action)**: 执行具体操作（调用API、写代码、操作文件）
4. **记忆 (Memory)**: 短期/长期记忆保持上下文连续性
5. **工具使用 (Tool Use)**: 调用外部工具扩展能力（搜索、代码执行）

## 🔗 工作流程

```
用户输入 → 感知层 → 推理引擎(LLM) → 规划器 → 行动执行 → 反馈循环
                ↓
            记忆存储
```

## 💡 Agent 框架

| 框架 | 语言 | 特点 |
|------|------|------|
| LangChain | Python/JS | 生态丰富，工具链完整 |
| AutoGen | Python | 微软出品，多Agent协作 |
| CrewAI | Python | 角色扮演，多Agent分工 |
| LangGraph | Python | 图结构，复杂流程编排 |
| Trae Agent | - | 内置 Agent 能力 |

## 🔗 相关链接

- [[Prompt工程]] - 与 Agent 交互的核心
- [[UE5AI助手]] - 游戏中的 Agent 应用

## 📚 学习资源

- [LangChain 文档](https://python.langchain.com/)
- [AutoGen 官方](https://microsoft.github.io/autogen/)
- [CrewAI GitHub](https://github.com/joaomdmoura/crewAI)
