---
id: parallel-fifths
site: theo
cat: T5
title: 平行五八度
title_en: Parallel Fifths and Octaves
summary: 被禁的原因不是难听，而是听起来像少了一个声部
summary_en: They are avoided not because they sound bad, but because they make two voices sound like one
level: standard
tags: [乐理, 和声, 声部写作]
tags_en: [theory, harmony, part writing]
alias: [平行五八度, 平行五度, 平行八度, parallel fifths]
order: 18
links:
  - "[[concept:voice-leading]]"
  - "[[concept:counterpoint]]"
  - "[[concept:perfect-interval]]"
  - "[[concept:consonance]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏的四声部写法：正因避开平行五八度，四条线才各有独立感 | Four-part hymn writing avoids parallel fifths and octaves so that each of the four lines keeps its identity
  - mutopia-000280 | 巴赫二部创意曲第一首：两声部大量采用反向与斜向，独立性因此极强 | Bach's first two-part invention leans on contrary and oblique motion, giving the two voices strong independence
  - giantmidi-006222 | 音阶练习以级进为主，天然避开了同向跳进 —— 可对照"有规则"与"无规则"两种写法 | Stepwise exercises avoid similar leaps by nature — a useful contrast between rule-bound and unconstrained writing
sources:
  - 平行五度与平行八度在和声写作中被避免，原因在于声部独立性的丧失，属对位与和声学通则
  - 隐伏五八度（同向到达）同样受限、平行三六度则允许，为通行和声写作表述
updated: 2026-09-24
---

::: zh
"平行五八度被禁"是学和声时最早听到的规则，也是最容易被误解的规则 ——
因为它**不是关于好听不好听的**。

## 真正的原因

纯五度与纯八度**融合得太好**（见 [[concept:perfect-interval|纯音程]]）。
两个声部要是**连续**保持五度或八度关系，它们听起来就不再是两条线，
而是**一条线加了一层厚度**。

> 所以被禁的不是"这两个音"，而是"**连续**"这件事本身。
> 后果不是难听，而是**声部数量凭空少了一个**。

这与 [[concept:voice-leading|声部进行]] 的目标直接冲突：声部进行的一切努力，
都是为了让每条线听得出来。

| 连续的音程 | 后果 |
|---|---|
| 平行五度 | 两声部合成一条线（五度的"空"使其更明显） |
| 平行八度 | 两声部合成一条线（更彻底，听起来像一个声部的加厚） |
| 平行三度、六度 | **允许** —— 三六度是"不完全协和"，不产生融合效应 |

最后一行是关键对照：**规则禁的是"完全协和音程的平行"，不是"平行"本身。**

## 两种相关情形

| 情形 | 说明 | 处理 |
|---|---|---|
| **隐伏五八度** | 两声部**同向**到达五度或八度，且**高声部有跳进** | 同样避免 —— 会有类似"合成"的听感 |
| **同向到达但高声部级进** | 效果弱得多 | 通常允许 |

## 为什么这条规则会被过度夸大

因为它是"最好教"的一条：容易看出、容易判分。于是它被当成和声学的代表规则，
甚至被误传成"平行五度听起来难听"——

**实际情况是**：平行五度在民间音乐、格里高利圣咏、印象派与摇滚里都很常见，
听感并不刺耳。它在**四声部写作训练**里被禁，是因为那套写作的目标是
**声部独立**，而不是"好听"。

## 图示：融合 vs 独立

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">两条线能不能被听成两条，取决于它们之间保持什么音程</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#C0504A" text-anchor="middle">
      <text x="0" y="0">G</text><text x="60" y="0">A</text><text x="120" y="0">B</text><text x="180" y="0">C</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#C0504A" text-anchor="middle">
      <text x="0" y="52">C</text><text x="60" y="52">D</text><text x="120" y="52">E</text><text x="180" y="52">F</text>
    </g>
    <g stroke="#C0504A" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="6" x2="0" y2="46"/><line x1="60" y1="6" x2="60" y2="46"/>
      <line x1="120" y1="6" x2="120" y2="46"/><line x1="180" y1="6" x2="180" y2="46"/>
    </g>
    <text x="0" y="76" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">平行五度：每一步都是五度</text>
    <text x="0" y="94" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">→ 听成一条线 + 一层厚度</text>

    <g transform="translate(280,-6)">
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">G</text><text x="60" y="0">F</text><text x="120" y="0">E</text><text x="180" y="0">D</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="52">C</text><text x="60" y="52">D</text><text x="120" y="52">E</text><text x="180" y="52">F</text>
      </g>
      <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
        <line x1="0" y1="6" x2="0" y2="46"/><line x1="60" y1="6" x2="60" y2="46"/>
        <line x1="120" y1="6" x2="120" y2="46"/><line x1="180" y1="6" x2="180" y2="46"/>
      </g>
      <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">反向进行：两声部方向相反</text>
      <text x="0" y="100" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">→ 听成两条独立的线</text>
    </g>
  </g>
</svg>
```

## 听一听：两条线与一条线

用进行播放器听一条常规进行。留意低音与上方声部**方向不同**时，
两条线是如何各自被听出来的 —— 这正是平行五八度所牺牲掉的东西。

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"常规进行（声部方向不同）","label_en":"A standard progression, voices moving in different directions","hint":"逐个和弦依次听，留意低音与上方的方向关系","hint_en":"Hear each chord in turn and watch how bass and upper voices relate"}
```

## 常见误解

- **「平行五度听起来难听」** → 听起来并不难听，民间音乐与摇滚里遍地都是。被禁是因为**声部独立性**。
- **「平行三度六度也被禁」** → 允许。三六度是不完全协和，不产生"融合成一条线"的效果。
- **「现代音乐没有这条规则」** → 印象派、爵士、摇滚确实自由使用；但只要你写的是**要求声部独立的四声部织体**，这条规则仍然适用。
- **「同向到达五度一定不行」** → 要看高声部：**有跳进**的隐伏五八度通常避免，级进到达则宽松得多。
:::

::: en
"Parallel fifths and octaves are forbidden" is the first rule most students hear, and the most misunderstood —
because it is **not about sounding good or bad.**

## The real reason

Perfect fifths and perfect octaves **fuse too well** (see [[concept:perfect-interval|perfect intervals]]). If two
voices **keep** a fifth or octave between them from one chord to the next, they stop being two lines and become
**one line with extra thickness**.

> So what is avoided is not "these two notes" but "**in succession**". The consequence is not ugliness — it is
> that **the texture has one voice fewer than it appears to have.**

That runs directly against the goal of [[concept:voice-leading|voice leading]], whose whole effort is to keep each
line audible.

| Consecutive interval | Consequence |
|---|---|
| parallel fifths | two voices merge into one (the fifth's hollowness makes it obvious) |
| parallel octaves | two voices merge, even more completely — it sounds like one thickened voice |
| parallel thirds and sixths | **permitted** — imperfect consonances do not fuse |

That last row is the key comparison: **the rule forbids parallel *perfect* consonances, not parallel motion.**

## Two related cases

| Case | Description | Treatment |
|---|---|---|
| **hidden (direct) fifths or octaves** | two voices arrive at a fifth or octave **by similar motion** with a **leap in the upper voice** | also avoided — a similar merging is heard |
| similar motion with a step in the upper voice | far weaker effect | generally permitted |

## Why the rule gets exaggerated

Because it is the easiest to teach: simple to spot and simple to mark. It therefore comes to stand for harmony in
general, and is even misreported as "parallel fifths sound bad".

**The reality**: parallel fifths are common in folk music, plainchant, Impressionism and rock, and they do not
grate. They are banned in **four-part writing exercises** because those exercises aim at **voice independence**,
not at pleasantness.

## Diagram: fusion versus independence

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Whether two lines are heard as two depends on the interval they keep between them</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#C0504A" text-anchor="middle">
      <text x="0" y="0">G</text><text x="60" y="0">A</text><text x="120" y="0">B</text><text x="180" y="0">C</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#C0504A" text-anchor="middle">
      <text x="0" y="52">C</text><text x="60" y="52">D</text><text x="120" y="52">E</text><text x="180" y="52">F</text>
    </g>
    <g stroke="#C0504A" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="6" x2="0" y2="46"/><line x1="60" y1="6" x2="60" y2="46"/>
      <line x1="120" y1="6" x2="120" y2="46"/><line x1="180" y1="6" x2="180" y2="46"/>
    </g>
    <text x="0" y="76" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">parallel fifths: a fifth at every step</text>
    <text x="0" y="94" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">heard as one line with extra thickness</text>

    <g transform="translate(280,-6)">
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">G</text><text x="60" y="0">F</text><text x="120" y="0">E</text><text x="180" y="0">D</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="52">C</text><text x="60" y="52">D</text><text x="120" y="52">E</text><text x="180" y="52">F</text>
      </g>
      <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
        <line x1="0" y1="6" x2="0" y2="46"/><line x1="60" y1="6" x2="60" y2="46"/>
        <line x1="120" y1="6" x2="120" y2="46"/><line x1="180" y1="6" x2="180" y2="46"/>
      </g>
      <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">contrary motion: the voices move opposite ways</text>
      <text x="0" y="100" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">heard as two independent lines</text>
    </g>
  </g>
</svg>
```

## Listen: two lines or one

Use the progression player on a standard progression. Notice how, when bass and upper voices move in **different
directions**, each line remains separately audible — exactly what parallel fifths give up.

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"常规进行（声部方向不同）","label_en":"A standard progression, voices moving in different directions","hint":"逐个和弦依次听，留意低音与上方的方向关系","hint_en":"Hear each chord in turn and watch how bass and upper voices relate"}
```

## Common misconceptions

- **"Parallel fifths sound bad."** They do not; folk and rock are full of them. They are avoided for the sake of **voice independence**.
- **"Parallel thirds and sixths are also banned."** They are permitted. Imperfect consonances do not fuse two lines into one.
- **"The rule no longer applies."** Impressionism, jazz and rock use them freely; but as long as the texture is **four-part writing meant to keep the voices independent**, the rule applies.
- **"Arriving at a fifth by similar motion is always wrong."** It depends on the upper voice: **hidden** fifths and octaves with a leap are normally avoided, while arriving by step is much freer.
:::
