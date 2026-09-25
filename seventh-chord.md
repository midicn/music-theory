---
id: seventh-chord
site: theo
cat: T4
title: 七和弦
title_en: Seventh Chord
summary: 在三和弦上再叠一个七度——四个音，多出来的张力就是推动力
summary_en: One more third on top of a triad — four notes, and the added seventh supplies the push
level: core
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [七和弦, seventh chord, 四种七和弦]
order: 22
links:
  - "[[concept:chord]]"
  - "[[concept:triad]]"
  - "[[concept:dominant-seventh]]"
  - "[[concept:major-seventh]]"
  - "[[concept:minor-seventh]]"
  - "[[concept:half-diminished-seventh]]"
  - "[[concept:diminished-seventh]]"
  - "[[concept:harmonic-function]]"
  - "[[concept:cadence]]"
instances:
  - giantmidi-006222 | 音阶与琶音练习：七和弦琶音把四个音逐个弹出，比三和弦多出的那个音听得最清楚 | Scale and arpeggio exercises spell out seventh chords one note at a time, making the extra note obvious
  - cyberhymnal-000695 | 管风琴圣咏：传统和声里属七和弦是终止式的常客，可听它如何把音乐推回主和弦 | An organ hymn — dominant sevenths are standard at cadences; hear how they push the music home
  - atepp-000318 | a 小调奏鸣曲：小调作品里导七和弦的解决过程是这条概念最清楚的实例 | A sonata in A minor — the resolution of a leading-tone seventh is the clearest instance of the idea
sources:
  - 七和弦 = 在三和弦上再叠一个三度（共四个音、三个三度），属和声学通则
  - 七和弦因含七度而必须解决，其具体解决方向由和弦性质与调性位置决定，为通行和声学表述
updated: 2026-09-24
---

::: zh
七和弦就是在 [[concept:triad|三和弦]] 上**再加一层三度**：四个音，三个三度。

> C 七和弦 = C–E–G–**B**

多出来的这个音，把和弦的性质彻底改变了。三和弦之间的差别是"明暗"，
七和弦之间的差别是"**要不要走**" —— 因为**七度本身就是一个不稳定音程**。

## 五种常用七和弦

| 名称 | 构成（从 C 起） | 三和弦基础 | 出处 |
|---|---|---|---|
| [[concept:dominant-seventh|属七]] | C–E–G–B♭ | 大三 + 小七 | 大调 V 级、小调 V 级 |
| [[concept:major-seventh|大七]] | C–E–G–B | 大三 + 大七 | 大调 I、IV 级 |
| [[concept:minor-seventh|小七]] | C–E♭–G–B♭ | 小三 + 小七 | 大调 ii、iii、vi 级 |
| [[concept:half-diminished-seventh|半减七]] | C–E♭–G♭–B♭ | 减三 + 小七 | 大调 vii 级、小调 ii 级 |
| [[concept:diminished-seventh|减七]] | C–E♭–G♭–B𝄫 | 减三 + 减七 | 小调 vii 级、变化音 |

**前四种都能在大调音阶上按级数叠出来**，第五种（减七）需要变化音。
这也解释了为什么减七和弦听起来最"外来"。

## 七音带来的推力

七和弦的核心价值是**推力**：

| 音程 | 位置 | 效果 |
|---|---|---|
| **小七度** | 根音到七音 | 柔和的不安定 —— 需要向下解决 |
| **大七度** | 根音到七音 | 尖锐的不安定 —— 强烈的"要收束"感 |
| **减七度** | 根音到七音 | 最紧张 —— 一条减七和弦里有**两个**三全音 |

另外，属七和弦里有一个特殊的结构：**三音与七音之间本身构成三全音**（E–B♭）。
这正是它成为最强推动力的原因 —— 两个音一个要上行、一个要下行，
方向相反却又同时解决，形成"收拢"的动作（见 [[concept:cadence|终止式]]）。

## 七和弦不是"更高级的三和弦"

一个常见的误解是把七和弦当作三和弦的升级版。实际上：

- 三和弦可以**独立站住**（主和弦就是三和弦）；
- 七和弦**本质上不稳定**，即使是大七和弦也带着"想解决"的倾向。

所以在传统和声里，七和弦几乎总是**经过性的**：出现、推动、解决。
把它当作终点用，是浪漫派之后才逐渐普遍的做法。

## 图示：多出来的那个音

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">三层三度 = 四个音；第四个音决定了和弦"要不要走"</text>
  </g>

  <g transform="translate(48,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="12" y1="0" x2="12" y2="52"/>
      <line x1="8" y1="0" x2="16" y2="0"/><line x1="8" y1="52" x2="16" y2="52"/>
    </g>
    <text x="24" y="30" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">三和弦（两个三度）</text>

    <g transform="translate(190,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">B♭</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.2">
        <line x1="12" y1="0" x2="12" y2="78"/>
        <line x1="8" y1="0" x2="16" y2="0"/><line x1="8" y1="78" x2="16" y2="78"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.3" stroke-dasharray="3 2">
        <line x1="-18" y1="0" x2="-18" y2="78"/>
        <line x1="-22" y1="0" x2="-14" y2="0"/><line x1="-22" y1="78" x2="-14" y2="78"/>
      </g>
      <text x="-30" y="30" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="end">小七度</text>
      <text x="-30" y="48" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="end">＝不安定</text>
      <text x="24" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">七和弦（三个三度）</text>
    </g>

    <g transform="translate(440,-6)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">属七和弦内部还藏着</text>
      <text x="0" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">一个三全音：</text>
      <text x="0" y="42" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">E ↔ B♭（6 个半音）</text>
      <text x="0" y="64" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">三音要上行、七音要下行</text>
      <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">→ 反向解决，形成最强的收束</text>
    </g>
  </g>
</svg>
```

## 听一听：三和弦与七和弦

先听 C 大三和弦（能站住），再听属七和弦（C–E–G–B♭，必须走）。
多出来的那个音，就是全部区别。

```audiolab
{"type":"chord","root":"C4","quality":"dom7","inversion":0,"label":"属七和弦（C–E–G–B♭）","label_en":"Dominant seventh (C–E–G–B♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"maj7","inversion":0,"label":"大七和弦（C–E–G–B）","label_en":"Major seventh (C–E–G–B)","hint":"与上一条对比：七音高了半个音，紧张感不同","hint_en":"Compare with the item above — the seventh is a semitone higher and the tension changes"}
```

## 常见误解

- **「七和弦就是三和弦加个七音」** → 加的是**三度**（再叠一层），因此得到的是"四个音、三个三度"；加别的音得到的是挂留或加音和弦。
- **「七和弦比三和弦更高级」** → 它本质上是**不稳定**的。三和弦能当终点，七和弦通常只能当过程。
- **「所有七和弦都要解决」** → 传统和声里如此；印象派与爵士里七和弦可以长期停留，甚至作为终点。
- **「减七和弦就是半减七和弦」** → 差别在七音：半减七的七音是小七度，减七的七音是减七度（低半个音）。两者是完全不同的和弦。
:::

::: en
A seventh chord is a [[concept:triad|triad]] with **one more third on top**: four notes, three thirds.

> C seventh chord = C–E–G–**B**

That added note changes the chord's nature entirely. The difference between triads is brightness; the difference
between seventh chords is **whether they must move** — because **a seventh is itself an unstable interval.**

## The five common seventh chords

| Name | Content (from C) | Base triad | Found on |
|---|---|---|---|
| [[concept:dominant-seventh|dominant seventh]] | C–E–G–B♭ | major + minor seventh | degree 5 in major and minor |
| [[concept:major-seventh|major seventh]] | C–E–G–B | major + major seventh | degrees 1 and 4 in major |
| [[concept:minor-seventh|minor seventh]] | C–E♭–G–B♭ | minor + minor seventh | degrees 2, 3, 6 in major |
| [[concept:half-diminished-seventh|half-diminished]] | C–E♭–G♭–B♭ | diminished + minor seventh | degree 7 in major, degree 2 in minor |
| [[concept:diminished-seventh|diminished seventh]] | C–E♭–G♭–B𝄫 | diminished + diminished seventh | degree 7 in minor, chromatic |

**The first four can all be stacked from a major scale by degree**; the fifth needs chromatic alteration. That is
also why the diminished seventh sounds the most imported of them.

## The push supplied by the seventh

A seventh chord's core value is **propulsion**:

| Interval | Position | Effect |
|---|---|---|
| **minor seventh** | root to seventh | a soft instability — needs to resolve downward |
| **major seventh** | root to seventh | a sharp instability — a strong pull to close |
| **diminished seventh** | root to seventh | maximum tension — one such chord holds **two** tritones |

There is also a special internal feature of the dominant seventh: **its third and seventh form a tritone between
them** (E–B♭). That is exactly why it pushes hardest — one note wants to rise while the other wants to fall, and
the opposing motions resolve together into a closing gesture (see [[concept:cadence|cadence]]).

## A seventh chord is not an "upgraded triad"

A common misreading treats seventh chords as triads with extras. In fact:

- a triad can **stand on its own** (a tonic triad does);
- a seventh chord is **inherently unstable** — even a major seventh carries a wish to resolve.

So in traditional harmony a seventh chord is nearly always **transitional**: it appears, it drives, it resolves.
Treating one as a destination only became widespread after the Romantic era.

## Diagram: the note that makes the difference

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Three layers of thirds make four notes; the fourth decides whether the chord must move</text>
  </g>

  <g transform="translate(48,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="12" y1="0" x2="12" y2="52"/>
      <line x1="8" y1="0" x2="16" y2="0"/><line x1="8" y1="52" x2="16" y2="52"/>
    </g>
    <text x="24" y="30" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">triad (two thirds)</text>

    <g transform="translate(190,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="26">E</text><text x="0" y="52">G</text><text x="0" y="78">B♭</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.2">
        <line x1="12" y1="0" x2="12" y2="78"/>
        <line x1="8" y1="0" x2="16" y2="0"/><line x1="8" y1="78" x2="16" y2="78"/>
      </g>
      <g stroke="#C0504A" stroke-width="1.3" stroke-dasharray="3 2">
        <line x1="-18" y1="0" x2="-18" y2="78"/>
        <line x1="-22" y1="0" x2="-14" y2="0"/><line x1="-22" y1="78" x2="-14" y2="78"/>
      </g>
      <text x="-30" y="30" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="end">a minor seventh</text>
      <text x="-30" y="48" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="end">means instability</text>
      <text x="24" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">seventh chord (three thirds)</text>
    </g>

    <g transform="translate(440,-6)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">A dominant seventh also</text>
      <text x="0" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">hides a tritone:</text>
      <text x="0" y="42" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">E against B♭ (6 semitones)</text>
      <text x="0" y="64" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">the third rises while the seventh falls</text>
      <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">opposite motions closing together</text>
    </g>
  </g>
</svg>
```

## Listen: triad against seventh chord

Hear the C major triad (it can stand), then the dominant seventh C–E–G–B♭ (it must move). The extra note is the
whole difference.

```audiolab
{"type":"chord","root":"C4","quality":"dom7","inversion":0,"label":"属七和弦（C–E–G–B♭）","label_en":"Dominant seventh (C–E–G–B♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"maj7","inversion":0,"label":"大七和弦（C–E–G–B）","label_en":"Major seventh (C–E–G–B)","hint":"与上一条对比：七音高了半个音，紧张感不同","hint_en":"Compare with the item above — the seventh is a semitone higher and the tension changes"}
```

## Common misconceptions

- **"A seventh chord is a triad plus a seventh note."** It is a triad plus **a third**, giving four notes and three thirds; adding other notes produces suspended or added-tone chords.
- **"Seventh chords are more advanced triads."** They are **inherently unstable**. A triad can be a destination; a seventh chord is usually a process.
- **"Every seventh chord must resolve."** In traditional harmony yes; in Impressionism and jazz they can linger, or even serve as the endpoint.
- **"The diminished seventh and the half-diminished seventh are the same."** They differ in the seventh: minor in the half-diminished, diminished (a semitone lower) in the diminished seventh. Two entirely different chords.
:::
