---
layout: page
title: 工作流总览 · Workflows
---

# 工作流总览 · Workflows

全部工作流的索引，每个带一句话说明和状态。机器可读版见 [/workflows.md](/workflows.md)。

> **状态说明：** 4 个核心工作流的方法已定，ComfyUI .json 图文件待 GPU 验证；逆向组合方法真实可用。

## 核心工作流（4 个）

- [参考视频逆向工作流](/workflows/reverse-prompt/)：Antigravity 逆向出提示词 → 改核 → 生成。状态：方法已定，ComfyUI .json 图文件待 GPU 验证。
- [2.5D 定妆人物锁脸工作流](/workflows/face-lock-2d/)：定妆图 → 图生视频，脸不漂。状态：方法已定，ComfyUI .json 图文件待 GPU 验证。
- [H3 环境工作流](/workflows/h3-environment/)：顶层公寓演播室环境生成。状态：方法已定，ComfyUI .json 图文件待 GPU 验证。
- [播报开篇工作流](/workflows/broadcast-opening/)：电影预告式开篇。状态：方法已定，ComfyUI .json 图文件待 GPU 验证。

## 逆向组合（核心方法在不同场景的应用）

- 逆向 → 改核 → 生成（Antigravity）：先逆向参考视频把核（运镜/节奏/结构）找出来，再改核。方法已定，ComfyUI .json 图文件待 GPU 验证。
- 逆向 → 结构化拆解 → 复刻方案（rea-video）：逐镜判定制作方式 + 字幕/BPM + 复刻方案。已审计 CAUTION，与 Antigravity 互补不是替代，未安装。
- 逆向 → 锁脸生成：逆向参考的运镜和氛围 + 定妆图锁脸出片。方法真实可用。
- 逆向 → H3 环境：逆向顶层公寓参考视频 → 建 H3 环境。顶层公寓提示词待逆向。

## 已公开案例

- Pavo 单人定妆镜头：已锁定（2026-11-06，8 秒 720p 脸全程稳定）；双人版在跑，三人版待重跑。
- EP1 v6：已公开案例，https://youtu.be/sz0ahhPtKGI
- 详见[案例复刻](/examples/)。
