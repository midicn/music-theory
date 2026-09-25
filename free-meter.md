---
id: free-meter
site: theo
cat: T7
title: 自由节拍与散板
title_en: Free Metre and Sanban
summary: 没有等分拍，但仍然有节奏——句读和张弛换了个方式存在
summary_en: No even pulse, yet rhythm remains — phrasing and tension simply live elsewhere
level: standard
tags: [乐理, 节奏, 中西]
tags_en: [theory, rhythm, comparative]
alias: [自由节拍, 散板, 无拍号, free metre, sanban]
order: 30
links:
  - "[[concept:meter]]"
  - "[[concept:metric-accent]]"
  - "[[concept:tempo]]"
  - "[[concept:phrase]]"
  - "[[cn:gongshang-jiaozhiyu|宫商角徵羽（中国用法）]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：旋律取自圣咏曲调，原型的节奏本就接近自由节拍，重音随歌词而非小节 | An organ hymn — the melody comes from a chant tune whose original rhythm is close to free metre, accent following the words rather than bars
  - atepp-000195 | 德彪西《月光》：大量弹性速度（rubato）让节拍不断被"拉伸"，是自由处理节拍的成熟范例 | Debussy's Clair de lune — extensive rubato stretches the metre constantly, a mature example of free handling
  - atepp-001928 | 巴赫《半音阶幻想曲与赋格》：幻想曲段落节拍自由、近乎即兴，与后面的赋格形成鲜明对照 | Bach's Chromatic Fantasia and Fugue — the fantasia is free and near-improvisatory, in sharp contrast with the fugue that follows
sources:
  - 自由节拍指无固定等分拍与重音周期的节奏组织方式；西方见于圣咏、宣叙调与弹性速度，属乐理通则
  - 「散板」为中国戏曲与器乐中的自由节拍形式，有板式而无等分律动，为通行戏曲音乐表述
updated: 2026-09-25
---

::: zh
自由节拍（free metre）指的是：**没有固定的等分拍，也没有固定的重音周期。**

最容易产生的误解是把它当成"没有节奏"。实际上——

> **没有拍号 ≠ 没有节奏。** 节奏的要素（长短、张弛、句读）仍然全部存在，
> 只是不再由"等分网格"来组织。

## 西方传统里的自由节拍

| 形态 | 特征 | 重音由什么决定 |
|---|---|---|
| **格里高利圣咏** | 无小节线，音符时值不固定 | **歌词的拉丁语重音** |
| **宣叙调** | 近似说话的语调 | **语句的抑扬** |
| **rubato** | 拍子存在，但被有意拉伸 | **演奏者的乐句判断** |
| **幻想曲 / 前奏曲** | 节拍自由，近即兴 | **和声的紧张与缓解** |

最后一行的机制值得注意：**当节拍松掉之后，重音的来源就换成了别的维度** ——
歌词、语调、和声张力。这正是自由节拍并不"乱"的原因。

## 中国的散板

**散板**是中国戏曲与器乐中的自由节拍形式：

| 项 | 说明 |
|---|---|
| **有板式** | 属于某个板式体系（如散板、摇板），不是"随便弹" |
| **有句读** | 乐句的起落、呼吸非常讲究 |
| **有张弛** | 通过疏密、长短、力度做出张力 |
| **无等分律动** | 没有可数的固定拍 |

关键认识：**散板是"把定量的拍子抽掉，但把句读与张弛保留下来"** ——
它的组织原则从"时间等分"换成了"**语气**"。

这与西方圣咏的逻辑其实相通：**两者都把重音交给了语言或语气，而不是小节。**

## 记谱上的三种做法

| 做法 | 适用 |
|---|---|
| **不写小节线** | 圣咏、散板谱（仅用逗号或分行标句读） |
| **虚线小节线** | 提示句读而非规范拍子 |
| **写拍号 + 大量延长记号/速度变化** | 幻想曲、rubato 段落 |

第三种最常见于 19 世纪后的乐谱 —— 作曲者用**写得尽量细的速度与表情标记**来弥补拍子的松动。

## 图示：重音的来源换了

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">有拍号时重音来自网格；没有拍号时，重音改由歌词、语气或和声提供</text>
  </g>

  <g transform="translate(52,52)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-22" y="0" text-anchor="end">有拍号</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.6">
      <line x1="0" y1="0" x2="400" y2="0"/>
      <line x1="0" y1="-8" x2="0" y2="8"/><line x1="100" y1="-8" x2="100" y2="8"/>
      <line x1="200" y1="-8" x2="200" y2="8"/><line x1="300" y1="-8" x2="300" y2="8"/>
      <line x1="400" y1="-8" x2="400" y2="8"/>
    </g>
    <text x="410" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">重音 = 网格位置</text>

    <g transform="translate(0,52)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-22" y="0" text-anchor="end">无拍号</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
        <text x="0" y="0">朱</text><text x="66" y="0">雀</text><text x="150" y="0">桥</text>
        <text x="200" y="0">边</text><text x="270" y="0">野</text><text x="330" y="0">草</text><text x="396" y="0">花</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.4">
        <line x1="0" y1="-14" x2="0" y2="-8"/>
        <line x1="150" y1="-14" x2="150" y2="-8"/>
        <line x1="396" y1="-14" x2="396" y2="-8"/>
      </g>
      <text x="0" y="-20" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">句读（不是等分）</text>
      <text x="410" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A63">重音 = 语言与语气</text>
    </g>

    <g transform="translate(0,104)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        散板：把定量的拍子抽掉，但把句读与张弛保留下来 —— 组织原则从"时间等分"换成"语气"
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        与圣咏相通：两者都把重音交给语言或语气，而不是小节
      </text>
    </g>
  </g>
</svg>
```

## 听一听：拍子松掉之后

自由节拍是"时间组织"的事，本站的听辨件都是等速的 —— 所以这里只能听**等分后的形态**。
请把它当作参照：真实演奏中，这样的段落会被**拉伸、压缩**，而句读的位置保持不变。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4"],"label":"等分形态（真实演奏会拉伸压缩）","label_en":"An even form — real performance stretches and compresses it","hint":"点「上行」：想象每一个音的长短都可自由伸缩，但句尾要停","hint_en":"Try Up and imagine each note freely stretched, with a pause at the phrase end","gap":0.5}
```

## 常见误解

- **「没有拍号就是没有节奏」** → 节奏的要素（长短、张弛、句读）全部存在，只是不由等分网格组织。
- **「散板是随便弹」** → 散板有板式、有句读、有张弛规范，只是没有可数的固定拍。
- **「自由节拍比有拍号简单」** → 更难：**没有网格可以依靠**，全靠演奏者对语气与结构的判断。
- **「自由节拍是东方或古代独有的」** → 圣咏、宣叙调、rubato 都属于它；西方音乐从未离开过它。
:::

::: en
Free metre means: **no fixed even pulse and no fixed accent cycle.**

The commonest misunderstanding is to treat it as "no rhythm". In fact —

> **No time signature does not mean no rhythm.** Every element of rhythm — durations, tension, phrasing — is
> still present; it is simply no longer organised by an even grid.

## Free metre in the Western tradition

| Form | Feature | What supplies the accent |
|---|---|---|
| **Gregorian chant** | no bar lines, values not fixed | **the Latin word accents** |
| **recitative** | close to speech inflection | **the rise and fall of the sentence** |
| **rubato** | the beat exists but is deliberately stretched | **the performer's phrasing** |
| **fantasia / prelude** | free, near-improvisatory | **harmonic tension and release** |

The last row is worth noting: **once the metre loosens, the source of accent shifts to another dimension** —
words, inflection, harmonic tension. That is why free metre is not chaotic.

## Sanban in Chinese music

**Sanban** (散板) is the free-metre form in Chinese opera and instrumental music:

| Item | Explanation |
|---|---|
| **a metrical system** | it belongs to a system of ban-shi (板式), not "anything goes" |
| **phrasing** | the rise and fall of phrases, and the breathing, are carefully shaped |
| **tension** | created by density, duration and dynamics |
| **no even pulse** | there is no countable fixed beat |

The key point: **sanban removes the measured beat but keeps phrasing and tension** — its organising principle
shifts from "dividing time" to "**tone of voice**".

Which is in fact the same logic as chant: **both hand the accent to language or inflection rather than to a bar.**

## Three notational approaches

| Approach | Used for |
|---|---|
| **no bar lines** | chant, sanban scores (phrasing marked by commas or line breaks) |
| **dashed bar lines** | suggesting phrasing rather than regulating beats |
| **a time signature plus many fermatas and tempo changes** | fantasias, rubato passages |

The third is commonest in scores after the nineteenth century: composers compensate for the loosened beat by
**writing tempo and expression markings as precisely as possible**.

## Diagram: the source of accent changes

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">With a signature the accent comes from the grid; without one it comes from words, inflection or harmony</text>
  </g>

  <g transform="translate(52,52)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-22" y="0" text-anchor="end">with a signature</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.6">
      <line x1="0" y1="0" x2="400" y2="0"/>
      <line x1="0" y1="-8" x2="0" y2="8"/><line x1="100" y1="-8" x2="100" y2="8"/>
      <line x1="200" y1="-8" x2="200" y2="8"/><line x1="300" y1="-8" x2="300" y2="8"/>
      <line x1="400" y1="-8" x2="400" y2="8"/>
    </g>
    <text x="410" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">accent = grid position</text>

    <g transform="translate(0,52)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-22" y="0" text-anchor="end">without one</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
        <text x="0" y="0">word</text><text x="66" y="0">word</text><text x="150" y="0">word</text>
        <text x="200" y="0">word</text><text x="270" y="0">word</text><text x="330" y="0">word</text><text x="396" y="0">word</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.4">
        <line x1="0" y1="-14" x2="0" y2="-8"/>
        <line x1="150" y1="-14" x2="150" y2="-8"/>
        <line x1="396" y1="-14" x2="396" y2="-8"/>
      </g>
      <text x="0" y="-20" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">phrasing, not division</text>
      <text x="410" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A63">accent = language and inflection</text>
    </g>

    <g transform="translate(0,104)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        Sanban removes the measured beat but keeps phrasing and tension: "dividing time" becomes "tone of voice"
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        Like chant: both hand the accent to language rather than to a bar
      </text>
    </g>
  </g>
</svg>
```

## Listen: after the beat loosens

Free metre concerns the organisation of time, and this site's listening tools are all steady — so what follows is
only the **even form**. Treat it as a reference point: in real performance such a passage is **stretched and
compressed**, while the phrase boundaries stay put.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4"],"label":"等分形态（真实演奏会拉伸压缩）","label_en":"An even form — real performance stretches and compresses it","hint":"点「上行」：想象每个音的长短自由伸缩，但句尾要停","hint_en":"Try Up and imagine each note freely stretched, with a pause at the phrase end","gap":0.5}
```

## Common misconceptions

- **"No time signature means no rhythm."** Every element of rhythm — durations, tension, phrasing — remains; it is
  just not organised by an even grid.
- **"Sanban means playing at random."** Sanban has a metrical system, phrasing and conventions of tension; it
  merely lacks a countable fixed beat.
- **"Free metre is easier than measured metre."** Harder: **there is no grid to lean on**, so everything rests on
  the performer's judgement of inflection and structure.
- **"Free metre is uniquely Eastern or ancient."** Chant, recitative and rubato all belong to it; Western music
  never left it behind.
:::
