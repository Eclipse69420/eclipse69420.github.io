---
layout: page
title: 财神视频工作流包
---

# 财神视频工作流包
# Caishen Video Workflow Pack

能直接跑的 ComfyUI 视频工作流包 + 逆向改核的方法 + 教程。
A ready-to-run ComfyUI video workflow pack, a reverse-engineer-and-remix prompt method, and tutorials.

> **当前状态：筹备中。** 工作流正在 AMD MI300X 上用 ComfyUI 制作，完成后上架。本站为筹备期骨架，购买链接待上架后填写。
> **Status: in preparation.** Workflows are being built in ComfyUI on an AMD MI300X. This site is the skeleton; the purchase link goes live when the pack ships.

## 包里有什么 · What's inside

### 核心工作流（4 个，制作中）

- [参考视频逆向工作流](/workflows/reverse-prompt/)：Antigravity 逆向出提示词 → 改核 → 生成。状态：制作中。
- [2.5D 定妆人物锁脸工作流](/workflows/face-lock-2d/)：定妆图 → 图生视频，脸不漂。状态：制作中。
- [H3 环境工作流](/workflows/h3-environment/)：顶层公寓演播室环境生成。状态：制作中。
- [播报开篇工作流](/workflows/broadcast-opening/)：电影预告式开篇。状态：制作中。

### 逆向组合（核心方法在不同场景的应用）

- 逆向 → 改核 → 生成（Antigravity）
- 逆向 → 结构化拆解 → 复刻方案（rea-video：已审计，未安装）
- 逆向 → 锁脸生成
- 逆向 → H3 环境
- 详见[工作流总览](/workflows/)。

### 之前的管线（已有的，算进包里）

- 战报视频管线：剧本先行、音频带时间线、纯配音 + 真实市场画面、无真人出镜
- 播报开篇管线：分镜大纲 → 逐段烧制（YouTube 16:9、X 9:16）
- 每日 K 线视频：文字 + 视频
- Pavo 单人定妆镜头：已锁定（2026-11-06，8 秒 720p 脸全程稳定）
- 漫剧 EP1 管线：已出 EP1 v6

### 配套资产

- 教程：系统教学 + 提示词技巧（逆向改核的方法论），[16 篇连发](/tutorials/)
- 提示词库：已逆向出的提示词
- 风格库：2.5D 定妆图（人物 + 服装，4 张设定图）
- 工具：视频搜索下载器 v1.4、视频库生成器
- 素材库：参考视频 + 提示词 + 链接
- 案例：EP1 v6、播报开篇

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

**不适合：**

- 训练自定义 checkpoint / LoRA
- 真人肖像商用（涉肖像权）
- 无 GPU 环境（纯 CPU 跑视频工作流极慢）

## 常见问题 · FAQ

- 跑这些工作流需要什么显卡？——需要 GPU；每条工作流的显存要求待跑通后实测（待核实）。
- 锁脸是怎么做的？——定妆图 + 参考图；单人定妆镜头已锁定（8 秒 720p 脸全程稳定），ComfyUI 版制作中。
- 逆向提示词是怎么做的？——用 Antigravity 把参考视频反成提示词，单镜头不超过 15 秒，写动作别写形容词。
- 买了之后更新怎么拿？——更新政策待确认（上线前定）。

更多问答见 [llms.txt](/llms.txt) 与[帮助](/help/)。

## 链接 · Links

- [定价](/pricing/) · [工作流总览](/workflows/) · [教程](/tutorials/) · [案例复刻](/examples/) · [帮助](/help/)
- 机器可读：[llms.txt](/llms.txt) · [pricing.md](/pricing.md) · [workflows.md](/workflows.md)
