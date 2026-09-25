---
id: motive
site: theo
cat: T8
title: 动机与主题
title_en: Motive and Subject
summary: 动机是"材料"，主题是"陈述"——区别在完整度，不在长度
summary_en: A motive is material, a subject is a statement — they differ in completeness, not length
level: standard
tags: [乐理, 旋律, 曲式]
tags_en: [theory, melody, form]
alias: [动机, 主题, motive, subject, motif]
order: 14
links:
  - "[[concept:melody]]"
  - "[[concept:thematic-development]]"
  - "[[concept:contrapuntal-devices]]"
  - "[[concept:phrase]]"
  - "[[concept:fugue]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：全曲由一个极短的动机发展而成，是"动机驱动整曲"的教科书样本 | Bach's first two-part invention grows entirely from a very short motive — the textbook of motive-driven form
  - mutopia-000522 | 《欢乐颂》主题：它本身是一个**主题**（完整乐思），内部又可拆出若干动机 | The Ode of Joy is itself a **subject** (a complete idea) from which several motives can be extracted
  - atepp-002452 | 巴赫《哥德堡变奏曲》第 12 变奏：低音主题反复提供素材，各段在其上作出不同处理 | Bach's Goldberg Variation 12 — the bass subject supplies the material repeatedly, handled differently each time
sources:
  - 动机为最短且具有辨识力的音高-节奏单元；主题为能构成完整乐思的旋律，属曲式与旋律分析通则
  - 动机与主题的区别在于完整度而非长度，为通行表述
updated: 2026-09-25
---

::: zh
这两个词常被混用，但其实分工清楚：

| | 动机（motive） | 主题（theme / subject） |
|---|---|---|
| 是什么 | **最短**且**有辨识力**的音高-节奏单元 | 能构成**完整乐思**的旋律 |
| 长度 | 通常 2–5 个音 | 通常一个乐句以上 |
| 作用 | **材料** | **陈述** |
| 例子 | 贝多芬第五交响曲开头的"三短一长" | 《欢乐颂》主题整句 |

**关键区分在"完整度"，不在长度。**
一个 3 个音的单元若是完整乐思，可以是主题；
一个 20 个音的片段若只是素材，仍是动机。

## 动机为什么重要：发展性

动机的全部价值在于**可被发展**。因为这个单元足够短、结构足够清楚，
它就能被反复改造而**始终被认出**（见 [[concept:thematic-development|主题的发展与变奏]]）：

| 改造方式 | 例 |
|---|---|
| 移位（模进） | 同一个动机换高度重复 |
| 倒影 | 上行改成下行 |
| 扩大 / 缩小 | 时值加倍或减半 |
| 片段化 | 只取其中两三个音反复 |
| 节奏改造 | 音高不动，只改长短 |

这正是 [[concept:contrapuntal-devices|对位变形手法]] 在旋律层面的应用。
**短 + 清楚 = 可被无限改造**，这就是动机的力量所在。

## 怎样判断"这是一个动机"

两个问句就能判断：

> **① 把音高换掉（全用一个音）还认得出吗？** → 认得出，节奏就是它的核心
> **② 把节奏换掉（全用同一种时值）还认得出吗？** → 认得出，音高关系就是它的核心

**两条都认不出** → 它既不是完整的动机，也还不是主题，只是一段音符。
**至少一条认得出** → 它具备动机的特征：**有一个突出的维度**。

## 主题的写法要求

主题比动机多一条要求：**必须自带"可发展的余地"**。
这也是作曲上最难判断的地方 ——

| 主题类型 | 问题 |
|---|---|
| **太完整** | 什么都说了，无处可发展（听起来像"完成了"） |
| **太空洞** | 没有特征，发展后仍无特征 |
| **刚好** | 有鲜明的特征 + 留有未说尽的部分 |

这也解释了为什么很多经典主题**听上去很朴素**：
它把特征压缩在最少的音里，反而留出了最大的发展空间。

## 图示：动机与主题的关系

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">主题由一个或多个动机构成；动机是"材料"，主题是"陈述"</text>
  </g>

  <g transform="translate(52,54)">
    <g>
      <g fill="#E07A3F">
        <rect x="0" y="-12" width="28" height="20" rx="2"/>
        <rect x="32" y="-12" width="28" height="20" rx="2"/>
        <rect x="64" y="-12" width="56" height="20" rx="2"/>
      </g>
      <text x="130" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">动机：三个音（特征鲜明）</text>
    </g>

    <g transform="translate(0,52)">
      <g fill="#5B7FA8" opacity=".85">
        <rect x="0" y="-12" width="28" height="20" rx="2"/>
        <rect x="32" y="-12" width="28" height="20" rx="2"/>
        <rect x="64" y="-12" width="56" height="20" rx="2"/>
      </g>
      <g fill="#5B7FA8" opacity=".6">
        <rect x="132" y="-12" width="28" height="20" rx="2"/>
        <rect x="164" y="-12" width="28" height="20" rx="2"/>
        <rect x="196" y="-12" width="56" height="20" rx="2"/>
      </g>
      <g fill="#5B7FA8" opacity=".35">
        <rect x="264" y="-12" width="56" height="20" rx="2"/>
        <rect x="324" y="-12" width="56" height="20" rx="2"/>
      </g>
      <text x="392" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">主题：若干动机连成一个完整乐思</text>
    </g>

    <g transform="translate(0,104)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        判断动机的两个问句：音高全换成同一个音还认得出吗？时值全改成一样还认得出吗？
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        至少一条认得出 = 有一个突出的维度；两条都认不出 = 只是音符串
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        好主题的标准：特征鲜明 + 留有未说尽的余地 —— 太完整就无处发展
      </text>
    </g>
  </g>
</svg>
```

## 听一听：一个单元的可能性

用 `scale` 组件听一条音阶，再想象把其中**三个音**单独拿出来反复改造（移位、倒影、扩大）——
**这正是动机驱动型作品的全部材料来源**。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"素材：从中可以取出动机","label_en":"Material: motives can be taken from this","hint":"点「上行」，想象只取前三个音反复改造","hint_en":"Try Up and imagine taking only the first three notes and developing them","gap":0.32}
```

## 常见误解

- **「动机和主题是同一个东西」** → 区分在**完整度**：动机是材料，主题是完整的陈述。
- **「动机就是短的旋律」** → 短只是表象。动机的定义是**有辨识力的最小单元**（至少一个维度突出）。
- **「主题越长越好」** → 相反：太完整的主题**无处发展**。经典主题往往把特征压在最少的音里。
- **「动机只用于古典音乐」** → 电影配乐的主题变形、流行歌的 hook 重复，都是动机思维。
:::

::: en
The two terms are often used interchangeably, but they divide cleanly:

| | Motive | Theme / subject |
|---|---|---|
| What it is | the **shortest** identifiable pitch-and-rhythm unit | a melody forming a **complete idea** |
| Length | usually 2–5 notes | usually a phrase or more |
| Role | **material** | **statement** |
| Example | the "three shorts and a long" opening of Beethoven's Fifth | the whole Ode of Joy theme |

**The distinction is completeness, not length.** A three-note unit that is a complete idea can be a subject; a
twenty-note fragment that is merely material is still a motive.

## Why motives matter: capacity for development

A motive's whole value is that it **can be developed**. Because the unit is short and clearly shaped, it can be
reworked repeatedly and **still be recognised** (see [[concept:thematic-development|thematic development]]):

| Treatment | Example |
|---|---|
| transposition (sequence) | the same motive repeated higher or lower |
| mirror | a rising figure turned falling |
| augmentation / diminution | values doubled or halved |
| fragmentation | only two or three notes repeated |
| rhythmic alteration | pitches kept, durations changed |

This is [[concept:contrapuntal-devices|contrapuntal devices]] applied at the melodic level.
**Short plus clear equals infinitely reworkable** — that is the power of a motive.

## How to decide "is this a motive"

Two questions settle it:

> **1. Replace every pitch with one note — is it still recognisable?** If yes, rhythm is its core.
> **2. Replace every duration with one value — is it still recognisable?** If yes, the pitch relations are its core.

**Neither survives** → it is not a complete motive and not yet a subject, just a run of notes.
**At least one survives** → it has the mark of a motive: **one dimension stands out**.

## What a subject additionally requires

A subject demands one more thing: **it must leave room to develop.** This is the hardest judgement in composing —

| Type | Problem |
|---|---|
| **too complete** | everything is said; there is nowhere to go (it sounds finished) |
| **too empty** | no character, and no character can be developed out of it |
| **just right** | a striking feature plus something left unsaid |

Which explains why many classic subjects **sound plain**: the feature is compressed into the fewest notes,
leaving the largest space for development.

## Diagram: motive and subject

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">A subject is built from one or more motives; motives are material, subjects are statements</text>
  </g>

  <g transform="translate(52,54)">
    <g>
      <g fill="#E07A3F">
        <rect x="0" y="-12" width="28" height="20" rx="2"/>
        <rect x="32" y="-12" width="28" height="20" rx="2"/>
        <rect x="64" y="-12" width="56" height="20" rx="2"/>
      </g>
      <text x="130" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">motive: three notes with a clear feature</text>
    </g>

    <g transform="translate(0,52)">
      <g fill="#5B7FA8" opacity=".85">
        <rect x="0" y="-12" width="28" height="20" rx="2"/>
        <rect x="32" y="-12" width="28" height="20" rx="2"/>
        <rect x="64" y="-12" width="56" height="20" rx="2"/>
      </g>
      <g fill="#5B7FA8" opacity=".6">
        <rect x="132" y="-12" width="28" height="20" rx="2"/>
        <rect x="164" y="-12" width="28" height="20" rx="2"/>
        <rect x="196" y="-12" width="56" height="20" rx="2"/>
      </g>
      <g fill="#5B7FA8" opacity=".35">
        <rect x="264" y="-12" width="56" height="20" rx="2"/>
        <rect x="324" y="-12" width="56" height="20" rx="2"/>
      </g>
      <text x="392" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">subject: motives joined into a complete idea</text>
    </g>

    <g transform="translate(0,104)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        Two tests: flatten the pitches — still recognisable? flatten the durations — still recognisable?
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        One survives means one dimension stands out; neither means it is only a run of notes
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        A good subject: a striking feature plus room left — too complete and there is nowhere to go
      </text>
    </g>
  </g>
</svg>
```

## Listen: the possibilities of one unit

Use `scale` to hear a scale, then imagine taking **three notes** from it and reworking them (transposition,
mirror, augmentation) — **that is the entire material of a motive-driven work.**

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"素材：从中可以取出动机","label_en":"Material: motives can be taken from this","hint":"点「上行」，想象只取前三个音反复改造","hint_en":"Try Up and imagine taking only the first three notes and developing them","gap":0.32}
```

## Common misconceptions

- **"A motive and a subject are the same."** They differ in **completeness**: a motive is material, a subject is a
  finished statement.
- **"A motive is just a short melody."** Brevity is only appearance. A motive is the **smallest identifiable unit**,
  with at least one dimension standing out.
- **"Longer subjects are better."** The opposite: too complete a subject has **nowhere to develop**. Classic
  subjects compress their feature into the fewest notes.
- **"Motives belong to classical music."** Thematic transformation in film scores and the repeated hook of a pop
  song are motive thinking.
:::
