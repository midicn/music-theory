---
id: jianpu
site: theo
cat: T10
title: 简谱
title_en: Numbered Notation (Jianpu)
summary: 用数字 1–7 记音级——易写易读，但有它自己的取舍
summary_en: Recording degrees with the digits 1–7 — easy to write and read, with its own trade-offs
level: standard
tags: [乐理, 记谱, 中国]
tags_en: [theory, notation, chinese]
alias: [简谱, 数字谱, numbered notation, jianpu]
order: 24
links:
  - "[[concept:staff]]"
  - "[[concept:clef]]"
  - "[[concept:scale]]"
  - "[[concept:gongchepu]]"
  - "[[concept:rhythm-training]]"
instances:
  - thesession-015836 | 《茉莉花》（民歌版）：同一曲调既可记成五线谱也可记成简谱，最适合用来对照两种体系 | The Jasmine Flower folk melody — one tune that can be notated either way, ideal for comparing the two systems
  - giantmidi-004956 | 《茉莉花》的钢琴改编：可见"同一曲调在不同记谱与编配下"的差别 | A piano arrangement of Jasmine Blossoms, showing one tune under different notation and arrangement
  - chinafolk-000149 | 《茉莉花》的声乐版本（**C3 · 仅限学习研究**）：简谱在中国声乐与民歌记写中最为常见，故选此版 | The vocal version of Jasmine Flower (**C3, study and research only**) — numbered notation is commonest for Chinese vocal and folk material, hence this choice
sources:
  - 简谱以阿拉伯数字 1–7 记写唱名音级、0 记休止，用加点表示八度、用减时线表示时值，为通行简谱规范
  - 简谱于 20 世纪初经日本传入中国并因学堂乐歌普及，为通行音乐史表述
updated: 2026-09-25
---

::: zh
简谱用最少的符号做一件事：**把音级写成数字。**

> `1 2 3 4 5 6 7` = do re mi fa sol la si，`0` = 休止。

## 三条规则就够了

| 要表示什么 | 怎么写 | 说明 |
|---|---|---|
| **音级** | `1`–`7` | 数字对应**唱名**（不是音名） |
| **八度** | 数字**上方加点** = 高八度；**下方加点** = 低八度 | 加两个点 = 两个八度 |
| **时值** | **减时线**：数字下加一条横线 = 八分；两条 = 十六分<br>**增时线**：数字后加一条横线 = 延长一拍 | 与五线谱"加符尾减半"同理 |

**再加两个记号**：

| 记号 | 含义 |
|---|---|
| `1 = C` | **调号**：规定 `1` 等于哪个音 |
| `4/4`（写在开头） | 拍号 |

**关键认识**：简谱里 **`1` 是什么音由调号决定** ——
`1 = C` 时 `1` 是 C；`1 = G` 时 `1` 就是 G。**这与五线谱必须配谱号是同一个道理**（见 [[concept:clef|谱号]]）。

## 与五线谱的根本差异

这是本条最值得说清的一点：

| | **简谱** | **五线谱** |
|---|---|---|
| 记的是 | **音级（相对关系）** | **位置（可对应绝对音高）** |
| 视觉上能看出什么 | 数字与本位音的关系 | **音高轮廓与音程宽度的图形** |
| 转调 | **只改调号**，数字完全不动 | 需改调号，谱面位置不变 |
| 复杂的多声部 | 记写困难 | **擅长** |
| 易写易读 | **对单声部旋律极方便** | 学习曲线较陡 |

**"转调时数字不动、只改调号"是简谱的一大优点** ——
因为唱名体系本身是**相对于主音**的，换调时**音级关系不变**，所以数字不必改。
（代价是：**看不出绝对音高**，同一份简谱在不同调号下是完全不同的音。）

## 它为什么在中国普及

一个历史事实：

| 时期 | 情况 |
|---|---|
| 20 世纪初 | 经日本传入（与学堂乐歌的推广大致同时） |
| 20 世纪中后 | 因**书写与阅读门槛低**，成为群众歌咏、民歌记录、戏曲与器乐简写的常用体系 |

**"门槛低"是它真正的优势**：五线谱的读写需要专门训练，
而简谱只要认识数字与几条规则就能唱 —— 这让它特别适合**传唱与记录单声部旋律**。
（中国的传统记谱体系见 [[concept:gongchepu|工尺谱]]。）

## 它不擅长什么

诚实地说清边界：

| 情形 | 简谱的困难 |
|---|---|
| **多声部合唱 / 乐队总谱** | 需要多行对齐，简谱没有五线谱那样的纵向直观 |
| **复杂和声与音型** | 和弦音同时记写时数字容易混乱 |
| **绝对音高写作** | 需要先确定调号，写"无调性"或频繁转调的内容很别扭 |
| **视奏器乐作品** | 五线谱能一眼看出音程宽窄，简谱要读数字 |

**结论**：**简谱不是"简化的五线谱"，而是为不同目的设计的另一套体系。**
它擅长"**单声部旋律的快速记录与传唱**"，不擅长"复杂织体的精确谱面"。

## 图示：数字、点与时值线

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">三条规则：数字记音级、加点记八度、划线记时值</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="Georgia,serif" font-size="17" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">1</text><text x="40" y="0">2</text><text x="80" y="0">3</text>
      <text x="140" y="0">5̇</text><text x="180" y="0">6̇</text>
      <text x="240" y="0">5̣</text><text x="280" y="0">6̣</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64" text-anchor="middle">
      <text x="40" y="18">音级（唱名）</text>
      <text x="160" y="18">上加点 = 高八度</text>
      <text x="260" y="18">下加点 = 低八度</text>
    </g>

    <g transform="translate(0,52)">
      <g font-family="Georgia,serif" font-size="17" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">5</text><text x="56" y="0">5</text><text x="112" y="0">5</text>
        <text x="196" y="0">3</text><text x="252" y="0">5</text>
        <text x="336" y="0">1</text><text x="392" y="0">—</text>
      </g>
      <g stroke="#5B7FA8" stroke-width="1.4">
        <line x1="-14" y1="6" x2="14" y2="6" opacity=".5"/>
        <line x1="42" y1="6" x2="70" y2="6"/>
        <line x1="98" y1="6" x2="126" y2="6"/>
        <line x1="98" y1="10" x2="126" y2="10"/>
        <line x1="182" y1="6" x2="210" y2="6"/>
        <line x1="238" y1="6" x2="266" y2="6"/>
        <line x1="322" y1="6" x2="350" y2="6"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64">
        <text x="0" y="28" text-anchor="middle">四分</text>
        <text x="56" y="28" text-anchor="middle">八分</text>
        <text x="112" y="28" text-anchor="middle">十六分</text>
        <text x="196" y="28" text-anchor="middle">八分</text>
        <text x="252" y="28" text-anchor="middle">八分</text>
        <text x="360" y="28" text-anchor="middle">增时线（延长一拍）</text>
      </g>
    </g>

    <g transform="translate(0,116)">
      <text x="0" y="0" font-family="Georgia,serif" font-size="13" fill="#E8C547">1 = C　4/4</text>
      <text x="120" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">← 调号规定「1 是哪个音」，拍号写在开头</text>
    </g>

    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      优点：转调只改调号、数字不动（唱名体系本身相对主音）；单声部旋律极易写易读
    </text>
    <text x="0" y="168" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      边界：多声部与复杂和声吃力，且看不出绝对音高 —— 它是为不同目的设计的另一套体系
    </text>
  </g>
</svg>
```

## 听一听：唱名是相对的

用 `scale` 听两条音阶：**同为 C 大调**与**同为 G 大调**的 `1 2 3 4 5`。
**两条的"1"在绝对音高上不同，但"1 到 2"的关系完全一样** —— 这就是简谱"数字不动、只改调号"的听觉依据。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4"],"label":"1 = C：1 2 3 4 5（从 C 开始）","label_en":"1 = C: degrees 1 to 5 starting on C","hint":"点「上行」，记住音级之间的关系","hint_en":"Try Up and hold on to the relations between degrees","gap":0.36}
```

```audiolab
{"type":"scale","notes":["G4","A4","B4","C5","D5"],"label":"1 = G：同一条 1 2 3 4 5（从 G 开始）","label_en":"1 = G: the same degrees 1 to 5 starting on G","hint":"与上一条对比：绝对音高不同，音级关系相同","hint_en":"Against the item above: different pitches, identical degree relations","gap":0.36}
```

## 常见误解

- **「简谱是五线谱的简化版」** → 它们是为**不同目的**设计的体系：一个记音级（相对），一个记位置（可对应绝对音高）。
- **「简谱只能记简单音乐」** → 它**不擅长多声部与复杂和声**，但单声部旋律的记写效率很高，民歌与戏曲大量使用。
- **「简谱没有调号概念」** → 有：`1 = X` 就是调号，且它决定了全部数字的实际音高。
- **「简谱过时了」** → 在中国它仍是民歌记录、群众歌咏与乐器简写的常用体系，且学习门槛低是它真正的优势。
:::

::: en
Numbered notation does one thing with the fewest possible signs: **it writes degrees as digits.**

> `1 2 3 4 5 6 7` = do re mi fa sol la si, and `0` = a rest.

## Three rules are enough

| What to show | How | Note |
|---|---|---|
| **degree** | `1`–`7` | the digits stand for **solfège names**, not note names |
| **octave** | a dot **above** = an octave higher; **below** = lower | two dots means two octaves |
| **duration** | a **line under** the digit halves it (one line = eighth, two = sixteenth)<br>a **dash after** the digit extends it by a beat | the same logic as "each flag halves" in staff notation |

**Two more signs**:

| Sign | Meaning |
|---|---|
| `1 = C` | the **key**: it fixes which pitch `1` is |
| `4/4` (at the start) | the metre |

**The crucial point**: in numbered notation **what `1` sounds depends on the key marking** — with `1 = C`, `1` is C;
with `1 = G`, `1` is G. **The same logic as a clef** (see [[concept:clef|clef]]).

## The fundamental difference from staff notation

The most valuable point in this entry:

| | **Numbered notation** | **Staff notation** |
|---|---|---|
| Records | **degrees (relations)** | **positions (mappable to absolute pitch)** |
| Visible at a glance | the digits and their relation to the tonic | **a picture of contour and interval width** |
| Transposition | **change the key marking only**; the digits stay | the signature changes; positions stay |
| Complex multi-part music | hard to write | **its strength** |
| Ease of writing and reading | **excellent for a single melodic line** | a steeper learning curve |

**"Change key, keep the digits" is a real advantage** — the solfège system is **relative to the tonic**, so on
transposition the degree relations are unchanged and the digits need no editing. (The cost: **no absolute pitch is
visible**; the same figures under a different key marking are entirely different notes.)

## Why it is widespread in China

A historical fact:

| Period | Situation |
|---|---|
| early twentieth century | introduced via Japan, roughly alongside the school-song movement |
| later twentieth century | its **low bar to writing and reading** made it the common system for mass singing, folk-song collection, opera and short instrumental scores |

**That low bar is the real advantage**: staff notation needs dedicated training, whereas numbered notation can be
sung once you know the digits and a few rules — which makes it ideal for **transmitting and recording a single
melodic line**. (For China's traditional system see [[concept:gongchepu|gongche notation]].)

## What it is not good at

Stating the boundary honestly:

| Case | Difficulty |
|---|---|
| **choirs, orchestral scores** | multiple aligned lines are less visually direct than a staff |
| **complex harmony and figuration** | digits for simultaneous chord tones become cluttered |
| **writing without a tonal centre** | a key must be fixed first; atonal or heavily modulating music is awkward |
| **instrumental sight-reading** | a staff shows interval width at a glance; here one reads digits |

**Conclusion**: **numbered notation is not a simplified staff, but a different system designed for different
purposes.** It excels at **quickly recording and transmitting a single melodic line**; it is poor at **dense,
precise textures**.

## Diagram: digits, dots and dashes

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Three rules: digits for degrees, dots for octaves, lines for durations</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="Georgia,serif" font-size="17" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">1</text><text x="40" y="0">2</text><text x="80" y="0">3</text>
      <text x="140" y="0">5̇</text><text x="180" y="0">6̇</text>
      <text x="240" y="0">5̣</text><text x="280" y="0">6̣</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64" text-anchor="middle">
      <text x="40" y="18">degrees</text>
      <text x="160" y="18">dot above: an octave up</text>
      <text x="260" y="18">dot below: an octave down</text>
    </g>

    <g transform="translate(0,52)">
      <g font-family="Georgia,serif" font-size="17" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">5</text><text x="56" y="0">5</text><text x="112" y="0">5</text>
        <text x="196" y="0">3</text><text x="252" y="0">5</text>
        <text x="336" y="0">1</text><text x="392" y="0">—</text>
      </g>
      <g stroke="#5B7FA8" stroke-width="1.4">
        <line x1="42" y1="6" x2="70" y2="6"/>
        <line x1="98" y1="6" x2="126" y2="6"/>
        <line x1="98" y1="10" x2="126" y2="10"/>
        <line x1="182" y1="6" x2="210" y2="6"/>
        <line x1="238" y1="6" x2="266" y2="6"/>
        <line x1="322" y1="6" x2="350" y2="6"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64">
        <text x="0" y="28" text-anchor="middle">quarter</text>
        <text x="56" y="28" text-anchor="middle">eighth</text>
        <text x="112" y="28" text-anchor="middle">sixteenth</text>
        <text x="196" y="28" text-anchor="middle">eighth</text>
        <text x="252" y="28" text-anchor="middle">eighth</text>
        <text x="360" y="28" text-anchor="middle">dash: one beat longer</text>
      </g>
    </g>

    <g transform="translate(0,116)">
      <text x="0" y="0" font-family="Georgia,serif" font-size="13" fill="#E8C547">1 = C　4/4</text>
      <text x="120" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">the key marking fixes which pitch 1 is; the metre is written at the start</text>
    </g>

    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Advantage: transpose by changing the key marking only; single lines are quick to write and read
    </text>
    <text x="0" y="168" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      Boundary: awkward for dense textures and shows no absolute pitch — a different system for different purposes
    </text>
  </g>
</svg>
```

## Listen: solfège is relative

Use `scale` on two five-note spans: **degrees 1 to 5 in C** and **degrees 1 to 5 in G**. **The two "1"s differ in
absolute pitch, while the relation from 1 to 2 is identical** — the aural basis for "change key, keep the digits".

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4"],"label":"1 = C：1 2 3 4 5（从 C 开始）","label_en":"1 = C: degrees 1 to 5 starting on C","hint":"点「上行」，记住音级之间的关系","hint_en":"Try Up and hold on to the relations between degrees","gap":0.36}
```

```audiolab
{"type":"scale","notes":["G4","A4","B4","C5","D5"],"label":"1 = G：同一条 1 2 3 4 5（从 G 开始）","label_en":"1 = G: the same degrees 1 to 5 starting on G","hint":"与上一条对比：绝对音高不同，音级关系相同","hint_en":"Against the item above: different pitches, identical degree relations","gap":0.36}
```

## Common misconceptions

- **"Numbered notation is a simplified staff."** They serve **different purposes**: one records degrees
  (relations), the other positions (mappable to absolute pitch).
- **"It can only record simple music."** It is **weak at multi-part music and complex harmony**, but very efficient
  for a single line — heavily used for folk song and opera.
- **"It has no concept of key."** It does: `1 = X` is the key marking and it fixes the sounding pitch of every
  digit.
- **"It is obsolete."** In China it remains a standard system for folk-song collection, mass singing and short
  instrumental notation, and its low learning barrier is a real advantage.
:::
