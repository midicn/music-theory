---
id: canon
site: theo
cat: T6
title: 卡农
title_en: Canon
summary: 一条旋律被另一声部严格追随到底——模仿用到极致
summary_en: One melody followed faithfully to the end by another voice — imitation taken to its limit
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [卡农, 轮唱, canon]
order: 24
links:
  - "[[concept:imitation]]"
  - "[[concept:counterpoint]]"
  - "[[concept:fugue]]"
  - "[[concept:contrapuntal-devices]]"
  - "[[concept:pedal-point]]"
instances:
  - atepp-002452 | 巴赫《哥德堡变奏曲》第 12 变奏：明确标为 Canon（Canone），是严格卡农最可靠的实例之一 | Bach's Goldberg Variations, Variation 12 — marked Canon outright, one of the most reliable instances of strict canon
  - atepp-000355 | 格里格《抒情小品》Op.38 中的《卡农》：浪漫派作曲家写卡农，可对照与巴洛克处理的差别 | Grieg's Lyric Pieces Op.38 includes a Canon — a Romantic composer's canon, useful against Baroque practice
  - mutopia-000280 | 巴赫二部创意曲第一首：声部的进入是完整的模仿，可听出"卡农式织体"的雏形 | Bach's first two-part invention — complete imitative entries, showing the germ of canonic texture
sources:
  - 卡农指同一旋律在不同声部按固定规则严格追随的复调写法，属对位学通则
  - 变形卡农（倒影 / 逆行 / 增值 / 减值）与"不同间隔、不同音程"的进入方式为通行对位教学表述
updated: 2026-09-24
---

::: zh
卡农只有一个条件：**一条旋律被追随到底，一句不落。**

> 模仿只要"跟着说一句"就够了；卡农要求**从进入那一刻起跟到最后**。

所以两者的关系是：

> **模仿是手法，卡农是"把模仿用到极限"的形态。**（见 [[concept:imitation|模仿]]）

## 最简形态与变化轴

**最简的卡农是同度进入** —— 第二个声部晚一小节从头唱同样的旋律，这就是「轮唱」
（《两只老虎》《划船歌》都是）。但要写得不撞车非常难，因为两声部永远差着固定的一步。

改变"追随规则"，就得到不同的卡农：

| 变化轴 | 做法 | 结果 |
|---|---|---|
| **进入间隔** | 一小节 / 两小节 / 半小节 | 越短越紧密（最短就是紧接） |
| **进入音程** | 同度 / 八度 / 五度 / 其他 | 五度、四度会带来调式色彩变化 |
| **方向** | 跟随声部唱**上下颠倒**的版本（倒影卡农） | 线条走向相反，仍能成对（见 [[concept:contrapuntal-devices|对位变形手法]]） |
| **时间** | 把旋律**时长加倍或减半**（增值 / 减值卡农） | 一个声部变成"慢动作"，织体立刻变宽 |
| **方向 + 时间** | 逆行（从尾到头）等 | 极端手法，常用于严格写作训练 |

## 一个必须澄清的常见误会

**帕赫贝尔的《D 大调卡农》并不严格是"卡农"。**

它由两层构成：

| 层 | 写法 |
|---|---|
| **低音** | 一个两小节的**固定低音**（ostinato）循环反复（见 [[concept:pedal-point|持续低音]]） |
| **上方三把小提琴** | 才是**卡农** —— 三声部严格追随 |

也就是说：**低音不是卡农，上方才是。** 整首作品是"固定低音 + 卡农"的组合体。
它之所以常被简化成"卡农"，是因为上方那层太出彩，把结构遮住了 ——
但准确地说，它是**固定低音变奏与卡农的复合**。

## 卡农与赋格的区别

两者都建立在模仿上，但目标不同：

| | 卡农 | 赋格 |
|---|---|---|
| 追随方式 | **全程严格**（一句不落） | 主题**多次进入**，中间用间插段连接 |
| 是否有"自由段" | 基本没有 | **有**（间插段正是自由段） |
| 靠什么发展 | 规则的变化（音程 / 方向 / 时值） | 主题在不同调性上的进入与组合 |
| 关系 | 更"严"，更接近数学 | 更"活"，可容纳丰富的和声变化 |

一句话：**卡农把规则用到极致，赋格把素材用到极致。**

## 图示：卡农的"差一步"

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">第二声部晚一步唱同样的东西 —— 难在"永远差着固定的一步"</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      <text x="-38" y="6" text-anchor="end">第一声部</text>
    </g>
    <g>
      <rect x="0" y="-6" width="130" height="18" rx="3" fill="#E07A3F"/>
      <text x="65" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">旋律 A</text>
      <rect x="130" y="-6" width="130" height="18" rx="3" fill="#E07A3F" opacity=".75"/>
      <text x="195" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">旋律 B</text>
      <rect x="260" y="-6" width="130" height="18" rx="3" fill="#E07A3F" opacity=".55"/>
      <text x="325" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">旋律 C</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      <text x="-38" y="62" text-anchor="end">第二声部</text>
    </g>
    <g>
      <rect x="130" y="50" width="130" height="18" rx="3" fill="#5B7FA8"/>
      <text x="195" y="63" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">旋律 A</text>
      <rect x="260" y="50" width="130" height="18" rx="3" fill="#5B7FA8" opacity=".75"/>
      <text x="325" y="63" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">旋律 B</text>
    </g>
    <g stroke="#E8C547" stroke-width="1.2" stroke-dasharray="3 3">
      <line x1="130" y1="-8" x2="130" y2="50"/>
    </g>
    <text x="136" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">固定的进入间隔</text>
    <text x="0" y="112" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      两声部永远差着同一个间隔 —— 所以每一个纵向音程都被"锁死"，写作难度就在这里
    </text>
    <text x="0" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      改变进入间隔 / 音程 / 方向 / 时值，就得到不同的卡农；倒影与逆行卡农属对位变形手法
    </text>
  </g>
</svg>
```

## 听一听：进入间隔的关系

卡农是两声部的事，本站的听辨件放不出真正的两声部 —— 这里用 `interval` 演示
**卡农进入时的音程**（第二声部从哪个高度进来），而这正是卡农最核心的变量。
两声部"差一步"的实际效果请到上面的实例里听：巴赫《哥德堡变奏曲》第 12 变奏（`atepp-002452`）最短最清楚。

```audiolab
{"type":"interval","a":"C4","b":"C5","label":"同度类进入：八度","label_en":"Octave entry — the unison class","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 G4 就是五度进入，色彩会明显不同（带属调倾向）。","hint2_en":"Set b to G4 for entry at the fifth — the colour changes noticeably, with a dominant lean."}
```

## 常见误解

- **「卡农就是帕赫贝尔那首」** → 卡农是一种**写法**，作品无数。而且帕赫贝尔那首里**只有上方三声部是卡农**，低音是固定低音。
- **「卡农必须完全一样」** → 那只是最简形态。倒影、逆行、增值、减值都是卡农的合法变体。
- **「卡农只是轮唱」** → 轮唱（同度卡农）是最简单的一种；卡农的大多数写法比它复杂得多。
- **「卡农比赋格简单」** → 卡农的**约束更紧**（全程严格），只是发展手段更少。两者是不同方向的困难。
:::

::: en
A canon has one requirement: **one melody followed faithfully all the way to the end, nothing omitted.**

> Imitation only needs "say one line back". A canon requires **following from the moment of entry to the end.**

So the relation is:

> **Imitation is the device; a canon is imitation taken to its limit.** (See [[concept:imitation|imitation]].)

## The simplest form and the axes of variation

**The simplest canon enters at the unison** — the second voice starts the same melody a bar later. That is
round singing (as in "Frère Jacques"). It is also very hard to write without collisions, because the two voices
are permanently one fixed step apart.

Change the "following rule" and you get different canons:

| Axis | Method | Result |
|---|---|---|
| **entry spacing** | a bar / two bars / half a bar | the shorter the tighter (the extreme is a stretto) |
| **entry interval** | unison / octave / fifth / other | fifths and fourths introduce modal colour changes |
| **direction** | the following voice sings the melody **upside down** (mirror canon) | the lines move in opposite directions yet still pair (see [[concept:contrapuntal-devices|contrapuntal devices]]) |
| **time** | double or halve the note values (augmentation / diminution canon) | one voice turns into "slow motion" and the texture widens at once |
| **direction and time** | retrograde (back to front) and similar | extreme devices, mostly for strict-writing study |

## One common misunderstanding that must be cleared up

**Pachelbel's Canon in D is not strictly "a canon".**

It has two layers:

| Layer | Writing |
|---|---|
| **bass** | a two-bar **ground bass** (ostinato) repeating (see [[concept:pedal-point|pedal point]]) |
| **three violins above** | these are the **canon** — three voices following strictly |

In other words: **the bass is not the canon; the parts above are.** The whole piece is a combination of ground
bass and canon. It is usually shortened to "Canon" because the upper layer is so striking that it hides the
structure — but accurately, it is **ground-bass variation combined with canon**.

## How it differs from a fugue

Both rest on imitation, but with different goals:

| | Canon | Fugue |
|---|---|---|
| Following | **strict throughout** (nothing omitted) | the subject **enters repeatedly**, linked by episodes |
| Free passages | essentially none | **yes** — episodes are exactly that |
| Means of development | changing the rule (interval / direction / time value) | the subject entering in different keys and combinations |
| Relation | more rigid, closer to mathematics | more flexible, admits rich harmonic change |

In one line: **a canon takes the rule to its limit; a fugue takes the material to its limit.**

## Diagram: the canon's fixed lag

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The second voice sings the same thing one step late — hard because the lag never changes</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      <text x="-38" y="6" text-anchor="end">voice one</text>
    </g>
    <g>
      <rect x="0" y="-6" width="130" height="18" rx="3" fill="#E07A3F"/>
      <text x="65" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">phrase A</text>
      <rect x="130" y="-6" width="130" height="18" rx="3" fill="#E07A3F" opacity=".75"/>
      <text x="195" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">phrase B</text>
      <rect x="260" y="-6" width="130" height="18" rx="3" fill="#E07A3F" opacity=".55"/>
      <text x="325" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">phrase C</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      <text x="-38" y="62" text-anchor="end">voice two</text>
    </g>
    <g>
      <rect x="130" y="50" width="130" height="18" rx="3" fill="#5B7FA8"/>
      <text x="195" y="63" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">phrase A</text>
      <rect x="260" y="50" width="130" height="18" rx="3" fill="#5B7FA8" opacity=".75"/>
      <text x="325" y="63" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">phrase B</text>
    </g>
    <g stroke="#E8C547" stroke-width="1.2" stroke-dasharray="3 3">
      <line x1="130" y1="-8" x2="130" y2="50"/>
    </g>
    <text x="136" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">a fixed entry lag</text>
    <text x="0" y="112" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      The lag never changes, so every vertical interval is locked in — that is where the difficulty lies
    </text>
    <text x="0" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Change the spacing, interval, direction or note values for different canons; mirror and retrograde are contrapuntal devices
    </text>
  </g>
</svg>
```

## Listen: the entry interval

A canon needs two voices, and this site's components are single-voice — so `interval` demonstrates **the interval
of the canon's entry** (the height at which the second voice comes in), one of its key variables. For the actual
fixed-lag effect, use the instances: Bach's Goldberg Variation 12 (`atepp-002452`) is the shortest and clearest.

```audiolab
{"type":"interval","a":"C4","b":"C5","label":"同度类进入：八度","label_en":"Octave entry — the unison class","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 G4 就是五度进入，色彩会明显不同（带属调倾向）。","hint2_en":"Set b to G4 for entry at the fifth — the colour changes noticeably, with a dominant lean."}
```

## Common misconceptions

- **"A canon means Pachelbel's."** A canon is a **way of writing**; there are countless works. And in Pachelbel's
  piece **only the three upper violins are the canon** — the bass is a ground bass.
- **"A canon must be identical throughout."** That is only the simplest form. Mirror, retrograde, augmentation and
  diminution canons are all legitimate variants.
- **"A canon is just a round."** Round singing (unison canon) is the easiest kind; most canons are far more
  complex.
- **"Canons are easier than fugues."** A canon's constraints are **tighter** (strict throughout), it simply has
  fewer means of development. The two are difficult in different directions.
:::
