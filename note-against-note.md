---
id: note-against-note
site: theo
cat: T6
title: 单音对位
title_en: Note Against Note
summary: 一个音对一个音——对位的最基本形态，也是最容易检查的形态
summary_en: One note to one note — the most basic form of counterpoint, and the easiest to check
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [单音对位, 一音对一音, note against note]
order: 12
links:
  - "[[concept:counterpoint]]"
  - "[[concept:first-species]]"
  - "[[concept:cantus-firmus]]"
  - "[[concept:voice-leading]]"
  - "[[concept:parallel-fifths]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：开头的声部进入几乎是一音对一音的写法，最接近单音对位 | Bach's first two-part invention — the opening entries are almost note against note, the closest thing to this texture
  - cyberhymnal-000695 | 管风琴圣咏：柱式和弦的**主调**写法，与单音对位的**复调**写法形成直接对照 | An organ hymn — block-chord **homophonic** writing, a direct contrast with the **polyphonic** note-against-note texture
  - giantmidi-006222 | 音阶与终止练习：每一步都在同一时值上，可听出"同节奏、不同线"的效果 | Scale and cadence exercises move in one note value throughout, making "same rhythm, different lines" audible
sources:
  - 单音对位指两声部以一音对一音的时值关系结合，属对位学通则
  - 单音对位作为对位训练的第一阶段（第一类对位）的基础形态，为通行对位教学表述
updated: 2026-09-24
---

::: zh
单音对位是最朴素的对位形态：**两个声部同时前进，一个音对一个音。**

> 两个声部**每一步都同时换音** —— 没有错位、没有经过音、没有长短。

## 它的价值在于"把变量降到最少"

复调写作里同时要管的事很多：纵向协和、横向线条、节奏错位、外音处理……
单音对位**把其中大部分变量消掉了**：

| 变量 | 单音对位里的状态 |
|---|---|
| 时值 | 两声部**完全相同**（通常都是一样的音符） |
| 节奏错位 | **不存在** |
| 外音 | **不存在**（每个音都是和弦音） |
| 纵向关系 | **每一步都要检查**（这是唯一的难点） |

所以它是对位训练的**第一步**（见 [[concept:first-species|第一类对位]]）：
**先把"每一步的音程是否合适"练成条件反射**，再逐层加上节奏复杂度。

## 与主调织体的根本差别

这一点常被忽略：单音对位听起来**接近**柱式和弦，但两者的思维完全不同。

| | 单音对位（复调） | 柱式和弦（主调） |
|---|---|---|
| 出发点 | **两条线** | 一个和弦 |
| 判断标准 | 每条线**单独唱**是否像旋律 | 和弦连接是否合理 |
| 换音时的约束 | 两声部**各自**移动到合适的位置 | 声部按功能排列 |

也就是说：**它们的音符可以完全一样，但写作时的思考顺序是相反的。**
单音对位要求你先想"这条线接下来要去哪"，再看"两条线合起来是什么音程"。

## 它的现实用途

单音对位不只是练习。真实作品里它出现在两个位置：

- **密集和声段**：所有声部同步换音，形成厚实的复调（如赞美诗的严格四声部写法）；
- **赋格或卡农的"紧凑段"**：为了把进入压紧，常把织体暂时变成一音对一音。

## 图示：同步换音，两条线

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">每一步都是同时换音 —— 变量只剩"音程合不合适"这一个</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">E</text><text x="128" y="0">G</text>
      <text x="192" y="0">A</text><text x="256" y="0">G</text><text x="320" y="0">C</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">E</text><text x="64" y="60">G</text><text x="128" y="60">C</text>
      <text x="192" y="60">C</text><text x="256" y="60">E</text><text x="320" y="60">G</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="54"/><line x1="64" y1="8" x2="64" y2="54"/>
      <line x1="128" y1="8" x2="128" y2="54"/><line x1="192" y1="8" x2="192" y2="54"/>
      <line x1="256" y1="8" x2="256" y2="54"/><line x1="320" y1="8" x2="320" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="80">三度</text><text x="64" y="80">三度</text><text x="128" y="80">五度</text>
      <text x="192" y="80">六度</text><text x="256" y="80">三度</text><text x="320" y="80">八度</text>
    </g>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      每一步都要检查纵向音程 —— 但每一步也都要问"这条线自己走得好不好"
    </text>
    <text x="0" y="128" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      连续三度（第 1–2 步）正是"平行"最危险的位置：不完全协和可以平行，但方向单一会削弱独立性
    </text>
  </g>
</svg>
```

## 听一听：纵向关系的质量

单音对位是两声部的，本站听辨件放不出真正的两声部 —— 这里用 `interval` 演示
**每一步的纵向音程**，而这正是单音对位唯一要检查的东西。
两声部同时换音的实际效果请到实例里听（二部创意曲的进入段最短）。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"单音对位里的一步：三度","label_en":"One step in note-against-note writing: a third","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 C4 得到同度，换成 G4 得到五度 —— 单音对位就是在每一步上做这种选择，且要连续做对。","hint2_en":"Set b to C4 for a unison, or G4 for a fifth — note-against-note writing makes this choice at every step, and must keep getting it right."}
```

## 常见误解

- **「单音对位就是柱式和弦」** → 音符可以一样，但**思考顺序相反**：一个从线条出发，一个从和弦出发。
- **「单音对位太简单，没什么可练」** → 简单在变量少，难在**每一步都无法掩饰**：错一处立刻听得出来。
- **「两声部同时换音就不能有外音」** → 在严格训练里如此；实际写作中可以加入经过音，那时就已进入第二类对位的范畴。
- **「它只是练习，作品里不用」** → 赞美诗的严格四声部、赋格的紧凑段都是这种织体。
:::

::: en
Note against note is the plainest form of counterpoint: **two voices advancing together, one note to one note.**

> Both voices **change pitch at every step** — no displacement, no passing notes, no differing lengths.

## Its value: reducing the variables to a minimum

Polyphonic writing normally juggles several things at once — vertical consonance, horizontal lines, rhythmic
displacement, foreign notes. Note against note **removes most of them**:

| Variable | State in note-against-note writing |
|---|---|
| note values | **identical** in both voices |
| rhythmic displacement | **absent** |
| foreign notes | **absent** (every note is a chord tone) |
| vertical relation | **must be checked at every step** — the only difficulty left |

So it is the **first step** of counterpoint training (see [[concept:first-species|first species]]):
**make "is the interval right at this step" automatic** before layering on rhythmic complexity.

## The essential difference from homophonic writing

This is often missed: note against note **sounds** close to block chords, but the thinking is opposite.

| | Note against note (polyphonic) | Block chords (homophonic) |
|---|---|---|
| Starting point | **two lines** | one chord |
| Test | does each line work **sung alone**? | do the chords connect well? |
| Constraint when changing | each voice **moves itself** to a good place | voices are arranged by function |

Their notes can be identical, yet the order of thought is reversed. Note against note asks you first "where does
this line want to go next", and only then "what interval do the two lines make".

## Where it is actually used

It is not only an exercise. It appears in two places in real music:

- **Dense harmonic passages** — all voices changing together into a thick polyphony (the strict four-part writing
  of hymn settings);
- **Tight passages in fugues and canons** — to squeeze the entries closer, the texture temporarily becomes note
  against note.

## Diagram: simultaneous change, two lines

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Every step changes both voices at once — leaving only "is this interval right" to decide</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">E</text><text x="128" y="0">G</text>
      <text x="192" y="0">A</text><text x="256" y="0">G</text><text x="320" y="0">C</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">E</text><text x="64" y="60">G</text><text x="128" y="60">C</text>
      <text x="192" y="60">C</text><text x="256" y="60">E</text><text x="320" y="60">G</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="54"/><line x1="64" y1="8" x2="64" y2="54"/>
      <line x1="128" y1="8" x2="128" y2="54"/><line x1="192" y1="8" x2="192" y2="54"/>
      <line x1="256" y1="8" x2="256" y2="54"/><line x1="320" y1="8" x2="320" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="80">a third</text><text x="64" y="80">a third</text><text x="128" y="80">a fifth</text>
      <text x="192" y="80">a sixth</text><text x="256" y="80">a third</text><text x="320" y="80">an octave</text>
    </g>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Every step checks the vertical interval — and asks whether each line itself moves well
    </text>
    <text x="0" y="128" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Consecutive thirds (steps 1–2) are where parallel motion gets risky: permitted, but a single direction weakens independence
    </text>
  </g>
</svg>
```

## Listen: the quality of the vertical relation

Note against note needs two voices, and this site cannot play them — so `interval` demonstrates **the vertical
interval of one step**, which is the only thing this texture must check. For the actual simultaneous effect, use
the instances (the opening entries of a two-part invention are the shortest).

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"单音对位里的一步：三度","label_en":"One step in note-against-note writing: a third","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 C4 得到同度，换成 G4 得到五度 —— 单音对位就是在每一步做这种选择，且要连续做对。","hint2_en":"Set b to C4 for a unison, or G4 for a fifth — this texture makes that choice at every step, and must keep getting it right."}
```

## Common misconceptions

- **"Note against note is just block chords."** The notes can match, but the **order of thought is reversed**: one
  starts from lines, the other from chords.
- **"It is too simple to be worth practising."** Simple in variables, hard because **nothing can be hidden** — one
  error is immediately audible.
- **"Simultaneous change means no foreign notes."** True of the strict exercise; real writing may add passing
  notes, at which point you have entered second-species territory.
- **"It is only an exercise."** Strict four-part hymn writing and the tight passages of fugues use exactly this
  texture.
:::
