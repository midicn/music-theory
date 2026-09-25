---
id: breath-phrasing
site: theo
cat: T8
title: 旋律的呼吸与句读
title_en: Breathing and Phrasing
summary: 旋律有呼吸——这是它区别于音阶跑动的关键
summary_en: A melody breathes — which is what separates it from a run of notes
level: standard
tags: [乐理, 旋律, 演奏]
tags_en: [theory, melody, performance]
alias: [呼吸, 句读, 分句, phrasing]
order: 18
links:
  - "[[concept:phrase]]"
  - "[[concept:melody]]"
  - "[[concept:cadence]]"
  - "[[concept:climax]]"
  - "[[concept:rhythm-training]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：乐句的收尾都用较长时值"落地"，呼吸点非常明显 | The Ode of Joy closes each phrase on a longer value — the breathing points are unmistakable
  - mutopia-000049 | 《绿袖子》：乐句以长音收束，句读清楚，适合照着"唱一遍"来找出气口 | Greensleeves ends its phrases on long notes with clear punctuation, ideal for singing through to find the breaths
  - cyberhymnal-000695 | 管风琴圣咏：旋律与诗句句读一致，文字结构直接给出呼吸位置 | An organ hymn — the melody follows the punctuation of the verse, so the words give the breathing places directly
sources:
  - 旋律呼吸的常见信号（长音、休止、终止式）为旋律与演唱实践通行表述
  - 声乐呼吸长度对旋律写作的约束（"可唱性"）为歌曲写作通则
updated: 2026-09-25
---

::: zh
旋律与音阶跑动的区别，不在音的选择，而在**呼吸**：

> **音阶跑动是一直往前；旋律会停、会喘、会收。**

所以判断一段音乐是"旋律"还是"跑动"，只要问一句：**它在哪里呼吸？** 答不上来，它就是跑动。

## 呼吸的三个信号

| 信号 | 说明 | 强度 |
|---|---|---|
| **长音** | 一个音明显比周围长，形成"停留" | 弱到中 |
| **休止** | 直接给出空隙 | 中 |
| **终止式** | 和声层面的收束（见 [[concept:cadence|终止式]]） | **最强** |

三者的强度不同，所以**句读是有层级的**：
长音是"逗号"，休止是"分号"，终止式是"句号"。
一段音乐的段落级别，就看它停在哪里（见 [[concept:phrase|乐句与乐段]]）。

## 声乐优先原则：为呼吸写旋律

一个很实用的事实：**旋律的句长受呼吸限制**。

| 演唱者 | 一个自然呼吸能唱的大致长度 |
|---|---|
| 一般歌唱者（中速） | 4–8 小节 |
| 训练有素的歌唱者 | 可延长，但靠的是技巧，不是常态 |

所以写作时若一句写得太长，演唱者就只能在中间**偷偷换气** ——
那会把句读切错位置。**因此"能不能一口气唱下来"是旋律写作的一条硬约束。**

器乐写作也继承了这条传统：即使没有人要唱，**旋律仍按"能唱"的句长来写**，
因为这符合听者的期待。

## 演奏中的句读

对演奏者而言，句读不是分析出来的，而是**做出来的**：

| 手段 | 效果 |
|---|---|
| **气口**（细微的停顿或呼吸） | 明确分句 |
| **力度起伏** | 一句内部做出走向（常与拱形轮廓配合） |
| **时间伸缩** | 句尾稍缓、句首稍紧（见 [[concept:metronome|节拍器与 BPM]]：rubato） |
| **音色变化** | 分句时轻微改变音色 |

**管乐与声乐最直观**：它们必须真的换气，所以句读是物理性的。
弦乐与键盘则可以"不换气地"连奏 —— 这正是不分句、听起来像练习的原因。

## 图示：三种强度的停顿

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">长音 = 逗号，休止 = 分号，终止式 = 句号 —— 停在哪里决定段落级别</text>
  </g>

  <g transform="translate(52,54)">
    <g fill="#5B7FA8">
      <rect x="0" y="-8" width="30" height="16" rx="2"/>
      <rect x="34" y="-8" width="30" height="16" rx="2"/>
      <rect x="68" y="-8" width="70" height="16" rx="2"/>
      <rect x="152" y="-8" width="30" height="16" rx="2"/>
      <rect x="186" y="-8" width="30" height="16" rx="2"/>
    </g>
    <g stroke="#E8C547" stroke-width="1.8">
      <line x1="138" y1="-14" x2="138" y2="10"/>
    </g>
    <text x="138" y="-20" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="middle">长音（逗号）</text>

    <g transform="translate(240,0)">
      <g fill="#5B7FA8">
        <rect x="0" y="-8" width="30" height="16" rx="2"/>
        <rect x="34" y="-8" width="30" height="16" rx="2"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.8" stroke-dasharray="3 3">
        <line x1="72" y1="-14" x2="72" y2="10"/>
      </g>
      <text x="72" y="-20" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="middle">休止（分号）</text>
      <g fill="#5B7FA8">
        <rect x="86" y="-8" width="30" height="16" rx="2"/>
        <rect x="120" y="-8" width="60" height="16" rx="2"/>
      </g>
    </g>

    <g transform="translate(0,66)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        终止式（句号）落在和声层面 —— 它比前两者更强，所以划分出的单位更大
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        声乐优先原则：一般歌唱者一个自然呼吸约 4–8 小节 —— 写得太长，唱者只能偷偷换气、切错句读
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        器乐也继承这条约束：即使没人要唱，旋律仍按"能唱"的句长来写，因为这符合听者的期待
      </text>
    </g>
  </g>
</svg>
```

## 听一听：有呼吸与无呼吸

用 `scale` 组件听一条音阶 —— 它是**没有呼吸**的形态（一直往前，等速进行）。
再想一下《欢乐颂》：同样的级进，**因为句尾用长音"落地"，就变成了旋律。**

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"没有呼吸的形态（等速进行）","label_en":"A form without breathing — even motion throughout","hint":"点「上行」：这就是“跑动”的听感","hint_en":"Try Up — this is what a run sounds like","gap":0.3}

```

## 常见误解

- **「呼吸只是演奏处理」** → 它在**写作**层面就存在：句长受可唱性约束，器乐也继承这条。
- **「停顿都一样」** → 有层级：长音（逗号）< 休止（分号）< 终止式（句号）。**停在哪里决定段落级别。**
- **「器乐不需要考虑呼吸」** → 器乐虽不必真换气，但旋律仍按"能唱"的句长写 —— 否则听者会失去句读感。
- **「分句靠感觉」** → 有依据：长音、休止、终止式三个信号，加上歌词或诗句的句读。
:::

::: en
The difference between a melody and a run lies not in the notes chosen but in **breathing**:

> **A run keeps going; a melody stops, breathes and closes.**

So to tell whether something is a melody or a run, ask one question: **where does it breathe?** If you cannot
answer, it is a run.

## Three signals of breathing

| Signal | Explanation | Strength |
|---|---|---|
| **long note** | one note noticeably longer than its neighbours, creating a pause | weak to medium |
| **rest** | a literal gap | medium |
| **cadence** | closure at the harmonic level (see [[concept:cadence|cadence]]) | **strongest** |

Their strengths differ, so **phrasing is hierarchical**: a long note is a comma, a rest a semicolon, a cadence a
full stop. The level of a section is read from where it stops (see [[concept:phrase|phrase and period]]).

## The vocal priority: write for the breath

A practical fact: **phrase length in a melody is limited by breathing.**

| Singer | Rough length in one natural breath |
|---|---|
| an ordinary singer at a moderate tempo | 4–8 bars |
| a trained singer | longer, but by technique, not by default |

So a phrase written too long forces the singer to **sneak a breath** in the middle — which cuts the phrasing in the
wrong place. **"Can it be sung in one breath" is therefore a hard constraint on melodic writing.**

Instrumental writing inherited the rule: even with nobody singing, **melodies are still shaped in singable phrase
lengths**, because that matches the listener's expectation.

## Phrasing in performance

For a performer, phrasing is not analysed but **made**:

| Means | Effect |
|---|---|
| **breath** (a tiny pause or inhalation) | marks the phrase |
| **dynamic shaping** | gives the phrase a direction (often matching an arch contour) |
| **flexible timing** | a slight easing at the end, a slight urgency at the start (see [[concept:metronome|metronome and BPM]] on rubato) |
| **change of colour** | a slight timbral shift at the break |

**Wind players and singers make this most obvious**: they must physically breathe, so their phrasing is
physiological. Strings and keyboards can play on without breathing — which is exactly why unphrased playing sounds
like an exercise.

## Diagram: three strengths of pause

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Long note = comma, rest = semicolon, cadence = full stop — where it stops sets the level</text>
  </g>

  <g transform="translate(52,54)">
    <g fill="#5B7FA8">
      <rect x="0" y="-8" width="30" height="16" rx="2"/>
      <rect x="34" y="-8" width="30" height="16" rx="2"/>
      <rect x="68" y="-8" width="70" height="16" rx="2"/>
      <rect x="152" y="-8" width="30" height="16" rx="2"/>
      <rect x="186" y="-8" width="30" height="16" rx="2"/>
    </g>
    <g stroke="#E8C547" stroke-width="1.8">
      <line x1="138" y1="-14" x2="138" y2="10"/>
    </g>
    <text x="138" y="-20" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="middle">long note</text>

    <g transform="translate(240,0)">
      <g fill="#5B7FA8">
        <rect x="0" y="-8" width="30" height="16" rx="2"/>
        <rect x="34" y="-8" width="30" height="16" rx="2"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.8" stroke-dasharray="3 3">
        <line x1="72" y1="-14" x2="72" y2="10"/>
      </g>
      <text x="72" y="-20" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="middle">rest</text>
      <g fill="#5B7FA8">
        <rect x="86" y="-8" width="30" height="16" rx="2"/>
        <rect x="120" y="-8" width="60" height="16" rx="2"/>
      </g>
    </g>

    <g transform="translate(0,66)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        The cadence closes at the harmonic level — stronger than both, so it divides larger units
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        Vocal priority: one breath is roughly 4 to 8 bars — write longer and the singer steals breaths and cuts wrongly
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        Instrumental music inherits the constraint: melodies stay in singable lengths even with no singer
      </text>
    </g>
  </g>
</svg>
```

## Listen: with and without breathing

Use `scale` to hear a scale — a form **without breathing** (onward motion at an even rate). Then think of the Ode
of Joy: the same kind of stepwise motion, **but with each phrase landing on a longer note, it becomes a melody.**

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"没有呼吸的形态（等速进行）","label_en":"A form without breathing — even motion throughout","hint":"点「上行」：这就是跑动的听感","hint_en":"Try Up — this is what a run sounds like","gap":0.3}
```

## Common misconceptions

- **"Breathing is only a performance matter."** It exists at the **writing** level: phrase length is limited by
  singability, and instrumental music inherits the limit.
- **"All pauses are alike."** They are hierarchical: long note (comma) < rest (semicolon) < cadence (full stop).
  **Where it stops sets the level of division.**
- **"Instrumental music need not consider breathing."** Instruments need not actually breathe, but melodies are
  still written in singable lengths — otherwise the listener loses the sense of phrasing.
- **"Phrasing is a matter of feeling."** It has evidence: long notes, rests, cadences, plus the punctuation of the
  words or verse.
:::
