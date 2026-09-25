---
id: one-part-form
site: theo
cat: T9
title: 一段体
title_en: One-Part Form
summary: 一个乐思自足——它是"有没有曲式"的基准线
summary_en: One idea standing alone — the baseline against which form itself is judged
level: standard
tags: [乐理, 曲式, 结构]
tags_en: [theory, form, structure]
alias: [一段体, 一部曲式, one-part form]
order: 36
links:
  - "[[concept:form]]"
  - "[[concept:phrase]]"
  - "[[concept:binary-form]]"
  - "[[concept:song-form]]"
  - "[[concept:motive]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：八小节内完成一次完整的陈述与收束，是"一个乐思自足"的最小样本 | The Ode of Joy completes a full statement and close inside eight bars, the smallest self-sufficient idea
  - thesession-019704 | 《小星星》：全曲只用五音与两种时值，尽管可分句，整体仍是一个完整乐思 | Twinkle Little Star uses five notes and two values; though it divides into phrases, it remains one idea
  - cyberhymnal-000695 | 管风琴圣咏：单句式的短小曲目常见"一段体"形态，可用来对照有段落对比的曲目 | An organ hymn — short single-sentence pieces often take this shape, a contrast with works that have sectional contrast
sources:
  - 一段体指全曲由一个乐思构成、不作段落级对比与回归的结构形态，属曲式分析通则
  - 一段体与"乐段"分属不同层级（乐段是旋律层结构，一段体是整曲曲式），为通行表述
updated: 2026-09-25
---

::: zh
一段体是最容易被忽略的曲式，因为它的定义是**否定式**的：

> **全曲只有一个乐思，不再作段落级的对比与回归。**

也就是：它**没有** ABA，也**没有** AB。听完就是"一个完整的东西"。

## 两个必须分清的概念

这是本条最要紧的部分 —— **"一段体"与"乐段"不是一回事**：

| | **乐段**（period） | **一段体**（one-part form） |
|---|---|---|
| 属于哪一层 | **旋律层**：由两个乐句构成 | **整曲层**：整首作品的曲式 |
| 讲的是 | 乐句怎么成对（见 [[concept:phrase|乐句与乐段]]） | 全曲有没有段落对比 |
| 一首曲子可以 | 含**多个**乐段 | 只有一个曲式 |

**所以"一段体"内部完全可以是"两个乐句"甚至"四个乐句"** ——
分句是旋律层的事，与"曲式只有一个部分"并不矛盾。

## 长度不是判据

最容易犯的错误是以为一段体 = 短：

| 误区 | 实际 |
|---|---|
| 一段体一定很短 | **长度不限** —— 一首 8 小节的民歌和一首 40 小节的练习曲都可能是 |
| 长曲子一定不是一段体 | 只要全曲不做段落级对比与回归，再长也是一段体 |

**判据只有一条**：全曲有没有"出去再回来"或"两段对比"这种**段落级**的安排。
有 → 二段体或三段体；没有 → 一段体。

## 它出现在哪里

| 类型 | 说明 |
|---|---|
| **民歌 / 圣咏** | 一首短歌常是一个完整乐思，不自成段落 |
| **短小器乐曲** | 前奏曲、练习曲、小品 |
| **主题本身** | 变奏曲的**主题**、赋格的**主题**都常是一段体（见 [[concept:theme-variations|变奏曲式]]） |
| **乐章内部** | 大型作品里的一个短小段落 |

第三行值得注意：**一段体是"更复杂结构的材料"** ——
变奏曲的主题、奏鸣曲式的主题，本身就是一段体。**这正说明一段体是构件，不只是缩小的作品。**

## 图示：三种层级不要混

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">乐句是旋律层，乐段是旋律层的一对，一段体是"整曲只有一个部分"</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="6" text-anchor="end">乐句</text>
      <text x="-20" y="46" text-anchor="end">乐段</text>
      <text x="-20" y="96" text-anchor="end">一段体</text>
    </g>

    <g fill="#5B7FA8" opacity=".8">
      <rect x="0" y="-6" width="70" height="18" rx="2"/>
      <rect x="76" y="-6" width="70" height="18" rx="2"/>
    </g>
    <text x="156" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">两句 → 成对（前开、后收）</text>

    <g transform="translate(0,40)">
      <g fill="#E8C547" opacity=".85">
        <rect x="0" y="-6" width="70" height="18" rx="2"/>
        <rect x="76" y="-6" width="70" height="18" rx="2"/>
      </g>
      <text x="156" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">这就是一个乐段 —— 它属于旋律层</text>
    </g>

    <g transform="translate(0,90)">
      <g fill="#E07A3F">
        <rect x="0" y="-6" width="146" height="18" rx="2"/>
      </g>
      <text x="156" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">整曲不加段落对比 = 一段体（内部仍可分句）</text>
    </g>

    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      判据只有一条：全曲有没有"出去再回来"或"两段对比"这种段落级安排
    </text>
    <text x="0" y="154" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      长度不是判据：8 小节的民歌与 40 小节的练习曲都可能是一段体
    </text>
  </g>
</svg>
```

## 听一听：一个乐思自足

用 `progression` 听一段"完整陈述并收束"的进行 —— 只有一次离开与回归，没有第二次。
**这就是一段体在和声层面的样子**：说完就结束，不做更大的安排。

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"一个完整乐思（说完就结束）","label_en":"One complete idea — said, then finished","hint":"逐个和弦依次听：只有一次收束，没有第二次","hint_en":"Hear each chord: one close, and no second"}
```

## 常见误解

- **「一段体就是乐段」** → 不同层级：乐段属**旋律层**（由乐句构成），一段体属**整曲层**（全曲的曲式）。
- **「一段体一定很短」** → 长度不限。判据是**有没有段落级对比与回归**，不是长短。
- **「一段体没有结构」** → 它有完整的内部结构（乐句成对、有起有收），只是**不做段落级的安排**。
- **「它是初级形态」** → 它是**构件**：变奏曲的主题、赋格的主题、奏鸣曲式的主题本身就是一段体。
:::

::: en
One-part form is the most easily overlooked form, because its definition is **negative**:

> **The whole piece is one idea, with no sectional contrast or return.**

That is: there is **no** ABA and **no** AB. What you hear is "one complete thing".

## Two concepts that must be kept apart

This is the heart of the entry — **"one-part form" and "period" are not the same thing**:

| | **Period** | **One-part form** |
|---|---|---|
| Which level | **melodic**: built from two phrases | **whole piece**: the form of the work |
| Concerns | how phrases pair (see [[concept:phrase|phrase and period]]) | whether the piece has sectional contrast |
| A piece may contain | **several** periods | only one form |

**So a one-part form may well contain two or even four phrases.** Phrasing belongs to the melodic level and does
not contradict "the form has one part".

## Length is not the test

The commonest error is assuming one-part means short:

| Misconception | Reality |
|---|---|
| it must be short | **no length limit** — an eight-bar folk song and a forty-bar study both qualify |
| a long piece cannot be one-part | if the whole piece avoids sectional contrast and return, it qualifies however long |

**There is one test**: does the piece contain a **sectional** "out and back" or "two-part contrast"? Yes means
binary or ternary; no means one-part.

## Where it appears

| Type | Explanation |
|---|---|
| **folk song / hymn** | a short song is often one complete idea, not divided into sections |
| **short instrumental pieces** | preludes, studies, small pieces |
| **themes themselves** | the **theme** of a variation set and the **subject** of a fugue are often one-part (see [[concept:theme-variations|variation form]]) |
| **inside a movement** | a short passage within a larger work |

The third row matters: **one-part form is the material of more complex structures** — the theme of a variation set
and the subject of a sonata movement are themselves one-part. **Which shows it is a building block, not merely a
shrunk-down piece.**

## Diagram: don't mix the levels

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Phrase is melodic; a period is a pair of phrases; one-part means the work has a single section</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="6" text-anchor="end">phrase</text>
      <text x="-20" y="46" text-anchor="end">period</text>
      <text x="-20" y="96" text-anchor="end">one-part</text>
    </g>

    <g fill="#5B7FA8" opacity=".8">
      <rect x="0" y="-6" width="70" height="18" rx="2"/>
      <rect x="76" y="-6" width="70" height="18" rx="2"/>
    </g>
    <text x="156" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">two phrases pairing: open, then closed</text>

    <g transform="translate(0,40)">
      <g fill="#E8C547" opacity=".85">
        <rect x="0" y="-6" width="70" height="18" rx="2"/>
        <rect x="76" y="-6" width="70" height="18" rx="2"/>
      </g>
      <text x="156" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">that is a period — it belongs to the melodic level</text>
    </g>

    <g transform="translate(0,90)">
      <g fill="#E07A3F">
        <rect x="0" y="-6" width="146" height="18" rx="2"/>
      </g>
      <text x="156" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">no sectional contrast in the whole piece: one-part</text>
    </g>

    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      One test: does the piece have a sectional out-and-back or a two-part contrast?
    </text>
    <text x="0" y="154" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Length is not the test: eight-bar songs and forty-bar studies both qualify
    </text>
  </g>
</svg>
```

## Listen: one idea, self-sufficient

Use `progression` on a span with a single departure and return and no second one. **That is one-part form at the
harmonic level**: it says its piece and stops, without larger planning.

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"一个完整乐思（说完就结束）","label_en":"One complete idea — said, then finished","hint":"逐个和弦依次听：只有一次收束，没有第二次","hint_en":"Hear each chord: one close, and no second"}
```

## Common misconceptions

- **"One-part form is a period."** Different levels: a period belongs to the **melodic** level (built from
  phrases), one-part form to the **whole-piece** level.
- **"One-part form must be short."** No length limit. The test is **sectional contrast and return**, not size.
- **"One-part form has no structure."** It has a complete internal structure (paired phrases, a rise and a close) —
  it simply makes no **sectional** arrangement.
- **"It is a beginner's shape."** It is a **building block**: variation themes, fugue subjects and sonata subjects
  are themselves one-part.
:::
