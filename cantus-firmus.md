---
id: cantus-firmus
site: theo
cat: T6
title: 固定旋律
title_en: Cantus Firmus
summary: 一条给定的旋律当骨架，其他声部围着它长出来
summary_en: One given melody as the frame, with everything else growing around it
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [固定旋律, 定旋律, cantus firmus, c.f.]
order: 30
links:
  - "[[concept:counterpoint]]"
  - "[[concept:first-species]]"
  - "[[concept:note-against-note]]"
  - "[[concept:pedal-point]]"
  - "[[concept:theme-variations]]"
instances:
  - mutopia-000049 | 《绿袖子》加固定低音：一条不变的旋律线贯穿全曲，其他声部围着它生长，正是固定旋律的形态 | Greensleeves to a Ground — one unchanging line runs through the piece while everything else grows around it
  - cyberhymnal-000695 | 管风琴圣咏：旋律通常取自圣咏曲调，和声按它逐音配置，与固定旋律的写法同源 | An organ hymn — the melody usually comes from a chant tune, harmonised note by note, the same lineage as cantus firmus writing
  - mutopia-000280 | 巴赫二部创意曲第一首：一个主题贯穿全曲并不断被模仿，可对照"固定素材"如何组织整曲 | Bach's first two-part invention — one subject runs through the piece and is continually imitated, showing how fixed material organises a whole work
sources:
  - 固定旋律指预先给定、作为写作骨架的旋律；中世纪以来用于定旋律弥撒与对位训练，为音乐史与对位学通行记载
  - 固定旋律在各声部间的位置可移动（低音 / 上方 / 内声部），为通行表述
updated: 2026-09-24
---

::: zh
固定旋律（cantus firmus，常缩写 c.f.）的做法只有一句：
**先用一条给定的旋律打底，其他声部围着它写。**

它之所以值得单列，因为它把复调写作的难度**削掉了一半**：

| 少了什么 | 得到什么 |
|---|---|
| 不必同时构思所有声部 | 可以先专注一条线上的每个音 |
| 骨架已经确定 | 纵向关系有明确的参照物 |

**这就是为什么五类对位全部建立在固定旋律之上**（见 [[concept:first-species|第一类对位]]）——
它把"创作"和"处理"分开了：你只需要决定**怎么围着它写**，不必先决定它是什么。

## 它在历史上的两种身份

| 身份 | 说明 |
|---|---|
| **作曲手法** | 中世纪与文艺复兴的定旋律弥撒：整首弥撒建立在一条圣咏旋律上，各乐章用同一条（或同一条的变形） |
| **训练工具** | 对位教学中的练习题基 —— 今天仍是 |

第二种身份流传至今，第一种则留下了一个重要的观念：**一条已有的旋律可以作为整部作品的地基。**
这条观念在后来演化为 [[concept:theme-variations|变奏曲式]]、[[concept:pedal-point|固定低音]]
（ground bass）等一系列"固定素材"写法。

## 固定旋律可以放在哪里

早期惯例是放在**最下方的声部**（"tenor" 一词本义就是"保持者"）。
后来的写作把它解放到各个位置：

| 位置 | 效果 |
|---|---|
| **低音** | 最传统；和声骨架最清楚 |
| **上方** | 固定旋律成为旋律主角，其他声部为伴奏 |
| **内声部** | 最隐蔽的用法，固定旋律成了"隐藏的主线" |

最后一行的效果值得注意：**当固定旋律藏在内声部时，它是给"知道内情的人"听的**——
这类"隐藏结构"在文艺复兴与巴洛克作品里大量存在。

## 与固定低音的区别（容易混）

| | 固定旋律 | 固定低音（ground bass） |
|---|---|---|
| 固定的是 | **旋律**（可短可长，可在任何声部） | **低音线**（通常短，循环反复） |
| 循环吗 | 不一定 | **是**，反复循环 |
| 其他声部 | 通常每个音配一次 | 每循环一次写一组新变奏 |

一句话：**固定旋律是"地基"，固定低音是"循环的地基"。**

## 图示：一条线定下来，其余围着它长

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">固定旋律（深色）不变，其他声部围绕它逐音配置</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E8C547" text-anchor="middle">
      <text x="0" y="0">G</text><text x="70" y="0">F</text><text x="140" y="0">E</text>
      <text x="210" y="0">D</text><text x="280" y="0">C</text>
    </g>
    <g stroke="#E8C547" stroke-width="2.4">
      <line x1="-8" y1="-10" x2="288" y2="-10"/>
    </g>
    <text x="300" y="-6" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">固定旋律（给定 · 不变）</text>

    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="-30">B♭</text><text x="70" y="-30">A</text><text x="140" y="-30">A♭</text>
      <text x="210" y="-30">F</text><text x="280" y="-30">E</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="42">D</text><text x="70" y="42">C</text><text x="140" y="42">C</text>
      <text x="210" y="42">A</text><text x="280" y="42">G</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      <text x="0" y="66">上方与下方声部逐音配置 —— 骨架已定，只需决定"怎么围着它写"</text>
    </g>
    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      这正是不必同时构思所有声部的能力：把"创作"与"处理"分开
    </text>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      与固定低音的区别：固定旋律不一定循环；固定低音必然反复循环
    </text>
  </g>
</svg>
```

## 听一听：固定骨架上的写作

用 `progression` 听一段功能进行：把它想成"骨架已定"的处境 ——
**低音与和声是给定的，你要决定的是上方怎么写**。这正是固定旋律训练的核心处境。

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"固定的功能骨架（I → IV → V → I）","label_en":"A fixed functional frame: I-IV-V-I","hint":"逐个和弦依次听 —— 骨架不变，变化都在上方","hint_en":"Hear each chord in turn — the frame holds, all change is above it"}
```

## 常见误解

- **「固定旋律只是练习题」** → 它同时是历史上的核心作曲手法（定旋律弥撒），并演化出变奏曲式、固定低音等一系列写法。
- **「固定旋律必须在低音」** → 早期惯例如此，后来可置于任何声部；藏在内声部时是一种"隐藏结构"手法。
- **「固定旋律与固定低音是一回事」** → 前者是旋律（不一定循环），后者是循环的低音线。
- **「用固定旋律就不算创作」** → 围绕它写作本身就是创作。历史上最复杂的复调作品，很多都建立在一条别人的旋律上。
:::

::: en
Cantus firmus (often abbreviated c.f.) is one instruction: **start with a given melody, then write the other
voices around it.**

It deserves its own entry because it **halves the difficulty** of polyphonic writing:

| What is removed | What is gained |
|---|---|
| no need to invent every voice at once | you can focus on one note of one line at a time |
| the frame is already fixed | vertical relations have a definite reference |

**That is why all five species are built on a cantus firmus** (see [[concept:first-species|first species]]): it
separates **composing from handling** — you need only decide **how to write around it**, not what it should be.

## Its two historical identities

| Identity | Explanation |
|---|---|
| **compositional device** | the medieval and Renaissance cantus-firmus Mass: a whole Mass built on one chant melody, each movement using it (or a transformation of it) |
| **training tool** | the given melody in counterpoint exercises — still today |

The second survives in the classroom; the first left behind an important idea: **an existing melody can serve as
the foundation of an entire work.** That idea later grew into [[concept:theme-variations|variation form]],
[[concept:pedal-point|ground bass]] and the whole family of "fixed material" writing.

## Where the cantus firmus may sit

Early practice placed it in the **lowest voice** (the word "tenor" literally means "holder"). Later writing freed
it to any position:

| Position | Effect |
|---|---|
| **bass** | most traditional; the harmonic frame is clearest |
| **top** | the cantus becomes the melodic protagonist and the others accompany |
| **inner voice** | the most concealed use — the cantus becomes a hidden thread |

The last is worth noting: **a cantus concealed in an inner voice is aimed at listeners who know the inside
story** — such hidden structures abound in Renaissance and Baroque music.

## How it differs from a ground bass (easily confused)

| | Cantus firmus | Ground bass |
|---|---|---|
| What is fixed | **a melody** (short or long, in any voice) | **a bass line** (usually short, repeating) |
| Does it repeat? | not necessarily | **yes, in a loop** |
| The other voices | usually set once per note | a new variation written for each cycle |

In one line: **a cantus firmus is a foundation; a ground bass is a foundation on repeat.**

## Diagram: one line fixed, the rest growing around it

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The cantus firmus (dark) does not change; the other voices are set around it note by note</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E8C547" text-anchor="middle">
      <text x="0" y="0">G</text><text x="70" y="0">F</text><text x="140" y="0">E</text>
      <text x="210" y="0">D</text><text x="280" y="0">C</text>
    </g>
    <g stroke="#E8C547" stroke-width="2.4">
      <line x1="-8" y1="-10" x2="288" y2="-10"/>
    </g>
    <text x="300" y="-6" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">cantus firmus: given, unchanged</text>

    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="-30">B♭</text><text x="70" y="-30">A</text><text x="140" y="-30">A♭</text>
      <text x="210" y="-30">F</text><text x="280" y="-30">E</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="42">D</text><text x="70" y="42">C</text><text x="140" y="42">C</text>
      <text x="210" y="42">A</text><text x="280" y="42">G</text>
    </g>
    <text x="0" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      The upper and lower voices are set note by note — the frame is fixed, only the writing remains
    </text>
    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      This is how the need to invent all voices at once is removed
    </text>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Unlike a ground bass: a cantus firmus need not repeat, a ground bass always does
    </text>
  </g>
</svg>
```

## Listen: writing over a fixed frame

Use `progression` on a functional progression and imagine the position of "the frame is given": **bass and
harmony are fixed; what you decide is the writing above.** That is precisely the situation cantus-firmus training
creates.

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"固定的功能骨架（I → IV → V → I）","label_en":"A fixed functional frame: I-IV-V-I","hint":"逐个和弦依次听 —— 骨架不变，变化都在上方","hint_en":"Hear each chord in turn — the frame holds, all change is above it"}
```

## Common misconceptions

- **"A cantus firmus is only an exercise."** It was also a central compositional device (the cantus-firmus Mass)
  and gave rise to variation form, ground bass and related practices.
- **"The cantus firmus must be in the bass."** That was early practice; later it may sit anywhere, and concealed in
  an inner voice it becomes a hidden structure.
- **"Cantus firmus and ground bass are the same thing."** The first is a melody (not necessarily repeating); the
  second is a repeating bass line.
- **"Using a cantus firmus is not composing."** Writing around it is the composing. Many of history's most complex
  polyphonic works are built on someone else's melody.
:::
