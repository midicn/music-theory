---
id: polyrhythm
site: theo
cat: T7
title: 复节奏与交错节奏
title_en: Polyrhythm and Cross Rhythm
summary: 两套等分同时走——和切分的区别是"几个周期"
summary_en: Two divisions running at once — the difference from syncopation is how many cycles there are
level: standard
tags: [乐理, 节奏, 织体]
tags_en: [theory, rhythm, texture]
alias: [复节奏, 交错节奏, 交叉节奏, polyrhythm, hemiola]
order: 24
links:
  - "[[concept:syncopation]]"
  - "[[concept:metric-accent]]"
  - "[[concept:tuplet]]"
  - "[[concept:simple-compound-meter]]"
  - "[[concept:counterpoint]]"
instances:
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：多处出现两套节奏同时进行的段落，是复节奏在作品里的实例 | Liszt's transcription of Danse macabre contains passages with two rhythmic layers at once
  - cyberhymnal-000695 | 管风琴圣咏：终止处常把两小节三拍改组成三个二拍（hemiola），是复节奏的经典用法 | Organ hymns often regroup two 3/4 bars as three duple units at a cadence — the classic hemiola
  - thesession-019704 | 《小星星》作对照：全曲只有一套等分，两者对比最容易听出"一套还是两套" | Twinkle Little Star has a single division throughout — the easiest contrast between one cycle and two
sources:
  - 复节奏指两种不同等分同时进行（如 3:2）；hemiola 指重音层面的 3 对 2 重组，属乐理通则
  - 最小公倍数决定两种等分的可对齐点（3:2 在 6 个细分点中的第 1、4 点对齐），为通行表述
updated: 2026-09-25
---

::: zh
复节奏（polyrhythm）的做法：**让两套不同的等分同时进行。**

> 最常见的例子是 **3:2** —— 一个声部把一拍分成三份，另一个分成两份，同时走。

## 与切分的区别：数周期

这是本条最要紧的判断点（上一段在 [[concept:syncopation|切分]] 里已铺垫）：

| | 切分 | 复节奏 |
|---|---|---|
| 周期数量 | **一个** | **两个**同时 |
| 做法 | 在原有网格上错位 | 另立一套不同的等分 |
| 记谱 | 延音线或重音记号 | 两套数字 / 两套符尾 |
| 听觉 | "重音还没来" | "两件事同时在发生" |

一句话：**切分是同一个周期的错位，复节奏是两个周期并存。**

## 3:2 为什么最自然

因为 **3 和 2 的最小公倍数是 6**：把一拍细分成六个点，两边就都能落在点上：

| 细分点 | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| **分两份** | ● | | | ● | | |
| **分三份** | ● | | ● | | ● | |
| **重合** | ✓ | | | ✓ | | |

**六个点里只有第 1、4 点重合** —— 重合点就是两个声部"碰头"的位置。
这也解释了为什么 3:2 听起来"错开又对得上"：它不是乱的，而是**周期性的错开**。

## Hemiola：重音层面的 3 对 2

有一种特别的复节奏叫 **hemiola**：不改变音符时值，只**改变重音的归组**。

> 两小节 3/4（共六拍）被重新分组为**三个二拍** —— 顿时有了二拍子的感觉。

这在文艺复兴与巴洛克音乐里极其常见，尤其是**终止之前**：
用 hemiola 把三拍感临时改成两拍感，落回主和弦时再变回三拍，收束因此更有力。
它的价值在于**不需要任何新素材** —— 只是把重音挪了位置（见 [[concept:metric-accent|强弱规律]]）。

## 它在不同音乐里的位置

| 音乐 | 复节奏的角色 |
|---|---|
| **非洲音乐** | **核心特征**：常常是三层以上同时进行，而非只有 3:2 |
| **古典** | 局部使用（hemiola 最常见），用于制造收束的紧张 |
| **爵士 / 拉丁** | 常见 3:2 与 2:3 的交替（"clave"类概念） |
| **现代创作** | 常作为结构手段，长时间维持两套周期 |

## 图示：六点上的 3 与 2

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">把一拍细分成六个点，3 与 2 都能落在点上；只有第 1、4 点重合</text>
  </g>

  <g transform="translate(56,58)">
    <g stroke="#343439" stroke-width="1">
      <line x1="0" y1="0" x2="480" y2="0"/>
    </g>
    <g stroke="#343439" stroke-width="1">
      <line x1="0" y1="-5" x2="0" y2="5"/><line x1="96" y1="-5" x2="96" y2="5"/>
      <line x1="192" y1="-5" x2="192" y2="5"/><line x1="288" y1="-5" x2="288" y2="5"/>
      <line x1="384" y1="-5" x2="384" y2="5"/><line x1="480" y1="-5" x2="480" y2="5"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="20">1</text><text x="96" y="20">2</text><text x="192" y="20">3</text>
      <text x="288" y="20">4</text><text x="384" y="20">5</text><text x="480" y="20">6</text>
    </g>

    <g transform="translate(0,-30)">
      <g fill="#5B7FA8">
        <circle cx="0" cy="0" r="7"/><circle cx="288" cy="0" r="7"/>
      </g>
      <text x="24" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">分两份（2）</text>
    </g>
    <g transform="translate(0,-58)">
      <g fill="#E07A3F">
        <circle cx="0" cy="0" r="7"/><circle cx="96" cy="0" r="7"/><circle cx="192" cy="0" r="7"/>
        <circle cx="288" cy="0" r="7"/><circle cx="384" cy="0" r="7"/><circle cx="480" cy="0" r="7"/>
      </g>
      <text x="504" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">分三份（3）</text>
    </g>
    <g stroke="#E8C547" stroke-width="1.4" stroke-dasharray="3 3">
      <line x1="0" y1="-70" x2="0" y2="8"/><line x1="288" y1="-70" x2="288" y2="8"/>
    </g>
    <text x="0" y="48" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      重合点是第 1、4 点 —— 两个声部在这里"碰头"，其余时间错开
    </text>
    <text x="0" y="70" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      hemiola：不改时值，只把两小节 3/4 的重音重新分组为三个二拍 → 临时变成二拍感
    </text>
    <text x="0" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      与切分的区别：切分是同一个周期的错位；复节奏是两个周期并存
    </text>
  </g>
</svg>
```

## 听一听：两种等分的对照

本站的听辨件是单声部的，放不出真正的两套节奏 —— 所以这里**并排**听两种等分，
请在心里把它们叠起来（先听二分的，再听三分的，想象二者同时）：

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"e e e e e e e e","bpm":72,"label":"分两份：八分均分","label_en":"Division by two: even eighths","hint":"先单独听这一套","hint_en":"Hear this division on its own first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"t t t t t t t t t t t t","bpm":72,"label":"分三份：三连音","label_en":"Division by three: triplets","hint":"再听这一套 —— 想象与上一条同时进行，就是 3:2","hint_en":"Then this one — imagine both at once, and you have 3 against 2"}
```

## 常见误解

- **「复节奏就是复杂节奏」** → 它的定义是**两套等分并存**，与"复杂"无关；3:2 本身很简单。
- **「复节奏与切分是一回事」** → 关键在**周期数量**：切分一个周期，复节奏两个。
- **「hemiola 是改变时值的写法」** → 恰恰相反：hemiola **不改时值**，只重组**重音**（所以它几乎不占篇幅，效果却很强）。
- **「复节奏只属于非洲音乐或现代作品」** → 巴洛克的 hemiola 就是复节奏；爵士与拉丁里也极常见。
:::

::: en
Polyrhythm does this: **let two different divisions run at the same time.**

> The commonest case is **3:2** — one voice divides a beat into three, another into two, simultaneously.

## The difference from syncopation: count the cycles

This is the key point of the entry (set up earlier under [[concept:syncopation|syncopation]]):

| | Syncopation | Polyrhythm |
|---|---|---|
| Number of cycles | **one** | **two** at once |
| Method | displacement within the existing grid | a second, different division |
| Notation | a tie or an accent | two sets of figures or beams |
| What you hear | "the accent has not arrived" | "two things are happening at once" |

In one line: **syncopation displaces one cycle; polyrhythm runs two.**

## Why 3:2 is the most natural

Because **the least common multiple of 3 and 2 is 6**: subdivide a beat into six points and both fit:

| Point | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| **in two** | ● | | | ● | | |
| **in three** | ● | | ● | | ● | |
| **coincide** | ✓ | | | ✓ | | |

**Only points 1 and 4 coincide** — and those are where the two voices meet. It also explains why 3:2 sounds
"offset yet aligned": it is not random, it is **periodically displaced**.

## Hemiola: 3 against 2 at the accent level

A special kind of polyrhythm is the **hemiola**: note values stay the same and only the **accent grouping**
changes.

> Two bars of 3/4 (six beats) regrouped as **three duple units** — and it immediately sounds duple.

This is extremely common in Renaissance and Baroque music, especially **before a cadence**: the triple feel is
temporarily turned duple and snaps back to triple on the tonic chord, which makes the close stronger. Its value
is that it **needs no new material** — only a shift of accent (see [[concept:metric-accent|metric accent]]).

## Where it sits in different musics

| Music | Role of polyrhythm |
|---|---|
| **African music** | **a core feature**: often three or more layers at once, not merely 3:2 |
| **classical** | used locally (hemiola most often), to tighten a close |
| **jazz / Latin** | 3:2 and 2:3 alternating (the clave family of concepts) |
| **contemporary** | often structural, sustaining two cycles for long stretches |

## Diagram: 3 and 2 across six points

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Subdivide the beat into six points and both 3 and 2 land on them; only points 1 and 4 coincide</text>
  </g>

  <g transform="translate(56,58)">
    <g stroke="#343439" stroke-width="1">
      <line x1="0" y1="0" x2="480" y2="0"/>
    </g>
    <g stroke="#343439" stroke-width="1">
      <line x1="0" y1="-5" x2="0" y2="5"/><line x1="96" y1="-5" x2="96" y2="5"/>
      <line x1="192" y1="-5" x2="192" y2="5"/><line x1="288" y1="-5" x2="288" y2="5"/>
      <line x1="384" y1="-5" x2="384" y2="5"/><line x1="480" y1="-5" x2="480" y2="5"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="20">1</text><text x="96" y="20">2</text><text x="192" y="20">3</text>
      <text x="288" y="20">4</text><text x="384" y="20">5</text><text x="480" y="20">6</text>
    </g>

    <g transform="translate(0,-30)">
      <g fill="#5B7FA8">
        <circle cx="0" cy="0" r="7"/><circle cx="288" cy="0" r="7"/>
      </g>
      <text x="24" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">in two</text>
    </g>
    <g transform="translate(0,-58)">
      <g fill="#E07A3F">
        <circle cx="0" cy="0" r="7"/><circle cx="96" cy="0" r="7"/><circle cx="192" cy="0" r="7"/>
        <circle cx="288" cy="0" r="7"/><circle cx="384" cy="0" r="7"/><circle cx="480" cy="0" r="7"/>
      </g>
      <text x="504" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">in three</text>
    </g>
    <g stroke="#E8C547" stroke-width="1.4" stroke-dasharray="3 3">
      <line x1="0" y1="-70" x2="0" y2="8"/><line x1="288" y1="-70" x2="288" y2="8"/>
    </g>
    <text x="0" y="48" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      The coincidences are points 1 and 4 — where the voices meet; the rest of the time they are offset
    </text>
    <text x="0" y="70" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Hemiola: keep the note values, regroup two 3/4 bars as three duple units, and the metre briefly turns duple
    </text>
    <text x="0" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Unlike syncopation: one displaced cycle versus two cycles coexisting
    </text>
  </g>
</svg>
```

## Listen: the two divisions side by side

This site's listening components are single-voice, so a true polyrhythm cannot be played. Hear the two divisions
**one after the other** and imagine them together — first the binary one, then the ternary:

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"e e e e e e e e","bpm":72,"label":"分两份：八分均分","label_en":"Division by two: even eighths","hint":"先单独听这一套","hint_en":"Hear this division on its own first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"t t t t t t t t t t t t","bpm":72,"label":"分三份：三连音","label_en":"Division by three: triplets","hint":"再听这一套 —— 想象与上一条同时进行，就是 3:2","hint_en":"Then this one — imagine both at once, and you have 3 against 2"}
```

## Common misconceptions

- **"Polyrhythm means complicated rhythm."** By definition it is **two divisions coexisting**, which has nothing to
  do with complexity; 3:2 on its own is simple.
- **"Polyrhythm and syncopation are the same."** The discriminator is the **number of cycles**: one for
  syncopation, two for polyrhythm.
- **"Hemiola changes note values."** The opposite: it **keeps the values** and regroups the **accents**, which is why
  it takes almost no space and has a strong effect.
- **"Polyrhythm belongs to African music or the avant-garde."** The Baroque hemiola is a polyrhythm, and jazz and
  Latin music are full of them.
:::
