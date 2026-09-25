---
id: staff
site: theo
cat: T10
title: 五线谱
title_en: The Staff
summary: 五条线是"位置"，不是"音高"——它必须配谱号才有意义
summary_en: Five lines give positions, not pitches — a staff means nothing without a clef
level: core
tags: [乐理, 记谱, 基础]
tags_en: [theory, notation, basics]
alias: [五线谱, 谱表, staff, stave]
order: 10
links:
  - "[[concept:clef]]"
  - "[[concept:note-values]]"
  - "[[concept:key-signature]]"
  - "[[concept:interval]]"
  - "[[concept:rests]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：谱面结构最清楚，可用来数"每一条线与每一个间" | Scale and cadence exercises have the clearest layout for counting each line and each space
  - mutopia-000522 | 《欢乐颂》主题：音域窄、级进为主，谱面上的位置移动非常规整，适合初学者对位 | The Ode of Joy has a narrow range and mostly stepwise motion, so positions on the staff move very regularly
  - thesession-019704 | 《小星星》：谱面极简，可用于确认"相邻位置=相邻音级"这条读谱铁律 | Twinkle Little Star's notation is minimal, useful for confirming that adjacent positions mean adjacent degrees
sources:
  - 五线谱由五条线与四个间构成、线间距为三度（相邻线空一个音级），为记谱法通则
  - 五线谱必须配合谱号才能确定音高，为通行记谱规范
updated: 2026-09-25
---

::: zh
五线谱最容易被误解的一点：

> **五条线本身不表示任何音高。** 它们只表示**位置**。
> 必须配上**谱号**（见 [[concept:clef|谱号]]），位置才变成音高。

所以"这条线上的音是什么"这个问题，**在没有谱号时是无法回答的**。

## 结构：线与间

| 元素 | 数量 | 说明 |
|---|---|---|
| **线** | 5 条 | 从下往上数：第一线到第五线 |
| **间** | 4 个 | 线之间：第一间到第四间 |
| **总位置** | **9 个** | 不够用时就加**加线**（上加线 / 下加线） |

## 最重要的读谱认识：相邻 = 三度

这是全部读谱的基石：

> **相邻的线（或相邻的间）之间隔着一个音级，也就是三度。**

| 位置关系 | 音程 |
|---|---|
| 线与**紧邻的**间 | **二度**（级进，相邻音级） |
| 线与**下一条**线 | **三度**（跳过一个音级） |
| 线与下下条线 | 五度 |

**记住"线—间 = 二度、线—线 = 三度"，读谱速度会立刻改变** ——
因为它让你不必每次都在心里数音名。

这也说明一件重要的事：**五线谱本质上是"级数图"，不是"音名表"**。
它画的是音阶上的第几级（高低关系），而不是绝对音名 ——
这与 [[concept:key-signature|调号]] 让同一谱面能表示不同调是同一个设计思想。

## 为什么是五条线

不是偶然，而是一次历史选择：

| 阶段 | 谱面 | 问题 |
|---|---|---|
| 早期（圣咏） | **四线** | 音域稍宽就要大量加线 |
| 后来 | **五线** | **常用音域刚好装下，加线不频繁** |
| 更宽的谱面 | 六线以上 | 读起来更费劲，收益不大 |

**五条线是"够用 + 好读"的平衡点。** 这也解释了为什么不同乐器要用不同**谱号**
（见 [[concept:clef|谱号]]）：**不是改谱面，而是把谱面"移到"该乐器最常用的音区**。

## 图示：位置与音程

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">五条线 + 四个间 = 九个位置；线到线是三度，线到间是二度</text>
  </g>

  <g transform="translate(60,52)">
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="0" x2="360" y2="0"/>
      <line x1="0" y1="16" x2="360" y2="16"/>
      <line x1="0" y1="32" x2="360" y2="32"/>
      <line x1="0" y1="48" x2="360" y2="48"/>
      <line x1="0" y1="64" x2="360" y2="64"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="9.5" fill="#6E6A64">
      <text x="-8" y="4" text-anchor="end">第 5 线</text>
      <text x="-8" y="20" text-anchor="end">第 4 线</text>
      <text x="-8" y="36" text-anchor="end">第 3 线</text>
      <text x="-8" y="52" text-anchor="end">第 2 线</text>
      <text x="-8" y="68" text-anchor="end">第 1 线</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="9.5" fill="#E8C547">
      <text x="372" y="12">第 4 间</text><text x="372" y="28">第 3 间</text>
      <text x="372" y="44">第 2 间</text><text x="372" y="60">第 1 间</text>
    </g>

    <g transform="translate(150,0)">
      <circle cx="0" cy="64" r="5" fill="#E07A3F"/>
      <circle cx="0" cy="48" r="5" fill="#E07A3F"/>
      <text x="14" y="60" font-family="system-ui,sans-serif" font-size="10" fill="#E07A3F">线→间 = 二度（级进）</text>
    </g>
    <g transform="translate(280,0)">
      <circle cx="0" cy="64" r="5" fill="#5B7FA8"/>
      <circle cx="0" cy="32" r="5" fill="#5B7FA8"/>
      <g stroke="#343439" stroke-width="1" stroke-dasharray="2 2"><line x1="8" y1="64" x2="8" y2="32"/></g>
      <text x="14" y="50" font-family="system-ui,sans-serif" font-size="10" fill="#5B7FA8">线→线 = 三度</text>
    </g>

    <text x="0" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      五线谱本质上是"级数图"（画高低关系），不是"音名表" —— 必须配谱号才有音高
    </text>
    <text x="0" y="114" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      为什么是五条线：早期圣咏用四线，五线是"常用音域刚好装下 + 加线不频繁"的平衡点
    </text>
  </g>
</svg>
```

## 听一听：级进与跳进在谱面上的样子

用 `scale` 组件听级进 —— **谱面上就是"线—间—线—间"的相邻移动**。
这正对应上表里的"线→间 = 二度"：五线谱的视觉结构与听觉的级进是直接对应的。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4"],"label":"级进（谱面上是线—间—线—间）","label_en":"Stepwise motion — line, space, line, space on the staff","hint":"点「上行」：每一步都是二度","hint_en":"Try Up: every step is a second","gap":0.36}
```

## 常见误解

- **「线表示音高」** → 线只表示**位置**。没有谱号，五线谱不传达任何音高。
- **「线之间的距离是二度」** → 是**三度**（中间隔着一条间/一个音级）。线到**间**才是二度。
- **「五线谱的音域很窄」** → 靠**加线**可任意扩展；钢琴用两个五线谱正是为了覆盖宽音域。
- **「不同乐器用不同谱号是习惯问题」** → 是**功能选择**：让该乐器最常用的音区落在谱面中央，减少加线。
:::

::: en
The single most misunderstood thing about the staff:

> **The five lines themselves indicate no pitch.** They indicate **positions**.
> Only with a **clef** (see [[concept:clef|clef]]) does a position become a pitch.

So "what note is on this line" **cannot be answered without a clef.**

## Structure: lines and spaces

| Element | Count | Explanation |
|---|---|---|
| **lines** | 5 | numbered from the bottom: first line to fifth line |
| **spaces** | 4 | between the lines: first space to fourth space |
| **total positions** | **9** | when that is not enough, **ledger lines** extend the staff |

## The crucial reading insight: adjacent means a third

This is the foundation of all score reading:

> **Adjacent lines (or adjacent spaces) are a third apart — they skip one degree.**

| Relation | Interval |
|---|---|
| a line to the **neighbouring** space | **a second** (a step) |
| a line to the **next** line | **a third** (one degree skipped) |
| a line to the line beyond that | a fifth |

**Once you hold "line-to-space is a second, line-to-line is a third", reading speed changes immediately** —
because you no longer count note names in your head at every step.

It also shows something important: **the staff is essentially a degree chart, not a name chart.** It shows which
degree of the scale (the high-low relation), not an absolute name — the same design idea that lets one staff serve
different keys (see [[concept:key-signature|key signature]]).

## Why five lines

Not an accident but a historical choice:

| Stage | Staff | Problem |
|---|---|---|
| early (chant) | **four lines** | a slightly wider range needed many ledger lines |
| later | **five lines** | **the common range fits with few ledger lines** |
| wider | six or more lines | harder to read, little gained |

**Five lines is the balance point between "enough" and "readable".** It also explains why different instruments use
different **clefs** (see [[concept:clef|clef]]): **the staff is not changed, it is shifted to sit in the register
that instrument uses most.**

## Diagram: positions and intervals

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Five lines plus four spaces make nine positions; line to line is a third, line to space a second</text>
  </g>

  <g transform="translate(60,52)">
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="0" x2="360" y2="0"/>
      <line x1="0" y1="16" x2="360" y2="16"/>
      <line x1="0" y1="32" x2="360" y2="32"/>
      <line x1="0" y1="48" x2="360" y2="48"/>
      <line x1="0" y1="64" x2="360" y2="64"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="9.5" fill="#6E6A64">
      <text x="-8" y="4" text-anchor="end">line 5</text>
      <text x="-8" y="20" text-anchor="end">line 4</text>
      <text x="-8" y="36" text-anchor="end">line 3</text>
      <text x="-8" y="52" text-anchor="end">line 2</text>
      <text x="-8" y="68" text-anchor="end">line 1</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="9.5" fill="#E8C547">
      <text x="372" y="12">space 4</text><text x="372" y="28">space 3</text>
      <text x="372" y="44">space 2</text><text x="372" y="60">space 1</text>
    </g>

    <g transform="translate(150,0)">
      <circle cx="0" cy="64" r="5" fill="#E07A3F"/>
      <circle cx="0" cy="48" r="5" fill="#E07A3F"/>
      <text x="14" y="60" font-family="system-ui,sans-serif" font-size="10" fill="#E07A3F">line to space: a second</text>
    </g>
    <g transform="translate(280,0)">
      <circle cx="0" cy="64" r="5" fill="#5B7FA8"/>
      <circle cx="0" cy="32" r="5" fill="#5B7FA8"/>
      <g stroke="#343439" stroke-width="1" stroke-dasharray="2 2"><line x1="8" y1="64" x2="8" y2="32"/></g>
      <text x="14" y="50" font-family="system-ui,sans-serif" font-size="10" fill="#5B7FA8">line to line: a third</text>
    </g>

    <text x="0" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      The staff is a degree chart, not a name chart — a clef is what turns positions into pitches
    </text>
    <text x="0" y="114" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Why five lines: chant used four; five fits the common range with few ledger lines
    </text>
  </g>
</svg>
```

## Listen: what steps look like on the staff

Use `scale` to hear stepwise motion — **on the staff this is the adjacent motion line, space, line, space.** That
matches "line to space is a second": the staff's visual structure corresponds directly to stepwise hearing.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4"],"label":"级进（谱面上是线—间—线—间）","label_en":"Stepwise motion — line, space, line, space on the staff","hint":"点「上行」：每一步都是二度","hint_en":"Try Up: every step is a second","gap":0.36}
```

## Common misconceptions

- **"Lines indicate pitch."** Lines indicate **position**. Without a clef the staff conveys no pitch at all.
- **"Lines are a second apart."** They are a **third** apart (one degree skipped). Line to **space** is a second.
- **"The staff's range is narrow."** **Ledger lines** extend it without limit; the piano uses two staves to cover a
  wide range.
- **"Different clefs are a matter of habit."** A **functional choice**: put the instrument's common register in the
  middle of the staff and reduce ledger lines.
:::
