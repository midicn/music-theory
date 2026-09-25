---
id: sequence
site: theo
cat: T5
title: 模进
title_en: Sequence
summary: 把同一音型在不同高度重复——最简单的推进手段
summary_en: Repeat one figure at different pitch levels — the simplest way to keep music moving
level: standard
tags: [乐理, 和声, 旋律]
tags_en: [theory, harmony, melody]
alias: [模进, 音型模进, sequence]
order: 28
links:
  - "[[concept:melody]]"
  - "[[concept:motive]]"
  - "[[concept:harmonic-function]]"
  - "[[concept:canon]]"
  - "[[concept:sonata-form]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：主题以模进方式在不同高度反复，全曲结构由此展开 | Bach's first two-part invention — the subject recurs at different pitch levels by sequence, and the piece unfolds from there
  - giantmidi-006222 | 音阶与琶音练习本身就是最朴素的模进：同一音型不断移位 | Scale and arpeggio exercises are the plainest kind of sequence — one figure shifted again and again
  - atepp-000318 | a 小调奏鸣曲：展开部大量使用模进推进，可听它如何制造"往前冲"的感觉 | A sonata in A minor — the development leans heavily on sequences, and the forward surge is audible
sources:
  - 模进指同一音型（旋律型或和声型）在不同音高上的重复，属乐理与曲式通则
  - 模进与单纯重复的区别在于是否移位，为通行表述
updated: 2026-09-24
---

::: zh
模进（sequence）只做一件事：**把刚才那个音型，原样搬到另一个高度再说一遍。**

> 原型：C–D–E
> 模进：D–E–F → E–F–G → …

它的力量来自**双重效果**：听者听到的是"熟悉的东西"（音型没变），
同时又是"新的东西"（高度变了）。**熟悉 + 新鲜**，这是它极其好用的原因。

## 与"重复"的区别

| | 重复 | 模进 |
|---|---|---|
| 音型 | 不变 | 不变 |
| 高度 | **不变** | **改变** |
| 效果 | 强调 | **推进** |

单纯重复三次会显得笨拙；模进三次则显得有方向。差别就在"移位"这一件事。

## 常见类型

| 类型 | 移位间隔 | 常见场合 |
|---|---|---|
| **二度模进** | 上行或下行一个音级 | 最常用，推进感最强 |
| **三度模进** | 三度 | 较温和，色彩变化明显 |
| **下行模进** | 向下移位 | 常用于"退让、叹息"的语气 |
| **和声模进** | 整组和弦一起移位 | 巴洛克与古典展开部的标配 |

**和声模进**尤其值得留意：它不是旋律单独移位，而是**旋律与和声一起搬**。
这让它成为最有效的"扩大结构"手段 —— 一个小乐思可以靠模进撑满一整段。

## 它在曲式里的位置

模进几乎是所有"需要推进"的位置的首选：见 [[concept:sonata-form|奏鸣曲式]] 的展开部、
赋格的间插段（参见 [[concept:canon|卡农]] 与 [[concept:fugue|赋格]]）。
它的功能是：**在不引入新素材的前提下，把音乐往前推。**

## 图示：音型不变，高度变了

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一个音型（上行两音）在三个高度上重复</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="40" y="0">D</text>
      <text x="140" y="-20">D</text><text x="180" y="-20">E</text>
      <text x="280" y="-40">E</text><text x="320" y="-40">F</text>
      <text x="420" y="-60">F</text><text x="460" y="-60">G</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="10" x2="40" y2="10"/>
      <line x1="140" y1="-10" x2="180" y2="-10"/>
      <line x1="280" y1="-30" x2="320" y2="-30"/>
      <line x1="420" y1="-50" x2="460" y2="-50"/>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="20" y1="6" x2="160" y2="-14"/>
      <line x1="160" y1="-14" x2="300" y2="-34"/>
      <line x1="300" y1="-34" x2="440" y2="-54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="20" y="28" text-anchor="middle">原型</text>
      <text x="160" y="8" text-anchor="middle">移位 1</text>
      <text x="300" y="-12" text-anchor="middle">移位 2</text>
      <text x="440" y="-32" text-anchor="middle">移位 3</text>
    </g>
    <text x="0" y="52" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      音型（上行两音）保持不变，只有高度在变 —— 听者因此感到"熟悉又新鲜"
    </text>
    <text x="0" y="74" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      和声模进：整组和弦一起移位（巴洛克与古典展开部的标配）
    </text>
  </g>
</svg>
```

## 听一听：模进的推进感

用进行播放器听一段**下行模进式**进行：功能和弦不变，但整组往下搬。
留意它如何在不引入新素材的情况下产生"往前走"的感觉。

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I","V","I","V"],"label":"同一音型的往复推进","label_en":"One figure pushed forward by repetition","hint":"逐个和弦依次听，注意它如何一直向前","hint_en":"Hear each chord in turn and notice the sense of onward motion"}
```

## 常见误解

- **「模进就是重复」** → 关键在**移位**。不移位的重复是强调，移位的重复才是推进。
- **「模进太机械，不算作曲手法」** → 它是巴洛克与古典最主要的展开手段之一，用在展开部、间插段、过渡段。
- **「模进必须完全一样」** → 严格模进（音程完全照搬）与自由模进（随和声调整）都有；后者更常见。
- **「模进只能向上」** → 上下都有。下行模进常表达退让或悲叹，在浪漫派作品里很常见。
:::

::: en
A sequence does exactly one thing: **take the figure you just had and say it again at another pitch level.**

> model: C–D–E
> sequence: D–E–F → E–F–G → …

Its power lies in a **double effect**: the listener hears something familiar (the figure is unchanged) and
something new (the pitch has moved). **Familiar plus fresh** is why it is so useful.

## How it differs from repetition

| | Repetition | Sequence |
|---|---|---|
| Figure | unchanged | unchanged |
| Pitch | **unchanged** | **changed** |
| Effect | emphasis | **propulsion** |

Repeating one thing three times looks clumsy; sequencing it three times sounds purposeful. The single variable is
the shift.

## Common types

| Type | Interval of the shift | Typical use |
|---|---|---|
| **stepwise sequence** | one degree up or down | the most common, strongest drive |
| **third sequence** | a third | gentler, with a clear change of colour |
| **descending sequence** | shifting downward | often a tone of yielding or lament |
| **harmonic sequence** | a whole chord group shifted | standard in Baroque and Classical development sections |

**Harmonic sequences** are worth particular attention: the melody and the harmony move **together**, which makes
them the most effective way to **enlarge a structure** — one small idea can fill a whole passage.

## Where it sits in form

A sequence is the first choice wherever music needs to advance: see the development of
[[concept:sonata-form|sonata form]], and the episodes of a fugue (see [[concept:canon|canon]] and
[[concept:fugue|fugue]]). Its function is **to push the music forward without introducing new material.**

## Diagram: same figure, different height

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One figure (a rising two-note step) repeated at three heights</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="40" y="0">D</text>
      <text x="140" y="-20">D</text><text x="180" y="-20">E</text>
      <text x="280" y="-40">E</text><text x="320" y="-40">F</text>
      <text x="420" y="-60">F</text><text x="460" y="-60">G</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="10" x2="40" y2="10"/>
      <line x1="140" y1="-10" x2="180" y2="-10"/>
      <line x1="280" y1="-30" x2="320" y2="-30"/>
      <line x1="420" y1="-50" x2="460" y2="-50"/>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="20" y1="6" x2="160" y2="-14"/>
      <line x1="160" y1="-14" x2="300" y2="-34"/>
      <line x1="300" y1="-34" x2="440" y2="-54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="20" y="28" text-anchor="middle">model</text>
      <text x="160" y="8" text-anchor="middle">shift 1</text>
      <text x="300" y="-12" text-anchor="middle">shift 2</text>
      <text x="440" y="-32" text-anchor="middle">shift 3</text>
    </g>
    <text x="0" y="52" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      The figure stays the same, only the height changes — familiar and fresh at once
    </text>
    <text x="0" y="74" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      A harmonic sequence shifts the whole chord group, standard in Baroque and Classical development
    </text>
  </g>
</svg>
```

## Listen: the drive of a sequence

Use the progression player on a **sequencing** progression: the functional chords stay the same while the whole
group is moved. Notice how it creates onward motion without any new material.

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I","V","I","V"],"label":"同一音型的往复推进","label_en":"One figure pushed forward by repetition","hint":"逐个和弦依次听，注意它如何一直向前","hint_en":"Hear each chord in turn and notice the sense of onward motion"}
```

## Common misconceptions

- **"A sequence is just repetition."** The **shift** is the whole point. Repetition without shifting emphasises; repetition with shifting propels.
- **"Sequences are mechanical, not real composing."** They are among the principal means of development in Baroque and Classical music — used in developments, episodes and transitions.
- **"A sequence must be exact."** Both strict sequences (intervals copied literally) and free ones (adjusted to the harmony) exist; the free kind is more common.
- **"Sequences only go up."** Both directions occur. Descending sequences often express yielding or lament, and are common in Romantic music.
:::
