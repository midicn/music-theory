---
id: simple-compound-meter
site: theo
cat: T7
title: 单拍子、复拍子与混合拍子
title_en: Simple, Compound and Irregular Metre
summary: 判据只有一个问题——每拍能不能平分成两个
summary_en: One question decides it — can each beat be split into two?
level: standard
tags: [乐理, 节奏, 基础]
tags_en: [theory, rhythm, basics]
alias: [单拍子, 复拍子, 混合拍子, 复合拍子, compound metre]
order: 20
links:
  - "[[concept:meter]]"
  - "[[concept:metric-accent]]"
  - "[[concept:tuplet]]"
  - "[[concept:rhythm]]"
  - "[[concept:dance-rhythm]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：常见的四拍写法，每拍可平分为二，是单拍子的标准形态 | An organ hymn in common time — each beat splits in two, the standard shape of simple metre
  - giantmidi-006222 | 音阶与终止练习：所记拍号多为单拍子，可用作"每拍分二"的基准 | Scale and cadence exercises are mostly notated in simple metre, a baseline for division by two
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：舞曲性质的三拍循环贯穿全曲，可与复拍子的三分感觉对照 | Liszt's transcription of Danse macabre — a dance-like triple cycle throughout, useful against compound metre's division by three
sources:
  - 单拍子（每拍二等分）/ 复拍子（每拍三等分，分子为 3 的倍数）/ 混合拍子（不规则组合）的分类，属乐理通则
  - 5/4 与 7/8 的重音分组（2+3 或 3+2）决定听感，为通行表述
updated: 2026-09-25
---

::: zh
三类拍子的区分只用一个问题就够了：

> **每一拍，能不能平分成两个？**

| 类别 | 每拍内部 | 判据 | 例 |
|---|---|---|---|
| **单拍子** | 分成**二** | 分子**不是** 3 的倍数（或分母 = 4 / 2） | 2/4 · 3/4 · 4/4 |
| **复拍子** | 分成**三** | 分子是 **3 的倍数**，且分母 ≥ 8 | 6/8 · 9/8 · 12/8 |
| **混合拍子** | — | 分子是 **5、7** 等不能整除的数 | 5/4 · 7/8 |

注意一个容易漏的点：**6/4 也是复拍子**（分子 6 = 3×2），所以判据里"分母 ≥ 8"是**附加**条件，
用来区分"6/8 这样的复拍子"与"6/4 这种实际按两个大拍走的写法"。真正可靠的办法是**听**：
每拍分成两个还是三个。

## 6/8 与 3/4 的区别到底是什么

这是本条最实用的辨识点：

| | 3/4 | 6/8 |
|---|---|---|
| 拍数 | 三拍 | 六拍（或两个大拍） |
| 每拍内部 | **分成二** | **分成三** |
| 听感 | 每拍一个重音，共三个 | 每两拍一组，共两大组 |
| 常见体裁 | 圆舞曲、进行曲 | 摇篮曲、船歌、许多民间舞曲 |

**关键：这不是"快慢"的区别，而是"每拍内部分成几份"的区别。**
把 3/4 弹快不会变成 6/8；把 6/8 弹慢也不会变成 3/4。

## 混合拍子：重音分组决定听感

5/4 和 7/8 本身是**不完整的**——它们必须被指定分组方式：

| 拍号 | 分组 | 听感 |
|---|---|---|
| **5/4** | **3+2** | 像"三拍的圆舞曲 + 两拍"（常见于《拿坡里舞曲》类） |
| **5/4** | **2+3** | 像"两拍 + 三拍"，重音在前，更方正 |
| **7/8** | **2+2+3** | 巴尔干民间音乐最典型的分组 |

**同一串音，换一种分组就变成另一首曲子** —— 因为重音周期变了（见 [[concept:metric-accent|强弱规律]]）。
这也是混合拍子"听起来很现代"的原因：它不是靠不协和，而是靠**让人数不清拍**来制造不安。

## 与连音的关系

一个容易混的边界：**复拍子里的三个音不需要连音记号**（分母本身就是 8 或 16），
而在单拍子里想放三个音就必须写三连音（见 [[concept:tuplet|连音]]）。

> **判断口诀：三是不是"写在拍号里"的？**
> 是 → 复拍子（无需连音）；不是 → 单拍子（需要连音）。

## 图示：三种拍子的内部结构

```svg
<svg viewBox="0 0 640 212" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">判据只有一个问题：每一拍能不能平分成两个</text>
  </g>

  <g transform="translate(52,50)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-24" y="0" text-anchor="end">单拍子 3/4</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="-10" width="110" height="16" rx="2"/>
      <rect x="120" y="-10" width="110" height="16" rx="2"/>
      <rect x="240" y="-10" width="110" height="16" rx="2"/>
    </g>
    <g stroke="#0B0B0C" stroke-width="1.2">
      <line x1="55" y1="-10" x2="55" y2="6"/><line x1="175" y1="-10" x2="175" y2="6"/><line x1="295" y1="-10" x2="295" y2="6"/>
    </g>
    <text x="366" y="2" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">每拍 = 两半</text>

    <g transform="translate(0,56)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-24" y="0" text-anchor="end">复拍子 6/8</text>
      </g>
      <g fill="#E8C547">
        <rect x="0" y="-10" width="110" height="16" rx="2"/>
        <rect x="120" y="-10" width="110" height="16" rx="2"/>
      </g>
      <g stroke="#0B0B0C" stroke-width="1.2">
        <line x1="36" y1="-10" x2="36" y2="6"/><line x1="73" y1="-10" x2="73" y2="6"/>
        <line x1="156" y1="-10" x2="156" y2="6"/><line x1="193" y1="-10" x2="193" y2="6"/>
      </g>
      <text x="246" y="2" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">每大拍 = 三份，共两大拍</text>
    </g>

    <g transform="translate(0,112)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-24" y="0" text-anchor="end">混合 5/4</text>
      </g>
      <g fill="#E07A3F">
        <rect x="0" y="-10" width="54" height="16" rx="2"/>
        <rect x="56" y="-10" width="54" height="16" rx="2"/>
        <rect x="112" y="-10" width="54" height="16" rx="2"/>
        <rect x="168" y="-10" width="36" height="16" rx="2"/>
        <rect x="206" y="-10" width="36" height="16" rx="2"/>
      </g>
      <text x="252" y="2" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">3+2：靠分组才成立（也可 2+3）</text>
    </g>

    <g transform="translate(0,152)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        3/4 与 6/8 的区别不是快慢，而是"每拍内部分成两份还是三份"
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        口诀：三是不是写在拍号里？是 → 复拍子（无需连音）；不是 → 单拍子（需写三连音）
      </text>
    </g>
  </g>
</svg>
```

## 听一听：两大拍与三拍

用 `rhythm` 对比 **6/8**（六个八分，按两个大拍感受）与 **3/4**（三个四分）。
请数"大重音隔多久回来"—— 6/8 是每三个小单位一组、共两组；3/4 是每拍一个重音、共三个。

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":96,"label":"3/4：三拍，每拍分二","label_en":"3/4: three beats, each split in two","hint":"点「播放」，数重音","hint_en":"Press play and count the accents"}
```

```audiolab
{"type":"rhythm","sig":"6/8","pattern":"e e e e e e","bpm":96,"label":"6/8：六个八分，按两大拍感受","label_en":"6/8: six eighths felt as two large beats","hint":"与 3/4 对比：分组方式完全不同","hint_en":"Against 3/4 — an entirely different grouping"}
```

## 常见误解

- **「6/8 就是加快的 3/4」** → 不是速度问题，是**内部等分方式**问题。两者是两类拍子。
- **「分子是 3 的倍数就是复拍子」** → 还需看分母：6/4 的写法常按两个大拍走，真正的判据是**听每拍内部分几份**。
- **「5/4 只是很少见」** → 它需要**指定分组**（3+2 或 2+3）才算完整；不同的分组是**不同的曲子**。
- **「复拍子里的三音是三连音」** → 不是（见 [[concept:tuplet|连音]]）。拍号里写了三，就不需要连音记号。
:::

::: en
One question is enough to sort the three types:

> **Can each beat be split into two?**

| Type | Beat divided into | Test | Examples |
|---|---|---|---|
| **simple** | **two** | numerator **not** a multiple of 3 (or denominator 4 / 2) | 2/4, 3/4, 4/4 |
| **compound** | **three** | numerator a **multiple of 3**, denominator ≥ 8 | 6/8, 9/8, 12/8 |
| **irregular** | — | numerator 5, 7 or similar | 5/4, 7/8 |

One easily missed detail: **6/4 is also compound** (6 = 3 × 2), so "denominator ≥ 8" is an **extra** condition
distinguishing patterns like 6/8 from 6/4, which is usually felt as two large beats. The reliable test remains
**listening**: does each beat divide in two or in three?

## What actually separates 6/8 from 3/4

The most practical distinction in this entry:

| | 3/4 | 6/8 |
|---|---|---|
| Beats | three | six (or two large beats) |
| Beat divided into | **two** | **three** |
| Impression | one accent per beat, three in all | pairs of beats, two groups in all |
| Typical genres | waltz, march | lullaby, barcarolle, many folk dances |

**The point: this is not a matter of speed but of how each beat divides.** Playing 3/4 faster does not make it
6/8, and playing 6/8 slower does not make it 3/4.

## Irregular metre: grouping decides the sound

5/4 and 7/8 are **incomplete** on their own — they must be given a grouping:

| Signature | Grouping | Impression |
|---|---|---|
| **5/4** | **3+2** | like "a bar of three plus a bar of two" (the Neapolitan dance pattern) |
| **5/4** | **2+3** | two then three, accent first, more square |
| **7/8** | **2+2+3** | the classic Balkan folk grouping |

**The same notes regrouped become a different piece**, because the accent cycle changes (see
[[concept:metric-accent|metric accent]]). It also explains why irregular metre "sounds modern": the unsettling
effect comes not from dissonance but from **being unable to count**.

## Its relation to tuplets

A boundary that is easily confused: **three notes inside a compound beat need no tuplet marking** (the
denominator already is 8 or 16), whereas three inside a simple beat require a triplet (see
[[concept:tuplet|tuplet]]).

> **A one-line test: is the three written into the time signature?**
> Yes → compound metre (no tuplet needed); no → simple metre (a triplet is required).

## Diagram: the inner structure of the three types

```svg
<svg viewBox="0 0 640 212" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One question decides it: can each beat be split into two?</text>
  </g>

  <g transform="translate(52,50)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-24" y="0" text-anchor="end">simple 3/4</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="-10" width="110" height="16" rx="2"/>
      <rect x="120" y="-10" width="110" height="16" rx="2"/>
      <rect x="240" y="-10" width="110" height="16" rx="2"/>
    </g>
    <g stroke="#0B0B0C" stroke-width="1.2">
      <line x1="55" y1="-10" x2="55" y2="6"/><line x1="175" y1="-10" x2="175" y2="6"/><line x1="295" y1="-10" x2="295" y2="6"/>
    </g>
    <text x="366" y="2" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">each beat = two halves</text>

    <g transform="translate(0,56)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-24" y="0" text-anchor="end">compound 6/8</text>
      </g>
      <g fill="#E8C547">
        <rect x="0" y="-10" width="110" height="16" rx="2"/>
        <rect x="120" y="-10" width="110" height="16" rx="2"/>
      </g>
      <g stroke="#0B0B0C" stroke-width="1.2">
        <line x1="36" y1="-10" x2="36" y2="6"/><line x1="73" y1="-10" x2="73" y2="6"/>
        <line x1="156" y1="-10" x2="156" y2="6"/><line x1="193" y1="-10" x2="193" y2="6"/>
      </g>
      <text x="246" y="2" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">each large beat = three parts, two in all</text>
    </g>

    <g transform="translate(0,112)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-24" y="0" text-anchor="end">irregular 5/4</text>
      </g>
      <g fill="#E07A3F">
        <rect x="0" y="-10" width="54" height="16" rx="2"/>
        <rect x="56" y="-10" width="54" height="16" rx="2"/>
        <rect x="112" y="-10" width="54" height="16" rx="2"/>
        <rect x="168" y="-10" width="36" height="16" rx="2"/>
        <rect x="206" y="-10" width="36" height="16" rx="2"/>
      </g>
      <text x="252" y="2" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">3+2: it only works once grouped (2+3 also common)</text>
    </g>

    <g transform="translate(0,152)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        3/4 and 6/8 differ not in speed but in whether each beat splits in two or in three
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        One-line test: is the three in the signature? Yes means compound, no means a triplet is needed
      </text>
    </g>
  </g>
</svg>
```

## Listen: two large beats versus three

Use `rhythm` to compare **6/8** (six eighths felt as two large beats) with **3/4** (three quarters). Count how
long it takes the main accent to return — in 6/8 it is one group of three out of two groups; in 3/4 it is every
beat, three times.

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":96,"label":"3/4：三拍，每拍分二","label_en":"3/4: three beats, each split in two","hint":"点「播放」，数重音","hint_en":"Press play and count the accents"}
```

```audiolab
{"type":"rhythm","sig":"6/8","pattern":"e e e e e e","bpm":96,"label":"6/8：六个八分，按两大拍感受","label_en":"6/8: six eighths felt as two large beats","hint":"与 3/4 对比：分组方式完全不同","hint_en":"Against 3/4 — an entirely different grouping"}
```

## Common misconceptions

- **"6/8 is just 3/4 played faster."** Not a matter of speed but of **how the beat divides**. They are two
  different classes of metre.
- **"Any numerator divisible by 3 is compound."** The denominator matters too: 6/4 is usually felt as two large
  beats, and the real test is **hearing how the beat divides**.
- **"5/4 is merely rare."** It is **incomplete without a grouping** (3+2 or 2+3), and different groupings are
  different pieces.
- **"The threes in compound metre are triplets."** They are not (see [[concept:tuplet|tuplet]]). The three is
  written into the signature, so no tuplet marking is needed.
:::
