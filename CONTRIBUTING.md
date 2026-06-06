# 贡献指南 · Contributing to Styledex

谢谢你想参与 Styledex！这个项目最需要的贡献就是 **新增设计风格** —— 每多一个高质量风格，工具就更有用。也欢迎修 bug、改进交互、完善文档。

整个原型是 **一个零依赖的单文件**：`Styledex_prototype.html`。用浏览器直接打开就能预览，改完刷新即可看到效果。

---

## 最常见的贡献：新增一个风格

每个风格的数据写在 `Styledex_prototype.html` 顶部的 `<script>` 里，分三处（第 2、3 处其一可选）。照着现有条目仿写即可。

### 1）`STYLES` 数组 —— 风格主体（必填）

```js
{id:'A-61', name:'风格中文名', en:'STYLE EN NAME', tagline:'a short english tagline',
 pal:['#bg','#c2','#ink','#accent','#accent2'],              // 5 个代表色
 flags:{bg:'#0a0a0a', surface:'#161616', ink:'#eee', acc:'#ff2e88', acc2:'#19f0ff',
        radius:8, border:1, font:'display', motif:'glow'},   // 驱动样本渲染
 recipe:{TYPOGRAPHY:'字体调性…', COLOR:'配色逻辑…', LAYOUT:'版式…', TEXTURE:'质感…'},
 tags:['标签1','标签2','标签3','标签4'],                       // 多维标签
 adj:['A-02','A-21'],                                        // 2 个相邻风格的 id
 prompt:'english prompt to feed image/coding AI, comma separated'},
```

字段取值约定：
- **id**：`A-` 加序号，接着现有最大号往后排（当前到 A-60）。
- **flags.font**：`sans` | `serif` | `mono` | `display`
- **flags.motif**：`flat` | `grid` | `glow` | `glass` | `chrome` | `soft`（决定样本的质感/光效）
- **flags.radius**：圆角像素（0–24 常见）；**flags.border**：描边粗细（0–4）
- **adj**：必须是已存在的 id，否则相邻风格点不动。

### 2）`EXTRA` 对象 —— 一句话抽象 + 何时使用（必填）

```js
'A-61':{one:'一句极致有趣、有记忆点的话。', when:'适合的产品/页面类型，逗号分隔。'},
```

### 3）`LAYO` 对象 —— 排版倾向（可选，不填则自动推导）

```js
'A-61':{a:'l', den:'dense', sc:'xl', g:2, u:1, ls:.04},
```
- **a** 对齐：`l`(左) | `c`(中)　**sc** 字阶：`sm|md|lg|xl`　**den** 密度：`airy|med|dense`
- **g** 网格强度：`0|1|2`　**u** 全大写：`0|1`　**ls** 字距(em)

> 顶部字幕和「SUBJECTS」数字会自动读取风格总数，无需手改。

### 自检清单
- [ ] `id` 唯一、序号连续
- [ ] `adj` 指向的 id 都存在
- [ ] 浏览器打开，能在首页看到新卡片，点进详情、样本、排版天性都正常
- [ ] 颜色对比度别太低，保证缩略图看得清

---

## 提交流程

1. Fork 本仓库，新建分支：`git checkout -b add-style-xxx`
2. 改 `Styledex_prototype.html`，本地浏览器自测
3. 提交并发起 Pull Request，描述里附上新风格的名字和一张截图

## 行为准则

友善、就事论事。设计审美可以讨论，但请尊重彼此。

有疑问就开一个 Issue 问。Happy styling ✦
