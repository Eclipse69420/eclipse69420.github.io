# 财神视频工作流包 · 工作流总目录（机器可读）
# Caishen Video Workflow Pack — Workflow catalog (machine-readable)

> 状态：方法已定。4 个核心工作流的方法已定，ComfyUI .json 图文件待 GPU 验证；模型、节点、显存、成本待 GPU 验证后实测。不要引用待定项作为已实测数据。

## 核心工作流

- 参考视频逆向工作流 — 用途：把参考视频逆向成提示词再改核生成；状态：方法已定，ComfyUI .json 图文件待 GPU 验证；模型：待定；节点：待定；显存：待实测；成本：待实测；链接：/workflows/reverse-prompt/
- 2.5D 定妆人物锁脸工作流 — 用途：定妆图 → 图生视频，同一张脸演完整集；状态：方法已定，ComfyUI .json 图文件待 GPU 验证；模型：待定；节点：待定；显存：待实测；成本：待实测；链接：/workflows/face-lock-2d/
- H3 环境工作流 — 用途：顶层公寓演播室环境生成；状态：方法已定，ComfyUI .json 图文件待 GPU 验证；模型：待定；节点：待定；显存：待实测；成本：待实测；链接：/workflows/h3-environment/
- 播报开篇工作流 — 用途：电影预告式开篇；状态：方法已定，ComfyUI .json 图文件待 GPU 验证；模型：待定；节点：待定；显存：待实测；成本：待实测；链接：/workflows/broadcast-opening/

## 逆向组合

- 逆向 → 改核 → 生成（Antigravity）— 状态：方法已定，ComfyUI .json 图文件待 GPU 验证；链接：/workflows/reverse-prompt/
- 逆向 → 结构化拆解 → 复刻方案（rea-video）— 状态：已审计 CAUTION，与 Antigravity 互补不是替代，未安装；链接：/workflows/reverse-prompt/
- 逆向 → 锁脸生成 — 状态：方法真实可用；链接：/workflows/face-lock-2d/
- 逆向 → H3 环境 — 状态：方法已定；顶层公寓提示词待逆向；链接：/workflows/h3-environment/

## 已公开案例

- Pavo 单人定妆镜头 — 8 秒 720p 脸全程稳定（2026-11-06 已锁定）；状态：已有；双人版在跑，三人版待重跑
- 漫剧 EP1 v6 — 已公开案例；状态：已有；链接：https://youtu.be/sz0ahhPtKGI
