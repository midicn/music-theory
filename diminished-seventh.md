---
id: diminished-seventh
site: theo
cat: T4
title: 减七和弦
title_en: Diminished Seventh
summary: 四个减三度等距堆叠——只有三种形态，且有两个三全音
summary_en: Four equal minor thirds — only three forms exist, and each holds two tritones
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [减七和弦, diminished seventh, vii°7]
order: 26
links:
  - "[[concept:seventh-chord]]"
  - "[[concept:half-diminished-seventh]]"
  - "[[concept:diminished-triad]]"
  - "[[concept:augmented-triad]]"
  - "[[concept:augmented-diminished]]"
  - "[[concept:cadence]]"
instances:
  - giantmidi-006222 | 琶音练习可弹出减七和弦琶音，用于听它"四边等长"的对称感 | Scale exercises can sound a diminished-seventh arpeggio, letting you hear its four equal sides
  - atepp-000318 | a 小调奏鸣曲：小调第 7 级上的减七和弦解决到主和弦，是最典型的用法 | A sonata in A minor — the diminished seventh on degree 7 resolving to the tonic, its most typical use
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：半音化和声里减七和弦常用来制造不安与转调过渡 | Liszt's transcription of Danse macabre — chromatic harmony often uses diminished sevenths for unease and as pivots
sources:
  - 减七和弦 = 三个减三度叠置（共四个音、根音到七音为减七度），属和声学通则
  - 因结构等距对称而只有三种不同形态、且含两个三全音，为通行和声学表述
updated: 2026-09-24
---

::: zh
减七和弦是 [[concept:diminished-triad|减三和弦]] 再叠一个小三度 —— 但结果不是"再加一个音"那么平淡：

> C 减七 = C–E♭–G♭–**B𝄫**（B𝄫 读作"降 B 再降一次"，实音等于 A）

四个音之间的间隔**全部相等**（每个都是小三度，3 个半音）。这个等距性带来三个很特别的后果。

## 后果一：只有三种

每三个半音结构重复一次，于是 C 起、C♯ 起、D 起各一条就覆盖了全部 ——
**只有三条**，其余都是 [[concept:enharmonic|等音]] 重复。
这与 [[concept:augmented-triad|增三和弦]]（只有四种）是同一类现象：**等距结构必然自我重复**。

## 后果二：两个三全音

四个音里能找出**两对**相距 6 个半音的音：

| 一对 | 音程 |
|---|---|
| C ↔ G♭（根音与五音） | 减五度 |
| E♭ ↔ B𝄫（三音与七音） | 减七度（等音于大六度） |

所以减七和弦是**音程层面最不稳定的和弦**。它一旦出现，几乎必然要求立刻解决。

## 后果三：没有唯一的根音

四个音等距，任何音都可以被听成根音。这带来两个实用后果：

- **听感极不稳定**，常被用来制造恐怖、悬疑与不安（默片配乐、恐怖片配乐里它是常客）；
- **是最好用的转调枢纽之一** —— 同一条减七和弦可以属于四个不同的调，
  换一个解释方向，调性就转到别处去了（见 [[concept:modulation|转调]]）。

## 图示：三种等距结构对照

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">等距 = 对称 = 自我重复、没有根音 —— 三种结构同源</text>
  </g>

  <g transform="translate(44,52)">
    <g transform="translate(0,0)">
      <circle cx="66" cy="60" r="44" fill="none" stroke="#343439"/>
      <g stroke="#E8C547" stroke-width="1.3">
        <line x1="66" y1="16" x2="132" y2="60"/>
        <line x1="132" y1="60" x2="66" y2="104"/>
        <line x1="66" y1="104" x2="66" y2="16"/>
      </g>
      <g fill="#E8C547">
        <circle cx="66" cy="16" r="4"/><circle cx="132" cy="60" r="4"/><circle cx="66" cy="104" r="4"/>
      </g>
      <text x="66" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547" text-anchor="middle">增三和弦</text>
      <text x="66" y="150" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">3 音 · 只有 4 种</text>
    </g>
    <g transform="translate(200,0)">
      <circle cx="66" cy="60" r="48" fill="none" stroke="#343439"/>
      <g stroke="#E07A3F" stroke-width="1.3">
        <line x1="66" y1="12" x2="145" y2="60"/>
        <line x1="145" y1="60" x2="66" y2="108"/>
        <line x1="66" y1="108" x2="66" y2="12"/>
      </g>
      <g stroke="#E07A3F" stroke-width="1.3" stroke-dasharray="3 2">
        <line x1="66" y1="12" x2="66" y2="108"/>
      </g>
      <g fill="#E07A3F">
        <circle cx="66" cy="12" r="4"/><circle cx="145" cy="60" r="4"/><circle cx="66" cy="108" r="4"/>
        <circle cx="66" cy="60" r="4" opacity=".55"/>
      </g>
      <text x="76" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F" text-anchor="middle">减七和弦</text>
      <text x="76" y="150" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">4 音等距 · 只有 3 种</text>
    </g>
    <g transform="translate(400,0)">
      <text x="0" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">对照非等距结构：</text>
      <text x="0" y="42" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">大 / 小三和弦、属七和弦</text>
      <text x="0" y="64" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">→ 音与音不等距</text>
      <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">→ 有明确根音、能站住、能承担功能</text>
    </g>
  </g>
</svg>
```

## 听一听：减七和弦

听的时候注意它"悬在中间"的感觉 —— 比减三和弦更紧张，因为里面有两个三全音。

```audiolab
{"type":"chord","root":"C4","quality":"dim7","inversion":0,"label":"减七和弦（C–E♭–G♭–B𝄫）","label_en":"Diminished seventh (C–E♭–G♭–B𝄫)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「减七和半减七是一回事」** → 七音不同：**半减七**的七音是小七度，**减七**的七音低半个音。听感差别明显，见 [[concept:half-diminished-seventh|半减七和弦]]。
- **「减七和弦有十二个」** → 只有三个（其余是等音重复）。
- **「B𝄫 是写错了」** → 不是。它是合法的重降记号；写成 A 会破坏"每隔一个音级名"的叠置结构。
- **「减七和弦只能用来制造恐怖」** → 那是它的一种用法。它同样是转调枢纽，也是浪漫派和声里最常用的推进工具之一。
:::

::: en
A diminished seventh is a [[concept:diminished-triad|diminished triad]] with one more minor third on top — but
the result is not merely "one more note":

> C diminished seventh = C–E♭–G♭–**B𝄫** (B𝄫 means "B flattened twice", sounding as A)

The four notes are **equally spaced** (each step a minor third, 3 semitones). That equidistance has three
unusual consequences.

## Consequence one: only three of them

The structure repeats every three semitones, so scales from C, C♯ and D cover everything — **there are only
three**, the rest being [[concept:enharmonic|enharmonic]] repeats. This is the same phenomenon as the
[[concept:augmented-triad|augmented triad]] (only four forms): **an equidistant structure must repeat itself.**

## Consequence two: two tritones

Among the four notes you can find **two separate pairs** six semitones apart:

| Pair | Interval |
|---|---|
| C ↔ G♭ (root and fifth) | diminished fifth |
| E♭ ↔ B𝄫 (third and seventh) | diminished seventh (enharmonically a major sixth) |

So the diminished seventh is **the least stable chord at the level of intervals**. Once it appears, resolution
is almost compulsory.

## Consequence three: no single root

With four equal steps, any note can be heard as the root. Two practical results follow:

- it sounds **unmistakably unstable**, which is why it is a fixture of horror and suspense scoring and of silent
  film accompaniment;
- it is one of the **handiest pivots for modulation** — the same chord can belong to four different keys, and
  reinterpreting it turns the music elsewhere (see [[concept:modulation|modulation]]).

## Diagram: three equidistant structures compared

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Equidistant means symmetrical means self-repeating and rootless — three structures, one family</text>
  </g>

  <g transform="translate(44,52)">
    <g transform="translate(0,0)">
      <circle cx="66" cy="60" r="44" fill="none" stroke="#343439"/>
      <g stroke="#E8C547" stroke-width="1.3">
        <line x1="66" y1="16" x2="132" y2="60"/>
        <line x1="132" y1="60" x2="66" y2="104"/>
        <line x1="66" y1="104" x2="66" y2="16"/>
      </g>
      <g fill="#E8C547">
        <circle cx="66" cy="16" r="4"/><circle cx="132" cy="60" r="4"/><circle cx="66" cy="104" r="4"/>
      </g>
      <text x="66" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547" text-anchor="middle">augmented triad</text>
      <text x="66" y="150" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">3 notes, only 4 forms</text>
    </g>
    <g transform="translate(200,0)">
      <circle cx="66" cy="60" r="48" fill="none" stroke="#343439"/>
      <g stroke="#E07A3F" stroke-width="1.3">
        <line x1="66" y1="12" x2="145" y2="60"/>
        <line x1="145" y1="60" x2="66" y2="108"/>
        <line x1="66" y1="108" x2="66" y2="12"/>
      </g>
      <g stroke="#E07A3F" stroke-width="1.3" stroke-dasharray="3 2">
        <line x1="66" y1="12" x2="66" y2="108"/>
      </g>
      <g fill="#E07A3F">
        <circle cx="66" cy="12" r="4"/><circle cx="145" cy="60" r="4"/><circle cx="66" cy="108" r="4"/>
        <circle cx="66" cy="60" r="4" opacity=".55"/>
      </g>
      <text x="76" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F" text-anchor="middle">diminished seventh</text>
      <text x="76" y="150" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">4 notes, only 3 forms</text>
    </g>
    <g transform="translate(400,0)">
      <text x="0" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Compare a non-equidistant chord:</text>
      <text x="0" y="42" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">major / minor triads, dominant seventh</text>
      <text x="0" y="64" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">unequal distances</text>
      <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">a clear root that stands and functions</text>
    </g>
  </g>
</svg>
```

## Listen: the diminished seventh

Notice how it hangs in mid-air — more tense than a diminished triad, because it contains two tritones.

```audiolab
{"type":"chord","root":"C4","quality":"dim7","inversion":0,"label":"减七和弦（C–E♭–G♭–B𝄫）","label_en":"Diminished seventh (C–E♭–G♭–B𝄫)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"Diminished and half-diminished sevenths are the same."** Their sevenths differ: minor in the **half-diminished**, a semitone lower in the **diminished** seventh. The heard difference is plain — see [[concept:half-diminished-seventh|half-diminished seventh]].
- **"There are twelve diminished sevenths."** Only three; the rest are enharmonic repeats.
- **"B𝄫 must be a typo."** It is a legal double flat. Writing A would break the every-other-letter stacking.
- **"It is only good for horror."** That is one use. It is equally a modulation pivot and one of the Romantic era's commonest propulsive devices.
:::
