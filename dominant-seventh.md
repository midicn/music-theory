---
id: dominant-seventh
site: theo
cat: T4
title: 属七和弦
title_en: Dominant Seventh
summary: 大三和弦加小七度——内部藏着一个三全音，是最强的推动力
summary_en: A major triad plus a minor seventh — it hides a tritone, and that is the strongest push in tonal music
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [属七和弦, dominant seventh, V7]
order: 24
links:
  - "[[concept:seventh-chord]]"
  - "[[concept:triad]]"
  - "[[concept:augmented-diminished]]"
  - "[[concept:cadence]]"
  - "[[concept:harmonic-function]]"
  - "[[concept:circle-of-fifths]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：属七和弦是终止式的常客，可听它如何把音乐推回主和弦 | An organ hymn — the dominant seventh is a fixture at cadences; hear how it pushes the music home
  - atepp-000318 | a 小调奏鸣曲：小调的属七和弦需要升第 7 级才能成立，可听这一处变化音的作用 | A sonata in A minor — a minor-key dominant seventh requires the raised seventh, and its effect is audible
  - mutopia-000049 | 《绿袖子》加固定低音的变奏：属七和弦在乐句收束处的解决过程清楚可辨 | Greensleeves to a Ground — the resolution of dominant sevenths at phrase endings is easy to follow
sources:
  - 属七和弦 = 大三和弦 + 小七度，根音到七音为小七度；三音与七音之间构成三全音，属和声学通则
  - 属七和弦在大小调中的构成差异（小调须升第 7 级）为通行和声学表述
updated: 2026-09-24
---

::: zh
属七和弦是七和弦里最有名的一个：**大三和弦 + 小七度**。

> C 属七 = C–E–G–B♭（大三和弦 C–E–G，加小七度 B♭）

名字里的"属"指它通常出现在**调的第 5 级上**（属音）。它是调性音乐里最强的推动力，
原因藏在一个不容易一眼看出的地方。

## 内部的三全音

把四个音拆开看，有一个关键的两个音：

> **三音（E）与七音（B♭）之间相距 6 个半音 —— 三全音。**

这正是属七和弦的引擎。三全音的两个音**方向相反**：

| 音 | 倾向 |
|---|---|
| 三音 E | 上行到主音 F（半音） |
| 七音 B♭ | 下行到 A（半音） |

一个升、一个降，两者**同时**解决 —— 这是所有收束动作里最干净的一种。
三全音属于最不稳定的音程（见 [[concept:augmented-diminished|增音程与减音程]]），
而属七和弦把它包装成了一个完整和弦，于是"不稳定"变成了可以规划、可以用和声处理的**工具**。

## 大小调里的两种构造

| 场合 | 构成 | 说明 |
|---|---|---|
| **大调 V7** | 大三 + 小七，完全来自音阶 | 无需变化音 |
| **小调 V7** | 需要把第 7 级**升上去** | 自然小调的 V 级是小七和弦，必须先变 [[concept:harmonic-minor|和声小调]] |

第二行解释了一个长期存在的疑问：**小调作品里为什么总出现升第 7 级的变化音？**
因为不升它，就没有属七和弦 —— 也就没有能推动收束的和声。

## 它为什么能"转调"

属七和弦还有一个额外用途：**它含三全音，而三全音是不对称的**。
同一条属七和弦可以被重新解释成另一个调的属七和弦 —— 这是
[[concept:modulation|转调]] 最常用的手段之一，也是 [[concept:circle-of-fifths|五度圈]]
能"绕"起来的和声基础。

## 图示：三音与七音的反向解决

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">三音上行、七音下行，两条线同时收进主和弦</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">B♭</text><text x="0" y="34">G</text><text x="0" y="68">E</text><text x="0" y="102">C</text>
    </g>
    <text x="-34" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">七音</text>
    <text x="-34" y="68" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">三音</text>
    <text x="-34" y="102" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">根音</text>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="0" y1="34" x2="0" y2="68"/>
      <line x1="0" y1="34" x2="0" y2="68"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      <text x="14" y="52">三全音（6 半音）</text>
    </g>

    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle" transform="translate(260,0)">
      <text x="0" y="0">A</text><text x="0" y="34">F</text><text x="0" y="68">C</text>
    </g>
    <text x="186" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">七音→</text>
    <text x="186" y="68" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">三音→</text>

    <g stroke="#E07A3F" stroke-width="1.3">
      <line x1="20" y1="0" x2="152" y2="0"/>
      <line x1="20" y1="0" x2="20" y2="0"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.3">
      <line x1="20" y1="68" x2="152" y2="34"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="290" y="4" fill="#E07A3F">B♭ 下行半音 → A</text>
      <text x="290" y="38" fill="#5B7FA8">E 上行半音 → F</text>
      <text x="290" y="72" fill="#5B7FA8">（F 是目标调的根音或三音）</text>
      <text x="290" y="104" fill="#6E6A64">每一步都只走半音 —— 这是最平滑也最有力的收束</text>
    </g>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      若三音与七音都留在原位（都不解决），属七和弦就失去推力，听感立刻变"悬停"
    </text>
  </g>
</svg>
```

## 听一听：属七和弦

先听整体（明显要"走"），再点「分解」听三音与七音之间的距离。

```audiolab
{"type":"chord","root":"C4","quality":"dom7","inversion":0,"label":"属七和弦（C–E–G–B♭）","label_en":"Dominant seventh (C–E–G–B♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```notation
{"clef":"treble","notes":[["C4","E4","G4","Bb4"],["F4","A4","C5","F5"]],"caption":"属七和弦（左）解决到主和弦（右）","caption_en":"A dominant seventh (left) resolving to the tonic (right)"}
```

## 常见误解

- **「属七和弦就是第五级的和弦」** → 更要紧的是它的**结构**（大三 + 小七）与由此带来的三全音。名字来自它最常出现的位置，不是它的定义。
- **「小调的属七和弦来自自然小调」** → 自然小调的第 5 级是小七和弦。要得到属七，必须升第 7 级。
- **「属七和弦必须解决到主和弦」** → 传统和声里几乎总是；爵士与流行里它常被当成稳定色彩，或去往别处。
- **「属七和大七只差一个音，听感差不多」** → 差的是半个音，紧张度差别极大：小七度柔和、大七度尖锐。
:::

::: en
The dominant seventh is the most famous seventh chord: **a major triad plus a minor seventh.**

> C dominant seventh = C–E–G–B♭ (major triad C–E–G, plus the minor seventh B♭)

The "dominant" in the name refers to its usual home, **degree 5 of the key**. It is the strongest propulsive force
in tonal music, and the reason is hidden where you would not first look.

## The tritone inside

Spread the four notes out and one pair matters most:

> **The third (E) and the seventh (B♭) are six semitones apart — a tritone.**

That is the engine. The two notes of the tritone pull in **opposite directions**:

| Note | Tendency |
|---|---|
| the third, E | rises a semitone to the tonic, F |
| the seventh, B♭ | falls a semitone to A |

One rises, one falls, and both resolve **at once** — the cleanest closing gesture there is. The tritone is among
the least settled intervals (see [[concept:augmented-diminished|augmented and diminished]]), and the dominant
seventh packs it into a single chord — turning instability into a planned, harmonically usable **tool**.

## Two constructions, major and minor

| Context | Content | Note |
|---|---|---|
| **V7 in major** | major triad + minor seventh, straight from the scale | no accidental needed |
| **V7 in minor** | the seventh degree must be **raised** | natural minor's degree 5 is a minor seventh chord; [[concept:harmonic-minor|harmonic minor]] comes first |

The second line answers a long-standing puzzle: **why do minor-key works keep sharpening the seventh?** Without
it there is no dominant seventh — and therefore no harmony capable of driving a close.

## Why it also enables modulation

The dominant seventh has a further use: **it contains a tritone, and a tritone is asymmetrical.** The same chord
can be reinterpreted as the dominant seventh of another key — one of the commonest means of
[[concept:modulation|modulation]], and the harmonic basis that lets the
[[concept:circle-of-fifths|circle of fifths]] keep turning.

## Diagram: the third and seventh resolving in opposite directions

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The third rises, the seventh falls, and both lines close into the tonic chord</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">B♭</text><text x="0" y="34">G</text><text x="0" y="68">E</text><text x="0" y="102">C</text>
    </g>
    <text x="-34" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">seventh</text>
    <text x="-34" y="68" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">third</text>
    <text x="-34" y="102" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">root</text>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="0" y1="34" x2="0" y2="68"/>
    </g>
    <text x="14" y="52" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">tritone (6 semitones)</text>

    <g transform="translate(260,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">A</text><text x="0" y="34">F</text><text x="0" y="68">C</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.3">
        <line x1="-240" y1="0" x2="-120" y2="0"/>
      </g>
      <g stroke="#5B7FA8" stroke-width="1.3">
        <line x1="-240" y1="68" x2="-120" y2="34"/>
      </g>
      <text x="30" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">B♭ falls a semitone to A</text>
      <text x="30" y="38" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">E rises a semitone to F</text>
      <text x="30" y="72" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">(F becomes root or third of the new chord)</text>
      <text x="30" y="104" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Every step is a semitone — the smoothest and strongest close</text>
    </g>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      If neither note resolves, the chord loses its push and the sound simply hangs
    </text>
  </g>
</svg>
```

## Listen: the dominant seventh

Hear the block first (it clearly wants to move), then press Arpeggio to hear the distance between third and
seventh.

```audiolab
{"type":"chord","root":"C4","quality":"dom7","inversion":0,"label":"属七和弦（C–E–G–B♭）","label_en":"Dominant seventh (C–E–G–B♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```notation
{"clef":"treble","notes":[["C4","E4","G4","Bb4"],["F4","A4","C5","F5"]],"caption":"属七和弦（左）解决到主和弦（右）","caption_en":"A dominant seventh (left) resolving to the tonic (right)"}
```

## Common misconceptions

- **"A dominant seventh is simply the chord on degree 5."** What matters more is its **structure** (major triad plus minor seventh) and the tritone that follows. Its position gave it the name, not its definition.
- **"A minor key's dominant seventh comes from natural minor."** Natural minor's degree 5 is a minor seventh chord. Getting a dominant seventh requires raising the seventh.
- **"A dominant seventh must resolve to the tonic."** In traditional harmony almost always; in jazz and pop it often acts as a stable colour or heads elsewhere.
- **"Dominant and major sevenths differ by one note, so they sound similar."** The difference is a semitone, and the tension differs enormously — a minor seventh is soft, a major seventh sharp.
:::
