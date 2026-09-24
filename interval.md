---
id: interval
site: theo
cat: T2
title: 音程
title_en: Interval
summary: 两个音之间的距离，由度数与音数共同决定
summary_en: The distance between two notes — decided by degree and by semitones
level: core
tags: [乐理, 音程, 基础]
tags_en: [theory, interval, basics]
alias: [音程关系, interval, 音距]
order: 10
links:
  - "[[concept:pitch]]"
  - "[[concept:interval-number]]"
  - "[[concept:semitone]]"
  - "[[concept:major-minor-interval]]"
  - "[[concept:perfect-interval]]"
  - "[[concept:interval-inversion]]"
  - "[[concept:consonance]]"
  - "[[concept:enharmonic]]"
  - "[[concept:scale]]"
instances:
  - giantmidi-006222 | 音阶与琶音练习——音程正是构成音阶的最小步进单位 | Scales and arpeggio exercises — intervals are the smallest steps a scale is built from
  - mutopia-000522 | 《欢乐颂》主题以级进铺陈，几乎不含跳进，最适合听「大二度」 | The "Ode to Joy" theme moves almost entirely by step — ideal for hearing major seconds
  - giantmidi-007791 | 《致爱丽丝》开头的著名小二度回环，可对照级进的两种宽度 | The famous minor-second turn at the start of "Für Elise" — compare the two widths of stepwise motion
sources:
  - 音程的度数与音数定义属乐理通则，各版教科书表述一致，本文为原创表述
  - 《欢乐颂》《致爱丽丝》主题音高走向依通行乐谱（公有领域）
updated: 2026-09-23
---

::: zh
音程是两个人音之间的距离。这句话听起来像废话，但它包含了乐理里最容易被跳过的一步：
**距离不是一件事，是两件事** —— 隔了几个音级名，和隔了几个半音。

搞不清这一点，后面所有的和弦、音阶、调性都会含糊。

## 度数与音数

先看两个必须同时回答的问题：

- **度数**：从低音到高音，**数过来包含几个音级名**。C 到 E 是 C、D、E 三个，所以是三度。
- **音数**：中间**隔了几个半音**。C 到 E 之间是 C–C♯–D–D♯–E，四个半音。

度数只看**字母名**，音数只看**键盘位置**。这两把尺子各量各的，缺一不可 ——
因为同样是"三度"，C–E 是四个半音，而 D–F 只有三个半音。**它们不可能是同一种三度。**

这就是 [[concept:major-minor-interval|大音程与小音程]] 的由来：四个半音的三度叫**大三度**，
三个半音的三度叫**小三度**。音数决定性质，度数决定名称。

## 图示：同一度数，两种音数

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="24">度数相同（都是三度），音数不同（4 半音 vs 3 半音）</text>
  </g>
  <g transform="translate(24,44)">
    <g font-family="Georgia,serif" font-size="13" fill="#F2EEE6">
      <text x="0" y="0">C – E</text>
      <text x="200" y="0">D – F</text>
    </g>
    <g transform="translate(0,14)">
      <rect x="0" y="0" width="180" height="44" rx="2" fill="#17171A" stroke="#343439"/>
      <g stroke="#343439">
        <line x1="26" y1="0" x2="26" y2="44"/><line x1="52" y1="0" x2="52" y2="44"/>
        <line x1="78" y1="0" x2="78" y2="44"/><line x1="104" y1="0" x2="104" y2="44"/>
        <line x1="130" y1="0" x2="130" y2="44"/><line x1="156" y1="0" x2="156" y2="44"/>
      </g>
      <rect x="3" y="2" width="20" height="40" rx="2" fill="#5B7FA8" opacity=".85"/>
      <rect x="81" y="2" width="20" height="40" rx="2" fill="#5B7FA8" opacity=".85"/>
      <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="2 2">
        <line x1="13" y1="-4" x2="13" y2="-12"/><line x1="91" y1="-4" x2="91" y2="-12"/>
        <line x1="13" y1="-10" x2="91" y2="-10"/>
      </g>
      <text x="52" y="-16" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">4 个半音</text>
    </g>
    <g transform="translate(220,14)">
      <rect x="0" y="0" width="180" height="44" rx="2" fill="#17171A" stroke="#343439"/>
      <g stroke="#343439">
        <line x1="26" y1="0" x2="26" y2="44"/><line x1="52" y1="0" x2="52" y2="44"/>
        <line x1="78" y1="0" x2="78" y2="44"/><line x1="104" y1="0" x2="104" y2="44"/>
        <line x1="130" y1="0" x2="130" y2="44"/><line x1="156" y1="0" x2="156" y2="44"/>
      </g>
      <rect x="29" y="2" width="20" height="40" rx="2" fill="#E07A3F" opacity=".85"/>
      <rect x="81" y="2" width="20" height="40" rx="2" fill="#E07A3F" opacity=".85"/>
      <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="2 2">
        <line x1="39" y1="-4" x2="39" y2="-12"/><line x1="91" y1="-4" x2="91" y2="-12"/>
        <line x1="39" y1="-10" x2="91" y2="-10"/>
      </g>
      <text x="65" y="-16" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">3 个半音</text>
    </g>
    <g transform="translate(0,74)" font-family="system-ui,sans-serif" font-size="12">
      <text x="0" y="0" fill="#5B7FA8">大三度（C–E）</text>
      <text x="220" y="0" fill="#E07A3F">小三度（D–F）</text>
    </g>
    <g transform="translate(0,96)" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="0">亮、稳定，是大调三和弦的底</text>
      <text x="220" y="0">暗、柔，是小调三和弦的底</text>
    </g>
  </g>
</svg>
```

## 听一听：大三度

把两个音分开听，再听它们同时响起 —— 这个"合起来"的音响，就是大三度最直接的听感。

```notation
{"clef":"treble","notes":["C4","E4"],"caption":"C4–E4：四个半音，大三度","caption_en":"C4–E4: four semitones, a major third"}
```

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度 C–E","label_en":"Major 3rd, C–E","hint":"先各自听，再听合起来","hint_en":"Hear each note, then both together","hint2":"换成 E–G 再听一次，音数少了一个半音，宽度明显变窄。","hint2_en":"Now try E–G: one semitone less, and the width audibly narrows."}
```

## 纯音程为什么是"纯"

一、四、五、八度不叫"大"或"小"，而叫**纯**（perfect）。这不是命名习惯，是历史：
这几个音程的频率比最简单 —— 八度 2:1，五度 3:2，四度 4:3。
在 [[concept:harmonic-series|泛音列]] 里，它们出现在最靠前的分音上，因此听觉上最"空"、最没有色彩倾向。

所以才有了这组对应关系：**纯音程没有大、小之分，只有"增减"** ——
纯五度再宽一个半音是增五度，再窄一个是减五度。详见 [[concept:perfect-interval]]。

## 转位：倒过来会变成什么

把两个音上下调换，或者把低音升八度，音程就**转位**了。这里有一条好用的口诀：

> **度数相加等于 9；性质相反（大↔小，增↔减）；纯音程转位后仍为纯。**

- 大三度（3）+ 小六度（6）= 9 ✓
- 纯五度（5）+ 纯四度（4）= 9 ✓

掌握转位能省掉一半的背诵量：只需要熟记到五度，六度以上用减法推。
展开见 [[concept:interval-inversion]]。

## 协和与不协和

听觉上，音程分为**协和**与**不协和**两类，但这个分界不是绝对的，而是**有程度的**：

| 层次 | 音程 | 听感 |
|---|---|---|
| 完全协和 | 纯一、纯八、纯五、纯四 | 融合、无张力 |
| 不完全协和 | 大/小三度、大/小六度 | 有色彩，但稳定 |
| 不协和 | 大/小二度、大/小七度、增四减五 | 需要解决、有推动力 |

西方和声的"张力—解决"机制就建立在这个分层上，详见 [[concept:consonance]]。
在库中找一个终止式听听看，[[concept:cadence]] 一节有具体例子。

## 常见误解

- **"三度就是三个半音"** → 错。三度是**度数**（三个音级名），半音数是**音数**。C–E 是四个半音，D–F 是三个半音，它们都是三度。
- **"增四度和减五度是同一个音程"** → 听起来一样（都是六个半音），但写法与功能不同。C–F♯ 是增四度，C–G♭ 是减五度；前者倾向向外扩张，后者倾向向内收拢。这属于 [[concept:enharmonic|等音]] 现象。
- **"纯音程是音准很准的意思"** → 不是。这里的"纯"指**频率比最简**，与演奏音准无关。
- **"音程越大听起来越远"** → 大跨度不一定更难听出来。纯八度跨度最大，却是最容易辨认的音程之一 —— 因为两个音听起来"像同一个音"。
- **"键盘上数格子就行了"** → 那只能算出音数。度数必须在五线谱上数（要考虑 [[concept:key-signature|调号]] 与临时记号的影响），两者的差别正是等音与重升重降的来源。

## 下一步

音程是 [[concept:scale|音阶]] 的构成单元，也是 [[concept:chord|和弦]] 的最小零件。
想靠耳朵认音程，可以看 [[concept:interval-ear-training|音程听辨方法]]，或直接用主站的
[音程听辨工具](https://midicn.com/tools/) 练手。
:::

::: en
An interval is the distance between two notes. That sounds like a throwaway line, but it hides
the step everyone skips: **a distance is not one thing, it is two** — how many letter names you
pass, and how many semitones you pass.

Miss this, and everything downstream — chords, scales, keys — stays fuzzy.

## Degree and semitones

Two questions, both of which must be answered:

- **Degree**: counting from the lower note up, **how many letter names are included**. C to E is
  C, D, E — three names — so it is a third.
- **Semitones**: **how many half steps** lie between them. From C to E: C–C♯–D–D♯–E, four semitones.

Degree reads **letter names only**. Semitones read **positions on the keyboard only**. Two rulers,
each measuring something different — and neither is optional. Because a "third" can be C–E
(four semitones) or D–F (three semitones). **They cannot possibly be the same kind of third.**

That is where [[concept:major-minor-interval|major and minor intervals]] come from: a third of four
semitones is a **major third**; a third of three semitones is a **minor third**. Semitones decide
the quality; the degree decides the name.

## Diagram: same degree, two semitone counts

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="24">Same degree (both are thirds), different semitone counts (4 vs 3)</text>
  </g>
  <g transform="translate(24,44)">
    <g font-family="Georgia,serif" font-size="13" fill="#F2EEE6">
      <text x="0" y="0">C – E</text>
      <text x="200" y="0">D – F</text>
    </g>
    <g transform="translate(0,14)">
      <rect x="0" y="0" width="180" height="44" rx="2" fill="#17171A" stroke="#343439"/>
      <g stroke="#343439">
        <line x1="26" y1="0" x2="26" y2="44"/><line x1="52" y1="0" x2="52" y2="44"/>
        <line x1="78" y1="0" x2="78" y2="44"/><line x1="104" y1="0" x2="104" y2="44"/>
        <line x1="130" y1="0" x2="130" y2="44"/><line x1="156" y1="0" x2="156" y2="44"/>
      </g>
      <rect x="3" y="2" width="20" height="40" rx="2" fill="#5B7FA8" opacity=".85"/>
      <rect x="81" y="2" width="20" height="40" rx="2" fill="#5B7FA8" opacity=".85"/>
      <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="2 2">
        <line x1="13" y1="-4" x2="13" y2="-12"/><line x1="91" y1="-4" x2="91" y2="-12"/>
        <line x1="13" y1="-10" x2="91" y2="-10"/>
      </g>
      <text x="40" y="-16" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">4 semitones</text>
    </g>
    <g transform="translate(220,14)">
      <rect x="0" y="0" width="180" height="44" rx="2" fill="#17171A" stroke="#343439"/>
      <g stroke="#343439">
        <line x1="26" y1="0" x2="26" y2="44"/><line x1="52" y1="0" x2="52" y2="44"/>
        <line x1="78" y1="0" x2="78" y2="44"/><line x1="104" y1="0" x2="104" y2="44"/>
        <line x1="130" y1="0" x2="130" y2="44"/><line x1="156" y1="0" x2="156" y2="44"/>
      </g>
      <rect x="29" y="2" width="20" height="40" rx="2" fill="#E07A3F" opacity=".85"/>
      <rect x="81" y="2" width="20" height="40" rx="2" fill="#E07A3F" opacity=".85"/>
      <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="2 2">
        <line x1="39" y1="-4" x2="39" y2="-12"/><line x1="91" y1="-4" x2="91" y2="-12"/>
        <line x1="39" y1="-10" x2="91" y2="-10"/>
      </g>
      <text x="58" y="-16" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">3 semitones</text>
    </g>
    <g transform="translate(0,74)" font-family="system-ui,sans-serif" font-size="12">
      <text x="0" y="0" fill="#5B7FA8">Major third (C–E)</text>
      <text x="220" y="0" fill="#E07A3F">Minor third (D–F)</text>
    </g>
    <g transform="translate(0,96)" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="0">Bright and stable — the floor of a major triad</text>
      <text x="220" y="0">Dark and soft — the floor of a minor triad</text>
    </g>
  </g>
</svg>
```

## Listen: a major third

Hear each note alone, then hear them sound together. That combined ring is the most direct
impression of a major third.

```notation
{"clef":"treble","notes":["C4","E4"],"caption":"C4–E4：四个半音，大三度","caption_en":"C4–E4: four semitones, a major third"}
```

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度 C–E","label_en":"Major 3rd, C–E","hint":"先各自听，再听合起来","hint_en":"Hear each note, then both together","hint2":"换成 E–G 再听一次，音数少了一个半音，宽度明显变窄。","hint2_en":"Now try E–G: one semitone less, and the width audibly narrows."}
```

## Why "perfect" intervals are perfect

Unisons, fourths, fifths and octaves are not called major or minor — they are called **perfect**.
That is not habit, it is history: their frequency ratios are the simplest. An octave is 2:1, a
fifth 3:2, a fourth 4:3. In the [[concept:harmonic-series|harmonic series]] they appear among the
earliest partials, which is why they sound the emptiest and least coloured.

Hence the rule: **perfect intervals have no major or minor form, only augmented or diminished.**
Widen a perfect fifth by a semitone and it becomes an augmented fifth; narrow it and it becomes
diminished. See [[concept:perfect-interval]].

## Inversion: what happens when you flip it

Move the upper note down an octave (or the lower one up) and the interval **inverts**. One rule
covers all of it:

> **The degrees add up to 9. The quality flips (major ↔ minor, augmented ↔ diminished).
> Perfect intervals stay perfect.**

- Major third (3) + minor sixth (6) = 9 ✓
- Perfect fifth (5) + perfect fourth (4) = 9 ✓

Inversion halves what you have to memorise: learn up to the fifth, derive everything above it.
Details in [[concept:interval-inversion]].

## Consonance and dissonance

To the ear, intervals fall into **consonant** and **dissonant** — but the line is not absolute.
It is a **gradient**:

| Layer | Intervals | Sound |
|---|---|---|
| Perfect consonance | P1, P8, P5, P4 | Fused, no tension |
| Imperfect consonance | M/m 3rd, M/m 6th | Coloured, but stable |
| Dissonance | M/m 2nd, M/m 7th, tritone | Wants resolution — it pushes |

Western harmony's whole "tension → resolution" engine is built on this gradient — see
[[concept:consonance]]. For a concrete case, listen to a cadence; [[concept:cadence]] has examples.

## Common misconceptions

- **"A third is three semitones."** No. A third is a **degree** (three letter names); semitones are
  a separate count. C–E is four semitones and D–F is three, and both are thirds.
- **"An augmented fourth and a diminished fifth are the same interval."** They sound alike (six
  semitones each) but are written and function differently. C–F♯ expands outward; C–G♭ contracts
  inward. This is the [[concept:enharmonic|enharmonic]] phenomenon.
- **"Perfect means in tune."** It does not. "Perfect" here refers to the **simplest frequency
  ratio**, nothing to do with intonation.
- **"Bigger intervals are harder to hear."** Not so. The octave is the widest of all and one of the
  easiest to identify — because the two notes sound like "the same note".
- **"Just count keys on the piano."** That gives you semitones only. Degrees must be counted on the
  staff, where [[concept:key-signature|key signatures]] and accidentals do apply. The gap between
  the two counts is exactly where enharmonics and double sharps come from.

## Next

Intervals are the building blocks of [[concept:scale|scales]] and the smallest parts of
[[concept:chord|chords]]. To train your ear on them, see
[[concept:interval-ear-training|interval ear training]], or use the
[interval trainer](https://midicn.com/tools/) on the main site.
:::
