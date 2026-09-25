---
id: key-signature
site: theo
cat: T10
title: 调号
title_en: Key Signature
summary: 调号是"默认值"，不是"是什么调"——同一调号能服务多个调
summary_en: A key signature sets defaults; it does not name a key — one signature serves several keys
level: core
tags: [乐理, 记谱, 基础]
tags_en: [theory, notation, basics]
alias: [调号, 升降号, key signature]
order: 14
links:
  - "[[concept:clef]]"
  - "[[concept:circle-of-fifths]]"
  - "[[concept:tonal-center]]"
  - "[[concept:accidentals]]"
  - "[[concept:scale]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：每条练习的调号都很清楚，适合逐条确认"哪些音被默认升降" | Scale and cadence exercises have clear signatures, useful for checking which notes are altered by default
  - mutopia-000522 | 《欢乐颂》主题：调号简单、无临时记号，是最干净的"调号即默认值"样本 | The Ode of Joy has a simple signature and no accidentals, the cleanest sample of "signature means default"
  - thesession-019704 | 《小星星》：同样无临时记号，与上条一起说明"没有临时记号"不等于"没有调" | Twinkle Little Star also has none, confirming that "no accidentals" does not mean "no key"
sources:
  - 调号写在谱号之后并全局生效；升号顺序 F-C-G-D-A-E-B、降号顺序为其倒序，属记谱法通则
  - 同一调号可对应大调及其关系小调（含各种调式），为通行乐理表述
updated: 2026-09-25
---

::: zh
调号做的事很朴素，但极易被误解：

> **它是"默认值"** —— 把一组音的升降**提前写在谱号后面**，
> 从此这些音**自动**按升降后的形态出现，不必每个都标临时记号。

**它是"省事"的产物，不是"调名"的标记。** 这条区别是本节的核心。

## 升降号的书写顺序

| 类别 | 顺序 | 记忆法 |
|---|---|---|
| **升号** | **F · C · G · D · A · E · B** | 按**五度圈顺时针**走出来的次序 |
| **降号** | **B · E · A · D · G · C · F** | **升号顺序的倒序** |

**为什么是这个顺序**：它正是 [[concept:circle-of-fifths|五度圈]] 上从 C 顺时针（升）与逆时针（降）的次序。
所以"升号顺序为什么是 F–C–G–D–A–E–B"这个问题，答案在五度圈上（见 [[concept:key-signature|调号]] 与该条）。

## ⭐ 关键认识：调号不表示调

这是最值得记住的一点：

| 调号 | 它**可以**表示的调 |
|---|---|
| 无升降 | **C 大调** 或 **a 小调** 或 C 上的各种调式 |
| 一个升号（F♯） | **G 大调** 或 **e 小调** |
| 两个降号 | **B♭ 大调** 或 **g 小调** |

**所以看到调号，只能知道"用了哪些音"，不能知道"是什么调"** ——
要知道调，还得看**终止式与中心音**（见 [[concept:tonal-center|调性中心]]）。

这也解释了一个常见困惑："这首曲子没有升降号，是不是 C 大调？"——
**不一定**，也可能是 a 小调或某个调式。

## 临时记号与调号的关系

| | 调号 | 临时记号 |
|---|---|---|
| 位置 | 谱号之后 | 音符之前 |
| 生效范围 | **整段（除非更换）** | **本小节内有效** |
| 作用 | 设定**默认值** | **一次性**的改动 |

**"临时记号只在本小节内有效"是硬规则**：若下一个小节还要那个音，必须**再标一次**。
这条规则常让初学者困惑，但它有一个明确的理由：
**小节是重音与和声的基本单位**（见 [[concept:meter|拍号]]），所以记号的效力也按小节划分。

## 换调号时会发生什么

| 情况 | 做法 |
|---|---|
| 转调到新调 | 在**新谱表行开头**写新调号，有时在行末写"取消旧调号" |
| 临时取消 | 用还原号（♮）逐个还原 |
| 短距离离调 | **不改调号**，改用临时记号（见 [[concept:accidentals|变音记号]]） |

第三行的取舍是记谱实务的核心：**近处用临时记号，远处才改调号** ——
所以"一首曲子里调号变了"往往意味着**发生了大的转调**（见 [[concept:modulation|转调]]）。

## 图示：调号是默认值

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">调号把升降"提前声明"为默认值；但它不告诉你这是什么调</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">升号</text>
      <text x="-20" y="46" text-anchor="end">降号</text>
    </g>
    <g font-family="Georgia,serif" font-size="13" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">F</text><text x="34" y="0">C</text><text x="68" y="0">G</text>
      <text x="102" y="0">D</text><text x="136" y="0">A</text><text x="170" y="0">E</text><text x="204" y="0">B</text>
    </g>
    <text x="226" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">← 五度圈顺时针</text>

    <g transform="translate(0,46)" font-family="Georgia,serif" font-size="13" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="0">B</text><text x="34" y="0">E</text><text x="68" y="0">A</text>
      <text x="102" y="0">D</text><text x="136" y="0">G</text><text x="170" y="0">C</text><text x="204" y="0">F</text>
    </g>
    <text x="226" y="50" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">← 升号的倒序（五度圈逆时针）</text>

    <g transform="translate(0,92)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        调号不表示调：无升降号可以是 C 大调、a 小调或 C 上的任何调式
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        要确定调，还得看终止式与中心音（调到 tonal-center 条）；调号只说明"用了哪些音"
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        临时记号只在本小节内有效 —— 因为小节是重音与和声的基本单位
      </text>
    </g>
  </g>
</svg>
```

## 听一听：同一批音，两个中心

同一批音既可以当大调、也可以当小调 —— **这就是"调号不表示调"的听觉证据**。
本站听不出调号，但可以听**两个不同中心的音阶**（大调与自然小调）：

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"C 大调（中心 = C）","label_en":"C major — centred on C","hint":"点「上行」，注意中心感落在 C","hint_en":"Try Up and notice the centre settling on C","gap":0.34}
```

```audiolab
{"type":"scale","notes":["A3","B3","C4","D4","E4","F4","G4","A4"],"label":"a 自然小调（中心 = A，同一批音）","label_en":"A natural minor — centred on A, the same notes","hint":"与上一条对比：音相同，中心不同","hint_en":"Against the item above: same notes, different centre","gap":0.34}
```

## 常见误解

- **「调号就是调」** → 调号只说用了哪些音。同一调号可服务大调、关系小调与各种调式。
- **「没有升降号就是 C 大调」** → 也可能是 a 小调或 C 上的调式（如 C 多里亚）。
- **「调号里的升降号每次都要弹」** → 它们是**默认值**：该音**自动**按升降后的形态出现，所以**不必再标临时记号**。
- **「临时记号会一直有效」** → 只在本小节内有效。下一小节若需同样改动，**必须重标**。
:::

::: en
What a key signature does is plain but very easily misread:

> **It sets defaults** — a group of sharps or flats is written **once after the clef**, and those notes thereafter
> appear **automatically** in their altered form, without an accidental on each.

**It is a labour-saving device, not a label for a key.** That distinction is the heart of this entry.

## The order of sharps and flats

| Type | Order | How to remember |
|---|---|---|
| **sharps** | **F · C · G · D · A · E · B** | the order you get walking **clockwise** round the circle of fifths |
| **flats** | **B · E · A · D · G · C · F** | **the reverse** of the sharp order |

**Why that order**: it is exactly the sequence of clockwise (sharps) and anticlockwise (flats) steps from C on the
[[concept:circle-of-fifths|circle of fifths]]. So "why is the order of sharps F–C–G–D–A–E–B" is answered on the
circle.

## ⭐ The key insight: a signature does not name a key

The most important point here:

| Signature | Keys it **can** indicate |
|---|---|
| no sharps or flats | **C major**, or **A minor**, or any mode on C |
| one sharp (F♯) | **G major** or **E minor** |
| two flats | **B♭ major** or **G minor** |

**So a signature tells you which notes are in use, not which key you are in** — for the key you must read the
**cadences and the central pitch** (see [[concept:tonal-center|tonal centre]]).

Which answers a common puzzle: "this piece has no sharps or flats, so it is C major?" **Not necessarily** — it may
be A minor, or a mode.

## How accidentals relate to the signature

| | Key signature | Accidental |
|---|---|---|
| Position | after the clef | before a note |
| Scope | **the whole passage (until changed)** | **within its bar** |
| Function | sets **defaults** | a **one-off** alteration |

**"An accidental lasts only to the end of its bar" is a hard rule**: if the same alteration is needed in the next
bar, it **must be written again**. The rule puzzles beginners but has a clear reason: **the bar is the basic unit
of accent and harmony** (see [[concept:meter|metre]]), so a sign's scope is divided the same way.

## What happens when the signature changes

| Case | Practice |
|---|---|
| modulating to a new key | write the new signature at the **start of a new system**, sometimes cancelling the old at the end |
| cancelling temporarily | use naturals (♮) one by one |
| a brief tonicization | **do not change the signature**; use accidentals instead (see [[concept:accidentals|accidentals]]) |

That third choice is the practical heart of notation: **accidentals for what is near, a new signature for what is
far** — so "the signature changed mid-piece" usually means **a substantial modulation took place** (see
[[concept:modulation|modulation]]).

## Diagram: the signature as defaults

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The signature declares sharps and flats in advance as defaults; it does not say which key this is</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">sharps</text>
      <text x="-20" y="46" text-anchor="end">flats</text>
    </g>
    <g font-family="Georgia,serif" font-size="13" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">F</text><text x="34" y="0">C</text><text x="68" y="0">G</text>
      <text x="102" y="0">D</text><text x="136" y="0">A</text><text x="170" y="0">E</text><text x="204" y="0">B</text>
    </g>
    <text x="226" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">clockwise round the circle</text>

    <g transform="translate(0,46)" font-family="Georgia,serif" font-size="13" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="0">B</text><text x="34" y="0">E</text><text x="68" y="0">A</text>
      <text x="102" y="0">D</text><text x="136" y="0">G</text><text x="170" y="0">C</text><text x="204" y="0">F</text>
    </g>
    <text x="226" y="50" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">the reverse, walking anticlockwise</text>

    <g transform="translate(0,92)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        A signature does not name a key: no sharps or flats may be C major, A minor, or any mode on C
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        To find the key, read the cadences and the central pitch; the signature only says which notes are used
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        An accidental lasts only to the end of its bar — bars are the unit of accent and harmony
      </text>
    </g>
  </g>
</svg>
```

## Listen: one set of notes, two centres

The same notes can serve a major or a minor key — **the aural evidence that a signature does not name a key**. This
site cannot show a signature, but it can play **two scales with different centres**:

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"C 大调（中心 = C）","label_en":"C major — centred on C","hint":"点「上行」，注意中心感落在 C","hint_en":"Try Up and notice the centre settling on C","gap":0.34}
```

```audiolab
{"type":"scale","notes":["A3","B3","C4","D4","E4","F4","G4","A4"],"label":"a 自然小调（中心 = A，同一批音）","label_en":"A natural minor — centred on A, the same notes","hint":"与上一条对比：音相同，中心不同","hint_en":"Against the item above: same notes, different centre","gap":0.34}
```

## Common misconceptions

- **"The key signature is the key."** It says only which notes are in use. One signature serves a major key, its
  relative minor and various modes.
- **"No sharps or flats means C major."** It may be A minor, or a mode on C (C Dorian, for instance).
- **"Every sharp in the signature must be played each time."** They are **defaults**: the notes appear altered
  automatically, so **no accidental is needed**.
- **"An accidental lasts."** Only to the end of its bar. If the alteration is needed in the next bar, **write it
  again**.
:::
