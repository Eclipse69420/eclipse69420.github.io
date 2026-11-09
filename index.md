---
layout: page
title: 财神视频工作流包
---

# 财神视频工作流包
# Caishen Video Workflow Pack

ComfyUI 视频工作流包 + 逆向改核的方法 + 教程。
A ComfyUI video workflow pack, a reverse-engineer-and-remix prompt method, and tutorials.

> **状态：方法已定。** 4 个核心工作流的方法已定，ComfyUI .json 图文件待 GPU 验证；逆向组合方法、Pavo 单人定妆镜头、EP1 v6 已公开案例、提示词库、工具脚本均已在包里。本站为产品页，购买链接待上架后填写。
> **Status: methods are set.** The methods of the 4 core workflows are set; the ComfyUI .json graph files are pending GPU verification. The reverse-combo methods, the Pavo single-shot lock, the public EP1 v6 case, the prompt library and the tool scripts are already in the pack. This site is the product page; the purchase link goes live when the pack ships.

## 包里有什么 · What's inside

### 核心工作流（4 个，方法已定）

- [参考视频逆向工作流](/workflows/reverse-prompt/)：Antigravity 逆向出提示词 → 改核 → 生成。方法已定；ComfyUI .json 图文件待 GPU 验证。
- [2.5D 定妆人物锁脸工作流](/workflows/face-lock-2d/)：定妆图 → 图生视频，脸不漂。方法已定；ComfyUI .json 图文件待 GPU 验证。
- [H3 环境工作流](/workflows/h3-environment/)：顶层公寓演播室环境生成。方法已定；ComfyUI .json 图文件待 GPU 验证。
- [播报开篇工作流](/workflows/broadcast-opening/)：电影预告式开篇。方法已定；ComfyUI .json 图文件待 GPU 验证。

### 逆向组合（核心方法在不同场景的应用）

- 逆向 → 改核 → 生成（Antigravity）：先逆向参考视频把核（运镜/节奏/结构）找出来，再改核。
- 逆向 → 结构化拆解 → 复刻方案（rea-video）：逐镜判定制作方式 + 字幕/BPM + 复刻方案；已审计 CAUTION，与 Antigravity 互补不是替代，未安装。
- 逆向 → 锁脸生成：逆向参考的运镜和氛围 + 定妆图锁脸出片。
- 逆向 → H3 环境：逆向顶层公寓参考视频 → 建 H3 环境；顶层公寓提示词待逆向。
- 详见[工作流总览](/workflows/)。

### 已公开案例

- Pavo 单人定妆镜头：已锁定（2026-11-06，8 秒 720p 脸全程稳定）；双人版在跑，三人版待重跑。
- 漫剧 EP1 v6：已公开案例，https://youtu.be/sz0ahhPtKGI

### 配套资产

- 教程：系统教学 + 提示词技巧（逆向改核的方法论），16 篇标题已定、正文待填，见[教程](/tutorials/)
- 提示词库：video-refs/prompts/（已逆向出的提示词）
- 工具：视频搜索下载器 v1.4、视频库生成器 build-video-library.ps1、find-videos.ps1
- 素材库：video-refs/（clips/ 参考视频 + prompts/ + links.md）
- 案例：EP1 v6（已公开，https://youtu.be/sz0ahhPtKGI）
- 两把刀：Antigravity CLI（已装，Windows 上已登录，Google AI Pro）、rea-video（已审计 CAUTION，未安装）

### 案例库与方法/模板笔记

- 见[案例复刻](/examples/)：只列文件名与目录原文的结论，不编内容。

## 价格 · Pricing

**$19 一次性买断 · $19 one-time purchase**

{% if site.gumroad_url != "" %}
[在 Gumroad 购买 · Buy on Gumroad]({{ site.gumroad_url }})
{% else %}
购买链接待上架后填写（收钱走 Gumroad）。
Purchase link coming when the pack ships (via Gumroad).
{% endif %}

详见[定价页](/pricing/)。

## 适用 / 不适用 · Who it's for

**适用：**

- 想在 ComfyUI 里做 2.5D 短片、同一张脸演完整集、播报开篇、图生视频、首尾帧锁定的用户
- 想把一条参考视频逆向成提示词，再改成自己的用户
- 想在 AMD MI300X / Kaggle T4 / 本地 GPU 上跑视频工作流的用户
