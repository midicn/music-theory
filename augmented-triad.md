---
id: augmented-triad
site: theo
cat: T4
title: 增三和弦
title_en: Augmented Triad
summary: 两个大三度叠起来——对称、无归属，自然音阶里根本不出现
summary_en: Two major thirds stacked — symmetrical, unanchored, and absent from every diatonic scale
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [增三和弦, augmented triad]
order: 20
links:
  - "[[concept:triad]]"
  - "[[concept:major-triad]]"
  - "[[concept:diminished-seventh]]"
  - "[[concept:whole-tone]]"
  - "[[concept:chromatic]]"
instances:
  - giantmidi-006222 | 琶音练习可弹出增三和弦琶音，用于听它"没有方向"的感觉 | Scale exercises can sound an augmented-triad arpeggio, useful for hearing its lack of direction
  - atepp-000082 | 斯克里亚宾晚期奏鸣曲：其和声以自创的对称音高集合为基础，可与此处的对称结构对照 | A late Scriabin sonata — its harmony rests on symmetrical pitch collections of his own design, a useful parallel
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：半音化写作中常出现增三和弦式的和声，可听它作为过渡的用法 | Liszt's transcription of Danse macabre — chromatic writing often throws up augmented sonorities, hear them used as transitions
sources:
  - 增三和弦 = 大三度 + 大三度，根音到五音为增五度，属和声学通则
  - 增三和弦因结构对称而只有四个不同形态（互为等音），为通行和声学表述
updated: 2026-09-24
---

::: zh
增三和弦是四种三和弦里最特殊的一个：**两个大三度叠起来**。

> C–E–G♯：C 到 E 是大三度，E 到 G♯ 也是大三度

它有两个别的三和弦没有的性质：

| 性质 | 说明 |
|---|---|
| **根音到五音是增五度** | 不是纯五度，也不是减五度 —— 比纯五度**宽**半个音 |
| **结构完全对称** | 三个音之间都是大三度，把任意一个音当根音，结构一模一样 |

## 对称带来的两个后果

**① 它只有四个。** 因为每四个半音重复一次结构，从 C、C♯、D、D♯ 各起一条就覆盖了全部，
再往上都是重复（互为 [[concept:enharmonic|等音]]）。这与 [[concept:diminished-seventh|减七和弦]]
是一样的道理 —— 都是**把八度等分的对称结构**。

**② 它没有方向。** 三和弦的功能性来自"哪个音是根音、要往哪里走"，
而增三和弦的三个音平等，任何一个都可以被听成根音 —— 于是"归属感"消失了。

## 自然音阶里没有它

前面说过，大调音阶的七个三和弦是：**大三 3 · 小三 3 · 减三 1 · 增三 0**。
增三和弦在自然音阶里**一个都不出现**，必须靠**变化音**才能得到。

因此它的典型用法都是"不安定"的：

- **过渡**：从一个和声区滑向另一个，不落在任何稳定和弦上；
- **半音化推进**：三个音同时向上或向下推进半个音，产生"整块滑移"的效果；
- **制造悬浮**：在需要"悬着"的段落作为持续和声（印象派与电影配乐常用）。

## 图示：两种对称结构

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">增三和弦与减七和弦都是"等距"结构 —— 因此都没有唯一的根音</text>
  </g>

  <g transform="translate(44,52)">
    <circle cx="96" cy="60" r="52" fill="none" stroke="#343439"/>
    <g stroke="#E8C547" stroke-width="1.3">
      <line x1="96" y1="8" x2="188" y2="60"/>
      <line x1="188" y1="60" x2="96" y2="112"/>
      <line x1="96" y1="112" x2="96" y2="8"/>
    </g>
    <g fill="#E8C547">
      <circle cx="96" cy="8" r="4.5"/><circle cx="188" cy="60" r="4.5"/><circle cx="96" cy="112" r="4.5"/>
    </g>
    <g font-family="Georgia,serif" font-size="11.5" fill="#F2EEE6" text-anchor="middle">
      <text x="96" y="2">C</text><text x="199" y="64">E</text><text x="96" y="128">G♯</text>
    </g>
    <text x="230" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">增三和弦：三边等长</text>
    <text x="230" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">每个角都是大三度（4 半音）</text>
    <text x="230" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">→ 只有四个形态，且没有根音</text>
    <text x="230" y="112" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">对照：减七和弦是四边等长（减三度 ×4）</text>
    <text x="230" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">两种对称结构都"不指向任何调"</text>
  </g>
</svg>
```

## 听一听：增三和弦

听的时候试着判断"根音是哪个" —— 你会发现判断不了。这既是它的特点，也是它只能当过渡的原因。

```audiolab
{"type":"chord","root":"C4","quality":"aug","inversion":0,"label":"增三和弦（C–E–G♯）","label_en":"Augmented triad (C–E–G♯)","hint":"整体 / 分解 / 宽排列 —— 三个按钮可听出它没有倾向","hint_en":"Block, arpeggio, open — none of them settles anywhere"}
```

## 常见误解

- **「增三和弦就是大三和弦加个升号」** → 是大三度再加一个大三度；根音到五音是**增五度**，不再是纯五度。
- **「它在乐曲里很常见」** → 它**不在任何自然音阶里**，只能靠变化音得到，因此比大/小三和弦少见得多。
- **「转位之后根音会变」** → 因为结构对称，转位后听起来"像换了个和弦"，但按记谱根音仍是原来那个。**这是它最容易被听错的地方。**
- **「对称结构听起来更稳定」** → 恰恰相反。稳定来自音与音之间的**不等距**；等距结构（增三、减七、全音音阶）都没有归属感。
:::

::: en
The augmented triad is the odd one out among the four triads: **two major thirds stacked.**

> C–E–G♯: C to E is a major third, and E to G♯ is a major third again

It has two properties the others lack:

| Property | Explanation |
|---|---|
| **Root to fifth is an augmented fifth** | Not perfect and not diminished — it is a semitone **wider** than perfect |
| **The structure is perfectly symmetrical** | Every span is a major third, so any of the three notes can serve as the root |

## Two consequences of the symmetry

**One: there are only four of them.** The structure repeats every four semitones, so scales starting on C, C♯, D
and D♯ cover everything; the rest are repeats ([[concept:enharmonic|enharmonic]] equivalents). It is the same
logic as the [[concept:diminished-seventh|diminished seventh]] — both are **symmetrical structures that divide
the octave equally**.

**Two: it has no direction.** The function of a triad comes from knowing which note is the root and where the
chord is heading. Here the three notes are equals and any of them can be heard as the root — so the sense of
belonging disappears.

## It does not occur in any diatonic scale

As noted earlier, the seven triads of a major scale run: **three major, three minor, one diminished,
zero augmented.** The augmented triad never appears diatonically; it requires **chromatic alteration**.

Which is why its typical uses are all unsettled ones:

- **Transitions**: sliding from one harmonic area to another without landing on a stable chord;
- **Chromatic motion**: all three notes move a semitone in the same direction, giving a block-slide effect;
- **Suspension**: held as a sustained harmony where hovering is the point (common in Impressionism and film
  scoring).

## Diagram: two symmetrical structures

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The augmented triad and the diminished seventh are both equidistant — so neither has a single root</text>
  </g>

  <g transform="translate(44,52)">
    <circle cx="96" cy="60" r="52" fill="none" stroke="#343439"/>
    <g stroke="#E8C547" stroke-width="1.3">
      <line x1="96" y1="8" x2="188" y2="60"/>
      <line x1="188" y1="60" x2="96" y2="112"/>
      <line x1="96" y1="112" x2="96" y2="8"/>
    </g>
    <g fill="#E8C547">
      <circle cx="96" cy="8" r="4.5"/><circle cx="188" cy="60" r="4.5"/><circle cx="96" cy="112" r="4.5"/>
    </g>
    <g font-family="Georgia,serif" font-size="11.5" fill="#F2EEE6" text-anchor="middle">
      <text x="96" y="2">C</text><text x="199" y="64">E</text><text x="96" y="128">G♯</text>
    </g>
    <text x="230" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">augmented triad: three equal sides</text>
    <text x="230" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">every corner a major third (4 semitones)</text>
    <text x="230" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">so only four forms exist, and none is a root</text>
    <text x="230" y="112" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">Compare: the diminished seventh has four equal sides</text>
    <text x="230" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">both symmetrical shapes point to no key at all</text>
  </g>
</svg>
```

## Listen: the augmented triad

As you listen, try to decide which note is the root — you will not be able to. That is both its character and the
reason it works only as a transition.

```audiolab
{"type":"chord","root":"C4","quality":"aug","inversion":0,"label":"增三和弦（C–E–G♯）","label_en":"Augmented triad (C–E–G♯)","hint":"整体 / 分解 / 宽排列 —— 三个按钮可听出它没有倾向","hint_en":"Block, arpeggio, open — none of them settles anywhere"}
```

## Common misconceptions

- **"An augmented triad is a major triad with a sharp added."** It is a major third plus another major third; root to fifth is an **augmented** fifth, no longer perfect.
- **"It is common in music."** It appears in **no diatonic scale** and requires chromatic alteration, so it is far rarer than major and minor triads.
- **"Inversion changes the root."** Because the structure is symmetrical, inversions *sound* like different chords, yet in notation the root stays put. **This is where the ear is most easily fooled.**
- **"Symmetry should sound more stable."** The opposite. Stability comes from **unequal** distances; equidistant structures (augmented triad, diminished seventh, whole-tone scale) offer no sense of belonging.
:::
