---
id: whole-tone
site: theo
cat: T3
title: 全音音阶
title_en: Whole Tone Scale
summary: 全是全音、没有半音、只有六个音——因而没有主音
summary_en: All whole tones, no semitones, six notes — and therefore no tonic
level: standard
tags: [乐理, 音阶, 人工音阶]
tags_en: [theory, scale, artificial]
alias: [全音阶, whole tone scale]
order: 44
links:
  - "[[concept:scale]]"
  - "[[concept:octatonic]]"
  - "[[concept:consonance]]"
  - "[[concept:perfect-interval]]"
instances:
  - maestro-000306 | 德彪西《前奏曲》第一册中的《帆》：全音音阶最常被引用的教科书例子 | Debussy's Voiles from the first book of Preludes — the textbook example of the whole-tone scale
  - atepp-000195 | 同为德彪西的作品，可对照他在同一时期使用的其他和声语汇 | Another Debussy work, for comparing the harmonic vocabulary he used in the same period
  - giantmidi-006222 | 音阶练习可按需弹出全音音阶，用于把六个等距的音听一遍 | Scale exercises play the whole-tone scale directly — hear the six equally spaced steps
sources:
  - 全音音阶由六个全音构成、八度被等分为六份，属乐理通则
  - 全音音阶在印象派（尤其德彪西）中的使用，为音乐史通行记载
updated: 2026-09-23
---

::: zh
全音音阶的结构一句话说清：**一个八度里只放六个音，相邻两个音全是全音**。

> C 全音音阶：C D E F♯ G♯ A♯ C

它有两个立刻能听出来的后果：

1. **没有半音** → 没有导音，也没有任何"要靠向哪里"的方向感。
   所有音程都一样宽，听觉上一片模糊、悬浮。
2. **只有两个调** → 从 C 起和从 C♯ 起各得到一条，再往上就重复了。
   12 个半音 ÷ 2 = 6 个音，所以全音音阶**只有两条**（互为倒影关系）。

## 为什么它"没有主音"

调性靠的是**音与音之间的不等距**：半音造成引力，全音造成稳定，两者交替才有中心。
全音音阶把距离完全抹平，主音就失去立足点 —— 任何一个音都可以是起点，也都不是终点。

这也解释了它为什么是印象派的常用工具：**要的正是"没有方向"的那种漂浮感**。

## 图示：等距的六份

```svg
<svg viewBox="0 0 640 168" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">八度被六等分：每两步之间都是全音，找不到半音的引力点</text>
  </g>

  <g transform="translate(40,56)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">D</text><text x="160" y="0">E</text>
      <text x="240" y="0">F♯</text><text x="320" y="0">G♯</text><text x="400" y="0">A♯</text>
      <text x="480" y="0">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="16" x2="480" y2="16"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">
      <text x="40" y="30">全音</text><text x="120" y="30">全音</text><text x="200" y="30">全音</text>
      <text x="280" y="30">全音</text><text x="360" y="30">全音</text><text x="440" y="30">全音</text>
    </g>
    <text x="0" y="58" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      对照：大调音阶在同一跨度里放了七个音，且有两处半音 —— 那就是调性的来源
    </text>
    <text x="0" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      只有两条：从 C 起一条，从 C♯ 起一条。其余起点都是这两条的重复
    </text>
  </g>
</svg>
```

## 听一听：等距六音

听的时候试着找主音 —— 你会发现找不到。这种"无归属"正是它的用途。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F#4","G#4","A#4","C5"],"label":"C 全音音阶","label_en":"C whole-tone scale","hint":"点「上行」听每一步都同样宽","hint_en":"Try Up — every step is exactly the same width","gap":0.40}
```

## 常见误解

- **「全音音阶有十二个调」** → 只有两条（互为倒影），因为六个音把八度等分了。
- **「它可以当普通音阶用」** → 它缺少调性所需的不等距结构，因此难以承载属—主关系，通常作色彩用。
- **「它是德彪西发明的」** → 更早已有理论记载与零星使用；德彪西使其成为标志性语汇。
- **「没有半音就意味着协和」** → 恰恰相反。全音音阶里的增四度关系随处可见，张力反而持续存在。
:::

::: en
The whole-tone scale in one line: **six notes to the octave, every step a whole tone.**

> C whole tone: C D E F♯ G♯ A♯ C

Two immediate consequences:

1. **No semitones** → no leading tone, and no sense of "leaning" in any direction. Every interval is the same
   width, so the ear hears something blurred and suspended.
2. **Only two keys** → one starting on C, one starting on C♯; beyond that it repeats. Twelve semitones divided
   into steps of two gives six notes, so there are **only two** whole-tone scales, mirror images of each other.

## Why it has no tonic

Tonality depends on **unequal distances**: semitones create pull, whole tones create stability, and their
alternation produces a centre. Flatten every distance and the tonic loses its footing — any note can be a start,
and none is an end.

That is exactly why Impressionism reached for it: **the point is the drifting, directionless quality.**

## Diagram: six equal parts

```svg
<svg viewBox="0 0 640 168" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The octave divided into six: every step is a whole tone, with no semitone to pull toward</text>
  </g>

  <g transform="translate(40,56)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">D</text><text x="160" y="0">E</text>
      <text x="240" y="0">F♯</text><text x="320" y="0">G♯</text><text x="400" y="0">A♯</text>
      <text x="480" y="0">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="16" x2="480" y2="16"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">
      <text x="40" y="30">W</text><text x="120" y="30">W</text><text x="200" y="30">W</text>
      <text x="280" y="30">W</text><text x="360" y="30">W</text><text x="440" y="30">W</text>
    </g>
    <text x="0" y="58" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Compare: a major scale fits seven notes into the same span, with two semitones — that is where tonality comes from
    </text>
    <text x="0" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Only two exist: one from C, one from C♯. Any other start merely repeats them
    </text>
  </g>
</svg>
```

## Listen: six equal steps

As you listen, try to find the tonic — you will not. That homelessness is precisely its use.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F#4","G#4","A#4","C5"],"label":"C 全音音阶","label_en":"C whole-tone scale","hint":"点「上行」听每一步都同样宽","hint_en":"Try Up — every step is exactly the same width","gap":0.40}
```

## Common misconceptions

- **"There are twelve whole-tone scales."** Only two (mirror images), because six notes divide the octave equally.
- **"It can serve as an ordinary scale."** It lacks the unequal structure tonality needs, so dominant-to-tonic relations are hard to build; it is usually a colouring device.
- **"Debussy invented it."** Earlier theory and scattered use exist; Debussy made it a signature vocabulary.
- **"No semitones means no tension."** The opposite: tritone relationships are everywhere in it, so tension is constant.
:::
