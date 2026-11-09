---
layout: page
title: 逆向工作流 × 2.5D 短片 · Reverse Prompt for 2.5D Shorts
---

# 逆向工作流 × 2.5D 短片
# Reverse Prompt Workflow for 2.5D Shorts

同一条逆向工作流，用在 2.5D 短片这个用途的具体做法和成本。

## 做法

1. 用 Antigravity CLI 把参考视频反成提示词：运镜、机位、镜头切换、节奏、结构，先逆向把核（运镜/节奏/结构）找出来，再改核，改成你自己的。
2. 单镜头不超过 15 秒，写动作别写形容词。
3. 逆向参考的运镜和氛围，结合定妆图锁脸出片：定妆图 → 图生视频，脸不漂。单人定妆镜头已用 Pavo 锁定（2026-11-06，8 秒 720p 脸全程稳定）；双人版在跑，三人版待重跑。
4. 提示词见提示词库 video-refs/prompts/（已逆向出的提示词）。

## 成本/耗时

待 GPU 验证后实测。

## 相关

- 工作流：[参考视频逆向工作流](/workflows/reverse-prompt/)
- 用途：[2.5D 短片](/use-cases/2d-drama/)
- 返回[工作流总览](/workflows/)
