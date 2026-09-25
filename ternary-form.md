---
id: ternary-form
site: theo
cat: T9
title: 三段体
title_en: Ternary Form
summary: ABA——出去再回来，最常见的曲式
summary_en: ABA — out and back, the commonest form of all
level: standard
tags: [乐理, 曲式, 结构]
tags_en: [theory, form, structure]
alias: [三段体, 三部曲式, ternary form, ABA]
order: 24
links:
  - "[[concept:form]]"
  - "[[concept:binary-form]]"
  - "[[concept:compound-ternary]]"
  - "[[concept:sonata-form]]"
  - "[[concept:phrase]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：常见的旋律组织为"陈述—对比—回归"，是 ABA 在声乐体裁里的基本形态 | An organ hymn — its melody commonly runs statement, contrast, return, the basic ABA shape in vocal genres
  - atepp-000355 | 格里格《抒情小品》：大量小品采用 ABA 结构，可听中段与回归段的对比 | Grieg's Lyric Pieces — many are in ABA, showing the contrast between middle section and return
  - mutopia-000049 | 《绿袖子》加固定低音：各段的变化可用来观察"回归"与"变化回归"的差别 | Greensleeves to a Ground — its variations show the difference between a plain return and a varied one
sources:
  - 三段体（ABA）的定义与"单三段 / 复三段"的区分，属曲式分析通则
  - 带再现的三段体与奏鸣曲式的区别在于是否伴随调性统一，为通行表述
updated: 2026-09-25
---

::: zh
三段体是最常见的曲式，结构就是三个字母：**A B A —— 出去，再回来。**

它之所以占据统治地位，原因在 [[concept:form|曲式]] 里已经讲过：
**它同时满足了"要新鲜"与"要完整"这两个矛盾的要求。**

| 部分 | 功能 | 听者的感受 |
|---|---|---|
| **A** | 陈述一个乐思 | 认识了 |
| **B** | 引入对比 | 新鲜 |
| **A** | 回归 | **完整、有结束感** |

## B 段的任务：对比，而不是发展

这一点容易混（尤其与 [[concept:sonata-form|奏鸣曲式]] 相比）：

| | 三段体的 B | 奏鸣曲式的展开部 |
|---|---|---|
| 对 A 的素材做什么 | **通常引入新材料**，或换调陈述 | **拆解 A 的素材**并发展 |
| 调性 | 常转到关系调或属调，但相对稳定 | **游移**，大量转调 |
| 功能 | 提供**对比** | 提供**激化** |

一句话：**B 是"换个话题"，不是"把话题拆开重讲"。**

## A 的回归：可以变

| 形态 | 标记 | 说明 |
|---|---|---|
| 完全重复 | ABA | 一字不差地回来（巴洛克与古典早期常见） |
| 变化回归 | **ABA′** | 回来时加装饰、加尾声 —— **实际作品里更常见** |

**ABA′ 比 ABA 更常见**，因为完全重复会显得机械；加一点变化既保留了"回归"的完整感，
又避免了僵硬。

## 单三段体 vs 复三段体

| | 单三段体（simple） | 复三段体（compound） |
|---|---|---|
| 每段的规模 | 乐段级别（见 [[concept:phrase|乐句与乐段]]） | **每段本身就是一个独立曲式** |
| 标记 | ABA | **A（本身是二段体/三段体）B A** |
| 例 | 歌曲、小品 | 圆舞曲、谐谑曲、进行曲（见 [[concept:compound-ternary|复三部曲式]]） |

区分方法很实用：**看每一段"能不能单独成篇"** ——
如果 A 段自己就是一个完整的 ABA，那外层就是复三段体。

## 与奏鸣曲式的关键差别

两者长得像（都是"出去—回来"），但有一处决定性差别：

> **三段体的回归是"重复"（回到原来的调、原来的样子）。**
> **奏鸣曲式的再现是"解决"（第二主题换了调，调性统一了）。**

判断法：**看 B 段有没有把素材拆开发展**（有 → 更接近奏鸣曲式），
以及**再现时有没有调性变化**（有 → 更接近奏鸣曲式）。

## 图示：ABA 的三个字母

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">A 陈述 → B 对比 → A 回归；B 换话题，不拆话题</text>
  </g>

  <g transform="translate(52,56)">
    <g fill="#5B7FA8"><rect x="0" y="-14" width="150" height="26" rx="3"/></g>
    <text x="75" y="4" font-family="system-ui,sans-serif" font-size="12" fill="#F2EEE6" text-anchor="middle">A</text>
    <g fill="#E07A3F"><rect x="164" y="-14" width="150" height="26" rx="3"/></g>
    <text x="239" y="4" font-family="system-ui,sans-serif" font-size="12" fill="#1A0E06" text-anchor="middle">B</text>
    <g fill="#5B7FA8"><rect x="328" y="-14" width="150" height="26" rx="3" opacity=".9"/></g>
    <text x="403" y="4" font-family="system-ui,sans-serif" font-size="12" fill="#F2EEE6" text-anchor="middle">A′</text>

    <g font-family="system-ui,sans-serif" font-size="10.5">
      <text x="75" y="30" fill="#5B7FA8" text-anchor="middle">陈述</text>
      <text x="239" y="30" fill="#E07A3F" text-anchor="middle">对比（新材料 / 换调）</text>
      <text x="403" y="30" fill="#5B7FA8" text-anchor="middle">回归（常带变化）</text>
    </g>

    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="150" y1="-30" x2="164" y2="-30"/>
      <line x1="314" y1="-30" x2="328" y2="-30"/>
    </g>

    <text x="0" y="64" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      单三段体：每段是乐段级别　｜　复三段体：每段本身就是一个独立曲式（见"复三部曲式"）
    </text>
    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      与奏鸣曲式的差别：B 有没有拆解素材；再现时有没有调性统一（有 → 更接近奏鸣曲式）
    </text>
  </g>
</svg>
```

## 听一听：陈述与回归

用 `progression` 听一组"陈述 → 离开 → 回归"的功能进行。
**最后一次回到 I 与第一次的 I 是同一个和弦，但听到的感受不同** —— 那就是"回归"的效果。

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"陈述 → 离开 → 回归","label_en":"Statement, departure, return","hint":"逐个和弦依次听：开头与结尾的 I 是同一个和弦","hint_en":"Hear each chord: the opening and closing I are the same chord"}
```

## 常见误解

- **「ABA 就是从头再来一遍」** → 回归**通常是变化回归（ABA′）**。完全重复反而少见，因为会显得机械。
- **「B 段是展开」** → B 的任务是**对比**，不是拆解发展（那是奏鸣曲式的展开部）。
- **「三段体和奏鸣曲式差不多」** → 关键差别在**调性有没有统一**，以及 **B 有没有发展素材**。
- **「单三段与复三段只是规模差别」** → 结构层级不同：单三段体的每段是乐段；复三段体的每段**本身就是一个曲式**。
:::

::: en
Ternary form is the commonest form of all, and its structure is three letters: **A B A — out, and back.**

Why it dominates was covered under [[concept:form|form]]: **it satisfies the two contradictory demands at once —
freshness and completeness.**

| Section | Function | What the listener feels |
|---|---|---|
| **A** | states an idea | "I know this" |
| **B** | introduces contrast | fresh |
| **A** | returns | **complete, finished** |

## The job of B: contrast, not development

This is easily confused (especially against [[concept:sonata-form|sonata form]]):

| | The B of a ternary form | A sonata development |
|---|---|---|
| What it does to A's material | **usually brings new material**, or restates in another key | **takes A apart** and develops it |
| Tonality | often to the relative or dominant key, but relatively stable | **unstable**, modulating widely |
| Function | provides **contrast** | provides **escalation** |

In one line: **B changes the subject; it does not dissect it.**

## The return can vary

| Shape | Label | Explanation |
|---|---|---|
| exact repeat | ABA | back note for note (common in the Baroque and early Classical) |
| varied return | **ABA′** | returns with ornament and often a coda — **more common in practice** |

**ABA′ outnumbers ABA**, because a literal repeat can sound mechanical; a small change keeps the completeness of
return without the stiffness.

## Simple versus compound ternary

| | Simple | Compound |
|---|---|---|
| Scale of each section | period level (see [[concept:phrase|phrase and period]]) | **each section is itself an independent form** |
| Label | ABA | **A (itself binary or ternary) B A** |
| Examples | songs, short pieces | waltzes, scherzos, marches (see [[concept:compound-ternary|compound ternary form]]) |

The test is practical: **can each section stand alone?** If A is itself a complete ABA, the outer form is compound.

## The decisive difference from sonata form

The two look alike (both "out and back"), but differ in one decisive respect:

> **A ternary return is repetition** (same key, same shape).
> **A sonata recapitulation is resolution** (the second subject is re-keyed; the tonality unifies).

How to tell: **did B take the material apart** (if so, closer to sonata form), and **does the return change the
tonality** (if so, closer to sonata form).

## Diagram: the three letters

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">A states, B contrasts, A returns; B changes the subject rather than dissecting it</text>
  </g>

  <g transform="translate(52,56)">
    <g fill="#5B7FA8"><rect x="0" y="-14" width="150" height="26" rx="3"/></g>
    <text x="75" y="4" font-family="system-ui,sans-serif" font-size="12" fill="#F2EEE6" text-anchor="middle">A</text>
    <g fill="#E07A3F"><rect x="164" y="-14" width="150" height="26" rx="3"/></g>
    <text x="239" y="4" font-family="system-ui,sans-serif" font-size="12" fill="#1A0E06" text-anchor="middle">B</text>
    <g fill="#5B7FA8"><rect x="328" y="-14" width="150" height="26" rx="3" opacity=".9"/></g>
    <text x="403" y="4" font-family="system-ui,sans-serif" font-size="12" fill="#F2EEE6" text-anchor="middle">A′</text>

    <g font-family="system-ui,sans-serif" font-size="10.5">
      <text x="75" y="30" fill="#5B7FA8" text-anchor="middle">statement</text>
      <text x="239" y="30" fill="#E07A3F" text-anchor="middle">contrast: new material or new key</text>
      <text x="403" y="30" fill="#5B7FA8" text-anchor="middle">return, often varied</text>
    </g>

    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="150" y1="-30" x2="164" y2="-30"/>
      <line x1="314" y1="-30" x2="328" y2="-30"/>
    </g>

    <text x="0" y="64" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Simple: each section at period level. Compound: each section is itself a complete form
    </text>
    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Versus sonata form: did B dissect the material, and does the return unify the tonality?
    </text>
  </g>
</svg>
```

## Listen: statement and return

Use `progression` on a statement-departure-return skeleton. **The closing I is the same chord as the opening I, but
it does not feel the same** — that is the effect of return.

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"陈述 → 离开 → 回归","label_en":"Statement, departure, return","hint":"逐个和弦依次听：开头与结尾的 I 是同一个和弦","hint_en":"Hear each chord: the opening and closing I are the same chord"}
```

## Common misconceptions

- **"ABA just means starting over."** The return is **usually varied (ABA′)**. A literal repeat is rarer because it
  sounds mechanical.
- **"B is a development."** B provides **contrast**, not dissection (that is the sonata development's job).
- **"Ternary and sonata form are much the same."** The decisive differences are **whether the tonality unifies** and
  whether **B develops the material**.
- **"Simple and compound ternary differ only in size."** The levels differ: in simple ternary each section is a
  period; in compound ternary **each section is itself a form**.
:::
