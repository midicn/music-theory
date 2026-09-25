---
id: pedal-point
site: theo
cat: T5
title: 持续低音
title_en: Pedal Point
summary: 一个音赖着不走，上方和声翻天覆地——张力就是这样攒出来的
summary_en: One note refuses to move while the harmony churns above it — that is how tension accumulates
level: standard
tags: [乐理, 和声, 织体]
tags_en: [theory, harmony, texture]
alias: [持续低音, 持续音, 踏板音, pedal point, organ point]
order: 36
links:
  - "[[concept:harmonic-function]]"
  - "[[concept:cadence]]"
  - "[[concept:consonance]]"
  - "[[concept:chord-voicing]]"
  - "[[concept:theme-variations]]"
instances:
  - mutopia-000049 | 《绿袖子》加固定低音（Ground）的变奏：低音线条反复不变，上方不断变化，正是持续低音的教科书形态 | Greensleeves to a Ground — the bass repeats unchanged while everything above varies, the textbook form of a pedal point
  - cyberhymnal-000695 | 管风琴圣咏：持续低音的名字就来自管风琴的踏板，这一织体本就诞生在管风琴上 | An organ hymn — the pedal point takes its name from the organ pedal, where the device originated
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：浪漫派常用持续音制造累积的张力，可听它如何一直不放 | Liszt's transcription of Danse macabre — Romantic writing uses pedal points to pile up tension, and the refusal to move is audible
sources:
  - 持续低音指某一声部（通常在低音）持续不变、上方和声继续变化的织体手法，属和声学与配器通则
  - 术语 pedal point / organ point 源自管风琴踏板，属音乐史通行记载
updated: 2026-09-24
---

::: zh
持续低音（pedal point）的做法只有一句：**让一个音一直响着不动，上方照常换和弦。**

> 它的英文名 **pedal point**（也称 organ point）来自管风琴的**踏板** ——
> 这个手法最初就是靠脚踩着一个音、双手继续弹和声实现的。

## 为什么它能攒出张力

这是它最值得理解的一点，机制并不神秘：

**低音持续时，上方和声的张力得不到低音的"解决"。**
正常情况下，一个不协和的和弦要在低音走到它该去的位置时才松开；
现在低音赖着不动，张力只能**一层层往上堆**。

而**当低音终于移动的那一刻**，积攒的张力一次性释放 ——
所以持续低音几乎总是出现在**需要"憋一下再放"**的位置：

| 位置 | 作用 |
|---|---|
| **属持续音**（低音停在属音，上方走各和弦） | 推向终止式，最常用；它把"要回家了"这件事拖久一点再兑现 |
| **主持续音**（低音停在各调主音） | 开头铺陈（确定中心），或结尾扩大（把收束拉长） |
| **上方的持续音** | 同一声部（常是高音）持续，产生"上面的钟声"效果 |

## 它与"长音"的区别

| | 长音 | 持续低音 |
|---|---|---|
| 上方 | 不一定变化 | **必须继续变化**（否则就只是长音） |
| 作用 | 延长某个音 | **制造和声层面的张力累积** |

**判别标准很干脆：上方和声有没有继续动。** 不动就只是长音，动了才是持续低音。

## 与固定低音变奏的关系

持续低音最极端的用法是**整首作品都建立在它上面** —— 这就是「**固定低音变奏**」
（ground bass / basso ostinato）：低音主题反复循环，上方不断写新内容。

> 巴洛克时期极为流行：《绿袖子》的加固定低音变奏、帕赫贝尔《卡农》的低音、
> 大量恰空与帕萨卡利亚都属此类。
> 它与 [[concept:theme-variations|变奏曲式]] 的关系是：**变化在上方，不变在下方。**

## 图示：低音不动，上方在动

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">低音停在属音上，上方不断换和弦 —— 张力因此只能往上堆</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="0" y="22" fill="#6E6A64">A</text><text x="0" y="44" fill="#6E6A64">F</text>
      <text x="120" y="0" fill="#E07A3F">B</text><text x="120" y="22" fill="#6E6A64">G</text><text x="120" y="44" fill="#6E6A64">D</text>
      <text x="240" y="0" fill="#E07A3F">C</text><text x="240" y="22" fill="#6E6A64">A</text><text x="240" y="44" fill="#6E6A64">F♯</text>
      <text x="360" y="0" fill="#E07A3F">D</text><text x="360" y="22" fill="#6E6A64">B</text><text x="360" y="44" fill="#6E6A64">G</text>
      <text x="480" y="0" fill="#5B7FA8">E</text><text x="480" y="22" fill="#5B7FA8">C</text><text x="480" y="44" fill="#5B7FA8">G</text>
    </g>
    <g font-family="Georgia,serif" font-size="13" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="72">G</text><text x="120" y="72">G</text><text x="240" y="72">G</text>
      <text x="360" y="72">G</text><text x="480" y="72">C</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="2">
      <line x1="-16" y1="72" x2="416" y2="72"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="60" y="90" text-anchor="middle">低音一直是 G（属持续音）</text>
      <text x="480" y="90" text-anchor="middle" fill="#E8C547">终于移动</text>
    </g>
    <text x="0" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      四拍里低音一动不动，上方换了四次和声 —— 张力堆到最高，然后随低音的移动一次释放
    </text>
    <text x="0" y="138" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      判别标准：上方和声有没有继续动。不动就只是长音，动了才是持续低音
    </text>
  </g>
</svg>
```

## 听一听：低音不动的效果

用进行播放器听一段完整的功能进行。想象最低音**从头到尾停在同一个音上**（属持续音），
只有上方在换 —— 那就是持续低音的听感：**一直没解决，于是越攒越紧。**

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"常规进行（低音会移动）","label_en":"A normal progression, with the bass moving","hint":"逐个和弦依次听，留意低音每次都在换","hint_en":"Hear each chord in turn and notice the bass changing every time"}
```

## 常见误解

- **「持续低音就是长音」** → 判别标准是**上方是否继续变化**。上方不动就只是长音。
- **「它必须出现在最低声部」** → 最低声部最常见（也因而得名），但**高音或内声部同样可以持续**。
- **「它只能用在结尾」** → 属持续音确实常用于推向终止，但主持续音常用于**开头**确定中心（如许多前奏曲的起始几小节）。
- **「它只属于巴洛克」** → 浪漫派（李斯特、瓦格纳）用它堆积张力，流行音乐的低音踏板音、电子舞曲的持续 bass note 都是同一手法。
:::

::: en
A pedal point does one simple thing: **hold one note while the chords above it keep changing.**

> Its name comes from the organ's **pedal** (hence also "organ point") — the device began as holding a note with
> the foot while both hands continued the harmony.

## Why it accumulates tension

This is the part worth understanding, and the mechanism is not mysterious:

**While the bass holds, the tension in the upper harmony cannot be resolved by the bass.** Normally a dissonant
chord releases when the bass moves where it ought to go; if the bass refuses to move, the tension can only **pile
up**.

And **the moment the bass finally moves**, the accumulated tension discharges at once. That is why a pedal point
almost always appears where something must be **held back and then released**:

| Position | Function |
|---|---|
| **dominant pedal** (bass held on the dominant) | drives toward a cadence — the commonest use; it postpones the arrival a little longer |
| **tonic pedal** (bass held on the tonic) | opening exposition (fixing the centre) or closing expansion (stretching the close) |
| **upper pedal** | a high voice held, producing a "bell above" effect |

## How it differs from a long note

| | Long note | Pedal point |
|---|---|---|
| Above it | need not change | **must keep changing** (otherwise it is merely a long note) |
| Function | sustains a pitch | **accumulates harmonic tension** |

**The test is blunt: does the upper harmony keep moving?** If not, it is a long note; if it does, it is a pedal
point.

## Its relation to ground-bass variations

The most extreme use is a whole piece built on one — the **ground bass** (basso ostinato): a bass figure repeats
while everything above is newly written each time.

> It was extremely popular in the Baroque: the ground-bass variations on Greensleeves, the bass of Pachelbel's
> Canon, and a great many chaconnes and passacaglias. Its relation to
> [[concept:theme-variations|variation form]] is this: **change above, constancy below.**

## Diagram: the bass stays, everything above moves

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The bass holds on the dominant while the chords above change — tension can only pile up</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="0" y="22" fill="#6E6A64">A</text><text x="0" y="44" fill="#6E6A64">F</text>
      <text x="120" y="0" fill="#E07A3F">B</text><text x="120" y="22" fill="#6E6A64">G</text><text x="120" y="44" fill="#6E6A64">D</text>
      <text x="240" y="0" fill="#E07A3F">C</text><text x="240" y="22" fill="#6E6A64">A</text><text x="240" y="44" fill="#6E6A64">F♯</text>
      <text x="360" y="0" fill="#E07A3F">D</text><text x="360" y="22" fill="#6E6A64">B</text><text x="360" y="44" fill="#6E6A64">G</text>
      <text x="480" y="0" fill="#5B7FA8">E</text><text x="480" y="22" fill="#5B7FA8">C</text><text x="480" y="44" fill="#5B7FA8">G</text>
    </g>
    <g font-family="Georgia,serif" font-size="13" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="72">G</text><text x="120" y="72">G</text><text x="240" y="72">G</text>
      <text x="360" y="72">G</text><text x="480" y="72">C</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="2">
      <line x1="-16" y1="72" x2="416" y2="72"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="60" y="90" text-anchor="middle">the bass stays on G (a dominant pedal)</text>
      <text x="480" y="90" text-anchor="middle" fill="#E8C547">it finally moves</text>
    </g>
    <text x="0" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Four beats with the bass motionless and the harmony changing four times — then one move releases it all
    </text>
    <text x="0" y="138" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The test: is the upper harmony still moving? If not it is a long note, not a pedal point
    </text>
  </g>
</svg>
```

## Listen: the effect of a stationary bass

Use the progression player on a complete progression. Imagine the lowest note **staying on one pitch throughout**
(a dominant pedal) while only the upper parts change — that is the sound of a pedal point: **never resolved, so
ever tighter.**

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"常规进行（低音会移动）","label_en":"A normal progression, with the bass moving","hint":"逐个和弦依次听，留意低音每次都在换","hint_en":"Hear each chord in turn and notice the bass changing every time"}
```

## Common misconceptions

- **"A pedal point is a long note."** The test is **whether the upper harmony keeps changing**. If nothing above
  moves, it is only a long note.
- **"It must be in the lowest voice."** The bass is the commonest place (hence the name), but **upper and inner
  voices can hold too**.
- **"It only belongs at the end."** A dominant pedal usually drives a cadence, but a tonic pedal often opens a
  piece to establish the centre (as in the first bars of many preludes).
- **"It is Baroque only."** Romantic composers (Liszt, Wagner) used it to pile up tension, and a pop song's
  sustained bass note or a dance track's held bass is the same device.
:::
