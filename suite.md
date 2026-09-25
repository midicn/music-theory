---
id: suite
site: theo
cat: T9
title: 组曲
title_en: Suite
summary: 一组各自成立的乐曲按原则排列——乐章之间不追求"整体"
summary_en: A set of self-standing pieces arranged by some principle — the movements do not seek wholeness
level: standard
tags: [乐理, 曲式, 结构]
tags_en: [theory, form, structure]
alias: [组曲, 舞曲组曲, suite]
order: 42
links:
  - "[[concept:form]]"
  - "[[concept:dance-rhythm]]"
  - "[[concept:large-scale-forms]]"
  - "[[concept:genre-vs-form]]"
  - "[[concept:dance-rhythm]]"
instances:
  - atepp-002033 | 巴赫《英国组曲》第一首 BWV 806 的阿勒曼德：舞曲组曲的开头乐章，可听组曲各乐章的独立性格 | The Allemande from Bach's English Suite No.1 BWV 806 — the opening movement of a dance suite, showing each movement's independent character
  - atepp-001847 | 亨德尔《组曲》第 12 首的吉格：组曲的常见收尾乐章，快速而流动 | The Gigue from Handel's Suite No.12 — the usual closing movement of a suite, fast and flowing
  - atepp-000184 | 德彪西《贝加马斯克组曲》中的小步舞曲：19 世纪的"组曲"不再限于舞曲，可对照巴洛克的写法 | The Minuet from Debussy's Suite bergamasque — by the nineteenth century a suite was no longer limited to dances
sources:
  - 巴洛克舞曲组曲的固定序列（阿勒曼德 / 库朗特 / 萨拉班德 / 吉格）与前置前奏曲的惯例，为音乐史与曲式学通行记载
  - 组曲与奏鸣曲的区别（各乐章独立 vs 整体统一），为通行表述
updated: 2026-09-25
---

::: zh
组曲的组织原则很特别，一句话：

> **它是一组"各自成立的乐曲"按某种原则排在一起 —— 而不追求"整体性"。**

这与 [[concept:large-scale-forms|奏鸣曲、交响曲]] 正好相反：
后者要求各乐章在调性、主题与情绪上构成一个整体；**组曲不要求**。

## 巴洛克舞曲组曲：序列固定

巴洛克组曲（suite / partita）有相当固定的序列：

| 位置 | 舞曲 | 国籍 | 速度与性格 |
|---|---|---|---|
| （前置） | **前奏曲** | — | 自由、展示技巧（常可省略） |
| 1 | **阿勒曼德** | 德国 | 中速、庄重、**四拍** |
| 2 | **库朗特** | 法国 | 快速、**三拍**、流动性强 |
| 3 | **萨拉班德** | 西班牙 | **极慢**、二拍、重音落在第二拍 |
| 4 | **吉格** | 英国／爱尔兰 | 快速、**复合拍子**（常 6/8），常为赋格式收尾 |

**这张表里有三条设计原则**，值得单独注意：

| 原则 | 说明 |
|---|---|
| **速度对比** | 中 → 快 → 极慢 → 快：一张"慢—快—慢—快"的呼吸弧线 |
| **节拍交替** | 四拍 → 三拍 → 二拍 → 复合拍：**每首的节拍都不同** |
| **国籍交替** | 德 → 法 → 西 → 英：**各乐章自带不同的民族风格** |

所以组曲不是随机拼盘 —— 它靠**速度、节拍、民族风格的对比**来组织。这一点常被忽略：
**组曲的"统一"不在于主题，而在于这套对比的框架。**

## 后来它变成了什么

| 时期 | 组曲的含义 |
|---|---|
| **巴洛克** | 一套舞曲（上述序列），通常同一调 |
| **古典** | 组曲形式式微，被奏鸣曲与交响曲取代；小夜曲、嬉游曲保留其精神 |
| **19 世纪** | 从戏剧、芭蕾、歌剧中**选段**组成"音乐会组曲" |
| **20 世纪** | 电影配乐组曲、舞剧组曲；也有作曲家重写巴洛克式组曲 |

第三行值得注意：**当"选段"成为组曲的主要来源后，"组曲"的核心特征从"舞曲序列"变成了"独立乐章的集合"** ——
这正是组曲与奏鸣曲的根本分野。

## 与奏鸣曲的关键区别

| | 组曲 | 奏鸣曲（多乐章） |
|---|---|---|
| 各乐章的关系 | **各自独立** | 构成**整体**（调性 / 主题 / 情绪） |
| 调性 | 常同一调，或各首自由 | **有调性布局** |
| 乐章数量 | 不固定（4 到 20 余首） | 通常 3–4 |
| 顺序原则 | 速度 / 节拍 / 风格的对比 | **戏剧性的弧线**（快—慢—舞曲—快） |

一句话：**组曲是"并列"，奏鸣曲是"叙事"。**

## 图示：三种对比轴

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">组曲靠速度、节拍、风格的对比组织 —— 不靠主题的统一</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">速度</text>
      <text x="-20" y="40" text-anchor="end">节拍</text>
      <text x="-20" y="80" text-anchor="end">风格</text>
    </g>

    <g>
      <rect x="0" y="-10" width="80" height="20" rx="3" fill="#5B7FA8"/>
      <rect x="86" y="-10" width="80" height="20" rx="3" fill="#E8C547"/>
      <rect x="172" y="-10" width="80" height="20" rx="3" fill="#E07A3F"/>
      <rect x="258" y="-10" width="80" height="20" rx="3" fill="#C0504A"/>
      <g font-family="system-ui,sans-serif" font-size="9.5" text-anchor="middle">
        <text x="40" y="4" fill="#F2EEE6">中</text><text x="126" y="4" fill="#1A0E06">快</text>
        <text x="212" y="4" fill="#1A0E06">极慢</text><text x="298" y="4" fill="#F2EEE6">快</text>
      </g>
    </g>
    <g transform="translate(0,40)">
      <rect x="0" y="-10" width="80" height="20" rx="3" fill="#5B7FA8" opacity=".7"/>
      <rect x="86" y="-10" width="80" height="20" rx="3" fill="#E8C547" opacity=".7"/>
      <rect x="172" y="-10" width="80" height="20" rx="3" fill="#E07A3F" opacity=".7"/>
      <rect x="258" y="-10" width="80" height="20" rx="3" fill="#C0504A" opacity=".7"/>
      <g font-family="system-ui,sans-serif" font-size="9.5" fill="#1A0E06" text-anchor="middle">
        <text x="40" y="4">4 拍</text><text x="126" y="4">3 拍</text>
        <text x="212" y="4">2 拍</text><text x="298" y="4">复合</text>
      </g>
    </g>
    <g transform="translate(0,80)">
      <g font-family="system-ui,sans-serif" font-size="9.5" fill="#6E6A64" text-anchor="middle">
        <text x="40" y="4">德国</text><text x="126" y="4">法国</text>
        <text x="212" y="4">西班牙</text><text x="298" y="4">英国</text>
      </g>
    </g>

    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      三条对比轴同时起作用：速度 · 节拍 · 民族风格 —— 这才是组曲真正的"组织原则"
    </text>
    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      与奏鸣曲的根本分野：组曲是并列（各乐章独立），奏鸣曲是叙事（各乐章构成整体）
    </text>
  </g>
</svg>
```

## 听一听：性格各异的乐章

用 `chord` 组件听同一个和弦的三种性质（大 / 小 / 减）——
**每个都独立成立、色彩各异**。这就像组曲的乐章：**各自完整，靠对比排在一起。**

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"大三和弦（明亮）","label_en":"Major triad — bright","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"min","inversion":0,"label":"小三和弦（转暗）—— 对照上一条","label_en":"Minor triad — darker, in contrast","hint":"与上一条对比：各自独立、色彩不同","hint_en":"Against the item above: independent, differently coloured"}
```

## 常见误解

- **「组曲只是曲子拼在一起」** → 巴洛克组曲有**固定序列**，并由速度、节拍、民族风格三条对比轴组织。
- **「组曲的乐章也构成一个整体」** → 不要求。**这正是它与奏鸣曲的根本分野**（并列 vs 叙事）。
- **「组曲过时了」** → 19 世纪的"选段组曲"、20 世纪的电影配乐组曲都是它的延续。
- **「组曲必须都是舞曲」** → 巴洛克组曲如此；19 世纪之后"选段组曲"里可以是任何体裁。
:::

::: en
The organising principle of a suite is peculiar, and it fits in one sentence:

> **It is a set of self-standing pieces arranged by some principle — with no pursuit of wholeness.**

That is exactly the opposite of [[concept:large-scale-forms|a sonata or symphony]], where the movements are meant
to form a whole in key, theme and mood. **A suite makes no such demand.**

## The Baroque dance suite: a fixed sequence

The Baroque suite (or partita) has a fairly fixed order:

| Position | Dance | Origin | Speed and character |
|---|---|---|---|
| (prefixed) | **prelude** | — | free, display of technique (often omitted) |
| 1 | **Allemande** | German | moderate, grave, **in four** |
| 2 | **Courante** | French | fast, **in three**, flowing |
| 3 | **Sarabande** | Spanish | **very slow**, in two, accent on the second beat |
| 4 | **Gigue** | English / Irish | fast, **compound metre** (often 6/8), often a fugal close |

**Three design principles hide in that table**, each worth noting:

| Principle | Explanation |
|---|---|
| **contrast of speed** | moderate, fast, very slow, fast — a breathing arc of slow and fast |
| **alternating metre** | four, three, two, compound: **every movement differs** |
| **alternating nationality** | German, French, Spanish, English: **each movement carries a different national style** |

So a suite is not a random assortment — it is organised by **contrast in speed, metre and national style**. This is
often missed: **a suite's coherence lies not in its themes but in this framework of contrasts.**

## What it later became

| Period | What "suite" meant |
|---|---|
| **Baroque** | a set of dances (the sequence above), usually in one key |
| **Classical** | the suite declined, replaced by sonata and symphony; serenades and divertimenti kept its spirit |
| **nineteenth century** | **selections** from theatre, ballet or opera assembled into a "concert suite" |
| **twentieth century** | film-score suites, ballet suites; some composers rewrote Baroque-style suites |

The third row matters: **once "selections" became the main source, the defining feature of a suite shifted from "a
sequence of dances" to "a collection of independent movements"** — which is precisely the division between a suite
and a sonata.

## The key difference from a sonata

| | Suite | Multi-movement sonata |
|---|---|---|
| Relation of movements | **independent** | forming **a whole** (key, theme, mood) |
| Tonality | usually one key, or freely varied | **a planned tonal scheme** |
| Number of movements | unfixed (four to twenty or more) | usually three or four |
| Ordering principle | contrast of speed, metre, style | **a dramatic arc** (fast, slow, dance, fast) |

In one line: **a suite juxtaposes; a sonata narrates.**

## Diagram: three axes of contrast

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">A suite is organised by contrasts of speed, metre and style — not by thematic unity</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">speed</text>
      <text x="-20" y="40" text-anchor="end">metre</text>
      <text x="-20" y="80" text-anchor="end">style</text>
    </g>

    <g>
      <rect x="0" y="-10" width="80" height="20" rx="3" fill="#5B7FA8"/>
      <rect x="86" y="-10" width="80" height="20" rx="3" fill="#E8C547"/>
      <rect x="172" y="-10" width="80" height="20" rx="3" fill="#E07A3F"/>
      <rect x="258" y="-10" width="80" height="20" rx="3" fill="#C0504A"/>
      <g font-family="system-ui,sans-serif" font-size="9.5" text-anchor="middle">
        <text x="40" y="4" fill="#F2EEE6">moderate</text><text x="126" y="4" fill="#1A0E06">fast</text>
        <text x="212" y="4" fill="#1A0E06">very slow</text><text x="298" y="4" fill="#F2EEE6">fast</text>
      </g>
    </g>
    <g transform="translate(0,40)">
      <rect x="0" y="-10" width="80" height="20" rx="3" fill="#5B7FA8" opacity=".7"/>
      <rect x="86" y="-10" width="80" height="20" rx="3" fill="#E8C547" opacity=".7"/>
      <rect x="172" y="-10" width="80" height="20" rx="3" fill="#E07A3F" opacity=".7"/>
      <rect x="258" y="-10" width="80" height="20" rx="3" fill="#C0504A" opacity=".7"/>
      <g font-family="system-ui,sans-serif" font-size="9.5" fill="#1A0E06" text-anchor="middle">
        <text x="40" y="4">in 4</text><text x="126" y="4">in 3</text>
        <text x="212" y="4">in 2</text><text x="298" y="4">compound</text>
      </g>
    </g>
    <g transform="translate(0,80)">
      <g font-family="system-ui,sans-serif" font-size="9.5" fill="#6E6A64" text-anchor="middle">
        <text x="40" y="4">German</text><text x="126" y="4">French</text>
        <text x="212" y="4">Spanish</text><text x="298" y="4">English</text>
      </g>
    </g>

    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Three axes working at once: speed, metre, national style — the suite's real organising principle
    </text>
    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Versus a sonata: a suite juxtaposes, a sonata narrates
    </text>
  </g>
</svg>
```

## Listen: movements with different characters

Use `chord` to hear one chord in three qualities (major, minor, diminished) — **each stands on its own, each a
different colour.** That is like the movements of a suite: **complete in themselves, placed together for
contrast.**

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"大三和弦（明亮）","label_en":"Major triad — bright","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"min","inversion":0,"label":"小三和弦（转暗）—— 对照上一条","label_en":"Minor triad — darker, in contrast","hint":"与上一条对比：各自独立、色彩不同","hint_en":"Against the item above: independent, differently coloured"}
```

## Common misconceptions

- **"A suite is just pieces thrown together."** The Baroque suite had a **fixed sequence**, organised by three axes
  of contrast: speed, metre and national style.
- **"A suite's movements also form a whole."** They need not. **That is exactly the divide from a sonata**
  (juxtaposition versus narrative).
- **"The suite is obsolete."** The nineteenth-century concert suite and the twentieth-century film-score suite are
  its continuations.
- **"A suite must be all dances."** True of the Baroque suite; after the nineteenth century a "selection suite" may
  contain anything.
:::
