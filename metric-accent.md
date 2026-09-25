---
id: metric-accent
site: theo
cat: T7
title: 强弱规律
title_en: Metric Accent
summary: 重音按固定周期回来——音乐因此有了"心跳"，也才有被打破的可能
summary_en: The accent returns on a fixed cycle — that gives music a pulse, and makes it possible to disrupt
level: standard
tags: [乐理, 节奏, 基础]
tags_en: [theory, rhythm, basics]
alias: [强弱规律, 拍子重音, metric accent]
order: 14
links:
  - "[[concept:meter]]"
  - "[[concept:rhythm]]"
  - "[[concept:syncopation]]"
  - "[[concept:harmonic-rhythm]]"
  - "[[concept:tuplet]]"
instances:
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：舞曲节拍把"强—弱—弱"的循环钉得很牢，全曲因此有稳定的动力 | Liszt's transcription of Danse macabre — the dance metre pins the strong-weak-weak cycle firmly, giving the piece steady drive
  - cyberhymnal-000695 | 管风琴圣咏：乐句的起伏与四拍子的重音层次紧密配合，重音一旦落实，分句就清楚了 | An organ hymn — phrase shaping tracks the accent hierarchy of quadruple metre; once the accents settle, the phrasing is clear
  - giantmidi-006222 | 音阶与终止练习：每一拍都对应一个音，重音周期与音的更替完全重合，最容易数 | Scale and cadence exercises put one note to each beat, aligning accent cycle and note change exactly
sources:
  - 拍子重音的层次（如四拍子"强—弱—次强—弱"、三拍子"强—弱—弱"）属乐理通则
  - 重音周期是切分与重音移位得以成立的前提，为通行乐理表述
updated: 2026-09-25
---

::: zh
强弱规律说的是：**在小节内部，各拍的"重量"并不相同。**

| 拍号 | 重音层次 | 说明 |
|---|---|---|
| **2/4** | **强 · 弱** | 最简：两拍一循环 |
| **3/4** | **强 · 弱 · 弱** | 一个重音 + 两个轻拍 |
| **4/4** | **强 · 弱 · 次强 · 弱** | 第 3 拍是"次级重音"（这就是它与 2/4 重复两次的差别） |
| **6/8** | **强 · 弱弱 · 次强 · 弱弱** | 两个大拍，每拍内含三小拍 |

**4/4 里第 3 拍的那个"次强"很关键**：如果它和其余弱拍一样轻，四拍子听起来就只是 2/4 重复两遍。
这个层次正是 4/4 能独立成立的原因。

## 它为什么重要：周期 = 心跳

重音的作用不是"让某些音更响"，而是**建立周期**：

> **有周期，才有"期待"；有期待，才有"打破期待"。**

一切节奏上的张力手段都以它为前提：

| 手段 | 做法 | 依赖 |
|---|---|---|
| **切分** | 把重音移到弱拍位置（见 [[concept:syncopation|切分]]） | 必须先有"正拍"才谈得上"错位" |
| **重音移位** | 临时把某个弱拍弹得更响 | 同上 |
| **复合节奏** | 同时呈现两种重音周期（见 [[concept:polyrhythm|复节奏]]） | 需要两个清晰的周期 |
| **连音** | 把两拍塞进三拍的位置（见 [[concept:tuplet|连音]]） | 需要先有一个明确的拍 |

## 重音与和声的配合

一个非常实用的观察：**和声更换通常落在重音上**。

| 位置 | 常见的和声行为 |
|---|---|
| 小节第 1 拍 | 最常换和弦 |
| 第 3 拍（次强） | 次常换和弦 |
| 弱拍 | 较少换和弦；换了就有推进感 |

这就是 [[concept:harmonic-rhythm|和声节奏]] 与拍子的交叉点：
**重音是"换和弦的默认位置"**，所以故意在弱拍换和弦（和声层面的切分）会产生强烈的推进效果。

## 图示：重音的层次

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">柱子的高度 = 那一拍的重量；第 3 拍是"次强"，不是普通弱拍</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">4/4</text>
      <text x="-20" y="70" text-anchor="end">3/4</text>
      <text x="-20" y="140" text-anchor="end">6/8</text>
    </g>

    <g>
      <rect x="0" y="-44" width="52" height="44" rx="2" fill="#E07A3F"/>
      <rect x="110" y="-18" width="52" height="18" rx="2" fill="#5B7FA8" opacity=".55"/>
      <rect x="220" y="-32" width="52" height="32" rx="2" fill="#E8C547"/>
      <rect x="330" y="-18" width="52" height="18" rx="2" fill="#5B7FA8" opacity=".55"/>
      <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
        <text x="26" y="14" fill="#E07A3F">强</text><text x="136" y="14" fill="#6E6A64">弱</text>
        <text x="246" y="14" fill="#E8C547">次强</text><text x="356" y="14" fill="#6E6A64">弱</text>
      </g>
      <g stroke="#343439" stroke-width="1"><line x1="-8" y1="0" x2="400" y2="0"/></g>
    </g>

    <g transform="translate(0,70)">
      <rect x="0" y="-44" width="52" height="44" rx="2" fill="#E07A3F"/>
      <rect x="110" y="-18" width="52" height="18" rx="2" fill="#5B7FA8" opacity=".55"/>
      <rect x="220" y="-18" width="52" height="18" rx="2" fill="#5B7FA8" opacity=".55"/>
      <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
        <text x="26" y="14" fill="#E07A3F">强</text><text x="136" y="14" fill="#6E6A64">弱</text><text x="246" y="14" fill="#6E6A64">弱</text>
      </g>
      <g stroke="#343439" stroke-width="1"><line x1="-8" y1="0" x2="300" y2="0"/></g>
    </g>

    <g transform="translate(0,140)">
      <rect x="0" y="-44" width="52" height="44" rx="2" fill="#E07A3F"/>
      <rect x="80" y="-18" width="34" height="18" rx="2" fill="#5B7FA8" opacity=".4"/>
      <rect x="120" y="-18" width="34" height="18" rx="2" fill="#5B7FA8" opacity=".4"/>
      <rect x="180" y="-32" width="52" height="32" rx="2" fill="#E8C547"/>
      <rect x="260" y="-18" width="34" height="18" rx="2" fill="#5B7FA8" opacity=".4"/>
      <rect x="300" y="-18" width="34" height="18" rx="2" fill="#5B7FA8" opacity=".4"/>
      <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
        <text x="26" y="14" fill="#E07A3F">强</text><text x="206" y="14" fill="#E8C547">次强</text>
      </g>
      <g stroke="#343439" stroke-width="1"><line x1="-8" y1="0" x2="360" y2="0"/></g>
    </g>
    <text x="0" y="164" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      重音的作用是建立周期：有周期才有期待，有期待才有"打破期待"
    </text>
  </g>
</svg>
```

## 听一听：重音周期

用 `rhythm` 组件听 4/4 与 3/4 的均分。**请数"强拍隔几拍回来一次"** ——
那个数字就是这种节拍的"心跳周期"，也是后续一切切分与复节奏的参照点。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":92,"label":"4/4 的周期：每 4 拍一个强拍","label_en":"4/4 cycle: a strong beat every four","hint":"点「播放」，注意第 1 拍与第 3 拍的差别","hint_en":"Press play and notice how beat 1 differs from beat 3"}
```

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":92,"label":"3/4 的周期：每 3 拍一个强拍","label_en":"3/4 cycle: a strong beat every three","hint":"与 4/4 对比，周期更短、更“转”","hint_en":"Against 4/4 the cycle is shorter and turns more"}

```

## 常见误解

- **「强弱规律就是"第一拍重"」** → 4/4 里第 3 拍是**次强**，不是普通弱拍。没有这个层次，四拍子就退化成 2/4 重复两遍。
- **「重音必须弹得更响」** → 重音是**结构位置**，实现方式可以是力度、时值、和声更换或织体，不必只是"响一点"。
- **「打破重音就是不要重音」** → 恰恰相反：切分依赖重音的存在（见 [[concept:syncopation|切分]]）。没有正拍就没有错位。
- **「复合拍子的重音和单拍子一样」** → 6/8 的重音是**两层**的（两个大拍，每拍内含三个小拍），与 3/4 的单层重音不同。
:::

::: en
Metric accent says this: **within a bar, the beats do not all weigh the same.**

| Signature | Accent hierarchy | Note |
|---|---|---|
| **2/4** | **strong · weak** | simplest: a two-beat cycle |
| **3/4** | **strong · weak · weak** | one accent, two light beats |
| **4/4** | **strong · weak · medium · weak** | beat 3 is a **secondary accent** — which is what separates it from 2/4 twice over |
| **6/8** | **strong · weak-weak · medium · weak-weak** | two large beats, each containing three small ones |

**That secondary accent on beat 3 of 4/4 matters**: make it as light as the other weak beats and quadruple metre
sounds like 2/4 repeated. The hierarchy is exactly why 4/4 can stand on its own.

## Why it matters: a cycle is a pulse

The accent's job is not "making some notes louder" but **establishing a cycle**:

> **A cycle creates expectation; expectation creates the possibility of disrupting it.**

Every rhythmic tension device presupposes it:

| Device | Method | Depends on |
|---|---|---|
| **syncopation** | displacing the accent onto a weak position (see [[concept:syncopation|syncopation]]) | there must be a "right" beat to be displaced from |
| **accent shift** | temporarily playing a weak beat louder | same |
| **polyrhythm** | presenting two accent cycles at once (see [[concept:polyrhythm|polyrhythm]]) | two clear cycles are needed |
| **tuplets** | fitting two beats into the space of three (see [[concept:tuplet|tuplet]]) | an established beat is required |

## Accent and harmony work together

A very practical observation: **chords usually change on the accent.**

| Position | Typical harmonic behaviour |
|---|---|
| beat 1 | chords change here most often |
| beat 3 (medium) | second most often |
| weak beats | rarer; when it happens you get a push |

This is where [[concept:harmonic-rhythm|harmonic rhythm]] meets metre: **the accent is the default place to change
chord**, so changing on a weak beat (harmonic syncopation) produces a strong propulsive effect.

## Diagram: the accent hierarchy

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Bar height = that beat's weight; beat 3 is a secondary accent, not an ordinary weak beat</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">4/4</text>
      <text x="-20" y="70" text-anchor="end">3/4</text>
      <text x="-20" y="140" text-anchor="end">6/8</text>
    </g>

    <g>
      <rect x="0" y="-44" width="52" height="44" rx="2" fill="#E07A3F"/>
      <rect x="110" y="-18" width="52" height="18" rx="2" fill="#5B7FA8" opacity=".55"/>
      <rect x="220" y="-32" width="52" height="32" rx="2" fill="#E8C547"/>
      <rect x="330" y="-18" width="52" height="18" rx="2" fill="#5B7FA8" opacity=".55"/>
      <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
        <text x="26" y="14" fill="#E07A3F">strong</text><text x="136" y="14" fill="#6E6A64">weak</text>
        <text x="246" y="14" fill="#E8C547">medium</text><text x="356" y="14" fill="#6E6A64">weak</text>
      </g>
      <g stroke="#343439" stroke-width="1"><line x1="-8" y1="0" x2="400" y2="0"/></g>
    </g>

    <g transform="translate(0,70)">
      <rect x="0" y="-44" width="52" height="44" rx="2" fill="#E07A3F"/>
      <rect x="110" y="-18" width="52" height="18" rx="2" fill="#5B7FA8" opacity=".55"/>
      <rect x="220" y="-18" width="52" height="18" rx="2" fill="#5B7FA8" opacity=".55"/>
      <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
        <text x="26" y="14" fill="#E07A3F">strong</text><text x="136" y="14" fill="#6E6A64">weak</text><text x="246" y="14" fill="#6E6A64">weak</text>
      </g>
      <g stroke="#343439" stroke-width="1"><line x1="-8" y1="0" x2="300" y2="0"/></g>
    </g>

    <g transform="translate(0,140)">
      <rect x="0" y="-44" width="52" height="44" rx="2" fill="#E07A3F"/>
      <rect x="80" y="-18" width="34" height="18" rx="2" fill="#5B7FA8" opacity=".4"/>
      <rect x="120" y="-18" width="34" height="18" rx="2" fill="#5B7FA8" opacity=".4"/>
      <rect x="180" y="-32" width="52" height="32" rx="2" fill="#E8C547"/>
      <rect x="260" y="-18" width="34" height="18" rx="2" fill="#5B7FA8" opacity=".4"/>
      <rect x="300" y="-18" width="34" height="18" rx="2" fill="#5B7FA8" opacity=".4"/>
      <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
        <text x="26" y="14" fill="#E07A3F">strong</text><text x="206" y="14" fill="#E8C547">medium</text>
      </g>
      <g stroke="#343439" stroke-width="1"><line x1="-8" y1="0" x2="360" y2="0"/></g>
    </g>
    <text x="0" y="164" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      The accent builds a cycle: a cycle creates expectation, expectation makes disruption possible
    </text>
  </g>
</svg>
```

## Listen: the accent cycle

Use `rhythm` on even 4/4 and 3/4. **Count how many beats pass between strong accents** — that number is the pulse
of the metre, and the reference point for every syncopation and polyrhythm that follows.

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":92,"label":"4/4 的周期：每 4 拍一个强拍","label_en":"4/4 cycle: a strong beat every four","hint":"点「播放」，注意第 1 拍与第 3 拍的差别","hint_en":"Press play and notice how beat 1 differs from beat 3"}
```

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":92,"label":"3/4 的周期：每 3 拍一个强拍","label_en":"3/4 cycle: a strong beat every three","hint":"与 4/4 对比，周期更短","hint_en":"Against 4/4 the cycle is shorter and turns more"}
```

## Common misconceptions

- **"Metric accent just means the first beat is loud."** In 4/4 beat 3 is a **secondary accent**, not an ordinary
  weak beat. Without that layer quadruple metre collapses into 2/4 twice.
- **"An accent must be played louder."** The accent is a **structural position**; it may be realised by dynamics,
  duration, harmonic change or texture — not by volume alone.
- **"Breaking the accent means doing without it."** The opposite: syncopation depends on the accent existing (see
  [[concept:syncopation|syncopation]]). No right beat, no displacement.
- **"Compound metre accents work like simple metre."** 6/8 accents on **two** levels (two large beats each holding
  three small ones), unlike the single level of 3/4.
:::
