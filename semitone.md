---
id: semitone
site: theo
cat: T2
title: 半音与全音
title_en: Semitone and Whole Tone
summary: 音数是音程的第二把尺子，量的是隔了几个半音
summary_en: Interval size is the second ruler — it measures how many semitones lie between two notes
level: core
tags: [乐理, 音程, 基础]
tags_en: [theory, interval, basics]
alias: [半音, 全音, 音数, semitone]
order: 14
links:
  - "[[concept:interval]]"
  - "[[concept:interval-number]]"
  - "[[concept:major-minor-interval]]"
  - "[[concept:note-name]]"
  - "[[concept:scale]]"
instances:
  - giantmidi-007791 | 《致爱丽丝》著名的开头：E 与 D♯ 之间只差半音，是最容易听出的最小步进 | The famous opening of Für Elise — E and D♯ are a semitone apart, the smallest step you can hear clearly
  - giantmidi-006222 | 音阶练习：E–F 与 B–C 两处半音紧跟在全音之后，同一串音里两种宽度直接对照 | Scale exercises — the E–F and B–C semitones follow whole tones directly, both widths side by side in one run
  - mutopia-000522 | 《欢乐颂》主题以全音级进为主，几乎不出现半音，适合先把"全音"听熟 | The Ode to Joy theme steps almost entirely in whole tones, the right place to learn that width first
sources:
  - 半音为最小音高单位、十二平均律下八度 = 12 半音，属乐理通则
  - 各音程的半音数表（一至八度）为通行表述，本文行文为原创
updated: 2026-09-23
---

::: zh
[[concept:interval-number|度数]]管"叫什么名字"，音数管"到底多宽"。两把尺子必须同时用：
度数只用 7 个字母去数，音数则在键盘上数半音。**同一个度数可以有不同音数**——
这句话的另一面就是：**同一个音数也可以落在不同度数上**。

## 半音是最小的一格

十二平均律把八度切成 12 份，每份就是一个**半音**；两个半音合成一个**全音**。
半音是这个体系里的最小刻度，没有比它更小的音名距离（差得更少的音只能靠演奏时的微调，不构成新音名）。

在键盘上数最直观：

| 起点 | 走一个半音 | 走一个全音 |
|---|---|---|
| C | C♯（黑键） | D |
| E | F（白键） | F♯ |
| B | C（白键） | C♯ |

注意 E → F 与 B → C **不需要黑键就已经是半音**。这一点决定了 [[concept:scale|音阶]] 的形状：
大调音阶之所以听起来"有大调味"，正是因为半音固定落在两个位置上。

## 音数表：度量音程的第二把尺子

| 音程 | 半音数 | 音程 | 半音数 |
|---|---|---|---|
| 纯一度 | 0 | 纯五度 | 7 |
| 小二度 | 1 | 小六度 | 8 |
| 大二度 | 2 | 大六度 | 9 |
| 小三度 | 3 | 小七度 | 10 |
| 大三度 | 4 | 大七度 | 11 |
| 纯四度 | 5 | 纯八度 | 12 |
| 增四度 / 减五度 | 6 | | |

这张表是练耳的底层依据：**听辨音程时，耳朵实际在比较的就是半音数**。
而纸面上的名字（大三度还是减四度）要回到度数才知道 —— 这也是
[[concept:enharmonic|等音]] 现象的来源：6 个半音既能叫增四度，也能叫减五度。

## 图示：半音藏在白键之间

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">两组白键之间天生就是半音，没有黑键可插</text>
  </g>

  <g transform="translate(60,56)">
    <g stroke="#343439">
      <rect x="0" y="0" width="40" height="80" rx="2" fill="#17171A"/>
      <rect x="62" y="0" width="40" height="80" rx="2" fill="#E07A3F" opacity=".22"/>
      <rect x="124" y="0" width="40" height="80" rx="2" fill="#17171A"/>
      <rect x="186" y="0" width="40" height="80" rx="2" fill="#17171A"/>
      <rect x="248" y="0" width="40" height="80" rx="2" fill="#17171A"/>
      <rect x="310" y="0" width="40" height="80" rx="2" fill="#5B7FA8" opacity=".22"/>
      <rect x="372" y="0" width="40" height="80" rx="2" fill="#17171A"/>
    </g>
    <g fill="#070706" stroke="#343439">
      <rect x="46" y="0" width="26" height="50" rx="2"/>
      <rect x="170" y="0" width="26" height="50" rx="2"/>
      <rect x="232" y="0" width="26" height="50" rx="2"/>
      <rect x="356" y="0" width="26" height="50" rx="2"/>
      <rect x="418" y="0" width="26" height="50" rx="2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="20" y="96">C</text><text x="82" y="96">D</text><text x="144" y="96">E</text>
      <text x="206" y="96">F</text><text x="268" y="96">G</text><text x="330" y="96">A</text>
      <text x="392" y="96">B</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="144" y1="-8" x2="206" y2="-8"/>
      <line x1="144" y1="-12" x2="144" y2="-4"/>
      <line x1="206" y1="-12" x2="206" y2="-4"/>
      <text x="150" y="-16" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">E–F 半音</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="20" y1="118" x2="82" y2="118"/>
      <line x1="20" y1="114" x2="20" y2="122"/>
      <line x1="82" y1="114" x2="82" y2="122"/>
      <text x="26" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C–D 全音</text>
    </g>
  </g>
</svg>
```

## 听一听：半音与全音

先听小二度（最窄），再听大二度（全音），最后听纯一度作对照 ——
三个音程的差别只在几十赫兹之间，却是整套乐理最底层的分界。

```audiolab
{"type":"interval","a":"E4","b":"F4","label":"小二度 E–F（1 个半音）","label_en":"Minor second E–F (1 semitone)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 G4 就是大二度（2 个半音）；换成 E4 则是纯一度（0 个半音）。","hint2_en":"Set b to G4 for a major second (2 semitones); set b to E4 for a perfect unison (0)."}
```

## 常见误解

- **「半音就是黑键到白键」** → E–F、B–C 是白键到白键，同样是半音。黑键只是"造出来的"音名，与宽度无关。
- **「音数相同就是同一个音程」** → 6 个半音可以是增四度，也可以是减五度。音数一样，写法与功能不同。
- **「全音比半音宽一倍，所以听起来远一倍」** → 听感不是线性倍数关系。全音与半音在听感上的差别远小于它们的比值。
- **「半音是音高差别的最小可能」** → 半音是最小的**音名距离**。演奏上还能差得更小，只是那些高度没有独立音名。
:::

::: en
[[concept:interval-number|Degree]] decides what an interval is *called*; interval size decides how *wide* it
actually is. Both rulers are needed at once: degree counts across seven letters, size counts semitones on a
keyboard. **One degree can have different sizes** — and the flip side is that **one size can land on different
degrees.**

## The semitone is the smallest step

Twelve-tone equal temperament cuts the octave into 12 equal parts; one part is a **semitone**, and two semitones
make a **whole tone**. The semitone is the smallest unit in the system — nothing smaller gets its own note name
(players can bend a pitch by less, but that is intonation, not a new name).

The keyboard makes it obvious:

| Start | One semitone up | One whole tone up |
|---|---|---|
| C | C♯ (black key) | D |
| E | F (white key) | F♯ |
| B | C (white key) | C♯ |

Note that E → F and B → C are semitones **without any black key**. This single fact shapes the
[[concept:scale|scale]]: a major scale sounds like a major scale because its two semitones always fall in the
same two places.

## The size table: the second ruler

| Interval | Semitones | Interval | Semitones |
|---|---|---|---|
| perfect unison | 0 | perfect fifth | 7 |
| minor second | 1 | minor sixth | 8 |
| major second | 2 | major sixth | 9 |
| minor third | 3 | minor seventh | 10 |
| major third | 4 | major seventh | 11 |
| perfect fourth | 5 | perfect octave | 12 |
| augmented fourth / diminished fifth | 6 | | |

This table is what ear training actually runs on: **when you identify an interval, the ear is comparing
semitones.** The written name (major third or diminished fourth) still needs the degree to settle — which is
exactly where [[concept:enharmonic|enharmonic]] equivalents come from: 6 semitones can be written as an
augmented fourth or a diminished fifth.

## Diagram: where semitones hide between white keys

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Two pairs of white keys are already a semitone apart — no black key fits between them</text>
  </g>

  <g transform="translate(60,56)">
    <g stroke="#343439">
      <rect x="0" y="0" width="40" height="80" rx="2" fill="#17171A"/>
      <rect x="62" y="0" width="40" height="80" rx="2" fill="#E07A3F" opacity=".22"/>
      <rect x="124" y="0" width="40" height="80" rx="2" fill="#17171A"/>
      <rect x="186" y="0" width="40" height="80" rx="2" fill="#17171A"/>
      <rect x="248" y="0" width="40" height="80" rx="2" fill="#17171A"/>
      <rect x="310" y="0" width="40" height="80" rx="2" fill="#5B7FA8" opacity=".22"/>
      <rect x="372" y="0" width="40" height="80" rx="2" fill="#17171A"/>
    </g>
    <g fill="#070706" stroke="#343439">
      <rect x="46" y="0" width="26" height="50" rx="2"/>
      <rect x="170" y="0" width="26" height="50" rx="2"/>
      <rect x="232" y="0" width="26" height="50" rx="2"/>
      <rect x="356" y="0" width="26" height="50" rx="2"/>
      <rect x="418" y="0" width="26" height="50" rx="2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="20" y="96">C</text><text x="82" y="96">D</text><text x="144" y="96">E</text>
      <text x="206" y="96">F</text><text x="268" y="96">G</text><text x="330" y="96">A</text>
      <text x="392" y="96">B</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="144" y1="-8" x2="206" y2="-8"/>
      <line x1="144" y1="-12" x2="144" y2="-4"/>
      <line x1="206" y1="-12" x2="206" y2="-4"/>
      <text x="150" y="-16" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">E–F, a semitone</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="20" y1="118" x2="82" y2="118"/>
      <line x1="20" y1="114" x2="20" y2="122"/>
      <line x1="82" y1="114" x2="82" y2="122"/>
      <text x="26" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C–D, a whole tone</text>
    </g>
  </g>
</svg>
```

## Listen: semitone against whole tone

Hear the minor second (the narrowest), then the major second, then a perfect unison as a control. The
difference is only a few tens of hertz, yet it is the deepest dividing line in music theory.

```audiolab
{"type":"interval","a":"E4","b":"F4","label":"小二度 E–F（1 个半音）","label_en":"Minor second E–F (1 semitone)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 G4 就是大二度（2 个半音）；换成 E4 则是纯一度（0 个半音）。","hint2_en":"Set b to G4 for a major second (2 semitones); set b to E4 for a perfect unison (0)."}
```

## Common misconceptions

- **"A semitone means black key to white key."** E–F and B–C are white to white and are still semitones. Black keys are invented names, not a definition of width.
- **"Same number of semitones means the same interval."** 6 semitones can be an augmented fourth or a diminished fifth — same width, different spelling and function.
- **"A whole tone is twice as far, so it sounds twice as far."** Perception is not a linear multiple; the heard gap between them is far smaller than the ratio suggests.
- **"A semitone is the smallest possible pitch difference."** It is the smallest difference **between note names**. Players can deviate by less, but those heights have no names of their own.
:::
