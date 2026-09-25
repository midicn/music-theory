---
id: meter-notation
site: theo
cat: T10
title: 拍号写法
title_en: Writing Time Signatures
summary: 写在哪里、C 记号是什么、中途换拍号怎么写
summary_en: Where it goes, what the C sign means, and how to change metre mid-piece
level: standard
tags: [乐理, 记谱, 基础]
tags_en: [theory, notation, basics]
alias: [拍号写法, 拍号, C 记号, 换拍号]
order: 36
links:
  - "[[concept:meter]]"
  - "[[concept:simple-compound-meter]]"
  - "[[concept:clef]]"
  - "[[concept:key-signature]]"
  - "[[concept:staff]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：最常见的 4/4 写法，适合用来确认拍号的位置 | Scale and cadence exercises in the commonest 4/4 notation, useful for confirming where the signature sits
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：三拍子的写法贯穿全曲，可与 4/4 对照"分子不同"的效果 | Liszt's transcription of Danse macabre is in triple metre throughout, a contrast with 4/4
  - pdmx-000007 | 莫扎特第 40 交响曲 K.550：古典作品的标准谱面，拍号、调号、谱号的次序一目了然 | Mozart's Symphony No.40 K.550 — a standard Classical layout where the order of clef, key and metre is clear
sources:
  - 拍号写在谱号与调号之后、第一小节之前；中途更换写在新小节开头，为记谱法通则
  - C 与 ¢ 记号的历史来源（中世纪记谱符号）及其与现代 4/4、2/2 的对应，为音乐史与记谱法通行记载
updated: 2026-09-25
---

::: zh
[[concept:meter|拍号]] 讲的是原理；这一条讲**写法实务**。

## 写在哪里

谱面开头的**次序是固定的**：

> **谱号 → 调号 → 拍号 → 第一小节**

| 顺序 | 为什么 |
|---|---|
| 1. **谱号** | 先确定"哪条线是什么音"（见 [[concept:clef|谱号]]） |
| 2. **调号** | 再确定"哪些音默认升降"（见 [[concept:key-signature|调号]]） |
| 3. **拍号** | 最后确定"怎么数拍" |

**这个次序不是随意的**：从"音高位置"到"默认值"再到"时间组织"，
**每一步都建立在前一步之上**。

## 两个字母记号

谱面上有时不写数字，而写字母：

| 记号 | 等于 | 说明 |
|---|---|---|
| **C** | **4/4** | 常被解作 **common time**（"常用拍"），但它其实是**中世纪记谱符号的遗留**（"不完全拍"的记号），与"common"的巧合是后人的附会 |
| **¢**（C 加竖线） | **2/2** | 称 **alla breve**：读法上按"二分音符为一拍"，所以**每小节两拍** |

**第二行值得多看一眼**：`¢` 与 `C` 的**分子分母都不同**（2/2 与 4/4），
所以它们**不是同一种拍子**：`¢` 的拍单位更大（二分音符），听感上更"流动、更快"。

**关于 C 的来历**要说得准确：它源自中世纪的**拍号记号体系**（表示"不完全"的时值关系），
后来与 4/4 混同使用。**"common time"是后起的通俗解释，不是它的词源。**
（这类"术语与词源脱节"的情况在音乐里很常见，见 [[concept:compound-ternary|复三部曲式]] 里"三声中部"的名字。）

## 中途换拍号

作品中途改变节拍时：

| 做法 | 说明 |
|---|---|
| 在**新小节开头**写新拍号 | 标准做法 |
| 有时在**行末**写提示 | 让演奏者提前准备 |
| **单小节**换拍号 | 常见于不规则节拍段落与民间音乐 |

**第三行值得注意**：大量民歌与 20 世纪作品**频繁换拍号**（如一小节 3/4、下一小节 5/8）——
这时谱面上会**连续出现拍号**，读谱时要**每小节都确认**。

## 复合与不规则拍子的写法

| 类型 | 写法惯例 |
|---|---|
| **简单拍号** | `3/4` · `4/4` |
| **复合拍号** | `6/8` · `9/8`（每拍三分，见 [[concept:simple-compound-meter|单复混合拍子]]） |
| **不规则拍子** | 常写作 `3+2/8` 或 `5/8` 并在谱面用**连桁分组**提示 |

**不规则拍子的关键**：**拍号本身不足以说明分组方式**（5/8 可以是 3+2，也可以是 2+3），
所以作曲者要么**写成 `3+2/8`**，要么**用连桁把分组画出来**（见 [[concept:note-values|音符时值]] 里"连桁在画拍子"）。

**所以"拍号写法"不只是排版问题** —— 它承担着**把节拍结构说清楚**的任务。

## 图示：固定次序与两种字母记号

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">开头次序固定：谱号 → 调号 → 拍号；C 与 ¢ 不是同一种拍子</text>
  </g>

  <g transform="translate(52,58)">
    <g>
      <rect x="0" y="-12" width="90" height="24" rx="3" fill="#5B7FA8"/>
      <rect x="98" y="-12" width="90" height="24" rx="3" fill="#E8C547"/>
      <rect x="196" y="-12" width="90" height="24" rx="3" fill="#E07A3F"/>
      <rect x="294" y="-12" width="140" height="24" rx="3" fill="#343439"/>
      <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
        <text x="45" y="4" fill="#F2EEE6">谱号</text>
        <text x="143" y="4" fill="#1A0E06">调号</text>
        <text x="241" y="4" fill="#1A0E06">拍号</text>
        <text x="364" y="4" fill="#6E6A64">第一小节</text>
      </g>
      <g stroke="#343439" stroke-width="1.2" fill="none">
        <line x1="92" y1="0" x2="96" y2="0"/><line x1="190" y1="0" x2="194" y2="0"/><line x1="288" y1="0" x2="292" y2="0"/>
      </g>
    </g>

    <g transform="translate(0,54)">
      <g font-family="Georgia,serif" font-size="26" fill="#E8C547" text-anchor="middle">
        <text x="20" y="6">C</text>
        <text x="90" y="6">¢</text>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10.5">
        <text x="42" y="0" fill="#E8C547">= 4/4（"common time" 是后起解释，源自中世纪"不完全拍"符号）</text>
        <text x="112" y="0" fill="#5B7FA8">= 2/2（alla breve，拍单位更大）</text>
      </g>
    </g>

    <text x="0" y="100" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      不规则拍子（5/8 · 7/8）必须说明分组：写 3+2/8，或用连桁把分组画出来
    </text>
    <text x="0" y="122" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      所以"拍号写法"不只是排版问题 —— 它承担着把节拍结构说清楚的任务
    </text>
  </g>
</svg>
```

## 听一听：四拍与两拍的差别

`C`（4/4）与 `¢`（2/2）在**分子分母上都不同** —— 用 `rhythm` 对比四拍循环与两拍循环，
体会"拍单位更大"的听感差别（更流动）。这与 [[concept:meter|拍号]] 那条的演示互为补充。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":92,"label":"4/4（C）：每四拍一轮","label_en":"4/4 (C): one cycle every four beats","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"2/4","pattern":"q q","bpm":92,"label":"2/4：每两拍一轮（¢ 的拍单位更大，听感更流动）","label_en":"2/4: two beats per cycle — alla breve feels more flowing","hint":"与上一条对比：循环更短","hint_en":"Against the item above: a shorter cycle"}
```

## 常见误解

- **「C 是 common time 的缩写」** → 它源自**中世纪记谱符号**（"不完全拍"），"common time" 是后起的通俗解释，**不是词源**。
- **「¢ 与 C 是同一种拍子」** → **2/2 与 4/4 不同**：`¢` 的拍单位是二分音符，听感更流动。
- **「5/8 一看就知道怎么数」** → 不够：可能是 3+2 也可能是 2+3，**必须靠 `3+2/8` 的写法或连桁分组确定**。
- **「拍号只写一次」** → 频繁换拍号很常见（民歌、20 世纪作品），读谱要**每小节确认**。
:::

::: en
[[concept:meter|Metre]] covered the principle; this entry covers **notational practice**.

## Where it goes

The order at the head of a score is **fixed**:

> **clef → key signature → time signature → first bar**

| Order | Why |
|---|---|
| 1. **clef** | first fix which line is which note (see [[concept:clef|clef]]) |
| 2. **key signature** | then fix which notes are altered by default (see [[concept:key-signature|key signature]]) |
| 3. **time signature** | finally fix how beats are counted |

**The order is not arbitrary**: from pitch positions, to defaults, to the organisation of time — **each step builds
on the one before.**

## The two letter signs

Sometimes a letter appears instead of numerals:

| Sign | Equals | Note |
|---|---|---|
| **C** | **4/4** | commonly read as **common time**, but it is in fact **a remnant of medieval notation** (the sign for "imperfect time"); the pun with "common" is a later rationalisation |
| **¢** (C with a stroke) | **2/2** | called **alla breve**: read with the half note as the beat, hence two beats per bar |

**The second row deserves a second look**: `¢` and `C` **differ in both numerator and denominator** (2/2 against
4/4), so **they are not the same metre**: `¢` has a larger beat unit and sounds more flowing, faster.

**On the origin of C, be precise**: it descends from the **medieval system of mensural signs** (denoting imperfect
duration), later used interchangeably with 4/4. **"Common time" is a later folk explanation, not its etymology.**
(These gaps between a term and its origin are common in music — see the name "trio" under
[[concept:compound-ternary|compound ternary form]].)

## Changing metre mid-piece

When the metre changes partway through:

| Practice | Note |
|---|---|
| write the new signature at the **start of the new bar** | the standard |
| sometimes mark it at the **end of the preceding system** | gives the performer warning |
| a change for **a single bar** | common in irregular metres and folk music |

**The third row matters**: much folk music and many twentieth-century works **change metre frequently** (3/4 in one
bar, 5/8 in the next), so the page shows a **run of signatures** and the reader must **confirm every bar**.

## Writing compound and irregular metres

| Type | Convention |
|---|---|
| **simple** | `3/4`, `4/4` |
| **compound** | `6/8`, `9/8` (each beat divided in three, see [[concept:simple-compound-meter|simple, compound and irregular metre]]) |
| **irregular** | often written `3+2/8` or `5/8`, with **beaming** to show the grouping |

**The key to irregular metres**: **the signature alone does not tell you the grouping** (5/8 may be 3+2 or 2+3), so
the composer either **writes `3+2/8`** or **draws the grouping with beams** (see "beaming draws the beats" under
[[concept:note-values|note values]]).

**So "writing a time signature" is not merely typesetting** — it carries the job of **making the metrical structure
clear**.

## Diagram: fixed order and the two letter signs

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The head order is fixed: clef, key, metre; and C and ¢ are not the same metre</text>
  </g>

  <g transform="translate(52,58)">
    <g>
      <rect x="0" y="-12" width="90" height="24" rx="3" fill="#5B7FA8"/>
      <rect x="98" y="-12" width="90" height="24" rx="3" fill="#E8C547"/>
      <rect x="196" y="-12" width="90" height="24" rx="3" fill="#E07A3F"/>
      <rect x="294" y="-12" width="140" height="24" rx="3" fill="#343439"/>
      <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
        <text x="45" y="4" fill="#F2EEE6">clef</text>
        <text x="143" y="4" fill="#1A0E06">key</text>
        <text x="241" y="4" fill="#1A0E06">metre</text>
        <text x="364" y="4" fill="#6E6A64">first bar</text>
      </g>
      <g stroke="#343439" stroke-width="1.2">
        <line x1="92" y1="0" x2="96" y2="0"/><line x1="190" y1="0" x2="194" y2="0"/><line x1="288" y1="0" x2="292" y2="0"/>
      </g>
    </g>

    <g transform="translate(0,54)">
      <g font-family="Georgia,serif" font-size="26" fill="#E8C547" text-anchor="middle">
        <text x="20" y="6">C</text>
        <text x="90" y="6">¢</text>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10.5">
        <text x="42" y="0" fill="#E8C547">= 4/4; "common time" is later rationalisation of a medieval sign</text>
        <text x="112" y="0" fill="#5B7FA8">= 2/2 (alla breve), a larger beat unit</text>
      </g>
    </g>

    <text x="0" y="100" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Irregular metres need the grouping stated: write 3+2/8, or draw it with beams
    </text>
    <text x="0" y="122" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      So writing a signature is not typesetting: it makes the metrical structure clear
    </text>
  </g>
</svg>
```

## Listen: four beats against two

`C` (4/4) and `¢` (2/2) differ in **both numerator and denominator** — use `rhythm` to compare a four-beat cycle
with a two-beat one and hear the larger beat unit (more flowing). This complements the demonstration under
[[concept:meter|metre]].

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":92,"label":"4/4（C）：每四拍一轮","label_en":"4/4 (C): one cycle every four beats","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"2/4","pattern":"q q","bpm":92,"label":"2/4：每两拍一轮（¢ 的拍单位更大，听感更流动）","label_en":"2/4: two beats per cycle — alla breve feels more flowing","hint":"与上一条对比：循环更短","hint_en":"Against the item above: a shorter cycle"}
```

## Common misconceptions

- **"C is short for common time."** It descends from **medieval mensural signs** (imperfect time); "common time" is
  a later folk explanation, **not the etymology**.
- **"¢ and C are the same metre."** **2/2 and 4/4 differ**: `¢` takes the half note as the beat and feels more
  flowing.
- **"5/8 tells you how to count."** It does not: it may be 3+2 or 2+3, and **`3+2/8` or the beaming must settle
  it**.
- **"A signature is written once."** Frequent changes are common (folk music, twentieth-century works), so **confirm
  every bar**.
:::
