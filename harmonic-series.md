---
id: harmonic-series
site: theo
cat: T1
title: 泛音列
title_en: Harmonic Series
summary: 一个音不是一个频率，而是一串整数倍频率的叠加
summary_en: A single tone is not one frequency but a stack of integer multiples of one
level: core
tags: [乐理, 声学, 基础]
tags_en: [theory, acoustics, basics]
alias: [分音列, overtone series, 谐波]
order: 60
links:
  - "[[concept:sound]]"
  - "[[concept:timbre]]"
  - "[[concept:octave]]"
  - "[[concept:perfect-interval]]"
  - "[[concept:triad]]"
  - "[[concept:pitch]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：管风琴的音栓正是按泛音列的音高逐级叠加的，同时发声时能听出这种「堆叠」 | An organ hymn — organ stops are stacked by harmonic pitch, and you can hear that stacking when they sound together
  - mutopia-000049 | 《绿袖子》加固定低音与变奏：变奏段把和弦音逐个拆出来弹，而和弦音正是同一条泛音列的第 4、5、6 分音 | Greensleeves to a Ground with Division — the divisions pick chord tones apart one by one, and those tones are partials 4, 5 and 6 of one series
  - giantmidi-006222 | 音阶与琶音练习：琶音依次弹出和弦音，而和弦音本身来自同一条泛音列的第 4、5、6 分音 | Scale and arpeggio exercises — an arpeggio spells out chord tones, and those tones are partials 4, 5 and 6 of one series
sources:
  - 泛音列的整数倍频率关系、前几个分音的音高、及 4:5:6 与大三和弦的对应，属音乐声学与和声学通则
  - 第七分音与十二平均律无完全对应，为已知事实
updated: 2026-09-23
---

::: zh
很少有一条规律能同时解释这么多事。泛音列就是那条规律：它同时说清了八度为什么最协和、
五度为什么次之、大三和弦为什么是"最稳的"和弦，以及同一音高由不同乐器发出为什么听起来不同。

## 一个音里藏着什么

弹下一个音，耳朵以为听到的是"一个音"。实际发声的是一整组频率：
一个最低的**基音**，加上一堆频率是基音整数倍的**分音**。

| 分音序号 | 频率 | 相对 C3 的音高 | 音名 |
|---|---|---|---|
| 1 | 1× | 基音 | C3 |
| 2 | 2× | 高八度 | C4 |
| 3 | 3× | 八度 + 纯五度 | G4 |
| 4 | 4× | 两个八度 | C5 |
| 5 | 5× | 两个八度 + 大三度 | E5 |
| 6 | 6× | 两个八度 + 纯五度 | G5 |
| 7 | 7× | 两个八度 + 小七度附近 | B♭5 |
| 8 | 8× | 三个八度 | C6 |

这组音是**算出来的**，不是选出来的。只要基音定了，上面的分音一个不多一个不少。

> 第七分音与十二平均律的任何键都不完全重合。习惯上把它记成 B♭，但它比平均律里的 B♭ 低。
> 这个"低一点"正是泛音列与平均律之间张力的第一个显形处。

## 图示：分音的比例与音高

```svg
<svg viewBox="0 0 640 268" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">以 C3 为基音的前 8 个分音 · 高度表示相对音高，标注为频率倍数</text>
  </g>

  <g transform="translate(60,46)">
    <line x1="-16" y1="152" x2="500" y2="152" stroke="#343439" stroke-width="1.2"/>
    <g>
      <rect x="-16" y="132" width="30" height="20" rx="2" fill="#E07A3F"/>
      <rect x="52" y="112" width="30" height="40" rx="2" fill="#5B7FA8"/>
      <rect x="120" y="98" width="30" height="54" rx="2" fill="#5B7FA8"/>
      <rect x="188" y="88" width="30" height="64" rx="2" fill="#5B7FA8"/>
      <rect x="256" y="80" width="30" height="72" rx="2" fill="#E8C547"/>
      <rect x="324" y="74" width="30" height="78" rx="2" fill="#5B7FA8"/>
      <rect x="392" y="69" width="30" height="83" rx="2" fill="#9C7A3C"/>
      <rect x="460" y="64" width="30" height="88" rx="2" fill="#5B7FA8"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="-1" y="126">C3</text><text x="67" y="106">C4</text><text x="135" y="92">G4</text>
      <text x="203" y="82">C5</text><text x="271" y="74">E5</text><text x="339" y="68">G5</text>
      <text x="407" y="63">B♭5</text><text x="475" y="58">C6</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64" text-anchor="middle">
      <text x="-1" y="170">×1</text><text x="67" y="170">×2</text><text x="135" y="170">×3</text>
      <text x="203" y="170">×4</text><text x="271" y="170">×5</text><text x="339" y="170">×6</text>
      <text x="407" y="170">×7</text><text x="475" y="170">×8</text>
    </g>
    <line x1="-1" y1="192" x2="67" y2="192" stroke="#5B7FA8" stroke-width="1"/>
    <text x="78" y="196" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">×2 = 八度（比例 2:1）</text>
    <line x1="120" y1="212" x2="188" y2="212" stroke="#E8C547" stroke-width="1"/>
    <text x="78" y="216" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">×3 ÷ ×2 = 纯五度（比例 3:2）</text>
    <line x1="188" y1="232" x2="256" y2="232" stroke="#E07A3F" stroke-width="1"/>
    <text x="78" y="236" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">×4 : ×5 : ×6 = 大三和弦（C–E–G）</text>
  </g>
</svg>
```

## 它解释了四件事

**一、八度为什么最协和。** 第 2、4、8 分音全是同名音。两个相差八度的音，重合的分音最多，
所以听起来像"同一个音"。详见 [[concept:octave|八度]]。

**二、纯五度为什么排第二。** 3:2 是最早出现非八度重合的比例（第 3 分音与第 2 分音）。
四度 4:3 紧随其后。频率比越简单，听感越"空"，这就是 [[concept:perfect-interval|纯音程]] 之所以"纯"的来历。

**三、大三和弦为什么最稳。** 第 4、5、6 分音正好是一个大三度叠小三度的结构，也就是 C–E–G。
它不是"被规定成大和弦"，而是**它本来就在泛音列里**。这一层是 [[concept:triad|三和弦]] 与整个和声学的起点。

**四、音色从哪来。** 分音各自有强有弱。基音强、高次分音弱，声音就"圆"；高次分音突出，声音就"亮"或"尖"。
各次分音在开头一瞬间如何变化，决定了乐器听起来的"起音"。这就是 [[concept:timbre|音色]] 的物理底层。

## 听一听：把泛音列逐个点出来

下面这串音不是一个音阶，而是**同一条泛音列的不同分音**（用十二平均律近似演奏）。
第 5 个音开始已经不完全对应真分音，听个结构即可。

```audiolab
{"type":"scale","notes":["C3","C4","G4","C5","E5","G5","A#5","C6"],"label":"C3 的前 8 个分音","label_en":"First 8 partials of C3","hint":"点「上行」听这一串跳着走的音；点「一起响」则接近一个明亮音色的瞬间","hint_en":"Try Up for the leapfrogging series; All together is close to one bright timbre","gap":0.34,"dur":0.32}
```

## 常见误解

- **「泛音是很高的、听不见的音」** → 它一直在响，而且很大一部分在可听范围内。听不见的是超过听觉上限的那部分。
- **「音色取决于基音」** → 基音只决定音高。音色几乎完全由分音的强弱分布决定。
- **「泛音列是乐理规定出来的」** → 它是振动的物理结果，先有它，后有乐理。乐理只是把它总结成了规则。
- **「第七分音就是 B♭」** → 记成 B♭ 是记谱上的妥协，它的实际频率比 B♭ 低。这也是键盘调律需要在两端做微调的原因之一。
- **「钢琴每个音都严格按平均律发声」** → 实际调律会在高低音区做拉伸，因为要把泛音之间的一致性也算进去。
:::

::: en
Few single regularities explain as much at once. The harmonic series does: it accounts for why the octave
is the most consonant interval, why the fifth comes next, why the major triad is the most stable chord, and
why one pitch sounds different on different instruments.

## What is hidden inside one tone

Strike a note and the ear believes it hears "one note". What actually sounds is a whole set of frequencies:
a lowest **fundamental**, plus a stack of **partials** at whole-number multiples of it.

| Partial | Frequency | Pitch relative to C4 | Note name |
|---|---|---|---|
| 1 | 1x | the fundamental | C4 |
| 2 | 2x | one octave up | C5 |
| 3 | 3x | octave + perfect fifth | G5 |
| 4 | 4x | two octaves up | C6 |
| 5 | 5x | two octaves + major third | E6 |
| 6 | 6x | two octaves + perfect fifth | G6 |
| 7 | 7x | near two octaves + minor seventh | B♭6 |
| 8 | 8x | three octaves up | C7 |

These pitches are **calculated**, not chosen. Once the fundamental is fixed, the partials above it are exactly
what they are — no more, no fewer.

> Partial 7 does not coincide with any key of twelve-tone equal temperament. Convention writes it as B♭, but it
> sits lower than the tempered B♭. That small discrepancy is the first visible tension between the series and
> the keyboard.

## Diagram: the ratios and pitches of the partials

```svg
<svg viewBox="0 0 640 268" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">First 8 partials of C3 · height shows relative pitch; labels give the frequency multiplier</text>
  </g>

  <g transform="translate(60,46)">
    <line x1="-16" y1="152" x2="500" y2="152" stroke="#343439" stroke-width="1.2"/>
    <g>
      <rect x="-16" y="132" width="30" height="20" rx="2" fill="#E07A3F"/>
      <rect x="52" y="112" width="30" height="40" rx="2" fill="#5B7FA8"/>
      <rect x="120" y="98" width="30" height="54" rx="2" fill="#5B7FA8"/>
      <rect x="188" y="88" width="30" height="64" rx="2" fill="#5B7FA8"/>
      <rect x="256" y="80" width="30" height="72" rx="2" fill="#E8C547"/>
      <rect x="324" y="74" width="30" height="78" rx="2" fill="#5B7FA8"/>
      <rect x="392" y="69" width="30" height="83" rx="2" fill="#9C7A3C"/>
      <rect x="460" y="64" width="30" height="88" rx="2" fill="#5B7FA8"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="-1" y="126">C3</text><text x="67" y="106">C4</text><text x="135" y="92">G4</text>
      <text x="203" y="82">C5</text><text x="271" y="74">E5</text><text x="339" y="68">G5</text>
      <text x="407" y="63">B♭5</text><text x="475" y="58">C6</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64" text-anchor="middle">
      <text x="-1" y="170">x1</text><text x="67" y="170">x2</text><text x="135" y="170">x3</text>
      <text x="203" y="170">x4</text><text x="271" y="170">x5</text><text x="339" y="170">x6</text>
      <text x="407" y="170">x7</text><text x="475" y="170">x8</text>
    </g>
    <line x1="-1" y1="192" x2="67" y2="192" stroke="#5B7FA8" stroke-width="1"/>
    <text x="78" y="196" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">x2 = octave (ratio 2:1)</text>
    <line x1="120" y1="212" x2="188" y2="212" stroke="#E8C547" stroke-width="1"/>
    <text x="78" y="216" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">x3 / x2 = perfect fifth (ratio 3:2)</text>
    <line x1="188" y1="232" x2="256" y2="232" stroke="#E07A3F" stroke-width="1"/>
    <text x="78" y="236" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">x4 : x5 : x6 = major triad (C–E–G)</text>
  </g>
</svg>
```

## Four things it explains

**One: why the octave is the most consonant.** Partials 2, 4 and 8 all carry the same note name. Two tones an
octave apart share the most partials, so they sound like "one note". See [[concept:octave|octave]].

**Two: why the fifth comes second.** The ratio 3:2 is the first non-octave overlap to appear (partial 3 against
partial 2), with the fourth at 4:3 close behind. The simpler the ratio, the emptier the sound — which is where
[[concept:perfect-interval|perfect intervals]] get their name.

**Three: why the major triad is the most stable.** Partials 4, 5 and 6 already form a major third stacked under
a minor third: C, E, G. The major triad was not decreed by rule; **it was in the series all along.** This is
where [[concept:triad|triads]] and all of harmony begin.

**Four: where timbre comes from.** Partials differ in strength. A strong fundamental with weak upper partials
sounds round; prominent upper partials sound bright or piercing. How the partials behave in the first
instant decides the instrument's attack. That is the physical floor under [[concept:timbre|timbre]].

## Listen: picking out the partials

The row below is not a scale but **different partials of one series**, approximated by equal temperament.
From the fifth tone on the match is no longer exact — listen for the shape.

```audiolab
{"type":"scale","notes":["C3","C4","G4","C5","E5","G5","A#5","C6"],"label":"C3 的前 8 个分音","label_en":"First 8 partials of C3","hint":"点「上行」听这一串跳着走的音；点「一起响」则接近一个明亮音色的瞬间","hint_en":"Try Up for the leapfrogging series; All together is close to one bright timbre","gap":0.34,"dur":0.32}
```

## Common misconceptions

- **"Overtones are high, inaudible tones."** They sound all the time, and a large part of them lies inside the audible range. Only the portion above the hearing limit is inaudible.
- **"Timbre depends on the fundamental."** The fundamental sets the pitch. Timbre is almost entirely determined by how strong each partial is.
- **"The harmonic series was invented by music theory."** It is a physical consequence of vibration. It came first; theory merely wrote it down.
- **"Partial 7 is just B♭."** Writing it as B♭ is a notational compromise; its actual frequency is lower. This is one reason keyboard tuning is stretched at both ends.
- **"Every piano note sounds strictly in equal temperament."** Real tuning stretches the extremes, because agreement between partials has to be factored in too.
:::
