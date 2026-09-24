---
id: triad
site: theo
cat: T4
title: 三和弦
title_en: Triad
summary: 两个三度叠成三个音——四种性质撑起整个和声学
summary_en: Two thirds stacked into three notes — four qualities that carry all of harmony
level: core
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [三和弦, triad]
order: 12
links:
  - "[[concept:chord]]"
  - "[[concept:major-triad]]"
  - "[[concept:minor-triad]]"
  - "[[concept:diminished-triad]]"
  - "[[concept:augmented-triad]]"
  - "[[concept:scale-harmony]]"
  - "[[concept:harmonic-function]]"
instances:
  - giantmidi-006222 | 琶音练习把三和弦逐音弹出：大三与小三的交替在同一组材料里就能对照 | Arpeggio exercises play triads one note at a time — major and minor alternate within one set of material
  - cyberhymnal-000695 | 管风琴圣咏：整首由三和弦柱式排列铺成，是最干净的三和弦样本 | An organ hymn in block chords throughout — the cleanest sample of triads
  - atepp-000318 | a 小调奏鸣曲：小调作品里小三和弦与减三和弦的运用可直接听辨 | A sonata in A minor — minor and diminished triads used where they can be heard directly
sources:
  - 三和弦由根音、三音、五音构成；四种性质由两个三度的宽窄组合决定，属和声学通则
  - 四种三和弦的出现频率与稳定性差异，为通行和声学表述
updated: 2026-09-23
---

::: zh
三和弦是**两个三度叠起来**的结果：根音 + 三音 + 五音，共三个音。

它的全部变化只来自一件事：**这两个三度各有多宽**。

| 下方三度 | 上方三度 | 得到 | 例（从 C 起） | 听感 |
|---|---|---|---|---|
| 大三度 | 小三度 | **大三和弦** | C–E–G | 明亮、稳定 |
| 小三度 | 大三度 | **小三和弦** | C–E♭–G | 暗淡、内敛 |
| 小三度 | 小三度 | **减三和弦** | C–E♭–G♭ | 不安、必须解决 |
| 大三度 | 大三度 | **增三和弦** | C–E–G♯ | 悬浮、无归属 |

**只有四种**，没有更多 —— 因为两个三度只有"大/小"两种宽度，组合数就是 2×2 = 4。

## 两个观察

**① 顺序决定性质。** 同样是大三度加小三度，谁在下谁在上，得到的和弦完全不同
（大三和弦 vs 小三和弦）。这与 [[concept:interval-inversion|音程转位]] 的道理一致：
上下关系本身就是结构信息。

**② 分布极不均匀。** 在大调音阶上叠三度得到的七个三和弦里，
大三和弦 3 个、小三和弦 3 个、减三和弦 1 个、增三和弦 **0 个**。
增三和弦在自然音阶里根本不出现 —— 这正是它听起来"不属于任何调"的原因。

## 三和弦与调性

三和弦是调性的最小承重单位：**主和弦决定调的中心，属和弦决定回到中心的引力**。
这层关系见 [[concept:harmonic-function|和声功能]]；
而"哪些三和弦能在某条音阶上出现"，见 [[concept:scale-harmony|音阶的和声含义]]。

## 图示：四种组合

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">两个三度的四种组合 —— 三和弦的全部可能</text>
  </g>

  <g transform="translate(36,52)">
    <g font-family="Georgia,serif" font-size="11.5" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C–E–G</text>
      <text x="160" y="0" fill="#5B7FA8">C–E♭–G</text>
      <text x="320" y="0" fill="#C0504A">C–E♭–G♭</text>
      <text x="480" y="0" fill="#E8C547">C–E–G♯</text>
    </g>
    <g stroke-width="1.3">
      <g stroke="#E07A3F">
        <line x1="0" y1="16" x2="0" y2="52"/><line x1="-4" y1="16" x2="4" y2="16"/><line x1="-4" y1="52" x2="4" y2="52"/>
        <line x1="14" y1="40" x2="14" y2="68"/><line x1="10" y1="40" x2="18" y2="40"/><line x1="10" y1="68" x2="18" y2="68"/>
      </g>
      <g stroke="#5B7FA8">
        <line x1="160" y1="16" x2="160" y2="40"/><line x1="156" y1="16" x2="164" y2="16"/><line x1="156" y1="40" x2="164" y2="40"/>
        <line x1="174" y1="40" x2="174" y2="76"/><line x1="170" y1="40" x2="178" y2="40"/><line x1="170" y1="76" x2="178" y2="76"/>
      </g>
      <g stroke="#C0504A">
        <line x1="320" y1="16" x2="320" y2="40"/><line x1="316" y1="16" x2="324" y2="16"/><line x1="316" y1="40" x2="324" y2="40"/>
        <line x1="334" y1="40" x2="334" y2="64"/><line x1="330" y1="40" x2="338" y2="40"/><line x1="330" y1="64" x2="338" y2="64"/>
      </g>
      <g stroke="#E8C547">
        <line x1="480" y1="16" x2="480" y2="52"/><line x1="476" y1="16" x2="484" y2="16"/><line x1="476" y1="52" x2="484" y2="52"/>
        <line x1="494" y1="52" x2="494" y2="88"/><line x1="490" y1="52" x2="498" y2="52"/><line x1="490" y1="88" x2="498" y2="88"/>
      </g>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="108" fill="#E07A3F">大三和弦：大 + 小</text>
      <text x="0" y="126" fill="#E07A3F">明亮稳定</text>
      <text x="160" y="108" fill="#5B7FA8">小三和弦：小 + 大</text>
      <text x="160" y="126" fill="#5B7FA8">暗淡内敛</text>
      <text x="320" y="108" fill="#C0504A">减三和弦：小 + 小</text>
      <text x="320" y="126" fill="#C0504A">不安、须解决</text>
      <text x="480" y="108" fill="#E8C547">增三和弦：大 + 大</text>
      <text x="480" y="126" fill="#E8C547">悬浮、无归属</text>
    </g>
  </g>
</svg>
```

## 听一听：四种三和弦

按顺序听：大 → 小 → 减 → 增。前两个是"能站住"的，后两个是"必须走"的。

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"大三和弦 C–E–G","label_en":"Major triad C–E–G","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"dim","inversion":0,"label":"减三和弦 C–E♭–G♭","label_en":"Diminished triad C–E♭–G♭","hint":"听它的不安：五音被压低了半个音","hint_en":"Hear the unease — the fifth is squeezed a semitone lower"}
```

```audiolab
{"type":"chord","root":"C4","quality":"aug","inversion":0,"label":"增三和弦 C–E–G♯","label_en":"Augmented triad C–E–G♯","hint":"听它的悬浮：两个大三度，找不到方向","hint_en":"Hear the suspension — two major thirds and no direction"}
```

## 常见误解

- **「三和弦有很多种」** → 只有四种，因为两个三度各只有大/小两种宽度。
- **「减三和弦和增三和弦只是理论上的」** → 减三和弦在调内大量出现（大调第 7 级、小调第 2 级）；增三和弦在自然音阶里不出现，但在半音化写作中很常见。
- **「把音重新排一下还是同一个和弦」** → 转位后根音不变，和弦名称也不变，但听感与功能会变（见 [[concept:chord-inversion|转位]]）。
- **「三和弦的音必须挨着」** → 排列可以很宽，只要仍是那三个音级（见 [[concept:chord-voicing|和弦排列]]）。
:::

::: en
A triad is the result of **stacking two thirds**: root, third and fifth — three notes.

All of its variation comes from one thing: **how wide each of those two thirds is.**

| Lower third | Upper third | Result | Example (from C) | Character |
|---|---|---|---|---|
| major | minor | **major triad** | C–E–G | bright, stable |
| minor | major | **minor triad** | C–E♭–G | dark, inward |
| minor | minor | **diminished triad** | C–E♭–G♭ | unstable, must resolve |
| major | major | **augmented triad** | C–E–G♯ | suspended, unanchored |

**There are only four**, and there can be no more — each third is either major or minor, so the combinations number
2 × 2 = 4.

## Two observations

**One: order decides quality.** A major third plus a minor third gives entirely different chords depending on
which comes first (major triad versus minor triad). The same logic as
[[concept:interval-inversion|interval inversion]]: the up-down relation is structural information.

**Two: the distribution is very uneven.** Of the seven triads stacked on a major scale: three are major, three
are minor, one is diminished, and **none is augmented**. The augmented triad never occurs in a diatonic scale,
which is exactly why it sounds like it belongs to no key.

## Triads and tonality

Triads are the smallest load-bearing unit of tonality: **the tonic chord fixes the key's centre, the dominant chord
fixes the pull back to it.** That relation is covered under [[concept:harmonic-function|harmonic function]], and
which triads a given scale can produce under [[concept:scale-harmony|scales as harmony]].

## Diagram: four combinations

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Four combinations of two thirds — every triad there is</text>
  </g>

  <g transform="translate(36,52)">
    <g font-family="Georgia,serif" font-size="11.5" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C–E–G</text>
      <text x="160" y="0" fill="#5B7FA8">C–E♭–G</text>
      <text x="320" y="0" fill="#C0504A">C–E♭–G♭</text>
      <text x="480" y="0" fill="#E8C547">C–E–G♯</text>
    </g>
    <g stroke-width="1.3">
      <g stroke="#E07A3F">
        <line x1="0" y1="16" x2="0" y2="52"/><line x1="-4" y1="16" x2="4" y2="16"/><line x1="-4" y1="52" x2="4" y2="52"/>
        <line x1="14" y1="40" x2="14" y2="68"/><line x1="10" y1="40" x2="18" y2="40"/><line x1="10" y1="68" x2="18" y2="68"/>
      </g>
      <g stroke="#5B7FA8">
        <line x1="160" y1="16" x2="160" y2="40"/><line x1="156" y1="16" x2="164" y2="16"/><line x1="156" y1="40" x2="164" y2="40"/>
        <line x1="174" y1="40" x2="174" y2="76"/><line x1="170" y1="40" x2="178" y2="40"/><line x1="170" y1="76" x2="178" y2="76"/>
      </g>
      <g stroke="#C0504A">
        <line x1="320" y1="16" x2="320" y2="40"/><line x1="316" y1="16" x2="324" y2="16"/><line x1="316" y1="40" x2="324" y2="40"/>
        <line x1="334" y1="40" x2="334" y2="64"/><line x1="330" y1="40" x2="338" y2="40"/><line x1="330" y1="64" x2="338" y2="64"/>
      </g>
      <g stroke="#E8C547">
        <line x1="480" y1="16" x2="480" y2="52"/><line x1="476" y1="16" x2="484" y2="16"/><line x1="476" y1="52" x2="484" y2="52"/>
        <line x1="494" y1="52" x2="494" y2="88"/><line x1="490" y1="52" x2="498" y2="52"/><line x1="490" y1="88" x2="498" y2="88"/>
      </g>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="108" fill="#E07A3F">major triad: M + m</text>
      <text x="0" y="126" fill="#E07A3F">bright, stable</text>
      <text x="160" y="108" fill="#5B7FA8">minor triad: m + M</text>
      <text x="160" y="126" fill="#5B7FA8">dark, inward</text>
      <text x="320" y="108" fill="#C0504A">diminished: m + m</text>
      <text x="320" y="126" fill="#C0504A">unstable, resolves</text>
      <text x="480" y="108" fill="#E8C547">augmented: M + M</text>
      <text x="480" y="126" fill="#E8C547">suspended, unanchored</text>
    </g>
  </g>
</svg>
```

## Listen: the four triads

In order: major, minor, diminished, augmented. The first two can stand; the last two must move.

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"大三和弦 C–E–G","label_en":"Major triad C–E–G","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"dim","inversion":0,"label":"减三和弦 C–E♭–G♭","label_en":"Diminished triad C–E♭–G♭","hint":"听它的不安：五音被压低了半个音","hint_en":"Hear the unease — the fifth is squeezed a semitone lower"}
```

```audiolab
{"type":"chord","root":"C4","quality":"aug","inversion":0,"label":"增三和弦 C–E–G♯","label_en":"Augmented triad C–E–G♯","hint":"听它的悬浮：两个大三度，找不到方向","hint_en":"Hear the suspension — two major thirds and no direction"}
```

## Common misconceptions

- **"There are many kinds of triad."** Only four, because each of the two thirds is either major or minor.
- **"Diminished and augmented triads are theoretical."** Diminished triads appear constantly in keys (degree 7 in major, degree 2 in minor); augmented triads never appear in a diatonic scale but are common in chromatic writing.
- **"Rearranging the notes keeps the same chord."** After inversion the root and the name stay the same, but the sound and function change (see [[concept:chord-inversion|inversion]]).
- **"A triad's notes must be adjacent."** The voicing can be wide open, so long as the three degree names remain (see [[concept:chord-voicing|voicing]]).
:::
