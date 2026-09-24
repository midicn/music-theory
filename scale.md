---
id: scale
site: theo
cat: T3
title: 音阶
title_en: Scale
summary: 音阶是从十二个半音里挑音并排好队的结果，挑法与排法决定风格
summary_en: A scale is a selection of pitches out of twelve, put in order — the choices shape the style
level: core
tags: [乐理, 音阶, 基础]
tags_en: [theory, scale, basics]
alias: [音阶是什么, scale, 调式音阶]
order: 10
links:
  - "[[concept:pitch]]"
  - "[[concept:semitone]]"
  - "[[concept:major-scale]]"
  - "[[concept:minor-scale]]"
  - "[[concept:pentatonic]]"
  - "[[concept:key-signature]]"
instances:
  - giantmidi-006222 | 音阶与琶音练习：把一条音阶原原本本走完，是认识"音阶"最直接的材料 | Scale and arpeggio exercises state a scale exactly as it is — the most direct material for hearing one
  - mutopia-000522 | 《欢乐颂》主题只用一条大调音阶里的音，旋律感正是从"用哪几个音"出发的 | The Ode of Joy theme uses only the notes of one major scale — the melodic character starts from which notes are chosen
  - pdmx-000607 | 莫扎特《小星星变奏曲》主题：整首变奏都建立在那七个音上，可听出音阶怎么撑起一整首作品 | Mozart's variations on Ah vous dirai-je maman — every variation stays within those seven notes, showing how a scale can carry a whole piece
sources:
  - 音阶为"按一定音程结构排列的音高集合"，属乐理通则
  - 音阶可由 12 个半音中择取若干音构成、并可移调，为通行表述
updated: 2026-09-23
---

::: zh
一个八度里有 12 个半音。绝大多数音乐只从里面挑 5 到 7 个来用，并按高低排好队 ——
**这个"挑 + 排"的结果，就是音阶**。

挑哪些、怎么排，直接决定了音乐听起来是明亮、忧郁、异域还是漂浮。
所以音阶不是基础知识，它是**风格的第一道闸门**。

## 音阶的两件事：选择与排列

| 要素 | 说明 | 例 |
|---|---|---|
| **选择** | 从 12 个半音里取几个 | 大调取 7 个，五声取 5 个，全音取 6 个 |
| **排列** | 这些音之间的**音程结构** | 大调 = 全全半全全全半 |

**排列比选择更重要**：同样是 7 个音，把半音的位置挪一挪，就得到完全不同的调式（见 [[concept:dorian|多里亚]] 等）。
换句话说，音阶的性格写在**半音落在哪儿**，而不是"用了几个音"。

## 主音：音阶的"家"

音阶的第一个音叫**主音**（tonic）。它不只是起点，还是听感上的归宿：
旋律走到主音时会觉得"到家了"。

把同一条音程结构从不同的音上开始，就得到**同一种音阶的不同调**——
这就是移调。结构不变，绝对高度全变。调号的存在就是为了记录这件事，
见 [[concept:key-signature|调号]]。

## 图示：从 12 个半音里挑

```svg
<svg viewBox="0 0 640 224" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">上排：十二个半音全在 · 下排：只留下大调音阶的七个</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="0">C</text><text x="44" y="0">C♯</text><text x="88" y="0">D</text>
      <text x="132" y="0">D♯</text><text x="176" y="0">E</text><text x="220" y="0">F</text>
      <text x="264" y="0">F♯</text><text x="308" y="0">G</text><text x="352" y="0">G♯</text>
      <text x="396" y="0">A</text><text x="440" y="0">A♯</text><text x="484" y="0">B</text>
    </g>
    <g>
      <g fill="#5B7FA8" opacity=".18">
        <rect x="-20" y="10" width="40" height="30" rx="2"/>
        <rect x="24" y="10" width="40" height="30" rx="2"/>
        <rect x="68" y="10" width="40" height="30" rx="2"/>
        <rect x="112" y="10" width="40" height="30" rx="2"/>
        <rect x="156" y="10" width="40" height="30" rx="2"/>
        <rect x="200" y="10" width="40" height="30" rx="2"/>
        <rect x="244" y="10" width="40" height="30" rx="2"/>
        <rect x="288" y="10" width="40" height="30" rx="2"/>
        <rect x="332" y="10" width="40" height="30" rx="2"/>
        <rect x="376" y="10" width="40" height="30" rx="2"/>
        <rect x="420" y="10" width="40" height="30" rx="2"/>
        <rect x="464" y="10" width="40" height="30" rx="2"/>
      </g>
      <g fill="#E07A3F" opacity=".9">
        <rect x="-20" y="56" width="40" height="30" rx="2"/>
        <rect x="68" y="56" width="40" height="30" rx="2"/>
        <rect x="156" y="56" width="40" height="30" rx="2"/>
        <rect x="200" y="56" width="40" height="30" rx="2"/>
        <rect x="288" y="56" width="40" height="30" rx="2"/>
        <rect x="376" y="56" width="40" height="30" rx="2"/>
        <rect x="464" y="56" width="40" height="30" rx="2"/>
      </g>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="76">C</text><text x="88" y="76">D</text><text x="176" y="76">E</text>
      <text x="220" y="76">F</text><text x="308" y="76">G</text><text x="396" y="76">A</text>
      <text x="484" y="76">B</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="112">被留下的五个半音位置：C♯ D♯ F♯ G♯ A♯ —— 它们不是"错的音"，只是不属于这条音阶</text>
      <text x="0" y="134">移动一个半音的位置，结构就变了：大调、小调、各种调式就此分家</text>
    </g>
  </g>
</svg>
```

## 听一听：一条音阶的走法

音阶的听感来自**全音与半音的位置**。上行时留意哪一步"迈得小"——那一步定义了整条音阶的性格。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"C 大调音阶","label_en":"C major scale","hint":"点「上行」听半音落在哪里","hint_en":"Try Up and listen for where the semitones fall","gap":0.38}
```

## 常见误解

- **「音阶就是音的顺序」** → 顺序只是表象，本质是**音程结构**（全音半音怎么排）。
- **「音阶越多越厉害」** → 一条大调音阶加几条调式，已能覆盖绝大多数音乐。数量不是能力。
- **「音阶之外的都是错音」** → 变化音（见 [[concept:chromatic|半音阶]]）是常用的色彩手段，只是不属于当前音阶而已。
- **「同一条音阶的不同调只是高低不同」** → 结构相同、绝对高度不同，记谱（调号）与乐器上的手感也跟着变。
:::

::: en
An octave holds twelve semitones. Most music picks five to seven of them and lines them up from low to high.
**That act of selecting and ordering is a scale.**

Which pitches are chosen, and how they are ordered, decides whether music sounds bright, melancholy, exotic or
floating. So a scale is not elementary background — it is **the first gate on style**.

## Two operations: selection and ordering

| Element | What it means | Example |
|---|---|---|
| **selection** | taking some of the twelve semitones | major takes 7, pentatonic takes 5, whole tone takes 6 |
| **ordering** | the **interval pattern** between them | major = whole, whole, half, whole, whole, whole, half |

**Ordering matters more than selection.** Take the same seven pitches and move where the semitones fall and you
get an entirely different mode (see [[concept:dorian|Dorian]] and friends). A scale's character is written in
**where the semitones land**, not in how many notes it uses.

## The tonic: a scale's home

The first degree is the **tonic**. It is not merely a starting point; it is where the ear wants to end. A
melody arriving on the tonic feels like coming home.

Start the same interval pattern on a different pitch and you have **the same scale in a different key** — that
is transposition. The pattern is unchanged; the absolute pitches all move. Key signatures exist to record this;
see [[concept:key-signature|key signature]].

## Diagram: choosing from twelve

```svg
<svg viewBox="0 0 640 224" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Top row: all twelve semitones. Bottom row: only the seven of a major scale</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="0">C</text><text x="44" y="0">C♯</text><text x="88" y="0">D</text>
      <text x="132" y="0">D♯</text><text x="176" y="0">E</text><text x="220" y="0">F</text>
      <text x="264" y="0">F♯</text><text x="308" y="0">G</text><text x="352" y="0">G♯</text>
      <text x="396" y="0">A</text><text x="440" y="0">A♯</text><text x="484" y="0">B</text>
    </g>
    <g>
      <g fill="#5B7FA8" opacity=".18">
        <rect x="-20" y="10" width="40" height="30" rx="2"/>
        <rect x="24" y="10" width="40" height="30" rx="2"/>
        <rect x="68" y="10" width="40" height="30" rx="2"/>
        <rect x="112" y="10" width="40" height="30" rx="2"/>
        <rect x="156" y="10" width="40" height="30" rx="2"/>
        <rect x="200" y="10" width="40" height="30" rx="2"/>
        <rect x="244" y="10" width="40" height="30" rx="2"/>
        <rect x="288" y="10" width="40" height="30" rx="2"/>
        <rect x="332" y="10" width="40" height="30" rx="2"/>
        <rect x="376" y="10" width="40" height="30" rx="2"/>
        <rect x="420" y="10" width="40" height="30" rx="2"/>
        <rect x="464" y="10" width="40" height="30" rx="2"/>
      </g>
      <g fill="#E07A3F" opacity=".9">
        <rect x="-20" y="56" width="40" height="30" rx="2"/>
        <rect x="68" y="56" width="40" height="30" rx="2"/>
        <rect x="156" y="56" width="40" height="30" rx="2"/>
        <rect x="200" y="56" width="40" height="30" rx="2"/>
        <rect x="288" y="56" width="40" height="30" rx="2"/>
        <rect x="376" y="56" width="40" height="30" rx="2"/>
        <rect x="464" y="56" width="40" height="30" rx="2"/>
      </g>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="76">C</text><text x="88" y="76">D</text><text x="176" y="76">E</text>
      <text x="220" y="76">F</text><text x="308" y="76">G</text><text x="396" y="76">A</text>
      <text x="484" y="76">B</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="112">The five omitted semitones — C♯ D♯ F♯ G♯ A♯ — are not wrong notes, just outside this scale</text>
      <text x="0" y="134">Move one semitone and the pattern changes: major, minor and the modes part company</text>
    </g>
  </g>
</svg>
```

## Listen: walking a scale

A scale's character comes from **where the whole tones and semitones fall**. As you listen up, notice which
step feels shorter — that step defines the whole scale.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"C 大调音阶","label_en":"C major scale","hint":"点「上行」听半音落在哪里","hint_en":"Try Up and listen for where the semitones fall","gap":0.38}
```

## Common misconceptions

- **"A scale is the order of the notes."** Order is surface; the substance is the **interval pattern**.
- **"More scales means more skill."** One major scale plus a few modes covers most music. Quantity is not ability.
- **"Anything outside the scale is a wrong note."** Chromatic notes (see [[concept:chromatic|chromatic scale]]) are a standard colouring device; they simply belong to another set.
- **"The same scale in another key is just higher or lower."** The pattern is the same, but the absolute pitches, the notation and the instrument's feel all change.
:::
