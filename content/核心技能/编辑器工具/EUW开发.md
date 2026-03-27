---
创建时间: 2026-03-27
标签: #核心技能 #编辑器工具 #EUW #UE5 #Blueprint
---

# Editor Utility Widget (EUW) 开发

## 📌 一句话定义

使用 Editor Utility Widget (EUW) 开发编辑器内嵌界面，是 Editor Utility Blueprint (EUB) 的 UI 层。

## 🎯 核心概念

| 概念 | 说明 |
|------|------|
| **EUW** | Editor Utility Widget - 编辑器内的 UMG 界面 |
| **EUB** | Editor Utility Blueprint - 编辑器内运行的 Blueprint |
| **Blutility** | 在编辑器中执行的脚本化 Blueprint |

## 🛠️ 开发要点

### 1. 创建 EUW
- 在 Content Browser 中右键 → Blueprint Class → 搜索 "EditorUtilityWidget"
- 或使用 Editor Utility Blueprint 模板

### 2. 常用场景
- 自定义编辑器面板
- 资产批量处理工具的界面
- 编辑器内调试面板
- 快捷操作工具

### 3. 与 UMG 的区别
| 特性 | EUW | UMG |
|------|-----|-----|
| 运行目标 | 编辑器内 | 游戏内 |
| 依赖 | SEditorWidget | UUserWidget |
| 交互 | 编辑器上下文 | 游戏运行时 |

### 4. 加载方式
- 通过 `FSoftObjectPath` 加载
- 或通过 `UEditorUtilityWidgetBlueprint` 动态加载

## 📊 匹配岗位

| 岗位 | 匹配度 |
|------|--------|
| UE 编辑器开发 | ⭐⭐⭐⭐⭐ |
| 技术美术 TA (工具向) | ⭐⭐⭐⭐⭐ |
| Blueprint 开发 | ⭐⭐⭐⭐ |

## 🔗 相关笔记

- [[核心技能/编辑器工具/UE编辑器|UE编辑器]]
- [[项目经历/汽车渲染工具|编辑器工具-汽车渲染]]

## 📝 实战项目

参考 [[项目经历/汽车渲染工具|编辑器工具-汽车渲染]] 中的 EUW 开发经验。

