---
id: free-form
site: theo
cat: T9
title: 自由曲式
title_en: Free Form
summary: 不套用既有模式——但"自由"不等于"没有曲式"
summary_en: No pre-existing pattern — but free does not mean formless
level: standard
tags: [乐理, 曲式, 结构]
tags_en: [theory, form, structure]
alias: [自由曲式, 幻想曲, 狂想曲, 交响诗, free form]
order: 50
links:
  - "[[concept:form]]"
  - "[[concept:phrase]]"
  - "[[concept:climax]]"
  - "[[concept:sonata-form]]"
  - "[[concept:rhythmic-pattern]]"
instances:
  - atepp-001928 | 巴赫《半音阶幻想曲与赋格》：幻想曲部分不套用任何固定曲式，结构由情绪与和声推动 | Bach's Chromatic Fantasia and Fugue — the fantasia follows no fixed form; its shape is driven by mood and harmony
  - atepp-000498 | 匈牙利狂想曲：段落由情绪、速度与素材决定，接近自由曲式的组织方式 | A Hungarian Rhapsody — its sections are determined by mood, tempo and material, close to free-form organisation
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：全曲按"形象叙事"推进而非按既定曲式展开 | Liszt's transcription of Danse macabre advances by pictorial narrative rather than a set form
sources:
  - 自由曲式指不套用既有曲式模式的作品；幻想曲 / 狂想曲 / 交响诗为其常见体裁，属曲式学通行表述
  - 自由曲式仍须具备内在组织逻辑（情绪弧线 / 素材关联等），为通行分析框架
updated: 2026-09-25
---

::: zh
自由曲式指的是一类作品：**它们不套用既有的曲式模式**（不是 ABA，也不是奏鸣曲式）。

但这里有个必须立刻纠正的误解：

> **"自由"不等于"没有曲式"** —— 它只是**不套用已有模式**，仍然必须具备内在的组织逻辑。

## 它靠什么被组织

自由曲式作品的"结构"常常写在别的地方：

| 组织手段 | 说明 |
|---|---|
| **情绪弧线** | 全曲按"紧张度"的起伏组织（见 [[concept:climax|高潮设计]]） |
| **速度与性格的对比段落** | 慢—快—慢—极快之类的交替 |
| **素材关联** | 不同段落共用同一动机或其变体（见 [[concept:theme-variations|变奏]]） |
| **标题 / 文学内容** | 交响诗按诗或故事推进，段落对应情节 |
| **调性迁移** | 全曲有一条调性路线（虽然不像奏鸣曲式那样对称） |

**注意最后一行之前的四项**：这些都是与主题无关的组织手段 ——
**说明"结构"并不只等于"主题怎么摆"**（这与 [[concept:large-scale-forms|大型作品结构]] 那条的结论一致）。

## 常见体裁

| 体裁 | 特征 |
|---|---|
| **前奏曲** | 短、单一情绪，常不再划分段落 |
| **幻想曲** | 最典型的自由曲式：写法自由，常含即兴成分 |
| **狂想曲** | 段落对比强烈，常引用民间素材 |
| **交响诗** | 单乐章，按文学或绘画内容推进 |
| **练习曲**（音乐会练习曲） | 技术目的 + 自由结构 |

**幻想曲最适合当代表**：它的名字本身就是"自由"（fantasia = 想象）——
巴洛克时期它甚至意味着"不按赋格那样严格"。

## 怎么分析它

分析自由曲式**不能靠贴字母**，而要靠**描述**：

| 步骤 | 做什么 |
|---|---|
| **1** | **找段落边界** —— 仍然看终止式与速度/性格的明显变化 |
| **2** | **描述每段的性格**，而不是给它贴 A/B/C |
| **3** | **问"为什么按这个顺序"** —— 情绪弧线？故事情节？素材关联？ |
| **4** | 若某段确实符合既有曲式，**就标出来**（自由曲式里常夹着奏鸣曲式段、赋格段） |

**第 3 步是关键**：它把分析从"归类"变成了"解释"。
这也解释了为什么自由曲式是**"曲式是描述、不是规定"的最强证据**（见 [[concept:form|曲式]]）：
如果曲式是规定，这类作品就"不合格"；而它们恰恰是保留曲目里最重要的一批。

## 图示：结构写在别处

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">没有字母标记，但仍有清楚的走向 —— 结构写在情绪、速度、素材与内容上</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">情绪</text>
    </g>
    <path d="M0,10 C60,-6 120,-2 180,-18 C240,-32 300,-6 360,-24 C420,-38 460,-2 500,-6"
          fill="none" stroke="#E07A3F" stroke-width="2"/>
    <circle cx="360" cy="-24" r="5" fill="#E07A3F"/>
    <text x="372" y="-20" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">高点（常对应高潮）</text>

    <g transform="translate(0,52)">
      <g fill="#5B7FA8" opacity=".85">
        <rect x="0" y="-8" width="110" height="16" rx="2"/>
        <rect x="116" y="-8" width="90" height="16" rx="2"/>
        <rect x="212" y="-8" width="130" height="16" rx="2"/>
        <rect x="348" y="-8" width="152" height="16" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="9.5" text-anchor="middle">
        <text x="55" y="4" fill="#F2EEE6">慢 · 沉静</text>
        <text x="161" y="4" fill="#F2EEE6">快 · 冲动</text>
        <text x="277" y="4" fill="#F2EEE6">极慢 · 悬停</text>
        <text x="424" y="4" fill="#F2EEE6">急板 · 收束</text>
      </g>
      <text x="508" y="4" font-family="system-ui,sans-serif" font-size="10" fill="#6E6A64">← 速度与性格分段</text>
    </g>

    <text x="0" y="88" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      分析它不能靠贴字母，而要靠描述：找边界 → 描述性格 → 问"为什么按这个顺序"
    </text>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      若某段确实符合既有曲式（奏鸣曲式段 / 赋格段），就标出来 —— 自由曲式里常夹着它们
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      它是"曲式是描述不是规定"的最强证据：若曲式是规定，这批作品就不合格 —— 而它们恰是保留曲目的核心
    </text>
  </g>
</svg>
```

## 听一听：没有模式，但有走向

用 `progression` 听一段不成套的功能进行（结束不回到主调）。
**它不符合任何标准终止式，但仍有自己的走向** —— 自由曲式就是这样：
不套模式，但每一步都有理由。

```audiolab
{"type":"progression","key":"C4","degrees":["I","vi","IV","ii","V"],"label":"不成套的进行（不回到主调）","label_en":"A non-standard progression that does not return home","hint":"逐个和弦依次听：没有标准收束，但仍有方向","hint_en":"Hear each chord: no standard close, yet still directed"}
```

## 常见误解

- **「自由曲式就是没有曲式」** → 它只是不套用既有模式。**组织逻辑仍然存在**（情绪弧线、素材关联、标题内容）。
- **「自由曲式比规范曲式简单」** → 更难：**没有现成框架可以依靠**，一切都要自己建立。
- **「分析自由曲式没法下手」** → 可以：找段落边界 → 描述性格 → 追问顺序的理由。**第 3 步是重点。**
- **「自由曲式是近代才有的」** → 幻想曲、托卡塔在巴洛克时期就存在；近代增加的只是规模与标题性。
:::

::: en
Free form refers to works that **follow no pre-existing formal pattern** — neither ABA nor sonata form.

But one misunderstanding must be corrected at once:

> **"Free" does not mean "formless".** It means only that **no existing pattern is used**; an internal organising
> logic is still required.

## What holds such a work together

In free-form works, "structure" is usually written somewhere else:

| Means | Explanation |
|---|---|
| **emotional arc** | the whole organised by rises and falls of tension (see [[concept:climax|designing a climax]]) |
| **contrasting sections of tempo and character** | slow, fast, slow, very fast and so on |
| **material connections** | sections sharing a motive or its variants (see [[concept:theme-variations|variation]]) |
| **title or literary content** | a symphonic poem advances with the poem or story, sections matching events |
| **tonal journey** | a route through keys, though not symmetrical like sonata form's |

**Note the four items before the last**: none is thematic — **which shows that "structure" does not mean only "how
themes are arranged"** (the same conclusion reached under [[concept:large-scale-forms|large-scale structures]]).

## Common genres

| Genre | Feature |
|---|---|
| **prelude** | short, single mood, often undivided |
| **fantasia** | the most typical free form: free in manner, often improvisatory |
| **rhapsody** | strong sectional contrast, often quoting folk material |
| **symphonic poem** | single movement, advancing with a literary or pictorial subject |
| **concert étude** | a technical purpose in a free structure |

**The fantasia is the best representative**: the name itself means "freedom" (fantasia — imagination). In the
Baroque it even meant "not as strict as a fugue".

## How to analyse it

Free form **cannot be analysed by pasting letters on it**, but by **describing**:

| Step | Do this |
|---|---|
| **1** | **find the section boundaries** — still by cadences and clear changes of tempo or character |
| **2** | **describe each section's character** rather than labelling it A/B/C |
| **3** | **ask why this order** — an emotional arc? a story? material connections? |
| **4** | if a section does match a known form, **say so** (free forms often contain sonata-form or fugal stretches) |

**Step 3 is the crux**: it turns analysis from classification into explanation.
It also shows why free form is **the strongest evidence that form describes rather than prescribes** (see
[[concept:form|form]]): if form were a rule, these works would fail it — and they are among the most central in the
repertoire.

## Diagram: structure written elsewhere

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">No letter labels, yet a clear shape — structure lives in mood, tempo, material and content</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">mood</text>
    </g>
    <path d="M0,10 C60,-6 120,-2 180,-18 C240,-32 300,-6 360,-24 C420,-38 460,-2 500,-6"
          fill="none" stroke="#E07A3F" stroke-width="2"/>
    <circle cx="360" cy="-24" r="5" fill="#E07A3F"/>
    <text x="372" y="-20" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">a peak, usually the climax</text>

    <g transform="translate(0,52)">
      <g fill="#5B7FA8" opacity=".85">
        <rect x="0" y="-8" width="110" height="16" rx="2"/>
        <rect x="116" y="-8" width="90" height="16" rx="2"/>
        <rect x="212" y="-8" width="130" height="16" rx="2"/>
        <rect x="348" y="-8" width="152" height="16" rx="2"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="9.5" text-anchor="middle">
        <text x="55" y="4" fill="#F2EEE6">slow, still</text>
        <text x="161" y="4" fill="#F2EEE6">fast, urgent</text>
        <text x="277" y="4" fill="#F2EEE6">very slow, hanging</text>
        <text x="424" y="4" fill="#F2EEE6">presto, closing</text>
      </g>
    </g>

    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Analyse by description: find boundaries, describe characters, ask why this order
    </text>
    <text x="0" y="118" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      If a section does match a known form, label it — free forms often contain sonata or fugal stretches
    </text>
    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      The strongest evidence that form describes rather than prescribes
    </text>
  </g>
</svg>
```

## Listen: no pattern, but a direction

Use `progression` on a non-standard span that does not return home. **It matches no standard cadence, yet it has a
direction.** That is free form: no pattern, but every step has a reason.

```audiolab
{"type":"progression","key":"C4","degrees":["I","vi","IV","ii","V"],"label":"不成套的进行（不回到主调）","label_en":"A non-standard progression that does not return home","hint":"逐个和弦依次听：没有标准收束，但仍有方向","hint_en":"Hear each chord: no standard close, yet still directed"}
```

## Common misconceptions

- **"Free form means no form."** It means only that no existing pattern is used. **An organising logic remains** —
  emotional arc, material connections, or a title's content.
- **"Free form is easier than standard forms."** Harder: **there is no ready frame to lean on**, so everything must
  be built from scratch.
- **"It cannot be analysed."** It can: find boundaries, describe characters, then ask why the order. **Step 3 is the
  point.**
- **"Free form is modern."** Fantasias and toccatas exist from the Baroque; what is recent is their scale and their
  use of titles.
:::
