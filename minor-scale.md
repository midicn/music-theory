---
id: minor-scale
site: theo
cat: T3
title: 自然小调
title_en: Natural Minor Scale
summary: 全半全全半全全——大调的第三、六、七级各降一个半音
summary_en: Whole, half, whole, whole, half, whole, whole — a major scale with the 3rd, 6th and 7th lowered
level: core
tags: [乐理, 音阶, 小调]
tags_en: [theory, scale, minor]
alias: [小调音阶, 自然小调, natural minor, aeolian]
order: 14
links:
  - "[[concept:scale]]"
  - "[[concept:major-scale]]"
  - "[[concept:harmonic-minor]]"
  - "[[concept:melodic-minor]]"
  - "[[concept:aeolian]]"
  - "[[concept:key-signature]]"
instances:
  - giantmidi-006222 | 音阶与琶音练习：把自然小调按最慢速度走完，三个降低音的位置听得最清楚 | Scale and arpeggio exercises walk the natural minor at its slowest — the three lowered degrees are plain to hear
  - giantmidi-001413 | 《爱奥利亚圆舞曲》：自然小调与爱奥利亚调式结构完全相同，一首曲子可同时用两个名字理解 | The Aeolian Waltz — natural minor and the Aeolian mode share one structure, so one piece carries both names
  - mutopia-000049 | 《绿袖子》以小音程与级进铺陈，旋律的暗淡底色正是小调音阶最常见的用法 | Greensleeves moves in small intervals and steps; its dark colour is the common use of the minor scale
sources:
  - 自然小调的音程结构（全半全全半全全）与"大调第 3/6/7 级降低"的对应关系，属乐理通则
  - 自然小调与爱奥利亚调式同构，为通行表述
updated: 2026-09-23
---

::: zh
自然小调最省事的理解方式是：**把大调音阶的第 3、6、7 级各降一个半音**。
剩下的音不动，结构就变成了：

> **全 — 半 — 全 — 全 — 半 — 全 — 全**

| 级数 | 与大调相比 | C 大调 → C 自然小调 |
|---|---|---|
| 1 | 不变 | C |
| 2 | 不变 | D |
| 3 | **降半音** | E → E♭ |
| 4 | 不变 | F |
| 5 | 不变 | G |
| 6 | **降半音** | A → A♭ |
| 7 | **降半音** | B → B♭ |

三个降低的音合起来改变了三件事：主和弦变成小三和弦（暗淡）、第 6 级不再是指向主音的
导音（回到主音的引力变弱）、调号少三个升号或多三个降号。

## 为什么小调还要分三种

自然小调有一处"不方便"：**第 7 级与主音之间是大二度，不是小二度**，
所以它缺少把旋律推向主音的那股力量。于是有了两种加工版：

| 名称 | 改动 | 代价 |
|---|---|---|
| [[concept:harmonic-minor|和声小调]] | 第 7 级升半音 | 第 6–7 级之间出现增二度，旋律难唱 |
| [[concept:melodic-minor|旋律小调]] | 上行时第 6、7 级都升，下行还原 | 上下行结构不同，记谱要标两遍 |

三者不是三条不同的音阶，而是**同一条音阶面对不同需求的三次调整**。

## 同名：自然小调 = 爱奥利亚调式

自然小调的音程结构与 [[concept:aeolian|爱奥利亚调式]] **完全相同**。
区别只在称呼的语境：讲调性时叫"a 小调"，讲调式时叫"a 爱奥利亚"。
同名现象在 [[concept:dorian|多里亚]] 与 [[concept:major-scale|大调]]/[[concept:mixolydian|混合利底亚]] 之间也存在。

## 图示：大调降三个音

```svg
<svg viewBox="0 0 640 228" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样的起点，降下三个音，明亮就换成了暗淡</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.3">
      <line x1="0" y1="16" x2="448" y2="16"/>
      <line x1="0" y1="12" x2="0" y2="20"/><line x1="448" y1="12" x2="448" y2="20"/>
    </g>
    <text x="458" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C 自然小调</text>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="32" y="36">全</text><text x="96" y="36">半</text><text x="160" y="36">全</text>
      <text x="224" y="36">全</text><text x="288" y="36">半</text><text x="352" y="36">全</text>
      <text x="416" y="36">全</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="128" y="-16">E</text><text x="320" y="-16">A</text><text x="384" y="-16">B</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="128" y1="-8" x2="128" y2="-2"/>
      <line x1="320" y1="-8" x2="320" y2="-2"/>
      <line x1="384" y1="-8" x2="384" y2="-2"/>
    </g>
    <text x="0" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      橙色三处 = 从大调降下来：第 3、6、7 级
    </text>
    <text x="0" y="88" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      第 3 级降下 → 主和弦变小三和弦（音色变暗）
    </text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      第 7 级降下 → 失去小二度的导音引力（这正是和声小调要把它升回去的原因）
    </text>
  </g>
</svg>
```

## 听一听：大调与小调的同一起点

先听大调，再听自然小调。**同样的主音、同样从 C 开始**，只有三个音不同，
整个色彩的明暗却完全翻转 —— 这就是那三个半音的全部作用。

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","Ab4","Bb4","C5"],"label":"C 自然小调","label_en":"C natural minor","hint":"点「上行」听三个降低音的位置","hint_en":"Try Up and listen for the three lowered degrees","gap":0.38}
```

```notation
{"clef":"treble","notes":["C4","D4","Eb4","F4","G4","Ab4","Bb4","C5:w"],"caption":"C 自然小调：第 3、6、7 级降低","caption_en":"C natural minor — degrees 3, 6 and 7 lowered"}
```

## 常见误解

- **「小调就是悲伤的」** → 自然小调提供的是**较暗的色彩与较弱的回到主音的引力**，情绪仍由节奏与和声决定。
- **「小调音阶只有一种」** → 自然、和声、旋律三种是常用形态，此外还有五声小调、爵士小调等。
- **「小调的调号要在末尾加降号」** → 调号只由主音决定（a 小调与 C 大调共用无升降的调号）。降低的音已包含在调号里，不必另写。
- **「自然小调与爱奥利亚是两回事」** → 结构完全相同，只是"讲调性"与"讲调式"两种语境下的两个名字。
:::

::: en
The shortest way to understand the natural minor scale: **lower the 3rd, 6th and 7th degrees of a major scale
by one semitone each.** Nothing else moves, and the pattern becomes:

> **whole — half — whole — whole — half — whole — whole**

| Degree | Versus major | C major → C natural minor |
|---|---|---|
| 1 | unchanged | C |
| 2 | unchanged | D |
| 3 | **lowered** | E → E♭ |
| 4 | unchanged | F |
| 5 | unchanged | G |
| 6 | **lowered** | A → A♭ |
| 7 | **lowered** | B → B♭ |

Together the three lowered degrees change three things: the tonic triad becomes minor (darker), the 7th is no
longer a leading tone pulling to the tonic (the pull home weakens), and the key signature gains three flats or
loses three sharps.

## Why minor comes in three forms

The natural minor has one inconvenience: **its 7th degree sits a whole tone below the tonic, not a semitone**,
so it lacks the force that drives a melody home. Hence two adjusted versions:

| Name | Change | Cost |
|---|---|---|
| [[concept:harmonic-minor|harmonic minor]] | raise the 7th | an augmented second appears between 6 and 7, awkward to sing |
| [[concept:melodic-minor|melodic minor]] | raise 6 and 7 going up, restore going down | the two directions differ, so notation must say both |

These are not three separate scales but **one scale adjusted three ways for three needs**.

## The alias: natural minor = the Aeolian mode

Its interval pattern is **identical** to the [[concept:aeolian|Aeolian mode]]. Only the context of the name
differs: in tonal language it is "A minor", in modal language "A Aeolian". The same doubling appears between
[[concept:dorian|Dorian]] and [[concept:major-scale|major]]/[[concept:mixolydian|Mixolydian]].

## Diagram: lowering three degrees

```svg
<svg viewBox="0 0 640 228" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same starting note; lower three degrees and bright turns dark</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.3">
      <line x1="0" y1="16" x2="448" y2="16"/>
      <line x1="0" y1="12" x2="0" y2="20"/><line x1="448" y1="12" x2="448" y2="20"/>
    </g>
    <text x="458" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C natural minor</text>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="32" y="36">W</text><text x="96" y="36">H</text><text x="160" y="36">W</text>
      <text x="224" y="36">W</text><text x="288" y="36">H</text><text x="352" y="36">W</text>
      <text x="416" y="36">W</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="128" y="-16">E</text><text x="320" y="-16">A</text><text x="384" y="-16">B</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="128" y1="-8" x2="128" y2="-2"/>
      <line x1="320" y1="-8" x2="320" y2="-2"/>
      <line x1="384" y1="-8" x2="384" y2="-2"/>
    </g>
    <text x="0" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      The three orange marks are lowered from major: degrees 3, 6 and 7
    </text>
    <text x="0" y="88" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Lowered 3rd: the tonic triad becomes minor — the colour darkens
    </text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Lowered 7th: the semitone leading pull disappears — which is exactly why harmonic minor raises it back
    </text>
  </g>
</svg>
```

## Listen: one tonic, two colours

Hear major first, then natural minor. **Same tonic, same starting C**, only three notes differ, and the whole
light flips. That is the entire job of those three semitones.

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","Ab4","Bb4","C5"],"label":"C 自然小调","label_en":"C natural minor","hint":"点「上行」听三个降低音的位置","hint_en":"Try Up and listen for the three lowered degrees","gap":0.38}
```

```notation
{"clef":"treble","notes":["C4","D4","Eb4","F4","G4","Ab4","Bb4","C5:w"],"caption":"C 自然小调：第 3、6、7 级降低","caption_en":"C natural minor — degrees 3, 6 and 7 lowered"}
```

## Common misconceptions

- **"Minor means sad."** Natural minor supplies a **darker colour and a weaker pull home**; mood still comes from rhythm and harmony.
- **"There is only one minor scale."** Natural, harmonic and melodic are the common forms; pentatonic minor and jazz minor also exist.
- **"A minor key needs flats added at the end."** The key signature follows the tonic only (A minor shares C major's empty signature). The lowered notes are already inside it.
- **"Natural minor and Aeolian are different things."** Identical structure, two names in two contexts.
:::
