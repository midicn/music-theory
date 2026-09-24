---
id: chord
site: theo
cat: T4
title: 和弦
title_en: Chord
summary: 三个以上的音同时发声，且按三度叠起来——"和弦"的关键在后半句
summary_en: Three or more notes sounding together — and stacked in thirds, which is the part that matters
level: core
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [和弦是什么, chord]
order: 10
links:
  - "[[concept:triad]]"
  - "[[concept:seventh-chord]]"
  - "[[concept:chord-inversion]]"
  - "[[concept:chord-voicing]]"
  - "[[concept:harmonic-function]]"
  - "[[concept:scale-harmony]]"
instances:
  - giantmidi-006222 | 琶音练习把和弦的音逐个弹出，可先听"分解的和弦"，再想它们同时响是什么样 | Arpeggio exercises play chord tones one at a time — hear the chord broken up before imagining it struck together
  - cyberhymnal-000695 | 管风琴圣咏：整首由同时发声的和弦铺成，是最典型的"柱式和弦"写法 | An organ hymn — built throughout from chords sounding together, the classic block-chord texture
  - mutopia-000522 | 《欢乐颂》主题配上和声时，和弦的选择几乎全由这条音阶决定 | Harmonised, the Ode to Joy theme takes chords almost entirely determined by its scale
sources:
  - 和弦为三个或以上音同时发声、按三度叠置构成，属和声学通则
  - 三度叠置以外的音群（如四度叠置、音块）属近现代用法，为通行和声学表述
updated: 2026-09-23
---

::: zh
"和弦"这个词容易被理解成"几个音一起响"。但**只要三个音同时响就算和弦吗？**
不算 —— 那样的话，任何一个音簇都成了和弦。真正的定义是两句话：

> **三个或三个以上的音同时发声，并且这些音是按三度依次叠起来的。**

后半句才是关键。它把"任意音群"筛掉，只留下有明确结构、可以命名、可以承担功能的那一类。

## 按三度叠：和弦的生成方式

从任意一个音出发，往上每隔一个音取一个，就得到一层层叠起来的三度：

| 叠几层 | 名称 | 构成 | 例（从 C 起） |
|---|---|---|---|
| 两个三度 | **三和弦** | 根音 + 三音 + 五音 | C–E–G |
| 三个三度 | **七和弦** | 再加七音 | C–E–G–B |
| 四个以上 | 九 / 十一 / 十三和弦 | 继续往上叠 | C–E–G–B–D … |

**和弦的名字来自最下面那个音**（根音），最高那个音决定它"叠到第几层"。
所以"属七和弦"听起来神秘，拆开就是"某个根音上叠三个三度"。

## 和弦的三个要素

| 要素 | 决定 | 例 |
|---|---|---|
| **根音** | 和弦叫什么 | C–E–G 是"C 和弦" |
| **性质** | 明暗与稳定性 | 大三 / 小三 / 减三 / 增三 |
| **排列** | 听感厚薄与声部空间 | 同样三个音，挤在低音区还是摊开在两个八度（见 [[concept:chord-voicing|和弦排列]]） |

再加上**转位**（哪个音在最低声部，见 [[concept:chord-inversion|转位与数字低音]]），
四个变量就足以描述绝大多数和弦。

## 图示：三度叠置 vs 任意音群

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">左：按三度叠 → 可命名、可承担功能　右：音程杂乱 → 是音簇，不是和弦</text>
  </g>

  <g transform="translate(48,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="30">E</text><text x="0" y="60">G</text>
      <text x="0" y="90">B</text><text x="0" y="120">D</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="14" y1="0" x2="14" y2="60"/>
      <line x1="10" y1="0" x2="18" y2="0"/><line x1="10" y1="60" x2="18" y2="60"/>
      <line x1="26" y1="30" x2="26" y2="90"/>
      <line x1="22" y1="30" x2="30" y2="30"/><line x1="22" y1="90" x2="30" y2="90"/>
      <line x1="38" y1="60" x2="38" y2="120"/>
      <line x1="34" y1="60" x2="42" y2="60"/><line x1="34" y1="120" x2="42" y2="120"/>
    </g>
    <text x="52" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">每层都是三度</text>
    <text x="52" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">→ 三和弦 / 七和弦 / 九和弦</text>

    <g transform="translate(280,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="30">D♭</text><text x="0" y="60">F♯</text>
        <text x="0" y="90">A</text>
      </g>
      <g stroke="#C0504A" stroke-width="1.2">
        <line x1="14" y1="0" x2="14" y2="30"/>
        <line x1="10" y1="0" x2="18" y2="0"/><line x1="10" y1="30" x2="18" y2="30"/>
        <line x1="26" y1="30" x2="26" y2="60"/>
        <line x1="26" y1="60" x2="26" y2="90"/>
      </g>
      <text x="42" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">音程杂乱</text>
      <text x="42" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">→ 音簇，不是和弦</text>
    </g>
  </g>
</svg>
```

## 听一听：和弦的三副面孔

同一个 C 大三和弦，三种听法：**整体**（柱式）、**分解**（琶音）、**宽排列**（摊开到两个八度）。
和弦的"性格"一半来自构成音，另一半来自排列方式。

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"C 大三和弦","label_en":"C major triad","hint":"整体 / 分解 / 宽排列 —— 三个按钮听同一组音","hint_en":"Block, arpeggio, open — three takes on the same notes"}
```

## 常见误解

- **「三个音一起响就是和弦」** → 必须是**三度叠置**。音程杂乱的音群是音簇，不能命名也不承担功能。
- **「和弦必须三个音」** → 两个音只是音程；三个以上都算，七、九、十三和弦都是和弦。
- **「和弦的根音就是最低音」** → 转位之后最低音不是根音，但根音仍是根音（见 [[concept:chord-inversion|转位]]）。
- **「同一组音只有一种听感」** → 排列与转位会让同一组音听起来完全不同（见 [[concept:chord-voicing|排列]]）。
:::

::: en
"Chord" is easily read as "a few notes sounding together". But **is any three notes struck at once a chord?**
No — by that reading any cluster would qualify. The real definition has two halves:

> **Three or more notes sounding together, stacked one third apart.**

The second half does the work. It filters out arbitrary note groups and leaves the kind that has a definite
structure, can be named, and can carry harmonic function.

## Stacking thirds: how chords are generated

Start on any note and take every other note upward, and you pile up thirds:

| Layers | Name | Content | Example (from C) |
|---|---|---|---|
| two thirds | **triad** | root + third + fifth | C–E–G |
| three thirds | **seventh chord** | add the seventh | C–E–G–B |
| four or more | ninth / eleventh / thirteenth | keep stacking | C–E–G–B–D … |

**A chord is named after its lowest stacked note** (the root), and its topmost note says how far the stacking
goes. So "dominant seventh" sounds mysterious and unpacks into "three thirds stacked on one root".

## Three elements of a chord

| Element | Decides | Example |
|---|---|---|
| **root** | the chord's name | C–E–G is "a C chord" |
| **quality** | brightness and stability | major / minor / diminished / augmented |
| **voicing** | thickness and spacing | the same three notes squeezed low or spread over two octaves (see [[concept:chord-voicing|voicing]]) |

Add **inversion** (which note is in the bass — see [[concept:chord-inversion|inversion and figured bass]]) and
those four variables describe the great majority of chords.

## Diagram: stacked thirds versus an arbitrary group

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Left: stacked in thirds, so nameable and functional. Right: mixed intervals, a cluster rather than a chord</text>
  </g>

  <g transform="translate(48,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="30">E</text><text x="0" y="60">G</text>
      <text x="0" y="90">B</text><text x="0" y="120">D</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="14" y1="0" x2="14" y2="60"/>
      <line x1="10" y1="0" x2="18" y2="0"/><line x1="10" y1="60" x2="18" y2="60"/>
      <line x1="26" y1="30" x2="26" y2="90"/>
      <line x1="22" y1="30" x2="30" y2="30"/><line x1="22" y1="90" x2="30" y2="90"/>
      <line x1="38" y1="60" x2="38" y2="120"/>
      <line x1="34" y1="60" x2="42" y2="60"/><line x1="34" y1="120" x2="42" y2="120"/>
    </g>
    <text x="52" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">every layer a third</text>
    <text x="52" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">triad / seventh / ninth</text>

    <g transform="translate(300,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="30">D♭</text><text x="0" y="60">F♯</text>
        <text x="0" y="90">A</text>
      </g>
      <g stroke="#C0504A" stroke-width="1.2">
        <line x1="14" y1="0" x2="14" y2="30"/>
        <line x1="10" y1="0" x2="18" y2="0"/><line x1="10" y1="30" x2="18" y2="30"/>
        <line x1="26" y1="30" x2="26" y2="60"/>
        <line x1="26" y1="60" x2="26" y2="90"/>
      </g>
      <text x="42" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">mixed intervals</text>
      <text x="42" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">a cluster, not a chord</text>
    </g>
  </g>
</svg>
```

## Listen: three faces of one chord

The same C major triad heard three ways: **as a block**, **broken up** (arpeggio), and **spread wide** across two
octaves. Half a chord's character comes from its notes, the other half from how they are arranged.

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"C 大三和弦","label_en":"C major triad","hint":"整体 / 分解 / 宽排列 —— 三个按钮听同一组音","hint_en":"Block, arpeggio, open — three takes on the same notes"}
```

## Common misconceptions

- **"Any three notes together make a chord."** They must be **stacked in thirds**. Mixed intervals give a cluster, which cannot be named or carry function.
- **"A chord has three notes."** Two notes are an interval; three or more are chords, and sevenths, ninths and thirteenths are all chords.
- **"A chord's root is its lowest note."** After inversion the bass is not the root, yet the root is still the root (see [[concept:chord-inversion|inversion]]).
- **"One set of notes sounds one way."** Voicing and inversion make the same notes sound completely different (see [[concept:chord-voicing|voicing]]).
:::
