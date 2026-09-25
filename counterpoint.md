---
id: counterpoint
site: theo
cat: T6
title: 对位
title_en: Counterpoint
summary: 几条旋律同时进行，每条都像旋律，合起来又是和声
summary_en: Several melodies at once, each one a melody on its own, together making harmony
level: core
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [对位, 对位法, 复调, counterpoint, polyphony]
order: 10
links:
  - "[[concept:voice-leading]]"
  - "[[concept:parallel-fifths]]"
  - "[[concept:non-chord-tone-treatment]]"
  - "[[concept:imitation]]"
  - "[[concept:first-species]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：两个声部各自成线，合起来又构成完整和声，是对位最标准的样本 | Bach's first two-part invention — two voices each with their own line, together forming complete harmony
  - mutopia-000287 | 巴赫第八首二部创意曲：同样的两声部写法，用于对照不同主题下的对位处理 | Bach's eighth two-part invention — the same two-voice approach applied to a different subject
  - cyberhymnal-000695 | 管风琴圣咏作对照：柱式和弦的**主调**织体，与上面两条的**复调**织体形成鲜明差别 | An organ hymn as a control — a block-chord **homophonic** texture against the **polyphonic** texture above
sources:
  - 对位指两个或以上独立旋律线同时结合，属对位学与复调音乐通则
  - 五类对位作为由简到繁的训练阶梯（一音对一音 → 华丽对位），为通行对位教学体系
updated: 2026-09-24
---

::: zh
对位要解决的是一个**双重目标**，全部难点都在这里：

> **让每一条线单独听起来都是旋律，同时让它们合起来又是和声。**

两个目标会互相拉扯 —— 只顾纵向的和谐，线就变得东碰西撞、不像旋律；
只顾横向的线条，合起来就会不协和、失去和声逻辑。
**对位法就是处理这场拉扯的技术。**

## 判别标准只有一句话

> **把任一声部单独唱一遍，它像不像旋律。**

像 → 对位成立。不像（成了"和弦的碎片"）→ 那就只是主调织体，不是对位。
这条标准很硬，也很好用：不需要任何分析工具，唱一遍就知道。

## 它与和声写作的关系

| | 和声写作（主调） | 对位（复调） |
|---|---|---|
| 出发点 | 和弦 | **线条** |
| 声部 | 有主要声部与伴奏 | **每条线都是独立的** |
| 判断标准 | 和弦连接是否合理 | **每条线单独听是否像旋律** |
| 二者关系 | —— | 对位是"线"，和声是"线交会的结果" |

关键认识：**和声不是先摆好、再让旋律去填的**；在对位思维里，
**和声是几条线走到一起时自然产生的纵向结果**（前面 [[concept:voice-leading|声部进行]]
讲的就是同一件事的另一面）。

## 五类对位：一条训练阶梯

对位法的经典训练方式是把复杂度逐级加上去，让学习者每次只处理一个新变量：

| 类别 | 做法 | 新增的难点 |
|---|---|---|
| **一音对一音** | 固定旋律每音对一个音 | 只处理纵向关系 |
| **二音对一音** | 每音对两个音 | 加入弱拍与经过音 |
| **四音对一音** | 每音对四个音 | 加入更复杂的节奏型 |
| **切分对位** | 用延留音错开重音 | 处理挂留与解决 |
| **华丽对位** | 自由混合以上各种 | 无预设，接近真实写作 |

这条阶梯的设计很值得注意：**它把"同时处理多件事"拆成"每次只加一件"** ——
这是任何复杂技能训练的通用原则。具体规则见 [[concept:first-species|第一类对位]]。

## 图示：同一时刻的两种视角

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">横向看是两条线（对位），纵向看是一串和声 —— 同一份音乐，两个视角</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="70" y="0">D</text><text x="140" y="0">E</text>
      <text x="210" y="0">F</text><text x="280" y="0">G</text>
    </g>
    <polyline points="-6,0 64,0 134,0 204,0 274,0" fill="none" stroke="#E07A3F" stroke-width="1.4"/>
    <text x="300" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">上声部（一条线）</text>

    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="72">E</text><text x="70" y="72">F</text><text x="140" y="72">G</text>
      <text x="210" y="72">A</text><text x="280" y="72">B</text>
    </g>
    <polyline points="-6,72 64,72 134,72 204,72 274,72" fill="none" stroke="#5B7FA8" stroke-width="1.4"/>
    <text x="300" y="76" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">下声部（另一条线）</text>

    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="66"/><line x1="70" y1="8" x2="70" y2="66"/>
      <line x1="140" y1="8" x2="140" y2="66"/><line x1="210" y1="8" x2="210" y2="66"/>
      <line x1="280" y1="8" x2="280" y2="66"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="92">六度</text><text x="70" y="92">六度</text><text x="140" y="92">六度</text>
      <text x="210" y="92">六度</text><text x="280" y="92">六度</text>
    </g>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      纵向看：每一步都是六度 —— 但上下并行五音以上会「合成一条线」（见平行五八度）
    </text>
    <text x="0" y="142" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      对位的真功夫：让上下两条线方向不同，各自都像旋律，交会时才成为和声
    </text>
  </g>
</svg>
```

## 听一听：纵向关系与横向线条

对位是两条线的事，而本站的听辨件是**单声部/和弦型**的 —— 这里放不出真正的两声部对位。
所以我只用 `interval` 演示**纵向的那一面**（两条线在同一时刻形成的音程），
横向的线条感请到上面的实例里听（巴赫的二部创意曲是最短路径）。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"纵向：两条线此刻形成三度","label_en":"Vertical: the two lines form a third at this instant","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 G4 得到五度，换成 B4 得到大七度 —— 纵向音程是当下的关系，而两条线各自的方向才是对位的核心。","hint2_en":"Set b to G4 for a fifth, or B4 for a major seventh — the vertical interval is a moment, but the two lines' directions are what counterpoint is about."}
```

## 常见误解

- **「对位就是几条旋律一起响」** → 关键在**每条都必须是旋律**。几条线互相让路、彼此补齐，才能算对位。
- **「对位与和声是两套东西」** → 是同一件事的两个视角：和声是纵向结果，对位是横向过程。
- **「主调音乐比对位低级」** → 是两种织体，分工不同。主调更适合叙述与情绪铺陈，复调更适合发展与编织。
- **「对位法是过时的教条」** → 它训练的是"同时处理横向与纵向"的能力，这个能力在爵士编曲、影视配器里同样用得上。
:::

::: en
Counterpoint has to satisfy a **double goal**, and every difficulty lives there:

> **Make each line sound like a melody on its own, while making them together sound like harmony.**

The two goals pull against each other: attend only to vertical agreement and the lines become a series of
collisions; attend only to horizontal flow and the result is dissonant, losing harmonic logic.
**Counterpoint is the technique for handling that pull.**

## One test decides it

> **Sing any single voice on its own: does it sound like a melody?**

Yes → the counterpoint holds. No (it has become "chord fragments") → it is homophonic texture, not counterpoint.
The test is blunt and practical: no analytical tools needed, just sing it.

## Its relation to harmonic writing

| | Harmonic (homophonic) writing | Counterpoint (polyphonic) |
|---|---|---|
| Starting point | chords | **lines** |
| Voices | one principal voice plus accompaniment | **every line independent** |
| Test | do the chords connect well? | **does each line work alone as a melody?** |
| Relation | — | counterpoint is the lines; harmony is where they meet |

The key realisation: **harmony is not laid out first and then filled by melody.** In contrapuntal thinking,
**harmony is the vertical result of several lines arriving together** — the other face of what
[[concept:voice-leading|voice leading]] describes.

## Five species: a training ladder

The classic method adds complexity one step at a time so the student handles a single new variable per stage:

| Species | Method | New difficulty |
|---|---|---|
| **note against note** | one note per note against the cantus firmus | vertical relations only |
| **second** | two notes per note | weak beats and passing notes |
| **third** | four notes per note | more complex rhythmic figures |
| **fourth** | suspensions displace the accents | holding and resolving |
| **fifth** | a free mixture of all the above | no preset; close to real writing |

Note the design: **it breaks "handling several things at once" into "add one thing at a time"** — a general
principle in training any complex skill. Rules are covered under [[concept:first-species|first species]].

## Diagram: two views of the same instant

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Horizontally, two lines (counterpoint); vertically, a string of harmonies — one music, two views</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="70" y="0">D</text><text x="140" y="0">E</text>
      <text x="210" y="0">F</text><text x="280" y="0">G</text>
    </g>
    <polyline points="-6,0 64,0 134,0 204,0 274,0" fill="none" stroke="#E07A3F" stroke-width="1.4"/>
    <text x="300" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">upper voice (one line)</text>

    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="72">E</text><text x="70" y="72">F</text><text x="140" y="72">G</text>
      <text x="210" y="72">A</text><text x="280" y="72">B</text>
    </g>
    <polyline points="-6,72 64,72 134,72 204,72 274,72" fill="none" stroke="#5B7FA8" stroke-width="1.4"/>
    <text x="300" y="76" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">lower voice (another line)</text>

    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="66"/><line x1="70" y1="8" x2="70" y2="66"/>
      <line x1="140" y1="8" x2="140" y2="66"/><line x1="210" y1="8" x2="210" y2="66"/>
      <line x1="280" y1="8" x2="280" y2="66"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="92">a sixth</text><text x="70" y="92">a sixth</text><text x="140" y="92">a sixth</text>
      <text x="210" y="92">a sixth</text><text x="280" y="92">a sixth</text>
    </g>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Vertically: a sixth at every step — but moving in parallel fuses two voices into one (see parallel fifths)
    </text>
    <text x="0" y="142" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      The real craft: have the lines move in different directions, each a melody, meeting as harmony
    </text>
  </g>
</svg>
```

## Listen: the vertical relation, and the lines you must hear elsewhere

Counterpoint needs two voices, and this site's listening components are single-voice or chord-based — so a true
two-part example cannot be played here. I use `interval` to demonstrate **the vertical face** (the interval the
two lines form at one instant); for the horizontal lines, go to the instances above — Bach's two-part inventions
are the shortest route.

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"纵向：两条线此刻形成三度","label_en":"Vertical: the two lines form a third at this instant","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"纵向音程是当下的关系；两条线各自的方向才是对位的核心。","hint2_en":"A vertical interval is a moment; the two lines' directions are what counterpoint is about."}
```

## Common misconceptions

- **"Counterpoint just means several melodies at once."** The point is that **each must be a melody**. Lines that
  make way for one another and complete one another qualify; simultaneous noodling does not.
- **"Counterpoint and harmony are two separate subjects."** Two views of one thing: harmony is the vertical
  result, counterpoint the horizontal process.
- **"Homophonic music is inferior to counterpoint."** They are two textures with different jobs. Homophony is
  better for narration and mood; polyphony for development and weaving.
- **"Species counterpoint is obsolete dogma."** It trains the ability to handle horizontal and vertical
  simultaneously — an ability jazz arranging and film orchestration need just as much.
:::
