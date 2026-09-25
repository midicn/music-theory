---
id: chord-inversion
site: theo
cat: T4
title: 和弦转位与数字低音
title_en: Chord Inversion and Figured Bass
summary: 换一个音当最低音——和弦名称不变，听感与功能全变
summary_en: Put a different chord tone in the bass — the name holds, the sound and function change
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [和弦转位, 数字低音, 通奏低音, figured bass, 六和弦]
order: 42
links:
  - "[[concept:chord]]"
  - "[[concept:triad]]"
  - "[[concept:seventh-chord]]"
  - "[[concept:chord-voicing]]"
  - "[[concept:interval-inversion]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：低音部不断在根音、三音、五音之间走动，转位造成的功能变化清晰可辨 | Bach's first two-part invention — the bass moves between root, third and fifth, making the functional effect of inversion audible
  - giantmidi-006222 | 琶音练习可弹出同一和弦的各种转位，用于听"低音换了、和弦没换"这件事 | Scale exercises can sound the same chord in different inversions — the bass changes while the chord does not
  - atepp-000318 | a 小调奏鸣曲：低音线条的走向大量依赖转位，是本条最直接的实例 | A sonata in A minor — the bass line relies heavily on inversions throughout
sources:
  - 转位 = 把和弦中除根音外的音放在最低声部；三和弦有两个转位、七和弦有三个，属和声学通则
  - 低音位置标记法在数字低音（通奏低音）体系中的写法（6 / 6-4 / 7 / 6-5 / 4-3 / 4-2），为通行乐理表述
updated: 2026-09-24
---

::: zh
转位只做一件事：**换一个音放到最低声部**。和弦的名字不变，但听感会变。

> 原位：C 在最低 → C–E–G
> 第一转位：E 在最低 → **E**–G–C
> 第二转位：G 在最低 → **G**–C–E

三种情况的**构成音完全相同**，差别只在"谁在最下面"。这一个差别带来两件重要的事：

1. **低音线条变得平滑** —— 不必总跳回根音，低音可以级进；
2. **功能重心移动** —— 同一个和弦放在不同低音上，稳定性与倾向都不同。

## 数字低音的来历

在通奏低音（巴洛克时期）时代，作曲者只写低音线，并在下方标数字，指示"这个低音上方要加哪些音"。
数字因此天然表达了转位：

| 低音位置 | 数字 | 含义 | 例（C 和弦） |
|---|---|---|---|
| 根音 | 7 / 无 | 原位 | C 在低音 |
| 三音 | **6** | 第一转位（三度与六度） | E 在低音 |
| 五音 | **6-4** | 第二转位（六度与四度） | G 在低音 |
| 七音 | **4-2** | 七和弦第三转位 | B 在低音 |

七和弦的另外两个转位记作 **6-5**（第一转位）与 **4-3**（第二转位）。
这套数字今天仍被用来分析，因为它比"第几转位"更直接地说明**低音上叠了什么音**。

## 转位不是"把音换个顺序"这么简单

最常见的误解是把它当成排列游戏。实际上转位承担明确的功能：

| 转位 | 常见作用 |
|---|---|
| **6**（三音在低音） | 让低音级进，弱化根音的"落点感"，使进行更连贯 |
| **6-4**（五音在低音） | 稳定感最弱，常用于**终止式中的装饰**或在持续低音上形成张力 |
| **4-2**（七音在低音） | 张力最大，因为最不稳定的音被放在最显眼的位置 |

一句话：**转位把"和弦是什么"与"低音是什么"这两件事拆开了**，这正是低音写作能独立成形的原因。

## 与音程转位的区分

[[concept:interval-inversion|音程转位]]是"把音程的上下颠倒"；和弦转位是"把和弦的某个音移低一个八度当低音"。
两者都改变上下关系，但作用对象不同：一个作用于两个音之间的距离，一个作用于整个和弦的低音位置。

## 图示：同一个和弦的三种位置

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">构成音相同，最低音不同 —— 数字低音就是给"最低音是谁"编码</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="0" y="24" fill="#6E6A64">E</text><text x="0" y="48" fill="#6E6A64">G</text>
      <text x="150" y="0" fill="#6E6A64">C</text><text x="150" y="24" fill="#5B7FA8">E</text><text x="150" y="48" fill="#6E6A64">G</text>
      <text x="300" y="0" fill="#6E6A64">C</text><text x="300" y="24" fill="#6E6A64">E</text><text x="300" y="48" fill="#E8C547">G</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.6"><line x1="-16" y1="0" x2="-16" y2="48"/></g>
    <g stroke="#5B7FA8" stroke-width="1.6"><line x1="134" y1="24" x2="134" y2="48"/></g>
    <g stroke="#E8C547" stroke-width="1.6"><line x1="284" y1="48" x2="284" y2="48"/></g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="76" fill="#E07A3F">原位</text>
      <text x="0" y="94" fill="#6E6A64">数字低音：无 / 7</text>
      <text x="150" y="76" fill="#5B7FA8">第一转位</text>
      <text x="150" y="94" fill="#6E6A64">数字低音：6</text>
      <text x="300" y="76" fill="#E8C547">第二转位</text>
      <text x="300" y="94" fill="#6E6A64">数字低音：6-4</text>
    </g>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      低位那条短线 = 最低音。注意越靠右，根音离低音部越远，稳定性越弱
    </text>
  </g>
</svg>
```

## 听一听：转位

同一条 C 大三和弦，三种低音。请留意"落地感"如何随着根音离开低音部而减弱。

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"原位：C 在最低","label_en":"Root position — C in the bass","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":1,"label":"第一转位：E 在最低","label_en":"First inversion — E in the bass","hint":"与上一条对照：构成音相同，低音不同","hint_en":"Compare with the item above — same notes, different bass"}
```

## 常见误解

- **「转位后和弦就变成另一个和弦了」** → 名字与构成音都不变，只有低音位置变。
- **「转位只是把音换个顺序」** → 它承担功能：让低音级进、削弱落点感、或在终止式里制造张力。
- **「数字低音是吉他和弦谱的前身」** → 它指示的是**低音上要叠哪些音**，是作曲与分析的工具，不是伴奏指法。
- **「根音永远是最低音」** → 只有原位才如此。转位里最低音是三音、五音或七音，根音仍叫根音。
:::

::: en
Inversion does one thing: **it puts a different chord tone in the lowest voice.** The chord's name does not
change, but the sound does.

> root position: C lowest → C–E–G
> first inversion: E lowest → **E**–G–C
> second inversion: G lowest → **G**–C–E

All three contain **exactly the same notes**; only the bottom note differs. That one difference matters twice
over:

1. **the bass line becomes smooth** — it need not keep leaping back to the root and can move by step;
2. **the functional centre of gravity moves** — the same chord over a different bass has different stability and
   different tendency.

## Where figured bass comes from

In the continuo era (Baroque) composers wrote only the bass line and put figures under it to say which notes
should sound above. The figures therefore encode inversion directly:

| Bass note | Figure | Meaning | Example (C chord) |
|---|---|---|---|
| root | 7 / none | root position | C in the bass |
| third | **6** | first inversion (a third and a sixth above) | E in the bass |
| fifth | **6-4** | second inversion (a sixth and a fourth) | G in the bass |
| seventh | **4-2** | third inversion of a seventh chord | B in the bass |

The other two inversions of a seventh chord are **6-5** (first) and **4-3** (second). The figures are still used
in analysis today because they state directly **which intervals sit above the bass**, which "first inversion"
does not.

## Inversion is not just reordering

The commonest misreading treats it as a game of arrangement. In fact inversions carry definite functions:

| Inversion | Typical role |
|---|---|
| **6** (third in the bass) | lets the bass move by step, softens the sense of landing, keeps the motion flowing |
| **6-4** (fifth in the bass) | the least stable; common as a decoration inside a cadence or over a sustained bass |
| **4-2** (seventh in the bass) | the most tense, because the least stable note is placed in the most exposed voice |

In one line: **inversion separates "what the chord is" from "what the bass is"** — which is exactly what lets
bass writing become a line in its own right.

## How it differs from interval inversion

[[concept:interval-inversion|Interval inversion]] turns an interval upside down; chord inversion moves one chord
tone down an octave to become the bass. Both change the up-down relation, but of different objects: one of the
distance between two notes, one of the chord's bass position.

## Diagram: one chord, three positions

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same notes, different bass — figured bass simply encodes which note is lowest</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="0" y="24" fill="#6E6A64">E</text><text x="0" y="48" fill="#6E6A64">G</text>
      <text x="150" y="0" fill="#6E6A64">C</text><text x="150" y="24" fill="#5B7FA8">E</text><text x="150" y="48" fill="#6E6A64">G</text>
      <text x="300" y="0" fill="#6E6A64">C</text><text x="300" y="24" fill="#6E6A64">E</text><text x="300" y="48" fill="#E8C547">G</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.6"><line x1="-16" y1="0" x2="-16" y2="48"/></g>
    <g stroke="#5B7FA8" stroke-width="1.6"><line x1="134" y1="24" x2="134" y2="48"/></g>
    <g stroke="#E8C547" stroke-width="1.6"><line x1="284" y1="48" x2="284" y2="48"/></g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="76" fill="#E07A3F">root position</text>
      <text x="0" y="94" fill="#6E6A64">figure: none / 7</text>
      <text x="150" y="76" fill="#5B7FA8">first inversion</text>
      <text x="150" y="94" fill="#6E6A64">figure: 6</text>
      <text x="300" y="76" fill="#E8C547">second inversion</text>
      <text x="300" y="94" fill="#6E6A64">figure: 6-4</text>
    </g>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The short lower line marks the lowest note. Further right, the root sits further from the bass and the chord is less settled
    </text>
  </g>
</svg>
```

## Listen: inversions

One C major triad, three basses. Notice how the sense of landing weakens as the root leaves the bass.

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"原位：C 在最低","label_en":"Root position — C in the bass","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":1,"label":"第一转位：E 在最低","label_en":"First inversion — E in the bass","hint":"与上一条对照：构成音相同，低音不同","hint_en":"Compare with the item above — same notes, different bass"}
```

## Common misconceptions

- **"Inverting turns the chord into a different chord."** Neither the name nor the notes change; only the bass position does.
- **"Inversion is just reordering notes."** It carries function: smoothing the bass, softening the sense of landing, or creating tension inside a cadence.
- **"Figured bass is an early form of chord chart."** It states **which intervals to place above the bass**; it is a tool for composing and analysis, not a fingering chart.
- **"The root is always the lowest note."** Only in root position. In inversions the bass is the third, fifth or seventh — and the root is still the root.
:::
