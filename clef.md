---
id: clef
site: theo
cat: T10
title: 谱号
title_en: Clef
summary: 谱号决定"哪条线是哪个音"——五线谱没有它就没有意义
summary_en: The clef decides which line is which note — without it a staff means nothing
level: core
tags: [乐理, 记谱, 基础]
tags_en: [theory, notation, basics]
alias: [谱号, 高音谱号, 低音谱号, 中音谱号, clef]
order: 12
links:
  - "[[concept:staff]]"
  - "[[concept:key-signature]]"
  - "[[concept:register]]"
  - "[[concept:octave]]"
  - "[[concept:pitch]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：谱面规整，可用来逐条确认"这个音在哪条线/哪个间上" | Scale and cadence exercises are regular enough to check line by line which line or space a note sits on
  - atepp-000083 | 斯克里亚宾第一钢琴奏鸣曲：大谱表（高低音谱号并用）的实例，可看两行谱号的分工 | Scriabin's Piano Sonata No.1 — a grand staff with treble and bass clefs, showing the division of labour
  - cyberhymnal-000695 | 管风琴圣咏：管风琴通常三行谱表（含踏板声部），谱号用法更清楚 | An organ hymn — the organ usually uses three staves including a pedal part, where the clef usage is clearest
sources:
  - 谱号以字母形状得名（G / F / C 谱号），其卷曲或方块所指的线即该音所在，为记谱法通则
  - 高音谱号第二线为 G4、低音谱号第四线为 F3、中音谱号第三线为 C4，为通行记谱规范
updated: 2026-09-25
---

::: zh
谱号做的事只有一件，但没有它五线谱就**完全失效**：

> **它规定"哪一条线是哪一个音"** —— 其余位置由此推出。

所以 [[concept:staff|五线谱]] 与谱号是**配套**的：前者给位置，后者把位置翻译成音高。

## 三种常用谱号

三种谱号的形状都来自**字母**，而字母的**关键部位恰好指着那条"基准线"**：

| 谱号 | 来自字母 | 基准线 | 该线是 | 常用于 |
|---|---|---|---|---|
| **高音谱号** | **G** | 第二线 | **G4** | 小提琴、长笛、右手、女高音 |
| **低音谱号** | **F** | 第四线（两点夹住） | **F3** | 大提琴、低音提琴、左手、男低音 |
| **中音谱号** | **C** | 第三线（方块中心） | **C4** | 中提琴 |

**形状的记忆法**：G 的**卷曲中心**落在第二线上；F 的**两个点**夹住第四线；
C 的**方块中心**落在第三条线上。**记住"关键部位指着哪条线"，就不必背表**。

## 为什么需要多种谱号

不是习惯问题，而是**功能选择**：

> **目的：让该乐器最常用的音区落在谱面中央，减少加线。**

| 若全部用高音谱号 | 后果 |
|---|---|
| 大提琴的低音区 | 大量下加线，难以阅读 |
| 低音提琴 | 更糟 |

所以谱号的选择标准是**"让谱面尽量不用加线"** ——
这也解释了为什么钢琴用**大谱表**（高音 + 低音谱号并用）：
**音域太宽，一个谱面装不下**（见 [[concept:register|音区与音域]]）。

## 一个容易搞错的补充：八度谱号

有时会在谱号上方看到 **`8`**（或 `8va`）：它表示**实际音高要高一个八度**。

| 写法 | 含义 |
|---|---|
| `8` 在谱号上 | 记谱比实际低一个八度 |
| `8` 在谱号下（`8vb`） | 记谱比实际高一个八度 |

它的用途与换谱号相同：**少画加线**。所以遇到它时，**不能照谱面直接读**。

## 图示：三种谱号的关键部位

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">形状来自字母；关键部位所指的那条线，就是它的基准音</text>
  </g>

  <g transform="translate(56,54)">
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="0" x2="180" y2="0"/><line x1="0" y1="16" x2="180" y2="16"/>
      <line x1="0" y1="32" x2="180" y2="32"/><line x1="0" y1="48" x2="180" y2="48"/>
      <line x1="0" y1="64" x2="180" y2="64"/>
      <line x1="230" y1="0" x2="410" y2="0"/><line x1="230" y1="16" x2="410" y2="16"/>
      <line x1="230" y1="32" x2="410" y2="32"/><line x1="230" y1="48" x2="410" y2="48"/>
      <line x1="230" y1="64" x2="410" y2="64"/>
      <line x1="460" y1="0" x2="640" y2="0"/><line x1="460" y1="16" x2="640" y2="16"/>
      <line x1="460" y1="32" x2="640" y2="32"/><line x1="460" y1="48" x2="640" y2="48"/>
      <line x1="460" y1="64" x2="640" y2="64"/>
    </g>

    <g transform="translate(30,0)">
      <text x="0" y="54" font-family="Georgia,serif" font-size="42" fill="#E07A3F">𝄞</text>
      <circle cx="30" cy="48" r="4" fill="#E07A3F"/>
      <text x="46" y="52" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">卷曲中心 → 第二线 = G</text>
      <text x="46" y="70" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">高音谱号</text>
    </g>
    <g transform="translate(250,0)">
      <text x="0" y="56" font-family="Georgia,serif" font-size="42" fill="#5B7FA8">𝄢</text>
      <g fill="#5B7FA8"><circle cx="3" cy="44" r="3"/><circle cx="3" cy="52" r="3"/></g>
      <text x="16" y="50" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">两点夹住 → 第四线 = F</text>
      <text x="16" y="70" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">低音谱号</text>
    </g>
    <g transform="translate(490,0)">
      <g fill="none" stroke="#E8C547" stroke-width="2">
        <path d="M-6,16 L14,16 L14,48 L-6,48 Z"/>
      </g>
      <text x="22" y="36" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">方块中心 → 第三线 = C</text>
      <text x="22" y="56" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">中音谱号</text>
    </g>

    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      选择谱号的标准是"让谱面尽量不用加线" —— 这是功能选择，不是习惯
    </text>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      钢琴用大谱表（高低音并用），正是因为音域太宽，一个谱面装不下
    </text>
  </g>
</svg>
```

## 听一听：同一位置、不同音高

本站无法演示谱面 —— 但可以听**同一个音名的两个八度**。
**谱面上的"同一个位置"，在不同谱号下正是这样的关系**（差一个八度或更多）。

```audiolab
{"type":"interval","a":"A3","b":"A4","label":"同音名、不同八度（谱号决定它是哪一个）","label_en":"Same note name, different octaves — the clef decides which","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"同一个 A 在不同谱号下写成不同位置；反过来说，同一个位置在不同谱号下也是不同的音高。","hint2_en":"The same A is written in different places under different clefs; conversely, the same position gives different pitches under different clefs."}
```

## 常见误解

- **「高音谱号是右手，低音谱号是左手」** → 谱号规定的是**音高位置**，与哪只手无关。左手也可以在高音谱号上记谱。
- **「谱号可以随便换」** → 换谱号会**改变每个位置的音高含义**，必须整段一致或有明确标示。
- **「五线谱自带你不知道的音高」** → 必须有谱号才成立；单独一张五线谱不传达音高。
- **「谱号上的 8 只是装饰」** → 它表示**实际音高差一个八度**，不能照谱面直读。
:::

::: en
The clef does one thing — and without it the staff **fails entirely**:

> **It specifies which line is which note**, and everything else follows from that.

So the [[concept:staff|staff]] and the clef are **a pair**: the staff gives positions, the clef translates
positions into pitches.

## The three common clefs

All three take their shape from a **letter**, and the letter's **key part points at the reference line**:

| Clef | From the letter | Reference line | That line is | Common for |
|---|---|---|---|---|
| **treble** | **G** | second line | **G4** | violin, flute, right hand, soprano |
| **bass** | **F** | fourth line (gripped by the dots) | **F3** | cello, double bass, left hand, bass |
| **alto** | **C** | third line (centre of the block) | **C4** | viola |

**How to remember**: the **centre of the G's curl** sits on the second line; the **two dots of the F** grip the
fourth line; the **centre of the C's block** sits on the third. **Remember which line the key part points at and
the table is unnecessary.**

## Why several clefs are needed

Not habit but **function**:

> **Purpose: put the instrument's most used register in the middle of the staff, reducing ledger lines.**

| If everything used the treble clef | Consequence |
|---|---|
| a cello's low register | many ledger lines below the staff, hard to read |
| double bass | worse still |

So the criterion is **"use the clef that needs the fewest ledger lines"** — which also explains why the piano uses a
**grand staff** (treble and bass together): **its range is simply too wide for one staff** (see
[[concept:register|register and range]]).

## One easily missed addition: the octave clef

Sometimes an **`8`** (or `8va`) appears above a clef, meaning **the sounding pitch is an octave higher**.

| Notation | Meaning |
|---|---|
| `8` above the clef | the notation is an octave below the sound |
| `8` below the clef (`8vb`) | the notation is an octave above the sound |

Its purpose is the same as changing clef: **fewer ledger lines**. So when you meet one, **you cannot read the staff
literally**.

## Diagram: the key part of each clef

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The shape comes from a letter; the line its key part points at is its reference pitch</text>
  </g>

  <g transform="translate(56,54)">
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="0" x2="180" y2="0"/><line x1="0" y1="16" x2="180" y2="16"/>
      <line x1="0" y1="32" x2="180" y2="32"/><line x1="0" y1="48" x2="180" y2="48"/>
      <line x1="0" y1="64" x2="180" y2="64"/>
      <line x1="230" y1="0" x2="410" y2="0"/><line x1="230" y1="16" x2="410" y2="16"/>
      <line x1="230" y1="32" x2="410" y2="32"/><line x1="230" y1="48" x2="410" y2="48"/>
      <line x1="230" y1="64" x2="410" y2="64"/>
      <line x1="460" y1="0" x2="640" y2="0"/><line x1="460" y1="16" x2="640" y2="16"/>
      <line x1="460" y1="32" x2="640" y2="32"/><line x1="460" y1="48" x2="640" y2="48"/>
      <line x1="460" y1="64" x2="640" y2="64"/>
    </g>

    <g transform="translate(30,0)">
      <text x="0" y="54" font-family="Georgia,serif" font-size="42" fill="#E07A3F">𝄞</text>
      <circle cx="30" cy="48" r="4" fill="#E07A3F"/>
      <text x="46" y="52" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">curl centre gives the second line = G</text>
      <text x="46" y="70" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">treble clef</text>
    </g>
    <g transform="translate(250,0)">
      <text x="0" y="56" font-family="Georgia,serif" font-size="42" fill="#5B7FA8">𝄢</text>
      <g fill="#5B7FA8"><circle cx="3" cy="44" r="3"/><circle cx="3" cy="52" r="3"/></g>
      <text x="16" y="50" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">dots grip the fourth line = F</text>
      <text x="16" y="70" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">bass clef</text>
    </g>
    <g transform="translate(490,0)">
      <g fill="none" stroke="#E8C547" stroke-width="2">
        <path d="M-6,16 L14,16 L14,48 L-6,48 Z"/>
      </g>
      <text x="22" y="36" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">block centre gives the third line = C</text>
      <text x="22" y="56" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">alto clef</text>
    </g>

    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      The criterion is fewest ledger lines — a functional choice, not a habit
    </text>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The piano's grand staff exists because the range will not fit on one staff
    </text>
  </g>
</svg>
```

## Listen: same position, different pitch

This site cannot show a staff — but it can play **two octaves of the same note name**. **Under different clefs, "the
same position" relates exactly that way.**

```audiolab
{"type":"interval","a":"A3","b":"A4","label":"同音名、不同八度（谱号决定它是哪一个）","label_en":"Same note name, different octaves — the clef decides which","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"同一个 A 在不同谱号下写成不同位置；反过来说，同一个位置在不同谱号下也是不同的音高。","hint2_en":"The same A is written in different places under different clefs; conversely, the same position gives different pitches under different clefs."}
```

## Common misconceptions

- **"Treble clef is the right hand, bass clef the left."** A clef fixes **pitch positions**, not hands. The left hand
  can be notated in the treble clef.
- **"Clefs can be swapped freely."** Changing clef **changes the pitch meaning of every position**, so it must
  remain consistent or be clearly marked.
- **"A staff implies a pitch by itself."** A clef is required; a bare staff conveys no pitch.
- **"The 8 on a clef is decoration."** It means **the sounding pitch is an octave away** — the staff cannot be read
  literally.
:::
