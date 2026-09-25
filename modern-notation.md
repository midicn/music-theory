---
id: modern-notation
site: theo
cat: T10
title: 现代记谱法
title_en: Contemporary Notation
summary: 当音乐不再以"音高 + 时值"为核心，传统记谱法的前提就不成立了
summary_en: When music stops centring on pitch and duration, the premises of traditional notation fail
level: standard
tags: [乐理, 记谱, 现代]
tags_en: [theory, notation, contemporary]
alias: [现代记谱法, 图形记谱, 比例记谱, contemporary notation]
order: 34
links:
  - "[[concept:staff]]"
  - "[[concept:note-values]]"
  - "[[concept:free-meter]]"
  - "[[concept:articulation]]"
  - "[[concept:improvisation]]"
instances:
  - atepp-000195 | 德彪西《月光》：虽然仍用传统记谱，但织体与和声已超出 19 世纪的惯例，是"传统谱面表达新内容"的过渡例 | Debussy's Clair de lune still uses traditional notation while its texture and harmony exceed nineteenth-century norms — a transitional case
  - atepp-000238 | 肖斯塔科维奇《前奏曲与赋格》Op.87：20 世纪作品仍可完全用传统记谱，说明"现代记谱"不是时代必然 | Shostakovich's Preludes and Fugues Op.87 show a twentieth-century work fully notatable in the traditional system
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：复杂织体与自由速度仍靠传统记号与文字说明表达 | Liszt's transcription of Danse macabre handles complex texture and free tempo with traditional signs and verbal instructions
sources:
  - 20 世纪以来出现的比例记谱、图形记谱、微分音与文字说明等记法，为通行当代音乐记谱表述
  - 传统记谱法以音高与时值为核心前提；当作品不以二者为核心时需另立记法，为通行表述
updated: 2026-09-25
---

::: zh
现代记谱法不是"更高级的记谱法"，而是**为传统记谱法表达不了的内容另立的记法**。

## 为什么需要它：前提失效

传统记谱法（见 [[concept:staff|五线谱]] 与 [[concept:note-values|音符时值]]）建立在两个前提上：

| 前提 | 传统记谱法如何应对 |
|---|---|
| **音高是离散的、有确定高度的** | 用位置表示 |
| **时值是比例化的、可等分的** | 用符尾与符点表示 |

**当作品不再以这两件事为核心时，记谱法就必须改**：

| 作品的特点 | 传统记谱法的问题 |
|---|---|
| 音高在**两个半音之间**（微分音） | 五线谱没有位置可写 |
| 时值**不确定**（由演奏者决定） | 符尾体系表达不了 |
| 重点是**音色与织体的变化**，而非音高 | 谱面写不下"变化过程" |
| 演奏法是**文字描述性的**（如"尽量慢地摩擦琴弦"） | 需要文字而非符号 |

**所以现代记谱法的多样性，根源在于音乐本身的重心转移** ——
与"记谱法服务于音乐实践"这条原则一致（见 [[concept:gongchepu|工尺谱]] 的取舍讨论）。

## 常见的几类做法

| 类型 | 做法 | 解决什么 |
|---|---|---|
| **比例记谱** | 谱面的**横向距离按时间比例**画 | 时值不确定、自由节拍 |
| **图形记谱** | 用图形、线条、色块表示过程 | 音色与织体的变化 |
| **微分音记号** | 特殊符号（↑↓ 或分数记号） | 半音之间的音高 |
| **文字说明** | 直接用文字描述演奏动作 | 演奏法无法符号化 |
| **开放式段落** | 只给材料与规则，由演奏者组合 | 即兴与偶然性 |

**第一行最常用**：**比例记谱**把"时间"从抽象比例变成**空间长度** ——
一眼就能看出"这里该持续多久"，代价是无法精确到毫秒（见 [[concept:free-meter|自由节拍与散板]]）。

## 它的代价：互操作性差

这是现代记谱法最大的实务问题：

| 问题 | 说明 |
|---|---|
| **没有统一标准** | 不同作曲家常**自制记号**并附说明 |
| **学习成本高** | 演奏者需先读说明才能演奏 |
| **难以长期流传** | 若说明丢失，谱面可能无法解读 |

**第二、三行值得对比**：传统记谱法的优势恰恰在于**它的标准化**
——一份 18 世纪的乐谱今天仍能读（见 [[concept:rhythmic-notation|节奏记谱]]）。
**所以现代记谱法并不"取代"传统记谱法，而是与之并存**：
能写清的内容仍用传统记法，写不清的才另立符号。

## 一个容易搞错的判断

**"20 世纪的音乐"不等于"必须用现代记谱法"**：

| 事实 | 说明 |
|---|---|
| 肖斯塔科维奇、普罗科菲耶夫等 | **完全用传统记谱** |
| 布列兹、利盖蒂、约翰·凯奇等 | 大量使用新记法 |
| 爵士与流行 | 用**和弦符号 + 主旋律谱**（lead sheet） |

**所以"用什么记谱法"取决于作品的内容需要，而不是取决于年代。**

## 图示：前提失效与对策

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">传统记谱法的两个前提失效时，才需要另立记法</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">前提</text>
    </g>
    <g fill="#5B7FA8" opacity=".8">
      <rect x="0" y="-10" width="200" height="20" rx="3"/>
    </g>
    <text x="100" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">音高离散 · 时值可等分</text>

    <g transform="translate(0,44)">
      <g fill="#C0504A" opacity=".8">
        <rect x="0" y="-10" width="200" height="20" rx="3"/>
      </g>
      <text x="100" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">前提失效</text>
      <g stroke="#343439" stroke-width="1.4" fill="none">
        <line x1="206" y1="0" x2="242" y2="0"/><polygon points="242,-5 252,0 242,5" fill="#343439" stroke="none"/>
      </g>
      <text x="262" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">微分音 · 不定时值 · 音色为重 · 文字性演奏法</text>
    </g>

    <g transform="translate(0,92)">
      <g fill="#E8C547">
        <rect x="0" y="-10" width="94" height="20" rx="3"/>
        <rect x="100" y="-10" width="94" height="20" rx="3"/>
        <rect x="200" y="-10" width="94" height="20" rx="3"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="9.5" fill="#1A0E06" text-anchor="middle">
        <text x="47" y="4">比例记谱</text><text x="147" y="4">图形记谱</text><text x="247" y="4">文字说明</text>
      </g>
      <text x="306" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">← 对策</text>
    </g>

    <text x="0" y="128" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      代价：没有统一标准、需附说明、难以长期流传 —— 所以它与传统记谱法并存，而不是取代它
    </text>
    <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      20 世纪作品并非必须用现代记谱法：肖斯塔科维奇全用传统记谱，爵士与流行用和弦符号谱
    </text>
  </g>
</svg>
```

## 听一听：确定性递减

用 `rhythm` 组件听**严格等距**的形态 —— 这是传统记谱法最擅长表达的"确定时值"。
现代记谱法常常要表达的，恰恰是**偏离这种确定性**（比例拉伸、自由节拍）。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":80,"label":"确定时值（传统记谱法的领域）","label_en":"Determinate values — the traditional system's home ground","hint":"点「播放」，注意严格的等距","hint_en":"Press play and notice the strict evenness"}
```

## 常见误解

- **「现代记谱法比传统记谱法先进」** → 它是**另一类工具**：解决传统记法表达不了的内容，代价是标准化与流通性。
- **「20 世纪音乐必须用现代记谱法」** → 不是。肖斯塔科维奇、普罗科菲耶夫都用传统记谱。
- **「图形记谱=随便画」** → 通常**附有明确说明**（哪些图形对应什么动作/音区），规范程度并不低。
- **「传统记谱法会被取代」** → 两者**并存**：能写清的内容仍用传统记法（这与工尺谱的历史结论一致）。
:::

::: en
Contemporary notation is not "more advanced notation" but **notations devised for what the traditional system
cannot express**.

## Why it is needed: the premises fail

Traditional notation (see [[concept:staff|the staff]] and [[concept:note-values|note values]]) rests on two
premises:

| Premise | How the traditional system handles it |
|---|---|
| **pitch is discrete, with definite heights** | represented by position |
| **duration is proportional and evenly divisible** | represented by flags and dots |

**When a work stops centring on those two things, the notation must change**:

| The music's feature | The traditional system's problem |
|---|---|
| pitch **between two semitones** (microtones) | no position to write it |
| duration **indeterminate**, left to the performer | the flag system cannot say it |
| the focus is **timbre and texture change**, not pitch | the page cannot show a "process" |
| the playing technique is **verbal** ("rub the string as slowly as possible") | words are needed, not signs |

**So the diversity of contemporary notation comes from a shift in the music's centre of gravity** — consistent with
the principle that notation serves musical practice (see the trade-offs discussed under
[[concept:gongchepu|gongche notation]]).

## The common families of solutions

| Type | Method | Solves |
|---|---|---|
| **proportional notation** | horizontal **distance on the page is proportional to time** | indeterminate durations, free metre |
| **graphic notation** | figures, lines and blocks for processes | timbral and textural change |
| **microtonal signs** | special symbols (arrows, fraction marks) | pitches between semitones |
| **verbal instructions** | describing the action in words | techniques that resist symbolisation |
| **open sections** | giving material and rules for the players to combine | improvisation and chance |

**The first is the commonest**: proportional notation turns time from an abstract ratio into **spatial length** —
you see at a glance how long something lasts, at the cost of millisecond precision (see
[[concept:free-meter|free metre and sanban]]).

## The cost: poor interoperability

This is contemporary notation's biggest practical problem:

| Problem | Explanation |
|---|---|
| **no common standard** | composers often invent signs and attach a key |
| **high learning cost** | the performer must read the instructions before playing |
| **poor survival** | if the key is lost, the page may become unreadable |

**The second and third rows bear comparison**: the traditional system's great strength is precisely **its
standardisation** — an eighteenth-century score is still readable today (see
[[concept:rhythmic-notation|notating rhythm]]). **So contemporary notation does not replace the traditional system
but coexists with it**: what can be written clearly still is, and only the unwritable gets new symbols.

## A judgement that is easily wrong

**"Twentieth-century music" does not imply "contemporary notation"**:

| Fact | Explanation |
|---|---|
| Shostakovich, Prokofiev and others | **entirely in traditional notation** |
| Boulez, Ligeti, John Cage and others | extensive use of new notations |
| jazz and pop | **chord symbols plus a lead melody** (lead sheets) |

**So which notation is used depends on what the work needs, not on the decade.**

## Diagram: premises failing and the responses

```svg
<svg viewBox="0 0 640 206" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">New notations are needed only when the traditional premises fail</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">premises</text>
    </g>
    <g fill="#5B7FA8" opacity=".8">
      <rect x="0" y="-10" width="200" height="20" rx="3"/>
    </g>
    <text x="100" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">discrete pitch, divisible duration</text>

    <g transform="translate(0,44)">
      <g fill="#C0504A" opacity=".8">
        <rect x="0" y="-10" width="200" height="20" rx="3"/>
      </g>
      <text x="100" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">premises fail</text>
      <g stroke="#343439" stroke-width="1.4" fill="none">
        <line x1="206" y1="0" x2="242" y2="0"/><polygon points="242,-5 252,0 242,5" fill="#343439" stroke="none"/>
      </g>
      <text x="262" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">microtones, open durations, timbre, verbal techniques</text>
    </g>

    <g transform="translate(0,92)">
      <g fill="#E8C547">
        <rect x="0" y="-10" width="94" height="20" rx="3"/>
        <rect x="100" y="-10" width="94" height="20" rx="3"/>
        <rect x="200" y="-10" width="94" height="20" rx="3"/>
      </g>
      <g font-family="system-ui,sans-serif" font-size="9.5" fill="#1A0E06" text-anchor="middle">
        <text x="47" y="4">proportional</text><text x="147" y="4">graphic</text><text x="247" y="4">verbal</text>
      </g>
      <text x="306" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">responses</text>
    </g>

    <text x="0" y="128" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Cost: no common standard, keys required, poor survival — so it coexists with traditional notation
    </text>
    <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Twentieth-century works need not use it: Shostakovich stayed traditional; jazz and pop use lead sheets
    </text>
  </g>
</svg>
```

## Listen: decreasing determinacy

Use `rhythm` to hear **a strictly even pattern** — the determinate durations the traditional system handles best.
What contemporary notation often needs to express is precisely **departure from that determinacy** (proportional
stretching, free metre).

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":80,"label":"确定时值（传统记谱法的领域）","label_en":"Determinate values — the traditional system's home ground","hint":"点「播放」，注意严格的等距","hint_en":"Press play and notice the strict evenness"}
```

## Common misconceptions

- **"Contemporary notation is more advanced."** It is **another kind of tool**: it solves what the traditional
  system cannot, at the cost of standardisation and circulation.
- **"Twentieth-century music must use it."** It need not; Shostakovich and Prokofiev wrote in the traditional
  system throughout.
- **"Graphic notation means scribbling."** It usually comes with an explicit **key** (which figure means which
  action or register), and is far from unregulated.
- **"The traditional system will be replaced."** The two **coexist**: whatever can be written clearly still is — the
  same conclusion reached for gongche notation.
:::
