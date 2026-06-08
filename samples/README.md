# Gallery — real generated samples · 真实生成样例

Fully-realized landing pages, one per style — showing what each Styledex style looks like when actually built, not just described. Each is a single self-contained `.html` you can open in a browser.

每个风格一个**真正落地的网页样例**，看到风格被完整实现的样子（而不只是被描述）。每个都是可直接双击预览的单文件 `.html`。

## How they're made · 怎么生成的

1. Open a style's detail page in the Styledex prototype and **screenshot the whole page**.
2. Send the screenshot to an AI (e.g. Claude) with this prompt:

> 根据这个页面描述的风格，帮我做一个现代网页首页，忠实于页面描述的风格，增加风格化的设计，独具一格，本地预览即可。
>
> *(EN: Based on the style described on this page, build me a modern website homepage faithful to that style. Add strong stylistic design, make it distinctive, single-file for local preview.)*

3. Save the result here following the naming convention below.

## Convention · 命名约定

- One self-contained file per style: **`A-NN-slug.html`** (e.g. `A-02-cyberpunk.html`), matching the style `id` in `Styledex_prototype.html`.
- Zero external deps except web fonts; must open by double-click.
- Add a top comment noting the subject id + style name.
- Then add a row to the index below.

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

## Contribute · 贡献

Pick a style that has no sample yet, generate one with the flow above, and open a PR adding the file + an index row. Keep it tasteful and faithful to the style — this gallery is the quality bar for "what Styledex styles can become."
