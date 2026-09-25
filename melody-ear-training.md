---
id: melody-ear-training
site: theo
cat: T8
title: 旋律的听辨
title_en: Hearing Melody
summary: 听旋律不是听绝对音高，而是听"关系"——三层由粗到细的方法
summary_en: Hearing a melody means hearing relations, not absolute pitches — three layers from coarse to fine
level: standard
tags: [乐理, 旋律, 练耳]
tags_en: [theory, melody, ear-training]
alias: [旋律听辨, 听旋律, melody ear training]
order: 22
links:
  - "[[concept:melody]]"
  - "[[concept:interval-ear-training]]"
  - "[[concept:phrase]]"
  - "[[concept:scale]]"
  - "[[concept:interval-melodic-role]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：轮廓以级进为主、句尾落音明确，是练"抓轮廓与落音"的最佳材料 | The Ode of Joy moves mostly by step with clear phrase endings — ideal for practising contour and landing note
  - thesession-019704 | 《小星星》：五音、两种时值，听辨时几乎不可能被复杂度干扰 | Twinkle Little Star uses five notes and two values, so complexity cannot get in the way
  - mutopia-000049 | 《绿袖子》：跳进与级进交替、句尾长音收束，可用于练习分辨"哪一步是跳进" | Greensleeves alternates leaps and steps and closes phrases on long notes, useful for spotting where the leaps fall
sources:
  - 旋律听辨的通行训练顺序（轮廓 → 落音 → 音程 → 记谱）为视唱练耳教学通则
  - 听觉记忆以音高"关系"为主而非绝对频率，为音乐心理学通行研究结论
updated: 2026-09-25
---

::: zh
听旋律的关键认识只有一句：

> **你记的不是频率，是关系。**

大多数人以为自己"记住了旋律"，其实记住的是**音与音之间的距离与方向** ——
所以把同一条旋律整体移到另一个调，仍然认得出（见 [[concept:scale|音阶]] 与调性无关的那一面）。

这也解释了为什么**听辨要从"关系"入手，而不是从"音名"入手**：
一上来就试图报音名，通常会在第二个音就卡住。

## 三层，由粗到细

| 层 | 听什么 | 忽略什么 | 大多数人现在的位置 |
|---|---|---|---|
| **① 轮廓** | 整体走向（上、下、拱形） | 具体音高、音程 | 通常已会 |
| **② 落音** | 每个乐句的**最后一个音** | 中间的音 | **最值得练** |
| **③ 音程** | 每一步的级进 / 跳进与宽度 | — | 需专门训练（见 [[concept:interval-ear-training|音程的听辨方法]]） |

**第②层最被低估。** 乐句的落音决定了句读与调式归属（见 [[concept:phrase|乐句与乐段]]），
而且**只要抓住落音，整条旋律的骨架就出来了** —— 中间的音可以之后再补。

## 具体做法

**第一步：只听轮廓，用手画。**
第一遍不要听音高，只用手跟着旋律上下比划。听完能画出走向，就算过了。

**第二步：只记落音。**
每个乐句结束的那个音，唱出来并记下它的**相对位置**（比句首高还是低、高多少）。
这比记整条旋律容易得多，但信息量最大。

**第三步：补中间的音。**
在已知骨架的前提下，把中间的音当作"从落音到落音之间的路径"来听 ——
问的是"这一步是级进还是跳进"，而不是"这是什么音"。

**第四步：写下来验证。**
听辨的检验标准是**能不能写出来**。写不出就是还没听清 —— 这与"感觉听懂了"是两件事。

## 一个常见的挫败及其原因

| 现象 | 真正的原因 |
|---|---|
| 听第二遍就忘了第一遍 | 在试图记**每一个音**，超负荷 |
| 能哼出来但说不出音程 | 音程层面还没训练（第③层） |
| 换一个调就听不出来了 | 一直在记**绝对音高**，没有抓关系 |
| 长旋律完全跟不上 | 没有用"乐句"分段，而是一口气听 |

**第一行与第四行是同一件事**：旋律必须**按句分段**来听，
因为听觉记忆的容量与"句"天然对齐（这正是 [[concept:breath-phrasing|呼吸与句读]] 在听觉上的对应）。

## 图示：三层剥开

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">先抓轮廓，再抓落音，最后才补中间的音 —— 顺序反了会很挫败</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="6" text-anchor="end">① 轮廓</text>
    </g>
    <path d="M0,0 L50,-16 L100,-6 L160,-22 L220,-10 L290,-26 L350,-4"
          fill="none" stroke="#5B7FA8" stroke-width="2"/>
    <text x="366" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">只看上下走向</text>

    <g transform="translate(0,54)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="-20" y="6" text-anchor="end">② 落音</text>
      </g>
      <g fill="#E8C547">
        <circle cx="160" cy="-12" r="6"/><circle cx="350" cy="6" r="6"/>
      </g>
      <path d="M0,10 L160,-6 L350,10" fill="none" stroke="#E8C547" stroke-width="1.4" stroke-dasharray="3 3"/>
      <text x="366" y="14" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">骨架：句尾停在哪个相对位置</text>
    </g>

    <g transform="translate(0,108)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="-20" y="6" text-anchor="end">③ 音程</text>
      </g>
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">
        <text x="0" y="10">级进 · 跳进 · 宽度 —— 在骨架已定的前提下补中间</text>
      </g>
    </g>

    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      听觉记忆的容量与"句"天然对齐 → 长旋律必须按句分段听
    </text>
  </g>
</svg>
```

## 听一听：从轮廓练起

用 `scale` 组件听**上行**与**下行**各一遍 —— 这就是第①层"轮廓"。
请先只听方向、不听音名，练到能立刻说出"上行"或"下行"。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4"],"label":"轮廓练习：上行","label_en":"Contour practice: rising","hint":"点「上行」——先只说方向，不要试图报音名","hint_en":"Try Up — state the direction only, do not name the pitches"}
```

## 常见误解

- **「听旋律就是听音名」** → 听的是**关系**（距离与方向），所以换调也能认出同一条旋律。
- **「记不住旋律是耳朵不好」** → 多半是**方法错了**（试图一次记住每个音，超出听觉记忆容量）。
- **「能哼出来就算听懂了」** → 哼得出来只说明轮廓抓住了；能不能**写下来**才是检验标准。
- **「练耳要专门抽时间」** → 三个层次都可以在平时听音乐时练：先只抓走向，再只抓句尾，最后再问音程。
:::

::: en
One recognition is all that matters:

> **What you remember is not frequency but relation.**

Most people believe they "remembered the melody". What they actually remembered is **the distance and direction
between notes** — which is why a melody moved to another key is still recognisable (see the side of
[[concept:scale|scales]] that is independent of key).

It also explains why **ear training starts from relations, not from note names**: trying to name pitches from the
first note usually breaks down by the second.

## Three layers, from coarse to fine

| Layer | What you hear | What you ignore | Where most people already are |
|---|---|---|---|
| **1 contour** | overall direction (up, down, arched) | exact pitches and intervals | usually fine |
| **2 landing notes** | the **last note** of each phrase | the notes in between | **the most worthwhile** |
| **3 intervals** | each step: leap or step, and how wide | — | needs dedicated training (see [[concept:interval-ear-training|ear training for intervals]]) |

**Layer 2 is the most undervalued.** A phrase's landing note determines the phrasing and the modal identity (see
[[concept:phrase|phrase and period]]), and **catching the landing notes gives you the whole skeleton** — the inner
notes can come later.

## How to practise

**Step 1: hear only the contour, draw it with your hand.** On the first listen, ignore pitch and trace the rise
and fall with a gesture. If you can draw the shape afterwards, you have passed.

**Step 2: note only the landings.** Sing the final note of each phrase and record its **relative position** (higher
or lower than the phrase's start, and by how much). Far easier than remembering everything, and far more
informative.

**Step 3: fill in the middle.** With the skeleton known, hear the inner notes as **the path from landing to
landing** — asking "was that a step or a leap", not "what note was that".

**Step 4: write it down to check.** The test of ear training is **whether you can write it out**. Being unable to
write it means you have not heard it, which is not the same as "it felt clear".

## A common frustration and its cause

| Symptom | Real cause |
|---|---|
| forgot the first half by the second listen | trying to store **every note**, which overloads memory |
| can hum it but cannot name intervals | layer 3 not yet trained |
| cannot recognise it in another key | storing **absolute pitches** instead of relations |
| cannot follow a long melody at all | not dividing it into phrases, hearing it in one gulp |

**Rows one and four are the same problem**: a melody must be heard **phrase by phrase**, because the capacity of
auditory memory aligns naturally with phrases — the aural counterpart of
[[concept:breath-phrasing|breathing and phrasing]].

## Diagram: peeling off the three layers

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Contour first, landings second, inner notes last — reverse the order and it becomes frustrating</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="6" text-anchor="end">1 contour</text>
    </g>
    <path d="M0,0 L50,-16 L100,-6 L160,-22 L220,-10 L290,-26 L350,-4"
          fill="none" stroke="#5B7FA8" stroke-width="2"/>
    <text x="366" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">direction only</text>

    <g transform="translate(0,54)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="-20" y="6" text-anchor="end">2 landings</text>
      </g>
      <g fill="#E8C547">
        <circle cx="160" cy="-12" r="6"/><circle cx="350" cy="6" r="6"/>
      </g>
      <path d="M0,10 L160,-6 L350,10" fill="none" stroke="#E8C547" stroke-width="1.4" stroke-dasharray="3 3"/>
      <text x="366" y="14" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">skeleton: where each phrase ends</text>
    </g>

    <g transform="translate(0,108)">
      <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
        <text x="-20" y="6" text-anchor="end">3 intervals</text>
      </g>
      <text x="0" y="10" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">
        steps, leaps, widths — filled in once the skeleton is secure
      </text>
    </g>

    <text x="0" y="140" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      Auditory memory aligns with phrases, so long melodies must be heard phrase by phrase
    </text>
  </g>
</svg>
```

## Listen: start from the contour

Use `scale` to hear a rising figure, then a falling one — that is layer 1. Hear only the direction, without naming
pitches, until you can state "rising" or "falling" instantly.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4"],"label":"轮廓练习：上行","label_en":"Contour practice: rising","hint":"点「上行」——先只说方向，不要试图报音名","hint_en":"Try Up — state the direction only, do not name the pitches"}
```

## Common misconceptions

- **"Hearing a melody means hearing note names."** You hear **relations** (distance and direction), which is why the
  same melody is recognisable in another key.
- **"Not remembering a melody means bad ears."** Usually the **method** is wrong — trying to store every note exceeds
  auditory memory.
- **"If you can hum it, you have heard it."** Humming shows the contour is caught; whether you can **write it out**
  is the real test.
- **"Ear training needs dedicated sessions."** All three layers can be practised while listening normally: first
  only the direction, then only the phrase endings, and finally the intervals.
:::
