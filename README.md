# 财神视频工作流包 · 站点骨架

本站是「财神视频工作流包」（$19 一次性买断）的 GitHub Pages 站骨架：首页、定价、llms.txt、工作流总览、10 类模板页骨架。

**当前状态：筹备中。** 工作流正在 AMD MI300X 上用 ComfyUI 制作，尚未跑通；本站只搭骨架，不许对外宣称工作流已经做完、已经发布。购买链接、域名、GitHub 仓库均为待填占位。

## 文件地图

- `index.md` — 首页
- `pricing/index.md` — 定价页（人可读）；`pricing.md` — 定价机器可读版（与定价页同源）
- `llms.txt` — 给 AI 爬虫读的产品说明（照 CreativeClaw 结构）
- `workflows/index.md` — 工作流总览；`workflows.md` — 工作流机器可读版
- `workflows/*/index.md` — 4 个核心工作流详情页（制作中）
- `workflows/reverse-prompt/for-2d-drama/index.md` — 工作流 × 用途组合页示例
- `use-cases/` — 用途着陆页（2.5D 短片、锁脸短片、播报开篇）
- `alternatives/` — 模型替代页
- `benchmarks/` — 实测对比页
- `examples/` — 案例复刻页（EP1 v6 为真实案例）
- `tutorials/index.md` — 16 篇教程索引（标题已定，正文待填）
- `cost-calculator/index.md` — 成本计算器页
- `help/index.md` — 帮助页
- `.well-known/product.json` — 产品卡片（机器可读）
- `_config.yml` — Jekyll 配置（域名、购买链接、仓库链接待填）

## 发布步骤（操作清单）

1. 在 GitHub 建一个公开仓库（名字自定；用户站用 `USERNAME.github.io`，项目站任意名）。
2. 把本站全部文件推到仓库主分支。
3. 打开仓库 Settings → Pages → Build and deployment → Source 选 "Deploy from a branch"，分支选主分支、目录选根目录（`/`）。
4. 等几分钟，打开 `https://USERNAME.github.io`（用户站）或 `https://USERNAME.github.io/仓库名/`（项目站）检查。
5. 项目站需把 `_config.yml` 里的 `baseurl` 改成 `/仓库名`；用户站留空。
6. 自定义域名（以后）：域名确定后，把 `_config.yml` 的 `url` 改成新域名；在仓库 Pages 设置里填 Custom domain；按 GitHub 提示在域名商处加 CNAME 记录；并把全站链接里的相对路径换成绝对地址（llms.txt 顶部的说明也要更新）。

## 上线前待填清单

- [ ] `_config.yml`：`url`（域名）、`gumroad_url`（购买链接）、`github_repo`（源码仓库）
- [ ] Gumroad 商品上架，拿到商品链接后填 `gumroad_url`
- [ ] 工作流跑通后，把各工作流详情页的模型/节点/显存/成本从"待定"换成实测值，并去掉"制作中"
- [ ] 免费试用、更新政策、退款政策确认后写入定价页与 llms.txt
- [ ] 16 篇教程正文、实测对比数据、成本计算器表填写
- [ ] 目录铺开（Civitai / OpenArt 引流）时，把站链接填进各平台

## 规矩

- 不许对外宣称工作流已经做完、已经发布：工作流没跑通之前，所有工作流页都标"制作中"。
- 没核实的东西标"待核实"/"待定"，不编数字。
- 用户自己的内部班子是他自己的东西，绝不进站。
- 中文为主，关键处附英文。
