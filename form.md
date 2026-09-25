---
id: form
site: theo
cat: T9
title: 曲式
title_en: Musical Form
summary: 曲式就是"重复、对比、回归"的组合方式——不是模子，是组织原则
summary_en: Form is how repetition, contrast and return are combined — not a mould but an organising principle
level: core
tags: [乐理, 曲式, 结构]
tags_en: [theory, form, structure]
alias: [曲式, 曲式学, musical form]
order: 10
links:
  - "[[concept:phrase]]"
  - "[[concept:cadence]]"
  - "[[concept:rhythm]]"
  - "[[concept:genre-vs-form]]"
  - "[[concept:sonata-form]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：八小节内就有一个完整的"陈述—收束"结构，是最小的曲式样本 | The Ode of Joy runs a complete statement-and-close inside eight bars — form in miniature
  - thesession-019704 | 《小星星》：aaba 四句，可用来演示"字母标记法"的最简单用法 | Twinkle Little Star is aaba, the simplest demonstration of letter labelling
  - atepp-000498 | 匈牙利狂想曲：段落由情绪与速度组织，接近"自由曲式"，可与规则曲式对照 | A Hungarian Rhapsody organises its sections by mood and tempo, close to free form — a contrast with schematic forms
sources:
  - 曲式的基本组织手段（重复 / 对比 / 变奏 / 回归）与字母标记法，属曲式分析通则
  - 曲式划分以终止式与段落对比为依据，为通行表述
updated: 2026-09-25
---

::: zh
曲式问的是一个问题：**一段几分钟的音乐，靠什么被组织起来？**

答案不神秘 —— 音乐只有四种组织手段，曲式就是它们的**组合方式**：

| 手段 | 作用 | 听者的感受 |
|---|---|---|
| **重复** | 把听过的东西再来一遍 | 熟悉、好记 |
| **对比** | 引入不同的东西 | 新鲜、有话可说 |
| **变奏** | 重复中带改变 | 熟悉又新鲜 |
| **回归** | 把开头的东西带回来 | **完整感、结束感** |

**回归**最值得注意：它是"大篇幅音乐能被理解"的关键 ——
离开后再回来，听者才知道自己走了多远、回到了哪里。

## 曲式名 = 字母标记

分析曲式用字母标记，每个字母代表一个段落：

| 结构 | 标记 | 说明 |
|---|---|---|
| 一段体 | **A** | 一个乐思自足 |
| 二段体 | **AB** | 两段对比，常用于舞曲 |
| 三段体 | **ABA** | 出去再回来 —— **最常见的曲式** |
| 回旋曲式 | **ABACA** | A 反复回归（见 [[concept:rondo-form|回旋曲式]]） |
| 变奏曲式 | **A A₁ A₂ A₃ …** | 同一主题不断换装（见 [[concept:theme-variations|变奏曲式]]） |

**ABA 为什么最常见**：它同时满足了"要新鲜"与"要完整"这两个矛盾的要求 ——
B 提供新东西，A 的回归提供结束感。**这一条心理机制解释了大量曲式的设计。**

## 怎么判断曲式：三步

| 步骤 | 做什么 |
|---|---|
| **1** | **找终止式** —— 段落边界几乎总是由终止式划出（见 [[concept:cadence|终止式]]） |
| **2** | **比素材** —— 各段的旋律/和声素材是否相同 |
| **3** | **标字母** —— 相同的用同一个字母，变化的加撇（A、A′） |

**第 1 步不能跳过。** 只靠"听感觉得这里告一段落"来划段落，
常会把一个八小节的乐段切成两半 —— 因为乐段内部本身就有一次停顿（见 [[concept:phrase|乐句与乐段]]）。

## 曲式不是模子

这是最重要的观念纠正：

> **曲式不是先把"ABA"三个格子画好、再往里填音乐。**
> 它是**从无数具体作品的写法里总结出来的模式**。

所以：

| 错误的理解 | 正确的理解 |
|---|---|
| 曲式是作曲的规则 | 曲式是**分析的描述** |
| 必须符合某个曲式 | 大量作品**混合**多种曲式，或自成一格 |
| 分析不上就是"没有曲式" | "自由曲式"也是一种曲式（见 [[concept:free-form|自由曲式]]） |

## 图示：四种手段的组合

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">四个手段 → 三种典型组合；回归是"大篇幅能被听懂"的关键</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="6" text-anchor="end">重复</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="-6" width="60" height="18" rx="2"/>
      <rect x="66" y="-6" width="60" height="18" rx="2" opacity=".8"/>
    </g>
    <text x="140" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">AA：熟悉、好记（太多则单调）</text>

    <g transform="translate(0,38)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="-20" y="6" text-anchor="end">对比</text>
      </g>
      <g fill="#E8C547"><rect x="0" y="-6" width="60" height="18" rx="2"/></g>
      <g fill="#E07A3F"><rect x="66" y="-6" width="60" height="18" rx="2"/></g>
      <text x="140" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">AB：新鲜（无回归则无结束感）</text>
    </g>

    <g transform="translate(0,76)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="-20" y="6" text-anchor="end">回归</text>
      </g>
      <g fill="#5B7FA8"><rect x="0" y="-6" width="60" height="18" rx="2"/></g>
      <g fill="#E07A3F"><rect x="66" y="-6" width="60" height="18" rx="2"/></g>
      <g fill="#5B7FA8"><rect x="132" y="-6" width="60" height="18" rx="2"/></g>
      <text x="206" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">ABA：出去再回来 —— 最常见的曲式</text>
    </g>

    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      判断三步：① 找终止式 ② 比素材 ③ 标字母 —— 第 1 步不能跳过
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      曲式不是模子：它是从无数具体作品里总结出来的模式，不是作曲前先画好的格子
    </text>
  </g>
</svg>
```

## 听一听：段落与回归

本站听辨件是单声部的，无法演示整段曲式。这里用 `progression` 听一组"出去再回来"的和声骨架 ——
**离开主调再回来**，正是 ABA 在最小尺度上的样子。

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I"],"label":"离开与回归（T → D → T）","label_en":"Departure and return: T-D-T","hint":"逐个和弦依次听：中间那一下就是“出去”","hint_en":"Hear each chord: the middle one is the departure"}

```

## 常见误解

- **「曲式是作曲的模子」** → 曲式是**分析的描述**，从具体作品里总结出来，不是作曲前的规定。
- **「曲式就是结构图」** → 结构图是结果；曲式讲的是**靠什么手段把音乐组织起来**（重复 / 对比 / 变奏 / 回归）。
- **「分析不出曲式的作品就是没有曲式」** → "自由曲式"也是一种曲式；没有明显重复与回归的作品同样有组织方式。
- **「曲式与体裁是一回事」** → 一个是**结构**，一个是**用途与场合**（见 [[concept:genre-vs-form|体裁与曲式辨异]]）。
:::

::: en
Form asks one question: **what holds a few minutes of music together?**

The answer is not mysterious — music has only four means of organisation, and form is how they are combined:

| Means | Function | What the listener feels |
|---|---|---|
| **repetition** | say it again | familiarity, memorability |
| **contrast** | introduce something different | freshness, something to say |
| **variation** | repeat with change | familiar yet new |
| **return** | bring the opening back | **completeness, a sense of ending** |

**Return** deserves the most attention: it is what makes long music comprehensible — after leaving and coming back,
the listener knows how far they travelled and where they are.

## Form names are letter labels

Analysis labels each section with a letter:

| Structure | Label | Explanation |
|---|---|---|
| one-part | **A** | a single self-sufficient idea |
| binary | **AB** | two contrasting sections, common in dances |
| ternary | **ABA** | out and back — **the commonest form of all** |
| rondo | **ABACA** | A returns repeatedly (see [[concept:rondo-form|rondo form]]) |
| variations | **A A₁ A₂ A₃ …** | one theme repeatedly re-dressed (see [[concept:theme-variations|variation form]]) |

**Why ABA is the commonest**: it satisfies two contradictory demands at once — B supplies something new, and A's
return supplies the ending. **That one psychological mechanism explains a great deal of formal design.**

## How to decide the form: three steps

| Step | Do this |
|---|---|
| **1** | **find the cadences** — section boundaries are almost always drawn by cadences (see [[concept:cadence|cadence]]) |
| **2** | **compare material** — are the melodic and harmonic materials the same? |
| **3** | **label with letters** — same material, same letter; altered material takes a prime (A, A′) |

**Step 1 cannot be skipped.** Dividing sections by "it felt like a pause here" will often split an eight-bar period
in half, because a period contains an internal pause of its own (see [[concept:phrase|phrase and period]]).

## Form is not a mould

The most important correction:

> **Form is not three boxes labelled A B A drawn first and filled with music afterwards.**
> It is a **pattern generalised from countless actual works.**

So:

| Misreading | Correct reading |
|---|---|
| form is a rule for composing | form is a **description for analysis** |
| a work must fit one form | many works **mix** forms, or follow one of their own |
| if no form fits, there is no form | free form is also a form (see [[concept:free-form|free form]]) |

## Diagram: combinations of the four means

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Four means, three typical combinations; return is what makes long music intelligible</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="6" text-anchor="end">repetition</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="-6" width="60" height="18" rx="2"/>
      <rect x="66" y="-6" width="60" height="18" rx="2" opacity=".8"/>
    </g>
    <text x="140" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">AA: familiar, memorable — too much is monotonous</text>

    <g transform="translate(0,38)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="-20" y="6" text-anchor="end">contrast</text>
      </g>
      <g fill="#E8C547"><rect x="0" y="-6" width="60" height="18" rx="2"/></g>
      <g fill="#E07A3F"><rect x="66" y="-6" width="60" height="18" rx="2"/></g>
      <text x="140" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">AB: fresh — but without return there is no ending</text>
    </g>

    <g transform="translate(0,76)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="-20" y="6" text-anchor="end">return</text>
      </g>
      <g fill="#5B7FA8"><rect x="0" y="-6" width="60" height="18" rx="2"/></g>
      <g fill="#E07A3F"><rect x="66" y="-6" width="60" height="18" rx="2"/></g>
      <g fill="#5B7FA8"><rect x="132" y="-6" width="60" height="18" rx="2"/></g>
      <text x="206" y="6" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">ABA: out and back, the commonest form</text>
    </g>

    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Three steps: find the cadences, compare the material, label the letters — never skip the first
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      Form is not a mould: it is generalised from works, not drawn before composing
    </text>
  </g>
</svg>
```

## Listen: sections and return

This site cannot play a whole form. Use `progression` to hear a harmonic skeleton that **leaves and comes back** —
departure from the tonic and return is ABA at its smallest scale.

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I"],"label":"离开与回归（T → D → T）","label_en":"Departure and return: T-D-T","hint":"逐个和弦依次听：中间那一下就是出去","hint_en":"Hear each chord: the middle one is the departure"}
```

## Common misconceptions

- **"Form is a mould for composing."** Form is a **description for analysis**, generalised from works rather than
  prescribed before writing.
- **"Form is just a structural diagram."** A diagram is the result; form concerns **what means hold the music
  together** (repetition, contrast, variation, return).
- **"If no form fits, there is no form."** Free form is also a form; works with no obvious repetition or return are
  still organised.
- **"Form and genre are the same."** One is **structure**, the other **use and occasion** (see
  [[concept:genre-vs-form|genre versus form]]).
:::
