---
id: artificial-scale
site: theo
cat: T3
title: 人工音阶
title_en: Artificial Scale
summary: 不是从传统长出来的，而是按某个想法造出来的
summary_en: Not grown from tradition but built from an idea
level: standard
tags: [乐理, 音阶, 人工音阶]
tags_en: [theory, scale, artificial]
alias: [人工音阶, artificial scale, 合成音阶]
order: 52
links:
  - "[[concept:scale]]"
  - "[[concept:whole-tone]]"
  - "[[concept:octatonic]]"
  - "[[concept:blues-scale]]"
  - "[[concept:chromatic]]"
instances:
  - giantmidi-006222 | 音阶练习可按需弹出各种结构，是把"人工音阶"听成实感的最便利用法 | Scale exercises can play any structure on demand, the handiest way to hear an artificial scale as a real thing
  - atepp-000082 | 斯克里亚宾晚期作品：和声建立在自创的音高集合上，是"造音阶"最典型的实例 | Late Scriabin — harmony built on a self-devised pitch collection, the clearest instance of inventing a scale
  - atepp-000121 | 德彪西练习曲：同一时期的作曲家也在为特定效果选配音高材料 | Debussy's études — a contemporary likewise choosing pitch material for particular effects
sources:
  - 人工音阶指不源自传统调式体系、按特定音程设计构成的音阶，属乐理通则
  - 全音音阶、八声音阶、蓝调音阶常被归入人工音阶一类，为通行分类表述
updated: 2026-09-23
---

::: zh
前面几条（[[concept:whole-tone|全音音阶]]、[[concept:octatonic|八声音阶]]、[[concept:blues-scale|蓝调音阶]]）
其实都属于同一类：**人工音阶** —— 它们不是从传统调式体系里慢慢长出来的，
而是**按某个明确的音程想法造出来的**。

## 判断标准：它是"长出来的"还是"造出来的"

| | 传统音阶 | 人工音阶 |
|---|---|---|
| 来源 | 长期实践中逐渐定型 | 由某条规则（或某个效果目标）设计 |
| 结构 | 通常不等距、有明确的音级功能 | 常等距或高度对称 |
| 代表 | 大调、小调、教会调式、五声 | 全音、八声、蓝调、各种自创集合 |

**这条界线不是价值判断**：人工音阶同样能写出一流的作品，只是它要求作曲者
自己定义"什么算协和、什么算解决"，因为传统里没有现成答案。

## 常见的人工构造思路

| 思路 | 做法 | 例子 |
|---|---|---|
| **等分** | 把八度等分成若干份 | 全音音阶（6 份）、半音阶（12 份） |
| **交替** | 两种步幅固定交替 | 八声音阶（全半交替） |
| **对称** | 结构在某点镜像 | 八声音阶、某些自创集合 |
| **插入** | 在既有音阶里加一个冲突音 | 蓝调音阶（五声 + 降五度） |
| **拼合** | 两个结构和在一起 | 用两条减七和弦拼出八声音阶 |

## 它为什么值得单独讲

因为**从 20 世纪起，"选材料"本身成了作曲的一部分**。传统音阶提供的是现成的语汇，
人工音阶提供的是一张白纸 —— 用哪个、怎么用，全部要自己决定。
这也是本站把它单列成条的原因：它不是"怪音阶"，而是一种**创作方法**。

## 图示：五种构造思路

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">人工音阶的五种常见构造思路（黑点 = 音阶取用的音）</text>
  </g>

  <g transform="translate(32,48)">
    <g fill="#343439">
      <rect x="0" y="0" width="560" height="10" rx="2"/>
      <rect x="0" y="40" width="560" height="10" rx="2"/>
      <rect x="0" y="80" width="560" height="10" rx="2"/>
      <rect x="0" y="120" width="560" height="10" rx="2"/>
    </g>
    <g fill="#E07A3F">
      <circle cx="0" cy="5" r="4"/><circle cx="93" cy="5" r="4"/><circle cx="187" cy="5" r="4"/>
      <circle cx="280" cy="5" r="4"/><circle cx="373" cy="5" r="4"/><circle cx="467" cy="5" r="4"/>

      <circle cx="0" cy="45" r="4"/><circle cx="93" cy="45" r="4"/><circle cx="140" cy="45" r="4"/>
      <circle cx="233" cy="45" r="4"/><circle cx="280" cy="45" r="4"/><circle cx="373" cy="45" r="4"/>
      <circle cx="420" cy="45" r="4"/><circle cx="513" cy="45" r="4"/>

      <circle cx="0" cy="85" r="4"/><circle cx="47" cy="85" r="4"/><circle cx="187" cy="85" r="4"/>
      <circle cx="280" cy="85" r="4"/><circle cx="327" cy="85" r="4"/>

      <circle cx="0" cy="125" r="4"/><circle cx="140" cy="125" r="4"/><circle cx="280" cy="125" r="4"/>
      <circle cx="373" cy="125" r="4"/><circle cx="513" cy="125" r="4"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="28">① 等分：六份 → 全音音阶</text>
      <text x="0" y="68">② 交替：全半反复 → 八声音阶</text>
      <text x="0" y="108">③ 插入：五声里加一个降五度 → 蓝调音阶</text>
      <text x="0" y="148">④ 拼合：两条减七和弦 → 八声音阶（另一种看法）</text>
      <text x="0" y="168" fill="#5B7FA8">⑤ 自创集合：按作曲者自己的音程设计（20 世纪后最常见）</text>
    </g>
  </g>
</svg>
```

## 听一听：一条自造的音阶

下面这条不是任何传统音阶，而是按"全半全全半全全"以外的步幅拼出来的 ——
存在库里、能听、能复现。人工音阶的关键从来不是稀有，而是**可被明确定义**。

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","G4","Ab4","B4","C5"],"label":"一条六声自造音阶（示例）","label_en":"A six-note invented scale (example)","hint":"点「上行」：这条音阶不属于任何传统体系，但每一步都清楚可复述","hint_en":"Try Up — it belongs to no tradition, yet every step is definite and repeatable","gap":0.38}
```

## 常见误解

- **「人工音阶不自然是坏东西」** → "人工"只说明来源方式，不说明质量。全音音阶与蓝调音阶都属此列。
- **「传统音阶就是自然生成的」** → 也是长期选择与习惯的结果；"传统"与"自然"不是一回事。
- **「人工音阶必须很复杂」** → 蓝调音阶只比五声多一个音，同样算是人工构造。
- **「用人工音阶就没有调性」** → 可以有意保留主音与中心音；是否有中心由用法决定，不由音阶是否"传统"决定。
:::

::: en
The preceding entries ([[concept:whole-tone|whole-tone]], [[concept:octatonic|octatonic]],
[[concept:blues-scale|blues]]) all belong to one family: **artificial scales** — not grown slowly out of a
traditional modal system, but **built from an explicit interval idea**.

## How to tell grown from built

| | Traditional scale | Artificial scale |
|---|---|---|
| Origin | settled gradually through practice | designed from a rule or a target effect |
| Structure | usually unequal, with clear degrees and functions | often equidistant or highly symmetrical |
| Examples | major, minor, church modes, pentatonic | whole tone, octatonic, blues, invented collections |

**This line is not a value judgement.** Artificial scales can carry first-rate music; they simply require the
composer to define what counts as consonance and resolution, because tradition supplies no ready answer.

## Common construction ideas

| Idea | Method | Example |
|---|---|---|
| **equal division** | split the octave into equal parts | whole tone (6), chromatic (12) |
| **alternation** | repeat two step sizes | octatonic (whole, half) |
| **symmetry** | mirror the structure at a point | octatonic, some invented collections |
| **insertion** | add a clashing note to an existing scale | blues (pentatonic plus a lowered fifth) |
| **combination** | merge two structures | two diminished sevenths make the octatonic |

## Why it deserves its own entry

Because **from the twentieth century onward, choosing the material became part of composing.** Traditional
scales hand you a ready vocabulary; an artificial scale hands you a blank page — which notes, used how, is all
down to you. That is why this is a separate entry: not a curiosity, but a **method of composition**.

## Diagram: five construction ideas

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Five common ways artificial scales are built (dot = a note used by the scale)</text>
  </g>

  <g transform="translate(32,48)">
    <g fill="#343439">
      <rect x="0" y="0" width="560" height="10" rx="2"/>
      <rect x="0" y="40" width="560" height="10" rx="2"/>
      <rect x="0" y="80" width="560" height="10" rx="2"/>
      <rect x="0" y="120" width="560" height="10" rx="2"/>
    </g>
    <g fill="#E07A3F">
      <circle cx="0" cy="5" r="4"/><circle cx="93" cy="5" r="4"/><circle cx="187" cy="5" r="4"/>
      <circle cx="280" cy="5" r="4"/><circle cx="373" cy="5" r="4"/><circle cx="467" cy="5" r="4"/>

      <circle cx="0" cy="45" r="4"/><circle cx="93" cy="45" r="4"/><circle cx="140" cy="45" r="4"/>
      <circle cx="233" cy="45" r="4"/><circle cx="280" cy="45" r="4"/><circle cx="373" cy="45" r="4"/>
      <circle cx="420" cy="45" r="4"/><circle cx="513" cy="45" r="4"/>

      <circle cx="0" cy="85" r="4"/><circle cx="47" cy="85" r="4"/><circle cx="187" cy="85" r="4"/>
      <circle cx="280" cy="85" r="4"/><circle cx="327" cy="85" r="4"/>

      <circle cx="0" cy="125" r="4"/><circle cx="140" cy="125" r="4"/><circle cx="280" cy="125" r="4"/>
      <circle cx="373" cy="125" r="4"/><circle cx="513" cy="125" r="4"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="28">1) equal division: six parts → whole tone</text>
      <text x="0" y="68">2) alternation: whole, half, repeating → octatonic</text>
      <text x="0" y="108">3) insertion: a lowered fifth added to the pentatonic → blues</text>
      <text x="0" y="148">4) combination: two diminished sevenths → the octatonic again</text>
      <text x="0" y="168" fill="#5B7FA8">5) invented collections: the composer's own interval design</text>
    </g>
  </g>
</svg>
```

## Listen: an invented scale

The line below belongs to no tradition — it is assembled from a step pattern of its own. It exists in the
library, plays, and can be repeated exactly. The point of an artificial scale is never rarity; it is
**being precisely definable**.

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","G4","Ab4","B4","C5"],"label":"一条六声自造音阶（示例）","label_en":"A six-note invented scale (example)","hint":"点「上行」：这条音阶不属于任何传统体系，但每一步都清楚可复述","hint_en":"Try Up — it belongs to no tradition, yet every step is definite and repeatable","gap":0.38}
```

## Common misconceptions

- **"Artificial means unnatural and therefore worse."** "Artificial" describes how it came about, not its quality. The whole-tone and blues scales are both artificial.
- **"Traditional scales are natural."** They too are the result of long selection and habit; traditional and natural are not the same thing.
- **"Artificial scales must be complicated."** The blues scale is a pentatonic plus one note — artificial all the same.
- **"An artificial scale destroys tonality."** A tonic and a centre can be kept deliberately; whether there is a centre depends on use, not on whether the scale is traditional.
:::
