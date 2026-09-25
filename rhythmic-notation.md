---
id: rhythmic-notation
site: theo
cat: T7
title: 节奏记谱
title_en: Notating Rhythm
summary: 音符形状表示的是"比例"，不是绝对秒数——这是读懂一切乐谱的前提
summary_en: Note shapes show proportions, not seconds — the premise for reading any score
level: standard
tags: [乐理, 节奏, 记谱]
tags_en: [theory, rhythm, notation]
alias: [节奏记谱, 时值记号, 附点, 休止符]
order: 34
links:
  - "[[concept:rhythm]]"
  - "[[concept:meter]]"
  - "[[concept:tempo]]"
  - "[[concept:tuplet]]"
  - "[[concept:staff]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：谱面上全是同一种时值，是观察"形状=比例"的最简单材料 | Scale and cadence exercises use a single note value throughout, the simplest material for seeing shape as proportion
  - thesession-019704 | 《小星星》：只用二分与四分两种时值，附点与连线的必要性一目了然 | Twinkle Little Star uses only halves and quarters, making clear when dots and ties are needed
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：复合拍子与连音混排，记谱法的取舍在谱面上非常清楚 | Liszt's transcription of Danse macabre mixes compound metre and tuplets, where notational choices are plain to see
sources:
  - 时值记号以比例关系（全 : 二 : 四 : 八 = 2 : 1 : 1/2 : 1/4）表示长短；绝对时长由速度决定，属记谱法通则
  - 附点、连线、休止符与谱号体系为通行记谱规范
updated: 2026-09-25
---

::: zh
节奏记谱的核心只有一句话：

> **音符形状表示的是"比例关系"，不是绝对秒数。**

一个四分音符是半个二分音符、两倍于八分音符 —— 至于它实际响多久，
**由速度决定**（`♩ = 60` 时是一秒，`♩ = 120` 时是半秒）。

这解释了初学者最常见的困惑："这个音多长？" —— **正确的答案是"它是四分音符"**，
而不是"0.5 秒"。

## 时值体系

| 音符 | 名称 | 相对全音符 |
|---|---|---|
| ○ | 全音符 | 1 |
| ○ + 符干 | 二分音符 | 1/2 |
| 实心 + 符干 | 四分音符 | 1/4 |
| + 一条符尾 | 八分音符 | 1/8 |
| + 两条符尾 | 十六分音符 | 1/16 |

规律很整齐：**每加一条符尾（或加一个符点），时值就减半**。
所以整张表其实是**同一个原则的重复**，不需要死记 —— 记住"符尾越多越短"就够了。

## 三个必要的补充记号

| 记号 | 作用 | 例 |
|---|---|---|
| **附点** | 延长**自身的一半** | `♩.` = 四分 + 八分 = 1.5 拍 |
| **连线**（延音线） | 把两个音**合成一个**（跨小节时必需） | `♩~♪` = 1.5 拍，但音起在小节内 |
| **休止符** | 表示**不发声**的时值（同样是比例） | `𝄽` = 四分休止 |

第二行值得强调：**跨小节的音必须用延音线**，不能写成"一个很长的音" ——
因为小节线是重音周期的标记（见 [[concept:meter|拍号]]），不能为了记谱方便而破坏它。

## 为什么时值要写成"比例"而不是"秒数"

| 若写成秒数 | 后果 |
|---|---|
| 改速度就要重写全谱 | 不现实 |
| 无法表达"伸缩"（rubato） | 音乐会变得机械 |
| 无法跨时代传递 | 巴洛克与今天的演奏速度不同（见 [[concept:tempo|速度术语]]） |

**比例记谱法把"结构"与"执行"分开了** —— 这正是西方记谱体系几百年来稳定的原因：
一份 18 世纪的乐谱，今天仍能读，因为**它的信息是"比例 + 相对时间"，不是"绝对时间"**。

## 图示：形状是比例，长度看速度

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样的四个音符，在两种速度下"响多久"完全不同，但记谱完全一样</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">谱面</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">♩</text><text x="40" y="0">♩</text><text x="80" y="0">♩</text><text x="120" y="0">♩</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="-12" y="10" width="24" height="14" rx="2"/>
      <rect x="28" y="10" width="24" height="14" rx="2"/>
      <rect x="68" y="10" width="24" height="14" rx="2"/>
      <rect x="108" y="10" width="24" height="14" rx="2"/>
    </g>
    <text x="160" y="22" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">记谱：四个四分音符（比例 1:1:1:1）</text>

    <g transform="translate(0,66)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">
        <text x="-20" y="0" text-anchor="end">♩=60</text>
      </g>
      <g fill="#5B7FA8" opacity=".85">
        <rect x="-12" y="-8" width="72" height="16" rx="2"/>
        <rect x="64" y="-8" width="72" height="16" rx="2"/>
        <rect x="140" y="-8" width="72" height="16" rx="2"/>
        <rect x="216" y="-8" width="72" height="16" rx="2"/>
      </g>
      <text x="300" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">每秒一个音（共 4 秒）</text>
    </g>

    <g transform="translate(0,102)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">
        <text x="-20" y="0" text-anchor="end">♩=120</text>
      </g>
      <g fill="#E07A3F" opacity=".85">
        <rect x="-12" y="-8" width="36" height="16" rx="2"/>
        <rect x="28" y="-8" width="36" height="16" rx="2"/>
        <rect x="68" y="-8" width="36" height="16" rx="2"/>
        <rect x="108" y="-8" width="36" height="16" rx="2"/>
      </g>
      <text x="156" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">每秒两个音（共 2 秒）</text>
    </g>

    <text x="0" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      比例记谱法把"结构"与"执行"分开：一份 18 世纪的乐谱今天仍能读
    </text>
    <text x="0" y="156" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      "这个音多长？"的正确回答是"它是四分音符"，不是"0.5 秒"
    </text>
  </g>
</svg>
```

## 听一听：同样的谱面，两种速度

用 `rhythm` 组件听**完全相同的节奏型**在两种速度下的差别。谱面不变，
**"响多久"却翻了一倍** —— 这就是"形状是比例、长度看速度"的直接证明。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":60,"label":"♩ = 60：每个音 1 秒","label_en":"Quarter = 60: one second per note","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":120,"label":"♩ = 120：每个音 0.5 秒","label_en":"Quarter = 120: half a second per note","hint":"与上一条对比：谱面完全一样","hint_en":"Against the item above — identical notation"}
```

## 常见误解

- **「音符形状表示具体的时长」** → 表示**比例**。实际时长由速度决定。
- **「全音符一定比四分音符长 4 倍」** → 比例上是 4 倍，但**绝对秒数取决于速度**（这是两件事）。
- **「长音可以直接写成一个大音符」** → 跨小节的长音**必须用延音线**，否则会破坏小节线的重音标记。
- **「附点是加固定长度」** → 附点是延长**自身的一半**（所以附点四分 ≠ 四分 + 十六分）。
:::

::: en
The core of rhythmic notation is one sentence:

> **A note's shape shows a proportion, not a number of seconds.**

A quarter note is half a half note and twice an eighth — how long it actually sounds is **decided by the tempo**
(one second at `♩ = 60`, half a second at `♩ = 120`).

This explains the beginner's commonest question — "how long is this note?" The right answer is **"it is a quarter
note"**, not "0.5 seconds".

## The system of values

| Note | Name | Relative to a whole |
|---|---|---|
| ○ | whole | 1 |
| ○ + stem | half | 1/2 |
| filled + stem | quarter | 1/4 |
| + one flag | eighth | 1/8 |
| + two flags | sixteenth | 1/16 |

The rule is tidy: **each extra flag (or dot) halves the value.** The whole table is therefore **one principle
repeated** — you need only remember "more flags, shorter note".

## Three necessary additions

| Sign | Function | Example |
|---|---|---|
| **dot** | lengthens by **half its own value** | `♩.` = quarter + eighth = 1.5 beats |
| **tie** | joins two notes **into one** (essential across a bar line) | `♩~♪` = 1.5 beats, starting inside the bar |
| **rest** | a value of **silence** (also a proportion) | `𝄽` = a quarter rest |

The second deserves emphasis: **a note crossing a bar line must use a tie**, never be written as one long note —
because bar lines mark the accent cycle (see [[concept:meter|metre]]) and must not be broken for notational
convenience.

## Why values are proportions rather than seconds

| If values were seconds | Consequence |
|---|---|
| changing tempo would mean rewriting the score | impractical |
| no way to notate stretching (rubato) | music would turn mechanical |
| no transmission across eras | Baroque and modern playing speeds differ (see [[concept:tempo|tempo]]) |

**Proportional notation separates structure from execution** — which is why the Western system has been stable for
centuries: an eighteenth-century score is still readable today because **it carries proportions and relative
time, not absolute time.**

## Diagram: the shape is a proportion, the length depends on tempo

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The same four notes last entirely different times at two tempos, with identical notation</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">score</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">♩</text><text x="40" y="0">♩</text><text x="80" y="0">♩</text><text x="120" y="0">♩</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="-12" y="10" width="24" height="14" rx="2"/>
      <rect x="28" y="10" width="24" height="14" rx="2"/>
      <rect x="68" y="10" width="24" height="14" rx="2"/>
      <rect x="108" y="10" width="24" height="14" rx="2"/>
    </g>
    <text x="160" y="22" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">notation: four quarters (1:1:1:1)</text>

    <g transform="translate(0,66)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">
        <text x="-20" y="0" text-anchor="end">quarter=60</text>
      </g>
      <g fill="#5B7FA8" opacity=".85">
        <rect x="-12" y="-8" width="72" height="16" rx="2"/>
        <rect x="64" y="-8" width="72" height="16" rx="2"/>
        <rect x="140" y="-8" width="72" height="16" rx="2"/>
        <rect x="216" y="-8" width="72" height="16" rx="2"/>
      </g>
      <text x="300" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">one note per second (4 s in all)</text>
    </g>

    <g transform="translate(0,102)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">
        <text x="-20" y="0" text-anchor="end">quarter=120</text>
      </g>
      <g fill="#E07A3F" opacity=".85">
        <rect x="-12" y="-8" width="36" height="16" rx="2"/>
        <rect x="28" y="-8" width="36" height="16" rx="2"/>
        <rect x="68" y="-8" width="36" height="16" rx="2"/>
        <rect x="108" y="-8" width="36" height="16" rx="2"/>
      </g>
      <text x="156" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">two notes per second (2 s in all)</text>
    </g>

    <text x="0" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Proportional notation separates structure from execution, which is why old scores remain readable
    </text>
    <text x="0" y="156" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      "How long is this note?" — the answer is "it is a quarter note", not "0.5 seconds"
    </text>
  </g>
</svg>
```

## Listen: one score, two tempos

Use `rhythm` to hear **the identical pattern** at two tempos. The notation does not change; **the sounding length
doubles** — direct proof that "the shape is a proportion, the length depends on tempo".

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":60,"label":"♩ = 60：每个音 1 秒","label_en":"Quarter = 60: one second per note","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":120,"label":"♩ = 120：每个音 0.5 秒","label_en":"Quarter = 120: half a second per note","hint":"与上一条对比：谱面完全一样","hint_en":"Against the item above — identical notation"}
```

## Common misconceptions

- **"A note shape states a specific duration."** It states a **proportion**; the actual duration follows the tempo.
- **"A whole note is always four times a quarter."** In proportion yes, but the **absolute seconds depend on the
  tempo** — two different statements.
- **"A long note can simply be written as one big note."** A note crossing a bar line **must use a tie**, or the
  bar line's accent marking is broken.
- **"A dot adds a fixed length."** A dot lengthens by **half the note's own value** (so a dotted quarter is not a
  quarter plus a sixteenth).
:::
