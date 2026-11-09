---
layout: page
title: 定价 · Pricing
---

# 定价 · Pricing

## 财神视频工作流包 · Caishen Video Workflow Pack

**$19 一次性买断 · $19 one-time purchase**

> 价格以本页为准；改价只改此处（机器可读版见[/pricing.md](/pricing.md)，与本页同源）。

{% if site.gumroad_url != "" %}
[在 Gumroad 购买 · Buy on Gumroad]({{ site.gumroad_url }})
{% else %}
购买链接待上架后填写（收钱走 Gumroad）。
{% endif %}

## 包含什么 · What's included

- 4 个核心 ComfyUI 视频工作流（方法已定，ComfyUI .json 图文件待 GPU 验证）：参考视频逆向、2.5D 定妆人物锁脸、H3 环境、播报开篇
- 逆向组合方法：Antigravity 逆向改核、rea-video 结构化拆解（rea-video 已审计 CAUTION，未安装）
- Pavo 单人定妆镜头：已锁定（2026-11-06，8 秒 720p 脸全程稳定）；双人版在跑，三人版待重跑
- EP1 v6：已公开案例（https://youtu.be/sz0ahhPtKGI）
- 16 篇教程：系统教学 + 提示词技巧（标题已定，正文待填）
- 提示词库：video-refs/prompts/（已逆向出的提示词）
- 工具：视频搜索下载器 v1.4、视频库生成器 build-video-library.ps1、find-videos.ps1
- 素材库：video-refs/（clips/ 参考视频 + prompts/ + links.md）
- 案例库与方法/模板笔记：见[案例复刻](/examples/)（只列文件名与目录原文的结论，不编内容）

## 不包含什么 · What's not included

- GPU / 算力：工作流在你自己的 GPU 上跑（AMD MI300X / Kaggle T4 / 本地 GPU）
- 模型文件：按附带的模型清单自行下载，遵守各模型许可
- 自定义 checkpoint / LoRA 训练
- 真人肖像商用（涉肖像权）
- 一对一订制服务

## 更新政策 · Updates

买断后该版本内容永久可用；后续新增工作流与更新政策待确认（上线前定）。

## 退款 · Refunds

待定（上线前确认，以 Gumroad 商品页说明为准）。

## 常见问题

- 免费试用有吗？——待定（计划提供 1 个免费工作流，上线前确认）。
- 每个工作流要花多少钱/多长时间？——待工作流 GPU 验证后实测（待核实）。
- 工作流打不开、缺节点怎么办？——缺节点时 ComfyUI Manager 会提示安装；缺模型时按清单里的下载链接取。详见[帮助](/help/)。
