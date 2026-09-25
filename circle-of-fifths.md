---
id: circle-of-fifths
site: theo
cat: T5
title: 五度圈
title_en: Circle of Fifths
summary: 十二个调按纯五度排成一圈——调号、近关系、功能链全在这一张图上
summary_en: Twelve keys arranged by perfect fifths — signatures, close relations and functional chains all live on this one diagram
level: core
tags: [乐理, 和声, 调性]
tags_en: [theory, harmony, tonality]
alias: [五度圈, 五度循环, circle of fifths]
order: 22
links:
  - "[[concept:key-signature]]"
  - "[[concept:modulation]]"
  - "[[concept:harmonic-function]]"
  - "[[concept:perfect-interval]]"
  - "[[concept:enharmonic]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：把十二个调逐一走一遍，正是五度圈上"环游"的实操 | Scale and cadence exercises walk the keys one by one — the circle of fifths done by hand
  - pdmx-000607 | 《小星星变奏曲》：各变奏之间的调性关系可用五度圈一眼定位 | In Mozart's Ah vous variations the key relations between variations can be located on the circle at a glance
  - mutopia-000522 | 《欢乐颂》主题：主—属—下属三个功能的位置，正好是五度圈上的相邻关系 | The Ode of Joy theme — tonic, dominant and subdominant sit next to each other on the circle
sources:
  - 五度圈按纯五度依次排列十二个调，升号与降号顺序由此得出，属乐理通则
  - 近关系调（相差一个调号）与等音调在圈上的位置关系，为通行表述
updated: 2026-09-24
---

::: zh
五度圈是一张**把十二个调按纯五度排成一圈**的图。它之所以值得单独成条，是因为
**乐理里一半的"记住就行"结论，都能在这张图上被推导出来**。

## 圈上的两条顺序

从 C 出发，顺时针每走一步升纯五度：

> **C → G → D → A → E → B → F♯ →（D♭）→ A♭ → E♭ → B♭ → F → C**

两件事同时成立：

| 方向 | 每走一步 | 结果 |
|---|---|---|
| **顺时针** | 加一个升号（或减一个降号） | 调号里的升号依次出现：**F C G D A E B** |
| **逆时针** | 加一个降号（或减一个升号） | 调号里的降号依次出现：**B E A D G C F**（正是升号顺序的倒序） |

所以"升号顺序为什么是 F–C–G–D–A–E–B"这个问题，答案就在圈上：**它就是五度圈顺时针走出来的次序**。

## 它能解释什么

| 问题 | 五度圈上的答案 |
|---|---|
| **调号有几个升降号？** | 数一数从 C 走到该调走了几步 |
| **哪些调是近关系？** | **相邻**的调（差 1 个调号）—— 转调最平滑（见 [[concept:modulation|转调]]） |
| **主—属—下属在哪？** | 主音**左右各一步**：顺时针是属，逆时针是下属（见 [[concept:harmonic-function|和声功能]]） |
| **升 F 和降 G 是什么关系？** | 圈上同一个位置的两种写法（见 [[concept:enharmonic|等音]]） |

第二行与第三行尤其有用：**功能关系在圈上就是"邻居关系"** ——
这解释了为什么 I–IV–V–I 听起来那么自然，也解释了为什么"属"推回"主"的力度最强。

## 为什么是五度，不是三度或四度

因为纯五度的比例是 **3:2** —— 最简单比例里唯一的非八度成员（见 [[concept:perfect-interval|纯音程]]）。
往上叠五度 12 次几乎回到原点（差一点，这个差就是音差），
所以它能"绕成一圈"，而叠三度或四度都做不到这一点。

## 图示：功能就在邻居之间

```svg
<svg viewBox="0 0 640 218" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">从 C 出发：左边一步是下属，右边一步是属 —— 功能关系就是邻居关系</text>
  </g>

  <g transform="translate(48,58)">
    <g>
      <circle cx="80" cy="50" r="30" fill="none" stroke="#5B7FA8" stroke-width="1.8"/>
      <text x="80" y="55" font-family="Georgia,serif" font-size="14" fill="#5B7FA8" text-anchor="middle">C</text>
      <text x="80" y="96" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">主 T</text>
    </g>
    <g>
      <circle cx="230" cy="50" r="30" fill="none" stroke="#E07A3F" stroke-width="1.8"/>
      <text x="230" y="55" font-family="Georgia,serif" font-size="14" fill="#E07A3F" text-anchor="middle">G</text>
      <text x="230" y="96" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">属 D（顺时针）</text>
    </g>
    <g>
      <circle cx="-70" cy="50" r="30" fill="none" stroke="#E8C547" stroke-width="1.8"/>
      <text x="-70" y="55" font-family="Georgia,serif" font-size="14" fill="#E8C547" text-anchor="middle">F</text>
      <text x="-70" y="96" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="middle">下属 S（逆时针）</text>
    </g>
    <g stroke="#343439" stroke-width="1.2" stroke-dasharray="4 3">
      <line x1="110" y1="50" x2="200" y2="50"/>
      <line x1="-40" y1="50" x2="50" y2="50"/>
    </g>
    <text x="155" y="42" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">纯五度</text>
    <text x="5" y="42" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">纯五度</text>

    <text x="310" y="16" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">再往右：D（2 升）→ A（3 升）→ E（4 升）…</text>
    <text x="310" y="36" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">再往左：B♭（2 降）→ E♭（3 降）→ A♭（4 降）…</text>
    <text x="310" y="62" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">相邻 = 近关系调（差 1 个调号）→ 转调最平滑</text>
    <text x="310" y="84" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">对面 = 最远关系（差 6 个调号）</text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      升号顺序 F–C–G–D–A–E–B 就是顺时针走出来的次序；降号顺序正好倒过来
    </text>
  </g>
</svg>
```

## 听一听：点着圈听

下面是一张可点的五度圈 —— **点任意一格，就听到那个调的主三和弦**，
圆心显示调名与升降号数。先点 C，再点相邻的 G，最后点对面的 F♯/G♭，比较三种距离的听感差别。

```audiolab
{"type":"circle","label":"五度圈（可点）","label_en":"Circle of fifths (clickable)","hint":"相邻 = 近关系；对面 = 最远","hint_en":"Neighbours are close keys; opposite is the farthest"}
```

## 常见误解

- **「五度圈是用来背调号的」** → 背调号只是它最浅的用途。它同时解释近关系、功能位置与等音关系。
- **「顺时针一定加升号」** → 严格说：顺时针是"加一个升号**或**减一个降号"。走过 6 个升号之后进入降号区。
- **「圈上相邻的调听起来很像」** → 只是**转调平滑**（共同音多），不等于"听起来像同一个调"。
- **「升 F 大调和降 G 大调是两个调」** → 音高完全相同，是等音调，只是记谱与使用习惯不同（见 [[concept:enharmonic|等音]]）。
:::

::: en
The circle of fifths is a diagram that **arranges the twelve keys by perfect fifths**. It deserves its own entry
because **half of the "just memorise it" conclusions in music theory can be derived from this one picture.**

## Two sequences on the circle

Start at C and step clockwise by a perfect fifth each time:

> **C → G → D → A → E → B → F♯ → (D♭) → A♭ → E♭ → B♭ → F → C**

Two things hold at once:

| Direction | Each step | Result |
|---|---|---|
| **clockwise** | add a sharp (or remove a flat) | sharps appear in the order **F C G D A E B** |
| **counter-clockwise** | add a flat (or remove a sharp) | flats appear in the order **B E A D G C F** — exactly the reverse |

So the question "why is the order of sharps F–C–G–D–A–E–B?" is answered on the circle: **that is the order you
get by walking clockwise.**

## What it explains

| Question | Answer on the circle |
|---|---|
| how many sharps or flats? | count the steps from C to that key |
| which keys are close? | **neighbouring** keys, one signature apart — the smoothest modulations (see [[concept:modulation|modulation]]) |
| where are tonic, dominant and subdominant? | **one step either side** of the tonic: clockwise is the dominant, counter-clockwise the subdominant (see [[concept:harmonic-function|harmonic function]]) |
| what is F♯ to G♭? | two spellings of one position (see [[concept:enharmonic|enharmonic]]) |

The second and third rows are especially useful: **functional relations are literally neighbour relations on the
circle** — which explains why I–IV–V–I sounds so natural, and why the dominant pushes hardest back to the tonic.

## Why fifths, and not thirds or fourths

Because the perfect fifth's ratio is **3:2** — the only non-octave member among the simplest ratios (see
[[concept:perfect-interval|perfect intervals]]). Stack fifths twelve times and you arrive almost back where you
started (the small discrepancy is the comma), so the chain **closes into a circle**. Stacking thirds or fourths
does not do this.

## Diagram: function lives among neighbours

```svg
<svg viewBox="0 0 640 218" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">From C: one step left is the subdominant, one step right the dominant — function as neighbourhood</text>
  </g>

  <g transform="translate(48,58)">
    <g>
      <circle cx="80" cy="50" r="30" fill="none" stroke="#5B7FA8" stroke-width="1.8"/>
      <text x="80" y="55" font-family="Georgia,serif" font-size="14" fill="#5B7FA8" text-anchor="middle">C</text>
      <text x="80" y="96" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">tonic</text>
    </g>
    <g>
      <circle cx="230" cy="50" r="30" fill="none" stroke="#E07A3F" stroke-width="1.8"/>
      <text x="230" y="55" font-family="Georgia,serif" font-size="14" fill="#E07A3F" text-anchor="middle">G</text>
      <text x="230" y="96" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">dominant (clockwise)</text>
    </g>
    <g>
      <circle cx="-70" cy="50" r="30" fill="none" stroke="#E8C547" stroke-width="1.8"/>
      <text x="-70" y="55" font-family="Georgia,serif" font-size="14" fill="#E8C547" text-anchor="middle">F</text>
      <text x="-70" y="96" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="middle">subdominant</text>
    </g>
    <g stroke="#343439" stroke-width="1.2" stroke-dasharray="4 3">
      <line x1="110" y1="50" x2="200" y2="50"/>
      <line x1="-40" y1="50" x2="50" y2="50"/>
    </g>
    <text x="155" y="42" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">a fifth</text>
    <text x="5" y="42" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">a fifth</text>

    <text x="310" y="16" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Further right: D (2 sharps), A (3), E (4)…</text>
    <text x="310" y="36" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">Further left: B♭ (2 flats), E♭ (3), A♭ (4)…</text>
    <text x="310" y="62" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">Neighbours are close keys — the smoothest modulations</text>
    <text x="310" y="84" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">Opposite is the farthest relation, six signatures away</text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The sharp order F-C-G-D-A-E-B is the clockwise walk; the flat order is its reverse
    </text>
  </g>
</svg>
```

## Listen: click around the circle

Below is a clickable circle — **click any segment to hear that key's tonic triad**, with the key name and
signature shown in the middle. Try C first, then the neighbouring G, then the opposite F♯/G♭, and compare how the
three distances feel.

```audiolab
{"type":"circle","label":"五度圈（可点）","label_en":"Circle of fifths (clickable)","hint":"相邻 = 近关系；对面 = 最远","hint_en":"Neighbours are close keys; opposite is the farthest"}
```

## Common misconceptions

- **"The circle is for memorising key signatures."** That is its shallowest use. It also explains close relations, functional positions and enharmonic equivalence.
- **"Clockwise always means adding a sharp."** Strictly, clockwise means adding a sharp **or** removing a flat. After six sharps you enter the flat region.
- **"Neighbouring keys sound alike."** They make modulations smooth, because they share notes — which is not the same as sounding like one key.
- **"F♯ major and G♭ major are two keys."** Identical pitches, enharmonic keys, differing only in notation and habit (see [[concept:enharmonic|enharmonic]]).
:::
