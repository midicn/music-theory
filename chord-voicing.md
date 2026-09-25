---
id: chord-voicing
site: theo
cat: T4
title: 和弦排列
title_en: Chord Voicing
summary: 同一组音，挤在一起还是摊开——听感可以完全不同
summary_en: The same notes, packed close or spread wide — and they can sound like different chords
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [和弦排列, 密集排列, 开放排列, voicing]
order: 46
links:
  - "[[concept:chord]]"
  - "[[concept:chord-inversion]]"
  - "[[concept:register]]"
  - "[[concept:consonance]]"
  - "[[concept:chord-color]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：同一批和弦在管风琴上以宽排列铺开，可听开放排列的宏大感 | An organ hymn — the same chords spread wide on the organ, letting you hear the grandeur of open voicing
  - giantmidi-006222 | 琶音练习的宽排列按钮正对应这一条：同一组音摊开到两个八度 | The open-voicing button in the scale exercises is exactly this topic — the same notes spread over two octaves
  - atepp-000195 | 德彪西《月光》：和弦音区被打得很开，低音与上方声部之间留出大片空间 | Debussy's Clair de lune — chords spaced widely, leaving large gaps between bass and upper voices
sources:
  - 排列 = 和弦各音在音区上的分布方式（密集排列 / 开放排列），属和声学通则
  - 低声部排列受制于泛音列的浑浊区（低音区密集排列易糊），为配器与和声写作通行表述
updated: 2026-09-24
---

::: zh
排列（voicing）问的是一个和构成音无关的问题：**这些音分别放在哪个高度？**

| 排列 | 特征 | 听感 |
|---|---|---|
| **密集排列** | 各音尽量靠近，在一个八度内 | 紧实、清晰、辨识度高 |
| **开放排列** | 各音摊开，跨越一个八度以上 | 宽阔、宏大、有时模糊 |
| **混合排列** | 低音单独在下，上方三音密集 | 最常用：既有低频支撑，又有清晰的上方 |

**关键点：排列不改变和弦的名称，但可以改变它听起来像什么。**
同一个 C 大三和弦，密集排列时是一个明确的"和弦"；把 E 与 G 抬高一个八度，
听感会**偏向根音加装饰**，甚至让人怀疑是不是别的和弦。

## 为什么低音区不能挤

这与 [[concept:harmonic-series|泛音列]] 直接相关：**音越低，泛音之间的间隔越近**，
所以低音区的密集排列会让泛音互相打架，听起来浑浊。

| 音区 | 排列惯例 |
|---|---|
| 大字组（很低） | 只放根音或五音，**绝不密集** |
| 小字组（中低） | 允许三度、五度，但仍要留空 |
| 小字一组以上（中高） | 可以密集，甚至可以二度、九度相撞 |

这条规则在配器里体现得最明显：管弦乐的低音区几乎从不出现密集和弦。

## 排列与转位是两件事

二者常被混为一谈：

| | 问的问题 | 例 |
|---|---|---|
| **转位** | **谁**在最下面？ | E 在低音 → 第一转位 |
| **排列** | 各音**分别在哪里**？ | E 在低音，但 G 与 C 分居两个八度 |

转位是"最低音的身份"，排列是"整体在音区上的分布"。**同一转位可以有多种排列。**

## 图示：三音组，三种分布

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">C–E–G 三种摆法：名称不变，听感与"可用音区"都变</text>
  </g>

  <g transform="translate(60,50)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">
      <text x="-16" y="4">高</text><text x="-16" y="70">中</text><text x="-16" y="134">低</text>
    </g>
    <g stroke="#343439" stroke-dasharray="3 3">
      <line x1="0" y1="0" x2="520" y2="0"/><line x1="0" y1="66" x2="520" y2="66"/>
      <line x1="0" y1="132" x2="520" y2="132"/>
    </g>

    <g transform="translate(40,0)">
      <circle cx="0" cy="60" r="6" fill="#5B7FA8"/><circle cx="0" cy="76" r="6" fill="#5B7FA8"/>
      <circle cx="0" cy="92" r="6" fill="#5B7FA8"/>
      <text x="14" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">密集</text>
      <text x="14" y="100" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">紧实清晰</text>
    </g>
    <g transform="translate(220,0)">
      <circle cx="0" cy="20" r="6" fill="#E8C547"/><circle cx="0" cy="76" r="6" fill="#E8C547"/>
      <circle cx="0" cy="132" r="6" fill="#E8C547"/>
      <text x="14" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">开放</text>
      <text x="14" y="100" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">宽阔宏大</text>
    </g>
    <g transform="translate(400,0)">
      <circle cx="0" cy="132" r="6" fill="#E07A3F"/><circle cx="0" cy="56" r="6" fill="#E07A3F"/>
      <circle cx="0" cy="72" r="6" fill="#E07A3F"/>
      <text x="14" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">混合（最常用）</text>
      <text x="14" y="100" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">低音托底 + 上方清晰</text>
    </g>
    <text x="0" y="164" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      低音区不放密集和弦：越低的音，泛音越挤，密集排列会互相打架
    </text>
  </g>
</svg>
```

## 听一听：三种排列

用组件的三个按钮听同一组音 —— **「整体」是密集，「宽排列」是开放**。差别完全来自音区分布。

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"同一个和弦的三种排列","label_en":"One chord in three voicings","hint":"整体 / 分解 / 宽排列 —— 按顺序对比音区分布","hint_en":"Block, arpeggio, open — compare the spacing in order"}
```

## 常见误解

- **「排列就是转位」** → 转位决定最低音是谁，排列决定各音的高度分布。**同一转位可以有多种排列。**
- **「音都一样，听感应该一样」** → 不一样。极端情况下，排列变了会让人怀疑是不是另一个和弦。
- **「音越多越厚」** → 低音区的密集排列只会糊。厚来自**跨音区的分布**，不来自音的数量。
- **「密集排列总是更清晰」** → 在中高音区是；在低音区恰好相反。
:::

::: en
Voicing asks a question unrelated to which notes the chord contains: **how high is each of them placed?**

| Voicing | Feature | Impression |
|---|---|---|
| **close** | notes packed together within an octave | compact, clear, easy to identify |
| **open** | notes spread across more than an octave | wide, grand, sometimes blurred |
| **mixed** | bass alone below, upper three close | the most common: low support plus a clear top |

**The key point: voicing does not change a chord's name, but it can change what the chord sounds like.** A
C major triad in close position is unmistakably "a chord"; raise E and G an octave and the sound leans toward
a root with decoration, to the point of making you doubt the chord's identity.

## Why the low register cannot be packed

This follows directly from the [[concept:harmonic-series|harmonic series]]: **the lower the note, the closer
together its partials are**, so a close voicing in a low register makes those partials collide and turns to mud.

| Register | Voicing convention |
|---|---|
| very low | root or fifth only — **never close** |
| low-middle | thirds and fifths allowed, but leave gaps |
| middle and above | close is fine, even seconds and ninths may collide |

Orchestration shows the rule at its clearest: dense chords almost never appear in a low orchestral register.

## Voicing and inversion are two different things

They are easily conflated:

| | The question asked | Example |
|---|---|---|
| **inversion** | **which** note is lowest? | E in the bass → first inversion |
| **voicing** | where is **each** note placed? | E in the bass, with G and C an octave apart |

Inversion is the bass note's identity; voicing is the distribution across registers. **One inversion admits many
voicings.**

## Diagram: three notes, three distributions

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">C–E–G arranged three ways: the name holds, the sound and the usable register change</text>
  </g>

  <g transform="translate(60,50)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">
      <text x="-16" y="4">high</text><text x="-16" y="70">mid</text><text x="-16" y="134">low</text>
    </g>
    <g stroke="#343439" stroke-dasharray="3 3">
      <line x1="0" y1="0" x2="520" y2="0"/><line x1="0" y1="66" x2="520" y2="66"/>
      <line x1="0" y1="132" x2="520" y2="132"/>
    </g>

    <g transform="translate(40,0)">
      <circle cx="0" cy="60" r="6" fill="#5B7FA8"/><circle cx="0" cy="76" r="6" fill="#5B7FA8"/>
      <circle cx="0" cy="92" r="6" fill="#5B7FA8"/>
      <text x="14" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">close</text>
      <text x="14" y="100" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">compact and clear</text>
    </g>
    <g transform="translate(220,0)">
      <circle cx="0" cy="20" r="6" fill="#E8C547"/><circle cx="0" cy="76" r="6" fill="#E8C547"/>
      <circle cx="0" cy="132" r="6" fill="#E8C547"/>
      <text x="14" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">open</text>
      <text x="14" y="100" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">wide and grand</text>
    </g>
    <g transform="translate(400,0)">
      <circle cx="0" cy="132" r="6" fill="#E07A3F"/><circle cx="0" cy="56" r="6" fill="#E07A3F"/>
      <circle cx="0" cy="72" r="6" fill="#E07A3F"/>
      <text x="14" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">mixed (most used)</text>
      <text x="14" y="100" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">low anchor, clear top</text>
    </g>
    <text x="0" y="164" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      No dense chords low down: the lower the note, the tighter its partials, so close spacing fights itself
    </text>
  </g>
</svg>
```

## Listen: three voicings

Use the component's three buttons on one set of notes — **Block is close, Open is spread.** The difference comes
entirely from register distribution.

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"同一个和弦的三种排列","label_en":"One chord in three voicings","hint":"整体 / 分解 / 宽排列 —— 按顺序对比音区分布","hint_en":"Block, arpeggio, open — compare the spacing in order"}
```

## Common misconceptions

- **"Voicing is inversion."** Inversion fixes the bass note; voicing fixes where each note sits. **One inversion admits many voicings.**
- **"Same notes should sound the same."** They do not. In extreme cases a different voicing makes you doubt the chord's identity.
- **"More notes means thicker."** A close voicing low down only muddies. Thickness comes from **distribution across registers**, not from note count.
- **"Close voicing is always clearer."** In the middle and upper registers yes; in the bass register exactly the opposite.
:::
