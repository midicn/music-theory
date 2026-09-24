---
id: octatonic
site: theo
cat: T3
title: 八声音阶
title_en: Octatonic Scale
summary: 全音与半音交替——八个音，两个减七和弦叠起来
summary_en: Whole and half steps alternating — eight notes, two diminished sevenths stacked
level: standard
tags: [乐理, 音阶, 人工音阶]
tags_en: [theory, scale, artificial]
alias: [八声音阶, 减音阶, diminished scale]
order: 48
links:
  - "[[concept:scale]]"
  - "[[concept:whole-tone]]"
  - "[[concept:chromatic]]"
  - "[[concept:triad]]"
instances:
  - giantmidi-006222 | 音阶练习可按需弹出八声音阶，用于听"全半交替"的基本形态 | Scale exercises play the octatonic directly — hear the alternating whole and half steps
  - atepp-000082 | 斯克里亚宾晚期奏鸣曲：同期的和声语汇大量使用减七类结构，可与之对照 | A late Scriabin sonata — its harmonic vocabulary leans heavily on diminished-seventh structures, useful as a comparison
  - pdmx-000607 | 大调主题可作对照：从它起交替取全音与半音，就能推出一条八声音阶 | A major-key theme as a control — take alternating whole and half steps from it and an octatonic emerges
sources:
  - 八声音阶 = 全音与半音交替排列、每八度八个音，属乐理通则
  - 该音阶由两条减七和弦叠合而成、常见于俄罗斯乐派与爵士，为通行理论表述
updated: 2026-09-23
---

::: zh
八声音阶的结构一句话：**全音、半音，交替进行**。

> C 八声音阶：C D E♭ F F♯ G♯ A B C

八个音一个八度，但**只有两种步幅**在反复：全音 1 → 半音 1 → 全音 1 → 半音 1……

## 为什么它和减七和弦是一回事

把八声音阶里**每隔一个音**取出来，得到两条**减七和弦**：

| 取出 | 得到 |
|---|---|
| 第 1、3、5、7 音（C E♭ F♯ A） | 减七和弦 |
| 第 2、4、6、8 音（D F G♯ B） | 另一条减七和弦 |

所以八声音阶也叫**减音阶**：它就是把两条减七和弦合起来、按高低排好。
这也解释了它的两个特性：**对称**（每隔三个半音重复一次结构）与**没有主音**
（与 [[concept:whole-tone|全音音阶]]、[[concept:chromatic|半音阶]]一样，等距结构无法提供中心）。

## 只有三条

由于每三个半音结构重复一次，八声音阶**只有三条**（从 C、从 C♯、从 D 各一条），
再往上都是这三条的重复。

## 图示：两条减七和弦叠成一条音阶

```svg
<svg viewBox="0 0 640 186" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">每隔一个音取一次，取出的两条正是减七和弦</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="11.5" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="56" y="0">D</text><text x="112" y="0">E♭</text>
      <text x="168" y="0">F</text><text x="224" y="0">F♯</text><text x="280" y="0">G♯</text>
      <text x="336" y="0">A</text><text x="392" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="16" x2="448" y2="16"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">
      <text x="28" y="30">全</text><text x="84" y="30">半</text><text x="140" y="30">全</text>
      <text x="196" y="30">半</text><text x="252" y="30">全</text><text x="308" y="30">半</text>
      <text x="364" y="30">全</text><text x="420" y="30">半</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      <text x="0" y="58">① 第 1、3、5、7 音 → C E♭ F♯ A：减七和弦</text>
      <text x="0" y="80">② 第 2、4、6、8 音 → D F G♯ B：另一条减七和弦</text>
      <text x="0" y="106" fill="#6E6A64">两条合起来 = 八声音阶（也称减音阶）</text>
      <text x="0" y="128" fill="#6E6A64">对称结构 ⇒ 从 C、C♯、D 起的三种写法即可覆盖全部，其余都是重复</text>
    </g>
  </g>
</svg>
```

## 听一听：全半交替

听的时候留意"一大步一小步"的节奏感 —— 这是它区别于全音音阶（步幅全同）的关键。

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","F#4","G#4","A4","B4","C5"],"label":"C 八声音阶","label_en":"C octatonic scale","hint":"点「上行」听全音与半音交替","hint_en":"Try Up — whole and half steps alternate","gap":0.34}
```

## 常见误解

- **「八声音阶是七声加一个音」** → 它不是对七声音阶的增补，而是**全半交替**这一独立结构的产物。
- **「它和全音音阶是一回事」** → 全音音阶步幅全同（6 音），八声音阶步幅交替（8 音），听感差别明显。
- **「它有十二个调」** → 只有三条（从 C、C♯、D 起），因为结构每三个半音重复一次。
- **「只有俄罗斯乐派用」** → 爵士里它是减七和弦即兴的标准材料，电影配乐也常用它制造不安。
:::

::: en
The octatonic scale in one line: **whole tone, half tone, alternating.**

> C octatonic: C D E♭ F F♯ G♯ A B C

Eight notes to the octave, but **only two step sizes**, repeating: whole, half, whole, half …

## Why it is the same thing as diminished sevenths

Take **every other note** of the octatonic and you get two **diminished seventh chords**:

| Take | Result |
|---|---|
| notes 1, 3, 5, 7 (C E♭ F♯ A) | a diminished seventh chord |
| notes 2, 4, 6, 8 (D F G♯ B) | the other diminished seventh chord |

So the octatonic is also called the **diminished scale**: it is two diminished sevenths combined and sorted by
pitch. That explains two of its properties: it is **symmetrical** (the structure repeats every three semitones)
and it has **no tonic** (like the [[concept:whole-tone|whole-tone]] and [[concept:chromatic|chromatic]] scales,
an equidistant structure offers no centre).

## Only three of them

Because the structure repeats every three semitones, there are **only three** octatonic scales (from C, from C♯,
from D). Every other starting note repeats one of them.

## Diagram: two diminished sevenths make one scale

```svg
<svg viewBox="0 0 640 186" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Take every other note and the two results are diminished seventh chords</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="11.5" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="56" y="0">D</text><text x="112" y="0">E♭</text>
      <text x="168" y="0">F</text><text x="224" y="0">F♯</text><text x="280" y="0">G♯</text>
      <text x="336" y="0">A</text><text x="392" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="16" x2="448" y2="16"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">
      <text x="28" y="30">W</text><text x="84" y="30">H</text><text x="140" y="30">W</text>
      <text x="196" y="30">H</text><text x="252" y="30">W</text><text x="308" y="30">H</text>
      <text x="364" y="30">W</text><text x="420" y="30">H</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      <text x="0" y="58">1) notes 1, 3, 5, 7 — C E♭ F♯ A: a diminished seventh</text>
      <text x="0" y="80">2) notes 2, 4, 6, 8 — D F G♯ B: the other diminished seventh</text>
      <text x="0" y="106" fill="#6E6A64">Together they make the octatonic (the diminished) scale</text>
      <text x="0" y="128" fill="#6E6A64">Symmetry means three spellings (from C, C♯, D) cover all cases</text>
    </g>
  </g>
</svg>
```

## Listen: alternating steps

Notice the feel of one long step then one short step. That alternation is what separates it from the whole-tone
scale, where every step is identical.

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","F#4","G#4","A4","B4","C5"],"label":"C 八声音阶","label_en":"C octatonic scale","hint":"点「上行」听全音与半音交替","hint_en":"Try Up — whole and half steps alternate","gap":0.34}
```

## Common misconceptions

- **"The octatonic is a seven-note scale plus one."** It is not an add-on but the product of an independent structure: alternating whole and half steps.
- **"It is the same as the whole-tone scale."** The whole-tone scale has identical steps (six notes); the octatonic alternates (eight notes). The heard difference is plain.
- **"There are twelve of them."** Only three — from C, C♯ and D — because the structure repeats every three semitones.
- **"Only Russian composers used it."** In jazz it is standard material for improvising over diminished sevenths, and film scoring uses it to create unease.
:::
