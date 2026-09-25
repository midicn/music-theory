---
id: sixth-chord
site: theo
cat: T4
title: 六和弦
title_en: Sixth Chord
summary: 三和弦加六度——与七和弦只差一个音区，功能却完全不同
summary_en: A triad plus a sixth — one register away from a seventh chord, yet a different function
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [六和弦, sixth chord, 加六和弦]
order: 38
links:
  - "[[concept:triad]]"
  - "[[concept:seventh-chord]]"
  - "[[concept:minor-seventh]]"
  - "[[concept:chord-inversion]]"
  - "[[concept:added-tone-chord]]"
instances:
  - giantmidi-006222 | 琶音练习可弹出六和弦，与七和弦对照可听出"六度在上"与"七度在上"的差别 | Scale exercises can sound sixth chords; against seventh chords the difference between a sixth on top and a seventh on top is audible
  - atepp-000195 | 德彪西《月光》：六度与附加音被当作稳定色彩使用，可听它在印象派语汇里的位置 | Debussy's Clair de lune — sixths and added tones as stable colour, showing its place in the Impressionist vocabulary
  - mutopia-000049 | 《绿袖子》加固定低音的变奏：小调语境下六度常作为稳定的色彩音出现 | Greensleeves to a Ground — in a minor context the sixth often appears as a stable colour tone
sources:
  - 六和弦 = 三和弦 + 六度（根音到六度为大六度或小六度），属和声学通则
  - 六和弦与七和弦的第一转位在音高上重合但功能不同，为通行和声学表述
updated: 2026-09-24
---

::: zh
六和弦是**三和弦再加一个六度**：

> C6 = C–E–G–**A**（大三和弦 + 大六度）

它常被认为"不重要"，因为六度与三度的关系不像七度那样醒目。但它有一个非常实用的性质：
**它是稳定的，而七和弦不是。**

## 一个容易搞混的巧合

**C6（C–E–G–A）与 Am7（A–C–E–G）的音高完全一样。** 那它们是同一个和弦吗？

| 视角 | 判断依据 | 结论 |
|---|---|---|
| **音高** | 按键位看，是同一组音 | 相同 |
| **功能** | 根音是谁？倾向于走去哪？ | **不同** |

C6 的根音是 C，听起来是个稳定的主功能和弦；Am7 的根音是 A，带七音，倾向于解决。
**同一组音在不同语境里完全可以承担不同功能** —— 这与 [[concept:enharmonic|等音]] 的逻辑一致：
**听感相同，写法与功能不同。**

## 六和弦的两种写法

| 写法 | 含义 | 常见场合 |
|---|---|---|
| **C6** | 三和弦 + 六度，功能上属 C | 爵士、流行 |
| **Am7/C** | Am7 的第一转位，低音是 C | 传统和声分析 |

同一组音，用哪个记法取决于**你把它听成什么**。这是分析与记谱相互影响的一个典型例子。

## 它为什么听起来"松了一口气"

对比一下同一位置的两个选择：

- **Cmaj7（C–E–G–B）**：七音 B 紧贴八度，产生悬置（见 [[concept:major-seventh|大七和弦]]）；
- **C6（C–E–G–A）**：六度 A 离八度还有两个半音，**没有悬置感**。

所以六和弦常被形容为"大七和弦解决了的感觉"。它在爵士里常作为大七和弦的替代，
在结尾更干净、更"落地"。

## 图示：同一组音，两种根音

```svg
<svg viewBox="0 0 640 184" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">音完全相同；区别在"你把它当成哪个和弦"</text>
  </g>

  <g transform="translate(60,50)">
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">A</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.4"><line x1="14" y1="0" x2="14" y2="78"/></g>
    <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C6：根音 C，稳定</text>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">听成主和弦</text>

    <g transform="translate(280,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">A</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.4"><line x1="14" y1="0" x2="14" y2="78"/></g>
      <g stroke="#E07A3F" stroke-width="1.2" stroke-dasharray="3 2"><line x1="34" y1="0" x2="34" y2="78"/></g>
      <text x="44" y="44" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">根音 A 藏在顶上</text>
      <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Am7/C：根音 A，带七音</text>
      <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">听成下属方向的和弦</text>
    </g>
  </g>
</svg>
```

## 听一听：六和弦

先听 C6（稳、落地），再听 Cmaj7（悬着）。同一位置的两个选择，收尾感完全不同。

```audiolab
{"type":"chord","root":"C4","quality":"six","inversion":0,"label":"六和弦（C–E–G–A）","label_en":"Sixth chord (C–E–G–A)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「C6 和 Am7 是同一个和弦」** → 音高相同，功能不同。选哪个记法取决于你把它听成什么。
- **「六和弦就是加了六度的九和弦」** → 六和弦不含七音；含七音的是七和弦、九和弦。
- **「六度不稳定」** → 大六度是协和音程，六和弦整体是稳定的。
- **「六和弦只在爵士里用」** → 传统和声里它以"七和弦转位"的身份大量出现，只是记法不同。
:::

::: en
A sixth chord is **a triad plus a sixth**:

> C6 = C–E–G–**A** (major triad plus a major sixth)

It is often dismissed as unimportant, since a sixth is less conspicuous than a seventh. But it has one very
useful property: **it is stable, whereas a seventh chord is not.**

## A coincidence that trips people up

**C6 (C–E–G–A) and Am7 (A–C–E–G) contain exactly the same pitches.** So are they the same chord?

| Viewpoint | Criterion | Verdict |
|---|---|---|
| **pitch** | the keys pressed are the same set | identical |
| **function** | which note is the root, and where does it want to go? | **different** |

C6 has C as its root and reads as a stable tonic-function chord; Am7 has A as its root, carries a seventh, and
wants to resolve. **One set of notes can carry different functions in different contexts** — the same logic as
[[concept:enharmonic|enharmonic]] spelling: **same sound, different notation and function.**

## Two ways to write it

| Notation | Meaning | Typical context |
|---|---|---|
| **C6** | triad plus sixth, functionally a C chord | jazz, pop |
| **Am7/C** | first inversion of Am7, with C in the bass | traditional harmonic analysis |

The same notes; which notation you use depends on **what you hear it as**. A textbook case of analysis and
notation shaping each other.

## Why it sounds like relief

Compare two options in the same position:

- **Cmaj7 (C–E–G–B)**: the seventh B sits a semitone below the octave, creating suspension (see
  [[concept:major-seventh|major seventh]]);
- **C6 (C–E–G–A)**: the sixth A is two semitones short of the octave, with **no suspension**.

So the sixth chord is often described as "a major seventh that has resolved". Jazz uses it as a substitute for
the major seventh where an ending should feel cleaner and more settled.

## Diagram: one set of notes, two roots

```svg
<svg viewBox="0 0 640 184" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Identical pitches; the difference is which chord you hear them as</text>
  </g>

  <g transform="translate(60,50)">
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">A</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.4"><line x1="14" y1="0" x2="14" y2="78"/></g>
    <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C6: root C, stable</text>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">heard as a tonic chord</text>

    <g transform="translate(280,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">A</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.4"><line x1="14" y1="0" x2="14" y2="78"/></g>
      <g stroke="#E07A3F" stroke-width="1.2" stroke-dasharray="3 2"><line x1="34" y1="0" x2="34" y2="78"/></g>
      <text x="44" y="44" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">the root A hides on top</text>
      <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Am7/C: root A, with a seventh</text>
      <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">heard as a subdominant-side chord</text>
    </g>
  </g>
</svg>
```

## Listen: the sixth chord

Hear C6 (settled, landed), then Cmaj7 (suspended). Two options in the same place, with very different closures.

```audiolab
{"type":"chord","root":"C4","quality":"six","inversion":0,"label":"六和弦（C–E–G–A）","label_en":"Sixth chord (C–E–G–A)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"C6 and Am7 are the same chord."** Same pitches, different function. The notation you choose follows what you hear.
- **"A sixth chord is a ninth chord with the ninth added."** It contains no seventh; chords with a seventh are seventh and ninth chords.
- **"A sixth is unstable."** A major sixth is consonant, and a sixth chord is stable overall.
- **"Sixth chords belong to jazz only."** Traditional harmony uses the same notes constantly, as an inversion of a seventh chord, under a different notation.
:::
