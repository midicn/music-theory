---
id: theme-variations
site: theo
cat: T9
title: 变奏曲式
title_en: Variation Form
summary: A A₁ A₂ A₃……同一主题反复换装——轮廓始终可辨
summary_en: A A₁ A₂ A₃ — one theme repeatedly re-dressed, its outline always recognisable
level: standard
tags: [乐理, 曲式, 结构]
tags_en: [theory, form, structure]
alias: [变奏曲式, 变奏曲, variation form, theme and variations]
order: 32
links:
  - "[[concept:form]]"
  - "[[concept:thematic-development]]"
  - "[[concept:pedal-point]]"
  - "[[concept:ornaments]]"
  - "[[concept:rhythmic-pattern]]"
instances:
  - atepp-002452 | 巴赫《哥德堡变奏曲》第 12 变奏：低音主题提供不变的骨架，各变奏在其上换装 | Bach's Goldberg Variation 12 — the bass theme supplies a constant frame on which each variation is dressed anew
  - mutopia-000049 | 《绿袖子》加固定低音：低音循环不变、上方不断新写，是"固定低音变奏"的教科书形态 | Greensleeves to a Ground — the bass loops unchanged while everything above is newly written
  - atepp-000356 | 格里格《抒情小品》：其中含变奏写法的段落，可听"骨架不变、表面全换"的效果 | Grieg's Lyric Pieces include variation passages showing an unchanged frame under a wholly changed surface
sources:
  - 变奏曲式的定义（主题轮廓不变、表面不断更换）与常见变奏手段，属曲式分析通则
  - 固定低音变奏（basso ostinato）与性格变奏的区别，为通行表述
updated: 2026-09-25
---

::: zh
变奏曲式是结构最简单、也最容易被误解的曲式：

> **A A₁ A₂ A₃ …** —— 同一主题反复出现，每次换一层皮。

## 与"主题发展"的根本区别

这两者最容易混（[[concept:thematic-development|主题的发展]] 那条已从另一面讲过）：

| | **变奏** | **发展** |
|---|---|---|
| 主题的**轮廓** | **始终可辨** | 常被**破坏** |
| 主题的**完整性** | 保留 | 拆散 |
| 换的是 | **表面**（节奏 / 织体 / 和声 / 装饰） | **内部结构** |
| 一句话 | 换**衣服** | 换**基因** |

**判断标准**：听者能不能始终认出"这是同一个主题"。
能 → 变奏；中途认不出了 → 已经发展成别的东西（或者干脆换了主题）。

## 常见的变奏手段

| 手段 | 做法 | 例 |
|---|---|---|
| **装饰变奏** | 旋律加花，和声骨架不变 | 古典时期最常见 |
| **节奏改造** | 主题音高不动，换节奏型 | 同一轮廓变成进行曲或舞曲 |
| **和声重配** | 旋律基本不动，换和声 | 同一句变明亮或阴暗 |
| **调式 / 调性变换** | 大调变小调（或反之），或换到别的调 | 性格立刻反转 |
| **织体变化** | 从单声部到厚密和弦，或反之 | 密度手段 |
| **性格变奏** | 只保留主题的**某个特征**（一个音程、一个节奏） | 浪漫派：变到几乎认不出 |

**最后一行是极端情况**：当变奏只保留"一个特征"时，它其实已经接近 [[concept:thematic-development|发展]]。
**这也说明变奏与发展不是两件事，而是同一条连续谱的两端。**

## 三种历史形态

| 时期 | 形态 | 说明 |
|---|---|---|
| **巴洛克** | **固定低音变奏** | 低音循环不变，上方每次新写（见 [[concept:pedal-point|持续低音]]） |
| **古典** | **装饰变奏** | 主题轮廓清晰，逐段加花，末段常转调或加速 |
| **浪漫** | **性格变奏** | 变奏之间性格差异极大，常变到认不出 |

第一种最"严格"（骨架完全不变），第三种最"自由"（只留基因）——
**这条演化线本身就是"作曲自由度"随时代扩大的证据。**

## 写变奏的难点

不是"想不出新花样"，而是：**在换掉表面的同时，保住主题的可辨性。**

| 常见失败 | 原因 |
|---|---|
| 变奏之间无差别 | 每次换的东西太少，听者听不出"换了" |
| 变了两个就不像了 | 换得太多，主题的可辨性被冲掉 |
| 整曲平铺 | 变奏之间**没有整体规划**（如逐步加快 / 逐步加厚） |

**第三条最要紧**：一组好的变奏通常有一条**整体的弧线** ——
常见的是"越往后越复杂、越快、越厚"，最后一段回到最简（或相反）。
**没有弧线的变奏组，听起来就是一堆并列的段落。**

## 图示：不变的骨架与不断更换的表面

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">骨架（下方）始终可见；上方每次换装 —— 这就是变奏的全部秘密</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="6" text-anchor="end">表面</text>
      <text x="-20" y="62" text-anchor="end">骨架</text>
    </g>

    <g fill="#E07A3F"><rect x="0" y="-8" width="80" height="18" rx="2"/></g>
    <text x="40" y="5" font-family="system-ui,sans-serif" font-size="10" fill="#1A0E06" text-anchor="middle">A</text>
    <g fill="#E8C547"><rect x="94" y="-8" width="80" height="18" rx="2"/></g>
    <text x="134" y="5" font-family="system-ui,sans-serif" font-size="10" fill="#1A0E06" text-anchor="middle">A₁ 加花</text>
    <g fill="#5B7FA8"><rect x="188" y="-8" width="80" height="18" rx="2"/></g>
    <text x="228" y="5" font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">A₂ 换节奏</text>
    <g fill="#C0504A"><rect x="282" y="-8" width="80" height="18" rx="2"/></g>
    <text x="322" y="5" font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">A₃ 换调式</text>

    <g transform="translate(0,50)">
      <g fill="#343439">
        <rect x="0" y="-8" width="80" height="18" rx="2"/>
        <rect x="94" y="-8" width="80" height="18" rx="2"/>
        <rect x="188" y="-8" width="80" height="18" rx="2"/>
        <rect x="282" y="-8" width="80" height="18" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64" text-anchor="middle">
        <text x="40" y="5">同一骨架</text><text x="134" y="5">同一骨架</text>
        <text x="228" y="5">同一骨架</text><text x="322" y="5">同一骨架</text>
      </g>
    </g>

    <text x="0" y="88" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      写变奏的难点不是想新花样，而是：换掉表面的同时保住主题的可辨性
    </text>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      一组好变奏要有整体弧线（越往后越复杂 / 越厚 / 越快）—— 没有弧线就只是一堆并列段落
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      变奏与发展是连续谱的两端：从"只换衣服"到"只留基因"
    </text>
  </g>
</svg>
```

## 听一听：骨架与它的变化

用 `chord` 组件听同一个和弦的三种形态（原位 / 第一转位 / 宽排列）——
**构成音不变、排列在变**。这就是变奏原理在最小尺度上的样子：
**骨架是同一组音，换的是呈现方式。**

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"同一和弦的三种呈现（变奏原理）","label_en":"One chord in three presentations — the principle of variation","hint":"整体 / 分解 / 宽排列 —— 构成音始终是 C–E–G","hint_en":"Block, arpeggio, open — the notes remain C-E-G throughout"}
```

## 常见误解

- **「变奏就是重复加花样」** → 关键是**主题的可辨性**。加花样只是手段之一；换调式、换织体、换性格同样常用。
- **「一组变奏越长越好」** → 长度不是目标。**一组变奏需要整体弧线**，否则听起来只是一堆并列段落。
- **「变奏与发展是两回事」** → 是**同一条连续谱的两端**：保留轮廓 → 保留基因。
- **「固定低音变奏只是老写法」** → 爵士的"riff 变奏"、流行歌的"loop 上叠加"都是同一个原理。
:::

::: en
Variation form has the simplest structure and is the most easily misunderstood:

> **A A₁ A₂ A₃ …** — the same theme returns again and again, each time in new clothing.

## The fundamental difference from thematic development

These two are most easily confused ([[concept:thematic-development|thematic development]] covered it from the
other side):

| | **Variation** | **Development** |
|---|---|---|
| The theme's **contour** | **always recognisable** | often **broken** |
| The theme's **completeness** | preserved | taken apart |
| What changes | the **surface** (rhythm, texture, harmony, ornament) | the **inner structure** |
| In one word | new **clothes** | new **genes** |

**The test**: can the listener always recognise "this is the same theme"? Yes means variation; if it becomes
unrecognisable midway, it has developed into something else — or the theme has simply been replaced.

## Common means of variation

| Means | Method | Example |
|---|---|---|
| **ornamental** | melody embroidered, harmonic frame intact | commonest in the Classical period |
| **rhythmic** | pitches kept, the rhythmic pattern replaced | one contour turns into a march or a dance |
| **reharmonisation** | melody nearly intact, harmony replaced | one phrase turns bright or dark |
| **modal / key change** | major to minor (or the reverse), or into another key | the character reverses at once |
| **textural** | from a single line to thick chords, or the reverse | a density device |
| **character variation** | only **one feature** of the theme retained (an interval, a rhythm) | Romantic: varied nearly beyond recognition |

**The last row is the extreme case**: when only one feature survives, the variation is close to
[[concept:thematic-development|development]]. **Which shows the two are not different things but the ends of one
continuum.**

## Three historical shapes

| Period | Shape | Explanation |
|---|---|---|
| **Baroque** | **ground-bass variation** | the bass loops unchanged while everything above is newly written (see [[concept:pedal-point|pedal point]]) |
| **Classical** | **ornamental variation** | the theme's contour stays clear, each section adds more ornament; the last often changes key or speeds up |
| **Romantic** | **character variation** | the variations differ wildly in character, often beyond recognition |

The first is the strictest (the frame never moves), the third the freest (only the genes survive) — **and that
evolution is itself evidence of composing freedom widening over time.**

## The difficulty of writing variations

It is not "thinking up new tricks" but this: **changing the surface while keeping the theme recognisable.**

| Common failure | Cause |
|---|---|
| the variations sound alike | too little changed, so the listener hears no variation |
| two variations in and it is gone | too much changed, the theme's identity washed out |
| the set lies flat | **no overall plan** between variations (say, gradually faster or thicker) |

**The third matters most**: a good set usually has an **arc** — commonly growing more complex, faster and thicker,
with the last variation returning to the simplest, or the reverse. **Without an arc, a set of variations is a pile
of parallel sections.**

## Diagram: a constant frame under a changing surface

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The frame below stays visible; the surface is re-dressed each time — that is all a variation is</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="6" text-anchor="end">surface</text>
      <text x="-20" y="62" text-anchor="end">frame</text>
    </g>

    <g fill="#E07A3F"><rect x="0" y="-8" width="80" height="18" rx="2"/></g>
    <text x="40" y="5" font-family="system-ui,sans-serif" font-size="10" fill="#1A0E06" text-anchor="middle">A</text>
    <g fill="#E8C547"><rect x="94" y="-8" width="80" height="18" rx="2"/></g>
    <text x="134" y="5" font-family="system-ui,sans-serif" font-size="10" fill="#1A0E06" text-anchor="middle">A1 ornamented</text>
    <g fill="#5B7FA8"><rect x="188" y="-8" width="80" height="18" rx="2"/></g>
    <text x="228" y="5" font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">A2 new rhythm</text>
    <g fill="#C0504A"><rect x="282" y="-8" width="80" height="18" rx="2"/></g>
    <text x="322" y="5" font-family="system-ui,sans-serif" font-size="10" fill="#F2EEE6" text-anchor="middle">A3 new mode</text>

    <g transform="translate(0,50)">
      <g fill="#343439">
        <rect x="0" y="-8" width="80" height="18" rx="2"/>
        <rect x="94" y="-8" width="80" height="18" rx="2"/>
        <rect x="188" y="-8" width="80" height="18" rx="2"/>
        <rect x="282" y="-8" width="80" height="18" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64" text-anchor="middle">
        <text x="40" y="5">same frame</text><text x="134" y="5">same frame</text>
        <text x="228" y="5">same frame</text><text x="322" y="5">same frame</text>
      </g>
    </g>

    <text x="0" y="88" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      The difficulty is not new tricks but keeping the theme recognisable while the surface changes
    </text>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      A good set needs an arc — without one it is a pile of parallel sections
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Variation and development are two ends of one continuum: from new clothes to new genes
    </text>
  </g>
</svg>
```

## Listen: a frame and its presentations

Use `chord` to hear one chord in three forms (root position, first inversion, open voicing) — **the notes are
unchanged, the presentation is not.** That is variation at its smallest scale: **the same frame, differently
presented.**

```audiolab
{"type":"chord","root":"C4","quality":"maj","inversion":0,"label":"同一和弦的三种呈现（变奏原理）","label_en":"One chord in three presentations — the principle of variation","hint":"整体 / 分解 / 宽排列 —— 构成音始终是 C–E–G","hint_en":"Block, arpeggio, open — the notes remain C-E-G throughout"}
```

## Common misconceptions

- **"A variation is repetition with decoration."** What matters is the **theme's recognisability**. Ornament is one
  means; mode, texture and character changes are equally common.
- **"Longer sets are better."** Length is not the goal. **A set needs an arc**, or it is a pile of parallel
  sections.
- **"Variation and development are separate things."** They are **the two ends of one continuum**: contour retained
  versus genes retained.
- **"Ground-bass variations are an old device."** A jazz riff variation or a pop song layering onto a loop is the
  same principle.
:::
