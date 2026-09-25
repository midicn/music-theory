---
id: melody
site: theo
cat: T8
title: 旋律的构成
title_en: The Making of a Melody
summary: 音阶是素材，旋律是从中做出的"选择 + 时间安排"
summary_en: A scale is material; a melody is a selection from it arranged in time
level: core
tags: [乐理, 旋律, 曲式]
tags_en: [theory, melody, form]
alias: [旋律, 旋律的构成, melody]
order: 10
links:
  - "[[concept:scale]]"
  - "[[concept:phrase]]"
  - "[[concept:motive]]"
  - "[[concept:rhythm]]"
  - "[[concept:interval-melodic-role]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：音域窄、级进为主、重复清楚，是"最省素材也能立住"的经典样本 | The Ode of Joy theme — narrow range, mostly stepwise, clear repetition — the classic proof that minimal material can stand
  - thesession-019704 | 《小星星》：只用五个音与两种时值，可用来验证"旋律的成立不依赖复杂素材" | Twinkle Little Star uses five notes and two values, showing a melody needs no complex material
  - mutopia-000049 | 《绿袖子》：旋律以级进与小跳展开、以长音收句，可与前两条对照不同时代的旋律写法 | Greensleeves unfolds in steps and small leaps and closes phrases on long notes, a contrast in melodic style
sources:
  - 旋律的四个可分析维度（音程关系 / 节奏 / 轮廓 / 句读）为旋律分析通行框架
  - 旋律的音高轮廓与节奏轮廓可相互独立变化，为通行旋律学表述
updated: 2026-09-25
---

::: zh
旋律的定义听起来平淡：**一串有组织的音高。** 但"有组织"三个字里全是内容。

先把旋律与音阶分开：

| | 音阶 | 旋律 |
|---|---|---|
| 是什么 | 一批**可用的音**（素材池） | 从中做出的**选择 + 时间安排** |
| 问的问题 | 用了哪些音？ | **为什么这样排列？** |

所以"这条旋律用了 C 大调音阶"几乎不说明任何事 ——
**C 大调音阶能生成无数条完全不同的旋律**。

## 四个可分析的维度

旋律之所以能被讨论，是因为它可以拆成四个**彼此独立**的维度：

| 维度 | 内容 | 常见判断 |
|---|---|---|
| **音程关系** | 级进多还是跳进多 | 级进为主 → 易唱、连贯；跳进 → 有个性、易记 |
| **节奏** | 长短组合 | 见 [[concept:rhythm|节奏]] 与 [[concept:rhythmic-pattern|节奏型]] |
| **轮廓** | 整体的走向（上行 / 下行 / 拱形） | 拱形（先上后下）最常见，与呼吸一致 |
| **句读** | 在哪里换气、哪里停 | 见 [[concept:phrase|乐句与乐段]] |

**四个维度独立**这件事很重要：它意味着**改一个维度而保留其余三个**是有意义的操作 ——
这正是"同一旋律换个节奏型就变成另一首曲子"能成立的原因。

## 旋律为什么最难讲清楚

和声有功能理论（T→S→D→T），节奏有等分与重音周期，**旋律没有对应的系统理论**。

这不是学者不努力，而是旋律的"好"高度依赖**文化与记忆**：

| 现象 | 说明 |
|---|---|
| 某些音程组合在一种文化里常见、在另一种里生疏 | 音阶与调式不同 |
| 同一旋律重复听会觉得"更顺" | 熟悉度本身影响判断 |
| 极简单的旋律也可能极动人 | 与复杂度无关 |

所以对旋律，我们能给出**可操作的经验**，但给不出"生成好旋律的算法"。

## 两条最有用的经验

**① 可记忆性来自"重复 + 变化"的比例。**

| 比例 | 效果 |
|---|---|
| 几乎不重复 | 难记，像散句 |
| 重复过多 | 单调，像练习 |
| **有重复又有变化** | **易记且不腻** —— 《小星星》的 aaba 结构就是典型 |

**② 音域窄的旋律往往更易唱、更易记。**
《欢乐颂》只用了一个八度附近；大量民歌也在一个八度内。
**这提醒我们：旋律的感染力不来自音域宽，而来自内部关系清楚。**

## 图示：四个维度各自独立

```svg
<svg viewBox="0 0 640 212" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一条旋律可以只改一个维度 —— 其余三个保持不变</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-22" y="6" text-anchor="end">原型</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="40" y="0">D</text><text x="80" y="0">E</text><text x="120" y="0">C</text>
    </g>
    <g fill="#E07A3F">
      <rect x="-12" y="10" width="24" height="12" rx="2"/><rect x="28" y="10" width="24" height="12" rx="2"/>
      <rect x="68" y="10" width="24" height="12" rx="2"/><rect x="108" y="10" width="24" height="12" rx="2"/>
    </g>

    <g transform="translate(0,54)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-22" y="6" text-anchor="end">只改节奏</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#E8C547" text-anchor="middle">
        <text x="0" y="0">C</text><text x="40" y="0">D</text><text x="80" y="0">E</text><text x="120" y="0">C</text>
      </g>
      <g fill="#E8C547">
        <rect x="-12" y="10" width="12" height="12" rx="2"/><rect x="4" y="10" width="12" height="12" rx="2"/>
        <rect x="28" y="10" width="24" height="12" rx="2"/>
        <rect x="68" y="10" width="48" height="12" rx="2"/>
      </g>
      <text x="140" y="20" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">音高不变，性格已变</text>
    </g>

    <g transform="translate(0,108)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-22" y="6" text-anchor="end">只改轮廓</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">C</text><text x="40" y="0">B</text><text x="80" y="0">A</text><text x="120" y="0">C</text>
      </g>
      <g fill="#5B7FA8">
        <rect x="-12" y="10" width="24" height="12" rx="2"/><rect x="28" y="10" width="24" height="12" rx="2"/>
        <rect x="68" y="10" width="24" height="12" rx="2"/><rect x="108" y="10" width="24" height="12" rx="2"/>
      </g>
      <text x="140" y="20" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">上行改成下行：情绪反转</text>
    </g>

    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      最有用的经验：可记忆性来自"重复 + 变化"的比例；音域窄的旋律往往更易唱、更易记
    </text>
  </g>
</svg>
```

## 听一听：三个维度的差别

用 `scale` 听一条音阶（级进为主，易唱），再想象把它改成以跳进为主 ——
**同样的音、同样的长度，可唱性立刻不同**。这就是"音程关系"这一维度的作用。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4"],"label":"级进为主（易唱、连贯）","label_en":"Mostly stepwise — singable and connected","hint":"点「上行」感受级进的连贯","hint_en":"Try Up and feel the continuity of stepwise motion","gap":0.36}
```

## 常见误解

- **「旋律就是音阶里的音」** → 音阶是**素材池**，旋律是**选择与安排**。同一音阶能生成无数不同旋律。
- **「旋律越复杂越好」** → 《小星星》只用五个音与两种时值，却传遍世界。**内部关系清楚**比素材复杂重要。
- **「旋律没法分析」** → 可以拆成四个维度（音程 / 节奏 / 轮廓 / 句读）分别讨论，只是没有"生成算法"。
- **「好旋律是天生的」** → 大量作品显示出共同经验（重复与变化的比例、音域的克制、拱形轮廓），这些是可学的。
:::

::: en
The definition sounds flat: **an organised succession of pitches.** But "organised" carries all the content.

First, separate melody from scale:

| | Scale | Melody |
|---|---|---|
| What it is | a set of **available pitches** (a pool) | a **selection plus arrangement in time** from that pool |
| The question it answers | which pitches? | **why arranged this way?** |

So "this melody uses the C major scale" tells you almost nothing — **the C major scale can generate countless
different melodies.**

## Four dimensions you can analyse

A melody can be discussed because it separates into four **independent** dimensions:

| Dimension | Content | Usual judgement |
|---|---|---|
| **intervals** | mostly steps or mostly leaps? | steps → singable and connected; leaps → characterful and memorable |
| **rhythm** | the combination of durations | see [[concept:rhythm|rhythm]] and [[concept:rhythmic-pattern|rhythmic pattern]] |
| **contour** | the overall shape (rising, falling, arched) | the arch (up then down) is commonest, matching the breath |
| **phrasing** | where it breathes, where it stops | see [[concept:phrase|phrase and period]] |

**That the four are independent** matters: it means **changing one while keeping the other three** is a meaningful
operation — which is why "one melody with a new rhythm becomes another tune" works.

## Why melody is the hardest thing to explain

Harmony has functional theory (T→S→D→T), rhythm has division and accent cycles — **melody has no equivalent
system**.

Not for want of effort: a melody's quality depends heavily on **culture and memory**.

| Phenomenon | Explanation |
|---|---|
| some interval patterns are common in one culture and foreign in another | different scales and modes |
| a melody feels "smoother" on repeated hearing | familiarity itself shapes judgement |
| an extremely simple melody can be deeply moving | nothing to do with complexity |

So for melody we can offer **workable experience** but not an algorithm that generates good ones.

## Two most useful pieces of experience

**One: memorability comes from the ratio of repetition to change.**

| Ratio | Effect |
|---|---|
| almost no repetition | hard to remember, like scattered phrases |
| too much repetition | monotonous, like an exercise |
| **repetition with change** | **memorable without weariness** — the aaba shape of Twinkle is the model |

**Two: melodies with a narrow range are usually easier to sing and to remember.**
The Ode of Joy stays close to an octave, and a great many folk songs do too. **Which reminds us: a melody's power
comes not from a wide range but from clear internal relations.**

## Diagram: four independent dimensions

```svg
<svg viewBox="0 0 640 212" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One melody with only one dimension changed — the other three untouched</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-22" y="6" text-anchor="end">original</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="40" y="0">D</text><text x="80" y="0">E</text><text x="120" y="0">C</text>
    </g>
    <g fill="#E07A3F">
      <rect x="-12" y="10" width="24" height="12" rx="2"/><rect x="28" y="10" width="24" height="12" rx="2"/>
      <rect x="68" y="10" width="24" height="12" rx="2"/><rect x="108" y="10" width="24" height="12" rx="2"/>
    </g>

    <g transform="translate(0,54)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-22" y="6" text-anchor="end">rhythm only</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#E8C547" text-anchor="middle">
        <text x="0" y="0">C</text><text x="40" y="0">D</text><text x="80" y="0">E</text><text x="120" y="0">C</text>
      </g>
      <g fill="#E8C547">
        <rect x="-12" y="10" width="12" height="12" rx="2"/><rect x="4" y="10" width="12" height="12" rx="2"/>
        <rect x="28" y="10" width="24" height="12" rx="2"/>
        <rect x="68" y="10" width="48" height="12" rx="2"/>
      </g>
      <text x="140" y="20" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">same pitches, new character</text>
    </g>

    <g transform="translate(0,108)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-22" y="6" text-anchor="end">contour only</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">C</text><text x="40" y="0">B</text><text x="80" y="0">A</text><text x="120" y="0">C</text>
      </g>
      <g fill="#5B7FA8">
        <rect x="-12" y="10" width="24" height="12" rx="2"/><rect x="28" y="10" width="24" height="12" rx="2"/>
        <rect x="68" y="10" width="24" height="12" rx="2"/><rect x="108" y="10" width="24" height="12" rx="2"/>
      </g>
      <text x="140" y="20" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">rising to falling: the mood reverses</text>
    </g>

    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Most useful experience: memorability comes from repetition against change; narrow ranges sing and stick better
    </text>
  </g>
</svg>
```

## Listen: the difference one dimension makes

Use `scale` to hear a scale (mostly steps, easy to sing) and then imagine it dominated by leaps — **the same
pitches at the same lengths, and immediately less singable.** That is the interval dimension at work.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4"],"label":"级进为主（易唱、连贯）","label_en":"Mostly stepwise — singable and connected","hint":"点「上行」感受级进的连贯","hint_en":"Try Up and feel the continuity of stepwise motion","gap":0.36}
```

## Common misconceptions

- **"A melody is the notes of a scale."** The scale is the **pool**; the melody is **selection and arrangement**.
  One scale yields countless melodies.
- **"More complex melody is better."** Twinkle uses five notes and two values and travelled the world. **Clear
  internal relations** matter more than complex material.
- **"Melody cannot be analysed."** It splits into four dimensions (intervals, rhythm, contour, phrasing) that can be
  discussed separately; there is simply no generative algorithm.
- **"Good melody is innate."** A large repertoire reveals shared experience (repetition against change, restraint of
  range, the arch contour) — all learnable.
:::
