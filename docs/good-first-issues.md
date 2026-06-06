# Good First Issues — ready to post

> 复制即用：每条含 **Title / Labels / Body**。在仓库 **Issues → New issue → Open a blank issue** 里逐条粘贴。
> 标签里 `good first issue`、`help wanted`、`documentation`、`enhancement` 是 GitHub 自带的；`new-style`、`a11y` 需要先在 **Issues → Labels → New label** 建一下（建议颜色：new-style `#7dffb0`、a11y `#6c7cff`）。

---

## 1 ✦ Claim & add a new style

**Labels:** `new-style` · `good first issue`

**Body:**
```
Pick a design style we don't have yet and add it — adding a style is basically
adding one block of structured data. Full guide: CONTRIBUTING.md.

Open candidates (claim one in a comment):
- Brutalist Poster      - Junk Journal         - Modern Guochao (new Chinese)
- Liquid Glass (2025)   - Racing Livery        - Medtech Clean
- Punk Zine             - Fintech Minimal      - Bauhaus Poster

Comment to claim, then open a PR. First time is totally fine — we'll help in review.

—— 中文 ——
挑一个还没收录的设计风格加进来：加一个风格 ≈ 加一段结构化数据，步骤见 CONTRIBUTING.md。
在评论里认领上面任意一个候选（或自荐），然后提 PR。第一次提没关系，我们会在 review 里帮你。
```

---

## 2 ✶ Sharpen "you may also like" links

**Labels:** `enhancement` · `good first issue`

**Body:**
```
Some styles' `adj` (adjacent/related styles) could be more accurate. Pick a few
styles, review their `adj` so the "you may also like" suggestions feel right.

—— 中文 ——
部分风格的 `adj`（相邻风格）还能更准。挑几个风格，校准它们的 `adj`，
让「你可能也喜欢」更合理。
```

---

## 3 ✎ Proofread & polish recipes / one-liners

**Labels:** `documentation` · `good first issue`

**Body:**
```
Read through existing styles' `recipe` and one-liner (`one`) and fix anything
inaccurate or not punchy enough. Both English (I18N) and Chinese welcome.

—— 中文 ——
通读现有风格的 `recipe` 与一句话抽象（`one`），修正不准确或不够有趣的描述。
中英文都欢迎（英文在 I18N，中文在 STYLES/EXTRA）。
```

---

## 4 ⚙ Split style data into a JSON file

**Labels:** `enhancement` · `help wanted`

**Body:**
```
Style data is currently inline in the HTML. Explore extracting STYLES / EXTRA /
LAYO / I18N into a styles.json, loaded without breaking the "just open the file"
experience (mind file:// fetch limits — may need a tiny build or inlining step).

—— 中文 ——
当前风格数据内联在 HTML 里。探索把 STYLES / EXTRA / LAYO / I18N 拆成 styles.json，
在不破坏「双击即开」体验的前提下加载（注意 file:// 下 fetch 限制，可能需要轻量构建）。
```

---

## 5 ♿ Accessibility & contrast review

**Labels:** `a11y` · `good first issue`

**Body:**
```
Review the dark UI for text contrast, keyboard navigation, and focus states.
File findings or open a PR with fixes.

—— 中文 ——
检查暗色界面的文字对比度、键盘可达性、焦点态，提改进建议或直接提 PR。
```

---

## 6 🎨 Flagship hi-fi sample

**Labels:** `enhancement` · `help wanted`

**Body:**
```
Pick one style (e.g. Cyberpunk or Swiss) and turn one of its cross-category
samples into a true high-fidelity page — a showcase "face" for the project.

—— 中文 ——
选一个风格（如赛博朋克 / 瑞士国际主义），把它的某个跨品类样本做成真正的
高保真页面，作为项目的「门面」展示。
```
