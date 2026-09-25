---
id: harmonic-function
site: theo
cat: T5
title: 级数与和声功能
title_en: Degrees and Harmonic Function
summary: 七个级数归成三组功能：主、属、下属——调性音乐最省力的组织方式
summary_en: Seven degrees collapse into three functions — tonic, dominant, subdominant — the most economical way to organise tonal music
level: core
tags: [乐理, 和声, 调性]
tags_en: [theory, harmony, tonality]
alias: [和声功能, 功能标记, 级数, harmonic function, TSD]
order: 12
links:
  - "[[concept:tonal-center]]"
  - "[[concept:cadence]]"
  - "[[concept:scale-harmony]]"
  - "[[concept:triad]]"
  - "[[concept:secondary-dominant]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：整首以主—下属—属—主的框架铺开，功能关系最清楚 | An organ hymn — laid out over a tonic-subdominant-dominant-tonic frame, the clearest view of function
  - atepp-000318 | a 小调奏鸣曲：小调里功能关系同样成立，只是属和弦需要升第 7 级 | A sonata in A minor — function works the same way in minor, provided the seventh is raised
  - mutopia-000049 | 《绿袖子》加固定低音：低音线条以功能关系推进，是功能逻辑的又一实例 | Greensleeves to a Ground — the bass advances by functional relation, another instance of the same logic
sources:
  - 和声功能把级数归纳为主（T）· 下属（S）· 属（D）三组，属和声学通则
  - 功能进行的常见序列（T–S–D–T 与 T–D–T 等）与替代关系为通行表述
updated: 2026-09-24
---

::: zh
调性音乐有七个级数，但**记七个不如记三个**。因为它们的"作用"其实只有三种：

| 功能 | 标记 | 包含的级数（大调） | 作用 |
|---|---|---|---|
| **主功能** | T | I、VI、III | 稳定、**落脚点** |
| **下属功能** | S | IV、II | 离开主，推向属 |
| **属功能** | D | V、VII | 最强张力，**要求回到主** |

这就是**功能圈**：**T → S → D → T**。绝大多数古典作品的骨架都能落在这条链上。

## 为什么能这样归并

因为**有些级数共享关键音**：

| 级数 | 与谁共享 | 效果 |
|---|---|---|
| VI 与 I | 共享三音与五音 | VI 可以替代 I |
| II 与 IV | 共享根音与三音 | II 可以替代 IV |
| VII 与 V | 共享三音与五音（V7 里） | VII 承担属功能 |

所以"七个级数"实际是**三组功能的多种表达**。这也是为什么分析时常常只标 T/S/D ——
标记的是**作用**，不是**编号**。

## 功能进行的常规与非常规

| 进行 | 性质 | 说明 |
|---|---|---|
| T → S → D → T | 常规 | 调性音乐的"标准路线" |
| T → D → T | 很常见 | 省略下属，收束更直接 |
| D → S | **反功能** | 属回到下属，听感"倒着走"，要谨慎使用 |
| S → T（变格） | 常见 | 柔和收束，见 [[concept:cadence|终止式]] |

"反功能"是这套体系里少见的**明确禁忌** —— 因为属已经是最紧张状态，
再回到下属等于把张力往后撤，听觉上会显得松散。

## 与小调的关系

小调里功能关系**完全成立**，只是属功能必须靠升第 7 级才能拿到大三和弦
（见 [[concept:harmonic-minor|和声小调]]）。所以小调作品里的变化音不是"意外"，
而是**功能需要的必需品**。

## 图示：功能圈

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">三个功能，一条主路线；反向走会"倒着走"</text>
  </g>

  <g transform="translate(60,58)">
    <g>
      <circle cx="70" cy="40" r="34" fill="none" stroke="#5B7FA8" stroke-width="1.6"/>
      <text x="70" y="36" font-family="system-ui,sans-serif" font-size="13" fill="#5B7FA8" text-anchor="middle">T 主</text>
      <text x="70" y="54" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">I · VI · III</text>
    </g>
    <g>
      <circle cx="240" cy="40" r="34" fill="none" stroke="#E8C547" stroke-width="1.6"/>
      <text x="240" y="36" font-family="system-ui,sans-serif" font-size="13" fill="#E8C547" text-anchor="middle">S 下属</text>
      <text x="240" y="54" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">IV · II</text>
    </g>
    <g>
      <circle cx="410" cy="40" r="34" fill="none" stroke="#E07A3F" stroke-width="1.6"/>
      <text x="410" y="36" font-family="system-ui,sans-serif" font-size="13" fill="#E07A3F" text-anchor="middle">D 属</text>
      <text x="410" y="54" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">V · VII</text>
    </g>

    <g stroke="#5B7FA8" stroke-width="1.4" fill="none">
      <line x1="104" y1="40" x2="206" y2="40"/><polygon points="206,34 218,40 206,46" fill="#5B7FA8" stroke="none"/>
    </g>
    <g stroke="#E8C547" stroke-width="1.4" fill="none">
      <line x1="274" y1="40" x2="376" y2="40"/><polygon points="376,34 388,40 376,46" fill="#E8C547" stroke="none"/>
    </g>
    <g stroke="#E07A3F" stroke-width="1.4" fill="none">
      <path d="M410,74 C410,116 70,116 70,74"/>
      <polygon points="64,74 70,62 76,74" fill="#E07A3F" stroke="none"/>
    </g>
    <text x="240" y="104" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F" text-anchor="middle">D → T：收束</text>

    <g stroke="#C0504A" stroke-width="1.3" stroke-dasharray="4 3" fill="none">
      <line x1="376" y1="16" x2="274" y2="16"/><polygon points="274,10 262,16 274,22" fill="#C0504A" stroke="none"/>
    </g>
    <text x="325" y="8" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A" text-anchor="middle">D → S：反功能（避免）</text>
  </g>
</svg>
```

## 听一听：功能进行

用进行播放器听 **T → S → D → T**（标准路线）与 **T → D → T**（省略下属）。
两者都收得住，区别在"绕了多远"。

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"T → S → D → T（标准路线）","label_en":"T-S-D-T, the standard route","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I"],"label":"T → D → T（省略下属）","label_en":"T-D-T, skipping the subdominant","hint":"与上一条对比：收束更直接","hint_en":"Compare with the item above — a more direct close"}
```

## 常见误解

- **「功能标记只是级数的别名」** → 它标的是**作用**。VI 在有些场合当主功能用，那时标 T 比标 VI 更有意义。
- **「反功能是硬性禁止」** → 是"强倾向避免"。浪漫派之后有大量故意使用，效果是刻意松弛。
- **「小调的功能关系不同」** → 完全一样，只是属功能要靠升第 7 级取得。
- **「功能只用于古典音乐」** → 流行音乐的常见进行（如 I–V–vi–IV）同样可以用功能解释。
:::

::: en
Tonal music has seven degrees, but **remembering three beats remembering seven**, because they do only three
jobs:

| Function | Symbol | Degrees (major) | Role |
|---|---|---|---|
| **tonic** | T | I, VI, III | stable, the **place to land** |
| **subdominant** | S | IV, II | leaves the tonic, pushes toward the dominant |
| **dominant** | D | V, VII | maximum tension, **demands a return** |

That is the **functional circle**: **T → S → D → T**. The skeleton of most classical works fits on that chain.

## Why the reduction works

Because **some degrees share critical notes**:

| Degree | Shares with | Effect |
|---|---|---|
| VI and I | the third and fifth | VI can substitute for I |
| II and IV | the root and third | II can substitute for IV |
| VII and V | the third and fifth (within V7) | VII carries dominant function |

So the "seven degrees" are really **several expressions of three functions**. It is why analysis often writes
only T / S / D — it labels the **job**, not the number.

## Normal and abnormal successions

| Succession | Status | Note |
|---|---|---|
| T → S → D → T | standard | the "main road" of tonal music |
| T → D → T | very common | the subdominant skipped; a more direct close |
| D → S | **retrogression** | the dominant moves back to the subdominant; sounds like walking backwards |
| S → T (plagal) | common | a gentler close — see [[concept:cadence|cadence]] |

Retrogression is one of the few outright taboos in the system: the dominant is the point of maximum tension, so
returning to the subdominant withdraws that tension and leaves the music sounding slack.

## Relation to minor

Functional relations hold **exactly the same way** in minor; the dominant simply requires a raised seventh to
produce a major triad (see [[concept:harmonic-minor|harmonic minor]]). So accidentals in minor-key music are not
surprises — **they are what the function demands.**

## Diagram: the functional circle

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Three functions, one main route; going backwards is a retrogression</text>
  </g>

  <g transform="translate(60,58)">
    <g>
      <circle cx="70" cy="40" r="34" fill="none" stroke="#5B7FA8" stroke-width="1.6"/>
      <text x="70" y="36" font-family="system-ui,sans-serif" font-size="13" fill="#5B7FA8" text-anchor="middle">T tonic</text>
      <text x="70" y="54" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">I, VI, III</text>
    </g>
    <g>
      <circle cx="240" cy="40" r="34" fill="none" stroke="#E8C547" stroke-width="1.6"/>
      <text x="240" y="36" font-family="system-ui,sans-serif" font-size="13" fill="#E8C547" text-anchor="middle">S subdom.</text>
      <text x="240" y="54" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">IV, II</text>
    </g>
    <g>
      <circle cx="410" cy="40" r="34" fill="none" stroke="#E07A3F" stroke-width="1.6"/>
      <text x="410" y="36" font-family="system-ui,sans-serif" font-size="13" fill="#E07A3F" text-anchor="middle">D domin.</text>
      <text x="410" y="54" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">V, VII</text>
    </g>

    <g stroke="#5B7FA8" stroke-width="1.4" fill="none">
      <line x1="104" y1="40" x2="206" y2="40"/><polygon points="206,34 218,40 206,46" fill="#5B7FA8" stroke="none"/>
    </g>
    <g stroke="#E8C547" stroke-width="1.4" fill="none">
      <line x1="274" y1="40" x2="376" y2="40"/><polygon points="376,34 388,40 376,46" fill="#E8C547" stroke="none"/>
    </g>
    <g stroke="#E07A3F" stroke-width="1.4" fill="none">
      <path d="M410,74 C410,116 70,116 70,74"/>
      <polygon points="64,74 70,62 76,74" fill="#E07A3F" stroke="none"/>
    </g>
    <text x="240" y="104" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F" text-anchor="middle">D to T: the close</text>

    <g stroke="#C0504A" stroke-width="1.3" stroke-dasharray="4 3" fill="none">
      <line x1="376" y1="16" x2="274" y2="16"/><polygon points="274,10 262,16 274,22" fill="#C0504A" stroke="none"/>
    </g>
    <text x="325" y="8" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A" text-anchor="middle">D to S: retrogression, avoid</text>
  </g>
</svg>
```

## Listen: functional progressions

Use the progression player for **T → S → D → T** (the standard route) and **T → D → T** (subdominant skipped).
Both close successfully; they differ in how far they travel.

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"T → S → D → T（标准路线）","label_en":"T-S-D-T, the standard route","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I"],"label":"T → D → T（省略下属）","label_en":"T-D-T, skipping the subdominant","hint":"与上一条对比：收束更直接","hint_en":"Compare with the item above — a more direct close"}
```

## Common misconceptions

- **"Function labels are just aliases for degree numbers."** They label the **job**. When a VI acts as a tonic, writing T says more than writing VI.
- **"Retrogression is forbidden."** Strongly avoided, not forbidden. From the Romantics onward it is used deliberately, for slackening.
- **"Minor keys work differently."** Exactly the same, except the dominant requires a raised seventh.
- **"Function applies only to classical music."** The common pop loop (I–V–vi–IV) is just as analysable in functional terms.
:::
