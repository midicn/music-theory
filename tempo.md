---
id: tempo
site: theo
cat: T7
title: 速度术语与标记
title_en: Tempo Terms and Markings
summary: 从"感觉词"到"每分钟多少拍"——术语的历史就是一部演奏实践史
summary_en: From feeling words to beats per minute — the history of tempo terms is a history of performance practice
level: core
tags: [乐理, 节奏, 历史]
tags_en: [theory, rhythm, history]
alias: [速度, 速度术语, tempo, 快板, 慢板, allegro]
order: 22
links:
  - "[[concept:rhythm]]"
  - "[[concept:metronome]]"
  - "[[concept:meter]]"
  - "[[concept:historical-performance]]"
  - "[[concept:melody]]"
instances:
  - atepp-000195 | 德彪西《月光》：持续的慢速与自由呼吸是它形象的一部分，速度本身就在塑造画面 | Debussy's Clair de lune — sustained slowness and free breathing are part of its image; the tempo is doing the depicting
  - atepp-001928 | 巴赫《半音阶幻想曲与赋格》：幻想曲部分速度变化极大，是"速度作为表情手段"的典型 | Bach's Chromatic Fantasia and Fugue — the fantasia's tempo shifts are extreme, a classic case of tempo as expression
  - giantmidi-006222 | 音阶与终止练习：固定的中速，是所有速度变化的参照基准 | Scale and cadence exercises move at a fixed moderate speed, the baseline against which tempo changes are felt
sources:
  - 速度术语的意大利语体系（largo / adagio / andante / moderato / allegro / presto）及其大致速度区间，属乐理通则
  - 节拍器数字标记由梅尔策尔于 19 世纪初推广；术语的实际速度随时代变化，为音乐史与历史演奏法通行研究结论
updated: 2026-09-25
---

::: zh
速度是"每分钟多少拍"。它的写法有两种，而两种的**可靠性差别很大**：

| 写法 | 例 | 可靠度 |
|---|---|---|
| **数字标记** | `♩ = 96` | **精确**：每分钟 96 个四分音符 |
| **术语** | Allegro（快板） | **大致**：只是"感觉区间" |

## 术语表与大致区间

| 术语 | 中文 | 大致 BPM（四分音符） | 感觉 |
|---|---|---|---|
| **Largo** | 广板 | 40–60 | 极慢、宽广 |
| **Adagio** | 慢板 | 60–76 | 缓慢、从容 |
| **Andante** | 行板 | 76–108 | "行走"的速度 |
| **Moderato** | 中板 | 108–120 | 中等 |
| **Allegro** | 快板 | 120–168 | 明快 |
| **Presto** | 急板 | 168–200 | 极快 |

表里的区间要**当作"大致"看**，原因见下。

## 这件事值得单独讲：术语的实际速度随时代变化

这是本条最有价值的部分。一个被历史演奏法研究确认的结论：

> **同一个术语，在不同时代的实际演奏速度可能相差很大。**

具体情况是：巴洛克时期的 `Adagio` 比 19 世纪的要**慢**得多（当时的记谱习惯、乐器构造、
演奏传统都不同）；而浪漫派作曲家写下 `Allegro` 时，也常因为演奏习惯而比我们今天的理解更快。
这也是为什么今天研究"历史演奏法"的演奏者要**从当时的文献、乐器与记谱惯例反推速度**
（见 [[concept:historical-performance|历史演奏法]]）。

**所以术语不是精确指令，而是"相对快慢 + 性格"的描述**：
它更多在说"这段该有什么气质"，而不是"这一拍要几毫秒"。

## 速度如何改变性格

这是速度最有用的一点 —— 它和 [[concept:rhythm|节奏型]] 是**两个独立的变量**：

| 同一节奏型 | 慢速 | 中速 | 快速 |
|---|---|---|---|
| 附点与长短交替 | 悲叹、庄重 | 行进感 | 紧张、追逐 |
| 四拍均分 | 沉思 | 平稳 | 机械、急促 |

**同一个节奏型换速度就换性格** —— 这说明速度不是"技术参数"，
而是一个**独立的表达维度**（这也正是 [[concept:metronome|节拍器]] 值得单列一条的原因：
它把"速度"从"感觉"变成了"数字"）。

## 图示：术语是区间，不是点

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">术语只是一个区间；数字标记才是一个点</text>
  </g>

  <g transform="translate(52,56)">
    <g stroke="#343439" stroke-width="1"><line x1="0" y1="0" x2="500" y2="0"/></g>
    <g stroke="#343439" stroke-width="1">
      <line x1="0" y1="-5" x2="0" y2="5"/><line x1="125" y1="-5" x2="125" y2="5"/>
      <line x1="250" y1="-5" x2="250" y2="5"/><line x1="375" y1="-5" x2="375" y2="5"/>
      <line x1="500" y1="-5" x2="500" y2="5"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="20">40</text><text x="125" y="20">80</text><text x="250" y="20">120</text>
      <text x="375" y="20">160</text><text x="500" y="20">200</text>
    </g>

    <g transform="translate(0,-20)">
      <rect x="0" y="-8" width="110" height="12" rx="2" fill="#5B7FA8" opacity=".8"/>
      <text x="0" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">Largo</text>
      <rect x="110" y="-8" width="90" height="12" rx="2" fill="#5B7FA8" opacity=".65"/>
      <text x="110" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">Adagio</text>
      <rect x="200" y="-8" width="140" height="12" rx="2" fill="#E8C547" opacity=".8"/>
      <text x="200" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">Andante</text>
      <rect x="340" y="-8" width="140" height="12" rx="2" fill="#E07A3F" opacity=".8"/>
      <text x="340" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">Allegro</text>
      <rect x="480" y="-8" width="80" height="12" rx="2" fill="#C0504A" opacity=".8"/>
      <text x="480" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">Presto</text>
    </g>

    <g transform="translate(268,60)">
      <circle cx="0" cy="0" r="5" fill="#E8C547"/>
      <text x="12" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">数字标记 ♩ = 96：一个点</text>
    </g>

    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      术语说"气质"，数字说"频率" —— 前者是区间，后者是点
    </text>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      ⚠️ 同一术语在不同时代的实际速度可能相差很大（巴洛克的 Adagio 远比 19 世纪慢）
    </text>
    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      所以术语不是精确指令，而是"相对快慢 + 性格"的描述
    </text>
  </g>
</svg>
```

## 听一听：同一节奏型，三档速度

用 `rhythm` 组件听**同一个节奏型**在 60 / 96 / 150 三档速度下的差别。
音符完全一样，感受完全不同 —— 这就是"速度是独立表达维度"的直接证据。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":60,"label":"♩ = 60（慢：沉思）","label_en":"Quarter = 60 — slow, contemplative","hint":"先听慢速，记住感受","hint_en":"Hear the slow version first and hold on to the impression"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":150,"label":"♩ = 150（快：急促）","label_en":"Quarter = 150 — fast, urgent","hint":"与 60 对比：节奏型没变，性格全变","hint_en":"Against 60 — same pattern, different character"}
```

## 常见误解

- **「速度术语有确定的速度」** → 只有大致区间，而且**随时代变化**。巴洛克的 Adagio 与 19 世纪的不是一回事。
- **「数字标记更"科学"所以更好」** → 它更精确，但不一定更忠实于作曲者的意图 —— 19 世纪前的作品本来就没有数字。
- **「速度只是技术问题」** → 它是**独立的表达维度**：同一节奏型换速度就换性格。
- **「节拍器练习必须始终跟节拍器」** → 节拍器是校准工具。音乐里的 rubato（弹性速度）恰恰是**有意偏离**（见 [[concept:metronome|节拍器与 BPM]]）。
:::

::: en
Tempo is "how many beats per minute". It is written two ways, and their **reliability differs sharply**:

| Notation | Example | Reliability |
|---|---|---|
| **numeric marking** | `♩ = 96` | **precise**: 96 quarter notes per minute |
| **term** | Allegro | **approximate**: a "feeling range" |

## The terms and their rough ranges

| Term | Meaning | Rough BPM (quarter) | Feeling |
|---|---|---|---|
| **Largo** | broad | 40–60 | very slow, spacious |
| **Adagio** | slow | 60–76 | slow, unhurried |
| **Andante** | walking | 76–108 | the speed of a walk |
| **Moderato** | moderate | 108–120 | medium |
| **Allegro** | fast | 120–168 | bright |
| **Presto** | very fast | 168–200 | rushing |

Treat those ranges as **rough**, for the reason below.

## The part worth its own paragraph: terms change speed with the era

This is the most valuable point in the entry. A conclusion established by historical performance research:

> **The same term may have been played at very different speeds in different eras.**

Specifically: a Baroque `Adagio` was **far slower** than a nineteenth-century one (notation habits, instrument
construction and playing traditions all differed), and Romantic composers writing `Allegro` were often played
faster than we assume today. That is why performers in the historical-performance movement **reconstruct tempo
from period treatises, instruments and notational conventions** (see
[[concept:historical-performance|historical performance]]).

**So a term is not a precise instruction but a description of "relative speed plus character"**: it says more
about what the passage should feel like than about milliseconds per beat.

## How tempo changes character

This is tempo's most useful property — and it is a **variable independent of** [[concept:rhythm|rhythmic pattern]]:

| Same pattern | Slow | Medium | Fast |
|---|---|---|---|
| dotted long-short alternation | lament, solemnity | marching | tense, pursuing |
| four even quarters | brooding | steady | mechanical, urgent |

**Change the tempo of one pattern and you change its character** — which shows tempo is not a "technical
parameter" but an **independent expressive dimension**. (It is also why the [[concept:metronome|metronome]]
deserves its own entry: it turned speed from a feeling into a number.)

## Diagram: a term is a range, a number is a point

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">A term is a range; a numeric marking is a point</text>
  </g>

  <g transform="translate(52,56)">
    <g stroke="#343439" stroke-width="1"><line x1="0" y1="0" x2="500" y2="0"/></g>
    <g stroke="#343439" stroke-width="1">
      <line x1="0" y1="-5" x2="0" y2="5"/><line x1="125" y1="-5" x2="125" y2="5"/>
      <line x1="250" y1="-5" x2="250" y2="5"/><line x1="375" y1="-5" x2="375" y2="5"/>
      <line x1="500" y1="-5" x2="500" y2="5"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="20">40</text><text x="125" y="20">80</text><text x="250" y="20">120</text>
      <text x="375" y="20">160</text><text x="500" y="20">200</text>
    </g>

    <g transform="translate(0,-20)">
      <rect x="0" y="-8" width="110" height="12" rx="2" fill="#5B7FA8" opacity=".8"/>
      <text x="0" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">Largo</text>
      <rect x="110" y="-8" width="90" height="12" rx="2" fill="#5B7FA8" opacity=".65"/>
      <text x="110" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">Adagio</text>
      <rect x="200" y="-8" width="140" height="12" rx="2" fill="#E8C547" opacity=".8"/>
      <text x="200" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">Andante</text>
      <rect x="340" y="-8" width="140" height="12" rx="2" fill="#E07A3F" opacity=".8"/>
      <text x="340" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">Allegro</text>
      <rect x="480" y="-8" width="80" height="12" rx="2" fill="#C0504A" opacity=".8"/>
      <text x="480" y="-14" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">Presto</text>
    </g>

    <g transform="translate(268,60)">
      <circle cx="0" cy="0" r="5" fill="#E8C547"/>
      <text x="12" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">numeric marking, quarter = 96: a point</text>
    </g>

    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      A term states character, a number states frequency — one is a range, the other a point
    </text>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      The same term may have meant very different speeds in different eras (a Baroque Adagio was far slower)
    </text>
    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      So a term is not a precise instruction but "relative speed plus character"
    </text>
  </g>
</svg>
```

## Listen: one pattern at three speeds

Use `rhythm` to hear **the same pattern** at 60, 96 and 150. The notes are identical; the impression is not —
direct evidence that tempo is an independent expressive dimension.

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":60,"label":"♩ = 60（慢：沉思）","label_en":"Quarter = 60 — slow, contemplative","hint":"先听慢速，记住感受","hint_en":"Hear the slow version first and hold on to the impression"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":150,"label":"♩ = 150（快：急促）","label_en":"Quarter = 150 — fast, urgent","hint":"与 60 对比：节奏型没变，性格全变","hint_en":"Against 60 — same pattern, different character"}
```

## Common misconceptions

- **"Tempo terms have definite speeds."** Only rough ranges, and they **change with the era**. A Baroque Adagio
  and a nineteenth-century one are not the same thing.
- **"Numeric markings are better because they are scientific."** They are more precise, but not necessarily more
  faithful to the composer's intention — music before the nineteenth century had no numbers.
- **"Tempo is a technical matter."** It is an **independent expressive dimension**: one pattern at two tempos is
  two characters.
- **"Practising must always follow the metronome."** The metronome is a calibration tool; rubato is precisely a
  **deliberate departure** from it (see [[concept:metronome|metronome and BPM]]).
:::
