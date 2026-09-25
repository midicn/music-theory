---
id: dynamics
site: theo
cat: T10
title: 力度记号
title_en: Dynamic Markings
summary: 力度是"相对"的——没有绝对音量，只有相互关系
summary_en: Dynamics are relative — there is no absolute volume, only relations
level: standard
tags: [乐理, 记谱, 实践]
tags_en: [theory, notation, practice]
alias: [力度记号, 力度, 强弱记号, dynamics]
order: 22
links:
  - "[[concept:articulation]]"
  - "[[concept:climax]]"
  - "[[concept:tempo]]"
  - "[[concept:historical-performance]]"
  - "[[concept:register]]"
instances:
  - atepp-000195 | 德彪西《月光》：力度层次细腻而持续偏轻，说明"轻"本身就是一种表达 | Debussy's Clair de lune keeps a delicate, mostly soft dynamic level — proof that "soft" is itself an expression
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：从极轻到极强的巨大跨度贯穿全曲，是力度对比的集中展示 | Liszt's transcription of Danse macabre spans the extremes from very soft to very loud, a concentration of dynamic contrast
  - cyberhymnal-000695 | 管风琴圣咏：力度变化不大，稳定在中强区间，可作对照 | An organ hymn varies little, staying around a moderate level — a useful control
sources:
  - 力度记号体系（pp p mp mf f ff 与渐强渐弱）及其于 18 世纪后的系统化，为记谱法与音乐史通行记载
  - 力度具有相对性（无绝对音量标准），与音区、织体及乐器特性相互影响，为通行演奏教学表述
updated: 2026-09-25
---

::: zh
力度记号看起来最直观，但有一个核心认识必须先说清：

> **力度是相对的 —— 没有绝对音量，只有相互关系。**

同样一个 `p`，在不同作品、不同时代、不同乐器上，实际音量**差别很大**。
所以力度记号的意思是"**相对于本曲其他部分而言**"，而不是"多少分贝"。

## 记号体系

| 记号 | 全称 | 大致感觉 |
|---|---|---|
| **pp** | pianissimo | 极弱 |
| **p** | piano | 弱 |
| **mp** | mezzo-piano | 中弱 |
| **mf** | mezzo-forte | 中强 |
| **f** | forte | 强 |
| **ff** | fortissimo | 极强 |

**渐变**：

| 记号 | 含义 |
|---|---|
| **crescendo**（或用 `<` 伸长的记号） | 渐强 |
| **diminuendo / decrescendo**（`>`） | 渐弱 |

## 它是何时出现的

一个历史事实值得知道：

| 时期 | 力度标记的情况 |
|---|---|
| **文艺复兴与早期巴洛克** | **几乎不标** —— 力度靠乐器、编制与场合自然形成 |
| **18 世纪以后** | 逐渐系统化（与键盘乐器的发展、乐队规模扩大有关） |
| **浪漫派** | 标记极其详尽（`ppp` 到 `fff`、大量渐变） |

**所以"巴洛克作品没有力度标记"不是作曲者不重要力度**，
而是**那个时代的力度不属于需要写下来的信息**（见 [[concept:historical-performance|历史演奏法]]）。

## 三条实务认识

**① 力度不等于音量。**
同一个 `mf`，在低音区听起来比在高音区"更响"（见 [[concept:register|音区]]）。
所以配器时**力度记号的写法要与音区配合**：低音区的 `f` 常常写得更保守。

**② 力度与织体互相影响。**
一个和弦（多人同奏）与一个单音，同样标 `f`，实际厚度差别很大。
**所以"力度"实际是"音响效果"，不只是演奏者的用力程度。**

**③ 渐变的速度与范围都要设计。**
`crescendo` 若从 `p` 到 `f` 只用了半小节，效果是"突强"；若用了八小节，效果是"逐步累积"（见 [[concept:climax|高潮设计]]）。
**渐变的"长度"本身就是表现手段。**

## 与演奏法记号的区别

这两个常被混在一起，但维度不同：

| | 力度记号 | 演奏法记号（见 [[concept:articulation|演奏法记号]]） |
|---|---|---|
| 管什么 | 音**多响** | 音与音**怎么连接** |
| 例 | `f` `p` `<` `>` | 连音线 · 断奏点 · 重音 `>` |

**注意**：重音记号 `>` 与渐弱记号外形相近，但**含义完全不同** ——
重音是**瞬间的**强调，渐弱是**一段时间内的**下降。读谱时要看清它标在音上还是标在音之间。

## 图示：相对关系，不是绝对值

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">力度记号的轴是"相对关系"，没有绝对起点；渐变的长度也是表现手段</text>
  </g>

  <g transform="translate(52,56)">
    <g stroke="#343439" stroke-width="1"><line x1="0" y1="0" x2="480" y2="0"/></g>
    <g stroke="#343439" stroke-width="1">
      <line x1="0" y1="-5" x2="0" y2="5"/><line x1="96" y1="-5" x2="96" y2="5"/>
      <line x1="192" y1="-5" x2="192" y2="5"/><line x1="288" y1="-5" x2="288" y2="5"/>
      <line x1="384" y1="-5" x2="384" y2="5"/><line x1="480" y1="-5" x2="480" y2="5"/>
    </g>
    <g font-family="Georgia,serif" font-size="11" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="20">pp</text><text x="96" y="20">p</text><text x="192" y="20">mp</text>
      <text x="288" y="20">mf</text><text x="384" y="20">f</text><text x="480" y="20">ff</text>
    </g>

    <g transform="translate(0,-24)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">← 这个刻度没有绝对起点</text>
    </g>

    <g transform="translate(0,48)">
      <path d="M0,-10 L180,-10" stroke="#E8C547" stroke-width="1.6"/>
      <path d="M0,-4 L180,-16" stroke="#E8C547" stroke-width="1.6"/>
      <text x="196" y="-10" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">同样 p → f：用八小节（累积）</text>
      <path d="M0,20 L40,20" stroke="#C0504A" stroke-width="1.6"/>
      <path d="M0,26 L40,14" stroke="#C0504A" stroke-width="1.6"/>
      <text x="56" y="20" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">用半小节（突强）——"渐变的长度"就是表现手段</text>
    </g>

    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      力度不等于音量：低音区的 f 听起来比高音区的 f 更响，所以配器时写法要与音区配合
    </text>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      巴洛克几乎不标力度 —— 不是不重要，而是那个时代的力度不属于"需要写下来"的信息
    </text>
  </g>
</svg>
```

## 听一听：强与弱的对比

用 `chord` 听**同一个和弦的两种排列**（紧密 / 宽排列）——
**同样的音、同样的"力度"，厚度却不同**。这正说明"力度"实际是**音响效果**，
不只取决于演奏者用多大力。

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"紧密排列（相对“轻”的音响）","label_en":"Close voicing — a relatively lighter sound","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}

```

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"同上 —— 点「宽排列」体会厚度变化","label_en":"The same chord — press Open to feel the thickness change","hint":"音与力度都没变，音响效果不同","hint_en":"Same notes, same dynamic — a different sound"}
```

## 常见误解

- **「力度记号表示绝对音量」** → 是**相对**关系，没有绝对标准。同一个 `p` 在不同作品里差别很大。
- **「巴洛克不标力度，说明力度不重要」** → 那个时代的力度不属于"需要写下来的信息"（场合与编制自然决定）。
- **「`f` 就是尽量响」** → 它是在**本曲的力度体系内**偏强。`ff` 在有些作品里仍很克制。
- **「重音记号与渐弱记号差不多」** → 完全不同：`>` 是**瞬间强调**，渐弱是**一段时间内的下降**。要看它标在音上还是音之间。
:::

::: en
Dynamic markings look the most straightforward, yet one recognition must come first:

> **Dynamics are relative — there is no absolute volume, only relations.**

The same `p` differs **considerably** in actual loudness across works, eras and instruments. So a dynamic marking
means "**relative to the rest of this piece**", not "so many decibels".

## The system of signs

| Sign | Full term | Roughly |
|---|---|---|
| **pp** | pianissimo | very soft |
| **p** | piano | soft |
| **mp** | mezzo-piano | moderately soft |
| **mf** | mezzo-forte | moderately loud |
| **f** | forte | loud |
| **ff** | fortissimo | very loud |

**Gradual change**:

| Sign | Meaning |
|---|---|
| **crescendo** (or an elongated `<`) | getting louder |
| **diminuendo / decrescendo** (`>`) | getting softer |

## When it appeared

One historical fact is worth knowing:

| Period | Dynamic markings |
|---|---|
| **Renaissance and early Baroque** | **almost none** — loudness arose from instruments, forces and occasion |
| **after the eighteenth century** | gradually systematised (linked to keyboard development and larger orchestras) |
| **Romantic** | extremely detailed (`ppp` to `fff`, many gradations) |

**So "Baroque music has no dynamic markings" does not mean the composer did not care about dynamics** — it means
loudness was not information that needed writing down in that era (see
[[concept:historical-performance|historical performance]]).

## Three practical points

**1. Dynamics are not volume.** The same `mf` sounds louder in a low register than a high one (see
[[concept:register|register]]). So in scoring, **markings must be adjusted for register**: an `f` in the bass is
usually written more conservatively.

**2. Dynamics and texture interact.** A chord played by many and a single note both marked `f` differ greatly in
thickness. **So "dynamics" is really "sonic result", not just how hard the performer pushes.**

**3. The length of a crescendo is itself expressive.** `p` to `f` over half a bar is a sudden jolt; over eight bars
it is a gradual accumulation (see [[concept:climax|designing a climax]]). **The duration of the change is part of
the effect.**

## The difference from articulation marks

The two are often confused, but they work on different dimensions:

| | Dynamic markings | Articulation (see [[concept:articulation|articulation]]) |
|---|---|---|
| Governs | how **loud** | how notes **connect** |
| Examples | `f`, `p`, `<`, `>` | slurs, staccato dots, accents |

**Note**: an accent `>` and a diminuendo look similar but **mean entirely different things** — an accent is a
**momentary** emphasis, a diminuendo a **decline over time**. Read carefully whether the sign sits on a note or
between notes.

## Diagram: relations, not absolutes

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The scale is relational and has no absolute starting point; the length of a crescendo is itself expressive</text>
  </g>

  <g transform="translate(52,56)">
    <g stroke="#343439" stroke-width="1"><line x1="0" y1="0" x2="480" y2="0"/></g>
    <g stroke="#343439" stroke-width="1">
      <line x1="0" y1="-5" x2="0" y2="5"/><line x1="96" y1="-5" x2="96" y2="5"/>
      <line x1="192" y1="-5" x2="192" y2="5"/><line x1="288" y1="-5" x2="288" y2="5"/>
      <line x1="384" y1="-5" x2="384" y2="5"/><line x1="480" y1="-5" x2="480" y2="5"/>
    </g>
    <g font-family="Georgia,serif" font-size="11" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="20">pp</text><text x="96" y="20">p</text><text x="192" y="20">mp</text>
      <text x="288" y="20">mf</text><text x="384" y="20">f</text><text x="480" y="20">ff</text>
    </g>

    <g transform="translate(0,-24)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">this scale has no absolute starting point</text>
    </g>

    <g transform="translate(0,48)">
      <path d="M0,-10 L180,-10" stroke="#E8C547" stroke-width="1.6"/>
      <path d="M0,-4 L180,-16" stroke="#E8C547" stroke-width="1.6"/>
      <text x="196" y="-10" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">the same p to f over eight bars: accumulation</text>
      <path d="M0,20 L40,20" stroke="#C0504A" stroke-width="1.6"/>
      <path d="M0,26 L40,14" stroke="#C0504A" stroke-width="1.6"/>
      <text x="56" y="20" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">over half a bar: a jolt — duration is part of the effect</text>
    </g>

    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Dynamics are not volume: an f in the bass sounds louder, so markings are adjusted for register
    </text>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Baroque music marks almost no dynamics: loudness was not information that needed writing down
    </text>
  </g>
</svg>
```

## Listen: the contrast of thick and thin

Use `chord` to hear **one chord in two layouts** (close and open) — **the same notes at the same "dynamic", yet a
different thickness**. Which shows that "dynamics" is really a **sonic result**, not merely how hard the performer
presses.

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"紧密排列（相对较轻的音响）","label_en":"Close voicing — a relatively lighter sound","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"同上 —— 点「宽排列」体会厚度变化","label_en":"The same chord — press Open to feel the thickness change","hint":"音与力度都没变，音响效果不同","hint_en":"Same notes, same dynamic — a different sound"}
```

## Common misconceptions

- **"A dynamic marking states absolute volume."** It is **relative**; there is no absolute standard. The same `p`
  differs greatly between works.
- **"Baroque music marks no dynamics, so dynamics did not matter."** Loudness was simply not information that
  needed writing down; occasion and forces settled it.
- **"`f` means as loud as possible."** It means on the loud side **within this piece's system**. Some `ff` markings
  remain restrained.
- **"An accent and a diminuendo are much the same."** Different entirely: `>` is a **momentary** emphasis, a
  diminuendo a **decline over time**.
:::
