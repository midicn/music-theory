---
id: pentatonic
site: theo
cat: T3
title: 五声音阶
title_en: Pentatonic Scale
summary: 一条没有半音的音阶——任何位置断开都不会撞上小二度
summary_en: A scale with no semitones at all — cut it anywhere and you never hit a minor second
level: core
tags: [乐理, 音阶, 五声]
tags_en: [theory, scale, pentatonic]
alias: [五声, pentatonic, 无半音音阶]
order: 18
links:
  - "[[concept:scale]]"
  - "[[concept:major-scale]]"
  - "[[concept:chinese-pentatonic]]"
  - "[[concept:semitone]]"
  - "[[concept:blues-scale]]"
  - "[[cn:wusheng-modes|五声调式（中国用法）]]"
instances:
  - mutopia-001727 | 《奇异恩典》全曲只用五个音，是"五声音阶听感"最短最干净的样本 | Amazing Grace uses only five pitches across the whole tune — the shortest, cleanest sample of pentatonic sound
  - thesession-019704 | 《小星星》同样落在五声范围内，可对照"五声也能有明确的调性感" | Twinkle Little Star also stays inside five notes, showing that pentatonic can still carry a clear tonal centre
  - giantmidi-006222 | 音阶练习里常含五声片段，可据此对照它比七声少了哪些音 | Scale exercises often include pentatonic fragments — a good way to hear which two notes the seven-note set adds back
sources:
  - 五声音阶可由大调音阶去掉第 4、7 级得到，为通行乐理表述
  - 五声音阶广泛存在于世界多处民间音乐中，属民族音乐学常识
updated: 2026-09-23
---

::: zh
五声音阶最简单的定义是：**大调音阶去掉第 4 级与第 7 级**，剩下的五个音就是它。

> C 大调：C D E **F** G A **B** C
> C 五声：C D E G A

去掉的这两个音（4 级与 7 级）有一个共同点：它们都参与了**小二度**（E–F、B–C）。
删掉它们之后，整条音阶里**一个半音都不剩**，相邻音之间全是全音或小三度。

## 没有半音，意味着什么

| 后果 | 说明 |
|---|---|
| **不存在明确的导音** | 少了大调里第 7 级对主音的小二度引力，旋律的"必须回到主音"感变弱 |
| **任意位置都能断开** | 任何音都可以当起点，都能得到一条听觉上站得住的音阶 → 所以五声有 5 种调式而非 1 种 |
| **旋法自由** | 少了两个"敏感音"，旋律更容易长时间停留、绕行，也更宽容（民间即兴常用它） |

这三条合起来解释了为什么五声音阶全世界都有：它**天然避开了最容易出错的音程**。

## 两种常见形态

| 形态 | 音程结构 | 听感 |
|---|---|---|
| **大调五声**（宫调式，见上方） | 全音 全音 小三度 全音 小三度 | 开阔、明亮 |
| **小调五声** | 小三度 全音 全音 小三度 全音 | 内敛、常用于即兴独奏 |

[[concept:blues-scale|蓝调音阶]]就是在小调五声里再加一个**降五度**得到的 —— 一个音，把它从"柔"变成"冲"。

## 中国的用法在这里之外

「宫商角徵羽」是五声在中国音乐里的**名称与用法体系**（哪个音当主音、怎么旋法、和什么乐器配），
属于中国音乐的语境。本站只讲结构，用法见 [[cn:wusheng-modes|五声调式（中国用法）]]；
结构层面的对照见 [[concept:chinese-pentatonic|中国五声调式]]。

## 图示：删掉两个音，半音就消失了

```svg
<svg viewBox="0 0 640 222" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">上：七个音（含两处半音）· 下：删掉第 4、7 级后，半音全部消失</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2" opacity=".9">
      <line x1="128" y1="12" x2="192" y2="12"/>
      <line x1="384" y1="12" x2="448" y2="12"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">
      <text x="160" y="24">半音</text><text x="416" y="24">半音</text>
    </g>
    <g stroke="#343439" stroke-dasharray="3 3">
      <line x1="192" y1="-24" x2="192" y2="44"/>
      <line x1="384" y1="-24" x2="384" y2="44"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="70">剪掉这两处</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="104">C</text><text x="112" y="104">D</text><text x="224" y="104">E</text>
      <text x="336" y="104">G</text><text x="448" y="104">A</text><text x="560" y="104">C</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="118" x2="560" y2="118"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="56" y="134">全音</text><text x="168" y="134">全音</text>
      <text x="280" y="134">小三度</text><text x="392" y="134">全音</text>
      <text x="504" y="134">小三度</text>
    </g>
    <text x="0" y="160" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      结果：全音与小三度交替，没有半音 → 任何位置都可以当主音
    </text>
  </g>
</svg>
```

## 听一听：五声与七声的对照

先听 C 五声（无半音、开阔），再听 C 大调（含两处半音）。
差别不在音的数量，而在"有没有那个让你想收束的半音"。

```audiolab
{"type":"scale","notes":["C4","D4","E4","G4","A4","C5"],"label":"C 大调五声","label_en":"C major pentatonic","hint":"点「上行」听：相邻音之间全是全音或小三度","hint_en":"Try Up — every step is a whole tone or a minor third","gap":0.42}
```

## 常见误解

- **「五声音阶是中国独有的」** → 苏格兰、爱尔兰、非洲、美洲原住民音乐里都有。它广泛存在的原因是结构上"宽容"，不是传播的结果。
- **「五声比七声简单、更原始」** → 少两个音不等于低级。它换来的是旋法自由度与即兴宽容度，是主动的选择。
- **「五声就是没有调性」** → 五声完全可以有明确的主音与调式色彩，见本页"两种形态"。
- **「五声里不能出现别的音」** → 实际演奏里常加入经过音与装饰音（蓝调音阶就是加了降五度的五声）。
:::

::: en
The simplest definition of a pentatonic scale: **take a major scale and remove degrees 4 and 7.**

> C major: C D E **F** G A **B** C
> C pentatonic: C D E G A

The two notes removed share one property: both take part in a **minor second** (E–F and B–C). Delete them and the
scale contains **no semitone at all** — every step is a whole tone or a minor third.

## What having no semitones means

| Consequence | Explanation |
|---|---|
| **No clear leading tone** | Without the minor second pulling up to the tonic, the sense that a melody *must* return home weakens |
| **It can be cut anywhere** | Any note works as a starting point, giving five equally usable modes instead of one |
| **Freedom of movement** | With the two "sensitive" notes gone, melodies can circle and linger — which is why folk improvisation favours it |

Together these explain why the pentatonic turns up all over the world: it **sidesteps the easiest intervals to
get wrong**.

## Two common forms

| Form | Pattern | Impression |
|---|---|---|
| **major pentatonic** (as above) | W W m3 W m3 | open, bright |
| **minor pentatonic** | m3 W W m3 W | inward, common for soloing |

The [[concept:blues-scale|blues scale]] is the minor pentatonic plus a **lowered fifth** — one note that turns
soft into gritty.

## The Chinese usage lies beyond this page

Gong, shang, jiao, zhi and yu form the **system of names and usage** that pentatonic material takes on in
Chinese music — which note leads, how lines move, which instruments pair with it. That belongs to the Chinese
music context: see [[cn:wusheng-modes|pentatonic modes in Chinese usage]] for the usage side, and
[[concept:chinese-pentatonic|Chinese pentatonic modes]] for the structural comparison.

## Diagram: remove two notes and the semitones vanish

```svg
<svg viewBox="0 0 640 222" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Top: seven notes with two semitones. Bottom: with degrees 4 and 7 removed, no semitone remains</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2" opacity=".9">
      <line x1="128" y1="12" x2="192" y2="12"/>
      <line x1="384" y1="12" x2="448" y2="12"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">
      <text x="160" y="24">semitone</text><text x="416" y="24">semitone</text>
    </g>
    <g stroke="#343439" stroke-dasharray="3 3">
      <line x1="192" y1="-24" x2="192" y2="44"/>
      <line x1="384" y1="-24" x2="384" y2="44"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="70">cut both away</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="104">C</text><text x="112" y="104">D</text><text x="224" y="104">E</text>
      <text x="336" y="104">G</text><text x="448" y="104">A</text><text x="560" y="104">C</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="118" x2="560" y2="118"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="56" y="134">W</text><text x="168" y="134">W</text>
      <text x="280" y="134">m3</text><text x="392" y="134">W</text>
      <text x="504" y="134">m3</text>
    </g>
    <text x="0" y="160" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Result: whole tones alternating with minor thirds, no semitone — any note can be the tonic
    </text>
  </g>
</svg>
```

## Listen: pentatonic against seven-note

Hear C pentatonic (no semitones, open), then C major (two semitones). The difference is not the number of notes
but whether that semitone which makes you want to close is present.

```audiolab
{"type":"scale","notes":["C4","D4","E4","G4","A4","C5"],"label":"C 大调五声","label_en":"C major pentatonic","hint":"点「上行」听：相邻音之间全是全音或小三度","hint_en":"Try Up — every step is a whole tone or a minor third","gap":0.42}
```

## Common misconceptions

- **"Pentatonic belongs to China."** It appears in Scottish, Irish, African and Native American music too. It is widespread because it is structurally **forgiving**, not because it spread from one place.
- **"Five notes is simpler and more primitive than seven."** Fewer notes is not lower grade; what it buys is freedom of movement and tolerance in improvisation.
- **"Pentatonic means no key."** It can carry a very clear tonic and modal colour — see the two forms above.
- **"No other notes may appear."** In practice passing and ornamental notes are common — the blues scale is a pentatonic with a lowered fifth added.
:::
