---
id: scale-harmony
site: theo
cat: T3
title: 音阶的和声含义
title_en: Scales as Harmony
summary: 音阶不只是旋律材料——在它上面叠三度，就得到调内的和弦家族
summary_en: A scale is not just melodic material — stack thirds on it and a family of chords appears
level: standard
tags: [乐理, 音阶, 和声]
tags_en: [theory, scale, harmony]
alias: [音阶与和声, 调内和弦, diatonic]
order: 54
links:
  - "[[concept:scale]]"
  - "[[concept:major-scale]]"
  - "[[concept:triad]]"
  - "[[concept:chord]]"
  - "[[concept:harmonic-function]]"
  - "[[concept:dorian]]"
instances:
  - giantmidi-006222 | 音阶与琶音练习：琶音正是"在音阶上叠三度"的直接形态，可听出调内和弦的来源 | Scale and arpeggio exercises — an arpeggio is literally stacking thirds on a scale, the direct origin of diatonic chords
  - mutopia-000522 | 《欢乐颂》主题：旋律与它天然相配的和声，都出自同一条音阶 | The Ode to Joy theme — both the melody and the harmony it naturally attracts come from the same scale
  - pdmx-000607 | 《小星星变奏曲》：变奏不断更换和声，但所有和弦都仍在这条音阶内 | The Ah vous variations change harmony constantly, yet every chord stays inside that one scale
sources:
  - 在音阶各音上叠三度即得调内三和弦（大调为 大三/小三/小三/大三/大三/小三/减三），属和声学通则
  - 调式各音上叠三度所得和弦序列不同，为调式和声学的通行表述
updated: 2026-09-23
---

::: zh
前面讲音阶时都在讲**旋律**：音阶是"从十二个半音里挑出来的音"。
这一条讲另一半：**音阶同时决定了和声**。

做法只有一步：**在音阶的每一个音上往上叠三度**（隔一个音取一个），就得到一组和弦。

## 大调音阶上的七个三和弦

| 级数 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| 和弦性质 | **大**三 | 小 | 小 | **大**三 | **大**三 | 小 | **减**三 |
| 罗马数字 | I | ii | iii | IV | V | vi | vii° |

这张表就是**调内和弦**的全部清单。它解释了和声学里几乎所有的基础结论：

- **I、IV、V 是大三和弦** → 所以"主—下属—属"是调性的骨架；
- **只有 vii 是减三和弦** → 所以它不稳定，必须解决；
- **vii 的根音是大调第 7 级（导音）** → 所以它天然指向 I，这是终止式的来源（见 [[concept:cadence|终止式]]）。

**这一切都不是规定，而是音阶结构的必然结果。** 你把大调音阶的结构改了，
和弦序列立刻跟着变 —— 这就是调式各有其和声色彩的原因。

## 换个音阶，换一整套和弦

| 音阶 | 第 1 级和弦 | 特征 |
|---|---|---|
| 大调 | 大三 | 稳定、明亮 |
| 自然小调 | 小三 | 暗，且属和弦是小三 → 推进力弱（故有和声小调） |
| [[concept:dorian|多里亚]] | 小三 | 与自然小调只差第 6 级，但 IV 级和弦变大三 → 最显著的区别 |

也就是说：**说"某调式听起来如何"，一半是在说"它上面能长出哪些和弦"。**

## 图示：叠三度

```svg
<svg viewBox="0 0 640 214" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">在音阶上每隔一个音取一个，就得到一个和弦</text>
  </g>

  <g transform="translate(40,50)">
    <g font-family="Georgia,serif" font-size="11.5" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="14" x2="256" y2="14"/>
      <line x1="0" y1="10" x2="0" y2="18"/><line x1="256" y1="10" x2="256" y2="18"/>
    </g>
    <text x="264" y="18" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">I：C–E–G（大三和弦）</text>
    <g stroke="#5B7FA8" stroke-width="1.4">
      <line x1="64" y1="34" x2="320" y2="34"/>
      <line x1="64" y1="30" x2="64" y2="38"/><line x1="320" y1="30" x2="320" y2="38"/>
    </g>
    <text x="328" y="38" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">ii：D–F–A（小三和弦）</text>
    <g stroke="#E8C547" stroke-width="1.4">
      <line x1="256" y1="54" x2="384" y2="54"/>
      <line x1="256" y1="50" x2="256" y2="58"/><line x1="384" y1="50" x2="384" y2="58"/>
    </g>
    <text x="392" y="58" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">V：属和弦</text>
    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      七个级数依次叠三度 → 大 / 小 / 小 / 大 / 大 / 小 / 减：这就是调内和弦的全部
    </text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      换成小调、多里亚或任何别的音阶，这张表就整张换掉 —— 调式的"色彩"由此而来
    </text>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      和弦的具体构造与转位见和弦类条目；功能与进行见了和声功能与和声进行条目
    </text>
  </g>
</svg>
```

## 听一听：琶音就是竖着弹的音阶

琶音把音阶上的三个音依次弹出 —— 听的时候可以想成"把音阶竖起来"。
这是把旋律材料与和声材料连起来的最短路径。

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"I 级：C 大三和弦","label_en":"Degree I — C major triad","hint":"整体听一声，再分解听构成音","hint_en":"Hear it as a block, then as its separate notes"}
```

## 常见误解

- **「音阶只管旋律」** → 音阶同时决定可用的和弦。改了音阶，整套和声都变。
- **「调内和弦是规定出来的」** → 它是叠三度的必然结果，不是人为规定。
- **「小调的属和弦和小调一样是小三和弦」** → 自然小调如此，但实际写作里几乎都会把第 7 级升上去得到**大**三和弦（[[concept:harmonic-minor|和声小调]]），否则终止式立不住。
- **「所有调式都有同样的和弦序列」** → 完全不同。多里亚与自然小调在旋律上只差一个音，但在和弦上会多出一个大三和弦。
:::

::: en
Everything said about scales so far concerned **melody**: a scale is a selection of pitches. This entry covers the
other half: **a scale also decides the harmony.**

One step is all it takes: **stack thirds above each note of the scale** (take every other note) and a set of
chords appears.

## The seven triads on a major scale

| Degree | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| Quality | **major** | minor | minor | **major** | **major** | minor | **diminished** |
| Roman | I | ii | iii | IV | V | vi | vii° |

This table is the complete inventory of **diatonic chords**, and it accounts for almost every basic conclusion in
harmony:

- **I, IV and V are major** → so tonic, subdominant and dominant form the tonal skeleton;
- **only vii is diminished** → so it is unstable and must resolve;
- **vii's root is the seventh degree (the leading tone)** → so it points at I, which is where cadences come from
  (see [[concept:cadence|cadence]]).

**None of this is a rule imposed from outside; all of it follows from the scale's structure.** Change the
structure and the chord sequence changes with it — which is why each mode has its own harmonic colour.

## Change the scale, change the whole chord set

| Scale | Chord on degree 1 | Character |
|---|---|---|
| major | major | stable, bright |
| natural minor | minor | dark, and its dominant is minor → weak pull (hence harmonic minor) |
| [[concept:dorian|Dorian]] | minor | one note from natural minor, but its IV becomes major — the most striking difference |

In other words: **saying how a mode sounds is half saying which chords can grow on it.**

## Diagram: stacking thirds

```svg
<svg viewBox="0 0 640 214" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Take every other note of the scale and a chord appears</text>
  </g>

  <g transform="translate(40,50)">
    <g font-family="Georgia,serif" font-size="11.5" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="14" x2="256" y2="14"/>
      <line x1="0" y1="10" x2="0" y2="18"/><line x1="256" y1="10" x2="256" y2="18"/>
    </g>
    <text x="264" y="18" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">I: C–E–G, major</text>
    <g stroke="#5B7FA8" stroke-width="1.4">
      <line x1="64" y1="34" x2="320" y2="34"/>
      <line x1="64" y1="30" x2="64" y2="38"/><line x1="320" y1="30" x2="320" y2="38"/>
    </g>
    <text x="328" y="38" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">ii: D–F–A, minor</text>
    <g stroke="#E8C547" stroke-width="1.4">
      <line x1="256" y1="54" x2="384" y2="54"/>
      <line x1="256" y1="50" x2="256" y2="58"/><line x1="384" y1="50" x2="384" y2="58"/>
    </g>
    <text x="392" y="58" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">V: the dominant</text>
    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Stacking thirds on all seven degrees gives major / minor / minor / major / major / minor / diminished
    </text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Switch to minor, Dorian or any other scale and the whole table changes — that is a mode's colour
    </text>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Chord construction and inversion belong to the chord entries; function and progressions to harmony
    </text>
  </g>
</svg>
```

## Listen: an arpeggio is a scale stood on end

An arpeggio plays three notes of the scale in turn — think of it as tipping the scale upright. It is the shortest
path connecting melodic material to harmonic material.

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"I 级：C 大三和弦","label_en":"Degree I — C major triad","hint":"整体听一声，再分解听构成音","hint_en":"Hear it as a block, then as its separate notes"}
```

## Common misconceptions

- **"A scale is only about melody."** It also fixes which chords are available; change the scale and the whole harmony changes.
- **"Diatonic chords are a set of rules."** They are the necessary result of stacking thirds.
- **"A minor key's dominant is a minor triad."** True of natural minor, but in practice the seventh is almost always raised to give a **major** dominant ([[concept:harmonic-minor|harmonic minor]]), or cadences will not hold.
- **"Every mode has the same chord sequence."** They are all different. Dorian and natural minor differ by one melodic note but Dorian gains a major triad where minor has a minor one.
:::
