---
id: sight-reading
site: theo
cat: T12
title: 视奏
title_en: Sight-Reading
summary: 视奏练的核心只有一件事——不停下来
summary_en: Sight-reading trains one thing above all — not stopping
level: standard
tags: [乐理, 演奏, 实践]
tags_en: [theory, performance, practice]
alias: [视奏, 读谱演奏, sight-reading]
order: 20
links:
  - "[[concept:sight-singing]]"
  - "[[concept:ear-training]]"
  - "[[concept:practice-method]]"
  - "[[concept:ensemble-listening]]"
  - "[[concept:staff]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：结构最规整，是视奏入门时最容易保持不停顿的材料 | Scale and cadence exercises are the most regular, the easiest material for keeping going while sight-reading
  - mutopia-000522 | 《欢乐颂》主题：音域窄、节奏简单，适合用来练"先扫谱再开始"的流程 | The Ode of Joy has a narrow range and simple rhythm, good for practising "scan first, then start"
  - thesession-019704 | 《小星星》：极短且可完整预读，适合检验"未看完全曲前能否直接开弹" | Twinkle Little Star is short enough to pre-read wholly, useful for testing whether you can start before reading it all
sources:
  - 视奏训练的核心原则为保持连续性（不停顿），优于逐个音的正确性，为通行乐器教学表述
  - 视奏的预备流程（先看调号 / 拍号 / 难点与结构）与"必要时简化"的策略，为通行表述
updated: 2026-09-25
---

::: zh
视奏与视唱分工不同（见 [[concept:sight-singing|视唱方法]]）：

| | 视唱 | **视奏** |
|---|---|---|
| 做什么 | **唱** | **演奏** |
| 训练什么 | 内听觉 | **读谱与实时反应** |

视奏的核心原则，值得先单独说清：

> **视奏练的是"不停下来"。宁可错，也不要停。**

## 为什么"不停"比"对"更重要

因为**音乐的时间不会等你**：

| 选择 | 后果 |
|---|---|
| 停下来改对 | **整体崩掉** —— 节奏断了，其他人（或你自己）接不回去 |
| 错了继续走 | 音乐保持完整，**错误只影响一个瞬间** |

**这不是"放低标准"，而是"视奏的标准本来就不同"** ——
视奏的目标是**把谱面变成连续的音乐**，而不是"每个音都对"。

**这一点在合奏中尤其明显**：合奏时停下来，就是**全体等你** ——
所以合奏视奏的第一要求就是"不管发生什么都继续数拍"（见 [[concept:ensemble-listening|合奏与倾听]]）。

## 三步流程

| 步骤 | 做什么 | 时间 |
|---|---|---|
| **① 扫谱** | 看**调号 · 拍号 · 速度 · 难点**（大跳、变化音、节奏切换） | 十几秒 |
| **② 定速度** | 选一个**能从头走到尾**的速度 | 关键判断 |
| **③ 开始并坚持** | 出错不停，继续往下 | —— |

**第①步不用看完全曲**：只要抓住调号、拍号与"哪里会卡"就够 ——
**全看一遍反而会忘掉开头**。

**第②步最需要经验**：定太快会崩，定太慢会失去音乐性。
**宁慢勿快**是稳妥的选择 —— 慢速下"走完"远比快速下"崩掉"有价值。

## 一个必须学会的策略：简化

视奏中**允许简化**，而且这是正确做法：

| 简化方式 | 保留什么 |
|---|---|
| 丢内声部，保**外声部与低音** | 旋律与和声骨架 |
| 丢装饰音与次要音 | **节奏与时值** |
| 复杂和弦只弹**关键音** | 和声性质 |

**原则**：**优先保节奏与时值，其次保旋律线，最后才是完整织体。**
因为**节奏一乱，音乐就散了**；而少弹几个音，音乐还成立。

## 图示：不停下来是核心

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">视奏的两种选择：停下来的代价远大于错一个音</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">
      <text x="0" y="0">错了继续走</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="2.4">
      <line x1="0" y1="14" x2="420" y2="14"/>
    </g>
    <circle cx="150" cy="14" r="5" fill="#C0504A"/>
    <text x="150" y="34" font-family="system-ui,sans-serif" font-size="10" fill="#C0504A" text-anchor="middle">错点</text>
    <text x="436" y="18" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">音乐完整，只影响一个瞬间</text>

    <g transform="translate(0,66)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">
        <text x="0" y="0">停下来改对</text>
      </g>
      <g stroke="#C0504A" stroke-width="2.4">
        <line x1="0" y1="14" x2="150" y2="14"/>
      </g>
      <circle cx="150" cy="14" r="6" fill="none" stroke="#C0504A" stroke-width="2"/>
      <g stroke="#C0504A" stroke-width="1.4" stroke-dasharray="3 3">
        <line x1="150" y1="24" x2="150" y2="44"/>
      </g>
      <text x="150" y="60" font-family="system-ui,sans-serif" font-size="10" fill="#C0504A" text-anchor="middle">断掉</text>
      <text x="166" y="18" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">整体崩掉 —— 节奏断了，接不回去</text>
    </g>

    <text x="0" y="152" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      合奏中尤其明显：停下来就是全体等你 —— 所以第一要求是"不管发生什么都继续数拍"
    </text>
    <text x="0" y="174" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      简化原则：优先保节奏与时值 → 其次保旋律线 → 最后才是完整织体
    </text>
  </g>
</svg>
```

## 听一听：连续性的重要

用 `rhythm` 听一段**均匀连续**的形态 —— 这就是视奏要维持的状态：
**每个音按时出现，不停顿**。请留意"连续"本身给人的稳定感。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":80,"label":"连续不断（视奏要维持的状态）","label_en":"Unbroken continuity — the state sight-reading must maintain","hint":"点「播放」，注意每个音都按时出现","hint_en":"Press play and notice every note arriving on time"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q h","bpm":80,"label":"出现空隙（相当于“停下来”）","label_en":"A gap opens — the equivalent of stopping","hint":"与上一条对比：空隙破坏了连续性","hint_en":"Against the item above: the gap breaks the continuity"}

```

## 常见误解

- **「视奏就是第一次弹就弹对」** → 视奏的目标是**保持连续**，不是"每个音都对"。
- **「错了要马上回去改」** → 视奏中**绝不能回头** —— 停下来会破坏整体（合奏中更严重）。
- **「要先把全曲看一遍再开始」** → 只需扫调号、拍号与难点；**全看一遍会忘掉开头**。
- **「视奏必须完整演奏所有声部」** → **允许简化**：优先保节奏与旋律线，少弹几个音比崩掉好。
:::

::: en
Sight-reading and sight-singing do different jobs (see [[concept:sight-singing|sight-singing]]):

| | Sight-singing | **Sight-reading** |
|---|---|---|
| What you do | **sing** | **play** |
| What it trains | inner hearing | **reading and real-time response** |

The core principle deserves stating first:

> **Sight-reading trains you not to stop. Err rather than stop.**

## Why "keep going" matters more than "get it right"

Because **musical time does not wait for you**:

| Choice | Consequence |
|---|---|
| stop and correct it | **the whole thing collapses** — the pulse breaks and neither you nor anyone else can rejoin |
| keep going with the error | the music stays whole, and **the error affects one moment only** |

**This is not lowering the standard; the standard for sight-reading is simply different** — its aim is **to turn the
page into continuous music**, not to get every note right.

**It is most obvious in ensemble playing**: stopping means **everyone waiting for you** — so the first requirement of
ensemble sight-reading is "keep counting whatever happens" (see [[concept:ensemble-listening|ensemble listening]]).

## A three-step procedure

| Step | Do this | Time |
|---|---|---|
| **1 scan** | check **key, metre, tempo and the hard places** (leaps, accidentals, changes of rhythm) | a few seconds |
| **2 set a tempo** | choose one you can **sustain to the end** | the key judgement |
| **3 start and persist** | do not stop for errors, keep moving | — |

**Step 1 does not mean reading everything**: catching the key, the metre and "where it will stick" is enough —
**reading it all through makes you forget the opening**.

**Step 2 needs experience**: too fast and it collapses, too slow and the music evaporates. **Slower is safer** —
getting to the end slowly beats collapsing quickly.

## A strategy you must learn: simplifying

**Simplifying is allowed in sight-reading, and it is the right thing to do**:

| What to drop | What is kept |
|---|---|
| inner voices, keeping **outer voices and bass** | melody and harmonic skeleton |
| ornaments and secondary notes | **rhythm and durations** |
| all but the **essential notes** of a complex chord | the chord's quality |

**The principle**: **rhythm and durations first, then the melodic line, and only last the full texture.** Because
**once the rhythm goes, the music falls apart**, whereas playing fewer notes still holds together.

## Diagram: not stopping is the core

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Two choices in sight-reading: the cost of stopping far exceeds one wrong note</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">
      <text x="0" y="0">keep going with the error</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="2.4">
      <line x1="0" y1="14" x2="420" y2="14"/>
    </g>
    <circle cx="150" cy="14" r="5" fill="#C0504A"/>
    <text x="150" y="34" font-family="system-ui,sans-serif" font-size="10" fill="#C0504A" text-anchor="middle">the error</text>
    <text x="436" y="18" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">the music stays whole</text>

    <g transform="translate(0,66)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">
        <text x="0" y="0">stop and correct</text>
      </g>
      <g stroke="#C0504A" stroke-width="2.4">
        <line x1="0" y1="14" x2="150" y2="14"/>
      </g>
      <circle cx="150" cy="14" r="6" fill="none" stroke="#C0504A" stroke-width="2"/>
      <g stroke="#C0504A" stroke-width="1.4" stroke-dasharray="3 3">
        <line x1="150" y1="24" x2="150" y2="44"/>
      </g>
      <text x="150" y="60" font-family="system-ui,sans-serif" font-size="10" fill="#C0504A" text-anchor="middle">broken</text>
      <text x="166" y="18" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">everything collapses, and the pulse cannot be rejoined</text>
    </g>

    <text x="0" y="152" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Most obvious in ensemble: stopping means everyone waits — keep counting whatever happens
    </text>
    <text x="0" y="174" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Simplifying: rhythm and durations first, then the melodic line, last the full texture
    </text>
  </g>
</svg>
```

## Listen: the importance of continuity

Use `rhythm` on an **even, unbroken** shape — the state sight-reading must maintain: **every note arriving on time,
no pauses**. Notice how much stability continuity itself provides.

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":80,"label":"连续不断（视奏要维持的状态）","label_en":"Unbroken continuity — the state sight-reading must maintain","hint":"点「播放」，注意每个音都按时出现","hint_en":"Press play and notice every note arriving on time"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q h","bpm":80,"label":"出现空隙（相当于停下来）","label_en":"A gap opens — the equivalent of stopping","hint":"与上一条对比：空隙破坏了连续性","hint_en":"Against the item above: the gap breaks the continuity"}
```

## Common misconceptions

- **"Sight-reading means getting it right the first time."** Its aim is **continuity**, not every note correct.
- **"You should go back and fix mistakes at once."** In sight-reading **never go back** — stopping breaks the whole
  (worse still in ensemble).
- **"Read the whole piece before starting."** Only scan the key, metre and hard places; **reading it all makes you
  forget the opening**.
- **"You must play every voice."** **Simplifying is allowed**: rhythm and melody first; playing fewer notes beats
  collapsing.
:::
