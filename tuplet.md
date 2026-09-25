---
id: tuplet
site: theo
cat: T7
title: 连音
title_en: Tuplet
summary: 在"放两个音"的位置放三个——因为时值体系是二分的，三没有位置
summary_en: Three notes where two belong — because the duration system divides by two, and three has no place
level: standard
tags: [乐理, 节奏, 记谱]
tags_en: [theory, rhythm, notation]
alias: [连音, 三连音, tuplet, triplet]
order: 18
links:
  - "[[concept:rhythm]]"
  - "[[concept:rhythmic-notation]]"
  - "[[concept:simple-compound-meter]]"
  - "[[concept:metric-accent]]"
  - "[[concept:polyrhythm]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：常见的三连音音阶跑动，可用于听"三等分一拍"的实际效果 | Scale and cadence exercises include triplet runs, letting you hear a beat divided into three
  - thesession-019704 | 《小星星》作对照：全曲只用二分时值，完全没有连音，两者对比最清楚 | Twinkle Little Star uses only binary values with no tuplets at all — the clearest contrast
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：三拍子与连音交替出现，可听"三"在两套体系里的不同身份 | Liszt's transcription of Danse macabre — triple metre and tuplets alternate, showing "three" in two different roles
sources:
  - 连音（tuplet）指在正常时值内改放不同数量的音；三连音为最常用形式，属乐理通则
  - 单拍子/复拍子中"三音"无需连音记号（因拍的单位本身即为三等分），为通行记谱规范
updated: 2026-09-25
---

::: zh
连音的做法是：**在原本"放两个音"的位置，放三个**（或反过来）。

> 常见写法是在符头上标一个数字：`3` 表示三连音，`5` 表示五连音，`7` 表示七连音。

## 为什么需要它：时值体系是二分的

现有的音符时值全部按**除以 2** 生成：

> 全音符 → 二分 → 四分 → 八分 → 十六分 → …

**"三"在这个体系里没有位置。** 所以想在两拍里放三个音，唯一的办法就是**用连音记号临时改变等分方式** ——
它不是"多了一种音符"，而是**暂时借用了另一种划分**。

## 一个必须分清的区分：连音 vs 复拍子里的"三"

这是本条最重要的判断点：

| | 三连音 | 6/8 里的三个八分 |
|---|---|---|
| 每个八分是 | **三分之一拍**（非常规时值） | 常规时值（分母就是 8） |
| 需要连音记号吗 | **需要** | **不需要** |
| 为什么 | 违背了二分的时值体系 | 复拍子本来就把一拍分成三份 |

也就是说：**"三个音一拍"本身不是连音；只有"在不该出现三的地方出现三"才是连音。**
（复拍子的结构见 [[concept:simple-compound-meter|单复混合拍子]]。）

## 常见形式

| 类型 | 含义 | 常见场合 |
|---|---|---|
| **三连音** | 两拍的位置放三个音 | 最常见；抒情线条中的流动感 |
| **五连音 / 七连音** | 四拍的位置放五 / 七个音 | 华彩段、现代作品 |
| **二连音** | 三拍的位置放两个音 | 复拍子里"临时改成单拍"的感觉 |

最后一行的**二连音**很少被提到，但它最能说明连音的本质：
**连音就是"临时借用另一种等分方式"** —— 可以往三走，也可以从三回到二
（见 [[concept:polyrhythm|复节奏]]：多种等分同时存在时，靠的就是这个机制）。

## 演奏上的要点

连音最容易犯的错是"弹得快一点含糊过去"。正确的做法是：

> **先把那一拍当成一个整体，在内部做三等分，而不是"加速塞进三个音"。**

两者的差别在听觉上很明显：前者是**均分**，后者是**前松后紧或前紧后松**。

## 图示：二分体系里的"外来者"

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">时值体系每次除以 2；三只能靠连音"临时借位"</text>
  </g>

  <g transform="translate(52,50)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">二分体系</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="-10" width="480" height="18" rx="2" opacity=".85"/>
    </g>
    <g stroke="#0B0B0C" stroke-width="1.4">
      <line x1="240" y1="-10" x2="240" y2="8"/>
      <line x1="120" y1="-10" x2="120" y2="8"/><line x1="360" y1="-10" x2="360" y2="8"/>
      <line x1="60" y1="-10" x2="60" y2="8"/><line x1="180" y1="-10" x2="180" y2="8"/>
      <line x1="300" y1="-10" x2="300" y2="8"/><line x1="420" y1="-10" x2="420" y2="8"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="490" y="4">÷2 → ÷2 → ÷2 ……</text>
    </g>

    <g transform="translate(0,60)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-20" y="0" text-anchor="end">三连音</text>
      </g>
      <g fill="#E07A3F">
        <rect x="0" y="-10" width="78" height="18" rx="2"/>
        <rect x="80" y="-10" width="78" height="18" rx="2"/>
        <rect x="160" y="-10" width="78" height="18" rx="2"/>
        <rect x="240" y="-10" width="78" height="18" rx="2"/>
        <rect x="320" y="-10" width="78" height="18" rx="2"/>
        <rect x="400" y="-10" width="78" height="18" rx="2"/>
      </g>
      <text x="119" y="-16" font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">3</text>
      <text x="359" y="-16" font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">3</text>
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="490" y="0">两拍的位置放三个音</text>
      </g>
    </g>

    <g transform="translate(0,118)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        分清：6/8 里的三个八分不是连音 —— 复拍子本来就把一拍分成三份，分母就是 8
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        只有当"三"出现在不该出现三的地方，才需要连音记号
      </text>
    </g>
  </g>
</svg>
```

## 听一听：二分与三等分

用 `rhythm` 组件对比**八分均分**（二分体系）与**三连音**（三等分）。
请留意三连音那种"转起来"的感觉 —— 那就是"三"与"二"在听感上的本质差别。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"e e e e e e e e","bpm":76,"label":"二分体系：八分均分","label_en":"Binary: even eighths","hint":"点「播放」，先听二分的规整","hint_en":"Press play and hear the binary regularity first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"t t t t t t t t t t t t","bpm":76,"label":"三等分：三连音","label_en":"Division by three: triplets","hint":"与上一条对比：同样的时间，分成三份","hint_en":"Against the item above — the same time divided into three"}
```

## 常见误解

- **「三连音就是三个音弹快一点」** → 关键是**均分**：那一拍被分成三等份，而不是"加速塞进去"。
- **「6/8 里的三个八分是三连音」** → 不是。那只是复拍子的常规时值，不需要连音记号。
- **「连音只有三连音」** → 五连、七连、二连都存在，本质都是"临时借用另一种等分方式"。
- **「连音会让节拍乱掉」** → 不会：连音**从属于**所在的拍，只是把那一拍内部分成三份（见 [[concept:metric-accent|强弱规律]] 里的"需要先有一个明确的拍"）。
:::

::: en
A tuplet does this: **where two notes would normally fit, three appear** (or the reverse).

> It is written by placing a number on the note group: `3` for a triplet, `5` for a quintuplet, `7` for a septuplet.

## Why it is needed: the duration system is binary

Every note value is generated by **dividing by two**:

> whole → half → quarter → eighth → sixteenth → …

**"Three" has no place in that system.** So to put three notes into the space of two, the only option is to
**temporarily change the division** — a tuplet is not "a new kind of note" but a **borrowed division**.

## A distinction you must keep straight: tuplets versus the "threes" of compound metre

This is the key point of this entry:

| | A triplet | Three eighths in 6/8 |
|---|---|---|
| Each eighth is | **one third of a beat** (an irregular value) | an ordinary value (the denominator is 8) |
| Tuplet marking needed? | **yes** | **no** |
| Why | it contradicts the binary duration system | compound metre already divides the beat in three |

In other words: **"three notes to a beat" is not a tuplet by itself; a tuplet exists only when a three appears
where three should not.** (For the structure behind this, see
[[concept:simple-compound-meter|simple, compound and irregular metre]].)

## Common forms

| Type | Meaning | Typical use |
|---|---|---|
| **triplet** | three notes in the space of two | commonest; a sense of flow in a lyrical line |
| **quintuplet / septuplet** | five or seven notes in the space of four | cadenzas, contemporary music |
| **duplet** | two notes in the space of three | the "temporarily simple" feel inside compound metre |

The **duplet** in the last row is rarely mentioned but shows the essence best: **a tuplet is a temporary borrowing
of a different division** — it can go towards three, and it can come back from three to two (see
[[concept:polyrhythm|polyrhythm]], where several divisions sound at once by the same mechanism).

## A performance point

The commonest mistake is to fudge a tuplet by playing it faster. The right approach is:

> **Treat that beat as one whole and divide it internally into three, rather than "speeding up to squeeze three
> notes in".**

The difference is clearly audible: the first is **even**, the second is loose-then-tight or the reverse.

## Diagram: an outsider inside a binary system

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The duration system halves every time; three can only be borrowed by a tuplet</text>
  </g>

  <g transform="translate(52,50)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">binary</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="-10" width="480" height="18" rx="2" opacity=".85"/>
    </g>
    <g stroke="#0B0B0C" stroke-width="1.4">
      <line x1="240" y1="-10" x2="240" y2="8"/>
      <line x1="120" y1="-10" x2="120" y2="8"/><line x1="360" y1="-10" x2="360" y2="8"/>
      <line x1="60" y1="-10" x2="60" y2="8"/><line x1="180" y1="-10" x2="180" y2="8"/>
      <line x1="300" y1="-10" x2="300" y2="8"/><line x1="420" y1="-10" x2="420" y2="8"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="490" y="4">÷2 → ÷2 → ÷2 …</text>
    </g>

    <g transform="translate(0,60)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-20" y="0" text-anchor="end">triplet</text>
      </g>
      <g fill="#E07A3F">
        <rect x="0" y="-10" width="78" height="18" rx="2"/>
        <rect x="80" y="-10" width="78" height="18" rx="2"/>
        <rect x="160" y="-10" width="78" height="18" rx="2"/>
        <rect x="240" y="-10" width="78" height="18" rx="2"/>
        <rect x="320" y="-10" width="78" height="18" rx="2"/>
        <rect x="400" y="-10" width="78" height="18" rx="2"/>
      </g>
      <text x="119" y="-16" font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">3</text>
      <text x="359" y="-16" font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">3</text>
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="490" y="0">three notes where two belong</text>
      </g>
    </g>

    <g transform="translate(0,118)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        Keep it straight: three eighths in 6/8 are not a tuplet — compound metre already divides the beat in three
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        A tuplet marking is needed only when a three appears where three should not
      </text>
    </g>
  </g>
</svg>
```

## Listen: division by two and by three

Use the `rhythm` component to compare **even eighths** (the binary system) with **triplets** (division by three).
Notice the "turning" quality of the triplets — that is the essential difference between three and two.

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"e e e e e e e e","bpm":76,"label":"二分体系：八分均分","label_en":"Binary: even eighths","hint":"点「播放」，先听二分的规整","hint_en":"Press play and hear the binary regularity first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"t t t t t t t t t t t t","bpm":76,"label":"三等分：三连音","label_en":"Division by three: triplets","hint":"与上一条对比：同样的时间分成三份","hint_en":"Against the item above — the same time divided into three"}
```

## Common misconceptions

- **"A triplet is just three notes played faster."** The point is **even division**: the beat is split in three, not
  three notes hurried into it.
- **"Three eighths in 6/8 are a triplet."** They are not; they are ordinary durations in a compound metre and need
  no tuplet marking.
- **"Triplets are the only tuplet."** Quintuplets, septuplets and duplets all exist; all are temporary borrowings of
  a different division.
- **"Tuplets wreck the metre."** They do not: a tuplet **belongs to** its beat and only divides that beat in three
  (see the note under [[concept:metric-accent|metric accent]] that an established beat is required).
:::
