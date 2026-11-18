---
deck_id: ucloud
kind: deck
category: brand
summary: UCloud（优刻得）企业宣传、公有云/混合云/AI智算产品发布、行业解决方案汇报与客户案例展示，严格遵循《UCloud VI 0929》视觉规范，融合双“U”重叠辅助图形、同心圆角波纹与2.5D玻璃质感图标。
keywords: [UCloud, 优刻得, 品牌VI, 云计算, AI智算]
primary_color: "#3860F4"
canvas_format: ppt169
canvas_width: 1280
canvas_height: 720
canvas_viewbox: "0 0 1280 720"
source_canvas_width: 1280
source_canvas_height: 720
source_viewbox: "0 0 1280 720"
replication_mode: standard
native_structure_mode: structured
page_count: 9
placeholders:
  04b_content_showcase: ["{{PAGE_TITLE}}", "{{SHOWCASE_HEADING}}", "{{CONTENT_AREA}}", "{{SECTION_NAME}}", "{{PAGE_NUM}}"]
  04c_content_four_cards: ["{{PAGE_TITLE}}", "{{CARD_1_TITLE}}", "{{CARD_1_DESC}}", "{{CARD_2_TITLE}}", "{{CARD_2_DESC}}", "{{CARD_3_TITLE}}", "{{CARD_3_DESC}}", "{{CARD_4_TITLE}}", "{{CARD_4_DESC}}", "{{SECTION_NAME}}", "{{PAGE_NUM}}"]
  04d_content_icon_grid: ["{{PAGE_TITLE}}", "{{GRID_1_TEXT}}", "{{GRID_2_TEXT}}", "{{GRID_3_TEXT}}", "{{GRID_4_TEXT}}", "{{GRID_5_TEXT}}", "{{GRID_6_TEXT}}", "{{GRID_7_TEXT}}", "{{GRID_8_TEXT}}", "{{SECTION_NAME}}", "{{PAGE_NUM}}"]
---

# UCloud 优刻得企业演示模板 — Design Specification

## I. Template Overview

| Application context | Definition |
| --- | --- |
| Recurring presentation family | UCloud（优刻得）企业宣传、公有云/混合云/AI 智算产品发布、行业解决方案汇报、客户案例展示与技术交流演示 |
| Intended audiences and outcomes | 面向政企与互联网客户决策者、技术架构师及合作伙伴；建立中立、安全、自主可控的云计算服务商印象，推进技术评审、架构共识与合作签约 |
| Delivery and reading assumptions | 以现场大屏主讲演示为主，同时支持会后导出 PDF/PPTX 独立分发阅读；内容页保留清晰页眉标识、章节归属与页码 |
| Representative narrative/page roles | 原型涵盖深色主封面、4 栏编号目录、浅色等距云章节页、VI 蓝青双“U”品牌章节页、通用开放内容页、左文右图展台页、4 栏产品卡片页、2×4 能力图标矩阵页与深色致谢封底 |

- **设计基调**：严格依据《UCloud VI 0929》规范与双 PPT 方案构建，采用深浅混排（`mixed`）——封面、品牌宣传章节页与封底使用品牌蓝 `#3860F4` 及蓝青渐变 `#00479D`→`#009CAB`，正文章节与内容页使用高对比白底 `#FFFFFF` 配浅蓝波纹与官方浅灰蓝层级。
- **母版体系**：全套共享 1 个基础母版 `ucloud_master`（`UCloud Master`），通过 9 个语义化版式覆盖品牌宣传与严谨业务汇报场景，不拆出冗余重复母版。

## II. Color Scheme

严格采纳《UCloud VI 0929》1.0.5 线上标准色与 1.0.6 线上辅助色/文本/背景/描边规范：

| Role | Color | Application |
| --- | --- | --- |
| Online Primary Blue (标准色) | `#3860F4` | 品牌核心主蓝；深色封面/封底底色、左上角胶囊标签、目录大号数字 `01`–`04`、章节短线与焦点强调 |
| Online Warm Yellow (标准色) | `#FFCF87` | 线上标准暖黄；封面分割点缀、品牌章节编号与关键数据亮点 |
| Online Deep Gray (标准色) | `#5A6776` | 线上标准深灰；次级图标、辅助标签与图表对比序列 |
| Aux Blue Gradient Start (辅助色) | `#5F87F8` | 线上辅助蓝渐变起点（`#5F87F8` → `#3860F4`） |
| Aux Yellow Gradient End (辅助色) | `#FFBC76` | 线上辅助黄渐变终点（`#FFCF87` → `#FFBC76`） |
| Brand Deep Cobalt (线下/渐变蓝) | `#00479D` | 品牌蓝青渐变起点（`#00479D` → `#009CAB`），用于 VI 方案一双“U”宣传章节背景 |
| Brand Teal Accent (线下/渐变青) | `#009CAB` | 品牌蓝青渐变终点，传递稳健与拓展科技感 |
| Deep Text (文本颜色) | `#0A1633` | 一级深色文本：页面主标题、卡片标题、重点正文 |
| Light Text (文本颜色) | `#6B798E` | 二级浅色文本：常规正文、副标题、卡片描述、章节说明 |
| Light Gray-Blue Text (文本颜色) | `#ABB4C3` | 三级浅灰蓝文本：页眉/页脚辅助信息、次级数据说明 |
| Note Text (文本颜色) | `#C3CAD9` | 备注文本与小面积背景描边 |
| Small Panel Bg (页面背景色) | `#EBF0FC` | 小面积背景色：图片展台底衬、卡片顶部视窗与图标徽章底衬 |
| Light Blue Tint (页面背景色) | `#E5EAFF` | 浅蓝色：次级信息高亮底色、深色页副标题文本 |
| Split Area Bg (页面背景色) | `#F9FAFF` | 页面分割背景：大面积弱区分区底色 |
| Light Blue Border (描边色) | `#E1E6F0` | 浅蓝色描边：卡片外框、页眉底线、目录分栏线与矩阵中轴线 |
| White | `#FFFFFF` | 内容页主画布背景、深色页主标题及反白 Logo |

> 禁用色说明：VI 规范中的 `#BBBBBB` 仅作界面禁用态参考，禁止用于正文与重要信息；图表扩展可辅以 `#45BBFA`（天青）与 `#6FC21A`（生态绿）。

## III. Typography

依据《UCloud VI 0929》1.0.8 中英文字体规范：

| Role | Font stack | Application |
| --- | --- | --- |
| Primary Sans (VI: 思源黑体 + Arial) | `Arial, Microsoft YaHei, Source Han Sans CN Normal, sans-serif` | VI 规定中文专用字体为**思源黑体**（Bold / Regular / Light），英文常规字体为 **Arial**（Bold / Regular）；SVG 首选 PPT 跨平台安全栈 `Arial, Microsoft YaHei` 以确保 PowerPoint 导出无字体告警，同时保留思源黑体视觉指向 |
| Cover & Display Title | `Arial Black, Microsoft YaHei, Arial, sans-serif` | 深色主封面与强冲击力标题 |
| Display Wordmark (VI: BLANCH / Light) | `Arial, Microsoft YaHei, Source Han Sans CN ExtraLight, sans-serif` | VI 规定大号展示英文可选用 **BLANCH**；致谢封底及装饰英文采用轻盈大字重对比 |

- 内容页主标题 `32` px 加粗（`#0A1633`），正文基准 `15`–`18` px（`#6B798E` / `#0A1633`），封面主标题 `48` px（`#FFFFFF`）。

## IV. Signature Design Elements

- **品牌标识安全留白与明度色阶（VI 1.0.1–1.0.4 & 1.1.3）**：
  - 全套 Logo 源自 `UCloud 新logo.ai` 矢量母版提取，保持 `12x × 61x` 原始比例与 `0.84x` 最小安全边距（`1280` 宽横版页右上角预留 `≥24px` 净空），禁止拉伸、描边、改色或与装饰图形直接绑定。
  - **明度色阶规范**：白色或 `K0–K40` 浅背景必须使用标准蓝 Logo（`logo_ucloud_blue.png`）；`K40–K100` 深色或品牌深蓝背景必须使用反白 Logo（`logo_ucloud_white.png`）。
- **双套官方辅助图形体系（VI 1.0.7）**：
  - **辅助图形 A（同心圆角波纹）**：以“U”为中心向外扩散的圆角波纹与行业圆点，体现中立性与生态延展，用于内容页白底波纹（`bg_content_ripple.png`）及等距云封面/章节底纹。
  - **辅助图形 B（双“U”重叠）**：两个“U”字形在 `#00479D`→`#009CAB` 蓝青渐变底上错位重叠融合，寓意“多一份稳定，多一层安心”，用于品牌宣传章节页（`03b_chapter_brand.svg`）。
- **左侧蓝色胶囊标题栏（VI 2.1.0 方案二）**：内容页（`02_toc` 及 `04a`–`04d`）左上角统一配置 `x=0, y=34, width=52, height=30` 的 `#3860F4` 圆角矩形胶囊，配左对齐 `32px` 标题与 `#E1E6F0` 页眉细线。
- **对齐与框体例外声明**：通用正文及卡片内文案均从所属 `data-pptx-bounds` 左上角左对齐起排；深色封面（`01_cover`）、浅色等距云章节页（`03a_chapter_light`）与深色封底（`05_ending`）保留右侧聚合焦距版式（`text-anchor="end"`），而 VI 双“U”品牌章节页（`03b_chapter_brand`）采用左对齐大字版式。

## V. Page Roster

| File | Master | Layout key | PowerPoint picker name | Visual character | Reusable slots |
| --- | --- | --- | --- | --- | --- |
| `01_cover.svg` | UCloud Master | cover_dark | Dark Cover | `#3860F4` 深蓝等距云立方体背景、右上反白矢量级 Logo 与股票代码 `688158`、`#FFCF87` 标准暖黄短线 | `title` (`{{TITLE}}`), `subtitle` (`{{SUBTITLE}}`), `body` (`{{AUTHOR}}`), `date` (`{{DATE}}`) |
| `02_toc.svg` | UCloud Master | toc_four_col | Four-Column Agenda | 白底波纹与左 `#3860F4` 胶囊页眉、4 栏等宽布局配 `#3860F4` 数字 `01`–`04` 与 `#E1E6F0` 分栏线 | `title` (`{{PAGE_TITLE}}`), 4×2 `body` (`{{TOC_ITEM_N_TITLE}}`, `{{TOC_ITEM_N_DESC}}`), `slide-number` (`{{PAGE_NUM}}`) |
| `03a_chapter_light.svg` | UCloud Master | chapter_light | Light Isometric Chapter | 浅色白蓝等距云背景（VI 方案二）、右上标准蓝 Logo、右侧 `#3860F4` 短线与大号章节编号 | `body` (`{{CHAPTER_NUM}}`), `title` (`{{CHAPTER_TITLE}}`), `subtitle` (`{{CHAPTER_DESC}}`), `slide-number` (`{{PAGE_NUM}}`) |
| `03b_chapter_brand.svg` | UCloud Master | chapter_brand | Brand Double-U Chapter | `#00479D`→`#009CAB` 蓝青渐变底 + VI 1.0.7 双“U”重叠辅助图形 B、底部深色带配右下角白 Logo 与左下页码（VI 方案一） | `body` (`{{CHAPTER_NUM}}`), `title` (`{{CHAPTER_TITLE}}`), `subtitle` (`{{CHAPTER_DESC}}`), `slide-number` (`{{PAGE_NUM}}`) |
| `04a_content_open.svg` | UCloud Master | content_open | Title and Open Content | 标准左 `#3860F4` 胶囊页眉 + 白底波纹，下方提供 `1160×530` 宽敞无遮挡开放内容画布 | `title` (`{{PAGE_TITLE}}`), `object` (`{{CONTENT_AREA}}`), `footer` (`{{SECTION_NAME}}`), `slide-number` (`{{PAGE_NUM}}`) |
| `04b_content_showcase.svg` | UCloud Master | content_showcase | Split Media Showcase | 左文右图产品/案例页；左侧蓝短线引导标题与正文，右侧 `#EBF0FC` 圆角展台配 `#E1E6F0` 描边承载大图 | `title` (`{{PAGE_TITLE}}`), `body` (`{{SHOWCASE_HEADING}}`, `{{CONTENT_AREA}}`), `picture` (16:10 展台图), `footer`, `slide-number` |
| `04c_content_four_cards.svg` | UCloud Master | content_four_cards | Four-Column Product Cards | 4 栏等宽 `#E1E6F0` 描边白底卡片，顶部 `#EBF0FC` 图像槽展示产品/方案主视觉，下方为标题与要点正文 | `title` (`{{PAGE_TITLE}}`), 4×`picture`, 4×2 `body` (`{{CARD_N_TITLE}}`, `{{CARD_N_DESC}}`), `footer`, `slide-number` |
| `04d_content_icon_grid.svg` | UCloud Master | content_icon_grid | Capability Icon Matrix | 2×4 能力与认证矩阵，`#E1E6F0` 中轴竖线分栏，8 组 `#EBF0FC` 圆角徽章承载 2.5D 图标与右侧说明文本 | `title` (`{{PAGE_TITLE}}`), 8×`picture`, 8×`body` (`{{GRID_N_TEXT}}`), `footer`, `slide-number` |
| `05_ending.svg` | UCloud Master | ending_dark | Dark Ending | `#3860F4` 深蓝等距平台背景、右上反白矢量级 Logo、轻盈大号致谢字与右侧联系信息 | `title` (`{{THANK_YOU}}`), `subtitle` (`{{CONTACT_INFO}}`), `body` (`{{CLOSING_MESSAGE}}`) |

## VI. Assets

| File | Intended usage |
| --- | --- |
| `logo_ucloud_blue.png` | 由 `UCloud 新logo.ai` 提取的高清透明标准蓝横版 Logo（`2242×275`），严格用于白底或 `K0–K40` 浅背景 |
| `logo_ucloud_white.png` | 由 `UCloud 新logo.ai` 同源提取的高清透明反白横版 Logo（`2242×275`），严格用于 `K40–K100` 深背景 |
| `bg_cover_dark.png` | `01_cover` 深蓝等距云立方体背景（由源 PPTX `image1.tiff` 转制优化） |
| `bg_chapter_light.jpg` | `03a_chapter_light` 浅色白蓝等距云背景（源自源 PPTX `image3.jpg`） |
| `bg_content_ripple.png` | 内容页通用同心圆角波纹（VI 辅助图形 A）白底背景（源自源 PPTX `image5.png`） |
| `bg_ending_dark.png` | `05_ending` 深蓝等距平台背景（由源 PPTX `image7.tiff` 转制优化） |
| `hero_ai_analytics.png` | 官网 2.5D 玻璃质感 AI 智研插画，用于 `04b_content_showcase` 默认展台配图 |
| `hero_model_platform.png` | 官网星图大模型平台插画，用于 `04c_content_four_cards` 示范配图 |
| `hero_paas_o2.png` | 官网 O2 PaaS 立体算力插画，用于 `04c_content_four_cards` 示范配图 |
| `icon_cloud_compute.png` | 官网基础云计算 2.5D 蓝白图标 |
| `icon_ai_compute.png` | 官网大模型算力底座 2.5D 蓝白图标 |
| `icon_hybrid_cloud.png` | 官网私有云/混合云 2.5D 蓝白图标 |
| `icon_ai_brain.png` | 官网人工智能 2.5D 蓝白图标 |
| `icon_network_cloud.png` | 官网混合云网络 2.5D 蓝白图标 |
| `icon_cloud_comm.png` | 官网云通信与企业应用 2.5D 蓝白图标 |
| `icon_enterprise_trust.png` | 官网企业级稳定可信 2.5D 蓝白图标 |
| `icon_datacenter_node.png` | 官网全球数据中心节点 2.5D 蓝白图标 |
