---
id: chord-color
site: theo
cat: T4
title: 和弦的音响色彩
title_en: Chord Colour
summary: 同一个和弦，为什么有时明亮有时幽暗——音区、排列、重复音都在起作用
summary_en: Why one chord can sound bright here and murky there — register, voicing and doubling all play a part
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [和弦色彩, 音响色彩, chord colour]
order: 48
links:
  - "[[concept:chord]]"
  - "[[concept:chord-voicing]]"
  - "[[concept:register]]"
  - "[[concept:timbre]]"
  - "[[concept:consonance]]"
instances:
  - atepp-000195 | 德彪西《月光》：和弦的音区分布与附加音共同造成朦胧的色彩，是本条最直观的样本 | Debussy's Clair de lune — register distribution and added tones together produce its hazy colour, the clearest sample here
  - cyberhymnal-000695 | 管风琴圣咏：宽排列的柱式和弦造成庄重明亮的色彩，可与上一条对照 | An organ hymn — widely voiced block chords make a solemn, bright colour, a direct contrast with the above
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：同样的和弦在低音区密集排列时显得阴森，可听音区对色彩的支配作用 | Liszt's transcription of Danse macabre — the same chord types packed low sound sinister; register governs colour
sources:
  - 和弦色彩受音区、排列、重复音与乐器音色共同影响，属和声学与配器学通则
  - 低音区密集排列造成浑浊、高音区密集排列造成明亮，为配器通行表述
updated: 2026-09-24
---

::: zh
"和弦色彩"听起来主观，但它的成因是可以逐条拆开的。同一个 C 大三和弦，在下面这些条件下会听起来完全不同：

## 四个可调参数

| 参数 | 作用 | 倾向 |
|---|---|---|
| **音区** | 最有力的一个 | 低音区 → 浑浊、沉重；中音区 → 清晰；高音区 → 明亮、单薄 |
| **排列** | 音之间的间距（见 [[concept:chord-voicing|和弦排列]]） | 密集 → 紧实；开放 → 宽阔 |
| **重复音** | 哪个音出现两次以上 | 重复根音 → 稳；重复三音 → 明确明暗；重复五音 → 空洞 |
| **乐器/音色** | 由谁演奏（见 [[concept:timbre|音色与波形]]） | 同一和弦，弦乐与铜管判若两人 |

把这四个参数当旋钮，就能理解为什么配器是一门独立的学问：**写对了音，还要放对地方。**

## 三个最常见的直觉错误

**① 以为"音越多越厚"。** 低音区密集排列只会糊；真正的厚度来自**跨音区的分布**。

**② 以为"高音区加音最能提亮"。** 高音区加音确实亮，但也容易变薄 —— 因为高音区缺少低频支撑。
更稳的做法是**低音区留根音、上方加色彩音**。

**③ 以为"协和音程一定好听"。** 低音区的纯五度会糊成一片（泛音相互干扰）。
协和与否不止取决于音程，也取决于**它在哪个音区**（见 [[concept:consonance|协和与不协和]]）。

## 一句可用的口诀

> **低音给重量，中音给清晰，高音给光泽。**

写和弦时按这三层分配，色彩问题基本就解决了。

## 图示：同一和弦的四种色彩

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样一个 C 大三和弦，参数一变，色彩就变</text>
  </g>

  <g transform="translate(40,52)">
    <g>
      <rect x="0" y="0" width="132" height="96" rx="4" fill="#17171A" stroke="#343439"/>
      <text x="66" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A" text-anchor="middle">低音区密集</text>
      <g fill="#C0504A">
        <circle cx="46" cy="60" r="5"/><circle cx="66" cy="64" r="5"/><circle cx="86" cy="68" r="5"/>
      </g>
      <text x="66" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">浑浊、沉重</text>
    </g>
    <g transform="translate(152,0)">
      <rect x="0" y="0" width="132" height="96" rx="4" fill="#17171A" stroke="#343439"/>
      <text x="66" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8" text-anchor="middle">中音区密集</text>
      <g fill="#5B7FA8">
        <circle cx="46" cy="52" r="5"/><circle cx="66" cy="58" r="5"/><circle cx="86" cy="64" r="5"/>
      </g>
      <text x="66" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">清晰、辨识度高</text>
    </g>
    <g transform="translate(304,0)">
      <rect x="0" y="0" width="132" height="96" rx="4" fill="#17171A" stroke="#343439"/>
      <text x="66" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547" text-anchor="middle">跨音区开放</text>
      <g fill="#E8C547">
        <circle cx="30" cy="76" r="5"/><circle cx="66" cy="52" r="5"/><circle cx="102" cy="32" r="5"/>
      </g>
      <text x="66" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">宽阔、宏大</text>
    </g>
    <g transform="translate(456,0)">
      <rect x="0" y="0" width="132" height="96" rx="4" fill="#17171A" stroke="#343439"/>
      <text x="66" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F" text-anchor="middle">低音根音 + 高音色彩</text>
      <g fill="#E07A3F">
        <circle cx="30" cy="80" r="5"/><circle cx="80" cy="34" r="5"/><circle cx="100" cy="26" r="5"/>
      </g>
      <text x="66" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">既有重量又有光泽</text>
    </g>
  </g>
</svg>
```

## 听一听：同一组音，不同参数

用「整体」与「宽排列」听同一组音 —— 前者接近中音区密集，后者跨音区开放。
本条的结论只有一条：**写对了音不等于写对了音响。**

```audiolab
{"type":"chord","root":"C4","quality":"maj9","inversion":1,"label":"同一组音，两种排列","label_en":"One set of notes, two voicings","hint":"先听「整体」，再听「宽排列」对比","hint_en":"Hear Block first, then Open to compare"}
```

## 常见误解

- **「和弦色彩是主观感受」** → 成因可以逐条拆开：音区、排列、重复音、乐器，四项都可控。
- **「和弦决定一切」** → 和弦只决定音高组合；放在哪个音区、由什么乐器演奏，影响同样大。
- **「低音区加厚最有力量」** → 低音区密集排列会造成浑浊，适得其反。
- **「同一和弦在钢琴与管风琴上差不多」** → 音色差异极大（见 [[concept:timbre|音色与波形]]），同一和弦的两副面孔。
:::

::: en
"Chord colour" sounds subjective, but its causes can be separated one by one. The same C major triad will sound
completely different under the following conditions.

## Four adjustable parameters

| Parameter | Effect | Tendency |
|---|---|---|
| **register** | the most powerful of the four | low → murky and heavy; middle → clear; high → bright but thin |
| **voicing** | the spacing of the notes (see [[concept:chord-voicing|voicing]]) | close → compact; open → wide |
| **doubling** | which note appears more than once | doubling the root → solid; the third → clear major/minor; the fifth → hollow |
| **instrument** | who plays it (see [[concept:timbre|timbre]]) | the same chord from strings and from brass are two different objects |

Treat these four as knobs and you see why orchestration is its own discipline: **getting the notes right is only
half the job — they must also be put in the right place.**

## Three intuitive mistakes

**One: assuming more notes means more weight.** A close voicing low down only muddies; real weight comes from
**distribution across registers**.

**Two: assuming adding high notes brightens best.** It does brighten, but it also thins the sound, because the
top register has no low-frequency support. It works better to **keep the root low and add colour notes above**.

**Three: assuming consonant intervals always sound good.** A perfect fifth in a low register turns to mush as the
partials interfere. Consonance depends not only on the interval but on **where it sits** (see
[[concept:consonance|consonance and dissonance]]).

## A rule of thumb worth keeping

> **Low register for weight, middle for clarity, high for sheen.**

Distribute a chord across those three layers and most colour problems resolve themselves.

## Diagram: one chord, four colours

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One C major triad, and colour changing with the parameters</text>
  </g>

  <g transform="translate(40,52)">
    <g>
      <rect x="0" y="0" width="132" height="96" rx="4" fill="#17171A" stroke="#343439"/>
      <text x="66" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A" text-anchor="middle">close, low</text>
      <g fill="#C0504A">
        <circle cx="46" cy="60" r="5"/><circle cx="66" cy="64" r="5"/><circle cx="86" cy="68" r="5"/>
      </g>
      <text x="66" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">murky, heavy</text>
    </g>
    <g transform="translate(152,0)">
      <rect x="0" y="0" width="132" height="96" rx="4" fill="#17171A" stroke="#343439"/>
      <text x="66" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8" text-anchor="middle">close, middle</text>
      <g fill="#5B7FA8">
        <circle cx="46" cy="52" r="5"/><circle cx="66" cy="58" r="5"/><circle cx="86" cy="64" r="5"/>
      </g>
      <text x="66" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">clear, easy to identify</text>
    </g>
    <g transform="translate(304,0)">
      <rect x="0" y="0" width="132" height="96" rx="4" fill="#17171A" stroke="#343439"/>
      <text x="66" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547" text-anchor="middle">open, across registers</text>
      <g fill="#E8C547">
        <circle cx="30" cy="76" r="5"/><circle cx="66" cy="52" r="5"/><circle cx="102" cy="32" r="5"/>
      </g>
      <text x="66" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">wide, grand</text>
    </g>
    <g transform="translate(456,0)">
      <rect x="0" y="0" width="132" height="96" rx="4" fill="#17171A" stroke="#343439"/>
      <text x="66" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F" text-anchor="middle">low root + high colour</text>
      <g fill="#E07A3F">
        <circle cx="30" cy="80" r="5"/><circle cx="80" cy="34" r="5"/><circle cx="100" cy="26" r="5"/>
      </g>
      <text x="66" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">weight and sheen together</text>
    </g>
  </g>
</svg>
```

## Listen: one set of notes, different parameters

Hear the same notes as Block, then as Open — the first close to the middle register, the second spread across
registers. The conclusion of this entry is a single sentence: **getting the notes right is not the same as
getting the sound right.**

```audiolab
{"type":"chord","root":"C4","quality":"maj9","inversion":1,"label":"同一组音，两种排列","label_en":"One set of notes, two voicings","hint":"先听「整体」，再听「宽排列」对比","hint_en":"Hear Block first, then Open to compare"}
```

## Common misconceptions

- **"Chord colour is purely subjective."** Its causes separate cleanly: register, voicing, doubling and instrument are all controllable.
- **"The chord decides everything."** A chord fixes the pitch combination; which register and which instrument matter just as much.
- **"Thickening the bass gives the most power."** A close voicing low down muddies instead.
- **"A chord sounds much the same on piano and organ."** The timbres differ enormously (see [[concept:timbre|timbre]]) — one chord, two faces.
:::
