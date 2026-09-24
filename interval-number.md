---
id: interval-number
site: theo
cat: T2
title: 音程度数
title_en: Interval Number
summary: 度数只数音级名，与半音无关——这是音程的第一把尺子
summary_en: Degree counts letter names only, ignoring semitones — the first ruler for any interval
level: standard
tags: [乐理, 音程, 基础]
tags_en: [theory, interval, basics]
alias: [度数, 音程级数, degree]
order: 12
links:
  - "[[concept:interval]]"
  - "[[concept:note-name]]"
  - "[[concept:semitone]]"
  - "[[concept:major-minor-interval]]"
  - "[[concept:staff]]"
instances:
  - giantmidi-006222 | 音阶练习：相邻两个音之间永远只隔一个音级名，是"二度"最纯粹的样本 | A scale exercise — neighbouring notes are always one letter name apart, the purest sample of a second
  - mutopia-000522 | 《欢乐颂》主题几乎全是级进，可以连续数十次验证"数音级名"这件事 | The Ode to Joy theme moves almost entirely by step — dozens of chances to count letter names in a row
  - mutopia-000280 | 巴赫二部创意曲第一首：两声部交错时各类度数接连出现，适合把数法练成条件反射 | Bach's first two-part invention — as the voices interlace, one degree after another appears, good for making the counting automatic
sources:
  - 音程度数按音级名（含首尾）计数的定义，属乐理通则，各版教科书表述一致
  - 本文行文为原创，未采用参考源句式
updated: 2026-09-23
---

::: zh
数音程度数时，只有一件事要做：**从低音数到高音，看中间夹着几个音级名**。
C 到 E 是 C、D、E 三个，所以是三度；C 到 G 是 C、D、E、F、G 五个，所以是五度。

就这么简单，但初学者几乎都会在这里出错，原因只有一个：**手上还带着半音的观念**。

## 数名字，不数黑白键

| 音程 | 音级名数过来 | 度数 |
|---|---|---|
| C → D | C, D | 二度 |
| C → E | C, D, E | 三度 |
| C → G | C, D, E, F, G | 五度 |
| C → C（高八度） | C, D, E, F, G, A, B, C | 八度 |

度数**只看字母名**，与键盘上隔了几个黑白键毫无关系。这条规则带来的第一个反直觉结论是：
**同一个度数可以有不同的宽度**。C 到 E 之间隔了四个半音，D 到 F 之间只隔三个半音，
但两者都是"三度"——因为它们包含的音级名都是三个。

宽度的差别不是例外，而是常态。它由 [[concept:semitone|半音与全音]] 决定，
是 [[concept:major-minor-interval|大音程与小音程]] 分家的原因。

## 一条口诀：数的时候要**把两个音都数进去**

只数"中间隔了几个音"是最常见的错误。C 到 E 中间只隔一个 D，但这是**三度**不是二度，
因为 C 和 E 自己也要算。八个度数的名字（一、二、三、四、五、六、七、八）本质上就是
"这一串音级名一共有几个"。

> **度数 = 终点序号 − 起点序号 + 1**
> 例如 E 是第五个字母、B 是第七个字母 → 7 − 5 + 1 = 3，所以 E–B 是三度。

## 图示：数的是音级名，不是键位

```svg
<svg viewBox="0 0 640 236" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样的七级音名，取不同的首尾 → 得到不同的度数</text>
  </g>

  <g transform="translate(32,54)">
    <g font-family="Georgia,serif" font-size="13" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="46" y="0">D</text><text x="92" y="0">E</text>
      <text x="138" y="0">F</text><text x="184" y="0">G</text><text x="230" y="0">A</text>
      <text x="276" y="0">B</text><text x="322" y="0">C</text>
    </g>
    <g>
      <circle cx="0" cy="0" r="15" fill="none" stroke="#E07A3F" stroke-width="1.3"/>
      <circle cx="92" cy="0" r="15" fill="none" stroke="#E07A3F" stroke-width="1.3"/>
      <line x1="0" y1="22" x2="92" y2="22" stroke="#E07A3F" stroke-width="1"/>
      <line x1="0" y1="18" x2="0" y2="26" stroke="#E07A3F" stroke-width="1"/>
      <line x1="92" y1="18" x2="92" y2="26" stroke="#E07A3F" stroke-width="1"/>
      <text x="100" y="26" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">C–E：三个音级名 → 三度</text>
    </g>
    <g transform="translate(0,64)">
      <circle cx="0" cy="0" r="15" fill="none" stroke="#5B7FA8" stroke-width="1.3"/>
      <circle cx="184" cy="0" r="15" fill="none" stroke="#5B7FA8" stroke-width="1.3"/>
      <line x1="0" y1="22" x2="184" y2="22" stroke="#5B7FA8" stroke-width="1"/>
      <line x1="0" y1="18" x2="0" y2="26" stroke="#5B7FA8" stroke-width="1"/>
      <line x1="184" y1="18" x2="184" y2="26" stroke="#5B7FA8" stroke-width="1"/>
      <text x="192" y="26" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">C–G：五个音级名 → 五度</text>
    </g>
    <g transform="translate(0,128)">
      <circle cx="92" cy="0" r="15" fill="none" stroke="#E8C547" stroke-width="1.3"/>
      <circle cx="138" cy="0" r="15" fill="none" stroke="#E8C547" stroke-width="1.3"/>
      <line x1="92" y1="22" x2="138" y2="22" stroke="#E8C547" stroke-width="1"/>
      <line x1="92" y1="18" x2="92" y2="26" stroke="#E8C547" stroke-width="1"/>
      <line x1="138" y1="18" x2="138" y2="26" stroke="#E8C547" stroke-width="1"/>
      <text x="146" y="26" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">E–F：两个音级名 → 二度（只有半音宽）</text>
    </g>
  </g>
</svg>
```

最后一行是关键：E 到 F 明明紧挨在一起，却是**二度**。所以"挨得近"和"度数小"是两件事。

## 听一听：度数的两种宽度

下面这条谱例里的每个相邻音都是二度，但宽度并不一致 —— 数法一样，听感不同。

```notation
{"clef":"treble","notes":["C4","D4","E4","F4","G4","F4","E4","D4","C4"],"caption":"级进上下行：全是二度，宽窄却有别","caption_en":"Stepwise up and down — all seconds, yet not all the same width"}
```

```audiolab
{"type":"interval","a":"C4","b":"D4","label":"二度：全音宽","label_en":"A second — one whole tone wide","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E4，度数就从二变成三：数音级名即可，不必先想半音。","hint2_en":"Now set b to E4: the degree goes from second to third — just count letter names first."}
```

## 常见误解

- **「度数就是几个半音」** → 半音数属于 [[concept:semitone|音数]]，是另一把尺子。三度可能是四个半音，也可能是三个半音。
- **「度数越大听起来越远」** → 度数大只是音级名跨度大。纯八度跨度最大，却是最好认的音程之一。
- **「C 到 E 中间隔一个 D，所以是二度」** → 首尾都要算。数出来是"三个音级名"，就是三度。
- **「减二度、增一度这类写法是错的」** → 它们是合法音程，只是宽度极端。见 [[concept:augmented-diminished|增音程与减音程]]。
:::

::: en
To count an interval's degree, do exactly one thing: **count from the lower note up to the higher one and see how
many letter names are involved.** C to E is C, D, E — three names, so a third. C to G is C, D, E, F, G — five
names, so a fifth.

That is all there is to it, yet beginners get it wrong almost every time, for one reason:
**they are still thinking in semitones.**

## Count names, not keys

| Interval | Letter names counted | Degree |
|---|---|---|
| C to D | C, D | second |
| C to E | C, D, E | third |
| C to G | C, D, E, F, G | fifth |
| C to C (an octave up) | C, D, E, F, G, A, B, C | octave |

Degree looks **only at letter names** and has nothing to do with how many black or white keys lie in between.
The first counter-intuitive consequence: **one degree can come in different widths.** C to E spans four
semitones; D to F spans three — both are thirds, because both contain three letter names.

That difference in width is not an exception but the norm. It is decided by
[[concept:semitone|semitones and whole tones]], and it is why
[[concept:major-minor-interval|major and minor intervals]] exist at all.

## A rule of thumb: count **both** endpoints

Counting only the notes "in between" is the classic mistake. C to E has just one D in the middle, but it is a
**third**, not a second, because C and E count too. The eight degree names are really just "how many letter
names this span contains".

> **Degree = position of the last name − position of the first + 1**
> E is the fifth letter, B is the seventh → 7 − 5 + 1 = 3, so E–B is a third.

## Diagram: counting letter names, not keys

```svg
<svg viewBox="0 0 640 236" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same seven letter names, different pairs of endpoints → different degrees</text>
  </g>

  <g transform="translate(32,54)">
    <g font-family="Georgia,serif" font-size="13" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="46" y="0">D</text><text x="92" y="0">E</text>
      <text x="138" y="0">F</text><text x="184" y="0">G</text><text x="230" y="0">A</text>
      <text x="276" y="0">B</text><text x="322" y="0">C</text>
    </g>
    <g>
      <circle cx="0" cy="0" r="15" fill="none" stroke="#E07A3F" stroke-width="1.3"/>
      <circle cx="92" cy="0" r="15" fill="none" stroke="#E07A3F" stroke-width="1.3"/>
      <line x1="0" y1="22" x2="92" y2="22" stroke="#E07A3F" stroke-width="1"/>
      <line x1="0" y1="18" x2="0" y2="26" stroke="#E07A3F" stroke-width="1"/>
      <line x1="92" y1="18" x2="92" y2="26" stroke="#E07A3F" stroke-width="1"/>
      <text x="100" y="26" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">C–E: three letter names → a third</text>
    </g>
    <g transform="translate(0,64)">
      <circle cx="0" cy="0" r="15" fill="none" stroke="#5B7FA8" stroke-width="1.3"/>
      <circle cx="184" cy="0" r="15" fill="none" stroke="#5B7FA8" stroke-width="1.3"/>
      <line x1="0" y1="22" x2="184" y2="22" stroke="#5B7FA8" stroke-width="1"/>
      <line x1="0" y1="18" x2="0" y2="26" stroke="#5B7FA8" stroke-width="1"/>
      <line x1="184" y1="18" x2="184" y2="26" stroke="#5B7FA8" stroke-width="1"/>
      <text x="192" y="26" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">C–G: five letter names → a fifth</text>
    </g>
    <g transform="translate(0,128)">
      <circle cx="92" cy="0" r="15" fill="none" stroke="#E8C547" stroke-width="1.3"/>
      <circle cx="138" cy="0" r="15" fill="none" stroke="#E8C547" stroke-width="1.3"/>
      <line x1="92" y1="22" x2="138" y2="22" stroke="#E8C547" stroke-width="1"/>
      <line x1="92" y1="18" x2="92" y2="26" stroke="#E8C547" stroke-width="1"/>
      <line x1="138" y1="18" x2="138" y2="26" stroke="#E8C547" stroke-width="1"/>
      <text x="146" y="26" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">E–F: two letter names → a second (only a semitone wide)</text>
    </g>
  </g>
</svg>
```

The last row is the point: E and F sit right next to each other, yet the interval is a **second**. So "close
together" and "low degree number" are two different things.

## Listen: two widths of the same degree

Every step in this figure is a second, yet they are not all the same width — same counting, different sound.

```notation
{"clef":"treble","notes":["C4","D4","E4","F4","G4","F4","E4","D4","C4"],"caption":"级进上下行：全是二度，宽窄却有别","caption_en":"Stepwise up and down — all seconds, yet not all the same width"}
```

```audiolab
{"type":"interval","a":"C4","b":"D4","label":"二度：全音宽","label_en":"A second — one whole tone wide","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E4，度数就从二变成三：数音级名即可，不必先想半音。","hint2_en":"Now set b to E4: the degree goes from second to third — just count letter names first."}
```

## Common misconceptions

- **"The degree is just a number of semitones."** Semitone count belongs to [[concept:semitone|interval size]], a different ruler. A third can be four semitones or three.
- **"A bigger degree always sounds farther."** A high degree only means the letter names span more. The perfect octave spans the most and is one of the easiest intervals to identify.
- **"There is one D between C and E, so it is a second."** Both endpoints count. Three letter names means a third.
- **"Diminished seconds and augmented unisons are impossible."** They are legal intervals with extreme widths — see [[concept:augmented-diminished|augmented and diminished intervals]].
:::
