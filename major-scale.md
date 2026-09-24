---
id: major-scale
site: theo
cat: T3
title: 大调音阶
title_en: Major Scale
summary: 全全半全全全半——七个音、两个半音位置，西方调性音乐的默认底子
summary_en: Whole, whole, half, whole, whole, whole, half — seven notes and two semitone gaps, the default ground of tonal music
level: core
tags: [乐理, 音阶, 基础]
tags_en: [theory, scale, basics]
alias: [大调, major scale, 全全半全全全半]
order: 12
links:
  - "[[concept:scale]]"
  - "[[concept:minor-scale]]"
  - "[[concept:semitone]]"
  - "[[concept:key-signature]]"
  - "[[concept:circle-of-fifths]]"
  - "[[concept:triad]]"
instances:
  - giantmidi-006222 | 音阶与琶音练习：把大调音阶按最慢的速度走完，全音半音的位置一清二楚 | Scale and arpeggio exercises walk the major scale at its slowest — every whole tone and semitone is plain to hear
  - mutopia-000522 | 《欢乐颂》主题几乎只用大调音阶的级进，是"大调听着是什么样"的最短样本 | The Ode to Joy theme is almost pure major-scale steps — the shortest sample of how major sounds
  - pdmx-000607 | 《小星星变奏曲》主题：整条主题全在大调音阶内，变奏每一次都在同一套音上换装 | The theme of the Ah vous variations stays entirely inside one major scale, and every variation re-dresses the same notes
sources:
  - 大调音阶的音程结构（全全半全全全半）与调号推导规则，属乐理通则
  - 大调音阶共 15 个调号写法（含等音调）为通行表述
updated: 2026-09-23
---

::: zh
大调音阶是西方调性音乐用得最多的一条音阶，结构只有一句话：

> **全 — 全 — 半 — 全 — 全 — 全 — 半**

七个音，两个半音分别落在**第 3–4 音**与**第 7–8 音**之间。这两个位置就是大调性格的全部来源：
第 3 音与主音之间是大三度（明亮），第 7 音与主音之间是小二度（强烈倾向主音，也就是导音）。

| 级数 | 名称 | 与主音的音程 |
|---|---|---|
| 1 | 主音 | — |
| 2 | 上主音 | 大二度 |
| 3 | 中音 | **大三度**（大调之所以"大"） |
| 4 | 下属音 | 纯四度 |
| 5 | 属音 | 纯五度 |
| 6 | 下中音 | 大六度 |
| 7 | 导音 | **大七度**（强烈要求回到主音） |

## 为什么全世界的入门教材都从它开始

因为它**自带调号推导规则**：纯五度往上走，升号依次增加；纯五度往下走，降号依次增加。
升号顺序永远是 F–C–G–D–A–E–B，降号顺序正好反过来。这套规则就是
[[concept:circle-of-fifths|五度圈]]，也是 [[concept:key-signature|调号]] 的来历。

## 大调不是"快乐的音阶"

"大调=快乐、小调=悲伤"这个说法流传很广，但只在下半句对。
大调的真正特点不是情绪，而是**稳定性**：三级为大三度，主和弦是大三和弦，
属音与导音形成最强的回到主音的引力。这个结构既可以写进行曲，也可以写哀歌。

## 图示：两个半音的位置

```svg
<svg viewBox="0 0 640 214" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">七步之中只有两步是半音，它们的位置决定了大调的味道</text>
  </g>

  <g transform="translate(40,58)">
    <g stroke="#343439">
      <line x1="0" y1="46" x2="512" y2="46" stroke-width="1.2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="30">C</text><text x="64" y="30">D</text><text x="148" y="30">E</text>
      <text x="192" y="30">F</text><text x="256" y="30">G</text><text x="320" y="30">A</text>
      <text x="404" y="30">B</text><text x="448" y="30">C</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="32" y="66">全</text><text x="106" y="66">全</text><text x="170" y="66">半</text>
      <text x="224" y="66">全</text><text x="288" y="66">全</text><text x="362" y="66">全</text>
      <text x="426" y="66">半</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="148" y1="14" x2="192" y2="14"/>
      <line x1="148" y1="10" x2="148" y2="18"/><line x1="192" y1="10" x2="192" y2="18"/>
      <line x1="404" y1="14" x2="448" y2="14"/>
      <line x1="404" y1="10" x2="404" y2="18"/><line x1="448" y1="10" x2="448" y2="18"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      <text x="150" y="4">3–4 半音</text><text x="406" y="4">7–8 半音</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="92" x2="148" y2="92"/>
      <line x1="0" y1="88" x2="0" y2="96"/><line x1="148" y1="88" x2="148" y2="96"/>
      <line x1="0" y1="112" x2="448" y2="112"/>
      <line x1="0" y1="108" x2="0" y2="116"/><line x1="448" y1="108" x2="448" y2="116"/>
    </g>
    <text x="158" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">主音到中音：大三度 → 大调的"大"</text>
    <text x="458" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">主音到八度</text>
  </g>
</svg>
```

## 听一听：大调音阶的"两处半音"

先把上行听完，再点「下行」——半音那两步在下行时会被听得更清楚，
因为它们在往下走时正是"要到家"和"刚离家"的两个位置。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"C 大调音阶（全全半全全全半）","label_en":"C major scale (W W H W W W H)","hint":"上行 / 下行 / 一起响","hint_en":"Up, down, or all together","gap":0.36}
```

```notation
{"clef":"treble","notes":["C4","D4","E4","F4","G4","A4","B4","C5:w"],"caption":"C 大调音阶：第 3–4 音与第 7–8 音之间是半音","caption_en":"C major scale — semitones between steps 3–4 and 7–8"}
```

## 常见误解

- **「大调就是开心的音乐」** → 大调提供的是**稳定与引力**，情绪由节奏、和声、速度共同决定。
- **「大调音阶有 12 条，因为半音有 12 个」** → 大调音阶只有一种结构，但可以从 12 个音上起，而且两端还要用等音调记法补齐（C♯ 大调 / D♭ 大调是同一个音高）。
- **「半音都在第 3–4 和第 7–8 音之间，是因为这两个间隔更小」** → 顺序反了。音阶定义在前，半音位置是这条定义的结果，不是原因。
- **「大调音阶里不能出现变化音」** → 可以。比如把第 6 音降低，就得到旋律小调的下行形态或民间音乐的混合色彩。
:::

::: en
The major scale is the most used scale in Western tonal music, and its structure is one sentence:

> **whole — whole — half — whole — whole — whole — half**

Seven notes, with the two semitones falling between **steps 3–4** and **steps 7–8**. Those two places are the
entire source of the major sound: a major third above the tonic (bright), and a minor second below it (a strong
pull back home — the leading tone).

| Degree | Name | Interval above the tonic |
|---|---|---|
| 1 | tonic | — |
| 2 | supertonic | major second |
| 3 | mediant | **major third** (why major is "major") |
| 4 | subdominant | perfect fourth |
| 5 | dominant | perfect fifth |
| 6 | submediant | major sixth |
| 7 | leading tone | **major seventh** (demands a return) |

## Why every beginner book starts here

Because the scale **carries its own key-signature rule**: go up in perfect fifths and sharps accumulate; go down
in fifths and flats accumulate. The order of sharps is always F–C–G–D–A–E–B, and the order of flats is exactly
the reverse. That rule is the [[concept:circle-of-fifths|circle of fifths]], and it is where
[[concept:key-signature|key signatures]] come from.

## Major does not mean "happy"

The popular saying — major happy, minor sad — is only half true. What major actually supplies is **stability**:
a major third, a major tonic triad, and a dominant and leading tone that pull hard toward home. The same
structure writes marches and writes laments.

## Diagram: where the two semitones sit

```svg
<svg viewBox="0 0 640 214" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Only two of the seven steps are semitones; where they fall defines the major sound</text>
  </g>

  <g transform="translate(40,58)">
    <g stroke="#343439">
      <line x1="0" y1="46" x2="512" y2="46" stroke-width="1.2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="30">C</text><text x="64" y="30">D</text><text x="148" y="30">E</text>
      <text x="192" y="30">F</text><text x="256" y="30">G</text><text x="320" y="30">A</text>
      <text x="404" y="30">B</text><text x="448" y="30">C</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="32" y="66">W</text><text x="106" y="66">W</text><text x="170" y="66">H</text>
      <text x="224" y="66">W</text><text x="288" y="66">W</text><text x="362" y="66">W</text>
      <text x="426" y="66">H</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="148" y1="14" x2="192" y2="14"/>
      <line x1="148" y1="10" x2="148" y2="18"/><line x1="192" y1="10" x2="192" y2="18"/>
      <line x1="404" y1="14" x2="448" y2="14"/>
      <line x1="404" y1="10" x2="404" y2="18"/><line x1="448" y1="10" x2="448" y2="18"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      <text x="150" y="4">3–4 semitone</text><text x="406" y="4">7–8 semitone</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="92" x2="148" y2="92"/>
      <line x1="0" y1="88" x2="0" y2="96"/><line x1="148" y1="88" x2="148" y2="96"/>
      <line x1="0" y1="112" x2="448" y2="112"/>
      <line x1="0" y1="108" x2="0" y2="116"/><line x1="448" y1="108" x2="448" y2="116"/>
    </g>
    <text x="158" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">tonic to mediant: a major third — the "major" in major</text>
    <text x="458" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">tonic to octave</text>
  </g>
</svg>
```

## Listen: the two semitones

Hear it ascending, then press Down — the semitones stand out even more on the way down, because descending they
are exactly the step that arrives home and the step that just left it.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"C 大调音阶（全全半全全全半）","label_en":"C major scale (W W H W W W H)","hint":"上行 / 下行 / 一起响","hint_en":"Up, down, or all together","gap":0.36}
```

```notation
{"clef":"treble","notes":["C4","D4","E4","F4","G4","A4","B4","C5:w"],"caption":"C 大调音阶：第 3–4 音与第 7–8 音之间是半音","caption_en":"C major scale — semitones between steps 3–4 and 7–8"}
```

## Common misconceptions

- **"Major means happy music."** Major supplies **stability and pull**; mood comes from rhythm, harmony and tempo together.
- **"There are twelve major scales because there are twelve semitones."** There is one major pattern, startable on twelve pitches — and the extremes need enharmonic spelling (C♯ major and D♭ major are the same pitches).
- **"The semitones sit at 3–4 and 7–8 because those gaps are smaller."** That reverses cause and effect: the scale is defined first, and the semitone positions are its consequence.
- **"No accidentals can appear in a major scale."** They can. Lower the sixth degree and you get the descending form of melodic minor, or a folk-inflected colour.
:::
