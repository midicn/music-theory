---
id: phrase
site: theo
cat: T8
title: 乐句与乐段
title_en: Phrase and Period
summary: 旋律的"一句话"与"一对句"——判据是终止式的强弱
summary_en: The melody's sentence and its pair of sentences — judged by the strength of cadences
level: core
tags: [乐理, 旋律, 曲式]
tags_en: [theory, melody, form]
alias: [乐句, 乐段, 句读, phrase, period]
order: 12
links:
  - "[[concept:melody]]"
  - "[[concept:cadence]]"
  - "[[concept:breath-phrasing]]"
  - "[[concept:motive]]"
  - "[[concept:sequence]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：典型的两句结构 —— 前句停在属和弦（开放），后句收在主和弦（收束） | The Ode of Joy theme is classically two-phrased — the first half rests on the dominant, the second closes on the tonic
  - thesession-019704 | 《小星星》：aaba 四句，前三句相似、末句转折收束，是最简的乐段样本 | Twinkle Little Star is aaba — three similar phrases and a closing one that turns — the simplest period
  - cyberhymnal-000695 | 管风琴圣咏：诗句即乐句，句末必有终止，与文字结构一一对应 | An organ hymn — each line of text is a phrase ending in a cadence, matching the words one to one
sources:
  - 乐句与乐段的划分以终止式的强弱为依据，属曲式分析通则
  - 四小节乐句的普遍性与呼吸长度及听觉记忆容量相关，为通行旋律学表述
updated: 2026-09-25
---

::: zh
旋律不是一连串音，而是**分成句**的。这一步的判断标准很硬：

> **看终止式的强弱** —— 和声在哪里"落下"，旋律就在哪里断句（见 [[concept:cadence|终止式]]）。

所以**不能只靠听旋律来分句**，必须连着和声一起看。这是初学者最常犯的错：
凭"气口"猜句读，结果和实际结构不符。

## 两个层级

| 层级 | 定义 | 判据 |
|---|---|---|
| **乐句**（phrase） | 能"一口气"唱完、有起有落的单位 | 句末有**终止式**（哪怕很弱） |
| **乐段**（period） | **两句成对**：前句开放、后句收束 | 前句**半终止**，后句**正格终止** |

**乐段的精髓在两句的对比**：

| 位置 | 和声 | 听感 |
|---|---|---|
| 前句句末 | **半终止**（停在属） | **开放**：话没说完 |
| 后句句末 | **正格终止**（回到主） | **收束**：话说完 |

如果前后两句都是同样的收束方式，那就不是"乐段"，只是两个并列的乐句。
**"一问一答"才是乐段的标志。**

## 为什么四小节这么常见

大量旋律用"4 + 4"的结构。原因不是规定，而是三个实际条件的重合：

| 条件 | 说明 |
|---|---|
| **呼吸** | 四小节的中等速度对应一次自然的呼吸长度 |
| **记忆** | 四小节的长度刚好能被记住、又短到不会忘记开头 |
| **可再分** | 4 可分成 2+2，也可扩成 8，弹性大 |

三者同时成立，所以它成了"默认长度" —— 而不是因为它更"正确"。

## 常见的乐句组织方式

| 结构 | 说明 | 例 |
|---|---|---|
| **aa'** | 后句是前句的变化重复 | 最常见 |
| **aaba** | 三句相似 + 一句转折 | 《小星星》 |
| **ab** | 两句不同，形成对比 | 常见于抒情旋律 |
| **aab** | 重复两次后转折 | 常见于民歌 |

**aa' 之所以最常见**，因为它同时满足两件事：**给听者熟悉感（a），又给新鲜感（a'）** ——
与 [[concept:melody|旋律]] 里"可记忆性来自重复与变化的比例"是同一条经验。

## 图示：乐段的"一问一答"

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">乐段的判据：前句开放（半终止），后句收束（正格终止）</text>
  </g>

  <g transform="translate(52,56)">
    <g fill="#5B7FA8" opacity=".85">
      <rect x="0" y="-12" width="180" height="22" rx="3"/>
    </g>
    <text x="90" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">前句 a</text>
    <g stroke="#E8C547" stroke-width="2">
      <line x1="180" y1="-14" x2="180" y2="12"/>
    </g>
    <text x="188" y="2" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">半终止：停在属 → 开放</text>

    <g fill="#E07A3F" opacity=".9">
      <rect x="0" y="44" width="180" height="22" rx="3"/>
    </g>
    <text x="90" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">后句 a'</text>
    <g stroke="#5B7FA8" stroke-width="2">
      <line x1="180" y1="42" x2="180" y2="68"/>
    </g>
    <text x="188" y="58" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">正格终止：回到主 → 收束</text>

    <g stroke="#343439" stroke-width="1.2" fill="none">
      <line x1="0" y1="86" x2="0" y2="106"/>
      <path d="M0,106 C40,126 140,126 180,106"/>
      <line x1="180" y1="86" x2="180" y2="106"/>
    </g>
    <text x="90" y="132" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">两句构成一个"一问一答" = 乐段</text>

    <text x="0" y="158" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      如果两句的收束方式相同，就只是两个并列乐句，不是乐段 —— "一问一答"才是标志
    </text>
    <text x="0" y="180" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      4 小节为何常见：呼吸长度 + 记忆容量 + 可再分，三个实际条件重合（不是"更正确"）
    </text>
  </g>
</svg>
```

## 听一听：开放与收束

用 `progression` 组件对比**半终止**（停在属，开放）与**正格终止**（回主，收束）。
这就是乐段里前句与后句的差别 —— **分句的判据在终止式，不在旋律的停顿感。**

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V"],"label":"前句：半终止（开放，话没说完）","label_en":"First phrase: half cadence — open, unfinished","hint":"逐个和弦依次听，注意它停在哪","hint_en":"Hear each chord and notice where it stops"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"后句：正格终止（收束，话说完）","label_en":"Second phrase: authentic cadence — closed","hint":"与上一条对比：同样停在属之后，这次回了主","hint_en":"Against the item above — after the same dominant, this one returns home"}
```

## 常见误解

- **「靠气口就能分句」** → 判据是**终止式的强弱**。旋律的停顿可能与实际结构不一致，必须连着和声看。
- **「乐段就是两个乐句」** → 需要**一问一答**（前开放、后收束）。两句都收束只是并列，不构成乐段。
- **「四小节是规定」** → 是三个实际条件（呼吸 / 记忆 / 可再分）的重合，不是规范。
- **「aaba 只是流行歌的结构」** → 它是最古老的旋律组织方式之一，民歌与圣咏里大量存在。
:::

::: en
A melody is not a string of notes but **divided into sentences**. The criterion here is hard-edged:

> **Look at the strength of the cadences** — where the harmony lands is where the melody breaks
> (see [[concept:cadence|cadence]]).

So **you cannot phrase a melody by ear alone**; the harmony must be read with it. This is the beginner's
commonest error: guessing the phrasing from breathing points and getting a structure that does not match.

## Two levels

| Level | Definition | Test |
|---|---|---|
| **phrase** | a unit that can be sung "in one breath", with a rise and a fall | a **cadence** at its end, however weak |
| **period** | **two phrases paired**: the first open, the second closed | first ends on a **half cadence**, second on an **authentic cadence** |

**The essence of a period is the contrast between the two phrases**:

| Position | Harmony | Impression |
|---|---|---|
| end of phrase 1 | **half cadence** (resting on the dominant) | **open**: the sentence is unfinished |
| end of phrase 2 | **authentic cadence** (back to the tonic) | **closed**: the sentence is complete |

If both phrases close the same way, it is not a period but two parallel phrases. **Question and answer is the mark
of a period.**

## Why four bars is so common

A great many melodies use "4 + 4". Not by rule, but because three practical conditions coincide:

| Condition | Explanation |
|---|---|
| **breath** | at a moderate tempo, four bars matches one natural breath |
| **memory** | long enough to hold, short enough not to lose the opening |
| **divisibility** | 4 splits into 2+2 and expands to 8 — very flexible |

All three at once, so it became the "default length" — not because it is more correct.

## Common ways of organising phrases

| Shape | Explanation | Example |
|---|---|---|
| **aa'** | the second phrase varies the first | the commonest |
| **aaba** | three similar phrases plus a turning one | Twinkle Little Star |
| **ab** | two different phrases in contrast | common in lyrical melodies |
| **aab** | two repeats then a turn | common in folk song |

**aa' is the commonest because it does two things at once**: it gives familiarity (a) and freshness (a') — the
same experience as "memorability comes from the ratio of repetition to change" under [[concept:melody|melody]].

## Diagram: the period as question and answer

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The test for a period: first phrase open (half cadence), second closed (authentic)</text>
  </g>

  <g transform="translate(52,56)">
    <g fill="#5B7FA8" opacity=".85">
      <rect x="0" y="-12" width="180" height="22" rx="3"/>
    </g>
    <text x="90" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">phrase 1</text>
    <g stroke="#E8C547" stroke-width="2">
      <line x1="180" y1="-14" x2="180" y2="12"/>
    </g>
    <text x="188" y="2" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">half cadence: open</text>

    <g fill="#E07A3F" opacity=".9">
      <rect x="0" y="44" width="180" height="22" rx="3"/>
    </g>
    <text x="90" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">phrase 2</text>
    <g stroke="#5B7FA8" stroke-width="2">
      <line x1="180" y1="42" x2="180" y2="68"/>
    </g>
    <text x="188" y="58" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">authentic cadence: closed</text>

    <g stroke="#343439" stroke-width="1.2" fill="none">
      <line x1="0" y1="86" x2="0" y2="106"/>
      <path d="M0,106 C40,126 140,126 180,106"/>
      <line x1="180" y1="86" x2="180" y2="106"/>
    </g>
    <text x="90" y="132" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">two phrases make one question and answer — a period</text>

    <text x="0" y="158" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      If both phrases close the same way they are merely parallel, not a period
    </text>
    <text x="0" y="180" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Why four bars: breath, memory and divisibility coincide — not because it is more correct
    </text>
  </g>
</svg>
```

## Listen: open and closed

Use `progression` to compare a **half cadence** (resting on the dominant, open) with an **authentic cadence**
(returning home). That is the difference between a period's first and second phrase — **phrasing is judged by
cadence, not by where the melody seems to pause.**

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V"],"label":"前句：半终止（开放，话没说完）","label_en":"First phrase: half cadence — open, unfinished","hint":"逐个和弦依次听，注意它停在哪","hint_en":"Hear each chord and notice where it stops"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"后句：正格终止（收束，话说完）","label_en":"Second phrase: authentic cadence — closed","hint":"与上一条对比：同样停在属之后，这次回了主","hint_en":"Against the item above — after the same dominant, this one returns home"}
```

## Common misconceptions

- **"You can phrase it by breathing points."** The criterion is the **strength of the cadence**. A melodic pause may
  not match the structure; read it with the harmony.
- **"A period is just two phrases."** It needs **question and answer** (open then closed). Two closing phrases are
  parallel, not a period.
- **"Four bars is a rule."** It is the coincidence of three practical conditions (breath, memory, divisibility),
  not a regulation.
- **"aaba is a pop-song shape."** It is one of the oldest ways of organising a melody and appears throughout folk
  song and chant.
:::
