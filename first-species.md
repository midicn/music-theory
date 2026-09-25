---
id: first-species
site: theo
cat: T6
title: 第一类对位
title_en: First Species
summary: 一音对一音的严格训练——先练"每一步音程都对"
summary_en: The strict one-to-one exercise — first get every single interval right
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [第一类对位, 一音对一音对位, first species]
order: 14
links:
  - "[[concept:note-against-note]]"
  - "[[concept:second-species]]"
  - "[[concept:cantus-firmus]]"
  - "[[concept:parallel-fifths]]"
  - "[[concept:consonance]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：声部进入段接近一音对一音，可用来核对每一步的音程关系 | Bach's first two-part invention — the entry passage is close to note against note, useful for checking each interval
  - cyberhymnal-000695 | 管风琴圣咏：四声部同步换音的写法，与第一类对位的织体同源 | An organ hymn — four voices changing together, the same texture family as first species
  - giantmidi-006222 | 音阶与终止练习：每一步同值进行，最适合用来练习"逐步检查纵向音程" | Scale and cadence exercises move in equal note values, ideal for practising step-by-step interval checking
sources:
  - 第一类对位（一音对一音）的规则：起止用完全协和、内部以不完全协和为主、避免平行与隐伏五八度，为通行对位教学体系
  - 完全协和作骨架、不完全协和作流动这一分工，与和声学的协和分级同源
updated: 2026-09-24
---

::: zh
第一类对位就是 [[concept:note-against-note|单音对位]] 的**严格训练阶段**：
一音对一音，每一步都要经得起检查。它只教一件事 —— **把"这一步用什么音程"变成条件反射**。

## 两条核心规则

**① 完全协和是骨架，不完全协和是流动。**

| 音程类别 | 音程 | 在第一类里 |
|---|---|---|
| **完全协和** | 纯一、纯八、纯五、纯四 | 用在**起点与终点**（骨架位置） |
| **不完全协和** | 大/小 三度、六度 | 用在**内部**（流动位置） |
| **不协和** | 二度、七度、增四减五 | **本类禁用** |

为什么这样分？因为完全协和**太稳定**：连续用它，音乐会听起来像一串终止式，
**分不出哪里是真正的结束**。所以骨架位置只在开头结尾（偶有中间的关键点），
中间用三度六度来"走动"（见 [[concept:consonance|协和与不协和]]）。

**② 避免平行与隐伏五八度。**

完全协和不能**连续**出现（见 [[concept:parallel-fifths|平行五八度]]）——
两声部会合成一条线，声部数量凭空少一个。
**隐伏五八度**（同向到达、且高声部有跳进）同样要避免。

## 写作时的检查顺序

这是第一类最实用的部分 —— **按固定顺序查，不要凭感觉**：

| 顺序 | 查什么 | 不合格的样子 |
|---|---|---|
| **1** | 每一步的纵向音程是否合法 | 中间出现二度或七度 |
| **2** | 起止是否落在完全协和上 | 结尾停在六度上（听起来没结束） |
| **3** | 有没有连续的完全协和 | 两个五度连着走 |
| **4** | 两条线的方向 | 全程同向（尤其全程同向跳进） |
| **5** | 每条线单独唱是否像旋律 | 出现了连续的大跳或"来回横跳" |

**第 5 条最重要，也最容易忘。** 前四条都合格、但两个声部都唱不出旋律的写法，
在检查表上是"全对"，在音乐上是失败的（见 [[concept:counterpoint|对位]]）。

## 图示：骨架位置与流动位置

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">首尾用完全协和（骨架），中间用不完全协和（流动）</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">C</text><text x="64" y="60">F</text><text x="128" y="60">A</text>
      <text x="192" y="60">A</text><text x="256" y="60">C</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="54"/><line x1="64" y1="8" x2="64" y2="54"/>
      <line x1="128" y1="8" x2="128" y2="54"/><line x1="192" y1="8" x2="192" y2="54"/>
      <line x1="256" y1="8" x2="256" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
      <text x="0" y="80" fill="#5B7FA8">八度（骨架）</text>
      <text x="64" y="80" fill="#E8C547">三度（流动）</text>
      <text x="128" y="80" fill="#E8C547">六度（流动）</text>
      <text x="192" y="80" fill="#E8C547">三度（流动）</text>
      <text x="256" y="80" fill="#5B7FA8">八度（骨架）</text>
    </g>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      完全协和太稳定 —— 连续用会像一串终止式，让人分不出哪里是真正的结束
    </text>
    <text x="0" y="128" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      检查顺序：①每步音程合法 ②起止完全协和 ③无连续完全协和 ④方向 ⑤每条线单独唱像不像旋律
    </text>
    <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      前四条全对、但两条线都唱不出旋律的写法：检查表上"全对"，音乐上是失败的
    </text>
  </g>
</svg>
```

## 听一听：骨架与流动的差别

第一类是两声部练习，本站听辨件放不出两声部。这里用 `interval` 对比**骨架音程与流动音程**：
先听八度与五度（完全协和，稳定），再听三度（不完全协和，有流动感）——
第一类对位要练的正是"在正确的时刻选对其中一种"。

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"骨架位置：纯五度","label_en":"A structural point: a perfect fifth","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E4 就是流动位置的三度 —— 稳定与流动，正是第一类对位要分清的两种处境。","hint2_en":"Set b to E4 for a third at a flowing point — stable versus flowing is exactly the distinction first species trains."}
```

## 常见误解

- **「第一类对位只是入门练习，没什么内容」** → 它教的判断（骨架 vs 流动、完全 vs 不完全协和）贯穿全部和声写作。
- **「完全协和越多越安全」** → 完全协和**不能连续**，而且连续出现会让调性中心模糊。
- **「只要每个音程都合法就写对了」** → 第 5 条才是关键：**每条线单独唱必须像旋律**。
- **「规则太多太死板」** → 每条规则都对应一个可听见的后果（融合成一条线、听不出结束、线条不像旋律）——不是审美偏好。
:::

::: en
First species is the **strict training stage** of [[concept:note-against-note|note against note]]: one note to one
note, every step accountable. It teaches exactly one thing — **making "which interval goes here" automatic.**

## The two core rules

**One: perfect consonances are the frame, imperfect ones the flow.**

| Class | Intervals | In first species |
|---|---|---|
| **perfect consonance** | unison, octave, fifth, fourth | used at the **start and end** (structural points) |
| **imperfect consonance** | major/minor thirds and sixths | used **internally** (flowing points) |
| **dissonance** | seconds, sevenths, tritone | **forbidden in this species** |

Why the split? Because perfect consonances are **too stable**: use them continuously and the music sounds like a
string of cadences, so **you can no longer tell where the real ending is**. Structural points therefore occur only
at the opening and close (with the occasional interior pivot), while thirds and sixths do the walking (see
[[concept:consonance|consonance and dissonance]]).

**Two: avoid parallel and hidden fifths and octaves.**

Perfect consonances must not appear **consecutively** (see [[concept:parallel-fifths|parallel fifths]]) — the two
voices fuse into one and the texture loses a voice. **Hidden fifths and octaves** (arriving by similar motion with
a leap in the upper voice) are avoided too.

## The order to check your work

This is the most practical part — **check in a fixed order, never by feel**:

| Order | Check | What failure looks like |
|---|---|---|
| **1** | is the vertical interval legal at every step? | a second or seventh in the middle |
| **2** | do start and end land on perfect consonances? | ending on a sixth, so it sounds unfinished |
| **3** | any consecutive perfect consonances? | two fifths in a row |
| **4** | direction of the two lines | similar motion throughout, especially with leaps |
| **5** | does each line work as a melody when sung alone? | repeated wide leaps, or jumping back and forth |

**The fifth matters most and is the most forgotten.** A setting that passes the first four and yet yields no
singable line in either voice is "all correct" on the checklist and a failure in music (see
[[concept:counterpoint|counterpoint]]).

## Diagram: structural points and flowing points

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Perfect consonances at the ends (frame), imperfect ones inside (flow)</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">C</text><text x="64" y="60">F</text><text x="128" y="60">A</text>
      <text x="192" y="60">A</text><text x="256" y="60">C</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="54"/><line x1="64" y1="8" x2="64" y2="54"/>
      <line x1="128" y1="8" x2="128" y2="54"/><line x1="192" y1="8" x2="192" y2="54"/>
      <line x1="256" y1="8" x2="256" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
      <text x="0" y="80" fill="#5B7FA8">octave (frame)</text>
      <text x="64" y="80" fill="#E8C547">third (flow)</text>
      <text x="128" y="80" fill="#E8C547">sixth (flow)</text>
      <text x="192" y="80" fill="#E8C547">third (flow)</text>
      <text x="256" y="80" fill="#5B7FA8">octave (frame)</text>
    </g>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Perfect consonances are too stable — used continuously they sound like cadences and hide the real ending
    </text>
    <text x="0" y="128" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      Check in order: intervals, endpoints, no consecutive perfects, direction, then whether each line sings
    </text>
    <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Correct on the checklist and unsingable in both voices: the classic failure
    </text>
  </g>
</svg>
```

## Listen: frame versus flow

First species is a two-voice exercise and cannot be played here. Use `interval` to compare a **structural
interval with a flowing one**: hear the fifth (perfect, stable), then the third (imperfect, mobile). First species
trains choosing the right one at the right moment.

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"骨架位置：纯五度","label_en":"A structural point: a perfect fifth","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E4 就是流动位置的三度 —— 稳定与流动正是第一类对位要分清的两件事。","hint2_en":"Set b to E4 for a third at a flowing point — stable versus flowing is exactly what first species trains."}
```

## Common misconceptions

- **"First species is just a beginner exercise."** The distinction it teaches — frame versus flow, perfect versus
  imperfect — runs through all harmonic writing.
- **"More perfect consonances is safer."** They must not be consecutive, and consecutive use blurs the tonal
  centre.
- **"If every interval is legal, the writing is correct."** The fifth test is decisive: **each line must sing.**
- **"Too many rules, too rigid."** Every rule names an audible consequence — voices fusing, the ending
  disappearing, a line that stops being melodic. Not taste, consequence.
:::
