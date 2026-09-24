---
id: chromatic
site: theo
cat: T3
title: 半音阶
title_en: Chromatic Scale
summary: 十二个半音一个不落——它是材料，不是调性
summary_en: All twelve semitones, none omitted — a material rather than a key
level: standard
tags: [乐理, 音阶, 人工音阶]
tags_en: [theory, scale, artificial]
alias: [半音阶, chromatic scale]
order: 46
links:
  - "[[concept:semitone]]"
  - "[[concept:scale]]"
  - "[[concept:enharmonic]]"
  - "[[concept:whole-tone]]"
instances:
  - aria-010102 | 巴赫《半音阶幻想曲与赋格》：标题即点明半音写法，是"半音材料怎么推动音乐"的经典样本 | Bach's Chromatic Fantasia and Fugue — the title names the device, and it is the classic sample of chromatic material driving music forward
  - giantmidi-006222 | 音阶练习可按需弹出半音阶，用于听"每一步都一样宽"的基本形态 | Scale exercises play the chromatic scale directly — hear the basic form where every step is identical
  - atepp-000195 | 德彪西作品中半音化的和声处理，可对照半音材料在另一套语汇里的用法 | Chromatic harmonic writing in Debussy — the same material inside a different vocabulary
sources:
  - 半音阶由十二个半音按序排列构成，属乐理通则
  - 半音化的历史发展（从装饰到和声手段）为音乐史通行记载
updated: 2026-09-23
---

::: zh
半音阶的定义最没有争议：**十二个半音，一个不落，按高低排好**。

> C 半音阶：C C♯ D D♯ E F F♯ G G♯ A A♯ B C

它与所有其他音阶的关系是**材料与选择**的关系：其他音阶是**从它里面挑几个**，
它本身是"全部的可用音高"。

## 它不是调性音阶

| 特征 | 大调音阶 | 半音阶 |
|---|---|---|
| 音数 | 7 | 12 |
| 半音位置 | 只有两处 | 处处都是 |
| 主音 | 明确 | **没有** |
| 用途 | 建立调性 | 提供**经过、装饰、张力**的材料 |

因为每一步都相同，半音阶无法提供"哪里是家"的信息 —— 这也是它常被用来写
**下行叹息**、**上行冲力**或**不安的过渡段**的原因。

## 记法上的两种传统

同一条半音阶，谱面上有不同写法（用升号还是降号、是否重复某个音级名）：

- **和声半音阶**：按调性功能选升或降（上行倾向用升号、下行倾向用降号），
  严格写法下某些音级名会出现两次；
- **现代写法**：一律用升号（或一律用降号），简单但对调性方向提示较少。

这与 [[concept:enharmonic|等音]] 是同一个问题：**听感相同，写法承载功能**。

## 图示：处处都是半音

```svg
<svg viewBox="0 0 640 176" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">上：七声（两处半音）· 下：十二声（处处半音，因而没有方向）</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="11.5" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="48" y="0">D</text><text x="96" y="0">E</text>
      <text x="144" y="0">F</text><text x="192" y="0">G</text><text x="240" y="0">A</text>
      <text x="288" y="0">B</text><text x="336" y="0">C</text>
    </g>
    <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="10" x2="336" y2="10"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="24" y="26">全</text><text x="72" y="26">全</text><text x="120" y="26">半</text>
      <text x="168" y="26">全</text><text x="216" y="26">全</text><text x="264" y="26">全</text>
      <text x="312" y="26">半</text>
    </g>
    <g font-family="Georgia,serif" font-size="11" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="62">C</text><text x="48" y="62">C♯</text><text x="96" y="62">D</text>
      <text x="144" y="62">D♯</text><text x="192" y="62">E</text><text x="240" y="62">F</text>
      <text x="288" y="62">F♯</text><text x="336" y="62">G</text><text x="384" y="62">G♯</text>
      <text x="432" y="62">A</text><text x="480" y="62">A♯</text><text x="528" y="62">B</text>
      <text x="576" y="62">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="2 3">
      <line x1="0" y1="74" x2="576" y2="74"/>
    </g>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      每一步都相同 → 没有"靠向哪里"的信息 → 无法建立调性
    </text>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      与全音音阶的对照：全音阶把八度分成 6 份，半音阶分成 12 份，两者都"没有主音"
    </text>
  </g>
</svg>
```

## 听一听：十二个半音

先听半音阶，再听大调音阶。前者提供的是**材料**，后者提供的是**结构**。

```audiolab
{"type":"scale","notes":["C4","C#4","D4","D#4","E4","F4","F#4","G4","G#4","A4","A#4","B4","C5"],"label":"C 半音阶","label_en":"C chromatic scale","hint":"点「上行」听每一步都一样宽","hint_en":"Try Up — every step is identical","gap":0.24,"dur":0.26}
```

## 常见误解

- **「半音阶是一条调」** → 它没有主音，不能建立调性，只提供材料。
- **「半音阶就是全音阶的反面」** → 两者都把八度等分（12 份 / 6 份），因而**都缺少调性所需的不等距结构**。
- **「写升记号和写降记号一样」** → 听感相同，但写法提示方向（上行倾向用升号、下行用降号），见 [[concept:enharmonic|等音]]。
- **「半音阶是近代才有的」** → 材料自古就有（古希腊的四音列里已含半音）；近代的是把它当作和声手段系统使用。
:::

::: en
The chromatic scale has the least contentious definition of all: **twelve semitones, none omitted, in order.**

> C chromatic: C C♯ D D♯ E F F♯ G G♯ A A♯ B C

Its relationship to every other scale is that of **material to selection**: other scales pick a few notes out of
it; it is the full set of available pitches.

## It is not a tonal scale

| Feature | Major scale | Chromatic scale |
|---|---|---|
| Notes | 7 | 12 |
| Semitones | only two | everywhere |
| Tonic | definite | **none** |
| Purpose | to establish a key | to supply **passing, colouring and tension** |

Because every step is identical, the chromatic scale cannot tell the ear where home is — which is exactly why it
gets used for **descending sighs**, **upward surges** and **restless transitions**.

## Two notational traditions

The same scale can be written in different ways (sharps or flats, whether a letter name repeats):

- **Harmonic chromatic**: choose sharps or flats by tonal function (sharps when rising, flats when falling), so
  under a strict reading some letter names appear twice.
- **Modern practice**: all sharps (or all flats), simple but offering less directional information.

This is the same question as [[concept:enharmonic|enharmonic]] spelling: **the sound is identical while the
writing carries function**.

## Diagram: semitones everywhere

```svg
<svg viewBox="0 0 640 176" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Top: seven notes with two semitones. Bottom: twelve notes, semitones throughout, hence no direction</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="11.5" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="48" y="0">D</text><text x="96" y="0">E</text>
      <text x="144" y="0">F</text><text x="192" y="0">G</text><text x="240" y="0">A</text>
      <text x="288" y="0">B</text><text x="336" y="0">C</text>
    </g>
    <g stroke="#6E6A64" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="10" x2="336" y2="10"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="24" y="26">W</text><text x="72" y="26">W</text><text x="120" y="26">H</text>
      <text x="168" y="26">W</text><text x="216" y="26">W</text><text x="264" y="26">W</text>
      <text x="312" y="26">H</text>
    </g>
    <g font-family="Georgia,serif" font-size="11" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="62">C</text><text x="48" y="62">C♯</text><text x="96" y="62">D</text>
      <text x="144" y="62">D♯</text><text x="192" y="62">E</text><text x="240" y="62">F</text>
      <text x="288" y="62">F♯</text><text x="336" y="62">G</text><text x="384" y="62">G♯</text>
      <text x="432" y="62">A</text><text x="480" y="62">A♯</text><text x="528" y="62">B</text>
      <text x="576" y="62">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="2 3">
      <line x1="0" y1="74" x2="576" y2="74"/>
    </g>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      Every step identical, so no leaning anywhere, so no key can be established
    </text>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Compare the whole-tone scale: six equal parts there, twelve here — neither has a tonic
    </text>
  </g>
</svg>
```

## Listen: twelve semitones

Hear the chromatic scale, then the major scale. The first supplies **material**; the second supplies
**structure**.

```audiolab
{"type":"scale","notes":["C4","C#4","D4","D#4","E4","F4","F#4","G4","G#4","A4","A#4","B4","C5"],"label":"C 半音阶","label_en":"C chromatic scale","hint":"点「上行」听每一步都一样宽","hint_en":"Try Up — every step is identical","gap":0.24,"dur":0.26}
```

## Common misconceptions

- **"The chromatic scale is a key."** It has no tonic and cannot establish one; it supplies material only.
- **"It is the opposite of the whole-tone scale."** Both divide the octave equally (twelve parts and six), so **both lack the unequal structure tonality needs**.
- **"Sharps and flats are interchangeable when writing it."** The sound matches, but spelling signals direction (sharps rising, flats falling) — see [[concept:enharmonic|enharmonic]].
- **"Chromaticism is modern."** The material is ancient (Greek tetrachords already contained semitones); what is modern is its systematic use as a harmonic device.
:::
