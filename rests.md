---
id: rests
site: theo
cat: T10
title: 休止符
title_en: Rests
summary: 休止符不是"空白"，它是音乐的一部分——呼吸、期待与清空
summary_en: A rest is not blank space but part of the music — breath, expectation and clearing
level: standard
tags: [乐理, 记谱, 实践]
tags_en: [theory, notation, practice]
alias: [休止符, 休止, rests]
order: 18
links:
  - "[[concept:note-values]]"
  - "[[concept:breath-phrasing]]"
  - "[[concept:rhythm]]"
  - "[[concept:climax]]"
  - "[[concept:non-chord-tone-treatment]]"
instances:
  - mutopia-000049 | 《绿袖子》加固定低音：句与句之间常有短暂停顿，正是休止造成的句读 | Greensleeves to a Ground — brief silences between phrases produce the punctuation
  - cyberhymnal-000695 | 管风琴圣咏：诗句之间靠休止断开，休止与文字结构一致 | An organ hymn breaks between verse lines with rests, matching the words' structure
  - giantmidi-006222 | 音阶与终止练习：音与音之间不间断，可作对照，体会"有休止"与"无休止"的差别 | Scale exercises run continuously, a useful contrast for feeling the difference a rest makes
sources:
  - 休止符的时值体系与音符一一对应；全休止符兼作整小节休止，为记谱法通则
  - 休止作为句读、期待与织体手段的功能，为通行演奏与作曲教学表述
updated: 2026-09-25
---

::: zh
休止符最容易被当成"没什么可写的地方"。但它和音符一样是**内容**：

> **休止是音乐的一部分，不是音乐的缺席。**

## 时值体系：与音符一一对应

| 休止符 | 名称 | 等于 |
|---|---|---|
| 𝄻 | 全休止 | 全音符的时值 |
| 𝄼 | 二分休止 | 二分音符的时值 |
| 𝄽 | 四分休止 | 四分音符的时值 |
| 𝄾 | 八分休止 | 八分音符的时值 |
| 𝄿 | 十六分休止 | 十六分音符的时值 |

**一个实务规则**：**全休止符兼作"整小节休止"** ——
不论拍号是 2/4、3/4 还是 4/4，**一整个小节不发声就写一个全休止符**。
（这一点容易让初学者困惑：3/4 里"一整个小节"明明是三拍，为什么写一个"四拍"的符号？——
因为在这里它表示的是"**整小节**"这个结构概念，而不是具体拍数。）

## 它在音乐里做三件事

| 功能 | 说明 |
|---|---|
| **呼吸与句读** | 休止是最明确的句读手段之一（见 [[concept:breath-phrasing|呼吸与句读]]） |
| **制造期待** | 停下来，听者立刻开始等下文 —— 这是最省力的张力手段之一 |
| **清空织体** | 突然全体休止，让下一个进入显得格外醒目 |

**第二行值得展开**：与"加东西"相比，**"减东西"制造紧张往往更有效** ——
因为听者的注意力会自动去填补空缺（见 [[concept:climax|高潮设计]] 里"累积"的讨论）。

## 休止的写法实务

| 情况 | 做法 |
|---|---|
| 声部**整小节**不发声 | 写一个全休止符（见上） |
| 多声部里某声部休止 | 休止符写在**该声部的位置**上，不能与其他声部混在一起 |
| 长休止（多个小节） | 用**多小节休止**记号（含数字），不必逐小节写 |
| 附点休止 | 与附点音符同理，延长自身一半 |

**第二行的规则很实用**：多声部乐谱里，**休止符的位置本身就是"声部在哪里"的提示** ——
所以休止符必须与它所休止的那个声部**对齐**（垂直位置）。

## 一个演奏上的要点

休止符**不等于"随便停下来"**：

> **它的时值必须精确** —— 休止和音符一样占时间。

作曲者写一个二分休止符，意思是"这里静默两拍"，而不是"这里自由处理"。
（**例外**是有明确标记的延长记号 `𝄐` 或自由节拍段落，见 [[concept:free-meter|自由节拍与散板]]。）

## 图示：休止做的三件事

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">休止不是"缺席"，而是三种主动的手段</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">
      <text x="0" y="0">① 呼吸与句读</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="12" width="70" height="16" rx="2"/>
      <rect x="92" y="12" width="70" height="16" rx="2"/>
    </g>
    <g stroke="#343439" stroke-width="1.4" stroke-dasharray="3 3">
      <line x1="76" y1="8" x2="76" y2="32"/>
    </g>
    <text x="86" y="24" font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64" text-anchor="middle">休止</text>
    <text x="176" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">← 最明确的句读手段之一</text>

    <g transform="translate(0,58)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">
        <text x="0" y="0">② 制造期待</text>
      </g>
      <g fill="#343439" opacity=".8">
        <rect x="0" y="12" width="46" height="16" rx="2"/>
      </g>
      <text x="56" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">停下后，听者立即开始等下文 —— 最省力的张力手段</text>
    </g>

    <g transform="translate(0,110)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">
        <text x="0" y="0">③ 清空织体</text>
      </g>
      <g fill="#5B7FA8" opacity=".7">
        <rect x="0" y="12" width="46" height="16" rx="2"/>
      </g>
      <text x="56" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">突然全体休止，下一个进入会格外醒目</text>
    </g>

    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      与"加东西"相比，"减东西"制造紧张往往更有效（听者会自动去填补空缺）
    </text>
  </g>
</svg>
```

## 听一听：有休止与无休止

用 `rhythm` 对比**连续均分**与**留有空白**的形态。两者总时长相同 ——
**但"留白"那一档的期待感完全不同**（见 [[concept:breath-phrasing|呼吸与句读]]）。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"不留空白（连续均分）","label_en":"No gaps — continuous even quarters","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q h","bpm":88,"label":"后半留白（期待感出现）","label_en":"A gap in the second half — expectation appears","hint":"与上一条对比：前面的音相同，后半留白","hint_en":"Against the item above: same opening, a gap after"}
```

## 常见误解

- **「休止就是"没有音乐"」** → 休止是**音乐的一部分**：它承担呼吸、期待与清空织体三种功能。
- **「休止符可以随便停」** → 它的时值必须**精确**（除非有延长记号或自由节拍标记）。
- **「3/4 里整小节休止要写三个四分休止符」** → 写**一个全休止符**即可：它在这里表示"整小节"这个结构概念。
- **「休止符的位置不重要」** → 多声部里休止符**必须与所在声部对齐**，它同时是"声部在哪里"的视觉提示。
:::

::: en
A rest is most easily mistaken for "somewhere with nothing to write". But it is **content**, just like a note:

> **A rest is part of the music, not the absence of music.**

## The value system: one to one with notes

| Rest | Name | Equals |
|---|---|---|
| 𝄻 | whole rest | the value of a whole note |
| 𝄼 | half rest | the value of a half note |
| 𝄽 | quarter rest | the value of a quarter |
| 𝄾 | eighth rest | the value of an eighth |
| 𝄿 | sixteenth rest | the value of a sixteenth |

**One practical rule**: a **whole rest also serves as a full-bar rest** — whatever the metre (2/4, 3/4 or 4/4), a
bar with no sound is written with a single whole rest. (This puzzles beginners: in 3/4 the whole bar is three beats,
so why a "four-beat" symbol? Because here it means the **structural concept** of "the whole bar", not a beat
count.)

## Three things a rest does

| Function | Explanation |
|---|---|
| **breath and phrasing** | a rest is one of the clearest means of punctuation (see [[concept:breath-phrasing|breathing and phrasing]]) |
| **creating expectation** | stop, and the listener immediately waits for what follows — one of the cheapest sources of tension |
| **clearing the texture** | a sudden full rest makes the next entry stand out sharply |

**The second deserves emphasis**: compared with adding material, **subtracting often creates tension more
effectively** — because the listener's attention automatically moves to fill the gap (see the discussion of
accumulation under [[concept:climax|designing a climax]]).

## Practical notation points

| Case | Practice |
|---|---|
| a part silent for **a whole bar** | one whole rest (see above) |
| one part resting in a multi-part texture | the rest is written **in that part's position**, not mixed with others |
| a long silence (several bars) | a **multi-bar rest** with a figure, rather than bar by bar |
| dotted rests | as with dotted notes: half the rest's own value added |

**The second row is very practical**: in a multi-part score, **the position of a rest is itself a cue to where a
part sits** — so rests must align with the part they silence.

## A performance point

A rest **does not mean "stop whenever you like"**:

> **Its value must be exact** — a rest occupies time just as a note does.

When a composer writes a half rest, the meaning is "two beats of silence here", not "handle this freely". (The
exception is an explicit fermata `𝄐` or a passage in free metre — see
[[concept:free-meter|free metre and sanban]].)

## Diagram: the three jobs of a rest

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">A rest is not an absence but three active devices</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">
      <text x="0" y="0">1 breath and phrasing</text>
    </g>
    <g fill="#5B7FA8">
      <rect x="0" y="12" width="70" height="16" rx="2"/>
      <rect x="92" y="12" width="70" height="16" rx="2"/>
    </g>
    <g stroke="#343439" stroke-width="1.4" stroke-dasharray="3 3">
      <line x1="76" y1="8" x2="76" y2="32"/>
    </g>
    <text x="176" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">one of the clearest punctuations</text>

    <g transform="translate(0,58)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">
        <text x="0" y="0">2 creating expectation</text>
      </g>
      <g fill="#343439" opacity=".8">
        <rect x="0" y="12" width="46" height="16" rx="2"/>
      </g>
      <text x="56" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">the listener waits at once — the cheapest tension</text>
    </g>

    <g transform="translate(0,110)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">
        <text x="0" y="0">3 clearing the texture</text>
      </g>
      <g fill="#5B7FA8" opacity=".7">
        <rect x="0" y="12" width="46" height="16" rx="2"/>
      </g>
      <text x="56" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">a sudden full rest makes the next entry stand out</text>
    </g>

    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Subtracting often creates tension better than adding: attention fills the gap by itself
    </text>
  </g>
</svg>
```

## Listen: with and without rests

Use `rhythm` to compare **continuous even quarters** with **a version that leaves a gap**. The total length is the
same — **but the sense of expectation is entirely different** (see [[concept:breath-phrasing|breathing and
phrasing]]).

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":88,"label":"不留空白（连续均分）","label_en":"No gaps — continuous even quarters","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q h","bpm":88,"label":"后半留白（期待感出现）","label_en":"A gap in the second half — expectation appears","hint":"与上一条对比：前面的音相同，后半留白","hint_en":"Against the item above: same opening, a gap after"}
```

## Common misconceptions

- **"A rest means there is no music."** A rest is **part of the music**, doing three jobs: breath, expectation and
  clearing the texture.
- **"You can stop however you like at a rest."** Its value is **exact** unless a fermata or a free-metre marking says
  otherwise.
- **"A full bar of rest in 3/4 takes three quarter rests."** A single whole rest serves: here it means the
  structural "whole bar".
- **"A rest's position does not matter."** In multi-part music a rest **must align with its part**; it doubles as a
  visual cue to where that part sits.
:::
