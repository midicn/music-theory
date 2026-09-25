---
id: minor-triad
site: theo
cat: T4
title: 小三和弦
title_en: Minor Triad
summary: 小三度加大三度——把大三和弦的三音压低半个音
summary_en: A minor third under a major third — a major triad with its third dropped a semitone
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [小三和弦, minor triad]
order: 16
links:
  - "[[concept:triad]]"
  - "[[concept:major-triad]]"
  - "[[concept:minor-scale]]"
  - "[[concept:harmonic-function]]"
instances:
  - giantmidi-006222 | 琶音练习里的小三和弦琶音，可与大三和弦琶音直接前后对照 | Minor-triad arpeggios in scale exercises, directly comparable with the major-triad ones
  - mutopia-000049 | 《绿袖子》以小音程与级进铺陈，其和声底色正是小三和弦 | Greensleeves moves in small intervals and steps, and its harmonic base is the minor triad
  - atepp-000318 | a 小调奏鸣曲：小调作品的主和弦就是小三和弦，全曲的中心由此确定 | A sonata in A minor — its tonic is a minor triad, and the whole piece is centred on it
sources:
  - 小三和弦 = 小三度 + 大三度，根音到五音仍为纯五度，属和声学通则
  - 小三和弦与大三和弦共用同一骨架、仅三音高度不同，为通行和声学表述
updated: 2026-09-24
---

::: zh
小三和弦是 [[concept:major-triad|大三和弦]] 的镜像：**小三度在下，大三度在上**。

> C–E♭–G：C 到 E♭ 是小三度（3 个半音），E♭ 到 G 是大三度（4 个半音）

与大三和弦相比，**根音与五音完全一样**（还是纯五度），**只有三音低了半个音**。
但它听起来完全不同：稳定感下降，色彩转暗，并且**多了一层"想回到大调"的暗示** ——
因为三音升高半音就回到大三和弦，这个"一步之遥"是它张力的来源。

## 它在哪里出现

| 场合 | 位置 |
|---|---|
| **大调音阶** | 第 2、3、6 级（ii / iii / vi）—— 全是小三和弦 |
| **自然小调** | 第 1、4、5 级（i / iv / v）—— 主和弦本身就是小三和弦 |
| **小调写作** | 第 1 级常作为全曲中心，第 4 级作下属 |

注意最上面一行：**大调里也有三个小三和弦**，而且数量与大三和弦相同（各 3 个）。
所以"大调=全是大三和弦"是错的 —— 大三、小三各三个，加一个减三和弦，
这就是大调音阶上七个三和弦的全部构成（见 [[concept:scale-harmony|音阶的和声含义]]）。

## 与小调的关系

自然小调的第 7 级没有升高，所以第 5 级（属和弦）是**小三和弦**，
"属 → 主"的推进力因此偏弱。这也是小调作品几乎都会把第 7 级升上去的原因
（见 [[concept:harmonic-minor|和声小调]]）——**目的就是让属和弦变回大三和弦**。

## 图示：镜像关系

```svg
<svg viewBox="0 0 640 180" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">两根三度上下互换，性质就从大变成小</text>
  </g>

  <g transform="translate(48,56)">
    <g font-family="Georgia,serif" font-size="13" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="90" y="0" fill="#E07A3F">E</text><text x="180" y="0" fill="#E07A3F">G</text>
      <text x="320" y="0" fill="#5B7FA8">C</text><text x="410" y="0" fill="#5B7FA8">E♭</text><text x="500" y="0" fill="#5B7FA8">G</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="14" x2="90" y2="14"/><line x1="0" y1="10" x2="0" y2="18"/><line x1="90" y1="10" x2="90" y2="18"/>
      <line x1="90" y1="14" x2="180" y2="14"/><line x1="180" y1="10" x2="180" y2="18"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="320" y1="14" x2="410" y2="14"/><line x1="320" y1="10" x2="320" y2="18"/><line x1="410" y1="10" x2="410" y2="18"/>
      <line x1="410" y1="14" x2="500" y2="14"/><line x1="500" y1="10" x2="500" y2="18"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="42" fill="#E07A3F">大三度 + 小三度 = 大三和弦</text>
      <text x="320" y="42" fill="#5B7FA8">小三度 + 大三度 = 小三和弦</text>
      <text x="0" y="68" fill="#6E6A64">共同点：根音到五音都是纯五度（7 半音）—— 骨架相同</text>
      <text x="0" y="90" fill="#6E6A64">不同点：三音差半个音 —— 明暗与稳定性由此分开</text>
    </g>
  </g>
</svg>
```

## 听一听：小三和弦

先听整体（暗、内敛），再点「分解」听三音比大三和弦低半个音。

```audiolab
{"type":"chord","root":"C4","quality":"min","inversion":0,"label":"c 小三和弦（C–E♭–G）","label_en":"C minor triad (C–E♭–G)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「小三和弦是"悲伤"的和弦」** → 它提供的是**较暗的色彩与较弱的稳定感**，情绪由速度、节奏、和声共同决定。
- **「大调里没有小三和弦」** → 有三个（ii、iii、vi），与大三和弦数量相同。
- **「小三和弦和大三和弦的五音不同」** → 五音一样，两者都是纯五度。差别只在三音。
- **「小调的主和弦是减三和弦」** → 自然小调的主和弦是小三和弦；减三和弦出现在小调的第 2 级。
:::

::: en
A minor triad is the mirror image of a [[concept:major-triad|major triad]]: **a minor third below, a major third above.**

> C–E♭–G: C to E♭ is a minor third (3 semitones), E♭ to G is a major third (4)

Compared with a major triad, **the root and fifth are identical** (still a perfect fifth) and **only the third is
a semitone lower**. Yet it sounds completely different: less stable, darker, and carrying **an implication of
returning to major** — raise the third a semitone and you are back. That one-step-away quality is where its
tension lives.

## Where it appears

| Context | Positions |
|---|---|
| **major scale** | degrees 2, 3 and 6 (ii / iii / vi) are all minor triads |
| **natural minor** | degrees 1, 4 and 5 (i / iv / v) — the tonic itself is a minor triad |
| **minor-key writing** | degree 1 as the centre of the piece, degree 4 as subdominant |

Note the first row: **a major scale also contains three minor triads**, the very same number as its major triads.
So "major key means major chords" is wrong — three major, three minor and one diminished triad make up the
complete set of seven, as covered under [[concept:scale-harmony|scales as harmony]].

## Its relation to minor keys

In natural minor the seventh degree is unraised, so the chord on degree 5 (the dominant) is a **minor triad**
and its push to the tonic is weak. That is precisely why minor-key music almost always raises the seventh
(see [[concept:harmonic-minor|harmonic minor]]) — **the point is to turn the dominant back into a major triad.**

## Diagram: the mirror relation

```svg
<svg viewBox="0 0 640 180" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Swap the two thirds and the quality flips from major to minor</text>
  </g>

  <g transform="translate(48,56)">
    <g font-family="Georgia,serif" font-size="13" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="90" y="0" fill="#E07A3F">E</text><text x="180" y="0" fill="#E07A3F">G</text>
      <text x="320" y="0" fill="#5B7FA8">C</text><text x="410" y="0" fill="#5B7FA8">E♭</text><text x="500" y="0" fill="#5B7FA8">G</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="14" x2="90" y2="14"/><line x1="0" y1="10" x2="0" y2="18"/><line x1="90" y1="10" x2="90" y2="18"/>
      <line x1="90" y1="14" x2="180" y2="14"/><line x1="180" y1="10" x2="180" y2="18"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="320" y1="14" x2="410" y2="14"/><line x1="320" y1="10" x2="320" y2="18"/><line x1="410" y1="10" x2="410" y2="18"/>
      <line x1="410" y1="14" x2="500" y2="14"/><line x1="500" y1="10" x2="500" y2="18"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="42" fill="#E07A3F">major third + minor third = major triad</text>
      <text x="320" y="42" fill="#5B7FA8">minor third + major third = minor triad</text>
      <text x="0" y="68" fill="#6E6A64">Shared: root to fifth is a perfect fifth (7 semitones) — the same frame</text>
      <text x="0" y="90" fill="#6E6A64">Different: the third sits a semitone lower — and that splits dark from bright</text>
    </g>
  </g>
</svg>
```

## Listen: the minor triad

Hear it as a block first (dark, inward), then press Arpeggio to hear the third sitting a semitone below the
major version.

```audiolab
{"type":"chord","root":"C4","quality":"min","inversion":0,"label":"c 小三和弦（C–E♭–G）","label_en":"C minor triad (C–E♭–G)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"A minor triad is a sad chord."** It supplies **a darker colour and less stability**; mood also depends on tempo, rhythm and harmony.
- **"Major keys contain no minor triads."** They contain three (ii, iii, vi) — the same number as major triads.
- **"Minor and major triads have different fifths."** The fifth is identical; both are perfect. Only the third differs.
- **"A minor key's tonic is a diminished triad."** In natural minor the tonic is a minor triad; the diminished triad sits on degree 2.
:::
