---
id: figured-bass
site: theo
cat: T5
title: 数字低音与通奏低音
title_en: Figured Bass and Continuo
summary: 只写一条低音线，用数字指示上方音——巴洛克把伴奏变成了可读的编码
summary_en: One bass line with figures telling you what to play above it — the Baroque turned accompaniment into readable code
level: standard
tags: [乐理, 和声, 巴洛克]
tags_en: [theory, harmony, baroque]
alias: [数字低音, 通奏低音, figured bass, basso continuo]
order: 34
links:
  - "[[concept:chord-inversion]]"
  - "[[concept:harmonic-function]]"
  - "[[concept:improvisation]]"
  - "[[concept:improvisation]]"
  - "[[period:baroque]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：低音线是全曲的和声骨架，通奏低音时代正是这样读低音的 | An organ hymn — the bass line carries the harmony, exactly how the bass was read in the continuo era
  - mutopia-000280 | 巴赫二部创意曲：低音与上方声部互相支撑，可听出巴洛克"低音驱动"的思维 | Bach's first two-part invention — bass and upper voice support each other, showing Baroque bass-driven thinking
  - mutopia-000287 | 巴赫第八首二部创意曲：同样的两声部织体，用于与上一条对照低音如何决定和声走向 | Bach's eighth two-part invention — the same two-voice texture, comparing how the bass determines the harmony
sources:
  - 数字低音用数字标记低音上方的音程（6 / 6-4 / 7 / 6-5 / 4-3 / 4-2），属巴洛克通奏低音实践通则
  - 通奏低音由低音乐器（大提琴 / 巴松）与和声乐器（羽管键琴 / 管风琴 / 琉特琴）组合实现，为音乐史通行记载
updated: 2026-09-24
---

::: zh
在巴洛克时期，作曲者常常**只写一条低音线**，在其下方标几个数字，
然后交给演奏者去完成上方的和声。这套做法叫**数字低音**（figured bass），
实际演奏方式叫**通奏低音**（basso continuo）。

> 一句话：**它是"和声思维"第一次被写成可读的编码。**

## 数字在说什么

数字标记的是**这个低音上方要叠什么音程**：

| 低音位置 | 数字 | 上方音 | 相当于 |
|---|---|---|---|
| 根音 | 无（或 7） | 三音、五音 | 原位 |
| 三音 | **6** | 三音 + 六音 | 第一转位 |
| 五音 | **6-4** | 六音 + 四音 | 第二转位 |
| 七音 | **4-2** | 四音 + 二音（+ 六音） | 七和弦第三转位 |

七和弦的另外两个转位记 **6-5**（第一转位）与 **4-3**（第二转位），
见 [[concept:chord-inversion|和弦转位与数字低音]]。

## 为什么它值得单独了解

**① 它解释了巴洛克音乐的"低音驱动"性格。**
既然和声是从低音往上推的，低音线就必然成为全曲最讲究的声部 ——
这直接塑造了那个时代的写作习惯：低音经常是级进的、线条化的，而不是"根音跳来跳去"。

**② 它是历史上第一次把"即兴伴奏"标准化。**
演奏者不是背下所有音，而是**读懂规则后当场实现（realize）**。
同一份数字低音，不同的演奏者会给出不同的织体 ——
这与今天看和弦记号弹伴奏是同一类实践，但**精度高得多**：数字说了要叠什么音程，
和弦记号只说和弦名。

**③ 它解释了"演奏家也是创作者"这件事的历史断裂。**
古典时期之后，作曲家越来越倾向于把每个声部都写死（见 [[concept:improvisation|即兴]] 一节的对照），
通奏低音逐渐消失。所以"演奏者有多大自由"这个问题，是**历史性的**，不是天然如此。

## 它怎么被演奏

| 角色 | 乐器 | 任务 |
|---|---|---|
| **低音乐器** | 大提琴 / 巴松 / 低音提琴 | 把低音线奏出来（音高由作曲家定） |
| **和声乐器** | 羽管键琴 / 管风琴 / 琉特琴 | 按数字补出上方和声（织体由演奏者定） |

两组合起来，就是"通奏低音组"。注意第二行的**自由范围**：音是作曲家给的，
**怎么排布由演奏者决定** —— 这与 [[concept:chord-voicing|和弦排列]] 讲的是同一件事。

## 图示：一份数字低音怎么读

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">低音线只写最下面一行；数字告诉你要在上面叠什么</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#6E6A64">G</text><text x="0" y="26" fill="#6E6A64">E</text><text x="0" y="52" fill="#6E6A64">C</text>
      <text x="140" y="0" fill="#5B7FA8">A</text><text x="140" y="26" fill="#5B7FA8">F</text><text x="140" y="52" fill="#5B7FA8">D</text>
      <text x="280" y="0" fill="#5B7FA8">A</text><text x="280" y="26" fill="#5B7FA8">F</text><text x="280" y="52" fill="#5B7FA8">D</text>
      <text x="420" y="0" fill="#6E6A64">G</text><text x="420" y="26" fill="#6E6A64">E</text><text x="420" y="52" fill="#6E6A64">C</text>
    </g>
    <g stroke="#343439" stroke-width="1.2">
      <line x1="14" y1="0" x2="126" y2="0"/><line x1="154" y1="0" x2="266" y2="0"/>
      <line x1="294" y1="0" x2="406" y2="0"/><line x1="434" y1="0" x2="546" y2="0"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E8C547" text-anchor="middle">
      <text x="0" y="72">C</text><text x="140" y="72">D</text><text x="280" y="72">D</text><text x="420" y="72">C</text>
    </g>
    <g font-family="Georgia,serif" font-size="11" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="90">—</text><text x="140" y="90">6</text><text x="280" y="90">6-4</text><text x="420" y="90">—</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="0" y="108" text-anchor="middle">原位</text>
      <text x="140" y="108" text-anchor="middle">第一转位</text>
      <text x="280" y="108" text-anchor="middle">第二转位</text>
      <text x="420" y="108" text-anchor="middle">原位</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      <text x="0" y="134">最下面一行是作曲家写的；上面几行是演奏者按数字补出来的（每次可以补得不一样）</text>
      <text x="0" y="156" fill="#6E6A64">数字说的是"叠什么音程"，不是"弹几个音" —— 织体、音区、是否加装饰都由演奏者决定</text>
    </g>
  </g>
</svg>
```

## 听一听：低音驱动的和声

用进行播放器听一段低音线条清晰的进行。请把注意力放在**最下面那个音**上 ——
巴洛克的和声正是从它往上构建的；上方的一切都可以变，低音定了，和声就定了。

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"低音驱动的进行（I → IV → V → I）","label_en":"Bass-driven harmony: I-IV-V-I","hint":"逐个和弦依次听，把注意力放在最低音上","hint_en":"Hear each chord in turn, focusing on the lowest note"}
```

## 常见误解

- **「数字低音就是和弦谱」** → 精度不同。数字说"上方叠什么音程"，和弦记号只说和弦名 —— 前者给的信息更具体也更容易实现。
- **「数字是"要弹几个音"」** → 说的是**音程**（与低音相距几度），不是数量。一个 6 可以只补两个音，也可以补四个。
- **「通奏低音是"随便即兴"」** → 实现方式有严格规则（要成什么音程、如何连接、外音怎么处理），自由在**织体与排列**，不在和声本身。
- **「它过时了，与现代无关」** → 今天用和弦记号弹伴奏、爵士里读 lead sheet，都是同一逻辑的延续；理解它会改变你对"演奏者自由度"的看法。
:::

::: en
In the Baroque era a composer would often write **only a bass line** with a few figures under it, leaving the
upper harmony to the performer. The notation is **figured bass**; the practice is **basso continuo**.

> In one line: **it was the first time harmonic thinking was written as readable code.**

## What the figures say

A figure states **which intervals to place above that bass note**:

| Bass note | Figure | Notes above | Equivalent to |
|---|---|---|---|
| root | none (or 7) | third, fifth | root position |
| third | **6** | a third and a sixth | first inversion |
| fifth | **6-4** | a sixth and a fourth | second inversion |
| seventh | **4-2** | a fourth and a second (plus a sixth) | third inversion of a seventh chord |

The remaining two inversions of a seventh chord are **6-5** (first) and **4-3** (second) — see
[[concept:chord-inversion|chord inversion and figured bass]].

## Why it deserves attention

**One: it explains the bass-driven character of Baroque music.** If harmony is built upward from the bass, the
bass line inevitably becomes the most carefully shaped voice — which shaped the writing habits of the age: bass
lines move by step and behave like real lines, rather than leaping from root to root.

**Two: it was the first standardisation of improvised accompaniment.** Performers did not memorise every note;
they **read the rules and realised the chord on the spot**. The same figured bass yields different textures from
different players — the same kind of practice as playing from chord symbols today, but **far more precise**:
figures state which intervals, symbols state only the chord name.

**Three: it explains the historical break in "the performer as creator".** After the Baroque, composers increasingly
wrote every voice out in full (see the comparison in [[concept:improvisation|improvisation]]), and continuo faded. So "how much freedom
does a performer have" is a **historical question**, not a natural constant.

## How it was played

| Role | Instruments | Task |
|---|---|---|
| **bass instrument** | cello, bassoon, double bass | plays the bass line (pitches fixed by the composer) |
| **harmony instrument** | harpsichord, organ, lute | supplies the upper harmony from the figures (texture chosen by the player) |

Together they form the continuo group. Note the **scope of freedom** in the second row: the notes are given, the
**arrangement is not** — the same question as [[concept:chord-voicing|chord voicing]].

## Diagram: how to read a figured bass

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Only the lowest line is written; the figures say what to stack above it</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#6E6A64">G</text><text x="0" y="26" fill="#6E6A64">E</text><text x="0" y="52" fill="#6E6A64">C</text>
      <text x="140" y="0" fill="#5B7FA8">A</text><text x="140" y="26" fill="#5B7FA8">F</text><text x="140" y="52" fill="#5B7FA8">D</text>
      <text x="280" y="0" fill="#5B7FA8">A</text><text x="280" y="26" fill="#5B7FA8">F</text><text x="280" y="52" fill="#5B7FA8">D</text>
      <text x="420" y="0" fill="#6E6A64">G</text><text x="420" y="26" fill="#6E6A64">E</text><text x="420" y="52" fill="#6E6A64">C</text>
    </g>
    <g stroke="#343439" stroke-width="1.2">
      <line x1="14" y1="0" x2="126" y2="0"/><line x1="154" y1="0" x2="266" y2="0"/>
      <line x1="294" y1="0" x2="406" y2="0"/><line x1="434" y1="0" x2="546" y2="0"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E8C547" text-anchor="middle">
      <text x="0" y="72">C</text><text x="140" y="72">D</text><text x="280" y="72">D</text><text x="420" y="72">C</text>
    </g>
    <g font-family="Georgia,serif" font-size="11" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="90">—</text><text x="140" y="90">6</text><text x="280" y="90">6-4</text><text x="420" y="90">—</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="0" y="108" text-anchor="middle">root position</text>
      <text x="140" y="108" text-anchor="middle">first inversion</text>
      <text x="280" y="108" text-anchor="middle">second inversion</text>
      <text x="420" y="108" text-anchor="middle">root position</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      <text x="0" y="134">The lowest row is the composer's; the rows above are supplied by the player, differently each time</text>
      <text x="0" y="156" fill="#6E6A64">Figures name intervals, not note counts — texture and register are the player's choice</text>
    </g>
  </g>
</svg>
```

## Listen: bass-driven harmony

Use the progression player on a progression with a clear bass line. Keep your attention on **the lowest note** —
Baroque harmony is built upward from it, and once the bass is fixed, the harmony is fixed. Everything above can
vary.

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"低音驱动的进行（I → IV → V → I）","label_en":"Bass-driven harmony: I-IV-V-I","hint":"逐个和弦依次听，把注意力放在最低音上","hint_en":"Hear each chord in turn, focusing on the lowest note"}
```

## Common misconceptions

- **"Figured bass is a chord chart."** It is more precise: figures state **which intervals above the bass**, while
  a chord symbol names the chord only.
- **"The numbers say how many notes to play."** They name **intervals** (the distance above the bass), not a
  count. A "6" may be filled in with two notes or four.
- **"Continuo means improvising freely."** Realisation follows strict rules (which intervals, how to connect, how
  to treat non-chord tones); the freedom lies in **texture and voicing**, not in the harmony itself.
- **"It is obsolete and irrelevant."** Playing from chord symbols, or a jazz musician reading a lead sheet, is the
  same logic continued — and understanding it changes how you think about a performer's freedom.
:::
