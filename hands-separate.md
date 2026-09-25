---
id: hands-separate
site: theo
cat: T12
title: 分手与分声部练习
title_en: Hands Separate
summary: 它降低的是"同时处理的信息量"——而合手本身是新任务
summary_en: It reduces the amount to process at once — and combining is a new task in itself
level: standard
tags: [乐理, 演奏, 练习]
tags_en: [theory, performance, practice]
alias: [分手练习, 分声部练习, hands separate]
order: 18
links:
  - "[[concept:practice-method]]"
  - "[[concept:slow-practice]]"
  - "[[concept:counterpoint]]"
  - "[[concept:rhythm-training]]"
  - "[[concept:memorization]]"
instances:
  - atepp-000083 | 斯克里亚宾第一钢琴奏鸣曲：两手分工复杂，分手练习的必要性最明显 | Scriabin's Piano Sonata No.1 gives the hands very different work, where hands-separate practice is plainly necessary
  - mutopia-000522 | 《欢乐颂》主题：结构简单，可用于验证"分手练熟后合手是否仍然出错" | The Ode of Joy is simple enough to test whether hands still fail on combining after being learnt separately
  - giantmidi-006222 | 音阶与终止练习：音阶可用"先分手、再慢速合手"的标准流程练 | Scale and cadence exercises suit the standard sequence of separate hands, then slow combination
sources:
  - 分手练习的作用为降低同时处理的信息量；合手本身是独立任务，须单独练习与降速，为通行乐器教学表述
  - 分声部练习（复调作品按声部练习）的必要性源自各声部的独立性，为通行表述
updated: 2026-09-25
---

::: zh
分手练习的真正作用，常被说成"因为手不熟"。更准确的表述是：

> **它降低的是"同时需要处理的信息量"。**

## 三层"分"

| 层次 | 分什么 | 适用 |
|---|---|---|
| **① 分手** | 左手 / 右手 | 键盘乐器 |
| **② 分声部** | 各旋律线（见 [[concept:counterpoint\|对位]]） | 复调作品、弦乐四重奏、合唱 |
| **③ 分音层** | 旋律 / 伴奏 / 低音 | 主调织体 |

**第②层与第①层不同**：分手是"按手分"，分声部是"**按线分**" ——
在复调作品里，**一只手常常要负责两条线**（而这两条线本身也值得分别练）。

**所以"分声部"比"分手"更接近音乐本身的结构** ——
它是按**声部**而非按**肢体**切分。

## 关键：合手不是"相加"

这是本条最容易被误解的一点：

> **合手本身是一个新任务，不是"两只手各自练好之后自然就合上了"。**

| 前提 | 结果 |
|---|---|
| 分手都练得很熟 | **仍然可能在合手时崩** |
| 分手熟 + **单独练"合"** | 才能真正合上 |

**为什么**：合手意味着**同时做两件事**，这是一个新的协调任务 ——
就像"会左手画圆、右手画方"不等于"能同时画"。

**所以合手要按独立任务对待**：

| 步骤 | 做法 |
|---|---|
| 1 | 分手各自练到能不出错 |
| 2 | **慢速合手**（比单手练习慢得多） |
| 3 | 逐步提速，**回到整曲** |

**第②步的"慢"容易被忽略**：很多人一手熟了就按原速合 —— 那几乎必然出错。
**合手的速度应当比单手更慢**，因为要处理的信息量更大。

## 一个常见的错误顺序

| 错误做法 | 问题 |
|---|---|
| 先快速合手试一遍，崩了再分手 | 在**重复错误**（见 [[concept:practice-method\|练习方法]]） |
| 只分手练，从不单独练合 | 直到演出前才第一次认真合手 |
| 合手时只盯着难的声部 | 另一只手失去控制 |

**第一行最普遍**：先"试"一遍再练，实际上**先给错误的动作做了一遍示范**。

## 图示：分与合是两件事

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">分手熟 ≠ 合手熟：合手是需要单独练的新任务</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">分</text>
      <text x="-20" y="54" text-anchor="end">合</text>
    </g>

    <g>
      <rect x="0" y="-12" width="90" height="24" rx="3" fill="#5B7FA8"/>
      <text x="45" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">右手</text>
      <rect x="98" y="-12" width="90" height="24" rx="3" fill="#5B7FA8" opacity=".75"/>
      <text x="143" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">左手</text>
      <text x="202" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">各自练到不出错（信息量小）</text>
    </g>

    <g transform="translate(0,54)">
      <rect x="0" y="-12" width="188" height="24" rx="3" fill="#E07A3F"/>
      <text x="94" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">合手（同时处理两件事）</text>
      <text x="202" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">← 新的协调任务，必须降速单独练</text>
    </g>

    <text x="0" y="94" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      类比例子：会左手画圆、右手画方，不等于能同时画 —— 合手不是"相加"
    </text>
    <text x="0" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      分声部比分手更接近音乐结构：复调作品里一只手常负责两条线，这两条线也值得分别练
    </text>
    <text x="0" y="138" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      常见错误顺序：先快速合手试一遍，崩了再分手 —— 那等于先给错误动作做了一遍示范
    </text>
  </g>
</svg>
```

## 听一听：两条独立线

分手/分声部练习的对象是**独立的线**。本站放不出两声部，但可以用 `interval` 感受**两条线在同一时刻的关系**——
**每条线各自连续、合起来才成和声**，这就是分声部练习要建立的听感。

```audiolab
{"type":"interval","a":"C4","b":"A4","label":"两条线的某一时刻（六度）","label_en":"One instant of two lines: a sixth","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"分声部练习的目标：每条线单独听像旋律，合起来才成和声（见对位那条）。","hint2_en":"The aim of part practice: each line is a melody on its own, and only together do they make harmony."}
```

## 常见误解

- **「分手练习是为了手熟」** → 更准确地说，是**降低同时处理的信息量**。
- **「两只手各自练好，合起来自然就行」** → **合手是新任务**，必须单独练，且**比单手更慢**。
- **「分声部就是分手」** → 不同：分手按**肢体**切，分声部按**音乐线条**切。复调作品里一只手可能有两条线。
- **「合手前先快速试一遍」** → 那是在**重复错误**，等于先示范一遍错的。应当**直接慢速开始**。
:::

::: en
Hands-separate practice is usually explained as "because the hands are not ready". More precisely:

> **It reduces the amount of information that must be handled at once.**

## Three ways to "separate"

| Level | Separated by | Applies to |
|---|---|---|
| **1 hands** | left / right | keyboard instruments |
| **2 parts** | each melodic line (see [[concept:counterpoint\|counterpoint]]) | polyphony, string quartets, choirs |
| **3 layers** | melody / accompaniment / bass | homophonic textures |

**Level 2 differs from level 1**: separating hands divides by **limb**, separating parts by **line** — and in
polyphonic music **one hand often carries two lines**, each of which also deserves separate practice.

**So part practice is closer to the music's own structure** — it divides by **voice**, not by **body**.

## The key point: combining is not addition

The most easily misread point here:

> **Combining is a new task, not something that happens automatically once each hand is ready.**

| Premise | Result |
|---|---|
| both hands well practised | **combining may still collapse** |
| both hands ready + **practising the combination itself** | it works |

**Why**: combining means **doing two things at once**, a new coordination task — like "can draw a circle with the
left hand and a square with the right" not implying "can do both simultaneously".

**So treat combining as an independent task**:

| Step | Do this |
|---|---|
| 1 | each hand practised to the point of no errors |
| 2 | **combine slowly** (much slower than the single-hand tempo) |
| 3 | raise the tempo gradually, **back to the whole piece** |

**The slowness of step 2 is easily missed**: many people combine at the original tempo as soon as one hand is ready —
which almost guarantees errors. **The combining tempo should be slower than either hand's**, because more information
is being processed.

## A common wrong order

| Wrong practice | Problem |
|---|---|
| try combining fast first, then separate when it collapses | **repeating errors** (see [[concept:practice-method\|how to practise]]) |
| practise hands separately only, never the combination | combining seriously for the first time just before a performance |
| watching only the difficult part when combining | the other hand loses control |

**The first is the commonest**: "trying" it once before practising gives **a demonstration of the wrong action**.

## Diagram: separating and combining are two things

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Hands ready separately does not mean the combination is ready: it is a new task</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">apart</text>
      <text x="-20" y="54" text-anchor="end">together</text>
    </g>

    <g>
      <rect x="0" y="-12" width="90" height="24" rx="3" fill="#5B7FA8"/>
      <text x="45" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">right</text>
      <rect x="98" y="-12" width="90" height="24" rx="3" fill="#5B7FA8" opacity=".75"/>
      <text x="143" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">left</text>
      <text x="202" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">each to the point of no errors</text>
    </g>

    <g transform="translate(0,54)">
      <rect x="0" y="-12" width="188" height="24" rx="3" fill="#E07A3F"/>
      <text x="94" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">combined: two things at once</text>
      <text x="202" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">a new coordination task: slow, and practised on its own</text>
    </g>

    <text x="0" y="94" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Analogy: drawing a circle and a square separately does not mean doing both at once
    </text>
    <text x="0" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Part practice is closer to the music's structure: one hand may carry two lines, each worth practising
    </text>
    <text x="0" y="138" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      Common wrong order: try it fast, then separate when it fails — that demonstrates the wrong action first
    </text>
  </g>
</svg>
```

## Listen: two independent lines

The object of part practice is **independent lines**. This site cannot play two voices, but `interval` lets you feel
**the relation of two lines at one instant** — **each line continuous on its own, harmony only when combined**, which
is the aural aim of part practice.

```audiolab
{"type":"interval","a":"C4","b":"A4","label":"两条线的某一时刻（六度）","label_en":"One instant of two lines: a sixth","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"分声部练习的目标：每条线单独听像旋律，合起来才成和声。","hint2_en":"The aim of part practice: each line is a melody on its own, and only together do they make harmony."}
```

## Common misconceptions

- **"Hands separate is for hand readiness."** More precisely, it **reduces the information to be processed at once**.
- **"Once both hands are ready, combining follows."** **Combining is a new task**, practised separately and **slower
  than either hand**.
- **"Part practice is hands separate."** They differ: one divides by **limb**, the other by **musical line**. In
  polyphony one hand may carry two lines.
- **"Try it fast first, then separate."** That is **repeating errors** — a demonstration of the wrong action.
  **Start slowly instead.**
:::
