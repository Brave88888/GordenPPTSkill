# Changelog

按版本倒序列出可读变更。机器读取请用 [`updates.json`](./updates.json)；只读哪些文件变动请用 [`manifest.json`](./manifest.json) 的 `last_modified` 字段。

## 1.0.0 — 2026-05-27

**首次发布。**

新增：

- 使用者脚本：`build_pptx.py` / `render_slides.py` / `check_update.py` / `apply_update.py` / `build_manifest.py`
- 17 个内置模板（每个 = `template.pptx` + `intro.md` + `detail.json` + `preview.png`）：
  - `minimal-business-summary` — 简约商务总结汇报（深蓝白，16 页）
  - `red-patriot-youth` — 新时代新青年红色教育（党政红，16 页）
  - `cute-orange-class` — 橙色可爱卡通教学（暖橙，17 页）
  - `quarterly-illust` — 蓝灰酸性插画季度总结（Y2K 亮蓝，19 页）
  - `geometric-summary` — 多彩几何工作总结（4 主色，21 页）
  - `red-patriot-general` — 红色爱国主题教育通用（党政红，25 页）
  - `thesis-novice` — 多专业开题方法论库（墨绿，34 页）
  - `premium-corp` — 高级感大厂 PPT 合辑（酱红，38 页）
  - `architecture-deck` — 领导爱的架构图合辑（深蓝，40 页）
  - `thesis-formula` — 开题报告万能公式（暖米色，41 页）
  - `data-viz-deck` — 数据可视化合辑（深蓝砖红，41 页，含原生 chart）
  - `top-thesis` — 名校开题报告合辑（酒红，41 页）
  - `mckinsey-style` — 麦肯锡风专业模板（酱红，42 页）
  - `report-savior` — 汇报救命合辑（深蓝，49 页）
  - `operations-deck` — 运营 PPT 合辑（深蓝，52 页）
  - `competition-speech` — 竞聘述职合辑（深蓝砖红，59 页）
  - `report-template-massive` — 118 页超大工作汇报合辑（深蓝）
- 参考文档 `references/` 系列
- 版本机制：`VERSION` / `CHANGELOG.md` / `updates.json` / `manifest.json`
- 字体 fallback 链：WenQuanYi Micro Hei → DengXian → Noto Sans SC → PingFang SC
- 非商业使用声明在 SKILL.md 顶部明确化
