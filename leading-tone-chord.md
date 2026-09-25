---
id: leading-tone-chord
site: theo
cat: T5
title: 导七和弦
title_en: Leading-Tone Seventh
summary: 建立在导音上的七和弦——不用转调就拿到最强的推力
summary_en: A seventh chord built on the leading tone — the strongest push, with no modulation required
level: standard
tags: [乐理, 和声, 调性]
tags_en: [theory, harmony, tonality]
alias: [导七和弦, 导和弦, 导七, vii°7]
order: 30
links:
  - "[[concept:dominant-seventh]]"
  - "[[concept:half-diminished-seventh]]"
  - "[[concept:diminished-seventh]]"
  - "[[concept:cadence]]"
  - "[[concept:harmonic-minor]]"
  - "[[concept:voice-leading]]"
instances:
  - atepp-000318 | a 小调奏鸣曲：小调里导七和弦由自然音阶直接产生，解决到主和弦的过程清楚可辨 | A sonata in A minor — in minor the leading-tone seventh arises diatonically, and its resolution to the tonic is easy to follow
  - cyberhymnal-000695 | 管风琴圣咏：传统和声里导七是终止式的常客，推力比属七更锐 | An organ hymn — the leading-tone seventh is a regular at cadences, with a sharper edge than the dominant seventh
  - giantmidi-006222 | 琶音练习可弹出导七琶音，用于与属七对照"低音位置不同造成的差别" | Scale exercises can sound a leading-tone seventh arpeggio, comparing its bass position with the dominant seventh
sources:
  - 导七和弦建立在音阶第 7 级；大调为半减七、小调（升 7 级）为减七，属和声学通则
  - 导七与属七同属属功能，区别在低音位置（导音而非属音），为通行和声学表述
updated: 2026-09-24
---

::: zh
导七和弦就是把 [[concept:seventh-chord|七和弦]] 建在**第 7 级**上：

> C 大调：B–D–F–A（viiø7，**半减七**）
> a 小调：G♯–B–D–F（vii°7，**减七**）

它和属七和弦（V7）**功能相同** —— 都是属功能，都要解决到主和弦。
差别在**低音位置**：属七的根音是属音，导七的根音是**导音**。

## 为什么它听起来比属七更"锐"

因为导音在最低声部。低音是全曲最被注意的位置（见 [[concept:chord-voicing|和弦排列]]），
把最不稳定的音放在那里，张力自然被放大。

| 和弦 | 低音 | 听感 |
|---|---|---|
| V7 | 属音（稳定） | 有力，但低音本身是稳的 |
| **vii°7** | **导音**（半音下方） | **更尖锐，更像"必须立刻解决"** |

这也解释了为什么在**小调**里作曲家更偏爱导七：小调的属和弦需要升第 7 级才能变成大三和弦
（见 [[concept:harmonic-minor|和声小调]]），而导七**用自然音阶就能得到**
（把第 7 级升上去之后，第 7 级上叠三度就是减七和弦）。

## 两种形态

| 调 | 和弦 | 七音 | 三全音数 |
|---|---|---|---|
| 大调 | viiø7 | 小七度 | 1 |
| 小调 | vii°7 | 减七度 | 2 |

第二行要留意的：小调导七是 [[concept:diminished-seventh|减七和弦]]，
**两个三全音**使它成为所有常用和弦里最不安定的一个。

## 它与属七的替换关系

在功能上二者可以互相替代，但**不能随意互换**：

| 替换 | 效果 |
|---|---|
| V7 → vii°7 | 张力增强（低音变成导音），低音线上升半音进入主音 |
| vii°7 → V7 | 张力减弱，低音变稳，收束更"踏实" |

所以选择哪一个，本质是在选**"结尾要多锐"**。

## 图示：同功能，不同低音

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">两个和弦都要解决到主，区别在低音是"稳的"还是"不稳的"</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#5B7FA8">B♭</text><text x="0" y="24" fill="#6E6A64">F</text>
      <text x="0" y="48" fill="#6E6A64">D</text><text x="0" y="72" fill="#E07A3F">G</text>
      <text x="180" y="0" fill="#5B7FA8">A</text><text x="180" y="24" fill="#6E6A64">F</text>
      <text x="180" y="48" fill="#6E6A64">D</text><text x="180" y="72" fill="#C0504A">B</text>
      <text x="360" y="0" fill="#E8C547">G</text><text x="360" y="24" fill="#E8C547">E</text>
      <text x="360" y="48" fill="#E8C547">C</text>
      <text x="360" y="72" fill="#E8C547">C</text>
    </g>
    <g stroke="#343439" stroke-width="1.2" fill="none">
      <line x1="14" y1="0" x2="166" y2="0"/><polygon points="166,-5 176,0 166,5" fill="#343439" stroke="none"/>
      <line x1="194" y1="0" x2="346" y2="0"/><polygon points="346,-5 356,0 346,5" fill="#343439" stroke="none"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="0" y="92" text-anchor="middle">V7（低音 = 属音，稳）</text>
      <text x="180" y="92" text-anchor="middle">vii°7（低音 = 导音，不稳）</text>
      <text x="360" y="92" text-anchor="middle">I（解决到位）</text>
    </g>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      导音放在最低声部 → 张力被放大，这也是小调偏爱护七的原因
    </text>
    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      功能相同，可互相替代；选哪个等于选"结尾要多锐"
    </text>
  </g>
</svg>
```

## 听一听：导七与属七

先听属七（V7），再听导七（vii°7）。两者都解决到主和弦，但低音的位置让听感截然不同。

```audiolab
{"type":"chord","root":"B3","quality":"dim7","inversion":0,"label":"导七和弦（B–D–F–A♭）","label_en":"Leading-tone seventh (B–D–F–A♭)","hint":"听低音在导音上时的紧张度","hint_en":"Hear the tension when the bass sits on the leading tone"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["V","I"],"label":"属七 → 主（对照）","label_en":"Dominant seventh to tonic, for comparison","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

## 常见误解

- **「导七和属七是两个不同的功能」** → 功能相同，都是属功能，都解决到主。区别只在低音位置与张力大小。
- **「大调里的导七是减七和弦」** → 大调自然的导七是**半减七**（viiø7）。要得到减七，需要把第 4 级也升高（常见于小调或变化音写法）。
- **「导七比属七更"高级"」** → 不是高级，是**更锐**。写作时按需要的力度选，不是按难度选。
- **「导七只能用于小调」** → 大调同样常见，只是形态为半减七而非减七。
:::

::: en
A leading-tone seventh is a [[concept:seventh-chord|seventh chord]] built on **degree 7**:

> C major: B–D–F–A (viiø7, a **half-diminished** seventh)
> A minor: G♯–B–D–F (vii°7, a **diminished** seventh)

It has the **same function** as the dominant seventh: both are dominant-function chords resolving to the tonic.
They differ in **the bass**: the dominant seventh has the dominant as its root, the leading-tone seventh has the
**leading tone**.

## Why it sounds sharper than a dominant seventh

Because the leading tone sits in the lowest voice. The bass is the most attended-to register (see
[[concept:chord-voicing|chord voicing]]), so putting the least stable note there magnifies the tension.

| Chord | Bass | Impression |
|---|---|---|
| V7 | the dominant (stable) | forceful, but the bass itself is settled |
| **vii°7** | **the leading tone** (a semitone below) | **sharper, more "must resolve now"** |

This also explains why composers favour it in **minor**: there the dominant needs a raised seventh to become a
major triad (see [[concept:harmonic-minor|harmonic minor]]), whereas the leading-tone seventh **comes straight
from the raised scale** — stack thirds on the raised seventh and you have a diminished seventh chord.

## The two forms

| Key | Chord | Seventh | Tritones |
|---|---|---|---|
| major | viiø7 | minor seventh | 1 |
| minor | vii°7 | diminished seventh | 2 |

The second row matters: in minor the leading-tone seventh is a
[[concept:diminished-seventh|diminished seventh]], and **two tritones** make it the least settled of the common
chords.

## Substituting one for the other

Functionally they can replace each other, but not indifferently:

| Substitution | Effect |
|---|---|
| V7 → vii°7 | tension increases (the bass becomes the leading tone), and the bass rises a semitone into the tonic |
| vii°7 → V7 | tension eases, the bass settles, and the close feels firmer |

So the choice is really a choice about **how sharp the ending should be**.

## Diagram: same function, different bass

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Both chords resolve to the tonic; the difference is whether the bass is settled</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#5B7FA8">B♭</text><text x="0" y="24" fill="#6E6A64">F</text>
      <text x="0" y="48" fill="#6E6A64">D</text><text x="0" y="72" fill="#E07A3F">G</text>
      <text x="180" y="0" fill="#5B7FA8">A</text><text x="180" y="24" fill="#6E6A64">F</text>
      <text x="180" y="48" fill="#6E6A64">D</text><text x="180" y="72" fill="#C0504A">B</text>
      <text x="360" y="0" fill="#E8C547">G</text><text x="360" y="24" fill="#E8C547">E</text>
      <text x="360" y="48" fill="#E8C547">C</text>
      <text x="360" y="72" fill="#E8C547">C</text>
    </g>
    <g stroke="#343439" stroke-width="1.2" fill="none">
      <line x1="14" y1="0" x2="166" y2="0"/><polygon points="166,-5 176,0 166,5" fill="#343439" stroke="none"/>
      <line x1="194" y1="0" x2="346" y2="0"/><polygon points="346,-5 356,0 346,5" fill="#343439" stroke="none"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="0" y="92" text-anchor="middle">V7 — bass on the dominant, settled</text>
      <text x="180" y="92" text-anchor="middle">vii°7 — bass on the leading tone, unsettled</text>
      <text x="360" y="92" text-anchor="middle">I — arrived</text>
    </g>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      The leading tone in the lowest voice magnifies the tension — why minor keys favour this chord
    </text>
    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Same function, interchangeable; the choice decides how sharp the ending is
    </text>
  </g>
</svg>
```

## Listen: leading-tone seventh against dominant seventh

Hear the dominant seventh (V7), then the leading-tone seventh (vii°7). Both resolve to the tonic, but the bass
position makes them sound completely different.

```audiolab
{"type":"chord","root":"B3","quality":"dim7","inversion":0,"label":"导七和弦（B–D–F–A♭）","label_en":"Leading-tone seventh (B–D–F–A♭)","hint":"听低音在导音上时的紧张度","hint_en":"Hear the tension when the bass sits on the leading tone"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["V","I"],"label":"属七 → 主（对照）","label_en":"Dominant seventh to tonic, for comparison","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

## Common misconceptions

- **"Leading-tone and dominant sevenths are different functions."** Same function: both are dominant-function chords resolving to the tonic. They differ in bass position and degree of tension.
- **"In major, the leading-tone seventh is diminished."** In a major key it is naturally **half-diminished** (viiø7). Getting a diminished seventh needs the fourth degree raised too (common in minor or in chromatic writing).
- **"The leading-tone seventh is more advanced."** Not more advanced — **sharper**. Choose it by the force you need, not by difficulty.
- **"It belongs to minor keys only."** It is just as common in major, merely as a half-diminished rather than diminished form.
:::
