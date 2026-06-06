# Good First Issues · 新手任务清单

> 这些是可以直接复制到 GitHub Issues 发布的任务（你建好仓库后照贴即可）。
> 都打 `good first issue` + 对应标签，方便新人认领。Styledex 最缺的就是**更多风格**。

---

### ✦ #1 认领并新增一个风格（最欢迎）
**labels:** `new-style`, `good first issue`

挑一个还没收录的设计风格，按 [CONTRIBUTING.md](../CONTRIBUTING.md) 加进去。还没被收录、值得做的候选：

- 极简主义海报风 / Brutalist Poster
- 蒸汽朋克手账 / Junk Journal
- 新中式国潮 2.0
- 苹果液态玻璃 / Liquid Glass (2025)
- 复古赛车 / Racing Livery
- 医疗科技 / Medtech Clean
- 朋克 zine / Punk Zine
- 极简金融 / Fintech Minimal

一个风格 ≈ 一段结构化数据。挑一个，开 PR。

---

### ✶ #2 给风格补「相邻风格」推荐
**labels:** `enhancement`, `good first issue`

部分风格的 `adj`（相邻风格）还能更准。挑几个风格，校准它们的 `adj`，让「你可能也喜欢」更合理。

---

### ✎ #3 校对/润色风格配方与一句话抽象
**labels:** `docs`, `good first issue`

通读现有风格的 `recipe` / `one`（一句话抽象），修正不准确或不够有趣的描述。中英文都欢迎。

---

### ⚙ #4 把风格数据拆成独立文件
**labels:** `enhancement`, `help wanted`

当前风格数据内联在 HTML 里。探索把 `STYLES` / `EXTRA` / `LAYO` 拆成独立的 `styles.json`，并在不破坏「双击即开」体验的前提下加载（注意 `file://` 下的 fetch 限制）。

---

### ♿ #5 无障碍 / 对比度审查
**labels:** `a11y`, `good first issue`

检查暗色界面的文字对比度、键盘可达性、焦点态，提改进建议或 PR。

---

### 🎨 #6 旗舰风格高保真样张
**labels:** `enhancement`, `help wanted`

选一个风格（如赛博朋克 / 瑞士国际主义），把它的某个跨品类样本做成真正的高保真页面，作为「门面」展示。
