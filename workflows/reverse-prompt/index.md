---
layout: page
title: 参考视频逆向工作流 · Reverse Prompt Workflow
---

# 参考视频逆向工作流
# Reverse Prompt Workflow

Antigravity 逆向出提示词 → 改核 → 生成。

**状态：方法已定。** ComfyUI .json 图文件待 GPU 验证。

## 方法（已定）

1. 用 Antigravity CLI 把参考视频反成提示词：运镜、机位、镜头切换、节奏、结构。
2. 先逆向把核找出来，再改核，改成你自己的。
3. 单镜头不超过 15 秒，写动作别写形容词。

工具：Antigravity CLI（已装，Windows 上已登录，Google AI Pro）。

## 规格（待 GPU 验证后实测）

- 输入：待验证
- 输出：待验证
- 模型：待定
- 自定义节点：待定
- 显存要求：待实测
- 成本/耗时：待实测

## 相关

- 组合页：[逆向工作流 × 2.5D 短片](/workflows/reverse-prompt/for-2d-drama/)
- 教程：[先逆向再生成：用 Antigravity 把参考视频反成提示词](/tutorials/)（正文待填）
- 返回[工作流总览](/workflows/)
