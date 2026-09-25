---
id: cadence
site: theo
cat: T5
title: 终止式
title_en: Cadence
summary: 和声的标点符号——正格、变格、半终止、阻碍，四种收束方式
summary_en: The punctuation of harmony — authentic, plagal, half and deceptive, four ways to close
level: core
tags: [乐理, 和声, 曲式]
tags_en: [theory, harmony, form]
alias: [终止式, 正格终止, 变格终止, 半终止, 阻碍终止, cadence]
order: 14
links:
  - "[[concept:harmonic-function]]"
  - "[[concept:tonal-center]]"
  - "[[concept:dominant-seventh]]"
  - "[[concept:melody]]"
  - "[[concept:sonata-form]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：每一句都以终止式收尾，是"和声标点"最规范的样本 | An organ hymn — every phrase closes with a cadence, the most regular sample of harmonic punctuation
  - mutopia-000522 | 《欢乐颂》主题：前半句停在属和弦上（半终止），后半句才真正收束，句读由此分明 | The Ode to Joy theme pauses on the dominant halfway and only closes at the end, which is what marks the phrasing
  - atepp-000318 | a 小调奏鸣曲：乐章内部的句读几乎全靠终止式划分，可听它如何组织段落 | A sonata in A minor — the internal phrasing is almost entirely delimited by cadences
sources:
  - 四种终止式（正格 / 变格 / 半 / 阻碍）的构成与收束强度差异，属和声学通则
  - 终止式在曲式分析中用于划分乐句与乐段，为通行表述
updated: 2026-09-24
---

::: zh
如果和声有标点符号，那就是**终止式**。它决定一个乐句是"说完了"还是"还没说完"。

## 四种终止式

| 名称 | 进行 | 收束感 | 相当于标点 |
|---|---|---|---|
| **正格终止** | V → I | **最强** | 句号 |
| **变格终止** | IV → I | 柔和、有余韵 | 也是句号，但语气轻 |
| **半终止** | 任何和弦 → V | **悬着** | 逗号 / 分号 |
| **阻碍终止** | V → vi | 被"骗"了一下 | 惊叹号 |

四者的差别可以只用一个问题概括：**最后落在哪个和弦上？**
落在主和弦就是收束（正格 / 变格），落在属和弦就是悬置（半终止），
落在别的和弦就是"意外"（阻碍）。

## 正格终止为什么最强

因为它是 [[concept:dominant-seventh|属七和弦]] 内部那个三全音的解决：
**导音上行半个音、七音下行半个音**，两条线同时收进主和弦（见 [[concept:harmonic-function|和声功能]]）。
其他三种终止都没有这种"双向夹紧"的动作。

## 变格终止的听觉特点

IV → I 缺少导音的那股冲力，所以听起来**更松弛、更有"落下帷幕"的感觉**。
它在教堂音乐、赞美诗结尾与摇滚乐里都很常见 —— 想要庄严而非果断时用它。

## 阻碍终止的用处

V → vi 的效果是**推迟**：明明要落地，却转到了关系小调上。
作曲家常用它来**延长乐句** —— 一次该结束的地方不结束，段落因此被拉长，
这也是 [[concept:melody|旋律]] 写作里扩大结构的常用手段。

## 终止式与曲式

终止式的**强度**直接决定了段落级别：

| 终止强度 | 通常划分出的单位 |
|---|---|
| 弱（半终止） | 乐句内部的小停顿 |
| 中（变格 / 弱的正格） | 乐句结束 |
| 强（完全正格） | 乐段结束、乐章段落分界 |

所以分析 [[concept:sonata-form|奏鸣曲式]] 的段落边界时，第一步就是**找终止式**。

## 图示：四种终止的落点

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">四种终止式的区别只在"最后落在哪个和弦"</text>
  </g>

  <g transform="translate(48,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">V</text><text x="70" y="0">I</text>
      <text x="180" y="0">IV</text><text x="250" y="0">I</text>
      <text x="360" y="0">I</text><text x="430" y="0">V</text>
      <text x="540" y="0">V</text><text x="610" y="0">vi</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.3">
      <line x1="8" y1="10" x2="62" y2="10"/><polygon points="62,5 72,10 62,15" fill="#5B7FA8" stroke="none"/>
      <line x1="188" y1="10" x2="242" y2="10"/><polygon points="242,5 252,10 242,15" fill="#5B7FA8" stroke="none"/>
    </g>
    <g stroke="#E8C547" stroke-width="1.3">
      <line x1="368" y1="10" x2="422" y2="10"/><polygon points="422,5 432,10 422,15" fill="#E8C547" stroke="none"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.3">
      <line x1="548" y1="10" x2="602" y2="10"/><polygon points="602,5 612,10 602,15" fill="#C0504A" stroke="none"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="34" fill="#5B7FA8">正格终止</text>
      <text x="0" y="52" fill="#6E6A64">最强 · 句号</text>
      <text x="180" y="34" fill="#5B7FA8">变格终止</text>
      <text x="180" y="52" fill="#6E6A64">柔和 · 余韵</text>
      <text x="360" y="34" fill="#E8C547">半终止</text>
      <text x="360" y="52" fill="#6E6A64">悬着 · 逗号</text>
      <text x="540" y="34" fill="#C0504A">阻碍终止</text>
      <text x="540" y="52" fill="#6E6A64">被推迟 · 惊叹号</text>
    </g>
    <text x="0" y="84" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      落点决定语气：落在主和弦 = 收束；落在属和弦 = 悬置；落在别的和弦 = 意外
    </text>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      分析段落时先找终止式 —— 终止的强度直接对应段落级别
    </text>
  </g>
</svg>
```

## 听一听：四种终止式

按顺序听：正格（V→I，最收）、变格（IV→I，柔和）、半终止（I→V，悬着）、阻碍（V→vi，被推迟）。

```audiolab
{"type":"progression","key":"C4","degrees":["V","I"],"label":"正格终止 V → I","label_en":"Authentic cadence, V to I","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["V","vi"],"label":"阻碍终止 V → vi（被推迟）","label_en":"Deceptive cadence, V to vi — the close is postponed","hint":"与上一条对比：本来要落地，却拐走了","hint_en":"Compare with the item above — the landing is diverted"}
```

## 常见误解

- **「终止式就是"结束"」** → 半终止完全不结束，反而制造期待。它是"标点"，不只是"句号"。
- **「变格终止是正格的弱化版」** → 更像另一种语气：庄严、松弛、有余韵，而不是"力度不够"。
- **「阻碍终止是写错了」** → 它是有意的推迟手段，是扩大乐句的常用技术。
- **「终止式只用于古典音乐」** → 流行音乐的"回到主和弦"与半终止（停在 V）同样可以用这套语言描述。
:::

::: en
If harmony had punctuation, it would be the **cadence**. A cadence decides whether a phrase has finished or is
still hanging.

## The four cadences

| Name | Motion | Closure | Punctuation |
|---|---|---|---|
| **authentic** | V → I | **strongest** | full stop |
| **plagal** | IV → I | soft, with afterglow | also a full stop, lighter in tone |
| **half** | any chord → V | **hangs** | comma or semicolon |
| **deceptive** | V → vi | diverted | exclamation mark |

The difference reduces to one question: **which chord does it land on?** Landing on the tonic closes (authentic or
plagal); landing on the dominant suspends (half); landing elsewhere surprises (deceptive).

## Why the authentic cadence is strongest

Because it resolves the tritone inside the [[concept:dominant-seventh|dominant seventh]]: **the leading tone
rises a semitone and the seventh falls a semitone**, both lines closing into the tonic at once (see
[[concept:harmonic-function|harmonic function]]). None of the other three has that two-way clamp.

## The sound of the plagal cadence

IV → I lacks the leading tone's thrust, so it lands more gently — with a sense of the curtain coming down rather
than a decisive cut. It is common in church music, hymn endings and rock — reach for it when you want solemn
rather than decisive.

## What the deceptive cadence is for

V → vi **postpones**. The music is about to land and instead turns to the relative minor. Composers use it to
extend a phrase: a place that should have closed does not, and the passage lengthens — a standard device for
enlarging structure in [[concept:melody|melodic]] writing.

## Cadences and form

The **strength** of a cadence fixes the level of the division it marks:

| Cadence strength | Unit it usually divides |
|---|---|
| weak (half) | a pause inside a phrase |
| medium (plagal, weak authentic) | the end of a phrase |
| strong (full authentic) | the end of a period, a section boundary |

Which is why the first step in analysing [[concept:sonata-form|sonata form]] is **finding the cadences**.

## Diagram: where each cadence lands

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The four cadences differ only in which chord they land on</text>
  </g>

  <g transform="translate(48,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">V</text><text x="70" y="0">I</text>
      <text x="180" y="0">IV</text><text x="250" y="0">I</text>
      <text x="360" y="0">I</text><text x="430" y="0">V</text>
      <text x="540" y="0">V</text><text x="610" y="0">vi</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.3">
      <line x1="8" y1="10" x2="62" y2="10"/><polygon points="62,5 72,10 62,15" fill="#5B7FA8" stroke="none"/>
      <line x1="188" y1="10" x2="242" y2="10"/><polygon points="242,5 252,10 242,15" fill="#5B7FA8" stroke="none"/>
    </g>
    <g stroke="#E8C547" stroke-width="1.3">
      <line x1="368" y1="10" x2="422" y2="10"/><polygon points="422,5 432,10 422,15" fill="#E8C547" stroke="none"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.3">
      <line x1="548" y1="10" x2="602" y2="10"/><polygon points="602,5 612,10 602,15" fill="#C0504A" stroke="none"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="34" fill="#5B7FA8">authentic</text>
      <text x="0" y="52" fill="#6E6A64">strongest, full stop</text>
      <text x="180" y="34" fill="#5B7FA8">plagal</text>
      <text x="180" y="52" fill="#6E6A64">soft, afterglow</text>
      <text x="360" y="34" fill="#E8C547">half</text>
      <text x="360" y="52" fill="#6E6A64">hanging, comma</text>
      <text x="540" y="34" fill="#C0504A">deceptive</text>
      <text x="540" y="52" fill="#6E6A64">postponed, exclamation</text>
    </g>
    <text x="0" y="84" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The landing decides the tone: tonic closes, dominant suspends, anything else surprises
    </text>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Find the cadences first — their strength maps directly onto the level of division
    </text>
  </g>
</svg>
```

## Listen: the four cadences

In order: authentic (V→I, firmest), plagal (IV→I, softer), half (I→V, hanging), deceptive (V→vi, postponed).

```audiolab
{"type":"progression","key":"C4","degrees":["V","I"],"label":"正格终止 V → I","label_en":"Authentic cadence, V to I","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["V","vi"],"label":"阻碍终止 V → vi（被推迟）","label_en":"Deceptive cadence, V to vi — the close is postponed","hint":"与上一条对比：本来要落地，却拐走了","hint_en":"Compare with the item above — the landing is diverted"}
```

## Common misconceptions

- **"A cadence means an ending."** A half cadence does not end anything; it creates expectation. A cadence is punctuation, not only a full stop.
- **"The plagal cadence is a weaker authentic."** It is more like a different tone of voice — solemn, relaxed, with afterglow — rather than insufficient force.
- **"A deceptive cadence is a mistake."** It is a deliberate postponement device, commonly used to extend phrases.
- **"Cadences belong to classical music."** A pop song returning to the tonic, or resting on V, can be described in exactly the same language.
:::
