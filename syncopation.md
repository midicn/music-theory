---
id: syncopation
site: theo
cat: T7
title: 切分
title_en: Syncopation
summary: 把重音从强拍挪到弱拍——张力来自"期待被推迟"
summary_en: Moving the accent off the strong beat — the tension comes from a delayed expectation
level: core
tags: [乐理, 节奏, 基础]
tags_en: [theory, rhythm, basics]
alias: [切分, 切分音, syncopation]
order: 16
links:
  - "[[concept:metric-accent]]"
  - "[[concept:meter]]"
  - "[[concept:rhythm]]"
  - "[[concept:polyrhythm]]"
  - "[[concept:non-chord-tone-treatment]]"
instances:
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：舞曲节拍上大量切分，让音乐一直"不稳"，正是切分的典型效果 | Liszt's transcription of Danse macabre — heavy syncopation over a dance metre keeps the music off balance, exactly the effect intended
  - abcmisc-000701 | 蓝调风格的民间材料：切分与摇摆感是小调/蓝调语汇的常见特征 | Folk material in a blues idiom — syncopation and swing are standard in that vocabulary
  - thesession-019704 | 《小星星》作对照：几乎完全没有切分，节奏方正，两者的差别最容易听出 | Twinkle Little Star as a control — almost no syncopation, a square rhythm, the contrast easiest to hear
sources:
  - 切分的常见实现（弱拍起音并跨过强拍、休止占强拍、重音记号移位）与"违背重音周期"的定义，属乐理通则
  - 切分与复节奏/交错节奏的区别（单一周期错位 vs 两个周期并存），为通行乐理表述
updated: 2026-09-25
---

::: zh
切分只有一件事：**把重音从它"该在"的位置挪走。**

> 强拍上不放音（或放轻音），重音落在弱拍上 —— 于是听者一直在等一个没按时出现的重音。

## 三种常见实现

| 做法 | 具体 | 例 |
|---|---|---|
| **跨过强拍** | 音从弱拍起，用延音线延续过强拍 | `♪–♩–`（音在强拍上仍在响，但不"起") |
| **休止占强拍** | 强拍写休止，音出现在弱拍 | `𝄽 ♪ ♩` |
| **重音记号** | 直接标在弱拍上（不改变时值） | 谱面上加 `>` |

第一种最常用，因为它**不需要额外的记号**：音本身跨过了强拍，重音自然"落空"。

## 为什么切分能产生张力

这一点最好从 [[concept:metric-accent|强弱规律]] 反推：

> **张力不来自"重音变轻了"，而来自"期待被推迟"。**

具体地：强拍是一个被期待的落点（见 [[concept:meter|拍号]] 里"小节线的功能"）。
切分占住了那个位置却不"落"，于是期待被悬置 —— 直到切分音结束、正拍重音终于出现时释放。
**这与和声上的"延留—解决"是同一套机制**，只是一个发生在时间轴上、一个发生在音高上。

## 与复节奏的区别（容易混）

| | 切分 | 复节奏 |
|---|---|---|
| 周期数量 | **一个**（就是原有节拍） | **两个**同时存在 |
| 做法 | 在原有网格上**错位** | 另立一套不同的等分（见 [[concept:polyrhythm|复节奏]]） |
| 记谱 | 只需延音线或重音 | 需要两套标记 |

一句话：**切分是"同一个周期的错位"，复节奏是"两个周期并存"。**

## 它在哪里最常见

| 风格 | 切分的作用 |
|---|---|
| **爵士 / 蓝调** | 摇摆感的核心；重音在后半拍（off-beat） |
| **拉丁音乐** | 高度结构化的切分音型 |
| **流行 / 摇滚** | 制造"推一下"的动感 |
| **古典** | 常用于推迟终止：明明该收束了，却因为切分而延后 |

## 图示：重音被挪走

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">上：正常重音　　下：切分——强拍上音还在响，但不"起"</text>
  </g>

  <g transform="translate(52,50)">
    <g stroke="#343439" stroke-width="1"><line x1="0" y1="0" x2="480" y2="0"/></g>
    <g stroke="#5B7FA8" stroke-width="1.6">
      <line x1="0" y1="-8" x2="0" y2="8"/><line x1="120" y1="-8" x2="120" y2="8"/>
      <line x1="240" y1="-8" x2="240" y2="8"/><line x1="360" y1="-8" x2="360" y2="8"/>
      <line x1="480" y1="-8" x2="480" y2="8"/>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="-6" width="110" height="14" rx="2"/>
      <rect x="120" y="-6" width="110" height="14" rx="2"/>
      <rect x="240" y="-6" width="110" height="14" rx="2"/>
      <rect x="360" y="-6" width="110" height="14" rx="2"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="-16">强</text><text x="120" y="-16">弱</text>
      <text x="240" y="-16">次强</text><text x="360" y="-16">弱</text>
    </g>

    <g transform="translate(0,50)">
      <g fill="#E07A3F">
        <rect x="60" y="-6" width="120" height="14" rx="2"/>
        <rect x="240" y="-6" width="120" height="14" rx="2"/>
        <rect x="420" y="-6" width="60" height="14" rx="2"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.4">
        <line x1="60" y1="-14" x2="60" y2="-8"/>
        <line x1="240" y1="-14" x2="240" y2="-8"/>
        <line x1="420" y1="-14" x2="420" y2="-8"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">
        <text x="62" y="-18">重音落在弱拍</text>
        <text x="242" y="-18">又落在弱拍</text>
      </g>
    </g>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      强拍位置没有音"起" → 期待被悬置，直到正拍重音终于出现时才释放
    </text>
    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      机制与和声的"延留—解决"同源：一个在时间轴上，一个在音高上
    </text>
    <text x="0" y="162" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      与复节奏的区别：切分是同一个周期的错位；复节奏是两个周期并存
    </text>
  </g>
</svg>
```

## 听一听：方正与切分

用 `rhythm` 组件对比**四拍均分**与**切分音型**。请留意听者"预期落点"的变化 ——
这正是切分唯一要做的事。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":92,"label":"方正：每一拍都在正拍上","label_en":"Square: every attack on the beat","hint":"点「播放」，先建立“正拍”的预期","hint_en":"Press play and establish the expectation of the beat first"}

```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q e e q q","bpm":92,"label":"切分：音起在弱位","label_en":"Syncopated: attacks off the beat","hint":"与上一条对比：同样的节拍，预期被打乱了","hint_en":"Against the item above — same metre, expectation disrupted"}
```

## 常见误解

- **「切分就是弱起」** → 弱起（anacrusis）只是**从小节前开始**，不一定错位；切分的关键是**重音被挪到非重音位置**。
- **「切分让音乐失去节拍」** → 恰恰相反：**节拍仍在，只是重音被推迟**。没有节拍就没有切分。
- **「切分与复节奏是一回事」** → 切分是单一周期的错位，复节奏是两个周期并存。
- **「切分只属于流行与爵士」** → 古典音乐里大量用于推迟终止；文艺复兴的舞曲也早有切分。
:::

::: en
Syncopation does one thing: **it moves the accent away from where it "should" be.**

> No attack on the strong beat (or only a light one), with the accent landing on a weak beat — so the listener keeps
> waiting for an accent that did not arrive on time.

## Three common realisations

| Method | Detail | Example |
|---|---|---|
| **crossing the strong beat** | attack on a weak beat, tied over the strong beat | `♪–♩–` (still sounding on the beat, but not starting there) |
| **rest on the strong beat** | a rest where the accent is expected, the note on a weak beat | `𝄽 ♪ ♩` |
| **accent mark** | a `>` written on a weak beat without changing durations | visible in the score |

The first is the commonest because it needs **no extra marking**: the note itself crosses the beat, so the accent
falls into empty space.

## Why syncopation creates tension

Work backwards from [[concept:metric-accent|metric accent]]:

> **The tension is not that the accent got quieter; it is that an expectation was delayed.**

Specifically: the strong beat is an expected point of arrival (see the function of bar lines under
[[concept:meter|metre]]). Syncopation occupies that space without landing in it, so the expectation is suspended —
and released when the syncopated note ends and the real accent finally arrives. **This is the same mechanism as a
suspension resolving in harmony**, one playing out in time and the other in pitch.

## How it differs from polyrhythm (easily confused)

| | Syncopation | Polyrhythm |
|---|---|---|
| Number of cycles | **one** (the existing metre) | **two** sounding at once |
| Method | **displacement** within the existing grid | a second, different division (see [[concept:polyrhythm|polyrhythm]]) |
| Notation | a tie or an accent suffices | two sets of markings needed |

In one line: **syncopation displaces one cycle; polyrhythm runs two cycles side by side.**

## Where it is most common

| Style | Role of syncopation |
|---|---|
| **jazz / blues** | the core of swing; accents on the off-beat |
| **Latin music** | highly structured syncopated figures |
| **pop / rock** | the "push" that drives a chorus |
| **classical** | often used to postpone a cadence — the close is due, and syncopation holds it back |

## Diagram: the accent displaced

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Top: normal accents. Bottom: syncopated — the note still sounds on the beat but does not start there</text>
  </g>

  <g transform="translate(52,50)">
    <g stroke="#343439" stroke-width="1"><line x1="0" y1="0" x2="480" y2="0"/></g>
    <g stroke="#5B7FA8" stroke-width="1.6">
      <line x1="0" y1="-8" x2="0" y2="8"/><line x1="120" y1="-8" x2="120" y2="8"/>
      <line x1="240" y1="-8" x2="240" y2="8"/><line x1="360" y1="-8" x2="360" y2="8"/>
      <line x1="480" y1="-8" x2="480" y2="8"/>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="-6" width="110" height="14" rx="2"/>
      <rect x="120" y="-6" width="110" height="14" rx="2"/>
      <rect x="240" y="-6" width="110" height="14" rx="2"/>
      <rect x="360" y="-6" width="110" height="14" rx="2"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="-16">strong</text><text x="120" y="-16">weak</text>
      <text x="240" y="-16">medium</text><text x="360" y="-16">weak</text>
    </g>

    <g transform="translate(0,50)">
      <g fill="#E07A3F">
        <rect x="60" y="-6" width="120" height="14" rx="2"/>
        <rect x="240" y="-6" width="120" height="14" rx="2"/>
        <rect x="420" y="-6" width="60" height="14" rx="2"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.4">
        <line x1="60" y1="-14" x2="60" y2="-8"/>
        <line x1="240" y1="-14" x2="240" y2="-8"/>
        <line x1="420" y1="-14" x2="420" y2="-8"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">
        <text x="62" y="-18">accent on a weak beat</text>
        <text x="242" y="-18">and again</text>
      </g>
    </g>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Nothing starts on the strong beat, so the expectation hangs until the real accent finally arrives
    </text>
    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      The same mechanism as a harmonic suspension: one in time, one in pitch
    </text>
    <text x="0" y="162" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Unlike polyrhythm: syncopation displaces one cycle, polyrhythm runs two
    </text>
  </g>
</svg>
```

## Listen: square and syncopated

Use the `rhythm` component to compare **four even quarters** with **a syncopated figure**. Listen to what happens
to your expectation of arrival — that is all syncopation does.

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":92,"label":"方正：每一拍都在正拍上","label_en":"Square: every attack on the beat","hint":"点「播放」，先建立正拍的预期","hint_en":"Press play and establish the expectation of the beat first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q e e q q","bpm":92,"label":"切分：音起在弱位","label_en":"Syncopated: attacks off the beat","hint":"与上一条对比：同样的节拍，预期被打乱了","hint_en":"Against the item above — same metre, expectation disrupted"}
```

## Common misconceptions

- **"Syncopation means an anacrusis."** An anacrusis simply starts before the bar; it need not displace the accent.
  Syncopation's point is that **the accent lands on a non-accented position**.
- **"Syncopation destroys the metre."** The opposite: **the metre is still there, the accent merely arrives late.**
  No metre, no syncopation.
- **"Syncopation and polyrhythm are the same."** One displaces a single cycle; the other runs two cycles at once.
- **"Syncopation belongs to pop and jazz."** Classical music uses it heavily to postpone cadences, and Renaissance
  dances were already syncopated.
:::
