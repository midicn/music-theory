---
id: fugue-form
site: theo
cat: T9
title: 赋格曲式
title_en: Fugue Form
summary: 赋格的结构：呈示段 → 中间段 → 结束段——它有自己的段落逻辑
summary_en: The structure of a fugue: exposition, middle section, final section — it has its own sectional logic
level: standard
tags: [乐理, 曲式, 复调]
tags_en: [theory, form, polyphony]
alias: [赋格曲式, 赋格结构, fugue form]
order: 38
links:
  - "[[concept:fugue]]"
  - "[[concept:form]]"
  - "[[concept:imitation]]"
  - "[[concept:sonata-form]]"
  - "[[concept:pedal-point]]"
instances:
  - atepp-001928 | 巴赫《半音阶幻想曲与赋格》：赋格段的声部进入与后续发展层次清楚，可逐段辨认 | Bach's Chromatic Fantasia and Fugue — the entries and their later development are clearly layered and can be followed section by section
  - atepp-000238 | 肖斯塔科维奇《前奏曲与赋格》Op.87：20 世纪的赋格，可对照传统段落逻辑的延续 | Shostakovich's Preludes and Fugues Op.87 — twentieth-century fugues, showing how the traditional sectional logic persists
  - atepp-001254 | 肖邦的赋格：浪漫派的赋格写法，可听主题处理方式与巴洛克的差别 | A fugue by Chopin — a Romantic fugue, useful for comparing how the subject is handled
sources:
  - 赋格的段落逻辑（呈示段 / 中间段 / 结束段）与各段常见手法，属曲式分析通则
  - 与奏鸣曲式的对照（赋格不依赖调性对比而依赖素材层叠），为通行表述
updated: 2026-09-25
---

::: zh
这一条与 [[concept:fugue|赋格（写法）]] 分工明确：

> **T6 的「赋格」讲的是写法**（主题如何进入、如何交织）；
> **本条讲的是结构** —— 把这种写法组织成整曲时，段落是怎么安排的。

## 三段的段落逻辑

| 段 | 内容 | 常见手法 |
|---|---|---|
| **呈示段** | 各声部**依次进入**，把主题交代完 | 主题 → 答题（属调）→ 主题 → 答题 |
| **中间段** | 主题继续出现，但**调性不断游移** | 间插段（用主题片段模进，见 [[concept:sequence|模进]]）+ 各调上的进入 |
| **结束段** | 主题**回到主调**，收束 | 密接和应（进入互相交叠）+ **持续音**（见 [[concept:pedal-point|持续低音]]）+ 尾声 |

**三段的划分依据与奏鸣曲式不同**：奏鸣曲式靠**调性对比**（第二主题在属调）；
赋格靠**主题进入的密集程度与调性距离** ——
**没有"第二主题"，只有同一个主题在不同调上反复出现。**

## 与奏鸣曲式的对照

两者都属于"呈示—展开—回归"的大家族，但机制有别：

| | 奏鸣曲式 | 赋格曲式 |
|---|---|---|
| 对比靠什么 | **两个主题 + 两个调** | **同一主题 + 密集度与调性距离** |
| "展开"的手段 | 把素材**拆开**（片段化） | 把主题**移位**（各调进入）+ 间插段 |
| 回归的标志 | 第二主题回主调（**调性统一**） | 主题回主调 + **密接和应** |
| 收束手段 | 终止式 | **持续音** + 终止式 |

一句话：**奏鸣曲式用"两个东西"制造张力，赋格用"同一个东西的不同处境"制造张力。**

## 图示：三段的划分依据

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">分界不靠终止式，而靠"主题进入的密集程度"与调性距离</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">呈示段</text>
      <text x="-20" y="54" text-anchor="end">中间段</text>
      <text x="-20" y="108" text-anchor="end">结束段</text>
    </g>

    <g>
      <g fill="#5B7FA8">
        <rect x="0" y="-10" width="60" height="20" rx="2"/>
        <rect x="90" y="-10" width="60" height="20" rx="2"/>
        <rect x="180" y="-10" width="60" height="20" rx="2"/>
        <rect x="270" y="-10" width="60" height="20" rx="2"/>
      </g>
      <text x="336" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">四个声部依次进入（主题→答题→主题→答题）</text>
    </g>

    <g transform="translate(0,54)">
      <g fill="#E8C547">
        <rect x="0" y="-10" width="34" height="20" rx="2"/>
        <rect x="60" y="-10" width="34" height="20" rx="2"/>
        <rect x="120" y="-10" width="34" height="20" rx="2"/>
        <rect x="180" y="-10" width="34" height="20" rx="2"/>
      </g>
      <g fill="#343439" opacity=".7">
        <rect x="38" y="-10" width="18" height="20" rx="2"/>
        <rect x="98" y="-10" width="18" height="20" rx="2"/>
        <rect x="158" y="-10" width="18" height="20" rx="2"/>
      </g>
      <text x="230" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">进入 + 间插段交替，调性不断游移</text>
    </g>

    <g transform="translate(0,108)">
      <g fill="#E07A3F">
        <rect x="0" y="-10" width="26" height="20" rx="2"/>
        <rect x="24" y="-10" width="26" height="20" rx="2"/>
        <rect x="56" y="-10" width="26" height="20" rx="2"/>
      </g>
      <text x="96" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">密接和应（进入互相交叠）+ 持续音收束</text>
    </g>

    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      对照：奏鸣曲式靠两个主题两个调；赋格靠同一主题的密集度与调性距离 —— 家族相似，机制不同
    </text>
  </g>
</svg>
```

## 听一听：回归与收束

用 `progression` 听一段"离开主调 → 回到主调"的进行。赋格结束段的收束感与此同源 ——
**主题在经历了各调游移之后回到主调**，那份"回家"的感觉就是结构完成的标志。

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I"],"label":"离开与回归（赋格结束段的收束感）","label_en":"Departure and return: the closing feel of a fugue's final section","hint":"逐个和弦依次听","hint_en":"Hear each chord in turn"}
```

## 常见误解

- **「赋格是固定曲式，段落数量固定」** → 段落逻辑存在，但**段落数量与长度高度自由**。二声部小赋格可能只有呈示段加一个间插段。
- **「赋格没有段落划分」** → 恰恰相反：它有清楚的三段逻辑，只是**分界不靠终止式，而靠主题进入的密集程度**。
- **「赋格必须四个声部」** → 二到五声部都有（见 [[concept:fugue|赋格]]）。
- **「赋格曲式就是奏鸣曲式的复调版」** → 家族相似但机制不同：一个靠调性对比，一个靠素材层叠。
:::

::: en
This entry divides the labour with [[concept:fugue|fugue as a technique]] clearly:

> **T6's "fugue" covers the writing** (how the subject enters and interweaves);
> **this entry covers the structure** — how that writing is arranged into sections across a whole piece.

## The three-section logic

| Section | Content | Common devices |
|---|---|---|
| **exposition** | voices **enter in turn**, stating the subject | subject → answer (dominant) → subject → answer |
| **middle** | the subject keeps appearing while **the tonality keeps moving** | episodes (subject fragments pushed by sequence, see [[concept:sequence|sequence]]) plus entries in various keys |
| **final** | the subject **returns to the tonic** and closes | stretto (overlapping entries) + **pedal point** (see [[concept:pedal-point|pedal point]]) + coda |

**The sections are divided on different grounds from sonata form**: sonata form relies on **tonal contrast** (the
second subject in the dominant); a fugue relies on **the density of entries and tonal distance** — **there is no
"second subject", only one subject recurring in different keys.**

## The comparison with sonata form

Both belong to the "exposition-development-return" family, but with different mechanisms:

| | Sonata form | Fugue form |
|---|---|---|
| What supplies contrast | **two subjects and two keys** | **one subject and varying density/tonal distance** |
| Means of "development" | taking the material **apart** (fragmentation) | **transposing** the subject (entries in many keys) plus episodes |
| Sign of return | the second subject returns to the tonic (**tonal unity**) | the subject returns to the tonic, often in **stretto** |
| Means of closing | cadence | **pedal point** plus cadence |

In one line: **sonata form builds tension from two things; a fugue builds it from one thing in changing
circumstances.**

## Diagram: what divides the sections

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Divisions rest on the density of entries and tonal distance, not on cadences</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">exposition</text>
      <text x="-20" y="54" text-anchor="end">middle</text>
      <text x="-20" y="108" text-anchor="end">final</text>
    </g>

    <g>
      <g fill="#5B7FA8">
        <rect x="0" y="-10" width="60" height="20" rx="2"/>
        <rect x="90" y="-10" width="60" height="20" rx="2"/>
        <rect x="180" y="-10" width="60" height="20" rx="2"/>
        <rect x="270" y="-10" width="60" height="20" rx="2"/>
      </g>
      <text x="336" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">four voices entering in turn</text>
    </g>

    <g transform="translate(0,54)">
      <g fill="#E8C547">
        <rect x="0" y="-10" width="34" height="20" rx="2"/>
        <rect x="60" y="-10" width="34" height="20" rx="2"/>
        <rect x="120" y="-10" width="34" height="20" rx="2"/>
        <rect x="180" y="-10" width="34" height="20" rx="2"/>
      </g>
      <g fill="#343439" opacity=".7">
        <rect x="38" y="-10" width="18" height="20" rx="2"/>
        <rect x="98" y="-10" width="18" height="20" rx="2"/>
        <rect x="158" y="-10" width="18" height="20" rx="2"/>
      </g>
      <text x="230" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">entries alternating with episodes, keys drifting</text>
    </g>

    <g transform="translate(0,108)">
      <g fill="#E07A3F">
        <rect x="0" y="-10" width="26" height="20" rx="2"/>
        <rect x="24" y="-10" width="26" height="20" rx="2"/>
        <rect x="56" y="-10" width="26" height="20" rx="2"/>
      </g>
      <text x="96" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">stretto entries overlapping, closed by a pedal point</text>
    </g>

    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Sonata form uses two subjects and two keys; a fugue uses one subject in changing circumstances
    </text>
  </g>
</svg>
```

## Listen: return and close

Use `progression` on a departure-and-return span. A fugue's closing feels the same way — **the subject coming home
after drifting through many keys** is what marks the structure complete.

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I"],"label":"离开与回归（赋格结束段的收束感）","label_en":"Departure and return: the closing feel of a fugue's final section","hint":"逐个和弦依次听","hint_en":"Hear each chord in turn"}
```

## Common misconceptions

- **"A fugue is a fixed form with a set number of sections."** The sectional logic exists, but **the number and
  length of sections are highly free**. A short two-voice fugue may be an exposition plus a single episode.
- **"A fugue has no sections."** The opposite: it has a clear three-part logic — its divisions rest on **the density
  of entries** rather than on cadences.
- **"A fugue must have four voices."** Two to five all occur (see [[concept:fugue|fugue]]).
- **"Fugue form is sonata form in polyphony."** Same family, different mechanism: one relies on tonal contrast, the
  other on the layering of one subject.
:::
