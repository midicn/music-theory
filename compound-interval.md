---
id: compound-interval
site: theo
cat: T2
title: 单音程与复音程
title_en: Simple and Compound Intervals
summary: 八度以内叫单音程，超出八度就是复音程
summary_en: Intervals within an octave are simple; anything wider than an octave is compound
level: standard
tags: [乐理, 音程, 基础]
tags_en: [theory, interval, basics]
alias: [复音程, 单音程, compound interval]
order: 22
links:
  - "[[concept:interval]]"
  - "[[concept:octave]]"
  - "[[concept:interval-number]]"
  - "[[concept:register]]"
instances:
  - atepp-003869 | 月光奏鸣曲第一乐章：右手的琶音音型在一个乐句里跨过两个八度以上，是最典型的复音程材料 | The first movement of the Moonlight Sonata — a single arpeggio figure spans more than two octaves, textbook compound-interval material
  - mutopia-000287 | 巴赫第八首二部创意曲：两个声部经常拉开到八度以上，单音程与复音程在同一句里交替 | Bach's eighth two-part invention — the voices often stretch beyond an octave, so simple and compound alternate inside one phrase
  - giantmidi-006222 | 音阶与琶音练习在八度上下往返，正好是单音程与复音程的分界线 | Scale and arpeggio exercises cross the octave boundary repeatedly — the line between simple and compound
sources:
  - 单音程（八度以内）与复音程（超出八度）的划分，属乐理通则
  - 复音程"减 7 得单音程"的换算方法为通行表述，本文行文为原创
updated: 2026-09-23
---

::: zh
两个人音之间的距离超过一个八度时，命名要换一套算法。八度以内的叫**单音程**，
超出八度的叫**复音程**。

## 复音程怎么读

复音程的名字 = **单音程名 + （几）个八度**：

| 实际音程 | 读法 | 也可以读成 |
|---|---|---|
| C → 上方 D（高九度） | 大九度 | 大二度 + 一个八度 |
| C → 上方 E（高十度） | 大十度 | 大三度 + 一个八度 |
| C → 上方 G（高十二度） | 纯十二度 | 纯五度 + 一个八度 |

看名字能直接换算：**把复音程的度数减 7，就回到单音程**（大九度 → 大二度、
纯十二度 → 纯五度）。所以复音程并不增加新的听辨类型，它只是把已经会的东西**抬了一个八度**。

## 为什么还需要这套说法

因为在写作里，"跳一个九度"和"跳一个二度"是两件事：

- **单音程**决定旋律的轮廓 —— 级进还是跳进；
- **复音程**决定声部之间的空间 —— 两个声部是贴着写还是拉得很开。

同一段素材，把上方声部整体抬一个八度，音程全部"加 7"，旋律听起来还是那条，
但两个声部之间的距离感完全改变。这属于 [[concept:register|音区]] 与配器的问题。

## 图示：减 7 就回到单音程

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">下方为单音程，上方为同一个音程抬一个八度后的复音程</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C4</text><text x="120" y="0">E4</text>
      <text x="0" y="72">C4</text><text x="240" y="72">E5</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="16" x2="120" y2="16"/>
      <line x1="0" y1="12" x2="0" y2="20"/><line x1="120" y1="12" x2="120" y2="20"/>
    </g>
    <text x="130" y="20" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">大三度（单音程）</text>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="52" x2="240" y2="52"/>
      <line x1="0" y1="48" x2="0" y2="56"/><line x1="240" y1="48" x2="240" y2="56"/>
      <line x1="120" y1="40" x2="120" y2="64" stroke-dasharray="2 3"/>
    </g>
    <text x="250" y="56" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">大十度 = 大三度 + 一个八度</text>
    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">10 − 7 = 3：复音程度数减 7，回到单音程</text>
  </g>
</svg>
```

## 听一听：抬起一个八度

同一个音程，抬八度前后听起来"是同一件事"，但空间感完全不同。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度（单音程）","label_en":"Major third (simple)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E5 就是大十度（复音程）：度数加 7，性质不变。","hint2_en":"Set b to E5 for a major tenth: degree plus 7, quality unchanged."}
```

## 常见误解

- **「复音程是另一类音程」** → 它只是单音程抬高八度的结果，性质（大/小/纯/增/减）完全不变。
- **「九度听起来比二度难得多」** → 听辨上它就是"二度 + 八度"，先认单音程，再把八度听出来即可。
- **「复音程不能超过两个八度」** → 可以，只是名称会继续加（如两个八度加三度）。演奏上受乐器音域限制，记谱上不受限。
- **「同一度数一定是同一种距离」** → 九度既可能是大九度也可能是小九度，性质仍由单音程那一层决定。
:::

::: en
Once the distance between two notes exceeds an octave, the naming changes method. Anything within an octave is
a **simple interval**; anything wider is a **compound interval**.

## How compound intervals are read

A compound name is the simple name **plus the number of octaves**:

| Actual interval | Read as | Also read as |
|---|---|---|
| C up to D | major ninth | major second + an octave |
| C up to E | major tenth | major third + an octave |
| C up to G | perfect twelfth | perfect fifth + an octave |

The arithmetic is reversible: **subtract 7 from a compound degree and you are back to a simple interval**
(major ninth → major second; perfect twelfth → perfect fifth). So compound intervals add no new listening
category — they lift something you already know by an octave.

## Why the terminology is needed

Because in writing, "a leap of a ninth" and "a leap of a second" are two different acts:

- **Simple intervals** shape the melodic outline — step or leap;
- **Compound intervals** set the space between voices — written close together or spread far apart.

Take the same material and raise the upper voice by an octave: every interval gains 7, the melody still reads
as the same melody, but the sense of distance between the parts changes completely. That belongs to
[[concept:register|register]] and orchestration.

## Diagram: subtract 7 and the simple interval returns

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Below, a simple interval; above, the same interval lifted an octave</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C4</text><text x="120" y="0">E4</text>
      <text x="0" y="72">C4</text><text x="240" y="72">E5</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="16" x2="120" y2="16"/>
      <line x1="0" y1="12" x2="0" y2="20"/><line x1="120" y1="12" x2="120" y2="20"/>
    </g>
    <text x="130" y="20" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">major third (simple)</text>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="52" x2="240" y2="52"/>
      <line x1="0" y1="48" x2="0" y2="56"/><line x1="240" y1="48" x2="240" y2="56"/>
      <line x1="120" y1="40" x2="120" y2="64" stroke-dasharray="2 3"/>
    </g>
    <text x="250" y="56" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">major tenth = major third + an octave</text>
    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">10 − 7 = 3: subtract 7 from the compound degree to get back</text>
  </g>
</svg>
```

## Listen: lifted by an octave

The same interval before and after an octave lift reads as "the same thing", yet the sense of space differs.

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度（单音程）","label_en":"Major third (simple)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E5 就是大十度（复音程）：度数加 7，性质不变。","hint2_en":"Set b to E5 for a major tenth: degree plus 7, quality unchanged."}
```

## Common misconceptions

- **"A compound interval is a separate category."** It is a simple interval lifted an octave; the quality (major, minor, perfect, augmented, diminished) never changes.
- **"Ninths are much harder to hear than seconds."** It is a second plus an octave. Identify the simple interval first, then hear the octave.
- **"Compound intervals stop at two octaves."** They do not; the name simply keeps adding. Performance limits are the instrument's range, not notation.
- **"One degree number always means one distance."** A ninth can be major or minor; the simple layer decides.
:::
