---
id: rondo-form
site: theo
cat: T9
title: 回旋曲式
title_en: Rondo Form
summary: ABACA——A 反复回来，插部每次不同
summary_en: ABACA — A keeps coming back while the episodes differ each time
level: standard
tags: [乐理, 曲式, 结构]
tags_en: [theory, form, structure]
alias: [回旋曲式, 回旋曲, rondo, rondeau]
order: 28
links:
  - "[[concept:form]]"
  - "[[concept:ternary-form]]"
  - "[[concept:sonata-form]]"
  - "[[concept:theme-variations]]"
instances:
  - atepp-000498 | 匈牙利狂想曲：段落反复回归、每次回归后接新材料，接近"回旋"的组织逻辑 | A Hungarian Rhapsody — sections return repeatedly with new material after each return, close to rondo logic
  - cyberhymnal-000695 | 管风琴圣咏：常见的"叠句—诗句—叠句"结构，与回旋曲式的 A—B—A 同源 | An organ hymn — the refrain-verse-refrain shape is the same family as rondo's A-B-A
  - giantmidi-006222 | 音阶与终止练习：反复回到同一个中心（主和弦），可听"回归"在最小尺度上的效果 | Scale and cadence exercises keep returning to one centre (the tonic), return at its smallest scale
sources:
  - 回旋曲式的定义（ABACA，A 反复回归、插部各不相同）与古典时期的完整形态，属曲式分析通则
  - 回旋曲式常用作古典奏鸣曲、交响曲的末乐章，为通行表述
updated: 2026-09-25
---

::: zh
回旋曲式的结构是 **A B A C A** —— 一个主题反复回来，每次之间换新内容。

> **A 是"回家的路"，B 与 C 是"出门"。**

## 为什么它有效

它和 [[concept:ternary-form|三段体]] 是同一种心理机制，只是用得**更多次**：

| 部分 | 功能 |
|---|---|
| **A** | 熟悉的主题（回归） |
| **B、C** | 插部（**每次都不一样**） |

**关键在"每次不一样"**：如果插部重复，就成了变奏或三段体的延长。
所以回旋曲式的精髓是：**回归可以重复，出门必须新鲜。**

这带来一个实用的优点：**它可以被任意延长** ——
想让作品更长，就多插一个插部，A 再回来一次即可。所以它特别适合**末乐章**（收束、明亮、热闹）。

## 完整形态与常见变体

| 形态 | 结构 | 说明 |
|---|---|---|
| 简单回旋 | **A B A C A** | 五个部分，最标准 |
| 完整古典回旋 | **A B A C A B A** + 尾声 | 末乐章常用；A 四次出现，末次前有主题再现感 |
| 回旋奏鸣曲式 | **A B A C A B A**，但带奏鸣曲式的调性设计 | 见下 |

**回旋奏鸣曲式**（sonata-rondo）值得单独知道：它的外表是回旋曲式，
但内部按 [[concept:sonata-form|奏鸣曲式]] 的规则安排调性 ——
**B 段相当于"第二主题"（在属调），末次 A B A 中 B 回到主调**。
所以它是两种曲式的杂交：**外形是回旋，逻辑是奏鸣。**

## 与三段体的区别：只看一件事

| | 三段体 | 回旋曲式 |
|---|---|---|
| A 回来的次数 | **一次** | **两次或以上** |
| 标记 | ABA | ABACA / ABACABA |

一句话：**A 回来一次是三段体，回来两次以上是回旋曲式。**

## 历史上的近亲：副歌

"叠句（refrain）— 诗句（verse）— 叠句"这个结构在声乐里非常古老 ——
中世纪与文艺复兴的法国回旋诗（rondeau）、民间歌曲、教堂圣咏里都有。
**它和流行歌"副歌反复回归"的结构是同一个原理**：用熟悉的段落做锚点，
让新内容有地方可挂（见 [[concept:song-form|歌曲形式]]）。

## 图示：A 作为锚点

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">A 反复回来做锚点，插部每次换新 —— 这条结构可以任意延长</text>
  </g>

  <g transform="translate(52,56)">
    <g fill="#5B7FA8"><rect x="0" y="-14" width="70" height="24" rx="3"/></g>
    <text x="35" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>
    <g fill="#E07A3F"><rect x="78" y="-14" width="70" height="24" rx="3"/></g>
    <text x="113" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">B</text>
    <g fill="#5B7FA8"><rect x="156" y="-14" width="70" height="24" rx="3"/></g>
    <text x="191" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>
    <g fill="#E8C547"><rect x="234" y="-14" width="70" height="24" rx="3"/></g>
    <text x="269" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">C</text>
    <g fill="#5B7FA8"><rect x="312" y="-14" width="70" height="24" rx="3"/></g>
    <text x="347" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>

    <g stroke="#343439" stroke-width="1.2" stroke-dasharray="3 3">
      <line x1="35" y1="16" x2="35" y2="34"/>
      <line x1="191" y1="16" x2="191" y2="34"/>
      <line x1="347" y1="16" x2="347" y2="34"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.6">
      <line x1="0" y1="34" x2="382" y2="34"/>
    </g>
    <text x="191" y="52" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">回归（锚点，每次都是同一段）</text>

    <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      出门必须新鲜：插部若重复，就不是回旋曲式，而成了变奏或加长的三段体
    </text>
    <text x="0" y="104" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      判断与三段体的差别只看一件事：A 回来一次（三段体）还是两次以上（回旋曲式）
    </text>
    <text x="0" y="126" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      回旋奏鸣曲式：外形是回旋，内部按奏鸣曲式安排调性 —— 两种曲式的杂交
    </text>
  </g>
</svg>
```

## 听一听：反复回到同一个中心

用 `progression` 听"离开—回归—再离开—再回归"。请留意**每次回到 I 的感受都一样** ——
这就是 A 作为锚点的效果，也是回旋曲式能被任意延长的原因。

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I","IV","I"],"label":"离开 → 回归 → 再离开 → 再回归","label_en":"Out, home, out again, home again","hint":"逐个和弦依次听：注意每次回到 I 的同一感受","hint_en":"Hear each chord: notice that every return to I feels the same"}
```

## 常见误解

- **「回旋曲式就是 ABA 加长」** → 关键是**插部每次不同**。插部重复的话，性质就成了变奏。
- **「它是古老而简单的曲式」** → 结构上简单，但**要求作曲家写多个不重复的插部**，写作难度并不低。
- **「回旋曲式只用于末乐章」** → 末乐章最常见，但独立的回旋曲（如钢琴小品）也大量存在。
- **「回旋奏鸣曲式是把两种曲式轮流用」** → 不是轮流，而是**外形回旋、内部奏鸣** —— 是一套统一的结构。
:::

::: en
Rondo form is **A B A C A** — one theme returning repeatedly, with new material in between.

> **A is the road home; B and C are the outings.**

## Why it works

It uses the same psychological mechanism as [[concept:ternary-form|ternary form]], only more often:

| Section | Function |
|---|---|
| **A** | the familiar theme (return) |
| **B, C** | episodes (**each one different**) |

**The key is "each one different"**: if the episodes repeated, the result would be a variation set or an extended
ternary form. So the essence of a rondo is: **returns may repeat, outings must stay fresh.**

That brings a practical advantage: **it can be extended at will** — want a longer piece, insert another episode and
bring A back again. Which makes it ideal for **final movements** (closing, bright, lively).

## The full shape and common variants

| Shape | Structure | Note |
|---|---|---|
| simple rondo | **A B A C A** | five parts, the standard |
| full Classical rondo | **A B A C A B A** + coda | common in final movements; A appears four times |
| sonata-rondo | **A B A C A B A**, with sonata-form tonal planning | see below |

**Sonata-rondo** deserves separate mention: outwardly a rondo, but its tonality follows
[[concept:sonata-form|sonata form]] — **B acts as a "second subject" in the dominant, and in the closing A B A, B
returns to the tonic**. It is a hybrid: **rondo in shape, sonata in logic.**

## The difference from ternary form: one thing only

| | Ternary | Rondo |
|---|---|---|
| How often A returns | **once** | **twice or more** |
| Label | ABA | ABACA / ABACABA |

In one line: **one return is ternary; two or more returns is a rondo.**

## A historical relative: the refrain

The shape "refrain, verse, refrain" is very old in vocal music — the medieval and Renaissance French rondeau,
folk song and chant all use it. **It works on the same principle as a pop chorus that keeps returning**: a familiar
section acts as an anchor, giving new material somewhere to hang (see [[concept:song-form|song form]]).

## Diagram: A as the anchor

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">A returns as an anchor while each episode brings something new — the shape extends at will</text>
  </g>

  <g transform="translate(52,56)">
    <g fill="#5B7FA8"><rect x="0" y="-14" width="70" height="24" rx="3"/></g>
    <text x="35" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>
    <g fill="#E07A3F"><rect x="78" y="-14" width="70" height="24" rx="3"/></g>
    <text x="113" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">B</text>
    <g fill="#5B7FA8"><rect x="156" y="-14" width="70" height="24" rx="3"/></g>
    <text x="191" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>
    <g fill="#E8C547"><rect x="234" y="-14" width="70" height="24" rx="3"/></g>
    <text x="269" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">C</text>
    <g fill="#5B7FA8"><rect x="312" y="-14" width="70" height="24" rx="3"/></g>
    <text x="347" y="3" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">A</text>

    <g stroke="#343439" stroke-width="1.2" stroke-dasharray="3 3">
      <line x1="35" y1="16" x2="35" y2="34"/>
      <line x1="191" y1="16" x2="191" y2="34"/>
      <line x1="347" y1="16" x2="347" y2="34"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.6">
      <line x1="0" y1="34" x2="382" y2="34"/>
    </g>
    <text x="191" y="52" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">returns: the anchor, always the same music</text>

    <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Outings must stay fresh: repeated episodes make it a variation set, not a rondo
    </text>
    <text x="0" y="104" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Versus ternary: one return (ternary) or two or more (rondo)
    </text>
    <text x="0" y="126" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      Sonata-rondo: rondo in shape, sonata in tonal logic — a hybrid of two forms
    </text>
  </g>
</svg>
```

## Listen: returning to the same centre

Use `progression` on "out, home, out again, home again". Notice that **every return to I feels the same** — the
effect of A as an anchor, and the reason a rondo can be extended at will.

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I","IV","I"],"label":"离开 → 回归 → 再离开 → 再回归","label_en":"Out, home, out again, home again","hint":"逐个和弦依次听：注意每次回到 I 的同一感受","hint_en":"Hear each chord: notice that every return to I feels the same"}
```

## Common misconceptions

- **"A rondo is just a longer ABA."** The key is that **the episodes differ each time**. Repeated episodes turn it
  into a variation set.
- **"It is an old and simple form."** Structurally simple, but it demands **several non-repeating episodes** — not
  easy to write well.
- **"Rondos are only for final movements."** Most common there, but stand-alone rondos (piano pieces, for instance)
  are plentiful.
- **"Sonata-rondo alternates the two forms."** It does not alternate: it is **rondo in shape and sonata in logic** —
  one unified structure.
:::
