---
id: enharmonic
site: theo
cat: T2
title: 等音
title_en: Enharmonic
summary: 同一个键位可以有不同写法，写法不同则功能与方向不同
summary_en: One key can carry several spellings — and the spelling, not the sound, carries the function
level: standard
tags: [乐理, 音程, 记谱]
tags_en: [theory, interval, notation]
alias: [等音程, 同音异名, enharmonic]
order: 28
links:
  - "[[concept:interval]]"
  - "[[concept:note-name]]"
  - "[[concept:augmented-diminished]]"
  - "[[concept:key-signature]]"
  - "[[concept:modulation]]"
instances:
  - atepp-003869 | 月光奏鸣曲第一乐章：全曲记在升号调上，同一批键位换成降号写法就是另一个调名 | The first movement of the Moonlight Sonata is notated with sharps; the very same keys respelled with flats would name a different key
  - atepp-000195 | 德彪西《月光》记在降号调上，与上一条互为等音调——键位相同、调名不同 | Debussy's Clair de lune is notated with flats and is enharmonically equivalent to the example above — same keys, different key name
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：同一个六半音音程，在不同位置被写成增四度或减五度 | Liszt's transcription of Danse macabre — the same six-semitone interval spelled as an augmented fourth or a diminished fifth depending on the spot
sources:
  - 等音（同音异名）与重升重降记号的用法，属乐理通则
  - 十二平均律下等音键位重合、而弦乐管乐对等音仍有音高差别，为音乐声学通行表述
updated: 2026-09-23
---

::: zh
保持音高不变、只换一个写法，就叫**等音**（同音异名）。C♯ 与 D♭ 在键盘上是同一个键，
但它们在乐理上不是同一件事。

## 为什么不能只留一种写法

因为在记谱体系里，**字母名承载着功能**：

| 写法 | 从哪来 | 往哪去 |
|---|---|---|
| C♯ | 升号：向上的运动 | 常作为 D 的导音 |
| D♭ | 降号：向下的运动 | 常作为 C 的邻音或下属方向的音 |

同一个键位，写成 C♯ 时读者知道它要上行，写成 D♭ 时读者知道它来自上方。
把两者合并成一种写法，这些方向信息就全丢了。这也是 [[concept:modulation|转调]] 记谱必须严格的原因。

## 三种常见的等音现象

1. **单音**：C♯ = D♭，E♯ = F，C♭ = B。还有重升（C𝄪）与重降（D𝄫），极端调性里才会出现。
2. **音程**：增四度 = 减五度（6 个半音），见 [[concept:augmented-diminished|增程与减程]]。
3. **调**：C♯ 大调 = D♭ 大调。调号不同（7 升 vs 5 降），键位相同。

## 平均律的"抹平"是有代价的

十二平均律把每个半音切成等份，等音才在键位上完全重合。换成别的律制，
C♯ 与 D♭ 会有实际音高差（这也是弦乐与管乐演奏者会对等音敏感、而钢琴不必的原因）。
换句话说：**等音是平均律的产物**，不是自然的必然。

## 图示：同键位，两种写法

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">一个黑键可以有两个名字；写法决定它"从哪来、往哪去"</text>
  </g>

  <g transform="translate(52,54)">
    <g stroke="#343439">
      <rect x="0" y="0" width="70" height="78" rx="2" fill="#17171A"/>
      <rect x="80" y="0" width="70" height="78" rx="2" fill="#17171A"/>
      <rect x="160" y="0" width="70" height="78" rx="2" fill="#17171A"/>
    </g>
    <g fill="#070706" stroke="#343439">
      <rect x="48" y="0" width="34" height="48" rx="2"/>
      <rect x="128" y="0" width="34" height="48" rx="2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="35" y="94">C</text><text x="115" y="94">D</text><text x="195" y="94">E</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">
      <text x="65" y="-12">C♯／D♭ 同一个键</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="120">写成 C♯：调性记在升号一侧，倾向向上解决</text>
      <text x="0" y="140">写成 D♭：调性记在降号一侧，倾向向下进行</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="65" y1="-8" x2="65" y2="-2"/>
      <line x1="145" y1="-8" x2="145" y2="-2" stroke="#5B7FA8"/>
    </g>
    <text x="152" y="-12" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">E♯／F 也互为等音</text>
  </g>
</svg>
```

## 听一听：听不出差别，正是要点

在平均律乐器上，下面两对音高完全相同 —— 这恰恰说明"等音"是**记谱与功能的区分**，
不是听觉的区分。听的时候，请把注意力放在"这一对音在谱面上会怎么走向"。

```audiolab
{"type":"interval","a":"C4","b":"C#4","label":"C–C♯（写成升号）","label_en":"C–C♯ (spelled with a sharp)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D♭4 —— 同样的键位、不同的名字：这是记谱的差别，不是音高的差别。","hint2_en":"Set b to D♭4 — the same key, a different name: a notational difference, not a pitch difference."}
```

## 常见误解

- **「等音就是同一个音」** → 键位相同，名字、功能、走向都不同。记谱上它们是两个音。
- **「重升重降是印刷错误」** → 是合法记号，出现在升号很多的调里（如 G♯ 小调需要 F𝄪）。
- **「所有乐器上等音都完全一样」** → 只在十二平均律下如此。弦乐与管乐可以根据倾向微调音高。
- **「既然一样，写作时随便选」** → 选错会破坏调性逻辑。调号、倾向音、和声功能都要一致。
:::

::: en
Keeping the pitch and changing only the spelling gives an **enharmonic** equivalent. C♯ and D♭ are the same
key on a keyboard, yet in music theory they are not the same thing.

## Why a single spelling will not do

Because in notation the **letter name carries function**:

| Spelling | Where it comes from | Where it goes |
|---|---|---|
| C♯ | a sharp: motion upward | typically a leading tone to D |
| D♭ | a flat: motion downward | typically a neighbour of C, or heading toward the subdominant |

Same key, but read C♯ the player knows it rises; read D♭ the player knows it came from above. Collapse the two
spellings and all that directional information vanishes — which is why notation for
[[concept:modulation|modulation]] has to be strict.

## Three common cases

1. **Single notes**: C♯ = D♭, E♯ = F, C♭ = B. Double sharps (C𝄪) and double flats (D𝄫) appear only in extreme keys.
2. **Intervals**: an augmented fourth equals a diminished fifth (6 semitones) — see
   [[concept:augmented-diminished|augmented and diminished]].
3. **Keys**: C♯ major equals D♭ major. Different key signatures (seven sharps versus five flats), the same keys.

## What equal temperament flattens away

Twelve-tone equal temperament cuts every semitone into equal parts, and only then do enharmonic spellings
coincide exactly. Under other tuning systems C♯ and D♭ really do differ in pitch — which is why string and wind
players stay sensitive to enharmonic spelling while pianists need not. In short: **enharmonic equivalence is a
product of equal temperament**, not a law of nature.

## Diagram: one key, two names

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One black key can carry two names; the spelling says where it comes from and where it goes</text>
  </g>

  <g transform="translate(52,54)">
    <g stroke="#343439">
      <rect x="0" y="0" width="70" height="78" rx="2" fill="#17171A"/>
      <rect x="80" y="0" width="70" height="78" rx="2" fill="#17171A"/>
      <rect x="160" y="0" width="70" height="78" rx="2" fill="#17171A"/>
    </g>
    <g fill="#070706" stroke="#343439">
      <rect x="48" y="0" width="34" height="48" rx="2"/>
      <rect x="128" y="0" width="34" height="48" rx="2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="35" y="94">C</text><text x="115" y="94">D</text><text x="195" y="94">E</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">
      <text x="65" y="-12">C♯ / D♭, one key</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="120">Spelled C♯: the key sits on the sharp side and tends upward</text>
      <text x="0" y="140">Spelled D♭: the key sits on the flat side and tends downward</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="65" y1="-8" x2="65" y2="-2"/>
      <line x1="145" y1="-8" x2="145" y2="-2" stroke="#5B7FA8"/>
    </g>
    <text x="152" y="-12" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">E♯ / F are enharmonic too</text>
  </g>
</svg>
```

## Listen: no difference in sound — that is the point

On an equal-tempered instrument the two pairs below sound identical. That is exactly the lesson: enharmonic
equivalence is a distinction of **notation and function**, not of hearing. As you listen, think about how each
spelling would move next on the page.

```audiolab
{"type":"interval","a":"C4","b":"C#4","label":"C–C♯（写成升号）","label_en":"C–C♯ (spelled with a sharp)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D♭4 —— 同样的键位、不同的名字：这是记谱的差别，不是音高的差别。","hint2_en":"Set b to D♭4 — the same key, a different name: a notational difference, not a pitch difference."}
```

## Common misconceptions

- **"Enharmonic means the same note."** The key is the same; the name, function and tendency are not. In notation they are two notes.
- **"Double sharps and flats are printing errors."** They are legal accidentals, needed in keys with many sharps (G♯ minor requires F𝄪).
- **"Every instrument treats them as identical."** Only under twelve-tone equal temperament. Strings and winds can shade the pitch toward its tendency.
- **"Since they sound alike, pick either."** The wrong choice breaks the tonal logic: key signature, tendency tone and harmonic function must all agree.
:::
