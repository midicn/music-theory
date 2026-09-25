---
id: voice-leading
site: theo
cat: T5
title: 声部进行
title_en: Voice Leading
summary: 和弦不是"换"过去的，是每个声部各自走过去的
summary_en: Chords do not get swapped — each voice travels to the next one on its own
level: core
tags: [乐理, 和声, 声部写作]
tags_en: [theory, harmony, part writing]
alias: [声部进行, 声部写作, part writing, voice leading]
order: 16
links:
  - "[[concept:chord]]"
  - "[[concept:chord-voicing]]"
  - "[[concept:parallel-fifths]]"
  - "[[concept:counterpoint]]"
  - "[[concept:harmonic-function]]"
  - "[[concept:chord-inversion]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：四个声部各自成线，共同构成和声，是声部进行最标准的样本 | An organ hymn — four voices each following a line while forming the harmony together, the standard sample of voice leading
  - mutopia-000280 | 巴赫二部创意曲第一首：只有两个声部，每条线的走向都清晰可辨 | Bach's first two-part invention — only two voices, so each line's motion is plainly audible
  - giantmidi-006222 | 音阶与终止练习：级进为主的连接方式可直接听出"平滑"与"生硬"的差别 | Scale and cadence exercises — stepwise connections make the difference between smooth and awkward directly audible
sources:
  - 声部进行的三条基本原则（共同音保持、级进优先、避免同向大跳）为和声学与对位学通则
  - 四声部配置（女高 / 女低 / 男高 / 男低）与声部间距惯例，为通行和声写作表述
updated: 2026-09-24
---

::: zh
初学者弹和弦时，脑子里想的是"**换和弦**"。但和声写作的核心不是换，而是：
**每个声部各自走到下一个音**。

> 四个声部四条线，同时到达下一个和弦 —— 和声是四条线**同时到站**的结果，
> 不是一整块被搬过去。

这个视角的转换非常重要，因为它立刻带来一批可操作的判断标准。

## 三条基本原则

| 原则 | 内容 | 为什么 |
|---|---|---|
| **共同音保持** | 两个和弦共有的音，尽量让它在同一声部**不动** | 少动一个声部，连接就更平滑 |
| **级进优先** | 其余声部尽量走**全音或半音** | 级进是最平滑的运动方式 |
| **避免同向大跳** | 声部之间尽量**反向或斜向**移动 | 同向大跳会让两条线"平行推进"，失去独立性 |

三条合起来的效果是：**听感上听不出"换和弦"这个动作，只听到音乐在流动。**

## 三种声部关系

| 关系 | 说明 | 效果 |
|---|---|---|
| **同向** | 两声部朝同一方向移动 | 自然，但用多了会显得单调 |
| **反向** | 一声部上行、一声部下（见 [[concept:interval-inversion|音程转位]] 的思路） | **最有力**，声部独立性最强 |
| **斜向** | 一声部不动、另一声部移动 | 最平稳，共同音保持就属这一类 |

## 四声部与声部间距

传统和声写作通常用四个声部（女高 / 女低 / 男高 / 男低）。间距有惯例：

| 位置 | 惯例 |
|---|---|
| 上方三声部之间 | 不超过一个八度（否则整体会"散架"） |
| 低音与男高音之间 | 可以更宽（低音本来就需要空间） |

这与 [[concept:chord-voicing|和弦排列]] 讲的是同一件事：**低音区要留空。**
在低音区放密集和弦，泛音会互相干扰，听感立刻变浑浊。

## 声部进行与和声功能的关系

声部进行不是独立的技巧，它**服务于功能**：属→主的推动力，正是靠
导音上行半音、七音下行半音这两条线实现的（见 [[concept:cadence|终止式]]）。
换句话说，**功能是"要去哪"，声部进行是"怎么去"**。

## 图示：三个和弦，看每个声部怎么走

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">和弦换了两处，但四条线几乎没有跳动 —— 这就是声部进行</text>
  </g>

  <g transform="translate(60,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#F2EEE6">G</text><text x="120" y="0" fill="#F2EEE6">G</text><text x="240" y="0" fill="#E07A3F">C</text>
      <text x="0" y="34" fill="#F2EEE6">E</text><text x="120" y="34" fill="#F2EEE6">E</text><text x="240" y="34" fill="#E07A3F">E</text>
      <text x="0" y="68" fill="#F2EEE6">C</text><text x="120" y="68" fill="#F2EEE6">C</text><text x="240" y="68" fill="#E07A3F">G</text>
      <text x="0" y="102" fill="#5B7FA8">C</text><text x="120" y="102" fill="#5B7FA8">F</text><text x="240" y="102" fill="#5B7FA8">C</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="14" y1="0" x2="106" y2="0"/><line x1="134" y1="0" x2="226" y2="0"/>
      <line x1="14" y1="34" x2="106" y2="34"/><line x1="134" y1="34" x2="226" y2="34"/>
      <line x1="14" y1="68" x2="106" y2="68"/><line x1="134" y1="68" x2="226" y2="68"/>
      <line x1="14" y1="102" x2="106" y2="102"/><line x1="134" y1="102" x2="226" y2="102"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="0" y="122" text-anchor="middle">I</text>
      <text x="120" y="122" text-anchor="middle">I⁶₄</text>
      <text x="240" y="122" text-anchor="middle">V</text>
    </g>
    <text x="300" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">上方两声部保持不动（共同音）</text>
    <text x="300" y="34" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">次中声部也只动了全音</text>
    <text x="300" y="68" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">低音是唯一的大跳（C→F→C）</text>
    <text x="300" y="104" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">结果：听起来只有低音在动，上方是一片稳定的和弦</text>
  </g>
</svg>
```

## 听一听：和弦连接

用进行播放器听 I → IV → V → I。留意每个和弦之间**几乎没有跳进**，
以及低音如何独自承担"走动"的任务。

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"I → IV → V → I（声部平滑连接）","label_en":"I-IV-V-I with smooth voice leading","hint":"逐个和弦依次听，注意和弦之间是否有跳进","hint_en":"Hear each chord in turn and notice whether anything leaps"}
```

## 常见误解

- **「和弦是整体换过去的」** → 声部进行的视角是每个声部各自移动。这一转换会立刻改变你对连接好坏判断的方式。
- **「声部进行只是"好听不好听"」** → 它有明确的实务标准（共同音保持、级进优先、反向优先），可以逐条检查。
- **「平行五八度是唯一的规则」** → 那只是其中最常被提到的一条（见 [[concept:parallel-fifths|平行五八度]]），整套规则还有很多条。
- **「现代音乐不需要声部进行」** → 即使是不协和的和声，声部走向仍决定听感是"有逻辑"还是"东碰西撞"。
:::

::: en
Beginners think of chord changes as **swapping chords**. But the core of harmonic writing is not swapping — it is
this: **each voice travels to its next note.**

> Four voices, four lines, arriving at the next chord together. Harmony is what happens when four lines
> **reach the station at the same time**; it is not one block being moved.

That shift of viewpoint matters, because it immediately produces a set of checkable criteria.

## Three principles

| Principle | Content | Why |
|---|---|---|
| **hold common tones** | where two chords share a note, keep it **still** in the same voice | one fewer voice moving means a smoother join |
| **prefer stepwise motion** | move the remaining voices by **whole or half step** | steps are the smoothest motion available |
| **avoid similar wide leaps** | favour **contrary or oblique** motion between voices | voices leaping the same way advance in parallel and lose independence |

Together the three achieve this: **you stop hearing a chord being changed and start hearing music moving.**

## Three relations between voices

| Relation | Description | Effect |
|---|---|---|
| **similar** | two voices move the same direction | natural, but monotonous if overused |
| **contrary** | one rises, one falls (the logic of [[concept:interval-inversion|interval inversion]]) | **strongest**, most independent |
| **oblique** | one stays, the other moves | the smoothest; holding a common tone is this case |

## Four voices and spacing

Traditional writing uses four voices (soprano, alto, tenor, bass). Spacing has conventions:

| Position | Convention |
|---|---|
| between the upper three voices | no more than an octave apart, or the texture falls apart |
| between bass and tenor | may be wider — the low register needs room |

This is the same point as [[concept:chord-voicing|chord voicing]]: **keep the low register open.** Pack a chord
low down and the partials interfere — the sound muddies at once.

## How voice leading relates to function

Voice leading is not a technique standing on its own; it **serves function**. The push of dominant to tonic is
precisely the leading tone rising a semitone and the seventh falling a semitone (see [[concept:cadence|cadence]]).
In other words: **function says where to go, voice leading says how to travel.**

## Diagram: three chords, and how each voice moves

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The chord changes twice, yet the four lines barely leap — that is voice leading</text>
  </g>

  <g transform="translate(60,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#F2EEE6">G</text><text x="120" y="0" fill="#F2EEE6">G</text><text x="240" y="0" fill="#E07A3F">C</text>
      <text x="0" y="34" fill="#F2EEE6">E</text><text x="120" y="34" fill="#F2EEE6">E</text><text x="240" y="34" fill="#E07A3F">E</text>
      <text x="0" y="68" fill="#F2EEE6">C</text><text x="120" y="68" fill="#F2EEE6">C</text><text x="240" y="68" fill="#E07A3F">G</text>
      <text x="0" y="102" fill="#5B7FA8">C</text><text x="120" y="102" fill="#5B7FA8">F</text><text x="240" y="102" fill="#5B7FA8">C</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="14" y1="0" x2="106" y2="0"/><line x1="134" y1="0" x2="226" y2="0"/>
      <line x1="14" y1="34" x2="106" y2="34"/><line x1="134" y1="34" x2="226" y2="34"/>
      <line x1="14" y1="68" x2="106" y2="68"/><line x1="134" y1="68" x2="226" y2="68"/>
      <line x1="14" y1="102" x2="106" y2="102"/><line x1="134" y1="102" x2="226" y2="102"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="0" y="122" text-anchor="middle">I</text>
      <text x="120" y="122" text-anchor="middle">I⁶₄</text>
      <text x="240" y="122" text-anchor="middle">V</text>
    </g>
    <text x="300" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">upper two voices hold still (common tones)</text>
    <text x="300" y="34" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">the inner voice moves only a whole tone</text>
    <text x="300" y="68" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">the bass alone makes the leaps (C to F to C)</text>
    <text x="300" y="104" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Result: only the bass seems to move; above it sits a stable chord</text>
  </g>
</svg>
```

## Listen: connecting chords

Use the progression player on I → IV → V → I. Notice how little leaps between chords, and how the bass alone
carries the travelling.

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"I → IV → V → I（声部平滑连接）","label_en":"I-IV-V-I with smooth voice leading","hint":"逐个和弦依次听，注意和弦之间是否有跳进","hint_en":"Hear each chord in turn and notice whether anything leaps"}
```

## Common misconceptions

- **"A chord is moved as a block."** The voice-leading view is that each voice moves on its own. That shift instantly changes how you judge a connection.
- **"Voice leading is just about sounding nice."** It has explicit practical criteria (hold common tones, prefer steps, prefer contrary motion) that can be checked one by one.
- **"Parallel fifths are the only rule."** That is merely the most quoted one (see [[concept:parallel-fifths|parallel fifths]]); the full set is much larger.
- **"Modern music needs no voice leading."** Even with dissonant harmony, how the voices move decides whether the result sounds logical or merely collided.
:::
