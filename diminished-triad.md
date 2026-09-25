---
id: diminished-triad
site: theo
cat: T4
title: 减三和弦
title_en: Diminished Triad
summary: 两个小三度叠起来——五音被压低，因而必须解决
summary_en: Two minor thirds stacked — its fifth is squeezed flat, so it must resolve
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [减三和弦, diminished triad]
order: 18
links:
  - "[[concept:triad]]"
  - "[[concept:major-triad]]"
  - "[[concept:minor-triad]]"
  - "[[concept:harmonic-minor]]"
  - "[[concept:scale-harmony]]"
  - "[[concept:half-diminished-seventh]]"
instances:
  - giantmidi-006222 | 琶音练习里可弹出减三和弦琶音，用于听它"不稳"的具体位置 | Scale exercises can sound a diminished-triad arpeggio, pointing at exactly where it feels unstable
  - atepp-000318 | a 小调奏鸣曲：小调第 2 级与第 7 级上都是减三和弦，解决到主和弦的过程清晰可辨 | A sonata in A minor — the diminished triads on degrees 2 and 7 resolve to the tonic in a way that is easy to follow
  - mutopia-000280 | 巴赫二部创意曲第一首：减三和弦出现在经过与推进处，随即被解决 | Bach's first two-part invention — diminished triads appear as passing and driving sonorities, resolved at once
sources:
  - 减三和弦 = 小三度 + 小三度，根音到五音为减五度，属和声学通则
  - 大调音阶上仅第 7 级为减三和弦、小调第 2 级与第 7 级常为减三和弦，为通行和声学表述
updated: 2026-09-24
---

::: zh
减三和弦的结构是**两个小三度叠起来**：

> C–E♭–G♭：C 到 E♭ 是小三度，E♭ 到 G♭ 也是小三度

它和 [[concept:major-triad|大三和弦]]、[[concept:minor-triad|小三和弦]] 的差别集中在**五音**：
前两者的根音到五音都是**纯五度**，而减三和弦是**减五度**（少了半个音）。

这一个半音，把"稳定"抽走了：

| 要素 | 大三 / 小三和弦 | 减三和弦 |
|---|---|---|
| 根音到五音 | 纯五度（7 半音） | **减五度**（6 半音） |
| 内部是否含增四度关系 | 否 | **根音到五音本身就是三全音** |
| 听感 | 可以站住 | **必须走** |

## 它几乎总在"解决"的路上

减三和弦是**功能性和弦**：它本身很少作为目标，主要作用是把音乐推向下一个和弦。

| 出现位置 | 解决方向 |
|---|---|
| **大调第 7 级**（vii°） | 根音是导音 → 强烈指向 I 级 |
| **小调第 2 级**（ii°） | 五音是下属方向的导音 → 指向 V 级 |
| **小调第 7 级**（vii°） | 同上，指向 i 级 |

**大调音阶上只有一个减三和弦**（第 7 级）—— 这也是它在七个调内和弦里最"显眼"的原因：
唯一不稳定，唯一必须解决，因此成为终止式里最强的一步
（见 [[concept:cadence|终止式]]、[[concept:harmonic-function|和声功能]]）。

## 图示：五音低了半个音

```svg
<svg viewBox="0 0 640 186" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">三音已经低了，五音再低半个音 —— 稳定感就没了</text>
  </g>

  <g transform="translate(48,56)">
    <g font-family="Georgia,serif" font-size="13" text-anchor="middle">
      <text x="0" y="0" fill="#6E6A64">C</text><text x="80" y="0" fill="#6E6A64">E♭</text><text x="170" y="0" fill="#6E6A64">G</text>
      <text x="300" y="0" fill="#C0504A">C</text><text x="380" y="0" fill="#C0504A">E♭</text><text x="470" y="0" fill="#C0504A">G♭</text>
    </g>
    <g stroke="#6E6A64" stroke-width="1.2">
      <line x1="0" y1="14" x2="170" y2="14"/><line x1="0" y1="10" x2="0" y2="18"/><line x1="170" y1="10" x2="170" y2="18"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.2">
      <line x1="300" y1="14" x2="470" y2="14"/><line x1="300" y1="10" x2="300" y2="18"/><line x1="470" y1="10" x2="470" y2="18"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="40" fill="#6E6A64">小三和弦：根音到五音 = 纯五度</text>
      <text x="300" y="40" fill="#C0504A">减三和弦：根音到五音 = 减五度</text>
      <text x="0" y="66" fill="#6E6A64">骨架还在，可以站住</text>
      <text x="300" y="66" fill="#C0504A">骨架被削去一半，必须解决</text>
      <text x="0" y="90" fill="#5B7FA8">另：减三和弦的根音到五音是增四度 / 减五度关系 —— 三全音本身就是最强的推动力</text>
    </g>
  </g>
</svg>
```

## 听一听：减三和弦

先听整体（不稳、有推力），再点「分解」听五音被压低的位置。

```audiolab
{"type":"chord","root":"C4","quality":"dim","inversion":0,"label":"减三和弦（C–E♭–G♭）","label_en":"Diminished triad (C–E♭–G♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「减三和弦是"坏"的和弦」** → 它是**功能性**和弦。没有它，终止式就失去最强的一步。
- **「大调音阶上有好几个减三和弦」** → 只有一个（第 7 级）。小调里通常有两个（第 2、7 级）。
- **「减三和弦与减七和弦是一回事」** → 减三和弦三个音，减七和弦四个音；后者见 [[concept:diminished-seventh|减七和弦]]。
- **「加了七音就变成减七和弦」** → 加小七度是**半减七和弦**（见 [[concept:half-diminished-seventh|半减七和弦]]），要加**减**七度才是减七和弦。
:::

::: en
A diminished triad is **two minor thirds stacked**:

> C–E♭–G♭: C to E♭ is a minor third, and E♭ to G♭ is a minor third again

Its difference from the major and minor triads lies in the **fifth**: in both of those, root to fifth is a
**perfect fifth**, while here it is a **diminished fifth** — half a semitone narrower.

That one semitone takes away the stability:

| Element | Major / minor triad | Diminished triad |
|---|---|---|
| Root to fifth | perfect fifth (7 semitones) | **diminished fifth** (6) |
| Internal tritone | no | **root to fifth is itself a tritone** |
| Impression | can stand | **must move** |

## It is almost always on its way somewhere

The diminished triad is a **functional chord**: it is rarely the destination, and mostly propels the music into
the next chord.

| Position | Where it resolves |
|---|---|
| **degree 7 in major** (vii°) | the root is the leading tone → strongly points to I |
| **degree 2 in minor** (ii°) | its fifth acts as a leading tone down to V |
| **degree 7 in minor** (vii°) | likewise, pointing to i |

**A major scale contains exactly one diminished triad** (on degree 7) — which is why it stands out among the
seven diatonic chords: the only unstable one, the only one that must resolve, and therefore the strongest step
in a cadence (see [[concept:cadence|cadence]] and [[concept:harmonic-function|harmonic function]]).

## Diagram: the fifth drops half a semitone

```svg
<svg viewBox="0 0 640 186" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The third is already low; drop the fifth as well and stability disappears</text>
  </g>

  <g transform="translate(48,56)">
    <g font-family="Georgia,serif" font-size="13" text-anchor="middle">
      <text x="0" y="0" fill="#6E6A64">C</text><text x="80" y="0" fill="#6E6A64">E♭</text><text x="170" y="0" fill="#6E6A64">G</text>
      <text x="300" y="0" fill="#C0504A">C</text><text x="380" y="0" fill="#C0504A">E♭</text><text x="470" y="0" fill="#C0504A">G♭</text>
    </g>
    <g stroke="#6E6A64" stroke-width="1.2">
      <line x1="0" y1="14" x2="170" y2="14"/><line x1="0" y1="10" x2="0" y2="18"/><line x1="170" y1="10" x2="170" y2="18"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.2">
      <line x1="300" y1="14" x2="470" y2="14"/><line x1="300" y1="10" x2="300" y2="18"/><line x1="470" y1="10" x2="470" y2="18"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="40" fill="#6E6A64">minor triad: root to fifth is a perfect fifth</text>
      <text x="300" y="40" fill="#C0504A">diminished triad: root to fifth is a diminished fifth</text>
      <text x="0" y="66" fill="#6E6A64">the frame holds; the chord can stand</text>
      <text x="300" y="66" fill="#C0504A">half the frame is gone; it must resolve</text>
      <text x="0" y="90" fill="#5B7FA8">Also: root to fifth is a tritone — and that interval is the strongest driving force there is</text>
    </g>
  </g>
</svg>
```

## Listen: the diminished triad

Hear the block first (unstable, pushing), then press Arpeggio to hear where the fifth is squeezed down.

```audiolab
{"type":"chord","root":"C4","quality":"dim","inversion":0,"label":"减三和弦（C–E♭–G♭）","label_en":"Diminished triad (C–E♭–G♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"A diminished triad is a bad chord."** It is a **functional** chord. Without it a cadence loses its strongest step.
- **"A major scale contains several diminished triads."** Exactly one, on degree 7. Minor keys usually have two (degrees 2 and 7).
- **"A diminished triad and a diminished seventh are the same."** Three notes versus four — see [[concept:diminished-seventh|diminished seventh]].
- **"Add a seventh and it becomes diminished."** Adding a minor seventh gives a **half-diminished** seventh (see [[concept:half-diminished-seventh|half-diminished seventh]]); only a diminished seventh completes the diminished seventh chord.
:::
