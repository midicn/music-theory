---
id: chord-hearing
site: theo
cat: T11
title: 和弦听辨
title_en: Hearing Chords
summary: 功能比性质重要——听出"它是属"比听出"它是大三"更有用
summary_en: Function matters more than quality — hearing "that is the dominant" beats hearing "that is major"
level: standard
tags: [乐理, 练耳, 和声]
tags_en: [theory, ear training, harmony]
alias: [和弦听辨, 和声听辨, chord hearing]
order: 14
links:
  - "[[concept:ear-training]]"
  - "[[concept:interval-hearing]]"
  - "[[concept:harmonic-function]]"
  - "[[concept:chord-inversion]]"
  - "[[concept:cadence]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：四声部和声进行规整，最适合用来练"听功能"（每句的收束在哪） | An organ hymn's four-part progressions are regular, ideal for hearing function and where each phrase closes
  - mutopia-000522 | 《欢乐颂》主题：和声简单、收束清楚，可用于确认"前后两半的收束不同" | The Ode of Joy has simple harmony and clear closes, useful for confirming the two halves end differently
  - atepp-000083 | 斯克里亚宾第一钢琴奏鸣曲：和声更复杂，可作为进阶材料检验"功能判断是否仍成立" | Scriabin's Piano Sonata No.1 has more complex harmony, advancing material for testing whether functional hearing still works
sources:
  - 和弦听辨的三个层次（性质 / 转位 / 功能）与"功能优先"的训练次序，为通行视唱练耳教学表述
  - 功能听辨以调性中心为前提，为通行和声学与练耳教学结论
updated: 2026-09-25
---

::: zh
和弦听辨常被当成"听出这是大三和弦还是小三和弦"。但那是**最低的一层**。

> **真正有用的是功能：这个和弦在调里做什么、要往哪走。**

理由很直接：**音乐是靠功能推进的，不是靠性质**。
一串"大三、小三、小三、大三"不能告诉你音乐在做什么；
而"主 → 下属 → 属 → 主"立刻就说清了过程（见 [[concept:harmonic-function|和声功能]]）。

## 三个层次

| 层次 | 听什么 | 难易 | 有用度 |
|---|---|---|---|
| **① 性质** | 大 / 小 / 减 / 增 | 较易 | 低 |
| **② 转位** | 低音是根音 / 三音 / 五音（见 [[concept:chord-inversion\|和弦转位]]） | 中 | 中 |
| **③ 功能** | 在调里是主 / 下属 / 属 / 离调和弦 | 较难 | **最高** |

**第①层为什么有用度低**：它**孤立地描述一个和弦**，
而孤立的和弦几乎不携带音乐信息 —— 同一个大三和弦，可以是主、是属、也可以是下属。

## 三步听法（顺序不能反）

> **① 先听低音 → ② 再听性质 → ③ 最后判功能**

**为什么先听低音**：低音决定**根音位置与转位**，而功能判断高度依赖低音
（终止四六和弦之所以特殊，正是因为低音是属音）。

**为什么功能放最后**：功能需要**上下文** ——
要先知道"这个调的中心在哪、前面走到哪了"，才能判断当前和弦在做什么。

## 一条实用捷径

**听两个和弦之间的关系，而不是听单个和弦。**

| 听法 | 得到 |
|---|---|
| 只听单个和弦 | "这是个大小七和弦" —— 孤立信息 |
| 听**前后两个和弦** | "它要解决到下一个" —— **功能信息** |

**所以最有效的练习是"听进行"，而不是"听和弦"**：
把注意力放在**变化的瞬间**（前一个怎么离开、后一个怎么落下），
功能判断就会自然出现。

**这也解释了为什么练和弦听辨要从"终止式"开始练** ——
终止式是功能关系最清楚的样本（见 [[concept:cadence|终止式]]）。

## 图示：三个层次与"功能优先"

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">层次越高越有用；听"进行"比听"单个和弦"有效得多</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">有用度</text>
    </g>
    <g>
      <rect x="0" y="-11" width="110" height="22" rx="3" fill="#C0504A" opacity=".75"/>
      <rect x="122" y="-11" width="150" height="22" rx="3" fill="#E8C547" opacity=".85"/>
      <rect x="284" y="-11" width="220" height="22" rx="3" fill="#5B7FA8"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">
      <text x="55" y="4">① 性质</text>
      <text x="197" y="4">② 转位</text>
      <text x="394" y="4">③ 功能（在调里做什么）</text>
    </g>

    <g transform="translate(0,44)">
      <text x="0" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">
        ↑ 性质低效的原因：同一个大三和弦可以是主、是属、也可以是下属 —— 孤立信息不携带音乐信息
      </text>
    </g>

    <g transform="translate(0,84)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        听法顺序不能反：先听低音（决定转位）→ 再听性质 → 最后判功能（需要上下文）
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        最有效的方式：听"两个和弦之间发生了什么"，而不是听单个和弦 —— 练起手从终止式开始
      </text>
    </g>
  </g>
</svg>
```

## 听一听：性质相同、功能不同

用 `chord` 听同一个**大三和弦**。它本身听不出功能 ——
**功能只能从"它前后是什么"判断出来**。这就是"性质有用度低"的直接演示。

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"大三和弦（性质可辨，但功能不明）","label_en":"A major triad: quality identifiable, function unknown","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"G4","quality":"maj","inversion":0,"label":"另一个大三和弦（性质相同，功能可能是“属”）","label_en":"Another major triad: same quality, possibly a dominant","hint":"两者性质相同 —— 功能要靠上下文才能判断","hint_en":"Same quality — function needs context to decide"}

```

## 常见误解

- **「和弦听辨就是听性质」** → 那是最低一层。**功能层才是最有用的一层**。
- **「听单个和弦就能判功能」** → 不能。功能需要**上下文**（调性中心 + 前后关系）。
- **「和弦听辨难在音多」** → 难在**功能判断需要调性框架**；有了框架，性质与转位都不难。
- **「练和弦听辨要背很多和弦」** → 更有效的是**听进行**：从终止式入手，功能关系最清楚。
:::

::: en
Chord hearing is often taken as "telling a major triad from a minor one". That is only **the lowest layer**.

> **What is genuinely useful is function: what this chord does in the key, and where it is going.**

The reason is direct: **music moves by function, not by quality.** A string of "major, minor, minor, major" tells
you nothing about what the music is doing, whereas "tonic, subdominant, dominant, tonic" states the process at
once (see [[concept:harmonic-function|harmonic function]]).

## Three layers

| Layer | What you hear | Difficulty | Usefulness |
|---|---|---|---|
| **1 quality** | major / minor / diminished / augmented | easier | low |
| **2 inversion** | is the bass the root, third or fifth? (see [[concept:chord-inversion\|chord inversion]]) | medium | medium |
| **3 function** | tonic, subdominant, dominant, applied chord | harder | **highest** |

**Why layer 1 is of low use**: it **describes a chord in isolation**, and an isolated chord carries almost no
musical information — the same major triad may be a tonic, a dominant, or a subdominant.

## A three-step order that cannot be reversed

> **1 hear the bass → 2 hear the quality → 3 judge the function**

**Why the bass first**: it fixes **the root position and the inversion**, and functional judgement depends heavily
on the bass (the cadential six-four is special precisely because its bass is the dominant).

**Why function comes last**: it needs **context** — you must know where the key's centre is and where the music has
travelled before you can say what the present chord is doing.

## A practical shortcut

**Listen to the relation between two chords, not to a single chord.**

| Listening | What you get |
|---|---|
| one chord alone | "that is a dominant seventh" — isolated information |
| **two consecutive chords** | "it is about to resolve into the next" — **functional information** |

**So the most effective exercise is hearing progressions, not chords**: put your attention on **the moment of
change** (how the first leaves, how the second lands), and functional hearing appears by itself.

**Which is also why chord hearing should begin with cadences** — a cadence is the clearest sample of functional
relations (see [[concept:cadence|cadence]]).

## Diagram: three layers and the priority of function

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The higher the layer the more useful; hearing progressions beats hearing single chords</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">usefulness</text>
    </g>
    <g>
      <rect x="0" y="-11" width="110" height="22" rx="3" fill="#C0504A" opacity=".75"/>
      <rect x="122" y="-11" width="150" height="22" rx="3" fill="#E8C547" opacity=".85"/>
      <rect x="284" y="-11" width="220" height="22" rx="3" fill="#5B7FA8"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">
      <text x="55" y="4">1 quality</text>
      <text x="197" y="4">2 inversion</text>
      <text x="394" y="4">3 function: what it does in the key</text>
    </g>

    <g transform="translate(0,44)">
      <text x="0" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">
        why quality is weak: one major triad may be tonic, dominant or subdominant — isolated information
      </text>
    </g>

    <g transform="translate(0,84)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        The order is fixed: bass, then quality, then function, which needs context
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        Most effective: listen to what happens between two chords; start from cadences
      </text>
    </g>
  </g>
</svg>
```

## Listen: same quality, different function

Use `chord` to hear one **major triad**. Its function cannot be heard from itself — **function is decided only by
what surrounds it**. A direct demonstration of why quality is of low use.

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"大三和弦（性质可辨，但功能不明）","label_en":"A major triad: quality identifiable, function unknown","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"G4","quality":"maj","inversion":0,"label":"另一个大三和弦（性质相同，功能可能是属）","label_en":"Another major triad: same quality, possibly a dominant","hint":"两者性质相同 —— 功能要靠上下文才能判断","hint_en":"Same quality — function needs context to decide"}
```

## Common misconceptions

- **"Chord hearing means hearing quality."** That is the lowest layer. **Function is the useful one.**
- **"One chord is enough to judge function."** It is not. Function requires **context** (the tonal centre and what
  comes before and after).
- **"Chord hearing is hard because of the number of notes."** It is hard because **functional judgement needs a
  tonal frame**; with the frame, quality and inversion are easy.
- **"You must memorise many chords."** More effective is **hearing progressions**: start from cadences, where
  functional relations are clearest.
:::
