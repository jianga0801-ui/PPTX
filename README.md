# PPTX 模板库

面向 **ppt-master** 的可复用 PPTX / 模板资源仓库。

## 适用场景

- 使用 ppt-master 生成、改写或扩展现有演示文稿
- 需要统一品牌视觉与版式结构（封面、目录、章节页、内容页、结尾页）
- 希望以「Deck 模板」方式复用，而不是每次从空白页开始

## 仓库结构

```
Deck/
  README.md          # Deck 模板规范说明（英文）
  decks_index.json   # 模板索引（deck_id → 摘要/画布/页数/主色）
  chinaunicom/       # 示例模板包：中国联通风格
    templates/       # SVG 版式原型 + design_spec.md
    images/          # 配图与品牌素材
    exports/         # 导出的 .pptx / .potx 预览
```

## 模板包说明

每个模板包（如 `chinaunicom`）包含：

| 目录 | 作用 |
|---|---|
| `templates/` | 页面原型（SVG）与设计规格 `design_spec.md` |
| `images/` | 封面图、Logo、装饰素材等 |
| `exports/` | 可直接预览的 PowerPoint / 模板文件 |

更完整的 Deck 模板契约、选择安装流程与 SVG 结构约定，见 [`Deck/README.md`](./Deck/README.md)。

## 使用方式

1. 在索引 [`Deck/decks_index.json`](./Deck/decks_index.json) 中按需求选择模板
2. 阅读对应包内 `templates/design_spec.md`，确认画布、主色与页面阵容
3. 按 ppt-master 工作流安装模板，再进入内容编排与导出

## 说明

- 本仓库提供的是**可复用的演示模板结构**，不是最终业务内容稿
- 新增模板包时请保持 `templates / images / exports` 目录约定，并更新 `decks_index.json`
