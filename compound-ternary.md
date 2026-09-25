---
id: compound-ternary
site: theo
cat: T9
title: 复三部曲式
title_en: Compound Ternary Form
summary: 三段体的放大版——每一段本身就是一个完整曲式
summary_en: Ternary form scaled up — each section is itself a complete form
level: standard
tags: [乐理, 曲式, 结构]
tags_en: [theory, form, structure]
alias: [复三部曲式, 复三部, 复三段体, compound ternary]
order: 30
links:
  - "[[concept:ternary-form]]"
  - "[[concept:binary-form]]"
  - "[[concept:form]]"
  - "[[concept:dance-rhythm]]"
  - "[[concept:rondo-form]]"
instances:
  - atepp-000355 | 格里格《抒情小品》：其中多首为"三段体套三段体"的写法，可听层级关系 | Grieg's Lyric Pieces — several are ternary within ternary, useful for hearing the levels
  - cyberhymnal-000695 | 管风琴圣咏：主歌部分常自成一段，与"每段独立成篇"的复三部思维相通 | An organ hymn — its verse sections stand as units of their own, the same logic of self-contained sections
  - atepp-000498 | 匈牙利狂想曲：大段落各自成篇，可与"每段是独立曲式"的复三部对照 | A Hungarian Rhapsody — large sections each complete in themselves, a comparison with compound ternary
sources:
  - 复三部曲式的定义（每段本身为独立曲式）与常见体裁（圆舞曲 / 谐谑曲 / 进行曲），属曲式分析通则
  - "三声中部"（trio）之名来自巴洛克时期由三件乐器演奏的段落，为音乐史通行记载
updated: 2026-09-25
---

::: zh
复三部曲式（compound ternary）是 [[concept:ternary-form|三段体]] 的放大版：

> **外观还是 ABA，但每一段本身就是一个完整的曲式。**

区别不在规模，而在**层级**：

| | 单三段体（simple） | 复三部曲式（compound） |
|---|---|---|
| A 段 | 一个乐段 | **一个二段体或三段体** |
| 结构层级 | **一层**（乐段 → 曲式） | **两层**（曲式 → 曲式） |
| 标记 | ABA | **A（a b）B（c d）A** |
| 常见体裁 | 歌曲、小品 | **圆舞曲 · 谐谑曲 · 进行曲 · 小步舞曲** |

**判断方法**：看 A 段"能不能单独成篇"。如果 A 段自己就有一个完整的"出去—回来"，
那外层就是复三部曲式。

## 中间段的名字：三声中部

复三部的中间段（B）传统上叫 **trio（三声中部）**，这个名字来自巴洛克时期：

> 当时这类舞曲的中间段**由三件乐器演奏**（其他声部休息），于是整段被叫作"三声部"，
> 后来即使乐器数量变了，名字仍保留。

这也是一个有趣的现象：**术语常常比它描述的事实活得更久** ——
今天写"Trio"的段落可能由整个乐队演奏，但名字还叫"三声部"。

## 为什么这种层级有用

因为它同时解决两个尺度上的问题：

| 尺度 | 解决的问题 |
|---|---|
| **大尺度** | ABA 提供"出去—回来"的完整感（整首作品） |
| **小尺度** | 每段内部各有自己的对比与收束（段落内部） |

**否则会长篇单调**：如果 A 段长达三分钟却只是同一种材料平铺，
听者在中途就会失去方向。复三部的层级保证了**每一层都有自己的起伏**。

## 与回旋曲式的区别

两者都能写长，但组织方式不同：

| | 复三部曲式 | 回旋曲式 |
|---|---|---|
| 结构 | A B A（**三段，各段是曲式**） | A B A C A（**多段，A 反复**） |
| 对比单元 | 只有**一个**中间段（trio） | **多个**插部 |
| 听感 | "出去一趟就回来" | "反复出门又回来" |

## 图示：两层结构

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">外层是 ABA，内层每段各成曲式 —— 层级不是规模</text>
  </g>

  <g transform="translate(52,58)">
    <g fill="#5B7FA8" opacity=".9"><rect x="0" y="-16" width="150" height="28" rx="3"/></g>
    <text x="75" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>
    <g fill="#E07A3F"><rect x="164" y="-16" width="150" height="28" rx="3"/></g>
    <text x="239" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">B（三声中部）</text>
    <g fill="#5B7FA8" opacity=".9"><rect x="328" y="-16" width="150" height="28" rx="3"/></g>
    <text x="403" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>

    <g transform="translate(0,28)">
      <g fill="#5B7FA8" opacity=".45">
        <rect x="0" y="-8" width="70" height="16" rx="2"/>
        <rect x="80" y="-8" width="70" height="16" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">
        <text x="35" y="4">a</text><text x="115" y="4">b</text>
      </g>
      <g fill="#E07A3F" opacity=".5">
        <rect x="164" y="-8" width="70" height="16" rx="2"/>
        <rect x="244" y="-8" width="70" height="16" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">
        <text x="199" y="4">c</text><text x="279" y="4">d</text>
      </g>
      <g fill="#5B7FA8" opacity=".45">
        <rect x="328" y="-8" width="70" height="16" rx="2"/>
        <rect x="408" y="-8" width="70" height="16" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">
        <text x="363" y="4">a</text><text x="443" y="4">b</text>
      </g>
    </g>

    <text x="0" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      为什么要两层：否则 A 段长达三分钟却只是平铺，听者会中途失去方向
    </text>
    <text x="0" y="88" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      中间段叫"三声中部（trio）"，因巴洛克时期由三件乐器演奏而得名 —— 术语常常比它描述的事实活得更久
    </text>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      与回旋曲式的区别：复三部只有一个中间段（出去一趟就回来）；回旋有多个插部（反复出门又回来）
    </text>
  </g>
</svg>
```

## 听一听：层级的必要

用 `progression` 听一段较长的功能进行。请留意**它内部也有起伏** ——
如果整段都是同一个和弦，即使很长也不会形成"段落感"。
**复三部曲式的价值就在于让每一层都有自己的起伏。**

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I","V","I"],"label":"段落内部的起伏（两次收束）","label_en":"Internal shaping: two closes inside one section","hint":"逐个和弦依次听：注意中间那次回到 I 也是一个“小结束”","hint_en":"Hear each chord: the middle return to I is a small close too"}

```

## 常见误解

- **「复三部只是三段体写长一点」** → 差别在**层级**：单三段的每段是乐段，复三部的每段是**曲式**。
- **「三声中部就是三个声部」** → 名字是历史遗留（原由三件乐器演奏），今天的 Trio 可能由整个乐队演奏。
- **「复三部与回旋曲式差不多」** → 复三部只有一个中间段；回旋曲式有多个插部。
- **「层级越多越高级」** → 层级是**为内容服务**的。短小的乐思硬套两层结构，只会显得空洞。
:::

::: en
Compound ternary form is [[concept:ternary-form|ternary form]] scaled up:

> **Still ABA in outline, but each section is itself a complete form.**

The difference is not size but **level**:

| | Simple ternary | Compound ternary |
|---|---|---|
| Section A | a period | **a binary or ternary form** |
| Number of levels | **one** (period to form) | **two** (form to form) |
| Label | ABA | **A (a b) B (c d) A** |
| Typical genres | songs, short pieces | **waltz, scherzo, march, minuet** |

**The test**: can section A stand alone? If A contains a complete out-and-back of its own, the outer form is
compound.

## The name of the middle section: trio

The middle section of a compound ternary is traditionally called the **trio**, and the name comes from the Baroque:

> Such middle sections were **played by three instruments** (the other parts resting), so the section was called
> "three-part"; the name stuck even after the scoring changed.

An interesting pattern in itself: **terms often outlive the facts they describe** — a passage marked "Trio" today
may be played by the whole orchestra, and still be called "three-part".

## Why the extra level is useful

Because it solves a problem at each scale:

| Scale | Problem solved |
|---|---|
| **large** | ABA provides the completeness of going out and returning (the whole work) |
| **small** | each section has its own contrast and closure (inside the section) |

**Without it, length turns monotonous**: a three-minute A section laid out as one continuous material loses the
listener halfway. The extra level guarantees that **every layer has its own rise and fall.**

## The difference from rondo form

Both can be long, but they organise differently:

| | Compound ternary | Rondo |
|---|---|---|
| Structure | A B A (**three sections, each a form**) | A B A C A (**several, A returns**) |
| Units of contrast | **one** middle section (trio) | **several** episodes |
| Impression | "one trip out and back" | "out and back, repeatedly" |

## Diagram: two levels

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">ABA outside, a complete form inside each section — a matter of levels, not size</text>
  </g>

  <g transform="translate(52,58)">
    <g fill="#5B7FA8" opacity=".9"><rect x="0" y="-16" width="150" height="28" rx="3"/></g>
    <text x="75" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>
    <g fill="#E07A3F"><rect x="164" y="-16" width="150" height="28" rx="3"/></g>
    <text x="239" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">B (trio)</text>
    <g fill="#5B7FA8" opacity=".9"><rect x="328" y="-16" width="150" height="28" rx="3"/></g>
    <text x="403" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>

    <g transform="translate(0,28)">
      <g fill="#5B7FA8" opacity=".45">
        <rect x="0" y="-8" width="70" height="16" rx="2"/>
        <rect x="80" y="-8" width="70" height="16" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">
        <text x="35" y="4">a</text><text x="115" y="4">b</text>
      </g>
      <g fill="#E07A3F" opacity=".5">
        <rect x="164" y="-8" width="70" height="16" rx="2"/>
        <rect x="244" y="-8" width="70" height="16" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">
        <text x="199" y="4">c</text><text x="279" y="4">d</text>
      </g>
      <g fill="#5B7FA8" opacity=".45">
        <rect x="328" y="-8" width="70" height="16" rx="2"/>
        <rect x="408" y="-8" width="70" height="16" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">
        <text x="363" y="4">a</text><text x="443" y="4">b</text>
      </g>
    </g>

    <text x="0" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Why two levels: without them a long A section laid out flat loses the listener halfway
    </text>
    <text x="0" y="88" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The middle section is called a trio from its three-instrument origin — terms outlive their facts
    </text>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Versus rondo: one middle section here, several episodes there
    </text>
  </g>
</svg>
```

## Listen: why the extra level is needed

Use `progression` on a longer functional span. Notice that **it has shaping inside it** — a section made of one
chord throughout would feel formless however long. **That is exactly what compound ternary's levels provide.**

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I","V","I"],"label":"段落内部的起伏（两次收束）","label_en":"Internal shaping: two closes inside one section","hint":"逐个和弦依次听：中间那次回到 I 也是一个小的结束","hint_en":"Hear each chord: the middle return to I is a small close too"}
```

## Common misconceptions

- **"Compound ternary is just longer ternary."** The difference is **level**: in simple ternary each section is a
  period; in compound ternary each section is a **form**.
- **"A trio means three voices."** The name is historical (three instruments originally); a Trio today may be played
  by the full orchestra.
- **"Compound ternary and rondo are much alike."** Compound ternary has a single middle section; a rondo has several
  episodes.
- **"More levels is more advanced."** Levels **serve the content**. Forcing two levels onto a short idea only leaves
  it hollow.
:::
