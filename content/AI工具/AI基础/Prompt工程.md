---
创建时间: 2026-03-26
标签: #Agent技术 #Prompt #提示词
aliases: [Prompt Engineering, 提示词工程]
---

# Prompt 工程

## 📌 一句话定义

Prompt 工程是设计和优化与 AI Agent 交互的提示词，以获得更准确、更有用的输出的技术。

## 🎯 核心概念

1. **零样本 (Zero-shot)**: 直接给出任务描述，不提供示例
2. **少样本 (Few-shot)**: 提供 1-3 个示例帮助理解
3. **思维链 (Chain-of-Thought)**: 引导 AI 展示推理过程
4. **角色扮演 (Role-playing)**: 设定 AI 扮演特定角色
5. **结构化输出**: 要求 AI 输出 JSON/YAML 等格式

## 💡 常用技巧

### 1. 清晰的任务描述
```
❌ 帮我看看这个代码
✅ 请检查以下 UE5 蓝图代码中的性能问题：
   1. 是否有 Event Tick 滥用
   2. 循环中是否有不必要的 GetAllActorOfClass
```

### 2. 上下文注入
```
我正在开发一个 UE5 射击游戏，
当前问题：子弹命中检测不准确
请分析以下碰撞代码...
```

### 3. 拆分复杂任务
```
Step 1: 分析材质节点结构
Step 2: 识别性能瓶颈
Step 3: 提供优化建议
```

## 🔗 相关链接

- [[Agent技术\AI基础\AIAgent基础|AI Agent]] - Agent 技术基础
- [[Agent技术\工具开发\Blueprint自动化|Blueprint 自动化]] - UE5 中的应用

## 📚 学习资源

- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [OpenAI Prompt Examples](https://platform.openai.com/examples)

