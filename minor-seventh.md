---
id: minor-seventh
site: theo
cat: T4
title: 小七和弦
title_en: Minor Seventh
summary: 小三和弦加小七度——七和弦里最温和、最常用的一个
summary_en: A minor triad plus a minor seventh — the gentlest and most widely used seventh chord
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [小七和弦, minor seventh, min7, m7]
order: 30
links:
  - "[[concept:seventh-chord]]"
  - "[[concept:minor-triad]]"
  - "[[concept:dominant-seventh]]"
  - "[[concept:major-seventh]]"
  - "[[concept:half-diminished-seventh]]"
  - "[[concept:scale-harmony]]"
instances:
  - giantmidi-006222 | 琶音练习可弹出小七和弦琶音，用于与属七、大七对照同一个七音的不同高度 | Scale exercises can sound a minor-seventh arpeggio, comparing the same seventh degree at different heights
  - atepp-000318 | a 小调奏鸣曲：小调第 4 级上的小七和弦常作下属功能，可听它柔和的推进 | A sonata in A minor — the minor seventh on degree 4 acts as a subdominant, its push soft rather than sharp
  - mutopia-000049 | 《绿袖子》加固定低音：小调语境下小七和弦不断出现，是它的自然土壤 | Greensleeves to a Ground — minor-seventh chords recur throughout, their natural habitat
sources:
  - 小七和弦 = 小三和弦 + 小七度，属和声学通则
  - 小七和弦在大调 ii / iii / vi 级与小调 i / iv / v 级上自然产生，为通行和声学表述
updated: 2026-09-24
---

::: zh
小七和弦是**小三和弦 + 小七度**：

> C 小七 = C–E♭–G–B♭

它是四种常用七和弦里**最温和**的一个 —— 因为它把两个"偏暗"的成分（小三度、小七度）放在一起，
反而没有尖锐的冲突音。

## 它出现得最多

按 [[concept:scale-harmony|音阶的和声含义]] 叠三度：

| 音阶 | 自然产生小七和弦的级数 |
|---|---|
| **大调** | 第 2、3、6 级（ii7 / iii7 / vi7）—— 三个 |
| **自然小调** | 第 1、4、5 级（i7 / iv7 / v7）—— 三个 |

对比一下另外两条：

- [[concept:major-seventh|大七和弦]]：大调只有 **2** 个（第 1、4 级）
- [[concept:half-diminished-seventh|半减七]]：大调只有 **1** 个（第 7 级）

**小七和弦是数量最多的一种**，因此在实践中出现频率最高 ——
在爵士里，ii7–V7–Imaj7 是最基本的进行，其中两个和弦都是七和弦。

## 七音的角色

| 和弦 | 七音 | 处理方式 |
|---|---|---|
| 属七 | 小七度 | 向下解决（**是**导音） |
| **小七** | 小七度 | 通常**保留**或平滑移动，不强制解决 |

注意第二行：**同样是小七度，在属七和弦里必须解决，在小七和弦里却可以停留**。
差别来自根基：属七带三全音（推），小七不含三全音（稳）。这说明**七音的作用由整个和弦决定，不由音程本身决定**。

## 图示：三条七和弦的"稳—推"光谱

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">从"可以停留"到"必须走"：三条常用七和弦的位置</text>
  </g>

  <g transform="translate(44,60)">
    <line x1="0" y1="0" x2="520" y2="0" stroke="#343439" stroke-width="1.2"/>
    <g stroke="#343439"><line x1="0" y1="-6" x2="0" y2="6"/><line x1="520" y1="-6" x2="520" y2="6"/></g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="24">可以停留</text><text x="520" y="24" text-anchor="end">必须解决</text>
    </g>
    <g fill="#5B7FA8"><circle cx="60" cy="0" r="6"/></g>
    <text x="60" y="-16" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8" text-anchor="middle">小七</text>
    <text x="60" y="46" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">无三全音</text>
    <g fill="#E8C547"><circle cx="270" cy="0" r="6"/></g>
    <text x="270" y="-16" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547" text-anchor="middle">大七</text>
    <text x="270" y="46" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">悬置（几乎到达）</text>
    <g fill="#E07A3F"><circle cx="460" cy="0" r="6"/></g>
    <text x="460" y="-16" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F" text-anchor="middle">属七</text>
    <text x="460" y="46" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">含三全音</text>
    <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      竖轴不是"好坏"，而是"这个和弦是否要求你继续往下走"
    </text>
  </g>
</svg>
```

## 听一听：小七和弦

听它与属七的差别 —— 同样是小七度，少了三全音之后，推力明显减弱。

```audiolab
{"type":"chord","root":"C4","quality":"min7","inversion":0,"label":"小七和弦（C–E♭–G–B♭）","label_en":"Minor seventh (C–E♭–G–B♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「小七和弦带"小"所以是不协和的」** → 它恰恰是最温和的一条，因为不含三全音。
- **「小七度都要解决」** → 在属七里要，在小七里通常不用。七音的作用取决于整个和弦的构造。
- **「小七和弦是从小三和弦推导的」** → 更准确地说，它和另外几种七和弦一样，是**在音阶上叠三度**的自然产物。
- **「和弦越复杂越不稳定」** → 不稳定来自**具体音程**（尤其三全音），不来自音的数量。九和弦、十三和弦都可能很稳定。
:::

::: en
A minor seventh is **a minor triad plus a minor seventh**:

> C minor seventh = C–E♭–G–B♭

It is the **gentlest** of the four common seventh chords — because it pairs two already-dark elements (a minor
third and a minor seventh) and contains no sharp internal clash.

## It is the most common one

Stack thirds by [[concept:scale-harmony|scale degree]]:

| Scale | Degrees that produce a minor seventh naturally |
|---|---|
| **major** | degrees 2, 3 and 6 (ii7, iii7, vi7) — three of them |
| **natural minor** | degrees 1, 4 and 5 (i7, iv7, v7) — three of them |

Compare the neighbours:

- [[concept:major-seventh|major seventh]]: only **2** in a major scale (degrees 1 and 4)
- [[concept:half-diminished-seventh|half-diminished]]: only **1** (degree 7)

**The minor seventh is the most plentiful**, and therefore the most frequent in practice. In jazz the basic
progression is ii7–V7–Imaj7, where two of the three chords are seventh chords.

## What the seventh does

| Chord | Seventh | Treatment |
|---|---|---|
| dominant seventh | minor seventh | resolves downward (it **is** a leading tone) |
| **minor seventh** | minor seventh | usually held or moved smoothly, no forced resolution |

Note the second row: **the same minor seventh must resolve in a dominant chord and may simply stay in a minor
one.** The difference comes from the foundation — a dominant seventh contains a tritone (push), a minor seventh
does not (rest). So **the seventh's role is decided by the whole chord, not by the interval alone.**

## Diagram: the rest-to-push spectrum

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">From "can rest" to "must move": where the common seventh chords sit</text>
  </g>

  <g transform="translate(44,60)">
    <line x1="0" y1="0" x2="520" y2="0" stroke="#343439" stroke-width="1.2"/>
    <g stroke="#343439"><line x1="0" y1="-6" x2="0" y2="6"/><line x1="520" y1="-6" x2="520" y2="6"/></g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="24">can rest</text><text x="520" y="24" text-anchor="end">must resolve</text>
    </g>
    <g fill="#5B7FA8"><circle cx="60" cy="0" r="6"/></g>
    <text x="60" y="-16" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8" text-anchor="middle">minor 7th</text>
    <text x="60" y="46" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">no tritone</text>
    <g fill="#E8C547"><circle cx="270" cy="0" r="6"/></g>
    <text x="270" y="-16" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547" text-anchor="middle">major 7th</text>
    <text x="270" y="46" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">suspended, nearly arrived</text>
    <g fill="#E07A3F"><circle cx="460" cy="0" r="6"/></g>
    <text x="460" y="-16" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F" text-anchor="middle">dominant 7th</text>
    <text x="460" y="46" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">contains a tritone</text>
    <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The axis is not good versus bad, but whether the chord asks you to keep going
    </text>
  </g>
</svg>
```

## Listen: the minor seventh

Hear how it differs from the dominant seventh — the same minor seventh, but without a tritone the push is
visibly weaker.

```audiolab
{"type":"chord","root":"C4","quality":"min7","inversion":0,"label":"小七和弦（C–E♭–G–B♭）","label_en":"Minor seventh (C–E♭–G–B♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"The word minor makes it dissonant."** It is the gentlest of the four, precisely because it has no tritone.
- **"Every minor seventh must resolve."** It must in a dominant seventh, usually not in a minor seventh. The seventh's role depends on the whole chord.
- **"A minor seventh is derived from a minor triad."** More accurately, it — like the others — arises from **stacking thirds on a scale**.
- **"More complex chords are more unstable."** Instability comes from **specific intervals** (especially the tritone), not from the number of notes. Ninths and thirteenths can be perfectly stable.
:::
