---
id: note-values
site: theo
cat: T10
title: 音符时值
title_en: Note Values
summary: 时值符号的读写实务——符干、符尾、附点与连桁的分组
summary_en: The practical reading and writing of note values — stems, flags, dots and beaming
level: standard
tags: [乐理, 记谱, 基础]
tags_en: [theory, notation, basics]
alias: [音符时值, 时值, 符尾, 附点, note values]
order: 16
links:
  - "[[concept:rhythmic-notation]]"
  - "[[concept:staff]]"
  - "[[concept:rests]]"
  - "[[concept:meter]]"
  - "[[concept:tuplet]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：谱面时值统一，最适合用来练"看符尾数时值" | Scale and cadence exercises use one value throughout, ideal for practising "count the flags"
  - thesession-019704 | 《小星星》：只用两种时值，附点与连桁的写法必要性一目了然 | Twinkle Little Star uses only two values, making the need for dots and beaming obvious
  - mutopia-000522 | 《欢乐颂》主题：句尾用较长时值"落地"，可看时值如何标记句读 | The Ode of Joy lands each phrase on a longer value, showing how durations mark phrasing
sources:
  - 时值以符尾数量递减（每加一条符尾时值减半）、附点延长自身一半，属记谱法通则
  - 连桁（beaming）按拍分组、符干方向按符头位置决定，为通行记谱规范
updated: 2026-09-25
---

::: zh
[[concept:rhythmic-notation|节奏记谱]] 讲的是原理（**比例，不是秒数**）；
这一条讲的是**符号本身的读写实务**。

## 时值链：每加一条符尾就减半

| 符号 | 名称 | 相对全音符 | 写法 |
|---|---|---|---|
| ○ | 全音符 | 1 | 只有空心符头 |
| ○+符干 | 二分音符 | 1/2 | 空心 + 符干 |
| ●+符干 | 四分音符 | 1/4 | 实心 + 符干 |
| ●+符干+1 尾 | 八分音符 | 1/8 | 加一条符尾 |
| ●+符干+2 尾 | 十六分音符 | 1/16 | 加两条 |
| +3 尾 | 三十二分音符 | 1/32 | 加三条 |

**整张表是同一个动作的重复** —— 记住"**符尾越多越短**"就够了，不必逐条背。

## 三条写读实务（最容易被忽略）

**① 符干方向：按符头位置决定。**
**符头在第三线以上，符干向下**；在第三线以下，符干向上。
（这条规则的意义是**让符干尽量留在谱面内**，减少视觉杂乱。）

**② 相邻的短音符用连桁（beam）连起来，并按拍分组。**

这是最重要的一条：

| 写法 | 读起来的差别 |
|---|---|
| 八个八分音符各带一条符尾 | 看不出拍的分组，读的人要自己数 |
| **按拍分成四组连桁**（每两个一组） | **一眼看出"每拍有两个音"** |

**所以连桁不只是省笔墨，它是在"画拍子"。** 这也是为什么同一串音按不同方式连桁，
读起来的难度差别很大 —— **写谱的人在用连桁告诉读谱的人"哪里是拍点"。**

**③ 附点延长自身的一半。**

| 写法 | 等于 |
|---|---|
| `♩.` | 四分 + 八分（1.5 拍） |
| `♪.` | 八分 + 十六分 |
| **复附点** `♩..` | 再延长四分之一（= 1.75 拍），较少见 |

**注意**：附点是延长**自身的一半**，不是"加一个固定长度"（见常见误解）。

## 跨小节与跨拍的长音怎么记

| 情况 | 做法 |
|---|---|
| 一个音要**跨过小节线** | **必须用延音线**（`♩~`）——不能写成一个超长音符 |
| 一个音跨过**拍点**（但未跨小节） | 通常也用延音线，以便看出拍的分组 |
| 同音重复 | 用延音线而不是重写符头（尤其是钢琴/弦乐的连奏） |

**第一条是硬规则**：小节线是重音周期的标记（见 [[concept:meter|拍号]]），
不能为了记谱方便把它"藏"起来。

## 图示：连桁在"画拍子"

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一串八分音符，连桁方式不同，读起来的难度完全不同</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-24" y="0" text-anchor="end">不分组的</text>
    </g>
    <g fill="#C0504A">
      <rect x="0" y="-9" width="16" height="16" rx="2"/><rect x="24" y="-9" width="16" height="16" rx="2"/>
      <rect x="48" y="-9" width="16" height="16" rx="2"/><rect x="72" y="-9" width="16" height="16" rx="2"/>
      <rect x="96" y="-9" width="16" height="16" rx="2"/><rect x="120" y="-9" width="16" height="16" rx="2"/>
      <rect x="144" y="-9" width="16" height="16" rx="2"/><rect x="168" y="-9" width="16" height="16" rx="2"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="8" y1="-14" x2="176" y2="-14"/>
    </g>
    <text x="196" y="-8" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">看不出拍的分组</text>

    <g transform="translate(0,52)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">
        <text x="-24" y="0" text-anchor="end">按拍分组</text>
      </g>
      <g fill="#E8C547">
        <rect x="0" y="-9" width="16" height="16" rx="2"/><rect x="24" y="-9" width="16" height="16" rx="2"/>
        <rect x="72" y="-9" width="16" height="16" rx="2"/><rect x="96" y="-9" width="16" height="16" rx="2"/>
        <rect x="144" y="-9" width="16" height="16" rx="2"/><rect x="168" y="-9" width="16" height="16" rx="2"/>
        <rect x="216" y="-9" width="16" height="16" rx="2"/><rect x="240" y="-9" width="16" height="16" rx="2"/>
      </g>
      <g stroke="#E8C547" stroke-width="1.4">
        <line x1="8" y1="-14" x2="32" y2="-14"/>
        <line x1="80" y1="-14" x2="104" y2="-14"/>
        <line x1="152" y1="-14" x2="176" y2="-14"/>
        <line x1="224" y1="-14" x2="248" y2="-14"/>
      </g>
      <text x="268" y="-8" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">一眼看出"每拍两个音"</text>
    </g>

    <text x="0" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      连桁不只是省笔墨，它是在"画拍子" —— 写谱的人用它告诉读谱的人"哪里是拍点"
    </text>
    <text x="0" y="114" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      符干方向：符头在第三线以上朝下、以下朝上 —— 目的是让符干留在谱面内
    </text>
    <text x="0" y="136" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      附点 = 延长自身的一半（不是加固定长度）；跨小节的长音必须用延音线
    </text>
  </g>
</svg>
```

## 听一听：时值长短的听感

用 `rhythm` 组件对比**四分均分**与**含附点、含八分**的音型。
请留意：**写谱时用的符号（附点/符尾）在听觉上就是"长短比例"** ——
这就是为什么读谱要"看形状"而不是"数秒数"（见 [[concept:rhythmic-notation|节奏记谱]]）。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"四分均分（最简单的时值组合）","label_en":"Four even quarters — the simplest combination","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"h q q","bpm":88,"label":"二分 + 两个四分（长—短—短的对比）","label_en":"A half plus two quarters — long, short, short","hint":"与上一条对比：总长度相同，形状不同","hint_en":"Against the item above: same total length, different shape"}
```

## 常见误解

- **「附点是"加一拍"」** → 附点延长**自身的一半**：`♩.` = 1.5 拍，`♪.` = 0.75 拍。
- **「连桁只是好写」** → 连桁的核心功能是**标出拍的分组**。同一串音换一种连桁，读谱难度立刻不同。
- **「跨小节的长音可以直接写一个大音符」** → 必须用**延音线**，否则破坏了小节线的重音标记。
- **「符干方向随便」** → 由符头位置决定，目的是把符干留在谱面内（第 3 线以上朝下）。
:::

::: en
[[concept:rhythmic-notation|Notating rhythm]] covered the principle (**proportions, not seconds**); this entry covers
the **practical reading and writing of the symbols themselves**.

## The chain of values: each flag halves it

| Symbol | Name | Relative to a whole | Written as |
|---|---|---|---|
| ○ | whole | 1 | hollow head only |
| ○ + stem | half | 1/2 | hollow head plus stem |
| ● + stem | quarter | 1/4 | filled head plus stem |
| ● + 1 flag | eighth | 1/8 | plus one flag |
| ● + 2 flags | sixteenth | 1/16 | plus two |
| + 3 flags | thirty-second | 1/32 | plus three |

**The whole table is one action repeated** — remembering "**more flags, shorter note**" is enough.

## Three practical points, commonly overlooked

**1. Stem direction follows the note head.** A head **on or above the third line takes a downward stem**; below it,
an upward stem. The purpose is **keeping stems inside the staff** and reducing visual clutter.

**2. Adjacent short notes are joined by beams, grouped by beat.**

This is the most important one:

| Notation | What reading it is like |
|---|---|
| eight eighths each with its own flag | no visible beat grouping; the reader must count |
| **beamed into four groups of two** | **"two notes per beat" is visible at a glance** |

**So beaming is not just economy — it draws the beats.** It is why the same notes beamed differently are much
harder or easier to read: **the notator is telling the reader where the beats fall.**

**3. A dot lengthens a note by half its own value.**

| Notation | Equals |
|---|---|
| `♩.` | quarter plus eighth (1.5 beats) |
| `♪.` | eighth plus sixteenth |
| **double dot** `♩..` | a further quarter (1.75 beats); rarer |

**Note**: a dot adds **half the note's own value**, not a fixed length.

## Notating long notes across beats and bars

| Case | Practice |
|---|---|
| a note **crossing a bar line** | **a tie is required** — never one oversized note |
| a note crossing a **beat** within a bar | usually tied as well, so the beat grouping stays visible |
| a repeated pitch | tied rather than re-struck (especially for legato on piano or strings) |

**The first is a hard rule**: bar lines mark the accent cycle (see [[concept:meter|metre]]) and must not be hidden
for notational convenience.

## Diagram: beaming draws the beats

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The same eight eighths, beamed differently, read very differently</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-24" y="0" text-anchor="end">ungrouped</text>
    </g>
    <g fill="#C0504A">
      <rect x="0" y="-9" width="16" height="16" rx="2"/><rect x="24" y="-9" width="16" height="16" rx="2"/>
      <rect x="48" y="-9" width="16" height="16" rx="2"/><rect x="72" y="-9" width="16" height="16" rx="2"/>
      <rect x="96" y="-9" width="16" height="16" rx="2"/><rect x="120" y="-9" width="16" height="16" rx="2"/>
      <rect x="144" y="-9" width="16" height="16" rx="2"/><rect x="168" y="-9" width="16" height="16" rx="2"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="8" y1="-14" x2="176" y2="-14"/>
    </g>
    <text x="196" y="-8" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">no visible beat grouping</text>

    <g transform="translate(0,52)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">
        <text x="-24" y="0" text-anchor="end">beamed by beat</text>
      </g>
      <g fill="#E8C547">
        <rect x="0" y="-9" width="16" height="16" rx="2"/><rect x="24" y="-9" width="16" height="16" rx="2"/>
        <rect x="72" y="-9" width="16" height="16" rx="2"/><rect x="96" y="-9" width="16" height="16" rx="2"/>
        <rect x="144" y="-9" width="16" height="16" rx="2"/><rect x="168" y="-9" width="16" height="16" rx="2"/>
        <rect x="216" y="-9" width="16" height="16" rx="2"/><rect x="240" y="-9" width="16" height="16" rx="2"/>
      </g>
      <g stroke="#E8C547" stroke-width="1.4">
        <line x1="8" y1="-14" x2="32" y2="-14"/>
        <line x1="80" y1="-14" x2="104" y2="-14"/>
        <line x1="152" y1="-14" x2="176" y2="-14"/>
        <line x1="224" y1="-14" x2="248" y2="-14"/>
      </g>
      <text x="268" y="-8" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">two notes per beat, at a glance</text>
    </g>

    <text x="0" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Beaming draws the beats: the notator tells the reader where the beat points are
    </text>
    <text x="0" y="114" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Stem direction: above the third line downward, below it upward
    </text>
    <text x="0" y="136" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      A dot adds half the note's own value; a note crossing a bar line needs a tie
    </text>
  </g>
</svg>
```

## Listen: how durations feel

Use `rhythm` to compare **four even quarters** with **a half plus two quarters**. Notice that the notation's symbols
(the dot, the flag) **are** the proportions you hear — which is why reading means reading **shapes**, not counting
seconds (see [[concept:rhythmic-notation|notating rhythm]]).

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"四分均分（最简单的时值组合）","label_en":"Four even quarters — the simplest combination","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"h q q","bpm":88,"label":"二分 + 两个四分（长—短—短的对比）","label_en":"A half plus two quarters — long, short, short","hint":"与上一条对比：总长度相同，形状不同","hint_en":"Against the item above: same total length, different shape"}
```

## Common misconceptions

- **"A dot adds one beat."** A dot adds **half the note's own value**: `♩.` is 1.5 beats, `♪.` is 0.75.
- **"Beaming is just for convenience."** Its core function is **showing the beat grouping**. Re-beaming the same
  notes changes how hard they are to read.
- **"A long note crossing a bar line can be written as one big note."** A **tie** is required, or the bar line's
  accent marking is destroyed.
- **"Stem direction is arbitrary."** It follows the note head's position, to keep stems inside the staff (downward
  from the third line up).
:::
