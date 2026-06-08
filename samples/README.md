# Gallery — real generated samples · 真实生成样例

Fully-realized landing pages, one per style — showing what each Styledex style looks like when actually built, not just described. Each is a single self-contained `.html` you can open in a browser.

[English](#english) · [中文](#中文)

---

## English

### How they're made

1. Open a style's detail page in the Styledex prototype and **screenshot the whole page**.
2. Send the screenshot to an AI (e.g. Claude) with this prompt:

   > Based on the style described on this page, build me a modern web page faithful to that style. **Choose a page / product type that best fits the style — ideally one suggested in the page's “When to use” section** (e.g. a fintech dashboard, a music-artist page, a luxury brand site), so the style shows at its strongest. Add strong, distinctive stylistic design, make it unique. A single self-contained file for local preview is enough.

3. Save the result here following the naming convention below.

### Naming convention

- One self-contained file per style: **`A-NN-slug.html`** (e.g. `A-02-cyberpunk.html`), where `A-NN` is the style `id` in `Styledex_prototype.html` and `slug` is the lowercased English name.
- Zero external deps except web fonts; must open by double-click.
- Add a top comment noting the subject id + style name, then add a row to the index below.

### Contribute

Pick a style that has no sample yet, generate one with the flow above, and open a PR adding the file + an index row. Keep it tasteful and faithful — this gallery is the quality bar for "what Styledex styles can become."

---

## 中文

### 怎么生成

1. 在 Styledex 原型里打开某个风格的详情页，**截整页的图**。
2. 把截图发给 AI（如 Claude），用这句提示词：

   > 根据这个页面描述的风格，帮我做一个现代网页，忠实于页面描述的风格；并**按页面里「何时使用」板块建议的产品/页面类型来选题**（比如金融仪表盘、音乐人主页、高端品牌站），让风格效果最大化。增加风格化的设计，独具一格，本地预览即可。

3. 按下面的命名约定保存。

### 命名约定

- 每个风格一个自包含文件：**`A-NN-slug.html`**（如 `A-02-cyberpunk.html`）；`A-NN` 是 `Styledex_prototype.html` 里的风格 `id`，`slug` 是英文名小写。
- 除网页字体外零外部依赖；必须双击即开。
- 文件顶部加一行注释标明 subject id + 风格名，并在下方索引表加一行。

### 贡献

挑一个还没有样例的风格，用上面的流程生成，提 PR 加上文件 + 索引行。保持有品味、忠于风格——这个画廊是「Styledex 风格能成为什么样」的质量基准。

---

## Index · 索引

| id | style | sample |
|----|-------|--------|
| A-02 | 赛博朋克 / CYBERPUNK | [A-02-cyberpunk.html](./A-02-cyberpunk.html) |
| A-04 | 新粗野主义 / NEUBRUTALISM | [A-04-neubrutalism.html](./A-04-neubrutalism.html) |
| A-05 | 瑞士国际主义 / SWISS / INTL | [A-05-swiss-intl.html](./A-05-swiss-intl.html) |
| A-09 | 复古终端 / RETRO TERMINAL | [A-09-retro-terminal.html](./A-09-retro-terminal.html) |
| A-26 | 孔版印刷 / RISOGRAPH | [A-26-risograph.html](./A-26-risograph.html) |
| A-31 | 波普艺术 / POP ART | [A-31-pop-art.html](./A-31-pop-art.html) |
| A-52 | 垃圾摇滚 / GRUNGE | [A-52-grunge.html](./A-52-grunge.html) |
| A-53 | 新艺术运动 / ART NOUVEAU | [A-53-art-nouveau.html](./A-53-art-nouveau.html) |
| A-55 | 卡哇伊 / KAWAII | [A-55-kawaii.html](./A-55-kawaii.html) |
| A-58 | 浮世绘 / UKIYO-E | [A-58-ukiyo-e.html](./A-58-ukiyo-e.html) |
