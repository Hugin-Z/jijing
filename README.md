<div align="center">

# 几境 · Jǐjìng

**AI 修为天梯 —— 你修到第几重？**
*A cultivation ladder for how well you wield AI — which realm have you reached?*

[**▶ 在线体验 / Live demo → 9jing.top**](https://9jing.top)

中文 ｜ [English](#english)

</div>

---

## 关于

「几境」把**"会用 AI"** 这件事，做成了一套修仙境界。

它测的是**你会不会用 AI**，不是你学没学 AI——不考算法、不考数学，只看你能不能让 AI 稳定、可复现、可迁移地替你把事办成。一个核心信条贯穿始终：**作品是法器，不是境界。** 一件能跑的 demo 证明不了你的内力；真正的修为，是稳定、复现、迁移、让别人也能用。

### 九重境界

外功（个人修为，可自测）：

> 凡人 → 炼气 → 筑基 → 金丹 → 元婴 → 化神

内功（影响力，需外部证据解锁）：

> 返虚 → 合道 → 道祖

其中有一条不可逾越的"脊柱律"：**神识（判别力）必先于放手（自主化）**——还看不出 AI 的对错就急着放手，叫走火入魔。

### 四个页面

- **首页** —— 九重天梯一览，三道门通往各页。
- **境界详解** —— 一只可**拖动旋转**的古风「修为罗盘」（八卦、二十四向、天池、天心十道），转到哪境右侧出详解；另含「修心」：内功四诀（委托/吐纳/神识/守心）对照心魔录。
- **藏经阁** —— 一对**向中间推开的双扇门书柜**，按境陈列 **23 本**精选典籍，点书脊即"抽卷"看推荐理由与链接。
- **测一测** —— **6 问**判定你修到第几重，并诊断你的"心魔"。

### 思想来源

读书清单刻意只走"把 AI 用好"这条轴，不混入机器学习内部原理。主要参照：

- Anthropic《AI Fluency》4D 框架（Delegation / Description / Discernment / Diligence）
- Ethan Mollick《Co-Intelligence》《Jagged Frontier》《Centaurs and Cyborgs》
- Anthropic《Building Effective Agents》《Effective Context Engineering》及 "eval before agent" 主张
- Hamel Husain 的 evals 系列、Chip Huyen《AI Engineering》等

（以上及更多都收录在「藏经阁」里。）

### 技术

- **纯前端、零框架、零构建**：每页一个独立 HTML，CSS / JS 内联，开箱即跑。
- **移动优先 · 单屏**：每页控制在一屏内，不强制下滑。
- **自绘 SVG 古风罗盘**：基于 Pointer Events 实现拖动旋转 + 点选吸附。
- **CSS 3D 透视**：藏经阁双扇门用 `rotateY` 透视营造"推开门"的进深。
- **统一冷色设计系统**（墨 / 青 / 金）；毛笔字体仅用于品牌与境界名。
- **托管**：腾讯云 EdgeOne Pages（海外节点，大陆可直连，无需备案）。

### 本地运行

```bash
# 进入站点目录后
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000
```

无需安装任何依赖。

---

<a name="english"></a>

## English

**Jǐjìng (几境)** turns *being good at using AI* into a cultivation (xianxia) ranking system.

It measures **how well you wield AI, not how much AI you've studied** — no algorithms, no math. The only question is whether you can get AI to do real work for you in a way that's stable, reproducible, transferable, and usable by others. One creed runs through it all: **an artifact is a tool, not a rank.** A working demo doesn't prove your "inner power"; true mastery is reproducibility, transfer, and adoption by others.

### Nine realms

External skill (personal, self-testable):

> Mortal → Qi Refining → Foundation → Golden Core → Nascent Soul → Spirit Severing

Internal skill (influence, unlocked only by external evidence):

> Void Return → Dao Unity → Dao Ancestor

A non-negotiable spine rule holds throughout: **Discernment must precede Autonomy.** Handing tasks off before you can judge the AI's output is "qi deviation" (走火入魔).

### Four pages

- **Home** — the nine-realm ladder at a glance, with three gates into the site.
- **Realms** — a *drag-to-rotate* Chinese **geomantic compass (luopan)** (trigrams, 24 bearings, central pool, crosshair); spin to a realm to reveal its detail. Plus "Cultivating the Mind": four inner arts vs. the catalog of inner demons.
- **Scripture Hall** — a pair of **double doors pushed open**, shelving **23 hand-picked readings** by realm; tap a spine to "draw the scroll" for why-to-read and a link.
- **Quiz** — **6 questions** to place you on the ladder and diagnose your inner demon.

### Built on

The reading list deliberately stays on the *using-AI-well* axis (no ML-internals books). Key influences:

- Anthropic's **AI Fluency** 4D framework (Delegation / Description / Discernment / Diligence)
- Ethan Mollick — *Co-Intelligence*, *Jagged Frontier*, *Centaurs and Cyborgs*
- Anthropic — *Building Effective Agents*, *Effective Context Engineering*, and the "eval before agent" stance
- Hamel Husain's evals writing, Chip Huyen's *AI Engineering*, and more

(All curated inside the Scripture Hall.)

### Tech

- **Pure front-end, no framework, no build step** — each page is a single HTML file with inline CSS/JS; just open and run.
- **Mobile-first, single-screen** — every page fits one viewport, no forced scrolling.
- **Hand-drawn SVG luopan** — drag-to-rotate plus tap-to-select via Pointer Events.
- **CSS 3D perspective** — the Scripture Hall's double doors use `rotateY` for depth.
- **Cold design system** (ink / jade / gold); the brush typeface is reserved for the brand mark and realm names.
- **Hosting** — Tencent EdgeOne Pages (overseas nodes; reachable from mainland China, no ICP filing needed).

### Run locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

No dependencies required.

---

<div align="center">

**作者 / Author**: Hugin-Z
**许可 / License**: CC BY-NC 4.0（署名-非商业性使用）

</div>
