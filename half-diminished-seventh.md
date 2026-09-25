---
id: half-diminished-seventh
site: theo
cat: T4
title: 半减七和弦
title_en: Half-Diminished Seventh
summary: 减三和弦加小七度——"减了一半"，因此比减七温和
summary_en: A diminished triad plus a minor seventh — half diminished, and therefore milder than a full diminished seventh
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [半减七和弦, half diminished, 导七和弦, m7b5]
order: 32
links:
  - "[[concept:seventh-chord]]"
  - "[[concept:diminished-seventh]]"
  - "[[concept:diminished-triad]]"
  - "[[concept:minor-seventh]]"
  - "[[concept:scale-harmony]]"
instances:
  - giantmidi-006222 | 琶音练习可弹出半减七琶音，与减七对照可听出七音高半音带来的缓和 | Scale exercises can sound a half-diminished arpeggio; against a diminished seventh the calming semitone is clear
  - atepp-000318 | a 小调奏鸣曲：小调第 2 级上的半减七和弦作下属功能，解决方向明确 | A sonata in A minor — the half-diminished seventh on degree 2 acts as a subdominant with a clear resolution
  - mutopia-000280 | 巴赫二部创意曲第一首：半减七和弦出现在推进处，随即被平滑解决 | Bach's first two-part invention — half-diminished sevenths appear as the music drives forward and resolve smoothly
sources:
  - 半减七和弦 = 减三和弦 + 小七度（三个音为小三度、小三度、大三度），属和声学通则
  - 大调 vii 级与小调 ii 级上自然产生半减七和弦，为通行和声学表述
updated: 2026-09-24
---

::: zh
半减七和弦的结构是**减三和弦 + 小七度**：

> C 半减七 = C–E♭–G♭–B♭（记作 Cø7 或 Cm7♭5）

名字里的"半减"来自历史：它**只减了一半** —— 三和弦是减的，七音却是普通的小七度。
而 [[concept:diminished-seventh|减七和弦]] 是**两头都减**（七音再低半个音）。

| 和弦 | 三和弦 | 七音 | 三全音个数 |
|---|---|---|---|
| **半减七** | 减三 | 小七度 | **1 个**（根音与五音） |
| **减七** | 减三 | 减七度 | **2 个** |

**一个三全音和两个三全音的差别，就是它比减七和弦"温和"的全部原因。**

## 它出没的位置

| 音阶 | 级数 | 常见用法 |
|---|---|---|
| **大调** | 第 7 级（viiø7） | 导和弦，解决到 I |
| **自然小调** | 第 2 级（iiø7） | 下属功能，解决到 V |

大调音阶上叠三度得到唯一的半减七和弦 —— 这让它成为"调内七和弦"里最容易被识别的一个。
在爵士里 **iiø7–V7–i** 是小调最基本的进行，两个和弦都是七和弦。

## 别和减七混起来

两者的音只差一个（五音不同？不是 —— **是七音差半个音**）：

| | 音（从 C 起） |
|---|---|
| 半减七 | C–E♭–G♭–**B♭** |
| 减七 | C–E♭–G♭–**B𝄫** |

听感差别不小：减七和弦"悬在空中"，半减七和弦则明显**指向某个方向**。
这也说明一件重要的事：**和弦的不稳定程度由内部三全音的数量决定**。

## 图示：减一半与全减

```svg
<svg viewBox="0 0 640 190" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样从减三和弦出发，七音的高度决定"悬停"还是"指向"</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="26">E♭</text><text x="0" y="52">G♭</text><text x="0" y="78">B♭</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2"><line x1="12" y1="0" x2="12" y2="78"/></g>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">半减七：1 个三全音</text>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">指向明确，可平滑解决</text>

    <g transform="translate(280,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#C0504A" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="26">E♭</text><text x="0" y="52">G♭</text><text x="0" y="78">B𝄫</text>
      </g>
      <g stroke="#C0504A" stroke-width="1.2"><line x1="12" y1="0" x2="12" y2="78"/></g>
      <g stroke="#C0504A" stroke-width="1.2" stroke-dasharray="3 2"><line x1="42" y1="0" x2="42" y2="78"/></g>
      <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">减七：2 个三全音</text>
      <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">悬停，急须解决</text>
    </g>
  </g>
</svg>
```

## 听一听：半减七和弦

听它的"暗但要说清楚方向"的感觉，再与减七对照。

```audiolab
{"type":"chord","root":"C4","quality":"hdim7","inversion":0,"label":"半减七和弦（C–E♭–G♭–B♭）","label_en":"Half-diminished seventh (C–E♭–G♭–B♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「半减七就是减七」** → 七音差半个音，三全音数量差一个（1 个 vs 2 个），听感差别明显。
- **「半减七和弦很罕见」** → 它在大调第 7 级、小调第 2 级上**自然出现**，是调内和弦之一。
- **「m7♭5 和 ø7 是两种和弦」** → 同一和弦的两种写法：前者是流行写法，后者是爵士记法。
- **「含减五度就一定极不稳定」** → 它比减七温和得多。不稳定程度与三全音的**数量**直接相关。
:::

::: en
A half-diminished seventh is **a diminished triad plus a minor seventh**:

> C half-diminished = C–E♭–G♭–B♭ (written Cø7 or Cm7♭5)

The name is historical: it is diminished **only half way** — the triad is diminished, but the seventh is an
ordinary minor seventh. The [[concept:diminished-seventh|diminished seventh]] is diminished **at both ends**
(its seventh sits a semitone lower).

| Chord | Triad | Seventh | Tritones |
|---|---|---|---|
| **half-diminished** | diminished | minor seventh | **1** (root and fifth) |
| **diminished seventh** | diminished | diminished seventh | **2** |

**One tritone versus two is the entire reason it sounds milder.**

## Where it lives

| Scale | Degree | Typical use |
|---|---|---|
| **major** | degree 7 (viiø7) | leading-tone chord resolving to I |
| **natural minor** | degree 2 (iiø7) | subdominant function resolving to V |

A major scale yields exactly one half-diminished seventh — which makes it among the easiest diatonic seventh
chords to recognise. In jazz **iiø7–V7–i** is the basic minor progression, with two seventh chords in it.

## Do not confuse it with the diminished seventh

The two differ in one note — and it is **the seventh**, not the fifth:

| | Notes from C |
|---|---|
| half-diminished | C–E♭–G♭–**B♭** |
| diminished seventh | C–E♭–G♭–**B𝄫** |

The difference is audible: the diminished seventh hangs in the air, while the half-diminished one clearly
**points somewhere**. It also makes a broader point: **how unstable a chord is depends on how many tritones it
contains.**

## Diagram: half diminished versus fully diminished

```svg
<svg viewBox="0 0 640 190" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Starting from the same diminished triad, the seventh's height decides "hanging" or "pointing"</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="26">E♭</text><text x="0" y="52">G♭</text><text x="0" y="78">B♭</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2"><line x1="12" y1="0" x2="12" y2="78"/></g>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">half-diminished: one tritone</text>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">points clearly, resolves smoothly</text>

    <g transform="translate(280,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#C0504A" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="26">E♭</text><text x="0" y="52">G♭</text><text x="0" y="78">B𝄫</text>
      </g>
      <g stroke="#C0504A" stroke-width="1.2"><line x1="12" y1="0" x2="12" y2="78"/></g>
      <g stroke="#C0504A" stroke-width="1.2" stroke-dasharray="3 2"><line x1="42" y1="0" x2="42" y2="78"/></g>
      <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">diminished seventh: two tritones</text>
      <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">hangs in mid-air, must resolve</text>
    </g>
  </g>
</svg>
```

## Listen: the half-diminished seventh

Hear how it sounds dark yet directional, then compare it with the diminished seventh.

```audiolab
{"type":"chord","root":"C4","quality":"hdim7","inversion":0,"label":"半减七和弦（C–E♭–G♭–B♭）","label_en":"Half-diminished seventh (C–E♭–G♭–B♭)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"Half-diminished is just the diminished seventh."** The seventh differs by a semitone and so does the tritone count (one versus two); the heard difference is clear.
- **"Half-diminished chords are rare."** They occur **naturally** on degree 7 in major and degree 2 in minor — they are diatonic chords.
- **"m7♭5 and ø7 are two different chords."** Two spellings of one chord: the first is pop notation, the second jazz notation.
- **"Any chord with a diminished fifth is extremely unstable."** It is far milder than the diminished seventh. Instability tracks the **number** of tritones.
:::
