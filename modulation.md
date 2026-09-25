---
id: modulation
site: theo
cat: T5
title: 转调
title_en: Modulation
summary: 调性中心搬家——近关系平滑，远关系突兀，全看怎么过渡
summary_en: Moving the tonal centre — smooth between close keys, abrupt between distant ones, and it all depends on the transition
level: core
tags: [乐理, 和声, 调性]
tags_en: [theory, harmony, tonality]
alias: [转调, 调性转换, modulation]
order: 20
links:
  - "[[concept:tonal-center]]"
  - "[[concept:circle-of-fifths]]"
  - "[[concept:secondary-dominant]]"
  - "[[concept:tonicization]]"
  - "[[concept:enharmonic]]"
instances:
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：半音化和声让调性不断漂移，是"远关系转调"的集中展示 | Liszt's transcription of Danse macabre — chromatic harmony keeps the key drifting, a concentration of distant modulations
  - atepp-000318 | a 小调奏鸣曲：乐章内部的转调把段落区分开来，可听中心如何被搬走又搬回 | A sonata in A minor — internal modulations separate the sections; hear the centre moved away and back
  - pdmx-000607 | 《小星星变奏曲》：变奏之间常有调性变化，可听同一主题在不同调上的效果差别 | Mozart's Ah vous variations — the key changes between variations, showing one theme in different keys
sources:
  - 转调指调性中心的转移；近关系调为相差一个升降号的调，属和声学通则
  - 共同和弦、副属和弦、等音重解是常用转调手段，为通行和声学表述
updated: 2026-09-24
---

::: zh
转调就是**把调性中心搬走**。它和 [[concept:tonicization|离调]]的区别不是手段，而是**时长与深度**：

| | 离调 | 转调 |
|---|---|---|
| 停留时间 | 几个和弦 | 一段完整的音乐 |
| 是否建立新中心 | 借一下，随即回来 | **确实建立** |
| 效果 | 色彩变化 | 结构变化 |

## 近关系与远关系

调与调之间的距离，用 [[concept:circle-of-fifths|五度圈]] 量最清楚：

| 关系 | 调号差 | 共同音 | 转调难度 |
|---|---|---|---|
| **近关系** | 相差 1 个升降号 | 6 个音相同 | 平滑 |
| **较远** | 相差 2–3 个 | 4–5 个相同 | 需要过渡 |
| **远关系** | 相差更多 | 很少 | 需要中介或等音手法 |

"近关系"之所以平滑，原因很朴素：**两个调共用的音多，不需要变化音就能过渡**。
所谓"关系大调 / 关系小调"（如 C 大调与 a 小调）就是**共用同一个调号**的那种最近关系。

## 三种常用手段

**① 共同和弦**（最平滑）
用一个**两个调都有的和弦**当桥梁，先把它听成旧调里的某级，再把它听成新调里的另一级。

**② 副属和弦**
在目标调前面放一个属和弦，直接"预告"新中心（见 [[concept:secondary-dominant|副属和弦]]）。

**③ 等音重解**（最突然）
同一个音或同一个和弦，换个写法就属于另一个调 ——
例如减七和弦、增三和弦这些对称结构，改一个解释方向就转过去了（见 [[concept:enharmonic|等音]]）。

## 转调在结构上的作用

转调不只是"换调"，它是**曲式的主要分界手段**：

- **奏鸣曲式**的展开部几乎就是"不断转调"；
- **三段体**的中段常用对比调性；
- **变奏曲**的变奏之间常换调，以制造新鲜感。

换句话说：**调性布局 = 结构的地图**。

## 图示：五度圈上的距离

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">从 C 出发：近关系只需走一步，远关系要走好几步</text>
  </g>

  <g transform="translate(52,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="70" y="0">G</text><text x="140" y="0">D</text>
      <text x="210" y="0">A</text><text x="280" y="0">E</text><text x="350" y="0">B</text>
      <text x="430" y="0">…</text>
    </g>
    <g stroke="#343439" stroke-width="1.2"><line x1="0" y1="14" x2="350" y2="14"/></g>
    <g stroke="#5B7FA8" stroke-width="1.6">
      <line x1="0" y1="34" x2="70" y2="34"/>
      <line x1="0" y1="30" x2="0" y2="38"/><line x1="70" y1="30" x2="70" y2="38"/>
    </g>
    <text x="80" y="38" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">近关系：相差 1 个调号</text>
    <g stroke="#E8C547" stroke-width="1.6">
      <line x1="0" y1="56" x2="210" y2="56"/>
      <line x1="0" y1="52" x2="0" y2="60"/><line x1="210" y1="52" x2="210" y2="60"/>
    </g>
    <text x="220" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">较远：相差 2–3 个</text>
    <g stroke="#C0504A" stroke-width="1.6">
      <line x1="0" y1="78" x2="350" y2="78"/>
      <line x1="0" y1="74" x2="0" y2="82"/><line x1="350" y1="74" x2="350" y2="82"/>
    </g>
    <text x="360" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">远关系：需要中介</text>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      近关系平滑的原因很朴素：两个调共用的音多，不需要变化音就能过渡
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      关系大调 / 关系小调（C 大调 ↔ a 小调）= 共用同一个调号，最近的一种
    </text>
  </g>
</svg>
```

## 听一听：两种过渡

用五度圈组件点几个相邻与不相邻的调，对比"一步之遥"与"绕远路"的听感差别。

```audiolab
{"type":"circle","label":"五度圈：点任意一格听该调","label_en":"Circle of fifths — click any segment","hint":"先点 C，再点相邻的 G，最后点对面的 F♯","hint_en":"Try C, then the neighbouring G, then the opposite F♯"}
```

## 常见误解

- **「转调与离调是同一件事」** → 离调是"借一下就走"，转调是"确实建立新中心"。区别在时长与深度，不在手段。
- **「转调必须用变化音」** → 近关系转调常常一个变化音都不用，全靠共同和弦。
- **「关系小调就是同一个调」** → 调号相同，但中心不同（C 与 a 是两个中心），因此是两个调。
- **「转调越突然越好」** → 突然的转调是有意为之的效果（如等音重解）。多数情况下作曲家会安排过渡，让听者跟得上。
:::

::: en
Modulation is **moving the tonal centre**. Its difference from [[concept:tonicization|tonicization]] is not the
technique but **duration and depth**:

| | Tonicization | Modulation |
|---|---|---|
| How long it lasts | a few chords | a whole passage |
| Does it establish a new centre? | borrows one, then returns | **yes, it establishes one** |
| Effect | a change of colour | a change of structure |

## Close and distant keys

The distance between keys is measured most clearly on the [[concept:circle-of-fifths|circle of fifths]]:

| Relation | Key signature difference | Shared notes | Difficulty |
|---|---|---|---|
| **close** | one sharp or flat apart | six notes in common | smooth |
| **moderately distant** | two or three apart | four or five in common | needs preparation |
| **distant** | further apart | few | needs a pivot or an enharmonic device |

The reason close keys are smooth is plain: **they share many notes, so no accidentals are needed to move across.**
"Relative major and minor" (C major and A minor) are the closest relation of all — they **share one signature.**

## Three common devices

**One: common chord** (smoothest). Use a chord that **exists in both keys** as a bridge: first hear it as a degree
of the old key, then reinterpret it as a degree of the new one.

**Two: secondary dominant.** Place a dominant chord of the target key in front of it, announcing the new centre
(see [[concept:secondary-dominant|secondary dominant]]).

**Three: enharmonic reinterpretation** (most abrupt). The same note or chord, respelled, belongs to another key —
symmetrical structures such as the diminished seventh or augmented triad turn with a change of interpretation (see
[[concept:enharmonic|enharmonic]]).

## What modulation does structurally

Modulation is not merely "changing key"; it is **the main way form is divided**:

- the development section of **sonata form** is little more than continuous modulation;
- the middle section of a **ternary form** typically uses a contrasting key;
- **variation sets** often change key between variations for freshness.

In other words: **the tonal plan is the map of the structure.**

## Diagram: distances on the circle

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Starting from C: close keys are one step away, distant ones several</text>
  </g>

  <g transform="translate(52,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="70" y="0">G</text><text x="140" y="0">D</text>
      <text x="210" y="0">A</text><text x="280" y="0">E</text><text x="350" y="0">B</text>
      <text x="430" y="0">…</text>
    </g>
    <g stroke="#343439" stroke-width="1.2"><line x1="0" y1="14" x2="350" y2="14"/></g>
    <g stroke="#5B7FA8" stroke-width="1.6">
      <line x1="0" y1="34" x2="70" y2="34"/>
      <line x1="0" y1="30" x2="0" y2="38"/><line x1="70" y1="30" x2="70" y2="38"/>
    </g>
    <text x="80" y="38" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">close: one signature apart</text>
    <g stroke="#E8C547" stroke-width="1.6">
      <line x1="0" y1="56" x2="210" y2="56"/>
      <line x1="0" y1="52" x2="0" y2="60"/><line x1="210" y1="52" x2="210" y2="60"/>
    </g>
    <text x="220" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">moderately distant: two or three</text>
    <g stroke="#C0504A" stroke-width="1.6">
      <line x1="0" y1="78" x2="350" y2="78"/>
      <line x1="0" y1="74" x2="0" y2="82"/><line x1="350" y1="74" x2="350" y2="82"/>
    </g>
    <text x="360" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">distant: needs a pivot</text>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Close keys are smooth for a plain reason: they share many notes, so no accidentals are needed
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Relative major and minor (C major with A minor) share one signature — the closest relation there is
    </text>
  </g>
</svg>
```

## Listen: two kinds of transition

Use the circle-of-fifths component to click neighbouring and non-neighbouring keys, comparing "one step away" with
"the long way round".

```audiolab
{"type":"circle","label":"五度圈：点任意一格听该调","label_en":"Circle of fifths — click any segment","hint":"先点 C，再点相邻的 G，最后点对面的 F♯","hint_en":"Try C, then the neighbouring G, then the opposite F♯"}
```

## Common misconceptions

- **"Modulation and tonicization are the same thing."** Tonicization borrows and leaves; modulation establishes a new centre. The difference is duration and depth, not technique.
- **"Modulation requires accidentals."** Close-key modulations often use none at all, relying on common chords.
- **"A relative minor is the same key."** Same signature, different centre (C and A are two centres), so two keys.
- **"The more abrupt the modulation the better."** Abruptness is a deliberate effect (enharmonic rewriting). Usually the composer prepares the listener.
:::
