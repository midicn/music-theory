---
id: meter
site: theo
cat: T7
title: 拍号
title_en: Metre and Time Signature
summary: 规定每小节几拍、以什么音符为一拍——重音周期的写法
summary_en: How many beats per bar and which note gets the beat — the notation of the accent cycle
level: core
tags: [乐理, 节奏, 基础]
tags_en: [theory, rhythm, basics]
alias: [拍号, 节拍, time signature, metre]
order: 12
links:
  - "[[concept:rhythm]]"
  - "[[concept:metric-accent]]"
  - "[[concept:simple-compound-meter]]"
  - "[[concept:syncopation]]"
  - "[[concept:tempo]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：通常记在 4/4 里，每小节的骨架与重音都规整可数 | Scale and cadence exercises are usually notated in 4/4, with a regular, countable frame and accent per bar
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：三拍子的舞曲节拍贯穿全曲，"一格三拍"的循环非常清楚 | Liszt's transcription of Danse macabre — a triple metre runs through it, the three-beat cycle unmistakable
  - cyberhymnal-000695 | 管风琴圣咏：四拍子中"强—弱—次强—弱"的层次是圣咏呼吸与分句的基础 | An organ hymn — the strong-weak-medium-weak hierarchy of quadruple metre underpins its breathing and phrasing
sources:
  - 拍号由分子（每小节拍数）与分母（以何种音符为一拍）构成，属乐理通则
  - 小节线的功能是标记重音周期而非仅仅是分行，为通行乐理表述
updated: 2026-09-25
---

::: zh
拍号写成 `4/4` 这样的分数形式，两个数字各管一件事：

| 位置 | 含义 | 在 `4/4` 里 |
|---|---|---|
| **分子** | 每小节**几拍** | 4 拍 |
| **分母** | **以什么音符为一拍** | 四分音符（分母 4 = 1/4 音符） |

所以 `4/4` 读作"每小节四拍，以四分音符为一拍"；`6/8` 是"每小节六拍，以八分音符为一拍"。

## 小节线的真正功能

初学者常以为小节线只是"把谱子分段方便看"。它的真正功能是**标记重音周期**：

> **每一条小节线之前的那一拍，都是这一轮的"起点"（强拍）。**

也就是说，拍号不是装饰 —— 它规定了**重音每隔多久回来一次**（见 [[concept:metric-accent|强弱规律]]）。
这也解释了为什么**跨过小节线的音**在记谱上特别受关注：它直接违背了重音周期，
是制造紧张最省力的手段（见 [[concept:syncopation|切分]]）。

## 为什么 4/4 最常见

一个可观察到的事实：大量音乐用 4/4。原因不神秘 ——

| 因素 | 说明 |
|---|---|
| **对称** | 四拍可以再分成 2+2，与人的左右对称、步伐的交替吻合 |
| **余地** | 四拍的长度足够容纳一个短乐思，又不至于记不住 |
| **可分** | 可细分为八分、十六分，也可粗分为两个二分，弹性大 |

但要注意：**4/4 常见不等于"更正确"**。三拍子在舞曲（圆舞曲）里是主流，
复合拍子（6/8、9/8）在民间音乐里极为常见（见 [[concept:simple-compound-meter|单复混合拍子]]）。

## 拍号不决定速度

这是最常见的混淆之一：

| | 决定 |
|---|---|
| **拍号** | 每小节几拍、以什么音符为一拍（**结构**） |
| **速度** | 每分钟多少拍（**演奏参数**，见 [[concept:tempo|速度]]） |

同一个 3/4，可以快成圆舞曲，也可以慢成挽歌。**拍号给的是骨架，速度给的是心跳频率。**

## 图示：分子与分母各管什么

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">分子管"几拍"，分母管"以什么音符为一拍"</text>
  </g>

  <g transform="translate(56,54)">
    <g transform="translate(0,0)">
      <text x="0" y="0" font-family="Georgia,serif" font-size="24" fill="#E07A3F" text-anchor="middle">4</text>
      <line x1="-14" y1="8" x2="14" y2="8" stroke="#E07A3F" stroke-width="1.6"/>
      <text x="0" y="32" font-family="Georgia,serif" font-size="24" fill="#5B7FA8" text-anchor="middle">4</text>
      <text x="34" y="6" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">每小节 4 拍</text>
      <text x="34" y="32" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">以四分音符为一拍</text>
    </g>

    <g transform="translate(200,0)">
      <text x="0" y="0" font-family="Georgia,serif" font-size="24" fill="#E07A3F" text-anchor="middle">6</text>
      <line x1="-14" y1="8" x2="14" y2="8" stroke="#E07A3F" stroke-width="1.6"/>
      <text x="0" y="32" font-family="Georgia,serif" font-size="24" fill="#5B7FA8" text-anchor="middle">8</text>
      <text x="34" y="6" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">每小节 6 拍</text>
      <text x="34" y="32" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">以八分音符为一拍</text>
    </g>

    <g transform="translate(0,78)">
      <g stroke="#343439" stroke-width="1"><line x1="0" y1="0" x2="440" y2="0"/></g>
      <g stroke="#5B7FA8" stroke-width="1.8">
        <line x1="0" y1="-8" x2="0" y2="8"/><line x1="110" y1="-8" x2="110" y2="8"/>
        <line x1="220" y1="-8" x2="220" y2="8"/><line x1="330" y1="-8" x2="330" y2="8"/>
        <line x1="440" y1="-8" x2="440" y2="8"/>
      </g>
      <text x="0" y="26" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        小节线标记的正是"重音周期"——每条线之前的那一拍都是这一轮的起点（强拍）
      </text>
    </g>
    <text x="0" y="126" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      跨过小节线的音之所以显眼，就是因为它违背了这个周期 —— 切分的技术基础
    </text>
    <text x="0" y="148" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      拍号给骨架，速度给心跳频率：同一个 3/4 可以快成圆舞曲，也可以慢成挽歌
    </text>
  </g>
</svg>
```

## 听一听：四拍与三拍的循环

用 `rhythm` 组件对比 **4/4 均分**与 **3/4 均分**。请数"重音隔多久回来一次"——
这就是拍号在实际听感里唯一要传达的信息。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"4/4：每四拍一轮","label_en":"4/4: one cycle every four beats","hint":"点「播放」，数强拍隔几拍回来","hint_en":"Press play and count the beats between strong accents"}
```

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":88,"label":"3/4：每三拍一轮","label_en":"3/4: one cycle every three beats","hint":"与 4/4 对比：循环周期短了一拍","hint_en":"Compare with 4/4 — the cycle is one beat shorter"}
```

## 常见误解

- **「拍号就是节奏型」** → 拍号只规定**骨架**（几拍、什么音符为一拍）；具体的长短组合属于节奏（见 [[concept:rhythm|节奏]]）。
- **「6/8 就是 3/4」** → 拍数、每拍的单位与重音层次都不同：6/8 通常按两个大拍（复合拍子）感受。
- **「拍号决定速度」** → 完全独立。拍号是结构，速度是演奏参数。
- **「4/4 更"正统"」** → 它只是最常见。三拍子与复合拍子在舞曲、民间音乐里同样是主流。
:::

::: en
A time signature is written as a fraction, `4/4`, and each number does one job:

| Position | Meaning | In `4/4` |
|---|---|---|
| **numerator** | **how many beats** per bar | four beats |
| **denominator** | **which note gets the beat** | the quarter note (denominator 4 = a 1/4 note) |

So `4/4` reads "four beats per bar, the quarter note taking a beat"; `6/8` is "six beats per bar, the eighth note
taking a beat".

## What bar lines are really for

Beginners often think bar lines merely break the page up for reading. Their real function is to **mark the accent
cycle**:

> **The beat immediately before each bar line is the start of a new cycle — the strong beat.**

So the time signature is not decoration: it fixes **how often the accent returns** (see
[[concept:metric-accent|metric accent]]). It also explains why a **note crossing a bar line** attracts attention:
it directly contradicts the accent cycle, which makes it the cheapest available source of tension (see
[[concept:syncopation|syncopation]]).

## Why 4/4 is the most common

A plain observation, with plain reasons:

| Factor | Explanation |
|---|---|
| **symmetry** | four beats subdivide as 2+2, matching left-right symmetry and alternating steps |
| **room** | long enough to hold a short idea, short enough to remember |
| **divisibility** | subdivides into eighths and sixteenths, or groups into two halves — very flexible |

But note: **common is not the same as correct.** Triple metre dominates dance (the waltz), and compound metres
(6/8, 9/8) are everywhere in folk music (see [[concept:simple-compound-meter|simple, compound and irregular metre]]).

## The time signature does not set the tempo

One of the commonest confusions:

| | Decides |
|---|---|
| **time signature** | how many beats per bar, which note takes a beat (**structure**) |
| **tempo** | how many beats per minute (**performance parameter**, see [[concept:tempo|tempo]]) |

The same 3/4 can race as a waltz or drag as a lament. **The signature gives the frame; the tempo gives the pulse
rate.**

## Diagram: what each number controls

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The numerator sets how many beats; the denominator sets which note takes one</text>
  </g>

  <g transform="translate(56,54)">
    <g transform="translate(0,0)">
      <text x="0" y="0" font-family="Georgia,serif" font-size="24" fill="#E07A3F" text-anchor="middle">4</text>
      <line x1="-14" y1="8" x2="14" y2="8" stroke="#E07A3F" stroke-width="1.6"/>
      <text x="0" y="32" font-family="Georgia,serif" font-size="24" fill="#5B7FA8" text-anchor="middle">4</text>
      <text x="34" y="6" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">four beats per bar</text>
      <text x="34" y="32" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">quarter note takes a beat</text>
    </g>

    <g transform="translate(220,0)">
      <text x="0" y="0" font-family="Georgia,serif" font-size="24" fill="#E07A3F" text-anchor="middle">6</text>
      <line x1="-14" y1="8" x2="14" y2="8" stroke="#E07A3F" stroke-width="1.6"/>
      <text x="0" y="32" font-family="Georgia,serif" font-size="24" fill="#5B7FA8" text-anchor="middle">8</text>
      <text x="34" y="6" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">six beats per bar</text>
      <text x="34" y="32" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">eighth note takes a beat</text>
    </g>

    <g transform="translate(0,78)">
      <g stroke="#343439" stroke-width="1"><line x1="0" y1="0" x2="440" y2="0"/></g>
      <g stroke="#5B7FA8" stroke-width="1.8">
        <line x1="0" y1="-8" x2="0" y2="8"/><line x1="110" y1="-8" x2="110" y2="8"/>
        <line x1="220" y1="-8" x2="220" y2="8"/><line x1="330" y1="-8" x2="330" y2="8"/>
        <line x1="440" y1="-8" x2="440" y2="8"/>
      </g>
      <text x="0" y="26" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        Bar lines mark the accent cycle: the beat before each line opens a new cycle
      </text>
    </g>
    <text x="0" y="126" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      A note crossing a bar line stands out because it contradicts that cycle — the basis of syncopation
    </text>
    <text x="0" y="148" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Signature gives the frame, tempo gives the pulse: one 3/4 can waltz or lament
    </text>
  </g>
</svg>
```

## Listen: cycles of four and of three

Use the `rhythm` component to compare **even 4/4** with **even 3/4**. Count how many beats pass between accents —
that is the only information a time signature actually conveys to the ear.

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"4/4：每四拍一轮","label_en":"4/4: one cycle every four beats","hint":"点「播放」，数强拍隔几拍回来","hint_en":"Press play and count the beats between strong accents"}
```

```audiolab
{"type":"rhythm","sig":"3/4","pattern":"q q q","bpm":88,"label":"3/4：每三拍一轮","label_en":"3/4: one cycle every three beats","hint":"与 4/4 对比：循环周期短了一拍","hint_en":"Compare with 4/4 — the cycle is one beat shorter"}
```

## Common misconceptions

- **"The time signature is the rhythm."** It fixes only the **frame** (how many beats, which note takes one);
  specific durations belong to rhythm (see [[concept:rhythm|rhythm]]).
- **"6/8 is the same as 3/4."** The beat count, the beat unit and the accent hierarchy all differ: 6/8 is normally
  felt as two large beats (a compound metre).
- **"The time signature sets the tempo."** Entirely independent. The signature is structure; tempo is a performance
  parameter.
- **"4/4 is the 'proper' metre."** It is merely the commonest. Triple and compound metres are equally mainstream in
  dance and folk music.
:::
