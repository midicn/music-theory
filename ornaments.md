---
id: ornaments
site: theo
cat: T10
title: 装饰音
title_en: Ornaments
summary: 记号是固定的，奏法随时代变化——照符号直译往往不对
summary_en: The signs are fixed; the execution changes with the era — literal reading is often wrong
level: standard
tags: [乐理, 记谱, 实践]
tags_en: [theory, notation, practice]
alias: [装饰音, 倚音, 颤音, 波音, 回音, ornaments]
order: 32
links:
  - "[[concept:articulation]]"
  - "[[concept:historical-performance]]"
  - "[[concept:counterpoint]]"
  - "[[concept:improvisation]]"
  - "[[concept:non-chord-tone]]"
instances:
  - atepp-002452 | 巴赫《哥德堡变奏曲》第 12 变奏：巴洛克装饰音的用法清楚，是"记号简单、奏法需推断"的典型 | Bach's Goldberg Variation 12 — Baroque ornamentation is clear here, a classic case of simple signs needing interpretation
  - atepp-001928 | 巴赫《半音阶幻想曲与赋格》：装饰音密集，可听它们如何参与旋律的流动而不只是"加点花" | Bach's Chromatic Fantasia and Fugue — dense ornamentation, audible as part of the line's flow rather than mere decoration
  - atepp-000195 | 德彪西《月光》：装饰性写法已融入织体本身，可对照巴洛克"独立符号"的做法 | Debussy's Clair de lune — ornamentation absorbed into the texture, a contrast with the Baroque's separate signs
sources:
  - 常见装饰音记号（倚音 / 颤音 / 波音 / 回音）及其奏法随时代与地区变化，为历史演奏法通行研究结论
  - 装饰音的功能（强调 / 增加流动 / 为演奏者留出空间）为通行乐理与演奏教学表述
updated: 2026-09-25
---

::: zh
装饰音的记号本身很清楚，但有一件事必须先讲：

> **记号是固定的，奏法随时代与地区变化极大。**

所以**"照符号直译"往往不是正确读法** —— 这一点与 [[concept:articulation|演奏法记号]] 和
[[concept:dynamics|力度记号]] 完全一致。

## 四种常见记号

| 记号 | 名称 | 基本做法 |
|---|---|---|
| **小音符**（写在主音前） | **倚音**（appoggiatura） | 从上方或下方的邻音进入主音 |
| **tr**（或波浪线） | **颤音**（trill） | 与上方邻音**快速交替** |
| **波浪短线** | **波音**（mordent） | 主音与邻音**一次**快速交替 |
| **S 形曲线** | **回音**（turn） | 环绕主音（上邻—主音—下邻—主音） |

## 三种功能

装饰音不只是"加花"，它做三件事：

| 功能 | 说明 |
|---|---|
| **强调** | 倚音落在**强拍**上时，把重音交给邻音再解决到主音 —— 这是最有力的强调方式之一 |
| **增加流动** | 在长音上加入装饰，让音乐不至于停滞 |
| **留出空间** | 记谱只给"轮廓"，具体做法交给演奏者（见 [[concept:improvisation|即兴]]） |

**第一行最重要**：巴洛克与古典时期的**倚音常占主音的时值**（甚至占一半），
它的和声作用相当于一个**外音**（见 [[concept:non-chord-tone|和弦外音]]），
不只是"先弹一下再弹主音"。

## 一个历史要点

装饰音的奏法**随时代变化**，这是本条最值得记住的：

| 时期 | 情况 |
|---|---|
| **巴洛克** | 记号简洁，**大量细节靠惯例与和声推断**；演奏者也可自行加装饰 |
| **古典** | 倚音的长度、颤音的起止有较明确的惯例（但仍因地区而异） |
| **浪漫以后** | 装饰音**常直接写定**（写成实际音符），记号减少 |

**所以"为什么巴洛克乐谱上的装饰音这么难弹"** ——
因为它**本来就不是"照着弹"的记号**，而是"**提示 + 惯例**"的组合。

这与工尺谱"记谱是框架 + 提示"的思路其实相通（见 [[concept:gongchepu|工尺谱]]）：
**不同传统的记谱法，对"写多少、留多少"有不同的选择。**

## 图示：符号固定，奏法流动

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一个倚音记号，在三个时期可能弹法完全不同</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">记号</text>
      <text x="-20" y="46" text-anchor="end">巴洛克</text>
      <text x="-20" y="92" text-anchor="end">古典</text>
      <text x="-20" y="138" text-anchor="end">浪漫后</text>
    </g>

    <g>
      <g font-family="Georgia,serif" font-size="12" fill="#E8C547">
        <text x="0" y="4">♯</text><text x="30" y="4">♩</text>
      </g>
      <text x="56" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">倚音记号（小音符）</text>
    </g>

    <g transform="translate(0,46)">
      <g fill="#5B7FA8">
        <rect x="0" y="-8" width="60" height="16" rx="2"/>
        <rect x="66" y="-8" width="60" height="16" rx="2"/>
      </g>
      <text x="140" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">常占主音一半时值 —— 是"外音"，不是装饰</text>
    </g>

    <g transform="translate(0,92)">
      <g fill="#E8C547">
        <rect x="0" y="-8" width="30" height="16" rx="2"/>
        <rect x="36" y="-8" width="90" height="16" rx="2"/>
      </g>
      <text x="140" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">长度有惯例，但因地区而异</text>
    </g>

    <g transform="translate(0,138)">
      <g fill="#A9A49B">
        <rect x="0" y="-8" width="14" height="16" rx="2"/>
        <rect x="20" y="-8" width="106" height="16" rx="2"/>
      </g>
      <text x="140" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">多已直接写成实际音符，记号减少</text>
    </g>

    <text x="0" y="170" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      所以"巴洛克装饰音难弹"，是因为它本来就不是"照着弹"的记号，而是"提示 + 惯例"
    </text>
  </g>
</svg>
```

## 听一听：装饰与不装饰

装饰音的本质是**邻音与主音之间的快速移动**。用 `interval` 听**小二度**（最常见的装饰音音程）——
然后想象它在主音上快速来回，那就是颤音与波音的核心。

```audiolab
{"type":"interval","a":"C4","b":"D♭4","label":"小二度（最常见的装饰音音程）","label_en":"A minor second — the commonest ornament interval","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D4 就是大二度，常见于波音与回音；快速来回移动即构成颤音。","hint2_en":"Set b to D4 for the major second used in mordents and turns; rapid alternation gives a trill."}
```

## 常见误解

- **「装饰音只是"加点花"」** → 它承担**强调、流动性、留空间**三种功能；巴洛克的倚音甚至具有外音的和声作用。
- **「装饰音的奏法固定」** → **随时代与地区变化极大**。照符号直译往往不是当时的实际奏法。
- **「现代乐谱不写装饰音」** → 浪漫派以后装饰音常**直接写成音符**；20 世纪则另有自己的记法（见 [[concept:modern-notation|现代记谱法]]）。
- **「装饰音可以忽略」** → 在巴洛克与古典作品里删掉装饰音，等于改变了**旋律的实际形态与和声**。
:::

::: en
The signs are clear enough, but one thing must come first:

> **The signs are fixed; their execution varies greatly with era and region.**

So **"translating the sign literally" is often not the right reading** — exactly as with
[[concept:articulation|articulation]] and [[concept:dynamics|dynamics]].

## Four common signs

| Sign | Name | Basic execution |
|---|---|---|
| **small note** before a main note | **appoggiatura** | approach the main note from a neighbour above or below |
| **tr** (or a wavy line) | **trill** | rapid **alternation** with the upper neighbour |
| **short wavy line** | **mordent** | **one** rapid alternation with a neighbour |
| **S-shaped curve** | **turn** | circling the main note (upper neighbour, main, lower neighbour, main) |

## Three functions

Ornamentation is not merely "adding flowers"; it does three things:

| Function | Explanation |
|---|---|
| **emphasis** | an appoggiatura on a **strong beat** gives the accent to the neighbour before resolving — one of the strongest emphases available |
| **flow** | ornamenting a long note keeps the music from stalling |
| **leaving space** | the notation gives a **contour** and hands the detail to the performer (see [[concept:improvisation|improvisation]]) |

**The first row matters most**: in the Baroque and Classical periods an **appoggiatura often takes part of the main
note's value** (sometimes half), and its harmonic role is that of a **non-chord tone** (see
[[concept:non-chord-tone|non-chord tones]]) — not simply "a quick note before the real one".

## One historical point

Ornament execution **changes with the era**, and this is the entry's most memorable fact:

| Period | Situation |
|---|---|
| **Baroque** | signs are terse, **much depends on convention and harmony**; performers also added ornaments of their own |
| **Classical** | the length of appoggiaturas and the start and end of trills follow clearer conventions (still regional) |
| **after the Romantic era** | ornaments are **often written out as actual notes**, so the signs dwindle |

**Which answers "why is Baroque ornamentation so hard to play"** — because the signs were never meant to be read
literally; they are a **combination of cue and convention**.

The logic resembles gongche notation's "frame plus cue" (see [[concept:gongchepu|gongche notation]]): **different
traditions make different choices about how much to write and how much to leave open.**

## Diagram: the sign fixed, the execution fluid

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One appoggiatura sign, three periods, three different executions</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">sign</text>
      <text x="-20" y="46" text-anchor="end">Baroque</text>
      <text x="-20" y="92" text-anchor="end">Classical</text>
      <text x="-20" y="138" text-anchor="end">after Romantic</text>
    </g>

    <g>
      <g font-family="Georgia,serif" font-size="12" fill="#E8C547">
        <text x="0" y="4">♯</text><text x="30" y="4">♩</text>
      </g>
      <text x="56" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">the appoggiatura sign</text>
    </g>

    <g transform="translate(0,46)">
      <g fill="#5B7FA8">
        <rect x="0" y="-8" width="60" height="16" rx="2"/>
        <rect x="66" y="-8" width="60" height="16" rx="2"/>
      </g>
      <text x="140" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">often half the main value: a non-chord tone, not decoration</text>
    </g>

    <g transform="translate(0,92)">
      <g fill="#E8C547">
        <rect x="0" y="-8" width="30" height="16" rx="2"/>
        <rect x="36" y="-8" width="90" height="16" rx="2"/>
      </g>
      <text x="140" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">lengths follow conventions, which vary by region</text>
    </g>

    <g transform="translate(0,138)">
      <g fill="#A9A49B">
        <rect x="0" y="-8" width="14" height="16" rx="2"/>
        <rect x="20" y="-8" width="106" height="16" rx="2"/>
      </g>
      <text x="140" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#A9A49B">usually written out as real notes; the signs recede</text>
    </g>

    <text x="0" y="170" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Baroque ornaments are hard because they are cues plus convention, not literal instructions
    </text>
  </g>
</svg>
```

## Listen: ornamented and plain

Ornamentation is essentially **rapid motion between a main note and a neighbour**. Use `interval` to hear **a minor
second** (the commonest ornament interval) — then imagine it alternating quickly on a main note, which is the core
of trills and mordents.

```audiolab
{"type":"interval","a":"C4","b":"D♭4","label":"小二度（最常见的装饰音音程）","label_en":"A minor second — the commonest ornament interval","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D4 就是大二度，常见于波音与回音；快速来回移动即构成颤音。","hint2_en":"Set b to D4 for the major second used in mordents and turns; rapid alternation gives a trill."}
```

## Common misconceptions

- **"Ornaments are just decoration."** They carry **emphasis, flow and open space**; a Baroque appoggiatura even
  functions as a non-chord tone.
- **"Ornament execution is fixed."** It **varies greatly by era and region**; a literal reading is often not what
  was played.
- **"Modern scores have no ornaments."** After the Romantic era they are usually **written out as notes**; the
  twentieth century has its own notations (see [[concept:modern-notation|contemporary notation]]).
- **"Ornaments can be ignored."** In Baroque and Classical works, dropping them changes the melody's **actual shape
  and harmony**.
:::
