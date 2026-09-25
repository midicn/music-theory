---
id: second-species
site: theo
cat: T6
title: 第二类对位
title_en: Second Species
summary: 一音对两音——弱拍终于可以是不协和音了
summary_en: Two notes against one — the weak beat may now be dissonant
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [第二类对位, 二音对一音, second species]
order: 16
links:
  - "[[concept:first-species]]"
  - "[[concept:third-species]]"
  - "[[concept:note-against-note]]"
  - "[[concept:non-chord-tone]]"
  - "[[concept:non-chord-tone-treatment]]"
instances:
  - mutopia-000287 | 巴赫第八首二部创意曲：句中的弱拍经过音很清楚，可听"强拍稳、弱拍动"的分工 | Bach's eighth two-part invention — passing notes on weak beats are clear, showing the strong-stable, weak-moving division
  - mutopia-000522 | 《欢乐颂》主题：级进里的经过音让旋律连贯，与和弦音的骨架形成对照 | The Ode of Joy theme — passing notes in the stepwise motion keep the line flowing, against the skeletal chord tones
  - giantmidi-006222 | 音阶与终止练习：每一步同值进行，适合观察"弱拍放宽"后织体的变化 | Scale and cadence exercises in equal note values show how the texture changes once weak beats are freed
sources:
  - 第二类对位（二音对一音）规则：强拍须为协和音、弱拍可用级进经过的不协和音，为通行对位教学体系
  - 弱拍放宽与和声节奏的原理一致（强拍承载骨架、弱拍承担连接），为通行表述
updated: 2026-09-24
---

::: zh
第二类对位在第一类的每一步之间**插入一个音**：

> 固定旋律每走一步，对位声部走两步。弱拍那一个音**终于可以是不协和的**。

## 新增的唯一变量：弱拍

第一类里每个音都必须是协和音，织体因此"一步一顿"。第二类放开的正是弱拍：

| 位置 | 要求 | 理由 |
|---|---|---|
| **强拍** | **必须协和** | 强拍是骨架位置，听觉上被"点数" |
| **弱拍** | **可以是不协和音**（级进经过） | 弱拍是连接位置，快速掠过不会被听成落点 |

这条放宽背后的原理，与 [[concept:harmonic-rhythm|和声节奏]] 完全一致：
**强拍承载骨架，弱拍承担连接。** 也正因如此，弱拍的不协和音必须**级进进入、级进离开**
（否则它会听起来像和弦音，见 [[concept:non-chord-tone-treatment|和弦外音处理]]）。

## 三条要注意的规则

**① 弱拍的不协和必须是"经过"型。**
两声部同向级进时最安全；如果构成跳进，听感立刻变成"错音"。

**② 不要每个弱拍都填经过音。**
全部塞满会让织体失去呼吸，实质上已变成第三类（见 [[concept:third-species|第三类对位]]）。
留白与填充的取舍，本身就是写作判断。

**③ 两声部的节奏要"错开"而不是"叠住"。**
如果两个声部总在同一时刻换音，第二类就退化成了"第一类加了个尾巴"。

## 与单音对位的关系

第二类不是"另一个体系"，而是 [[concept:note-against-note|单音对位]] 的**第一步放宽**：

> **第一类练"每一步都对"，第二类练"什么时候可以不那么对"。**

这个思路在整套训练里反复出现：**每次只放开一个限制，并给出配套的规则** ——
放开弱拍，就用"级进经过"来约束它。

## 图示：强拍与弱拍的分工

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">强拍稳住骨架，弱拍用级进的经过音连接</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">E</text><text x="160" y="0">G</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">C</text><text x="40" y="60">D</text><text x="80" y="60">E</text>
      <text x="120" y="60">F</text><text x="160" y="60">G</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="54"/><line x1="80" y1="8" x2="80" y2="54"/>
      <line x1="160" y1="8" x2="160" y2="54"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="2 3">
      <line x1="40" y1="8" x2="40" y2="54"/><line x1="120" y1="8" x2="120" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
      <text x="0" y="80" fill="#E8C547">强拍：八度（协和）</text>
      <text x="40" y="96" fill="#C0504A">弱拍：D（经过音 · 不协和）</text>
      <text x="80" y="80" fill="#E8C547">强拍：三度（协和）</text>
      <text x="120" y="96" fill="#C0504A">弱拍：F（经过音）</text>
      <text x="160" y="80" fill="#E8C547">强拍：五度（协和）</text>
    </g>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      弱拍的不协和音必须级进进入、级进离开 —— 否则会听起来像和弦音
    </text>
    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      原理与和声节奏一致：强拍承载骨架，弱拍承担连接
    </text>
  </g>
</svg>
```

## 听一听：协和与不协和的相邻

第二类是两声部练习，本站放不出两声部。这里用 `interval` 对比**强拍与弱拍上会出现的两种音程**：
先听三度（协和，可当骨架），再听二度（不协和，只能当经过）。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"强拍可用的三度（协和）","label_en":"A third, usable on a strong beat (consonant)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D4 得到二度 —— 它只能在弱拍上快速经过，不能停在强拍。","hint2_en":"Set b to D4 for a second — usable only as a quick passing note on a weak beat, never resting on a strong one."}
```

## 常见误解

- **「弱拍可以随便写不协和音」** → 必须**级进经过**。跳跃进入的不协和音听起来就是错音。
- **「弱拍越满越好」** → 每个弱拍都填经过音会失去呼吸，实质已进入第三类的写法。
- **「强拍的规则放宽了」** → 没有。强拍仍必须是协和音，第二类只放宽了弱拍。
- **「第二类比第一类简单」** → 变量更多（要同时管强拍、弱拍与两声部的节奏关系），只是织体更流动。
:::

::: en
Second species **inserts one note between the steps** of first species:

> For each step of the cantus firmus, the counterpoint moves twice. The note on the weak beat **may now be
> dissonant.**

## The one new variable: the weak beat

In first species every note had to be consonant, which made the texture step-locked. Second species frees
precisely the weak beat:

| Position | Requirement | Why |
|---|---|---|
| **strong beat** | **must be consonant** | the strong beat is a structural point; the ear counts it |
| **weak beat** | **may be dissonant** (by step) | the weak beat is a joining point; passed over quickly, it is not heard as an arrival |

The principle behind the relaxation is exactly that of [[concept:harmonic-rhythm|harmonic rhythm]]: **strong beats
carry the frame, weak beats carry the connection.** Which is also why the dissonant weak-beat note must **enter
and leave by step** (otherwise it will be heard as a chord tone — see
[[concept:non-chord-tone-treatment|treating non-chord tones]]).

## Three rules worth watching

**One: the weak-beat dissonance must be a passing note.** It is safest when both voices move by step in the same
direction; if it is approached by leap, it immediately sounds like an error.

**Two: do not fill every weak beat with a passing note.** Filling everything removes the texture's breathing and in
effect turns it into third species (see [[concept:third-species|third species]]). Deciding where to leave space is
itself a compositional judgement.

**Three: the two voices should be offset, not stacked.** If both always change pitch at the same instant, second
species degenerates into "first species with a tail".

## Its relation to note-against-note writing

Second species is not a separate system but the **first relaxation** of
[[concept:note-against-note|note-against-note]] writing:

> **First species trains "every step right"; second species trains "when you may stop being quite so right".**

The pattern recurs throughout the training: **relax one constraint at a time, and supply a rule to manage it.**
Freeing the weak beat comes with the rule "pass by step".

## Diagram: the division of labour between beats

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Strong beats hold the frame; weak beats join with passing notes</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">E</text><text x="160" y="0">G</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">C</text><text x="40" y="60">D</text><text x="80" y="60">E</text>
      <text x="120" y="60">F</text><text x="160" y="60">G</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="54"/><line x1="80" y1="8" x2="80" y2="54"/>
      <line x1="160" y1="8" x2="160" y2="54"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="2 3">
      <line x1="40" y1="8" x2="40" y2="54"/><line x1="120" y1="8" x2="120" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
      <text x="0" y="80" fill="#E8C547">strong: an octave (consonant)</text>
      <text x="40" y="96" fill="#C0504A">weak: D, a passing dissonance</text>
      <text x="80" y="80" fill="#E8C547">strong: a third</text>
      <text x="120" y="96" fill="#C0504A">weak: F, a passing note</text>
      <text x="160" y="80" fill="#E8C547">strong: a fifth</text>
    </g>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      A weak-beat dissonance must enter and leave by step, or it will sound like a chord tone
    </text>
    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The same principle as harmonic rhythm: strong beats carry the frame, weak beats the connection
    </text>
  </g>
</svg>
```

## Listen: consonant next to dissonant

Second species is a two-voice exercise and cannot be played here. Use `interval` to compare **the two intervals
that will appear on strong and weak beats**: a third (consonant, can be structural), then a second (dissonant,
passing only).

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"强拍可用的三度（协和）","label_en":"A third, usable on a strong beat (consonant)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D4 得到二度 —— 它只能在弱拍上快速经过，不能停在强拍。","hint2_en":"Set b to D4 for a second — usable only as a quick passing note on a weak beat, never resting on a strong one."}
```

## Common misconceptions

- **"Weak beats can hold any dissonance."** It must be a **passing** dissonance approached and left by step. A
  leap into a dissonance sounds like a mistake.
- **"Filling every weak beat is better."** That removes the breathing and effectively moves into third-species
  writing.
- **"The strong-beat rule was relaxed."** It was not. Strong beats must still be consonant; only the weak beat was
  freed.
- **"Second species is easier than first."** More variables are in play (strong beat, weak beat, and the rhythmic
  relation between the two voices); it is merely more flowing.
:::
