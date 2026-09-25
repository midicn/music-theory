---
id: sonata-form
site: theo
cat: T9
title: 奏鸣曲式
title_en: Sonata Form
summary: 它不只是"三部分"——核心是调性的"先分裂、后统一"
summary_en: Not merely three sections — its core is a tonality first split, then unified
level: standard
tags: [乐理, 曲式, 古典]
tags_en: [theory, form, classical]
alias: [奏鸣曲式, 奏鸣曲快板曲式, sonata form]
order: 22
links:
  - "[[concept:form]]"
  - "[[concept:ternary-form]]"
  - "[[concept:thematic-development]]"
  - "[[concept:modulation]]"
  - "[[concept:cadence]]"
  - "[[concept:fugue-form]]"
instances:
  - atepp-000083 | 斯克里亚宾第一钢琴奏鸣曲 Op.6 第一乐章：标题即"Allegro con fuoco"，是奏鸣曲式第一乐章的标准形态 | Scriabin's Piano Sonata No.1 Op.6, first movement — marked Allegro con fuoco, the standard shape of a sonata-form opening movement
  - giantmidi-010674 | 莫扎特《双钢琴奏鸣曲乐章》K.Anh.42：标题直接写作"Sonata Movement"，可听两个主题的性格对比 | Mozart's Sonata Movement for Two Pianos K.Anh.42 — literally titled Sonata Movement, useful for hearing the two subjects' contrast
  - atepp-000295 | 斯卡拉蒂键盘奏鸣曲 K.208：单乐章的**二段体**，是奏鸣曲式出现之前的前身形态 | Scarlatti's Keyboard Sonata K.208 — a single-movement **binary** piece, the shape that preceded sonata form
sources:
  - 奏鸣曲式的三部分（呈示 / 展开 / 再现）与"呈示部调性分裂、再现部调性统一"的核心机制，属曲式分析通则
  - 该曲式在古典时期的中心地位与其"戏剧性"的关联，为音乐史通行表述
updated: 2026-09-25
---

::: zh
奏鸣曲式常被简化为"三部分"。但那只是外形 —— 它的内核是一个**调性设计**：

> **呈示部：两个主题分处两个调。**
> **再现部：两个主题统一到同一个调。**

**这才叫奏鸣曲式。** 少了这层"调性分裂 → 调性统一"，就只是一个普通的三段体。

## 三个部分各自做什么

| 部分 | 素材 | 调性 | 功能 |
|---|---|---|---|
| **呈示部** | 第一主题（主调）+ 第二主题（**属调或关系调**） | **分裂** | 建立对比与张力 |
| **展开部** | 把主题**拆开**、片段化（见 [[concept:thematic-development|主题的发展]]） | **游移**：大量转调，远离主调 | 激化张力 |
| **再现部** | 两个主题都回来 | **统一**：第二主题改在主调 | **解决张力** |

**再现部的关键不在"主题回来了"，而在"调性统一了"。** 这是它区别于 ABA 三段体的地方：

| | 三段体的 A 回归 | 奏鸣曲式的再现 |
|---|---|---|
| 回来的内容 | 同样的主题 + 同样的调 | 同样的主题，**但第二主题换了调** |
| 心理效果 | **重复**（回去了） | **解决**（矛盾消解了） |

## 为什么它成了古典时期最重要的曲式

因为它天然支持一种观感：**冲突 → 激化 → 解决**。

| 部分 | 对应 |
|---|---|
| 呈示部 | 提出两个有差异的东西（两个主题 + 两个调） |
| 展开部 | 让它们互相冲撞（素材拆解 + 调性游移） |
| 再现部 | 让它们在同一条线上和解（调性统一） |

这套结构在古典时期的交响曲、奏鸣曲、室内乐的第一乐章里普遍出现，
**因为它是当时审美里"严肃、有分量"的等价物**（见 [[concept:large-scale-forms|大型作品结构]]）。

## 三个常见变体

| 变体 | 说明 |
|---|---|
| **没有展开部** | 呈示部直接接再现部（常见于慢乐章、序曲） |
| **展开部吸收新材料** | 少数作品（尤其是浪漫派）在展开部引入新材料 |
| **奏鸣回旋曲式** | 奏鸣曲式与回旋曲式结合：A B A C A B A（见 [[concept:rondo-form|回旋曲式]]） |

## 图示：调性的分裂与统一

```svg
<svg viewBox="0 0 640 212" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">关键不是"三段"，而是两个主题的调性关系：先分开，再统一</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">呈示部</text>
      <text x="-20" y="54" text-anchor="end">展开部</text>
      <text x="-20" y="108" text-anchor="end">再现部</text>
    </g>

    <g>
      <rect x="0" y="-10" width="70" height="20" rx="3" fill="#5B7FA8"/>
      <text x="35" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">主调</text>
      <rect x="76" y="-10" width="70" height="20" rx="3" fill="#E07A3F"/>
      <text x="111" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">属调</text>
      <text x="158" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">← 两个主题分处两个调</text>
    </g>

    <g transform="translate(0,54)">
      <g fill="#343439">
        <rect x="0" y="-10" width="22" height="20" rx="2"/>
        <rect x="46" y="-10" width="22" height="20" rx="2"/>
        <rect x="76" y="-10" width="22" height="20" rx="2"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.4" stroke-dasharray="3 2">
        <line x1="0" y1="16" x2="120" y2="16"/>
      </g>
      <text x="132" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">拆解 + 大量转调（远离主调）</text>
    </g>

    <g transform="translate(0,108)">
      <rect x="0" y="-10" width="70" height="20" rx="3" fill="#E8C547"/>
      <text x="35" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">主调</text>
      <rect x="76" y="-10" width="70" height="20" rx="3" fill="#E8C547" opacity=".8"/>
      <text x="111" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">也回主调</text>
      <text x="158" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">← 统一：这才是"解决"</text>
    </g>

    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      三段体的 A 回归＝重复（回去了）；奏鸣曲式的再现＝解决（矛盾消解了）
    </text>
  </g>
</svg>
```

## 听一听：离开与回归

用 `progression` 听**主调 → 属调 → 回主调**的骨架。请留意最后那一次回主调：
**它不是"又弹了一遍"，而是"终于落定了"** —— 这正是奏鸣曲式再现部的心理效果。

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","V","I"],"label":"主调 → 属调（离开）→ 回主调（落定）","label_en":"Tonic to dominant, then home again","hint":"逐个和弦依次听：最后一次回到 I 就是“统一”","hint_en":"Hear each chord: the final return to I is the unification"}

```

## 常见误解

- **「奏鸣曲式＝奏鸣曲」** → 奏鸣曲是**体裁**（一种多乐章作品），奏鸣曲式是**曲式**（一种结构）。交响曲、协奏曲、室内乐的第一乐章也用奏鸣曲式。
- **「它只是三段体的一种」** → 关键在于**调性分裂与统一**；缺了这一层就只是 ABA（见 [[concept:ternary-form|三段体]]）。
- **「必须有两个主题」** → 常见但非必需。有些作品的两个"主题"其实是同一素材的不同形态；也有作品只有一个主题。
- **「必须有展开部」** → 慢乐章与序曲常省略展开部，直接呈示接再现。
:::

::: en
Sonata form is often reduced to "three sections". That is only the outline — its kernel is a **tonal design**:

> **Exposition: the two subjects sit in two different keys.**
> **Recapitulation: both subjects are brought into one key.**

**That is what makes it sonata form.** Without the "tonal split, then tonal unity", it is merely an ordinary ternary
shape.

## What each section does

| Section | Material | Tonality | Function |
|---|---|---|---|
| **exposition** | first subject (tonic) + second subject (**dominant or relative key**) | **split** | establish contrast and tension |
| **development** | the material **taken apart** and fragmented (see [[concept:thematic-development|thematic development]]) | **unstable**: much modulation, far from the tonic | intensify the tension |
| **recapitulation** | both subjects return | **unified**: the second subject is now in the tonic | **resolve the tension** |

**The point of the recapitulation is not that the subjects come back but that the tonality unifies.** That is where
it differs from ABA:

| | The A of a ternary form | A sonata-form recapitulation |
|---|---|---|
| What returns | the same subject in the same key | the same subjects, **but the second in a new key** |
| Psychological effect | **repetition** (we came back) | **resolution** (the conflict is dissolved) |

## Why it became the central form of the Classical era

Because it naturally supports one shape: **conflict, escalation, resolution.**

| Section | Corresponds to |
|---|---|
| exposition | presenting two things that differ (two subjects, two keys) |
| development | letting them collide (material fragmented, tonality adrift) |
| recapitulation | letting them reconcile on one line (tonal unity) |

The design appears throughout Classical symphonies, sonatas and chamber works, **because it was the period's
equivalent of "serious, weighty"** (see [[concept:large-scale-forms|large-scale structures]]).

## Three common variants

| Variant | Explanation |
|---|---|
| **no development** | exposition runs straight into recapitulation (common in slow movements and overtures) |
| **new material in the development** | a minority practice, mostly Romantic |
| **sonata-rondo** | sonata form combined with rondo: A B A C A B A (see [[concept:rondo-form|rondo form]]) |

## Diagram: the tonal split and unification

```svg
<svg viewBox="0 0 640 212" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The point is not "three sections" but the two subjects' tonal relation: split first, unify after</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">exposition</text>
      <text x="-20" y="54" text-anchor="end">development</text>
      <text x="-20" y="108" text-anchor="end">recapitulation</text>
    </g>

    <g>
      <rect x="0" y="-10" width="70" height="20" rx="3" fill="#5B7FA8"/>
      <text x="35" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">tonic</text>
      <rect x="76" y="-10" width="70" height="20" rx="3" fill="#E07A3F"/>
      <text x="111" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">dominant</text>
      <text x="158" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">two subjects, two keys</text>
    </g>

    <g transform="translate(0,54)">
      <g fill="#343439">
        <rect x="0" y="-10" width="22" height="20" rx="2"/>
        <rect x="46" y="-10" width="22" height="20" rx="2"/>
        <rect x="76" y="-10" width="22" height="20" rx="2"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.4" stroke-dasharray="3 2">
        <line x1="0" y1="16" x2="120" y2="16"/>
      </g>
      <text x="132" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">fragmented, modulating far from home</text>
    </g>

    <g transform="translate(0,108)">
      <rect x="0" y="-10" width="70" height="20" rx="3" fill="#E8C547"/>
      <text x="35" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">tonic</text>
      <rect x="76" y="-10" width="70" height="20" rx="3" fill="#E8C547" opacity=".8"/>
      <text x="111" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">also tonic</text>
      <text x="158" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">unified: that is the resolution</text>
    </g>

    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      A ternary return is repetition; a sonata recapitulation is resolution
    </text>
  </g>
</svg>
```

## Listen: departure and return

Use `progression` to hear the skeleton **tonic, dominant, back to tonic**. Notice the final return: **it is not
"here it is again" but "everything has settled"** — precisely the psychological effect of a recapitulation.

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","V","I"],"label":"主调 → 属调（离开）→ 回主调（落定）","label_en":"Tonic to dominant, then home again","hint":"逐个和弦依次听：最后一次回到 I 就是统一","hint_en":"Hear each chord: the final return to I is the unification"}
```

## Common misconceptions

- **"Sonata form means a sonata."** A sonata is a **genre** (a multi-movement work); sonata form is a **structure**.
  Symphonies, concertos and chamber works use it for their first movements too.
- **"It is just a kind of ternary form."** The decisive feature is **tonal split and unification**; without it, it is
  only ABA (see [[concept:ternary-form|ternary form]]).
- **"Two subjects are required."** Common but not essential. In some works the two "subjects" are different shapes of
  one idea; others have only one subject.
- **"A development section is required."** Slow movements and overtures often omit it, joining exposition straight to
  recapitulation.
:::
