---
id: canon-form
site: theo
cat: T9
title: 卡农曲式
title_en: Canon Form
summary: 把卡农写法组织成整曲——结构由"追随规则的变化"构成
summary_en: Organising canonic writing into a whole piece — the structure is built from changes in the following rule
level: standard
tags: [乐理, 曲式, 复调]
tags_en: [theory, form, polyphony]
alias: [卡农曲式, 卡农结构, canon form]
order: 40
links:
  - "[[concept:canon]]"
  - "[[concept:form]]"
  - "[[concept:fugue-form]]"
  - "[[concept:contrapuntal-devices]]"
  - "[[concept:theme-variations]]"
instances:
  - atepp-002452 | 巴赫《哥德堡变奏曲》第 12 变奏（Canone）：明确标为卡农的变奏，可听"规则变了、素材没变" | Bach's Goldberg Variation 12, marked Canone — a variation labelled as a canon, where the rule changes but the material does not
  - atepp-000355 | 格里格《抒情小品》中的《卡农》：浪漫派的卡农写法，可对照巴洛克的严格处理 | Grieg's Canon from the Lyric Pieces — a Romantic canon, useful against stricter Baroque handling
  - mutopia-000280 | 巴赫二部创意曲第一首：声部进入严格追随，可听"卡农式结构"在短曲中的雏形 | Bach's first two-part invention — strictly imitative entries, showing canonic structure in miniature
sources:
  - 卡农曲式指以卡农写法组织整曲时的结构安排，与"卡农（写法）"分属不同层面，属曲式分析通则
  - 巴赫《哥德堡变奏曲》每三首变奏含一首卡农、进入间隔逐次递增，为音乐史通行记载
updated: 2026-09-25
---

::: zh
与 [[concept:fugue-form|赋格曲式]] 的分工方式相同：

> **T6 的「卡农」讲写法**（一条旋律被另一声部严格追随）；
> **本条讲结构** —— 把这种写法组织成整曲时，段落由什么构成。

## 三种结构形态

| 形态 | 说明 | 例 |
|---|---|---|
| **完整卡农** | 整首曲子就是一个卡农（从头跟到尾） | 各种卡农曲、轮唱曲 |
| **含卡农段** | 整曲由多个段落构成，**其中若干段是卡农** | 见下：哥德堡变奏曲 |
| **卡农式连接** | 只在段落交接处用卡农写法过渡 | 大量古典作品的过渡段 |

## ⭐ 一个绝佳的结构实例：哥德堡变奏曲

巴赫《哥德堡变奏曲》的组织方式值得单独讲，因为它把"卡农"用成了**结构原则**：

| 事实 | 结构意义 |
|---|---|
| **每三首变奏中，有一首明确标为 Canon** | 卡农成为**周期的锚点**，而不是偶发手法 |
| **各首卡农的进入间隔逐次递增**：同度 → 二度 → 三度 → … → 九度 | **规则本身在变化** —— 这就是全曲的组织轴 |
| 其余变奏为舞曲、托卡塔、赋格式等 | 提供对比，使卡农的回归更有分量 |

**注意第二行**：变化的不只是音乐，而是**规则**。
这与 [[concept:theme-variations|变奏曲式]] 的"换表面、保骨架"不同 ——
**卡农变奏换的是"追随的方式"**，骨架与规则同时被改造。

## 与赋格曲式的对照

两者都是复调，但**结构靠什么支撑**不同：

| | 卡农曲式 | 赋格曲式 |
|---|---|---|
| 变化的是 | **追随规则**（进入间隔 / 音程 / 方向 / 时值） | **主题出现的调性与密集度** |
| 是否有"自由段" | 较少（卡农段内部高度严格） | **有**（间插段正是自由段） |
| 结构标记 | 常由段落对比标出（如"卡农变奏"与"非卡农变奏"交替） | 三段逻辑（呈示 / 中间 / 结束） |

一句话：**赋格靠"主题去了哪里"组织，卡农靠"追随的方式怎么变"组织。**

## 图示：规则本身作为结构轴

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">卡农曲式的结构轴：不变的素材 + 不断变化的"追随规则"</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">素材</text>
    </g>
    <g fill="#343439">
      <rect x="0" y="-8" width="80" height="16" rx="2"/>
      <rect x="94" y="-8" width="80" height="16" rx="2"/>
      <rect x="188" y="-8" width="80" height="16" rx="2"/>
      <rect x="282" y="-8" width="80" height="16" rx="2"/>
    </g>
    <text x="376" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">素材始终是同一批音</text>

    <g transform="translate(0,44)">
      <g fill="#5B7FA8"><rect x="0" y="-10" width="80" height="20" rx="2"/></g>
      <text x="40" y="4" font-family="system-ui,sans-serif" font-size="9.5" fill="#F2EEE6" text-anchor="middle">同度</text>
      <g fill="#E8C547"><rect x="94" y="-10" width="80" height="20" rx="2"/></g>
      <text x="134" y="4" font-family="system-ui,sans-serif" font-size="9.5" fill="#1A0E06" text-anchor="middle">二度</text>
      <g fill="#E07A3F"><rect x="188" y="-10" width="80" height="20" rx="2"/></g>
      <text x="228" y="4" font-family="system-ui,sans-serif" font-size="9.5" fill="#1A0E06" text-anchor="middle">三度</text>
      <g fill="#C0504A"><rect x="282" y="-10" width="80" height="20" rx="2"/></g>
      <text x="322" y="4" font-family="system-ui,sans-serif" font-size="9.5" fill="#F2EEE6" text-anchor="middle">…九度</text>
    </g>

    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="40" y1="22" x2="40" y2="34"/>
      <line x1="134" y1="22" x2="134" y2="34"/>
      <line x1="228" y1="22" x2="228" y2="34"/>
      <line x1="322" y1="22" x2="322" y2="34"/>
    </g>

    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      哥德堡变奏曲：每三首变奏含一首卡农，各首卡农的进入间隔同度→二度→…→九度逐次递增
    </text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      变化的不只是音乐，而是"规则"本身 —— 这就是全曲的组织轴
    </text>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      对照：赋格靠"主题去了哪里"组织；卡农靠"追随的方式怎么变"组织
    </text>
  </g>
</svg>
```

## 听一听：同素材、不同高度

用 `interval` 听同素材在不同高度进入的关系（三度 / 五度）——
**素材没变，进入音程变了**。这正是卡农曲式里"规则变化"的最小演示。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"三度进入（规则之一）","label_en":"Entry at the third — one of the rules","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 G4 就是五度进入 —— 素材不变，规则的改变就是结构本身。","hint2_en":"Set b to G4 for entry at the fifth — the material is unchanged; the change of rule is the structure."}
```

## 常见误解

- **「卡农曲式就是卡农」** → 同源但不同层面：卡农是**写法**，卡农曲式是**结构安排**（整曲由什么段落构成）。
- **「卡农曲式变化太少、写不长」** → 哥德堡变奏曲用"规则递增"撑起了一整套变奏，证明它可以有严密的大结构。
- **「它和赋格曲式差不多」** → 变化的东西不同：一个变**规则**，一个变**调性与密集度**。
- **「卡农段之间没有对比」** → 常与非卡农段落交替（舞曲、托卡塔、赋格式），**交替本身就是结构**。
:::

::: en
The division of labour matches [[concept:fugue-form|fugue form]]:

> **T6's "canon" covers the writing** (one melody strictly followed by another voice);
> **this entry covers the structure** — what the sections consist of when that writing is organised into a piece.

## Three structural shapes

| Shape | Explanation | Example |
|---|---|---|
| **complete canon** | the whole piece is one canon (followed from start to finish) | canon pieces and rounds |
| **canon sections** | the piece has several sections, **some of them canons** | see the Goldberg Variations below |
| **canonic transition** | canonic writing used only at a join between sections | countless Classical transitions |

## ⭐ An outstanding structural example: the Goldberg Variations

Bach's organisation deserves separate mention, because it turns "canon" into a **structural principle**:

| Fact | Structural meaning |
|---|---|
| **every third variation is explicitly marked Canon** | the canon becomes a **periodic anchor**, not an occasional device |
| **the entry interval increases each time**: unison → second → third → … → ninth | **the rule itself changes** — this is the organising axis of the whole work |
| the remaining variations are dances, toccatas, fugal pieces | they supply contrast, making the canons' returns weightier |

**Note the second row**: what varies is not only the music but **the rule**.
That differs from [[concept:theme-variations|variation form]]'s "change the surface, keep the frame" —
**here the manner of following changes**, so frame and rule are both transformed.

## The comparison with fugue form

Both are polyphonic, but **what holds the structure up** differs:

| | Canon form | Fugue form |
|---|---|---|
| What changes | **the following rule** (spacing, interval, direction, note values) | **the key and density of the subject's appearances** |
| Free passages | fewer (canon sections are highly strict inside) | **yes** (episodes are exactly that) |
| Structural markers | often section contrast (canon variations alternating with non-canons) | three-part logic (exposition, middle, final) |

In one line: **a fugue is organised by where the subject goes; a canon is organised by how the following rule
changes.**

## Diagram: the rule itself as the structural axis

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Canon form's axis: unchanged material plus a continually changing following rule</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">material</text>
    </g>
    <g fill="#343439">
      <rect x="0" y="-8" width="80" height="16" rx="2"/>
      <rect x="94" y="-8" width="80" height="16" rx="2"/>
      <rect x="188" y="-8" width="80" height="16" rx="2"/>
      <rect x="282" y="-8" width="80" height="16" rx="2"/>
    </g>
    <text x="376" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">the material is always the same notes</text>

    <g transform="translate(0,44)">
      <g fill="#5B7FA8"><rect x="0" y="-10" width="80" height="20" rx="2"/></g>
      <text x="40" y="4" font-family="system-ui,sans-serif" font-size="9.5" fill="#F2EEE6" text-anchor="middle">unison</text>
      <g fill="#E8C547"><rect x="94" y="-10" width="80" height="20" rx="2"/></g>
      <text x="134" y="4" font-family="system-ui,sans-serif" font-size="9.5" fill="#1A0E06" text-anchor="middle">second</text>
      <g fill="#E07A3F"><rect x="188" y="-10" width="80" height="20" rx="2"/></g>
      <text x="228" y="4" font-family="system-ui,sans-serif" font-size="9.5" fill="#1A0E06" text-anchor="middle">third</text>
      <g fill="#C0504A"><rect x="282" y="-10" width="80" height="20" rx="2"/></g>
      <text x="322" y="4" font-family="system-ui,sans-serif" font-size="9.5" fill="#F2EEE6" text-anchor="middle">… ninth</text>
    </g>

    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="40" y1="22" x2="40" y2="34"/>
      <line x1="134" y1="22" x2="134" y2="34"/>
      <line x1="228" y1="22" x2="228" y2="34"/>
      <line x1="322" y1="22" x2="322" y2="34"/>
    </g>

    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Goldberg: every third variation is a canon, each at a higher entry interval, unison through ninth
    </text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      What varies is not only the music but the rule itself — that is the organising axis
    </text>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      A fugue is organised by where the subject goes; a canon by how the following rule changes
    </text>
  </g>
</svg>
```

## Listen: one material, different heights

Use `interval` to hear the relation of the same material entering at different heights (a third, a fifth) — **the
material is unchanged, the entry interval is not.** That is the smallest demonstration of a canon form's "change of
rule".

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"三度进入（规则之一）","label_en":"Entry at the third — one of the rules","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 G4 就是五度进入 —— 素材不变，规则的改变就是结构本身。","hint2_en":"Set b to G4 for entry at the fifth — the material is unchanged; the change of rule is the structure."}
```

## Common misconceptions

- **"Canon form means a canon."** Related but different levels: a canon is **writing**, canon form is the
  **structural arrangement** of a whole piece.
- **"Canon form varies too little to sustain length."** The Goldberg Variations sustain an entire set through an
  escalating rule — proof that it can carry a rigorous large structure.
- **"It is much like fugue form."** Different things change: one varies **the rule**, the other **key and
  density**.
- **"There is no contrast between canon sections."** They usually alternate with non-canonic variations (dances,
  toccatas, fugal pieces) — **the alternation itself is the structure**.
:::
