---
id: register
site: theo
cat: T1
title: 音区
title_en: Register
summary: 音域是能到哪儿，音区是此刻待在哪儿
summary_en: Range is how far an instrument can go; register is where the music is sitting right now
level: standard
tags: [乐理, 配器, 基础]
tags_en: [theory, orchestration, basics]
alias: [音区与音域, 音域, range]
order: 50
links:
  - "[[concept:pitch]]"
  - "[[concept:octave]]"
  - "[[concept:clef]]"
  - "[[concept:staff]]"
  - "[[concept:timbre]]"
instances:
  - mutopia-000049 | 《绿袖子》加固定低音与变奏：高音旋律与低音 ground 分处两个音区，同曲内即可对比 | Greensleeves to a Ground with Division — a high melody over a low ground, two registers inside one piece
  - cyberhymnal-000695 | 管风琴圣咏：脚踏板走低音区、键盘走中高音区，一件乐器同时占住两个音区 | An organ hymn — the pedals hold the low register while the manuals work mid-to-high, two registers from one instrument
  - giantmidi-006222 | 音阶与琶音练习：逐级上行一条线扫过整个音区，音区的移动听得最直白 | Scale and arpeggio exercises — one line sweeping upward makes the shift of register unmistakable
sources:
  - 音区与音域的定义、谱号与加线的记法、各乐器音域的层级划分，属通行乐理与配器常识
  - 本文行文为原创，未采用参考源句式
updated: 2026-09-23
---

::: zh
一组乐器名单里，最容易混淆的两个词就是**音域**与**音区**。一句话分开：

- **音域**：一件乐器或一个人**能唱到的边界**，是范围，是一个固定属性。
- **音区**：某一时刻音乐**实际待在的位置**，是坐标，是随时在变的。

音域决定了作品能写多宽，音区决定了这一段听起来是什么质地。同一件乐器在不同音区里，
音色、力度潜力、发音反应会明显不同 —— 这也是配器时最先被考虑的事。

## 音区不是一个点，是一段范围

音区听起来像"某个音在哪儿"，但真正被感知到的从来是**一段范围**。三种最典型的形态：

| 形态 | 例子 | 听到的是什么 |
|---|---|---|
| 两个音区叠置 | 高音旋律 + 低音固定线条（ground） | 两条线各占一片，互不干扰 |
| 一件乐器同时跨两个音区 | 管风琴：脚踏板走低音、键盘走中高音 | 同一副音色在两端呈现不同重量 |
| 一条线自己扫过整个音区 | 音阶与琶音练习逐级上行 | 音区在移动，而不是两个静止的层 |

这三种形态说明**音区与音色是绑在一起的**：说"这段用哪件乐器"，其实是同时决定了音色和音区。
反过来，一件乐器在它的极端音区里，音色也常常会变成另一副样子 —— 低音区的长笛像气声，
高音区的大提琴会变薄，这些都不是"音不准"，而是构造带来的必然。


## 图示：音区与谱号的关系

```svg
<svg viewBox="0 0 640 256" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">从左到右 = 音高从低到高 · 竖条区为常见记谱覆盖的音区</text>
  </g>

  <g transform="translate(24,42)">
    <rect x="0" y="0" width="592" height="150" rx="3" fill="#17171A" stroke="#343439"/>
    <g stroke="#343439">
      <line x1="98" y1="0" x2="98" y2="150"/><line x1="196" y1="0" x2="196" y2="150"/>
      <line x1="294" y1="0" x2="294" y2="150"/><line x1="392" y1="0" x2="392" y2="150"/>
      <line x1="490" y1="0" x2="490" y2="150"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64" text-anchor="middle">
      <text x="49" y="142">低音区</text><text x="147" y="142">中低音区</text>
      <text x="245" y="142">中音区</text><text x="343" y="142">中高音区</text>
      <text x="441" y="142">高音区</text><text x="539" y="142">极高音区</text>
    </g>

    <g opacity=".92">
      <rect x="30" y="14" width="150" height="22" rx="2" fill="#E07A3F"/>
      <text x="188" y="30" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">低音管 / 大提琴（低音谱号）</text>

      <rect x="130" y="44" width="150" height="22" rx="2" fill="#E8C547"/>
      <text x="288" y="60" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">单簧管 / 中提琴（中音与高音谱号）</text>

      <rect x="250" y="74" width="150" height="22" rx="2" fill="#5B7FA8"/>
      <text x="408" y="90" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">小提琴 / 长笛 / 女高音（高音谱号）</text>

      <rect x="400" y="104" width="150" height="22" rx="2" fill="#9C7A3C"/>
      <text x="408" y="126" font-family="system-ui,sans-serif" font-size="11.5" fill="#9C7A3C">短笛 / 极高音区（需大量加线）</text>
    </g>
  </g>
</svg>
```

音区越高，记谱就越依赖**加线**或换用别的谱号 —— 因为五条线能稳稳容纳的范围只有一个多八度。
各谱号具体覆盖哪些音，见 [[concept:clef|谱号]]；谱表本身的读法见 [[concept:staff|五线谱]]。

## 听一听：从低到高走一遍

同一串音名在不同八度上重复，音区的移动会带来"重量感逐渐变轻"的直觉。

```audiolab
{"type":"scale","notes":["C2","C3","C4","C5","C6"],"label":"五个八度的 C","label_en":"C across five octaves","hint":"点「上行」逐级升高，注意越往上余音越短、越薄","hint_en":"Try Up: step by step, the higher tones die away faster and thinner","gap":0.44,"dur":0.36}
```

## 常见误解

- **「音域宽的乐器更好」** → 音域宽意味着在两端音区里必然有不好用的地方。不少乐器被选中恰恰是因为它在中音区特别均匀。
- **「女高音的音区永远比男低音高」** → 女高音可以唱到低音区（只是音色发暗），男低音也有高音区（只是吃力）。音区不是身份，是当前坐标。
- **「音区就是音高」** → 音高是单个音的位置，音区是一段音乐整体所在的位置范围。两者尺度不同。
- **「换了谱号就把音升高了」** → 谱号只改变**记谱**的读法，不改变实际音高。同一段音乐用中音谱号还是高音谱号写，发出来的声音一样。
:::

::: en
Two words in an instrument list are the easiest to confuse: **range** and **register**. One line separates them.

- **Range** is the boundary an instrument or a voice **can reach**. It is a span, and it is fixed.
- **Register** is where the music **actually sits** at a given moment. It is a coordinate, and it moves constantly.

Range decides how wide a piece can be written. Register decides what this passage sounds like. The same
instrument behaves quite differently in different registers — in timbre, in loudness potential, in how quickly
it speaks — which is why register is the first thing orchestration considers.

## A register is a stretch, not a point

Register sounds like "where one note sits", but what is actually perceived is always **a stretch of range**.
Three typical shapes:

| Shape | Example | What you hear |
|---|---|---|
| Two registers stacked | a high melody over a low ground line | two lines, each holding its own band |
| One instrument spanning both | an organ: pedals low, manuals mid-to-high | one colour that weighs differently at each end |
| One line sweeping the whole range | a scale or arpeggio exercise climbing step by step | register in motion, not two static layers |

These three shapes show that **register and timbre are tied together**: choosing which instrument plays a
passage decides the timbre and the register at the same time. Conversely, an instrument at the extremes of its
own range usually becomes a different animal — a low flute turns breathy, a high cello thins out. None of that
is "out of tune"; it is the construction showing through.


## Diagram: register and clef

```svg
<svg viewBox="0 0 640 256" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Left to right = low to high · the bars show the register each type of notation typically covers</text>
  </g>

  <g transform="translate(24,42)">
    <rect x="0" y="0" width="592" height="150" rx="3" fill="#17171A" stroke="#343439"/>
    <g stroke="#343439">
      <line x1="98" y1="0" x2="98" y2="150"/><line x1="196" y1="0" x2="196" y2="150"/>
      <line x1="294" y1="0" x2="294" y2="150"/><line x1="392" y1="0" x2="392" y2="150"/>
      <line x1="490" y1="0" x2="490" y2="150"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64" text-anchor="middle">
      <text x="49" y="142">low</text><text x="147" y="142">low-mid</text>
      <text x="245" y="142">middle</text><text x="343" y="142">mid-high</text>
      <text x="441" y="142">high</text><text x="539" y="142">very high</text>
    </g>

    <g opacity=".92">
      <rect x="30" y="14" width="150" height="22" rx="2" fill="#E07A3F"/>
      <text x="188" y="30" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">Bassoon / cello (bass clef)</text>

      <rect x="130" y="44" width="150" height="22" rx="2" fill="#E8C547"/>
      <text x="288" y="60" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">Clarinet / viola (alto and treble clefs)</text>

      <rect x="250" y="74" width="150" height="22" rx="2" fill="#5B7FA8"/>
      <text x="408" y="90" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">Violin / flute / soprano (treble clef)</text>

      <rect x="400" y="104" width="150" height="22" rx="2" fill="#9C7A3C"/>
      <text x="408" y="126" font-family="system-ui,sans-serif" font-size="11.5" fill="#9C7A3C">Piccolo / very high (many ledger lines)</text>
    </g>
  </g>
</svg>
```

The higher the music, the more notation depends on **ledger lines** or a different clef, because five lines
comfortably hold a little over one octave. Which pitches each clef covers is covered under
[[concept:clef|clef]]; reading the staff itself under [[concept:staff|staff]].

## Listen: walking from low to high

The same note name repeats at different octaves, and moving register brings a clear sense of weight draining
away.

```audiolab
{"type":"scale","notes":["C2","C3","C4","C5","C6"],"label":"五个八度的 C","label_en":"C across five octaves","hint":"点「上行」逐级升高，注意越往上余音越短、越薄","hint_en":"Try Up: step by step, the higher tones die away faster and thinner","gap":0.44,"dur":0.36}
```

## Common misconceptions

- **"A wider range is always better."** A wide range means both extremes are necessarily awkward. Many instruments are chosen precisely because they are unusually even in the middle.
- **"A soprano always sings higher than a bass."** A soprano can sing low (it just turns dark), and a bass has a high register (it just costs effort). Register is a coordinate, not an identity.
- **"Register means pitch."** Pitch is the position of one note; register is the positional band a whole passage occupies. Different scales of description.
- **"Changing the clef raises the notes."** A clef changes how notation is **read**, not the sounding pitch. The same passage written in alto or treble clef sounds identical.
:::
