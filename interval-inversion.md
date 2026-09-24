---
id: interval-inversion
site: theo
cat: T2
title: 音程转位
title_en: Interval Inversion
summary: 把低音抬高八度，度数相加为九、性质相反
summary_en: Raise the lower note an octave and the degrees add to nine while the quality flips
level: standard
tags: [乐理, 音程, 基础]
tags_en: [theory, interval, basics]
alias: [转位, inversion]
order: 24
links:
  - "[[concept:interval]]"
  - "[[concept:octave]]"
  - "[[concept:interval-number]]"
  - "[[concept:perfect-interval]]"
  - "[[concept:counterpoint]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：同一条主题不断被上下颠倒地模仿，是旋律转位最直观的听感材料 | Bach's first two-part invention — one subject imitated upside down again and again, the clearest listening material for melodic inversion
  - mutopia-000050 | 《绿袖子》加固定低音的变奏：高音旋律与低音线条互成上下镜像，可听出同一素材的两个方向 | Greensleeves to a Ground — melody above and ground below mirror each other, the same material in two directions
  - mutopia-000287 | 巴赫第八首二部创意曲：两声部一上一下交替陈述，单音程转位后性质的变化在其中反复出现 | Bach's eighth two-part invention — two voices alternate high and low, so inverted qualities keep recurring
sources:
  - 转位口诀（度数相加为九、大↔小、增↔减、纯仍为纯），为通行乐理表述
  - 旋律转位与和声转位两个义项的区分，属乐理与对位写作常识
updated: 2026-09-23
---

::: zh
转位有两种含义，先分清，否则会一直混：

- **音程转位**：把下方的音移高一个八度（或把上方的音移低），原来的距离倒过来看。
- **旋律转位**：把一条旋律上下颠倒，向上的音程变成向下。
- **和声转位**：改变和弦的低音，属于 [[concept:chord-inversion|和弦转位]] 的话题。

本站这一条只讲第一种。

## 一条口诀，省掉一半背诵

> **度数相加等于 9；大↔小、增↔减互换；纯音程转位后仍是纯。**

| 原音程 | 转位后 | 验证 |
|---|---|---|
| 大三度（3） | 小六度（6） | 3 + 6 = 9 ✓ |
| 纯五度（5） | 纯四度（4） | 5 + 4 = 9 ✓ |
| 增四度（4） | 减五度（5） | 4 + 5 = 9 ✓ |
| 小二度（2） | 大七度（7） | 2 + 7 = 9 ✓ |

只要把五度以内记熟，六度以上用减法推：想不出"小六度"，就先想它的大三度转位。

## 为什么"纯"是唯一不翻转的

因为纯音程的名字里没有"大"和"小"可翻转。它只能变成增或减，
而一个纯音程转位之后**仍然是纯的**（纯四度 ↔ 纯五度，纯八度自己转成自己）。
这条不对称恰好说明：大小之分来自音数的细微差别，而纯音程属于另一套判断标准。

## 图示：相加为 9

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">低音抬高八度后，原来的上方音变成了新的下方音</text>
  </g>

  <g transform="translate(48,56)">
    <g font-family="Georgia,serif" font-size="13" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C4</text><text x="0" y="-70">E5</text>
      <text x="220" y="0">E4</text><text x="220" y="-70">C5</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.3">
      <line x1="0" y1="-58" x2="0" y2="-12"/>
      <line x1="-4" y1="-12" x2="4" y2="-12"/><line x1="-4" y1="-58" x2="4" y2="-58"/>
    </g>
    <text x="10" y="-30" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">大三度 → 转位为小六度</text>
    <g stroke="#E07A3F" stroke-width="1.3">
      <line x1="220" y1="-58" x2="220" y2="-12"/>
      <line x1="216" y1="-12" x2="224" y2="-12"/><line x1="216" y1="-58" x2="224" y2="-58"/>
    </g>
    <text x="230" y="-30" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">3 + 6 = 9</text>
    <g stroke="#343439" stroke-dasharray="3 4">
      <line x1="-14" y1="0" x2="234" y2="0"/>
      <line x1="0" y1="-8" x2="220" y2="-8" stroke="#6E6A64"/>
    </g>
    <text x="0" y="112" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      转位把音程的方向翻转：原本向上的三度，变成向下的六度
    </text>
  </g>
</svg>
```

## 听一听：同一个音程的两个方向

先听大三度（向上），再听它转位后的小六度（向上但起点换成了原来的高音）——
两组音高其实是同一对，只是谁在下面变了。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度 C–E","label_en":"Major third C–E","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把两个音换成 E4–C5，就是它转位后的小六度：同一对音名的另一种排列。","hint2_en":"Switch to E4–C5 for the inverted minor sixth — the same two names, rearranged."}
```

## 常见误解

- **「转位就是把音序前后颠倒」** → 那是旋律转位的一种。音程转位只把其中一个音移八度，不改任何音的先后。
- **「大音程转位变大音程」** → 大变小、小变大。只有纯音程转位后还是纯的。
- **「度数相加为 8」** → 是 9。因为首尾都被数了两次（C–E 的三度，与 E–C 的六度，合计覆盖一个八度加一个音级名）。
- **「增四度转位是减四度」** → 增四度的转位是减五度。转位后的度数由 9 减去原度数决定，性质按增减互换。
:::

::: en
Inversion carries more than one meaning, so separate them first:

- **Interval inversion**: move the lower note up an octave (or the upper note down) and see the distance reversed.
- **Melodic inversion**: turn a melody upside down, so rising intervals become falling ones.
- **Chord inversion**: change which chord tone is in the bass — that belongs to [[concept:chord-inversion|chord inversion]].

This entry covers the first only.

## One rule, half the memorising

> **Degrees add up to 9; major ↔ minor; augmented ↔ diminished; perfect stays perfect.**

| Original | Inverted | Check |
|---|---|---|
| major third (3) | minor sixth (6) | 3 + 6 = 9 ✓ |
| perfect fifth (5) | perfect fourth (4) | 5 + 4 = 9 ✓ |
| augmented fourth (4) | diminished fifth (5) | 4 + 5 = 9 ✓ |
| minor second (2) | major seventh (7) | 2 + 7 = 9 ✓ |

Master everything up to a fifth and derive the rest by subtraction: if a minor sixth will not come to mind,
recall its major-third inversion.

## Why "perfect" is the one that does not flip

Because the perfect family has no major or minor label to flip. A perfect interval can only become augmented or
diminished — and a perfect interval **stays perfect** when inverted (perfect fourth ↔ perfect fifth; the octave
inverts into itself). That asymmetry is a useful clue: major and minor come from small differences in size,
while perfect intervals are judged by a different standard.

## Diagram: they add up to 9

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Raise the lower note an octave and the former upper note becomes the new lower one</text>
  </g>

  <g transform="translate(48,56)">
    <g font-family="Georgia,serif" font-size="13" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C4</text><text x="0" y="-70">E5</text>
      <text x="220" y="0">E4</text><text x="220" y="-70">C5</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.3">
      <line x1="0" y1="-58" x2="0" y2="-12"/>
      <line x1="-4" y1="-12" x2="4" y2="-12"/><line x1="-4" y1="-58" x2="4" y2="-58"/>
    </g>
    <text x="10" y="-30" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">major third → inverts to a minor sixth</text>
    <g stroke="#E07A3F" stroke-width="1.3">
      <line x1="220" y1="-58" x2="220" y2="-12"/>
      <line x1="216" y1="-12" x2="224" y2="-12"/><line x1="216" y1="-58" x2="224" y2="-58"/>
    </g>
    <text x="230" y="-30" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">3 + 6 = 9</text>
    <g stroke="#343439" stroke-dasharray="3 4">
      <line x1="-14" y1="0" x2="234" y2="0"/>
      <line x1="0" y1="-8" x2="220" y2="-8" stroke="#6E6A64"/>
    </g>
    <text x="0" y="112" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Inversion reverses the direction: an upward third becomes a downward sixth
    </text>
  </g>
</svg>
```

## Listen: one interval, two directions

Hear the major third, then its inverted minor sixth — the very same pair of pitches, with a different note
underneath.

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度 C–E","label_en":"Major third C–E","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把两个音换成 E4–C5，就是它转位后的小六度：同一对音名的另一种排列。","hint2_en":"Switch to E4–C5 for the inverted minor sixth — the same two names, rearranged."}
```

## Common misconceptions

- **"Inversion means reversing the order of notes."** That is one kind of melodic inversion. Interval inversion moves one note by an octave and changes no order.
- **"A major interval inverts to a major interval."** Major becomes minor and minor becomes major. Only perfect intervals stay perfect.
- **"The degrees add up to 8."** They add to 9, because both endpoints are counted in each direction.
- **"An augmented fourth inverts to a diminished fourth."** It inverts to a diminished fifth: take 9 minus the original degree, then swap augmented for diminished.
:::
