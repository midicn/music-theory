---
id: imitation
site: theo
cat: T6
title: 模仿
title_en: Imitation
summary: 一条线刚说过的话，另一条线跟着说——复调音乐最经济的手法
summary_en: One line says something, another says it back — the most economical device in polyphony
level: core
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [模仿, 模仿式复调, imitation]
order: 22
links:
  - "[[concept:counterpoint]]"
  - "[[concept:canon]]"
  - "[[concept:fugue]]"
  - "[[concept:sequence]]"
  - "[[concept:contrapuntal-devices]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：主题在两个声部先后进入，是模仿最干净的样本 | Bach's first two-part invention — the subject enters in one voice then the other, the cleanest sample of imitation
  - atepp-001875 | 巴赫三声部创意曲 BWV 787：同一个素材在三个声部轮流出现，模仿的立体感更明显 | Bach's three-part invention BWV 787 — the same material passes through three voices, imitation in stronger relief
  - mutopia-000287 | 巴赫第八首二部创意曲：模仿的进入间隔与音程与上一条不同，可对照"同一手法、不同处理" | Bach's eighth two-part invention — a different entry interval and spacing for the same device
sources:
  - 模仿指一条旋律线在其他声部依次重现，属对位学通则
  - 严格模仿与自由模仿、紧接模仿（stretto）的分类为通行对位教学表述
updated: 2026-09-24
---

::: zh
模仿的做法一句话：**一条线刚说过的东西，另一条线跟着说一遍。**

> 素材只用一次，但**被听到两次以上** —— 这就是它的全部价值。

## 为什么它这么有用

因为它同时解决了复调写作的两个难题：

| 难题 | 模仿如何解决 |
|---|---|
| **素材从哪来** | 不必不断写新东西，一个乐思可以反复使用 |
| **怎么让多声部"像一个整体"** | 同一个素材出现在不同声部 → 统一的听觉印记 |

所以它是复调里**最经济**的手法：**投入最少（只写一次），效果最强（多声部统一）**。

## 模仿的三个变量

写作时真正要决定的只有三件事：

| 变量 | 常见选择 | 效果差别 |
|---|---|---|
| **进入音程** | 同度 / 八度 / 五度 / 其他 | 八度最统一；五度带来"属调色彩"；其他音程会产生调式变化 |
| **进入间隔** | 一小节 / 半小节 / 更短 | **间隔越短，越紧凑**；缩到极短就是「紧接」（stretto） |
| **严格程度** | 严格 / 自由 | 严格＝音程完全照搬；自由＝按和声需要调整（更常见） |

第三行的取舍很实际：**严格模仿听起来更"整"，但更容易与和声冲突**。
实际写作里通常是**大致严格、局部调整**。

## 与另外两种手法的区别

三种手法都用"重复素材"，但方向不同：

| 手法 | 重复方式 | 方向 |
|---|---|---|
| **重复** | 同一高度、同一声部 | 不动 |
| **模进** | 换高度、**同一声部** | **横向**（见 [[concept:sequence|模进]]） |
| **模仿** | 同一素材、**不同声部** | **纵向**（本条） |

一句话：**模进是把素材往上搬，模仿是把素材换个声部交代。**

## 模仿的极致：卡农

如果模仿**完整而且持续**（整条旋律一句不落地被追随，一直跟到底），那就是
[[concept:canon|卡农]]。所以两者的关系是：

> **模仿是手法，卡农是"把模仿用到极致"的形态。**

同样，[[concept:fugue|赋格]]的每一次声部进入也都是模仿 —— 赋格是把模仿组织成一整套结构。

## 图示：素材在声部之间传递

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一段素材，从高音传到低音，再传回来 —— 素材只写了一次</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-32" y="6" text-anchor="end">高</text>
      <text x="-32" y="60" text-anchor="end">低</text>
    </g>
    <g>
      <rect x="0" y="-6" width="120" height="18" rx="3" fill="#E07A3F" opacity=".9"/>
      <text x="60" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">主题</text>
      <rect x="150" y="-6" width="120" height="18" rx="3" fill="#5B7FA8" opacity=".9"/>
      <text x="210" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">主题（模仿）</text>
      <rect x="300" y="-6" width="120" height="18" rx="3" fill="#E07A3F" opacity=".75"/>
      <text x="360" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">主题（再进入）</text>
    </g>
    <g>
      <rect x="0" y="48" width="120" height="18" rx="3" fill="#343439"/>
      <rect x="150" y="48" width="120" height="18" rx="3" fill="#E07A3F" opacity=".9"/>
      <text x="210" y="61" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">主题</text>
      <rect x="300" y="48" width="120" height="18" rx="3" fill="#5B7FA8" opacity=".9"/>
      <text x="360" y="61" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">主题（模仿）</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="120" y1="0" x2="150" y2="48"/>
      <line x1="270" y1="54" x2="300" y2="0"/>
    </g>
    <text x="0" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      进入间隔越短越紧凑；缩到极短就是「紧接」（stretto）
    </text>
    <text x="0" y="114" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      三个变量：进入音程 / 进入间隔 / 严格程度 —— 写作时要决定的只有这三件
    </text>
  </g>
</svg>
```

## 听一听：素材的两次出现

模仿是声部之间的事，本站的听辨件放不出真正的两声部 —— 所以这里用 `interval` 演示
模仿**进入时的音程**（第二个声部从哪个高度进来），而这正是模仿最关键的变量之一。
声部之间传递的效果请到上面的实例里听（巴赫二部创意曲是最短路径）。

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"进入音程：上方五度","label_en":"Entry interval: a fifth above","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 C5 就是八度进入（最统一），换成 E4 则是三度进入（色彩变化更明显）。","hint2_en":"Set b to C5 for entry at the octave (the most unified), or E4 for entry at a third (a more pronounced colour change)."}
```

## 常见误解

- **「模仿就是重复」** → 重复在同一高度、同一声部；模仿**换声部**，这是两种不同的手法。
- **「模仿必须完全一样」** → 严格模仿只是其中一种。实际写作里**自由模仿更常见** —— 按和声需要调整音程。
- **「模仿只属于巴洛克」** → 爵士的"呼应"（call and response）、流行歌里主唱与和声的交替、电影配乐里的主题传递，都是模仿。
- **「模仿和卡农是一回事」** → 卡农是**完整且持续**的模仿；模仿只是那个手法本身，可以只用一次就转向别处。
:::

::: en
Imitation in one line: **one line says something, another line says it back.**

> The material is written once but **heard two or more times** — that is its entire value.

## Why it is so useful

Because it solves polyphony's two problems at once:

| Problem | How imitation solves it |
|---|---|
| **where does material come from** | no need to keep inventing; one idea can be reused |
| **how do several voices sound like one piece** | the same material in different voices gives a unifying aural stamp |

So it is the **most economical** device in polyphony: **least input (written once), strongest effect (unified
voices)**.

## The three variables

When writing, only three decisions really matter:

| Variable | Common choices | Difference |
|---|---|---|
| **entry interval** | unison / octave / fifth / other | an octave is the most unified; a fifth brings dominant colour; other intervals alter the mode |
| **entry spacing** | a bar / half a bar / shorter | **the shorter the spacing, the tighter**; at the extreme it becomes a **stretto** |
| **strictness** | strict / free | strict copies the intervals exactly; free adjusts them to the harmony (more common) |

The third is a practical trade-off: **strict imitation sounds more unified but clashes more easily with the
harmony**. Real writing is usually **approximately strict, adjusted locally**.

## How it differs from two related devices

All three reuse material, but in different directions:

| Device | How it repeats | Direction |
|---|---|---|
| **repetition** | same pitch, same voice | no movement |
| **sequence** | new pitch, **same voice** | **horizontal** (see [[concept:sequence|sequence]]) |
| **imitation** | same material, **different voice** | **vertical** (this entry) |

In one line: **a sequence carries the material upward; imitation hands it to another voice.**

## The extreme case: canon

If the imitation is **complete and continuous** — the whole line followed faithfully to the end — that is a
[[concept:canon|canon]]. So the relation is:

> **Imitation is the device; canon is imitation taken to its limit.**

Equally, every voice entry in a [[concept:fugue|fugue]] is an imitation — a fugue organises imitation into an
entire structure.

## Diagram: material passed between voices

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One figure passed from the top voice to the bottom and back — written once</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-32" y="6" text-anchor="end">high</text>
      <text x="-32" y="60" text-anchor="end">low</text>
    </g>
    <g>
      <rect x="0" y="-6" width="120" height="18" rx="3" fill="#E07A3F" opacity=".9"/>
      <text x="60" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">subject</text>
      <rect x="150" y="-6" width="120" height="18" rx="3" fill="#5B7FA8" opacity=".9"/>
      <text x="210" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">subject (imitated)</text>
      <rect x="300" y="-6" width="120" height="18" rx="3" fill="#E07A3F" opacity=".75"/>
      <text x="360" y="7" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">subject again</text>
    </g>
    <g>
      <rect x="0" y="48" width="120" height="18" rx="3" fill="#343439"/>
      <rect x="150" y="48" width="120" height="18" rx="3" fill="#E07A3F" opacity=".9"/>
      <text x="210" y="61" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">subject</text>
      <rect x="300" y="48" width="120" height="18" rx="3" fill="#5B7FA8" opacity=".9"/>
      <text x="360" y="61" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">subject (imitated)</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="120" y1="0" x2="150" y2="48"/>
      <line x1="270" y1="54" x2="300" y2="0"/>
    </g>
    <text x="0" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      The tighter the spacing, the closer the weave — at the extreme it is a stretto
    </text>
    <text x="0" y="114" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Three variables: entry interval, entry spacing, strictness — the only decisions to make
    </text>
  </g>
</svg>
```

## Listen: the entry interval

Imitation happens between voices, and this site's listening components are single-voice — so `interval`
demonstrates **the interval at which the second voice enters**, which is one of imitation's key variables. For
the effect of passing between voices, use the instances above; Bach's two-part inventions are the shortest route.

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"进入音程：上方五度","label_en":"Entry interval: a fifth above","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 C5 就是八度进入（最统一），换成 E4 则是三度进入（色彩变化更明显）。","hint2_en":"Set b to C5 for entry at the octave (the most unified), or E4 for entry at a third (a more pronounced colour change)."}
```

## Common misconceptions

- **"Imitation is repetition."** Repetition stays at the same pitch in the same voice; imitation **changes voice**.
  Two different devices.
- **"Imitation must be exact."** Strict imitation is only one kind. **Free imitation is more common** — intervals
  adjusted to fit the harmony.
- **"Imitation belongs to the Baroque."** Jazz call and response, a pop lead trading with its backing vocals, and
  a film score passing a theme between sections are all imitation.
- **"Imitation and canon are the same."** A canon is **complete and continuous** imitation; imitation itself is
  the device, and may be used once before the music turns elsewhere.
:::
