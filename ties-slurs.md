---
id: ties-slurs
site: theo
cat: T10
title: 连音线与圆滑线
title_en: Ties and Slurs
summary: 外形几乎一样，含义完全不同——这是最常见的读谱错误
summary_en: Nearly identical in shape, entirely different in meaning — the commonest misreading
level: standard
tags: [乐理, 记谱, 基础]
tags_en: [theory, notation, basics]
alias: [连音线, 圆滑线, 延音线, ties and slurs]
order: 28
links:
  - "[[concept:note-values]]"
  - "[[concept:articulation]]"
  - "[[concept:phrase]]"
  - "[[concept:meter]]"
  - "[[concept:breath-phrasing]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：乐句的圆滑线清楚，句尾的长音用连音线合并，两种线在同一页都有 | The Ode of Joy shows slurs across its phrases and ties joining long closing notes — both signs on one page
  - giantmidi-006222 | 音阶与终止练习：同一音高的重复若需合并，必须用连音线，可用于辨析两者 | Scale exercises require a tie whenever a repeated pitch must be held, useful for telling the two apart
  - cyberhymnal-000695 | 管风琴圣咏：声乐性写法里圆滑线常与歌词的音节对应 | An organ hymn — in vocal-style writing slurs often correspond to syllables of the text
sources:
  - 连音线（tie）合并同音高的两个音符为一个音；圆滑线（slur）表示不同音高间的连奏，为记谱法通则
  - 圆滑线在声乐中表示一字多音，为通行记谱规范
updated: 2026-09-25
---

::: zh
两种记号的外形几乎一样（一条弧线），但含义**完全不同**。
把它们混起来，是初学者最常见的读谱错误。

> **连音线（tie）= 把两个同音合并成一个音。**
> **圆滑线（slur）= 把几个不同音连起来奏（唱）。**

## 一张表分清楚

| | **连音线**（tie） | **圆滑线**（slur） |
|---|---|---|
| 连接的音 | **必须音高相同** | **音高不同** |
| 效果 | 时值**相加**，实际是**一个音** | 每个音**都发声**，只是连起来 |
| 用途 | 跨小节 / 跨拍延长时值 | 演奏法（连奏）、声乐的一字多音 |
| 数量 | 通常两音相连 | 可以覆盖**多个**音 |

## 怎么判断：看音高

**只有一个判据**：

> **弧线两端的音高相同 → 连音线；不同 → 圆滑线。**

| 谱面 | 判断 | 实际效果 |
|---|---|---|
| `♩~♪` 两个都是 C | **连音线** | 一个 1.5 拍的 C |
| `C~D` 两个音不同 | **圆滑线** | 两个音都发声，连奏 |

**所以遇到弧线，第一步不是看它有多长，而是看两端是什么音。**

## 各自的用途

**连音线**（回顾 [[concept:note-values|音符时值]]）：

| 情形 | 为什么需要 |
|---|---|
| 音**跨过小节线** | 小节线必须保留（它是重音标记，见 [[concept:meter|拍号]]） |
| 音跨过**拍点** | 让拍的分组仍然看得清 |
| 所有音高相同 | 这是连音线成立的**前提** |

**圆滑线**：

| 情形 | 含义 |
|---|---|
| 器乐 | **连奏（legato）** —— 音与音之间不断开 |
| 声乐 | **一字多音** —— 一个音节唱多个音 |
| 木管 / 弦乐 | 提示**换气位置**与**弓法分组** |

**第三行很实用**：管乐手看到圆滑线就知道这一段**要一口气吹完**；弦乐手据此决定一弓拉几个音
（见 [[concept:articulation|演奏法记号]] 与 [[concept:breath-phrasing|呼吸与句读]]）。

## 一个容易搞错的情形

**同一小节内相邻的两个同音**：

| 写法 | 含义 |
|---|---|
| 只写一个音，时值更长 | 一个音 |
| 写两个音 + **连音线** | **一个音**（时值相加） |
| 写两个音 + **圆滑线** | **两个音**（各自发声，但连奏） |

**第二与第三行的区别在"音高是否相同"** —— 如果音高相同、你却把它当圆滑线读，
就会**多弹一次**（这在钢琴上是很明显的错误）。

**在钢琴与弦乐上，音高相同且带连音线时**：**只发声一次**，不要重新击键或换弓。

## 图示：一条弧线，两种含义

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">判断方法只有一个：弧线两端的音高是否相同</text>
  </g>

  <g transform="translate(56,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">
      <text x="0" y="0">两端音高相同 → 连音线（合并为一个音）</text>
    </g>
    <g font-family="Georgia,serif" font-size="13" fill="#E8C547" text-anchor="middle">
      <text x="20" y="24">C</text><text x="80" y="24">C</text>
    </g>
    <path d="M8,32 Q50,16 92,32" fill="none" stroke="#E8C547" stroke-width="1.6"/>
    <text x="110" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">= 一个 1.5 拍的 C（只发声一次）</text>

    <g transform="translate(0,58)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">
        <text x="0" y="0">两端音高不同 → 圆滑线（连奏）</text>
      </g>
      <g font-family="Georgia,serif" font-size="13" fill="#5B7FA8" text-anchor="middle">
        <text x="20" y="24">C</text><text x="80" y="24">D</text>
      </g>
      <path d="M8,32 Q50,16 92,32" fill="none" stroke="#5B7FA8" stroke-width="1.6"/>
      <text x="110" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">= 两个音都发声，但连起来奏</text>
    </g>

    <g transform="translate(0,120)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
        把连音线当圆滑线读 → 会多弹一次（钢琴与弦乐上尤其明显）
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        圆滑线在声乐里表示一字多音；在管乐里提示换气位置；在弦乐里决定一弓几个音
      </text>
    </g>
  </g>
</svg>
```

## 听一听：一次发声与两次发声

本站无法演示谱面，但可以听**同一个音重复两次**与**一个持续音**的差别 ——
这正是"圆滑线读法"与"连音线读法"在听觉上的分界。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q h","bpm":76,"label":"两次发声（若把连音线误读成圆滑线）","label_en":"Two attacks — what happens if you misread a tie as a slur","hint":"点「播放」，注意开头的两下","hint_en":"Press play and notice the two attacks at the start"}
```

## 常见误解

- **「两种线是一回事」** → 完全不同：一个**合并时值**，一个**表示连奏**。判断看两端音高。
- **「连音线连接的音要各弹一次」** → 只发声**一次**（时值相加）。重弹是明显错误。
- **「圆滑线只用于器乐」** → 声乐里它表示**一字多音**，是最常见的用法之一。
- **「长弧线一定是圆滑线」** → 长度不是判据。**音高**才是判据（同音相连就是连音线，多长都一样）。
:::

::: en
The two signs look nearly identical (an arc), but mean **entirely different things**. Confusing them is the
commonest reading error among beginners.

> **A tie joins two notes of the same pitch into one.**
> **A slur connects several notes of different pitches.**

## A table to keep them apart

| | **Tie** | **Slur** |
|---|---|---|
| Notes joined | **must be the same pitch** | **different pitches** |
| Effect | values **added**, in practice **one note** | every note **sounds**, but connected |
| Use | extending a value across beats or bars | articulation (legato), one syllable over several notes in vocal music |
| Number of notes | usually two | may cover **many** |

## How to tell: look at the pitch

**One test only**:

> **Same pitch at both ends of the arc means a tie; different pitches mean a slur.**

| Notation | Verdict | Actual effect |
|---|---|---|
| `♩~♪`, both C | **tie** | a single C lasting 1.5 beats |
| `C~D`, different | **slur** | both notes sound, played legato |

**So on meeting an arc, the first question is not how long it is but what notes it joins.**

## What each is for

**Ties** (recall [[concept:note-values|note values]]):

| Case | Why needed |
|---|---|
| a note **crossing a bar line** | the bar line must be preserved (it marks the accent, see [[concept:meter|metre]]) |
| a note crossing a **beat** | keeps the beat grouping visible |
| all pitches equal | the **precondition** for a tie |

**Slurs**:

| Case | Meaning |
|---|---|
| instrumental | **legato** — no break between notes |
| vocal | **one syllable over several notes** |
| wind / strings | indicates **where to breathe** and how to group a bow |

**The third row is practical**: a wind player reading a slur knows that passage must be played in one breath, and a
string player decides how many notes go in one bow (see [[concept:articulation|articulation]] and
[[concept:breath-phrasing|breathing and phrasing]]).

## One case that is easily misread

**Two adjacent notes of the same pitch inside one bar**:

| Written as | Meaning |
|---|---|
| one note with a longer value | one note |
| two notes plus a **tie** | **one note** (values added) |
| two notes plus a **slur** | **two notes** (both sound, played legato) |

**The difference between rows two and three is whether the pitches are equal.** If the pitches are equal and you
read it as a slur, you will **play the note twice** — a very audible error on piano.

**On piano and strings, equal pitches joined by a tie sound once**: do not re-strike the key or change bow.

## Diagram: one arc, two meanings

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One test: are the pitches at the two ends the same?</text>
  </g>

  <g transform="translate(56,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">
      <text x="0" y="0">same pitch at both ends means a tie, joined into one note</text>
    </g>
    <g font-family="Georgia,serif" font-size="13" fill="#E8C547" text-anchor="middle">
      <text x="20" y="24">C</text><text x="80" y="24">C</text>
    </g>
    <path d="M8,32 Q50,16 92,32" fill="none" stroke="#E8C547" stroke-width="1.6"/>
    <text x="110" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">one C of 1.5 beats, sounding once</text>

    <g transform="translate(0,58)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">
        <text x="0" y="0">different pitches mean a slur, played legato</text>
      </g>
      <g font-family="Georgia,serif" font-size="13" fill="#5B7FA8" text-anchor="middle">
        <text x="20" y="24">C</text><text x="80" y="24">D</text>
      </g>
      <path d="M8,32 Q50,16 92,32" fill="none" stroke="#5B7FA8" stroke-width="1.6"/>
      <text x="110" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">both notes sound, connected</text>
    </g>

    <g transform="translate(0,120)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
        Misreading a tie as a slur makes you play the note twice — very audible on piano and strings
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        In vocal music a slur means one syllable over several notes; for winds it marks the breath; for strings the bow
      </text>
    </g>
  </g>
</svg>
```

## Listen: one attack or two

This site cannot show a staff, but it can play **a repeated note twice** against **one sustained note** — exactly
the aural difference between reading an arc as a slur and as a tie.

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q h","bpm":76,"label":"两次发声（误读连音线的结果）","label_en":"Two attacks — what happens if you misread a tie as a slur","hint":"点「播放」，注意开头的两下","hint_en":"Press play and notice the two attacks at the start"}
```

## Common misconceptions

- **"The two signs are the same."** Entirely different: one **adds durations**, the other **marks legato**. The test
  is the pitch at each end.
- **"Notes joined by a tie are each played."** The note sounds **once** (values added). Re-striking is a clear error.
- **"Slurs are only for instruments."** In vocal music a slur means **one syllable over several notes**, one of its
  commonest uses.
- **"A long arc must be a slur."** Length is not the test. **Pitch** is — equal pitches make a tie however long it
  is.
:::
