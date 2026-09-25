---
id: accidentals
site: theo
cat: T10
title: 变音记号
title_en: Accidentals
summary: 五种记号、一条范围规则、三种用途
summary_en: Five signs, one scope rule, three uses
level: standard
tags: [乐理, 记谱, 基础]
tags_en: [theory, notation, basics]
alias: [变音记号, 临时记号, 升号, 降号, 还原号, accidentals]
order: 20
links:
  - "[[concept:key-signature]]"
  - "[[concept:enharmonic]]"
  - "[[concept:chromatic]]"
  - "[[concept:harmonic-minor]]"
  - "[[concept:leading-tone-chord]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：谱面简洁，可用于确认"哪些音需要临时记号" | Scale and cadence exercises are clean enough for checking which notes need accidentals
  - atepp-000318 | a 小调奏鸣曲：小调的导音常需升高（临时记号），是"变音为功能服务"的实例 | A sonata in A minor — the leading tone is usually raised, an instance of accidentals serving function
  - cyberhymnal-000695 | 管风琴圣咏：传统写法里临时记号克制，可作"少用变音"的对照 | An organ hymn — accidentals are restrained in traditional writing, a control for "few accidentals"
sources:
  - 变音记号共五种（升 / 降 / 还原 / 重升 / 重降），作用于本小节内同高度的音，为记谱法通则
  - 等音写作（重升 / 重降的使用）与和声意义的关联，为通行乐理与记谱规范表述
updated: 2026-09-25
---

::: zh
变音记号（accidentals）共**五种**，但规则只有**一条**，用途有**三种**。

## 五种记号

| 记号 | 名称 | 作用 |
|---|---|---|
| **♯** | 升号 | 升高半音 |
| **♭** | 降号 | 降低半音 |
| **♮** | 还原号 | 取消前面的升降，回到本位 |
| **𝄪** | 重升号 | 升高两个半音（= 一个全音） |
| **𝄫** | 重降号 | 降低两个半音 |

**重升与重降看起来奇怪，但有明确的必要性**：
当某个音**已经被调号升高过一次**（比如 F♯），而你又需要**再升高它**时，
就用重升号（𝄪）——**而不是写 G**。原因见下面第三种用途。

## 一条范围规则

> **变音记号只在本小节内、同一高度上有效。**

| 情形 | 规则 |
|---|---|
| 同一小节内**同音高的音**再次出现 | **不必重标**（auto 生效） |
| 跨到**下一小节** | **必须重标**（否则自动还原） |
| 同一小节内**不同八度**的同音名 | **需要另标**（严格记谱规范） |

**最后一行是容易被忽略的细节**：变音记号的作用是**"那个高度的音"**，不是"那个音名在任何八度"。
（不同出版社的从宽做法不一，但严格规范要求另标。）

## 三种用途

**① 为和声功能服务**（最常见）

| 用法 | 例 |
|---|---|
| 升高导音 | 小调里把第 7 级升高，以取得属功能（见 [[concept:harmonic-minor|和声小调]]） |
| 副属和弦的变化音 | 见 [[concept:leading-tone-chord|导七和弦]] |
| 半音经过 | 见 [[concept:chromatic|半音]] |

**② 改变调式**
旋律小调的上行升高第 6、7 级，就是靠临时记号实现的。

**③ 等音写法**（为什么需要重升重降）

同一个音高，可以有**不同的写法**，而写法**携带和声意义**（见 [[concept:enharmonic|等音的写法]]）：

| 音高 | 可能的写法 | 各自的意义 |
|---|---|---|
| 与 G 同高 | **G** · **F𝄪**（重升 F） · **A𝄫**（重降 A） | G：本位的第 5 级；F𝄪：升高的 F（在 G♯ 小调里它是导音）；A𝄫：降低的 A |

**所以"写法"不是排版问题，而是"这个音在和声上担任什么角色"** ——
写成 F𝄪 的音，读谱者立刻知道它要上行解决到 G♯；写成 G 就失去了这个信息。

## 图示：一条范围规则

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">五种记号、一条范围规则：本小节内同高度的音自动生效，跨小节必须重标</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      <text x="0" y="0">同一小节内（自动生效，同高度的音不必再标）</text>
    </g>
    <g transform="translate(0,12)">
      <rect x="0" y="0" width="230" height="44" rx="3" fill="none" stroke="#343439" stroke-width="1.2"/>
      <g font-family="Georgia,serif" font-size="12" fill="#E8C547" text-anchor="middle">
        <text x="34" y="28">F♯</text><text x="140" y="28">F♯</text>
      </g>
      <text x="86" y="28" font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64" text-anchor="middle">第二个不必标</text>
    </g>

    <g transform="translate(0,74)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
        <text x="0" y="0">跨到下一小节（必须重标）</text>
      </g>
      <g transform="translate(0,10)">
        <rect x="0" y="0" width="110" height="40" rx="3" fill="none" stroke="#343439" stroke-width="1.2"/>
        <rect x="120" y="0" width="110" height="40" rx="3" fill="none" stroke="#343439" stroke-width="1.2"/>
        <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
          <text x="55" y="26" fill="#E8C547">F♯</text><text x="175" y="26" fill="#C0504A">F♮</text>
        </g>
        <text x="175" y="56" font-family="system-ui,sans-serif" font-size="10" fill="#C0504A" text-anchor="middle">不重标就自动还原</text>
      </g>
    </g>

    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      三种用途：为和声功能服务（升导音）· 改变调式 · 等音写法
    </text>
    <text x="0" y="168" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      写法携带和声意义：写 F𝄪 的人是在说"它要上行解决到 G♯"，写 G 则失去这个信息
    </text>
  </g>
</svg>
```

## 听一听：本位与升高

用 `interval` 对比**大二度**与**小二度** —— 后者正是临时记号常造成的效果（升高半音）。
**变音记号在听觉上就是"半音的移动"**。

```audiolab
{"type":"interval","a":"C4","b":"D4","label":"大二度（无变音）","label_en":"A major second — no accidental","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D♭4（= C♯4）就是小二度 —— 升高或降低半音，正是变音记号做的事。","hint2_en":"Set b to D♭4 — a minor second. That half-step shift is what an accidental does."}
```

## 常见误解

- **「临时记号会一直有效」** → 只在**本小节内**有效；跨小节必须重标。
- **「重升号罕见，可以写成高一级的音」** → 写法携带**和声意义**。F𝄪 与 G 同高，但在 G♯ 小调里 F𝄪 是导音，写成 G 就丢了信息。
- **「变音记号就是"改变音高"」** → 它常为**和声功能**服务（升导音、半音经过），不只是"改个音"。
- **「同一小节内不同八度的同音名也自动生效」** → 严格规范要求**另标**：记号作用于"那个高度"。
:::

::: en
There are **five** accidentals, but only **one** scope rule and **three** uses.

## The five signs

| Sign | Name | Effect |
|---|---|---|
| **♯** | sharp | raises by a semitone |
| **♭** | flat | lowers by a semitone |
| **♮** | natural | cancels a previous sharp or flat |
| **𝄪** | double sharp | raises by two semitones (a whole tone) |
| **𝄫** | double flat | lowers by two semitones |

**The double sharp and double flat look odd but are necessary**: when a note has **already been raised by the key
signature** (F♯, say) and you need to **raise it again**, you write 𝄪 — **not G**. The reason is the third use
below.

## One scope rule

> **An accidental applies only within its bar, to that pitch.**

| Case | Rule |
|---|---|
| the **same pitch** later in the same bar | **no need to repeat** the sign |
| crossing into the **next bar** | **the sign must be repeated** (otherwise it reverts) |
| the **same note name in another octave**, same bar | **a separate sign is required** (strict practice) |

**That last row is easily missed**: an accidental governs **that specific pitch**, not "that note name in any
octave". (Publishers differ in leniency; strict practice requires the extra sign.)

## Three uses

**1. Serving harmonic function** (the commonest)

| Use | Example |
|---|---|
| raising the leading tone | in minor the seventh degree is raised to obtain dominant function (see [[concept:harmonic-minor|harmonic minor]]) |
| chromatic notes in secondary dominants | see [[concept:leading-tone-chord|leading-tone seventh]] |
| chromatic passing motion | see [[concept:chromatic|chromatic]] |

**2. Altering the mode.** The raised sixth and seventh of melodic minor are written with accidentals.

**3. Enharmonic spelling** (why double sharps and flats exist)

The same sounding pitch can be **written in different ways**, and the spelling **carries harmonic meaning** (see
[[concept:enharmonic|enharmonic spelling]]):

| Pitch | Possible spellings | What each means |
|---|---|---|
| sounding as G | **G** · **F𝄪** · **A𝄫** | G: the fifth degree; F𝄪: a raised F, the leading tone in G♯ minor; A𝄫: a lowered A |

**So spelling is not a typesetting matter but a question of what role the note plays in the harmony** — written as
F𝄪, the reader knows at once that it resolves upward to G♯; written as G, that information is gone.

## Diagram: one scope rule

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Five signs, one scope rule: within the bar the pitch carries over; across a bar line it must be rewritten</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      <text x="0" y="0">within one bar — it carries over, no second sign needed</text>
    </g>
    <g transform="translate(0,12)">
      <rect x="0" y="0" width="230" height="44" rx="3" fill="none" stroke="#343439" stroke-width="1.2"/>
      <g font-family="Georgia,serif" font-size="12" fill="#E8C547" text-anchor="middle">
        <text x="34" y="28">F♯</text><text x="140" y="28">F♯</text>
      </g>
      <text x="86" y="28" font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64" text-anchor="middle">no sign here</text>
    </g>

    <g transform="translate(0,74)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
        <text x="0" y="0">across the bar line — it must be written again</text>
      </g>
      <g transform="translate(0,10)">
        <rect x="0" y="0" width="110" height="40" rx="3" fill="none" stroke="#343439" stroke-width="1.2"/>
        <rect x="120" y="0" width="110" height="40" rx="3" fill="none" stroke="#343439" stroke-width="1.2"/>
        <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
          <text x="55" y="26" fill="#E8C547">F♯</text><text x="175" y="26" fill="#C0504A">F♮</text>
        </g>
        <text x="175" y="56" font-family="system-ui,sans-serif" font-size="10" fill="#C0504A" text-anchor="middle">without a sign it reverts</text>
      </g>
    </g>

    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Three uses: serving harmonic function, altering the mode, enharmonic spelling
    </text>
    <text x="0" y="168" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Spelling carries meaning: F double sharp says "resolves up to G sharp"; writing G loses that
    </text>
  </g>
</svg>
```

## Listen: natural and raised

Use `interval` to compare **a major second** with **a minor second** — the latter is exactly the effect an accidental
usually produces. **An accidental, heard, is a semitone shift.**

```audiolab
{"type":"interval","a":"C4","b":"D4","label":"大二度（无变音）","label_en":"A major second — no accidental","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D♭4（= C♯4）就是小二度 —— 半音的移动正是变音记号做的事。","hint2_en":"Set b to D♭4 — a minor second. That half-step shift is what an accidental does."}
```

## Common misconceptions

- **"An accidental lasts."** Only **within its bar**; across a bar line it must be rewritten.
- **"Double sharps are rare, so write the next note up."** Spelling carries **harmonic meaning**. F𝄪 and G sound
  alike, but in G♯ minor F𝄪 is the leading tone — writing G throws that away.
- **"An accidental just changes a pitch."** It often serves **harmonic function** (raising a leading tone,
  chromatic passing), not merely "changing a note".
- **"The same note name in another octave carries over automatically."** Strict practice requires **a separate
  sign**: the accidental governs that pitch.
:::
