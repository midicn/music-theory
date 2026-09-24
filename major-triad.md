---
id: major-triad
site: theo
cat: T4
title: 大三和弦
title_en: Major Triad
summary: 大三度加小三度——调性里最稳的那个和弦
summary_en: A major third under a minor third — the most stable chord in tonality
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [大三和弦, major triad]
order: 14
links:
  - "[[concept:triad]]"
  - "[[concept:minor-triad]]"
  - "[[concept:major-scale]]"
  - "[[concept:harmonic-function]]"
instances:
  - giantmidi-006222 | 琶音练习里的大三和弦琶音：三个音依次弹出，能听出它为什么"站得住" | Major-triad arpeggios in scale exercises — the three notes in turn, showing why the chord stands so firmly
  - cyberhymnal-000695 | 管风琴圣咏：柱式排列的大三和弦是传统和声最常用的落脚点 | An organ hymn — block-voiced major triads, the commonest resting point in traditional harmony
  - pdmx-000607 | 《小星星变奏曲》：主三和弦为大三和弦，全曲的稳定感来自它 | The Ah vous variations — the tonic triad is major, and the sense of stability comes from it
sources:
  - 大三和弦 = 大三度 + 小三度，根音到五音为纯五度，属和声学通则
  - 大三和弦在主—属功能关系中的核心地位，为通行和声学表述
updated: 2026-09-23
---

::: zh
大三和弦只有一句话：**大三度在下，小三度在上**。

> C–E–G：C 到 E 是大三度（4 个半音），E 到 G 是小三度（3 个半音）

它听起来"稳"，有三个可验证的原因：

| 原因 | 说明 |
|---|---|
| **含纯五度** | 根音到五音是纯五度（7 个半音），是除八度外最协和的音程 |
| **含大三度** | 根音到三音是大三度，泛音列里第 4、5、6 分音正好就是这个结构（见 [[concept:harmonic-series|泛音列]]） |
| **不含半音冲突** | 三个音之间是大三度与小三度，没有小二度或增四度那种强张力 |

第三条最直观：把大三和弦的三个音排开，**找不到需要立刻解决的音**。这就是"稳"的技术含义。

## 它在哪里出现

**任何大调音阶上都有三个大三和弦**：I 级、IV 级、V 级。
这三级就是调性的骨架（主—下属—属），也是几乎所有古典作品的和声主干
（见 [[concept:harmonic-function|和声功能]]）。

自然小调里大三和弦较少但并非没有：III、VI、VII 级都是大三和弦 ——
这也是小调作品里"忽然亮一下"的常见来源。

## 与[[concept:minor-triad|小三和弦]]的唯一差别

把大三和弦的**三音降低半个音**，就得到小三和弦：

> 大三：C–**E**–G　　小三：C–**E♭**–G

一个音，稳定感与明暗完全反转。这也说明：**和弦的"性格"主要由三音决定**，五音是骨架。

## 图示：一个音之差

```svg
<svg viewBox="0 0 640 176" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">根音与五音不动，只把三音降半个音</text>
  </g>

  <g transform="translate(48,56)">
    <g font-family="Georgia,serif" font-size="13" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="90" y="0" fill="#E07A3F">E</text><text x="180" y="0" fill="#E07A3F">G</text>
      <text x="300" y="0" fill="#5B7FA8">C</text><text x="390" y="0" fill="#5B7FA8">E♭</text><text x="480" y="0" fill="#5B7FA8">G</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="14" x2="90" y2="14"/><line x1="0" y1="10" x2="0" y2="18"/><line x1="90" y1="10" x2="90" y2="18"/>
      <line x1="90" y1="14" x2="180" y2="14"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="300" y1="14" x2="390" y2="14"/><line x1="300" y1="10" x2="300" y2="18"/><line x1="390" y1="10" x2="390" y2="18"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="40" fill="#E07A3F">大三度（4 半音）</text>
      <text x="300" y="40" fill="#5B7FA8">小三度（3 半音）</text>
      <text x="0" y="62" fill="#6E6A64">根音到五音：两者都是纯五度（7 半音）—— 骨架不变</text>
      <text x="0" y="84" fill="#6E6A64">变化的只有三音，于是明亮与暗淡互换</text>
    </g>
  </g>
</svg>
```

## 听一听：大三和弦

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"C 大三和弦","label_en":"C major triad","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「大三和弦是"高兴"的和弦」** → 它提供的是**稳定**。用大三和弦写哀歌很常见。
- **「大调里所有和弦都是大三和弦」** → 七个级数里只有三个（I、IV、V）是。
- **「大三度在下就是大三和弦」** → 还要看上方那个三度是小三度。两个都大就是增三和弦。
- **「转位之后就不是大三和弦了」** → 性质由构成音决定，转位只改低音，不改性质。
:::

::: en
A major triad in one line: **a major third below, a minor third above.**

> C–E–G: C to E is a major third (4 semitones), E to G is a minor third (3)

It sounds stable for three verifiable reasons:

| Reason | Explanation |
|---|---|
| **It contains a perfect fifth** | Root to fifth is 7 semitones, the most consonant interval after the octave |
| **It contains a major third** | Root to third is major, and partials 4, 5 and 6 of the harmonic series are exactly this shape (see [[concept:harmonic-series|harmonic series]]) |
| **It contains no semitone clash** | The internal intervals are a major and a minor third — no minor second or tritone pulling for resolution |

The third is the most tangible: spread the three notes out and **there is nothing that demands immediate
resolution**. That is what "stable" means technically.

## Where it appears

**Every major scale contains three major triads**: on degrees I, IV and V. Those three are the tonal skeleton
(tonic, subdominant, dominant) and the harmonic backbone of nearly all classical music
(see [[concept:harmonic-function|harmonic function]]).

Natural minor has fewer, but not none: degrees III, VI and VII are major triads — which is a common source of
those sudden brightenings in minor-key music.

## The one difference from a [[concept:minor-triad|minor triad]]

Lower the **third** by a semitone and you have a minor triad:

> major: C–**E**–G　　 minor: C–**E♭**–G

One note, and stability and brightness both invert. It also shows that **a chord's character rests mainly on its
third**, while the fifth supplies the frame.

## Diagram: one note apart

```svg
<svg viewBox="0 0 640 176" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Root and fifth stay put; only the third drops a semitone</text>
  </g>

  <g transform="translate(48,56)">
    <g font-family="Georgia,serif" font-size="13" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="90" y="0" fill="#E07A3F">E</text><text x="180" y="0" fill="#E07A3F">G</text>
      <text x="300" y="0" fill="#5B7FA8">C</text><text x="390" y="0" fill="#5B7FA8">E♭</text><text x="480" y="0" fill="#5B7FA8">G</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="14" x2="90" y2="14"/><line x1="0" y1="10" x2="0" y2="18"/><line x1="90" y1="10" x2="90" y2="18"/>
      <line x1="90" y1="14" x2="180" y2="14"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="300" y1="14" x2="390" y2="14"/><line x1="300" y1="10" x2="300" y2="18"/><line x1="390" y1="10" x2="390" y2="18"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="40" fill="#E07A3F">major third (4 semitones)</text>
      <text x="300" y="40" fill="#5B7FA8">minor third (3 semitones)</text>
      <text x="0" y="62" fill="#6E6A64">Root to fifth is a perfect fifth in both (7 semitones) — the frame is unchanged</text>
      <text x="0" y="84" fill="#6E6A64">Only the third moves, and bright and dark trade places</text>
    </g>
  </g>
</svg>
```

## Listen: the major triad

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"C 大三和弦","label_en":"C major triad","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"A major triad is a happy chord."** It supplies **stability**. Laments written in major triads are common.
- **"In a major key all the chords are major."** Only three of the seven degrees (I, IV, V) are.
- **"A major third on the bottom makes a major triad."** The upper third must be minor too. Two major thirds make an augmented triad.
- **"Inverting it stops it being a major triad."** Quality is fixed by the notes; inversion changes only the bass.
:::
