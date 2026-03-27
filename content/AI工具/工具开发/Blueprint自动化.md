---
创建时间: 2026-03-26
标签: #Agent技术 #UE5 #自动化
aliases: [Blueprint Automation, 蓝图自动化]
---

# Blueprint 自动化

## 📌 一句话定义

使用 Blueprint 本身和 AI Agent 实现工作流程自动化，减少重复性工作。

## 🎯 核心概念

1. **蓝图宏**: 封装常用逻辑，一键复用
2. **蓝图工具类**: Editor Utility Blueprint 自动化任务
3. **AI 驱动自动化**: 自然语言触发蓝图执行
4. **批量处理**: 自动处理多个资产/对象

## 💡 您的技能应用

### UI 材质自动化
```
用户输入："创建一个玻璃材质"
AI 触发蓝图：
1. 创建 Material Asset
2. 设置材质疑似度 (Translucent)
3. 连接 Fresnel 节点
4. 添加反射探针采样
5. 设置 Roughness ≈ 0.05
```

### Niagara SDF 效果自动化
```
用户输入："添加一个距离场光环特效"
AI 触发蓝图：
1. Spawn Niagara System
2. 配置 SDF 采样参数
3. 设置粒子发射形状
4. 连接材质球
5. 调参 (Glow, Falloff)
```

## 🔧 工具链

| 工具 | 用途 | 您是否会 |
|------|------|----------|
| Editor Utility Widget | 自定义编辑器UI | ✅ |
| Editor Utility Blueprint | 自动化脚本 | ✅ |
| Python Script | 批量处理 | 待学 |
| AI Agent | 自然语言触发 | 待学 |

## 🔗 相关链接

- [[Agent技术\工具开发\Blueprint编辑器AI|Blueprint 编辑器 AI]] - 编辑器增强
- [[核心技能/编辑器工具/UE编辑器|UE编辑器]] - 工具开发岗位
- [[Notes\Agent技术\UE5集成\UE5AI助手|UE5 AI助手]] - AI 集成

## 📚 学习资源

- [UE5 Editor Utility Widgets](https://docs.unrealengine.com/5.0/zh-CN/)
- [Blutility 文档](https://docs.unrealengine.com/)

