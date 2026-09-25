---
id: fugue
site: theo
cat: T6
title: 赋格
title_en: Fugue
summary: 一个主题在几个声部依次进入，然后用它把整曲撑起来
summary_en: One subject enters in voice after voice, and then carries the whole piece
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [赋格, 赋格曲, fugue]
order: 26
links:
  - "[[concept:imitation]]"
  - "[[concept:canon]]"
  - "[[concept:counterpoint]]"
  - "[[concept:fugue-form]]"
  - "[[concept:motive]]"
  - "[[period:baroque]]"
instances:
  - atepp-001928 | 巴赫《半音阶幻想曲与赋格》：赋格段式的主题在声部间依次进入，是这一体裁最有名的实例之一 | Bach's Chromatic Fantasia and Fugue — the subject enters voice by voice, one of the best-known instances of the genre
  - atepp-000238 | 肖斯塔科维奇《前奏曲与赋格》Op.87：20 世纪的赋格写作，可听这一古老体裁的现代形态 | Shostakovich's Preludes and Fugues Op.87 — twentieth-century fugue writing, the old genre in modern dress
  - atepp-001254 | 肖邦的赋格：浪漫派作曲家也写赋格，可对照与巴洛克处理的差别 | A fugue by Chopin — Romantic composers wrote them too, a useful contrast with Baroque handling
sources:
  - 赋格由主题、答题、对题、间插段、密接和应等部件构成，属对位学通则
  - 答题通常在属调（五度）上进入；赋格是写法与织体，不是固定曲式，为通行乐理表述
updated: 2026-09-24
---

::: zh
赋格的做法是：**把一个主题在各声部依次交代一遍，然后用它把整首曲子撑起来。**

它的特别之处不在"用了什么"，而在**用得有多省**：

> **整首作品只靠一个主题（加上它的对题）发展出来。**
> 没有第二主题、没有对比段落式的"新材料" —— 一切都从同一个乐思长出来。

## 五个部件

| 部件 | 作用 |
|---|---|
| **主题**（subject） | 全曲的种子，通常短而有个性（一个鲜明的音程或节奏型） |
| **答题**（answer） | 主题在**另一个声部**的模仿进入；**通常在上方五度**（属调） |
| **对题**（countersubject） | 与答题**同时**出现的另一条旋律，此后常与主题成对出现 |
| **间插段**（episode） | 主题不在时，用主题的片段做**模进**推进，连接两次进入 |
| **密接和应**（stretto） | 主题的进入**互相交叠**，最紧凑的段落，常用于推向高潮 |

**答题为什么常是五度？** 因为属调是最近的调（见 [[concept:circle-of-fifths|五度圈]]）——
主 → 属的进入方式既明确了调性，又不需要任何变化音。这条选择不是随意规定的，
而是"最近的调"这一事实的必然结果。

## 赋格是"手法"，不是"曲式"

这是最容易搞错的一点：

| | 说明 |
|---|---|
| **赋格（本站 T6）** | 一种**写法与织体** —— 主题如何进入、如何交织、如何发展 |
| **赋格曲式（T9）** | 把这种写法组织成整曲时的**结构安排** |

所以"这首作品是不是赋格"不是看它有几个段落，而是看它**是否以单一主题的模仿进入为核心**
（见 [[concept:fugue-form|赋格曲式]]）。很多作品里会出现"赋格段"——
比如奏鸣曲式展开部里的一段严密模仿 —— 它不构成整曲的曲式，但确实是赋格写法。

## 为什么它被视为复调写作的顶点

三个理由，都是可验证的：

**① 经济性。** 素材只有一个，却撑起数分钟的music —— 这是作曲上最苛刻的考验（见 [[concept:motive|动机与主题]]）。

**② 双重约束。** 每条线必须像旋律，同时所有线合起来必须和声合理（见 [[concept:counterpoint|对位]]）。
约束越多，解越难找。

**③ 发展性。** 主题必须**既能独立成立、又留有余地** ——
太完整就无法发展，太空洞就立不住。这种"留白"的判断力，是赋格写作最难教的部分。

## 图示：主题在声部间依次进入

```svg
<svg viewBox="0 0 640 216" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">四个声部依次进入：主题 → 答题（五度）→ 主题 → 答题（五度）</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">
      <text x="-10" y="6">女高</text><text x="-10" y="32">女低</text>
      <text x="-10" y="58">男高</text><text x="-10" y="84">男低</text>
    </g>
    <g>
      <rect x="0" y="-4" width="110" height="18" rx="3" fill="#E07A3F"/>
      <text x="55" y="9" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">主题</text>
      <rect x="240" y="-4" width="110" height="18" rx="3" fill="#E07A3F" opacity=".8"/>
      <text x="295" y="9" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">主题</text>

      <rect x="120" y="22" width="110" height="18" rx="3" fill="#5B7FA8"/>
      <text x="175" y="35" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">答题</text>
      <rect x="360" y="22" width="110" height="18" rx="3" fill="#5B7FA8" opacity=".8"/>
      <text x="415" y="35" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">答题</text>

      <rect x="240" y="48" width="110" height="18" rx="3" fill="#E07A3F" opacity=".6"/>
      <text x="295" y="61" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">主题</text>

      <rect x="360" y="74" width="110" height="18" rx="3" fill="#5B7FA8" opacity=".6"/>
      <text x="415" y="87" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">答题</text>
    </g>
    <g stroke="#E8C547" stroke-width="1.2" stroke-dasharray="3 3">
      <line x1="470" y1="9" x2="560" y2="9"/>
      <line x1="470" y1="35" x2="560" y2="35"/>
    </g>
    <text x="470" y="106" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">其后 = 间插段（用主题片段模进推进）</text>
    <text x="0" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      答题通常在上方五度进入 —— 因为属调是最近的调，不需要任何变化音
    </text>
    <text x="0" y="156" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      整首作品只靠一个主题（加对题）发展：经济性、双重约束、发展性 —— 三条都成立的极少数写法
    </text>
  </g>
</svg>
```

## 听一听：五度进入的关系

赋格的核心动作是"主题在五度上被模仿"。用 `interval` 听这个五度 ——
**主与属的关系**就是赋格最初两次进入之间的距离。真正的四声部交织请到实例里听：
巴赫《半音阶幻想曲与赋格》（`atepp-001928`）是最完整的一条。

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"主题与答题之间的距离：纯五度","label_en":"The distance between subject and answer: a perfect fifth","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 C5 则是八度进入 —— 赋格里也有，但五度进入更能确立调性。","hint2_en":"Set b to C5 for entry at the octave — which also occurs, though the fifth establishes the key more firmly."}
```

## 常见误解

- **「赋格是一种曲式」** → 它是**写法与织体**。看一首作品是不是赋格，要看它是否以单一主题的模仿进入为核心，而不是看段落数量（结构层面见 [[concept:fugue-form|赋格曲式]]）。
- **「赋格必须四个声部」** → 二声部到五声部都有。声部数由织体需要决定，不是定义的一部分。
- **「主题进入的顺序是固定的」** → 常见的是从中间声部开始、向外扩展，但大量作品不遵循这一顺序。
- **「赋格是过时的形式」** → 20 世纪仍有人写（如肖斯塔科维奇 Op.87 全套 24 首），因为它训练的是"用一个素材发展到底"的能力，这在任何时代都有用。
:::

::: en
A fugue works like this: **state one subject in voice after voice, then let it carry the whole piece.**

What sets it apart is not what it uses but **how little it uses**:

> **An entire work grows from a single subject (plus its countersubject).** No second subject, no
> contrasting "new material" — everything comes out of one idea.

## The five components

| Component | Function |
|---|---|
| **subject** | the seed of the piece, usually short and distinctive (a striking interval or rhythmic figure) |
| **answer** | the subject's imitative entry in **another voice**, **usually a fifth above** (the dominant key) |
| **countersubject** | a second line sounding **simultaneously** with the answer, thereafter often paired with the subject |
| **episode** | where the subject is absent, fragments of it are pushed along by **sequence**, linking two entries |
| **stretto** | entries **overlapping** one another — the tightest passage, often driving to a climax |

**Why is the answer usually a fifth above?** Because the dominant is the closest key (see
[[concept:circle-of-fifths|circle of fifths]]) — tonic-to-dominant establishes the key without needing a single
accidental. The choice is not an arbitrary rule but a consequence of "the nearest key".

## A fugue is a technique, not a form

This is the most frequent confusion:

| | Explanation |
|---|---|
| **fugue (this site, T6)** | a **way of writing and a texture** — how the subject enters, interweaves and develops |
| **fugue form (T9)** | the **structural arrangement** when that writing is organised across a whole piece |

So "is this a fugue" is not answered by counting sections but by asking whether it **turns on imitative entries
of a single subject** (see [[concept:fugue-form|fugue form]]). Many works contain a "fugal passage" — a tightly
imitative stretch inside a development section, for instance — which is fugal writing without being a fugue form.

## Why it is regarded as the summit of polyphonic writing

Three reasons, all verifiable:

**One: economy.** One idea carries minutes of music — the most demanding test in composition (see
[[concept:motive|motive and subject]]).

**Two: double constraint.** Each line must work as a melody while all lines together must work as harmony (see
[[concept:counterpoint|counterpoint]]). More constraints, fewer solutions.

**Three: capacity for development.** The subject must **stand on its own yet leave room** — too complete and it
cannot develop, too empty and it collapses. Judging that "leave room" is the hardest part of fugue writing to
teach.

## Diagram: the subject entering voice by voice

```svg
<svg viewBox="0 0 640 216" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Four voices enter in turn: subject, answer (a fifth), subject, answer (a fifth)</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">
      <text x="-10" y="6">S</text><text x="-10" y="32">A</text>
      <text x="-10" y="58">T</text><text x="-10" y="84">B</text>
    </g>
    <g>
      <rect x="0" y="-4" width="110" height="18" rx="3" fill="#E07A3F"/>
      <text x="55" y="9" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">subject</text>
      <rect x="240" y="-4" width="110" height="18" rx="3" fill="#E07A3F" opacity=".8"/>
      <text x="295" y="9" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">subject</text>

      <rect x="120" y="22" width="110" height="18" rx="3" fill="#5B7FA8"/>
      <text x="175" y="35" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">answer</text>
      <rect x="360" y="22" width="110" height="18" rx="3" fill="#5B7FA8" opacity=".8"/>
      <text x="415" y="35" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">answer</text>

      <rect x="240" y="48" width="110" height="18" rx="3" fill="#E07A3F" opacity=".6"/>
      <text x="295" y="61" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">subject</text>

      <rect x="360" y="74" width="110" height="18" rx="3" fill="#5B7FA8" opacity=".6"/>
      <text x="415" y="87" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">answer</text>
    </g>
    <g stroke="#E8C547" stroke-width="1.2" stroke-dasharray="3 3">
      <line x1="470" y1="9" x2="560" y2="9"/>
      <line x1="470" y1="35" x2="560" y2="35"/>
    </g>
    <text x="470" y="106" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">then: episodes, pushing subject fragments by sequence</text>
    <text x="0" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      The answer usually enters a fifth above — the nearest key, so no accidental is needed
    </text>
    <text x="0" y="156" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      A whole piece from one subject: economy, double constraint, capacity for development
    </text>
  </g>
</svg>
```

## Listen: the fifth between entries

The central action of a fugue is "the subject imitated a fifth higher". Use `interval` to hear that fifth — **the
relation of tonic and dominant** is the distance between the fugue's first two entries. For real four-voice
weaving go to the instances: Bach's Chromatic Fantasia and Fugue (`atepp-001928`) is the most complete.

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"主题与答题之间的距离：纯五度","label_en":"The distance between subject and answer: a perfect fifth","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 C5 则是八度进入 —— 赋格里也有，但五度进入更能确立调性。","hint2_en":"Set b to C5 for entry at the octave — which also occurs, though the fifth establishes the key more firmly."}
```

## Common misconceptions

- **"A fugue is a form."** It is a **way of writing and a texture**. Whether a piece is a fugue depends on
  imitative entries of a single subject, not on how many sections it has (for the structural layer see
  [[concept:fugue-form|fugue form]]).
- **"A fugue must have four voices."** Two to five all occur. The voice count follows the texture, not the
  definition.
- **"The order of entries is fixed."** Starting from a middle voice and expanding outward is common, but many
  works ignore it.
- **"The fugue is obsolete."** It was still being written in the twentieth century (Shostakovich's complete set of
  24 in Op.87), because it trains the ability to develop one idea to the end — useful in any era.
:::
