---
id: major-seventh
site: theo
cat: T4
title: 大七和弦
title_en: Major Seventh
summary: 大三和弦加大七度——七音只比主音低半个音，所以最尖锐
summary_en: A major triad plus a major seventh — the seventh sits a semitone below the octave, which makes it the sharpest
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [大七和弦, major seventh, maj7]
order: 28
links:
  - "[[concept:seventh-chord]]"
  - "[[concept:dominant-seventh]]"
  - "[[concept:minor-seventh]]"
  - "[[concept:half-diminished-seventh]]"
instances:
  - atepp-000195 | 德彪西《月光》：大七度与九度被当作持续的色彩而非待解决的紧张，可听它在另一套语汇里的用法 | Debussy's Clair de lune — major sevenths and ninths used as sustained colour rather than tension, the chord in another vocabulary
  - giantmidi-006222 | 琶音练习可弹出大七和弦琶音，用于听七音紧贴八度的位置 | Scale exercises can sound a major-seventh arpeggio, making the seventh's closeness to the octave audible
  - cyberhymnal-000695 | 管风琴圣咏作对照：传统和声里大七和弦罕见，与上面的用法形成鲜明差异 | An organ hymn as a control — the major seventh is rare in traditional harmony, contrasting sharply with the above
sources:
  - 大七和弦 = 大三和弦 + 大七度；根音到七音为 11 个半音，属和声学通则
  - 大七和弦在 20 世纪和声与爵士中成为稳定的色彩和弦，为通行表述
updated: 2026-09-24
---

::: zh
大七和弦是**大三和弦 + 大七度**：

> C 大七 = C–E–G–B

它和 [[concept:dominant-seventh|属七和弦]] 只差一个音高：把 B♭ 升成 B。
但这半个音带来的是**完全不同的紧张度**。

## 为什么它听起来"尖锐"

大七度（11 个半音）**只比八度低一个半音**（见 [[concept:octave|八度]]）。
于是七音会不断"被听成八度的错觉音"—— 耳朵预期它到 C，却差半步停住。
这种"几乎到达"的悬置感，就是大七和弦特有的锐度。

| 七音位置 | 音程 | 听感 |
|---|---|---|
| 距八度 2 个半音（小七度） | 柔和的不安定 | 属七和弦 |
| **距八度 1 个半音（大七度）** | **尖锐的悬置** | **大七和弦** |

## 它出现的位置

大调音阶上叠三度，**第 1 级与第 4 级是自然的大七和弦**（Imaj7 / IVmaj7）。
小调里不自然出现，需要升第 3 级或升第 6 级。

在传统和声里它很少作为目标使用；到了 20 世纪，它变成了**稳定的色彩和弦** ——
爵士与城市流行音乐里，大七和弦常常是**句子的终点**，而不需要解决。
这是"和弦功能"随风格变化的典型例子。

## 图示：七音与八度只差半音

```svg
<svg viewBox="0 0 640 186" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样是大三和弦，七音的位置决定了整条和弦的性格</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">B♭</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="12" y1="0" x2="12" y2="78"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.3" stroke-dasharray="3 2">
      <line x1="46" y1="78" x2="46" y2="104"/>
    </g>
    <text x="56" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">离八度还差 2 个半音</text>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">属七和弦：柔和的不安定</text>

    <g transform="translate(300,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">B</text>
      </g>
      <g stroke="#5B7FA8" stroke-width="1.2">
        <line x1="12" y1="0" x2="12" y2="78"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.3" stroke-dasharray="3 2">
        <line x1="46" y1="78" x2="46" y2="92"/>
      </g>
      <text x="56" y="90" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">只差 1 个半音</text>
      <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">大七和弦：尖锐的悬置</text>
    </g>
  </g>
</svg>
```

## 听一听：大七和弦

听它"几乎到达却停住"的感觉，再与属七和弦对照。

```audiolab
{"type":"chord","root":"C4","quality":"maj7","inversion":0,"label":"大七和弦（C–E–G–B）","label_en":"Major seventh (C–E–G–B)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「大七和属七只差一个音，差不多」** → 七音差半个音，紧张度完全不同：小七度柔和、大七度尖锐。
- **「大七和弦必须解决」** → 传统和声里通常如此；爵士与流行里它是稳定的终点。
- **「大七和弦只在大调里有」** → 大调第 1、4 级自然产生；小调里需要变化音。
- **「带"大"字所以比属七更"强"」** → "大七"指的是七度的**大小**（大七度），与和弦的强弱或功能无关。
:::

::: en
A major seventh is **a major triad plus a major seventh**:

> C major seventh = C–E–G–B

It differs from the [[concept:dominant-seventh|dominant seventh]] by a single semitone: B♭ becomes B. That
half-step changes the tension completely.

## Why it sounds sharp

The major seventh spans 11 semitones — **one semitone short of the octave** (see [[concept:octave|octave]]).
So the seventh keeps being heard as an octave that has not arrived: the ear expects C and the note stops a
semitone short. That almost-there suspension is the specific edge of a major seventh chord.

| Position of the seventh | Interval | Impression |
|---|---|---|
| two semitones below the octave (minor seventh) | soft instability | dominant seventh |
| **one semitone below the octave (major seventh)** | **sharp suspension** | **major seventh** |

## Where it appears

Stacking thirds on a major scale produces natural major seventh chords on **degrees 1 and 4** (Imaj7, IVmaj7).
Minor keys do not produce it without chromatic alteration.

In traditional harmony it is rarely a destination. In the twentieth century it became a **stable colour chord**:
in jazz and city pop a major seventh is often the **end of a phrase**, needing no resolution. A textbook case of
harmonic function shifting with style.

## Diagram: the seventh sitting a semitone below the octave

```svg
<svg viewBox="0 0 640 186" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same major triad; where the seventh sits decides the chord's character</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">B♭</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="12" y1="0" x2="12" y2="78"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.3" stroke-dasharray="3 2">
      <line x1="46" y1="78" x2="46" y2="104"/>
    </g>
    <text x="56" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">two semitones short of the octave</text>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">dominant seventh: soft instability</text>

    <g transform="translate(300,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">B</text>
      </g>
      <g stroke="#5B7FA8" stroke-width="1.2">
        <line x1="12" y1="0" x2="12" y2="78"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.3" stroke-dasharray="3 2">
        <line x1="46" y1="78" x2="46" y2="92"/>
      </g>
      <text x="56" y="90" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">only one semitone short</text>
      <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">major seventh: sharp suspension</text>
    </g>
  </g>
</svg>
```

## Listen: the major seventh

Hear the almost-arriving-and-stopping quality, then compare it with the dominant seventh.

```audiolab
{"type":"chord","root":"C4","quality":"maj7","inversion":0,"label":"大七和弦（C–E–G–B）","label_en":"Major seventh (C–E–G–B)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"Major and dominant sevenths differ by one note, so they are alike."** The seventh differs by a semitone and the tension is completely different — soft for the minor seventh, sharp for the major.
- **"A major seventh must resolve."** Usually true traditionally; in jazz and pop it is a stable endpoint.
- **"Major sevenths only exist in major keys."** They arise naturally on degrees 1 and 4 of a major scale; minor keys need accidentals.
- **"The word major makes it 'stronger' than a dominant seventh."** "Major seventh" names the *size* of the seventh, not the chord's strength or function.
:::
