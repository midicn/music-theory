---
id: non-chord-tone
site: theo
cat: T4
title: 和弦外音
title_en: Non-Chord Tone
summary: 不属于当前和弦的音——旋律与和声因此不再一一对应
summary_en: A note outside the current chord — which lets melody and harmony stop being one-to-one
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [和弦外音, 经过音, 辅助音, 倚音, non-chord tone]
order: 44
links:
  - "[[concept:chord]]"
  - "[[concept:melody]]"
  - "[[concept:suspended-chord]]"
  - "[[concept:consonance]]"
  - "[[concept:counterpoint]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：旋律里大量出现不属于当下和弦的经过音，是"外音"最常见的形态 | The Ode to Joy theme is full of passing notes foreign to the prevailing chord — the commonest form of non-chord tone
  - mutopia-000049 | 《绿袖子》加固定低音：旋律线与低音的和声不完全重合，倚音在其中很清楚 | Greensleeves to a Ground — the melody does not align exactly with the bass harmony, and its appoggiaturas stand out
  - giantmidi-006222 | 音阶与琶音练习 — 级进走法天然产生经过音，可与纯和弦音走法对照 | Scale and arpeggio exercises — stepwise motion generates passing notes naturally, comparable with chord-tone-only motion
sources:
  - 和弦外音指不属于当前和声的旋律音，常见类型（经过音、辅助音、倚音、延留音、先现音、 Escape tone）为通行和声学表述
  - 外音须按惯例解决、且通常出现在弱拍或短时值上，属对位与和声写作通则
updated: 2026-09-24
---

::: zh
如果旋律的每个音都必须属于当下的和弦，音乐很快就变成"拨和弦"。
**和弦外音就是打破这个限制的东西**：它是不属于当前和弦的音，出现在旋律里（或内声部里），
按惯例在短时间内解决掉。

> 它让**旋律**与**和声**变成两条可以不完全重合的线 —— 这是复调思维的基础。

## 常见的几种

| 名称 | 出现方式 | 例（和弦 C–E–G） |
|---|---|---|
| **经过音** | 两个和弦音之间的级进填充 | C–**D**–E |
| **辅助音** | 离开和弦音又回到同一个音 | E–**F**–E |
| **倚音** | 强拍上的外音，随后级进解决 | **F** → E（强拍起） |
| **延留音** | 前一和弦的音被"留"住，随后解决 | 见 [[concept:suspended-chord|挂留和弦]] |
| **先现音** | 提前出现下一个和弦的音 | C–E–G 上出现 **A**（预示下一个和弦） |
| **逃逸音** | 级进进入、跳进离去 | C–**D** → B |

## 三条判断惯例

1. **时值短**：外音通常比它两侧的和弦音更短；
2. **落在弱拍**（倚音与延留音除外）：强拍外音需要明确解决，写作上要更小心；
3. **级进进入、级进离去**：跳进处理外音会让它听起来像和弦音，破坏区分。

## 为什么它重要

| 作用 | 说明 |
|---|---|
| **让旋律自由** | 旋律不必被和弦"锁死"，可以级进、可以有独立的呼吸 |
| **制造局部张力** | 外音与和弦音相撞，形成短促的不协和，随即释放 |
| **连接和声** | 先现音可以预示下一个和弦，让进行更连贯 |

**一句总结**：和弦外音是"旋律不为和声让路"的技术手段 ——
没有它，旋律就只是和弦的分解。（旋律层的内容见 [[concept:melody|旋律]]。）

## 图示：外音让两条线错开

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">上排：只有和弦音 → 旋律 = 和弦分解　下排：加入外音 → 旋律自成一线</text>
  </g>

  <g transform="translate(48,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="0">C</text><text x="60" y="0">E</text><text x="120" y="0">G</text><text x="180" y="0">E</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="210" y="4">全部是 C 和弦的构成音 → 听感像拨和弦</text>
    </g>

    <g transform="translate(0,52)">
      <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
        <text x="0" y="0" fill="#5B7FA8">C</text><text x="60" y="0" fill="#E07A3F">D</text>
        <text x="120" y="0" fill="#5B7FA8">E</text><text x="180" y="0" fill="#E07A3F">F</text>
        <text x="240" y="0" fill="#5B7FA8">E</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.4">
        <line x1="60" y1="10" x2="60" y2="16"/><line x1="180" y1="10" x2="180" y2="16"/>
      </g>
      <text x="270" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">橙色 = 外音</text>
      <text x="0" y="30" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        D 是经过音（级进填充）· F 是辅助音（离开又回到 E）—— 都是短时值、随即解决
      </text>
    </g>
  </g>
</svg>
```

## 听一听：外音的效果

用琶音组件听三和弦的构成音（"和弦分解"），再想象同样的旋律骨架里插入经过音 ——
外音的作用是让旋律不再像分解和弦。

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"C 大三和弦（构成音）","label_en":"C major triad (its chord tones)","hint":"点「分解」听只有和弦音的旋律","hint_en":"Press Arpeggio — this is melody made of chord tones alone"}
```

## 常见误解

- **「外音就是错音」** → 它有明确类型与解决规则，是写作手段，不是失误。
- **「外音只出现在旋律里」** → 内声部同样有外音，且它们的处理更严格（因为更容易被听出冲突）。
- **「外音可以随意停留」** → 惯例上时值短、并级进解决；长时间停留会让它变成和弦音或挂留音。
- **「有了外音就不需要管和声了」** → 恰恰相反：外音必须**按和声的规矩**来解决，否则会听起来像写错。
:::

::: en
If every note of a melody had to belong to the current chord, music would quickly become strumming.
**Non-chord tones break that limit**: a note outside the prevailing harmony appears in the melody (or an inner
voice) and by convention resolves within a short time.

> They let **melody** and **harmony** become two lines that need not coincide exactly — the basis of
> contrapuntal thinking.

## The common types

| Name | How it appears | Example (over C–E–G) |
|---|---|---|
| **passing tone** | fills the step between two chord tones | C–**D**–E |
| **neighbour tone** | leaves a chord tone and returns to it | E–**F**–E |
| **appoggiatura** | a foreign note on a strong beat, resolving by step | **F** → E (entered on the beat) |
| **suspension** | a note from the previous chord held over, then resolved | see [[concept:suspended-chord|suspended chord]] |
| **anticipation** | a note of the next chord arriving early | **A** appearing over C–E–G |
| **escape tone** | entered by step, left by leap | C–**D** → B |

## Three conventions

1. **Short duration** — foreign notes are usually shorter than the chord tones either side;
2. **On a weak beat** (appoggiaturas and suspensions excepted) — a foreign note on a strong beat needs an
   explicit resolution and demands more care;
3. **Enter and leave by step** — approaching or quitting a foreign note by leap makes it sound like a chord
   tone and destroys the distinction.

## Why they matter

| Role | Explanation |
|---|---|
| **melodic freedom** | the melody need not be locked to the chord; it can move by step and breathe on its own |
| **local tension** | the foreign note collides with a chord tone, creating brief dissonance that is then released |
| **linking harmony** | an anticipation can announce the next chord and keep the progression flowing |

**In one line**: non-chord tones are the technique that lets **melody refuse to give way to harmony**. Without
them a melody is only an arpeggio. (For the melodic layer, see [[concept:melody|melody]].)

## Diagram: foreign notes pull the two lines apart

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Top: chord tones only, so the melody is an arpeggio. Bottom: with foreign notes the melody stands on its own</text>
  </g>

  <g transform="translate(48,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="0">C</text><text x="60" y="0">E</text><text x="120" y="0">G</text><text x="180" y="0">E</text>
    </g>
    <text x="210" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">all chord tones, so it reads as strumming</text>

    <g transform="translate(0,52)">
      <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
        <text x="0" y="0" fill="#5B7FA8">C</text><text x="60" y="0" fill="#E07A3F">D</text>
        <text x="120" y="0" fill="#5B7FA8">E</text><text x="180" y="0" fill="#E07A3F">F</text>
        <text x="240" y="0" fill="#5B7FA8">E</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.4">
        <line x1="60" y1="10" x2="60" y2="16"/><line x1="180" y1="10" x2="180" y2="16"/>
      </g>
      <text x="270" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">orange = foreign notes</text>
      <text x="0" y="30" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        D is a passing tone; F is a neighbour tone (leaving E and returning) — both short and immediately resolved
      </text>
    </g>
  </g>
</svg>
```

## Listen: the effect of foreign notes

Use the chord player to hear a triad's chord tones (melody as an arpeggio), then imagine passing notes inserted
into the same melodic frame — the point of a foreign note is that the melody stops sounding like a broken chord.

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"C 大三和弦（构成音）","label_en":"C major triad (its chord tones)","hint":"点「分解」听只有和弦音的旋律","hint_en":"Press Arpeggio to hear melody made of chord tones alone"}
```

## Common misconceptions

- **"A foreign note is a wrong note."** It has defined types and resolution rules; it is a compositional device, not a mistake.
- **"Foreign notes appear only in the melody."** Inner voices have them too, and handle them more strictly, since a clash is easier to hear there.
- **"A foreign note may linger."** Convention keeps it short and resolved by step; held for long it becomes a chord tone or a suspension.
- **"With foreign notes the harmony stops mattering."** The opposite: they must resolve **according to the harmony**, or they will sound like errors.
:::
