---
deck_id: chinaunicom
kind: deck
category: brand
summary: 中国联通企业通用演示模板——面向工作汇报、项目验收、培训材料与方案介绍的红色商务版式体系
keywords: [中国联通, 国企央企, 红色商务, 工作汇报, 培训]
primary_color: "#CC0000"
canvas_format: ppt169
canvas_width: 1280
canvas_height: 720
canvas_viewbox: "0 0 1280 720"
source_canvas_width: 1280
source_canvas_height: 720
source_viewbox: "0 0 1280 720"
replication_mode: standard
native_structure_mode: structured
page_count: 7
---

# 中国联通 — Design Specification

## I. Template Overview

| Application context | Definition |
|---|---|
| Recurring presentation family | 中国联通各业务线的对内/对外演示：工作汇报、项目验收、培训材料、产品方案介绍、实施推广 |
| Intended audiences and outcomes | 面向公司领导、业务部门、合作伙伴与培训学员；承载信息传达、成果汇报与知识讲解 |
| Delivery and reading assumptions | 会议室投屏演示为主，兼顾近距离阅读与材料分发 |
| Representative narrative/page roles | 封面 → 目录 → 章节过渡 → 图文内容（单栏/双栏/大图）→ 致谢结尾 |

- 浅色白底内容页配联通红点缀；封面为通栏红色图片带配白色居中标题；整体为国企红色商务风格。

## II. Color Scheme

| Role | HEX | 用途 |
|---|---|---|
| 主色 联通红 | #CC0000 | 章节面板、目录序号块、标题侧标、结尾主标题 |
| 辅助红 | #E08E79 | 目录序号块交替色、次级红色装饰 |
| 深灰 | #333333 | 正文默认色 |
| 中灰 | #808080 | 描述文字、页码 |
| 浅灰 | #A0A0A0 | 目录条目描边、版权页脚 |
| 黑 / 白 | #000000 / #FFFFFF | 标题 / 红底与图片带上的反白文字 |

- 红色仅作强调与身份识别，不大面积堆叠（章节页左侧面板除外）。

## III. Typography

- 全模板微软雅黑；封面主标题 60px bold 白色，副标题 28px 白色，日期 20px 白色。
- 页标题 32px bold 黑色，左侧 8×40 红色竖条标识；正文 20px #333333；说明性文字 16px #808080。
- 页码 14px #808080，格式 `- N -`，右下对齐；版权页脚 `© CHINAUNICOM` 13px #A0A0A0 右下。

## IV. Signature Design Elements

- 封面通栏图片带（1280×360，纵向居中偏上），白色居中标题/副标题/日期压于带上；右上角联通 logo（固定版式资产）。
- 图片带右下白色四角星形装饰（star4 preset，主 56×42、次 40×30，0.9/0.75 不透明度）。
- 目录条目：红色"第 N 部分"序号块（200×98）+ 白底灰描边条目块（586×98），当前项主红、次项浅红交替。
- 内容页页眉：左侧红色竖条 + 32px 页标题；正文区 64,128 起 1152×520 安全区。
- 章节页：左侧 480px 通高红色面板 + 96px 白色章节号，右侧章节标题与描述。
- 结尾页：居中 logo + 红色短横条 + 60px 红色致谢 + 联系信息。

## V. Page Roster

| File | Master | Layout key | PowerPoint picker name | Visual character | Reusable slots |
| --- | --- | --- | --- | --- | --- |
| `01_cover.svg` | 中国联通母版 | cover | 封面 | 通栏红色图片带、白色居中标题簇、右上 logo、右下星形装饰 | 标题、副标题、日期、通栏图片 |
| `02_toc.svg` | 中国联通母版 | toc | 目录 | 红块序号加白底灰描边条目的四行目录 | 页面标题、四个目录项标题与描述、页码 |
| `03_chapter.svg` | 中国联通母版 | chapter | 章节页 | 左侧通高红色面板加白色章节号、右侧标题描述 | 章节号、章节标题、章节描述、页码 |
| `04_content.svg` | 中国联通母版 | content | 内容页 | 红色页眉竖条加单栏大开放正文区 | 页面标题、正文、页码 |
| `05_content_two_col.svg` | 中国联通母版 | content-two-col | 内容页-双栏图文 | 红色页眉竖条、左侧正文右配图 | 页面标题、正文、配图、页码 |
| `06_content_media.svg` | 中国联通母版 | content-media | 内容页-大图展示 | 红色页眉竖条、中部大图加下方说明 | 页面标题、大图、说明文字、页码 |
| `07_ending.svg` | 中国联通母版 | ending | 结尾页 | 居中 logo、红色短横条、红色致谢与联系信息 | 致谢语、联系信息 |

## VI. Assets

| File | 用途 | 来源 |
|---|---|---|
| images/unicom-logo.png | 封面/结尾页 logo（487×329） | 源 PPTX 素材裁剪（去除 2022 冬奥会联合标识） |
| images/cover-hero-red.jpg | 封面默认通栏图片带 | 源 PPTX 素材（联通红色抽象底纹） |
| images/visual-red-pattern.png | 双栏/大图页默认配图 | 源 PPTX 素材（联通红色纹理） |
