---
id: binary-form
site: theo
cat: T9
title: 二段体
title_en: Binary Form
summary: AB 两段——巴洛克舞曲的基本形态，也是奏鸣曲式的前身
summary_en: Two sections, A and B — the basic shape of Baroque dances and the ancestor of sonata form
level: standard
tags: [乐理, 曲式, 结构]
tags_en: [theory, form, structure]
alias: [二段体, 二部曲式, binary form]
order: 26
links:
  - "[[concept:form]]"
  - "[[concept:ternary-form]]"
  - "[[concept:sonata-form]]"
  - "[[concept:suite]]"
  - "[[concept:modulation]]"
instances:
  - atepp-000295 | 斯卡拉蒂键盘奏鸣曲 K.208：单乐章、两段各带反复，是二段体最干净的实例 | Scarlatti's Keyboard Sonata K.208 — one movement, two repeated sections, the cleanest instance of binary form
  - cyberhymnal-000695 | 管风琴圣咏：诗句结构常形成"两段并列"，可与二段体对照 | An organ hymn — its verses often form two parallel sections, a useful comparison
  - mutopia-000049 | 《绿袖子》加固定低音：固定低音的循环造成清晰的段落划分，可用于观察段落的反复 | Greensleeves to a Ground — the ground bass loop creates clear divisions, useful for observing repeated sections
sources:
  - 二段体（AB）的定义、巴洛克舞曲中"每段各重复一次"的记谱习惯，属曲式分析通则
  - 带再现的二段体与奏鸣曲式在调性设计上的传承关系，为通行音乐史与曲式学表述
updated: 2026-09-25
---

::: zh
二段体只有两个字母：**A B** —— 两段，各说一件事。

## 巴洛克舞曲的标配

在巴洛克时期，二段体是**舞曲的基本形态**，而且有一个固定的记谱习惯：

> **每一段都各重复一次** —— 记作 `‖: A :‖‖: B :‖`

所以实际听到的是 **A A B B**。这个习惯也解释了为什么巴洛克舞曲听起来
"每段都很短、但要反复" —— 那段反复不是装饰，而是**舞蹈本身需要**
（一段音乐要跳两遍：一遍向左、一遍向右，或用不同的步法）。

## 两种类型

| 类型 | 说明 | 例 |
|---|---|---|
| **简单二段体** | B 用新材料，与 A 形成对比 | 部分舞曲 |
| **带再现的二段体** | **B 的末尾回到 A 的开头材料** | 巴洛克舞曲与奏鸣曲乐章的小步舞曲 |

**判断方法很简单：听第二段的末尾有没有回来的感觉。**
若有，就是带再现的二段体；若 B 自始至终都是新东西，就是简单二段体。

## ⭐ 它是奏鸣曲式的前身

这是二段体最值得知道的一点。巴洛克二段体的调性走法是：

| 段 | 调性 | 对应后来的 |
|---|---|---|
| **A** | 从主调出发，**结束在属调**（或关系调） | 呈示部的**调性分裂** |
| **B** | 从属调出发，**走回主调** | 再现部的**调性统一**（雏形） |

把这个"走出去—走回来"的调性弧线**放大、加长，并在其中加入两个主题与展开**，
就得到了 [[concept:sonata-form|奏鸣曲式]]。

**所以奏鸣曲式不是凭空出现的，而是二段体的调性设计被放大、被戏剧化的结果。**

## 与三段体的关系

| | 二段体 | 三段体 |
|---|---|---|
| 结构 | AB | ABA |
| 有没有"回来" | 可能（带再现时） | **一定有** |
| 听者的完整感 | 相对弱 | 强 |

**带再现的二段体与三段体的边界其实很模糊**：
如果 B 段末尾的"再现"足够长、足够完整，分析者就会把它标成 ABA。
**这不是矛盾，而是说明曲式是连续谱，不是离散的分类框。**

## 图示：调性弧线

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">二段体的调性弧线：A 从主调走到属调，B 从属调走回主调</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">A 段</text>
      <text x="-20" y="54" text-anchor="end">B 段</text>
    </g>

    <g>
      <rect x="0" y="-14" width="120" height="24" rx="3" fill="#5B7FA8"/>
      <text x="60" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">主调</text>
      <g stroke="#343439" stroke-width="1.4" fill="none">
        <line x1="120" y1="0" x2="176" y2="0"/><polygon points="176,-5 186,0 176,5" fill="#343439" stroke="none"/>
      </g>
      <rect x="188" y="-14" width="120" height="24" rx="3" fill="#E07A3F"/>
      <text x="248" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">属调</text>
      <text x="320" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">← A 段结束在这里（分裂）</text>
    </g>

    <g transform="translate(0,54)">
      <rect x="0" y="-14" width="120" height="24" rx="3" fill="#E07A3F" opacity=".8"/>
      <text x="60" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">属调</text>
      <g stroke="#343439" stroke-width="1.4" fill="none">
        <line x1="120" y1="0" x2="176" y2="0"/><polygon points="176,-5 186,0 176,5" fill="#343439" stroke="none"/>
      </g>
      <rect x="188" y="-14" width="120" height="24" rx="3" fill="#E8C547"/>
      <text x="248" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">回主调</text>
      <text x="320" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">← B 段走回来（统一）</text>
    </g>

    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      把这条调性弧线放大加长、加入两个主题与展开 → 就是奏鸣曲式
    </text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      巴洛克习惯：每段各重复一次（A A B B）—— 那是舞蹈本身需要，不是装饰
    </text>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      曲式是连续谱，不是离散分类：带再现的二段体与三段体之间没有硬边界
    </text>
  </g>
</svg>
```

## 听一听：走出与走回

用 `progression` 听**主调 → 属调 → 回主调**的弧线。这就是二段体在最小尺度上的调性设计，
也是后来奏鸣曲式的骨架。

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","V","I"],"label":"A 段走到属调 → B 段走回主调","label_en":"A moves to the dominant; B returns home","hint":"逐个和弦依次听：这就是二段体的调性弧线","hint_en":"Hear each chord: this is binary form's tonal arc"}
```

## 常见误解

- **「二段体就是两段，没有回来」** → **带再现的二段体**（B 段末尾回到开头材料）非常常见，尤其在舞曲与奏鸣曲乐章里。
- **「巴洛克的反复是装饰」** → 那是**舞蹈本身的需要**（一段音乐要跳两遍）。反复是结构的一部分。
- **「二段体比三段体低级」** → 它是**奏鸣曲式的直接前身**。欧洲器乐几百年的发展都建立在这个形态上。
- **「曲式之间界限分明」** → 曲式是**连续谱**：带再现的二段体与三段体的边界，分析者常要给出一句说明才能定论。
:::

::: en
Binary form has only two letters: **A B** — two sections, each saying one thing.

## The standard shape of Baroque dances

In the Baroque, binary form was **the basic shape of the dance**, with a fixed notational habit:

> **each section is repeated** — written `‖: A :‖‖: B :‖`

So what is heard is **A A B B**. The habit explains why Baroque dances sound "short but repeated": the repeat is not
decoration, it is **what the dance needs** (the music is danced twice — to the left and to the right, or with
different steps).

## Two types

| Type | Explanation | Example |
|---|---|---|
| **simple binary** | B uses new material, contrasting with A | some dances |
| **rounded binary** | **B's ending returns to A's opening material** | Baroque dances and minuets in sonata movements |

**The test is simple: does the end of the second section feel like a return?** If so, it is rounded binary; if B is
new material throughout, it is simple binary.

## ⭐ It is the ancestor of sonata form

This is the most valuable thing to know about binary form. Its tonal route is:

| Section | Tonality | Later corresponds to |
|---|---|---|
| **A** | leaves the tonic and **ends in the dominant** (or relative key) | the exposition's **tonal split** |
| **B** | leaves the dominant and **walks back to the tonic** | the recapitulation's **tonal unity**, in embryo |

Scale that out-and-back tonal arc up, lengthen it, and add two subjects plus a development, and you have
[[concept:sonata-form|sonata form]].

**So sonata form did not appear from nowhere: it is binary form's tonal design enlarged and dramatised.**

## Its relation to ternary form

| | Binary | Ternary |
|---|---|---|
| Structure | AB | ABA |
| Is there a return? | possibly (when rounded) | **always** |
| Sense of completeness | weaker | strong |

**The border between rounded binary and ternary is genuinely fuzzy**: if B's closing return is long and complete
enough, analysts will label it ABA. **This is not a contradiction but a reminder that form is a continuum, not a
set of discrete boxes.**

## Diagram: the tonal arc

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Binary form's tonal arc: A walks from tonic to dominant, B walks back to the tonic</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">A</text>
      <text x="-20" y="54" text-anchor="end">B</text>
    </g>

    <g>
      <rect x="0" y="-14" width="120" height="24" rx="3" fill="#5B7FA8"/>
      <text x="60" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">tonic</text>
      <g stroke="#343439" stroke-width="1.4" fill="none">
        <line x1="120" y1="0" x2="176" y2="0"/><polygon points="176,-5 186,0 176,5" fill="#343439" stroke="none"/>
      </g>
      <rect x="188" y="-14" width="120" height="24" rx="3" fill="#E07A3F"/>
      <text x="248" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">dominant</text>
      <text x="320" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">A ends here: the split</text>
    </g>

    <g transform="translate(0,54)">
      <rect x="0" y="-14" width="120" height="24" rx="3" fill="#E07A3F" opacity=".8"/>
      <text x="60" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">dominant</text>
      <g stroke="#343439" stroke-width="1.4" fill="none">
        <line x1="120" y1="0" x2="176" y2="0"/><polygon points="176,-5 186,0 176,5" fill="#343439" stroke="none"/>
      </g>
      <rect x="188" y="-14" width="120" height="24" rx="3" fill="#E8C547"/>
      <text x="248" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#1A0E06" text-anchor="middle">home</text>
      <text x="320" y="3" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">B walks back: the unity</text>
    </g>

    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Enlarge and lengthen that arc, add two subjects and a development, and you have sonata form
    </text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Baroque habit: each section repeated, A A B B — the dance needs it, it is not decoration
    </text>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Form is a continuum: rounded binary and ternary have no hard border
    </text>
  </g>
</svg>
```

## Listen: walking out and back

Use `progression` on the arc **tonic, dominant, tonic**. This is binary form's tonal design at its smallest scale,
and the skeleton that later became sonata form.

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","V","I"],"label":"A 段走到属调 → B 段走回主调","label_en":"A moves to the dominant; B returns home","hint":"逐个和弦依次听：这就是二段体的调性弧线","hint_en":"Hear each chord: this is binary form's tonal arc"}
```

## Common misconceptions

- **"Binary means two sections with no return."** **Rounded binary** (B's ending returning to A's opening) is very
  common, especially in dances and sonata movements.
- **"Baroque repeats are decoration."** They are **what the dance needs** (the music is danced twice). The repeat is
  part of the structure.
- **"Binary form is inferior to ternary."** It is the **direct ancestor of sonata form**. Centuries of European
  instrumental music are built on this shape.
- **"Forms are cleanly separated."** Form is a **continuum**: the border between rounded binary and ternary often
  needs a sentence of explanation to settle.
:::
