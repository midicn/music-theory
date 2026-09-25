---
id: interval-hearing
site: theo
cat: T11
title: 音程听辨（调内）
title_en: Hearing Intervals in Context
summary: 同一个音程在不同调内位置，意义完全不同
summary_en: The same interval means entirely different things in different positions in a key
level: standard
tags: [乐理, 练耳, 音程]
tags_en: [theory, ear training, intervals]
alias: [音程听辨, 调内音程, interval hearing]
order: 20
links:
  - "[[concept:interval-ear-training]]"
  - "[[concept:ear-training]]"
  - "[[concept:scale-hearing]]"
  - "[[concept:interval-melodic-role]]"
  - "[[concept:harmonic-function]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：级进为主、音域窄，是练"听级数关系"最省力的材料 | The Ode of Joy moves mostly by step within a narrow range, the easiest material for hearing degree relations
  - thesession-019704 | 《小星星》：五音两值，可用来验证"同一个音程在不同位置是否听感不同" | Twinkle Little Star uses five notes and two values, useful for testing whether one interval feels different in different positions
  - giantmidi-006222 | 音阶与终止练习：级进走法清楚，适合建立"级数地图"再回头听音程 | Scale and cadence exercises have clear stepwise motion, good for building a degree map before returning to intervals
sources:
  - 调内音程听辨与孤立音程听辨的区别（前者以主音为参照、后者脱离脉络），为通行视唱练耳教学表述
  - 同一音程在不同调内位置承担不同功能，为通行和声学与练耳教学结论
updated: 2026-09-25
---

::: zh
本站另有一条 [[concept:interval-ear-training|音程的听辨方法]]（在 T2）—— 分工很清楚：

> **那条讲"音程是什么、怎么孤立地听"；**
> **本条讲"把音程放在调性框架里听"，以及为什么这样听更有效。**

## 核心洞见：音程的"身份"取决于位置

同一个音程，在不同调内位置上的**功能与听感完全不同**：

| 音程 | 出现的位置 | 听感与功能 |
|---|---|---|
| **大三度** | 在 **I 级**上（如 C–E） | 稳定、明亮 —— 它本身就是主和弦的构成 |
| **大三度** | 在 **V 级**上（如 G–B） | **带张力**：B 是导音，强烈指向主音（见 [[concept:harmonic-function\|和声功能]]） |

**两个都是大三度，但一个"落定"、一个"要走"** ——
所以**孤立地听音程，只能得到"这是大三度"这个贫乏的信息**（与 [[concept:ear-training|练耳]] 里"练习材料是去脉络化的"是同一件事）。

## 正确顺序：先建地图，再听音程

| 步骤 | 做什么 |
|---|---|
| **① 建立主音** | 用终止式或结尾确定中心（见 [[concept:scale-hearing\|调性听辨]]） |
| **② 听级数** | 每个音**与主音的关系**（一级？五级？） |
| **③ 再听音程** | 相邻音之间的距离与方向 |

**第②步是关键，也是最常被跳过的一步。** 它的意思是：
**不要问"这两个音之间是几度"，而要问"这两个音分别在调里是第几级"。**

| 听法 | 得到的信息 |
|---|---|
| "这是大三度" | 孤立、贫乏 |
| "这是从三级到五级" | **带功能的信息**（可判断它要往哪走） |

## 一条实用的辅助技巧（及其边界）

**用已知旋律当"锚"** 是常见的入门方法：

| 音程 | 可用的锚 |
|---|---|
| 大三度 | 《欢乐颂》开头（C–E 那类上行大三度） |
| 纯四度 | 《婚礼进行曲》开头 |
| 小三度 | 《欢乐颂》中的下行小三度 |

**但要注意它的边界**：

| 锚能做什么 | 锚不能做什么 |
|---|---|
| 帮你**快速识别**一个孤立音程 | **不能**告诉你它在调里做什么 |
| 入门阶段降低门槛 | 依赖锚会**延缓调内听觉的建立** |

**所以锚是"拐杖"，不是"腿"** —— 入门可用，但目标是不需要它。

## 图示：同一个大三度的两种身份

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样的音程，位置不同则功能不同 —— 所以"先建地图再听音程"</text>
  </g>

  <g transform="translate(52,58)">
    <g>
      <rect x="0" y="-14" width="230" height="28" rx="3" fill="#5B7FA8"/>
      <text x="115" y="5" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">I 级上的大三度 C–E</text>
      <text x="246" y="5" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">→ 稳定、明亮（主和弦自身）</text>
    </g>

    <g transform="translate(0,48)">
      <rect x="0" y="-14" width="230" height="28" rx="3" fill="#E07A3F"/>
      <text x="115" y="5" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">V 级上的大三度 G–B</text>
      <text x="246" y="5" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">→ 带张力（B 是导音，指向主音）</text>
    </g>

    <g transform="translate(0,96)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        正确顺序：① 建主音 → ② 听级数（与主音的关系）→ ③ 再听相邻音程
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        问"这是几度"得到的是孤立信息；问"这是从三级到五级"才带功能信息
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        已知旋律作"锚"是拐杖不是腿：入门可用，但目标是不依赖它
      </text>
    </g>
  </g>
</svg>
```

## 听一听：同一个音程、两种处境

用 `interval` 听**同一个大三度 C–E**。它听起来"稳定明亮"。
现在想象它出现在属和弦上（G–B）—— **同样的音程宽度，但因为 B 是导音，它会强烈要求走向主音**。
音频无法直接演示两种调内处境，但这个对比正是本条的核心。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度（孤立听：只有“宽度”这一个信息）","label_en":"A major third heard in isolation: only its width","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"要判断它“要往哪走”，必须知道它在调里的位置 —— 这就是本条与孤立音程听辨的区别。","hint2_en":"To judge where it wants to go you must know its position in the key — the difference between this entry and hearing intervals in isolation."}

```

## 常见误解

- **「音程听辨就是听出几度」** → 那只得到**孤立信息**。调内音程听辨问的是**"第几级到第几级"**。
- **「同一个音程听起来总是一样」** → 不一样。**位置不同，功能与听感都不同**。
- **「用旋律当锚就够了」** → 锚是**拐杖**：入门可用，但它**不能告诉你音程在调里做什么**。
- **「要先练好孤立音程，再练调内」** → 更有效的是**尽早建立主音与级数地图**（见 [[concept:scale-hearing|调性听辨]]）——
  有了地图，音程自然有位置。
:::

::: en
This site has a separate entry on [[concept:interval-ear-training|methods for hearing intervals]] (under T2), and the
division of labour is clear:

> **That one covers what intervals are and how to hear them in isolation;**
> **this one covers hearing intervals inside a tonal frame, and why that works better.**

## The core insight: an interval's identity depends on its position

The same interval has **entirely different function and feel** in different positions in a key:

| Interval | Position | Feel and function |
|---|---|---|
| **major third** | on **degree I** (C–E) | stable, bright — it *is* the tonic triad |
| **major third** | on **degree V** (G–B) | **tense**: B is the leading tone, strongly pointing to the tonic (see [[concept:harmonic-function\|harmonic function]]) |

**Both are major thirds, yet one settles and the other must move** — so **hearing an interval in isolation yields
only the meagre information "that is a major third"** (the same point as "exercise material is decontextualised"
under [[concept:ear-training|ear training]]).

## The right order: build the map, then hear intervals

| Step | Do this |
|---|---|
| **1 establish the tonic** | fix the centre by cadence or the ending (see [[concept:scale-hearing\|hearing key]]) |
| **2 hear the degrees** | each note's **relation to the tonic** (degree 1? degree 5?) |
| **3 then hear intervals** | the distance and direction between adjacent notes |

**Step 2 is the key and the most often skipped.** It means: **do not ask "how many degrees apart are these two
notes" but "which degree is each of them in the key".**

| Listening | Information obtained |
|---|---|
| "that is a major third" | isolated, meagre |
| "that is from degree 3 to degree 5" | **functional information** (you can tell where it wants to go) |

## A useful crutch — and its limits

**Using a known melody as an anchor** is a common beginner method:

| Interval | Usable anchor |
|---|---|
| major third | the opening of the Ode of Joy |
| perfect fourth | the opening of the Wedding March |
| minor third | the descending minor third in the Ode of Joy |

**But note its limits**:

| An anchor can | An anchor cannot |
|---|---|
| help you **quickly identify** an isolated interval | tell you **what it does in the key** |
| lower the barrier at the start | replace tonal hearing — relying on it **delays** it |

**So an anchor is a crutch, not a leg**: usable at the beginning, with the goal of not needing it.

## Diagram: two identities for one major third

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same interval, different position, different function — hence build the map first</text>
  </g>

  <g transform="translate(52,58)">
    <g>
      <rect x="0" y="-14" width="230" height="28" rx="3" fill="#5B7FA8"/>
      <text x="115" y="5" font-family="system-ui,sans-serif" font-size="11" fill="#F2EEE6" text-anchor="middle">major third on I: C-E</text>
      <text x="246" y="5" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">stable, bright — the tonic triad itself</text>
    </g>

    <g transform="translate(0,48)">
      <rect x="0" y="-14" width="230" height="28" rx="3" fill="#E07A3F"/>
      <text x="115" y="5" font-family="system-ui,sans-serif" font-size="11" fill="#1A0E06" text-anchor="middle">major third on V: G-B</text>
      <text x="246" y="5" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">tense: B is the leading tone, pointing home</text>
    </g>

    <g transform="translate(0,96)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        Right order: build the tonic, hear the degrees, then hear adjacent intervals
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        "Which degree" carries function; "how many degrees apart" does not
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        A melodic anchor is a crutch, not a leg: useful at the start, not the goal
      </text>
    </g>
  </g>
</svg>
```

## Listen: one interval, two situations

Use `interval` to hear **the same major third C–E**. It sounds stable and bright. Now imagine it on the dominant
(G–B) — **the same width, but because B is the leading tone it demands to resolve to the tonic.** The audio cannot
stage both tonal contexts, yet this contrast is the entry's core.

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度（孤立听只有宽度这一个信息）","label_en":"A major third heard in isolation: only its width","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"要判断它要往哪走，必须知道它在调里的位置 —— 这就是本条与孤立音程听辨的区别。","hint2_en":"To judge where it wants to go you must know its position in the key — the difference between this entry and hearing intervals in isolation."}
```

## Common misconceptions

- **"Interval hearing means naming the number"** — that gives **isolated information**. Tonal interval hearing asks
  **"from which degree to which degree".**
- **"The same interval always sounds the same."** It does not: **position changes function and feel**.
- **"Melodic anchors are enough."** They are a **crutch**: usable at the start, but they **cannot tell you what the
  interval does in the key**.
- **"Learn isolated intervals first, then tonal ones."** More effective is **building the tonic and degree map early**
  (see [[concept:scale-hearing|hearing key]]) — with the map, intervals have positions.
:::
