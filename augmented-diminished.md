---
id: augmented-diminished
site: theo
cat: T2
title: 增音程与减音程
title_en: Augmented and Diminished Intervals
summary: 纯音程与大小音程再宽一个半音或窄一个半音的结果
summary_en: What a perfect or major interval becomes when widened or narrowed by one more semitone
level: standard
tags: [乐理, 音程, 变化音]
tags_en: [theory, interval, chromatic]
alias: [增四度, 减五度, 三全音, tritone]
order: 20
links:
  - "[[concept:interval]]"
  - "[[concept:perfect-interval]]"
  - "[[concept:major-minor-interval]]"
  - "[[concept:enharmonic]]"
  - "[[concept:consonance]]"
instances:
  - pdmx-002038 | 圣-桑《骷髅之舞》的钢琴谱：核心动机就架在增四度上，整曲的不安感由此而来 | Saint-Saëns' Danse macabre in piano score — the core motif is built on an augmented fourth, the source of the whole piece's unease
  - giantmidi-004040 | 李斯特把同一首改编成钢琴独奏，音程骨架没变，可对照听出增四度在不同织体里的同一张力 | Liszt's solo-piano transcription keeps the interval skeleton, so the same tritone tension can be compared across textures
  - pdmx-002199 | 同一作品的另一份谱面版本，用于核对"写的不同、听的一样"这类等音现象 | Another score edition of the same work, useful when checking the enharmonic case of different spellings that sound alike
sources:
  - 增/减音程的定义（在纯音程或大/小音程基础上再宽/窄一个半音），属乐理通则
  - 增四度与减五度音数相同（6 半音）、历史上有"音乐中的魔鬼"之称，为通行乐史记载
updated: 2026-09-23
---

::: zh
[[concept:perfect-interval|纯音程]]不分大小，[[concept:major-minor-interval|大小音程]]不能再叫"更大小"，
那还要更宽或更窄怎么办？用**增**与**减**：

| 起点 | ↔ | 变形 |
|---|---|---|
| 纯音程 | 宽一个半音 | **增**音程（增四度、增五度…） |
| 纯音程 | 窄一个半音 | **减**音程（减五度、减四度…） |
| 大音程 | 宽一个半音 | 增音程（增二度、增六度…） |
| 小音程 | 窄一个半音 | 减音程（减三度、减七度…） |

规则里有一条容易搞混：**大音程窄一个半音就变成小音程**，只有小音程再窄才叫减。
也就是说"减三度"不是把小三度改一改那么简单，它是一个真正罕见、听感接近大二度的音程。

## 三全音：一个名字，两种写法

6 个半音的位置最特殊：它既能写成**增四度**（C–F♯），也能写成**减五度**（C–G♭）。
两者**听感完全相同**，写法与倾向不同：

- 增四度向外扩张，倾向解决到五度或六度；
- 减五度向内收拢，倾向解决到三度。

在调性音乐里，这个音程是最强的推动力之一，也因此长期被称为"音乐中的魔鬼"。
关于"同音不同写法"的机制，见 [[concept:enharmonic|等音]]。

## 图示：同一个 6 半音，两种写法

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">键盘上同一段距离，谱面上可以是两种完全不同的写法</text>
  </g>

  <g transform="translate(40,50)">
    <g stroke="#343439">
      <rect x="0" y="0" width="34" height="66" rx="2" fill="#17171A"/>
      <rect x="80" y="0" width="34" height="66" rx="2" fill="#17171A"/>
      <rect x="120" y="0" width="34" height="66" rx="2" fill="#17171A"/>
      <rect x="160" y="0" width="34" height="66" rx="2" fill="#17171A"/>
      <rect x="200" y="0" width="34" height="66" rx="2" fill="#17171A"/>
    </g>
    <g fill="#070706" stroke="#343439">
      <rect x="42" y="0" width="22" height="42" rx="2"/>
      <rect x="102" y="0" width="22" height="42" rx="2"/>
      <rect x="142" y="0" width="22" height="42" rx="2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="17" y="80">C</text><text x="53" y="80">C♯</text><text x="97" y="80">D</text>
      <text x="137" y="80">D♯</text><text x="177" y="80">E</text><text x="217" y="80">F</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="17" y1="-10" x2="53" y2="-10"/>
      <line x1="17" y1="-14" x2="17" y2="-6"/><line x1="53" y1="-14" x2="53" y2="-6"/>
    </g>
    <text x="60" y="-12" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">C–C♯ 增一度：小二度宽一个半音</text>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="17" y1="102" x2="217" y2="102"/>
      <line x1="17" y1="98" x2="17" y2="106"/><line x1="217" y1="98" x2="217" y2="106"/>
    </g>
    <text x="60" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C–F♯ 增四度 = C–G♭ 减五度（都是 6 个半音）</text>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="290" y="0">写成增四度时向外扩张</text>
      <text x="290" y="22">写成减五度时向内收拢</text>
      <text x="290" y="44">听感相同，倾向相反</text>
    </g>
  </g>
</svg>
```

## 听一听：三全音

先听增四度，再把同一个距离听成减五度 —— 音高一样，写法不同，
这正是"名称属于记谱、音数属于听觉"最清楚的一次示范。

```audiolab
{"type":"interval","a":"C4","b":"F#4","label":"增四度 C–F♯（6 个半音）","label_en":"Augmented fourth C–F♯ (6 semitones)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"它与 C–G♭ 减五度的音数完全相同，只是写法与解决倾向不同。","hint2_en":"It has exactly the same size as the diminished fifth C–G♭ — only the spelling and the tendency differ."}
```

## 常见误解

- **「增四度和减五度是两个音程」** → 音数相同、听感相同，属于 [[concept:enharmonic|等音程]]；区别在写法与倾向。
- **「增减只是理论上的东西」** → 增四度是调性音乐推动力最强的音程之一，也是爵士与电影配乐里的常客。
- **「大音程窄一个半音就是减音程」** → 大音程窄一个半音先变成**小**音程，减音程要从小音程再窄一个半音。
- **「三全音听起来一定刺耳」** → 它的张力很强，但在恰当的和声里可以呈现为柔和而悬置的色彩，取决于上下文。
:::

::: en
[[concept:perfect-interval|Perfect intervals]] split into no major or minor, and
[[concept:major-minor-interval|major and minor intervals]] cannot become "more major". So how do we make an
interval wider or narrower still? With **augmented** and **diminished**:

| Starting point | → | Result |
|---|---|---|
| perfect | one semitone wider | **augmented** (augmented fourth, augmented fifth …) |
| perfect | one semitone narrower | **diminished** (diminished fifth, diminished fourth …) |
| major | one semitone wider | augmented (augmented second, augmented sixth …) |
| minor | one semitone narrower | diminished (diminished third, diminished seventh …) |

One easily confused point: **a major interval narrowed by a semitone becomes minor.** Only a minor interval
narrowed again becomes diminished. So a "diminished third" is not merely a squeezed minor third — it is a
genuinely rare interval that sounds close to a major second.

## The tritone: one sound, two spellings

The position six semitones up is the special case: it can be written as an **augmented fourth** (C–F♯) or as a
**diminished fifth** (C–G♭). Both sound identical, but they are spelled and they tend differently:

- the augmented fourth expands outward, resolving toward a fifth or sixth;
- the diminished fifth contracts inward, resolving toward a third.

In tonal music this interval is one of the strongest engines of motion, which is why it was long nicknamed
"the devil in music". The mechanism behind "same sound, different spelling" is covered under
[[concept:enharmonic|enharmonic]].

## Diagram: the same six semitones, two spellings

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One distance on the keyboard can carry two completely different spellings on the page</text>
  </g>

  <g transform="translate(40,50)">
    <g stroke="#343439">
      <rect x="0" y="0" width="34" height="66" rx="2" fill="#17171A"/>
      <rect x="80" y="0" width="34" height="66" rx="2" fill="#17171A"/>
      <rect x="120" y="0" width="34" height="66" rx="2" fill="#17171A"/>
      <rect x="160" y="0" width="34" height="66" rx="2" fill="#17171A"/>
      <rect x="200" y="0" width="34" height="66" rx="2" fill="#17171A"/>
    </g>
    <g fill="#070706" stroke="#343439">
      <rect x="42" y="0" width="22" height="42" rx="2"/>
      <rect x="102" y="0" width="22" height="42" rx="2"/>
      <rect x="142" y="0" width="22" height="42" rx="2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="17" y="80">C</text><text x="53" y="80">C♯</text><text x="97" y="80">D</text>
      <text x="137" y="80">D♯</text><text x="177" y="80">E</text><text x="217" y="80">F</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="17" y1="-10" x2="53" y2="-10"/>
      <line x1="17" y1="-14" x2="17" y2="-6"/><line x1="53" y1="-14" x2="53" y2="-6"/>
    </g>
    <text x="60" y="-12" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">C–C♯: an augmented unison — a minor second widened</text>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="17" y1="102" x2="217" y2="102"/>
      <line x1="17" y1="98" x2="17" y2="106"/><line x1="217" y1="98" x2="217" y2="106"/>
    </g>
    <text x="60" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C–F♯ augmented fourth = C–G♭ diminished fifth (6 semitones)</text>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="290" y="0">spelled augmented, it expands outward</text>
      <text x="290" y="22">spelled diminished, it contracts inward</text>
      <text x="290" y="44">same sound, opposite tendency</text>
    </g>
  </g>
</svg>
```

## Listen: the tritone

Hear the augmented fourth, then hear the very same distance as a diminished fifth. Same pitches, different
spelling — the clearest demonstration that names belong to notation while size belongs to hearing.

```audiolab
{"type":"interval","a":"C4","b":"F#4","label":"增四度 C–F♯（6 个半音）","label_en":"Augmented fourth C–F♯ (6 semitones)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"它与 C–G♭ 减五度的音数完全相同，只是写法与解决倾向不同。","hint2_en":"It has exactly the same size as the diminished fifth C–G♭ — only the spelling and the tendency differ."}
```

## Common misconceptions

- **"An augmented fourth and a diminished fifth are two different intervals."** Same size, same sound, and they belong together as [[concept:enharmonic|enharmonic intervals]]; the difference lives in spelling and tendency.
- **"Augmented and diminished are purely theoretical."** The tritone is one of the strongest engines in tonal music, and a staple of jazz and film scoring.
- **"A major interval narrowed a semitone is diminished."** Narrowing a major interval first yields a **minor** one; diminished requires one more semitone down from minor.
- **"A tritone always sounds harsh."** Its tension is strong, but in the right harmony it can read as a soft, suspended colour. Context decides.
:::
