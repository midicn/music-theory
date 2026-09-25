---
id: extended-chord
site: theo
cat: T4
title: 九、十一、十三和弦
title_en: Ninth, Eleventh and Thirteenth Chords
summary: 继续往上叠三度——五音先省略，然后是十一音与十三音
summary_en: Keep stacking thirds — the fifth goes first, then the eleventh and thirteenth arrive
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [九和弦, 十一和弦, 十三和弦, extended chord]
order: 40
links:
  - "[[concept:seventh-chord]]"
  - "[[concept:added-tone-chord]]"
  - "[[concept:suspended-chord]]"
  - "[[concept:chord-voicing]]"
  - "[[concept:scale-harmony]]"
instances:
  - atepp-000195 | 德彪西《月光》：九度与附加音作为持续色彩铺陈，是延伸和弦最早成体系的用法之一 | Debussy's Clair de lune — ninths and added tones laid out as sustained colour, among the earliest systematic uses of extensions
  - giantmidi-006222 | 琶音练习可按需弹出各层延伸音，用于听"叠得越高越复杂"的递进 | Scale exercises can sound each extension in turn, letting you hear the growing complexity
  - cyberhymnal-000695 | 管风琴圣咏作对照：传统和声以三和弦与七和弦为限，延伸和弦几乎不出现 | An organ hymn as a control — traditional harmony rarely goes beyond triads and seventh chords
sources:
  - 延伸和弦 = 在七和弦上继续叠三度（九、十一、十三度），属和声学通则
  - 高叠和弦常在排列中省略五音（有时省略其他音）以避免音程冲突，为通行和声学表述
updated: 2026-09-24
---

::: zh
七和弦是**叠三层三度**。继续往下叠，就得到延伸和弦：

| 层数 | 名称 | 从 C 起 | 状态 |
|---|---|---|---|
| 3 层 | 七和弦 | C–E–G–B（或 B♭） | 日常 |
| 4 层 | **九和弦** | C–E–G–B–D | 常用 |
| 5 层 | **十一和弦** | C–E–G–B–D–F | 有条件使用 |
| 6 层 | **十三和弦** | C–E–G–B–D–F–A | 有条件使用 |

规律很简单：**叠得越高，音越多；但实际弹出来时，音反而更少** —— 因为要做减法。

## 为什么要省音

| 冲突 | 处理 |
|---|---|
| 十一音（F）与三音（E）相隔半音，直接相撞 | **常省略三音**（此时听感接近挂四和弦） |
| 九音与根音相隔一个八度 + 二度，低音区会糊 | **抬高八度**，或省掉根音由低音部代奏 |
| 十三和弦有 7 个音，超出听觉分辨能力 | **省略五音、十一音**，留下根音、三音、七音、十三音 |

最常被省略的是**五音**：它对和弦性质的决定性最小（三音定明暗、七音定张力、根音定身份）。

## 一句有用的口诀

> **三音定明暗，七音定张力，九音加色彩，五音最先省。**

按这个优先级做减法，就得到爵士与流行里那种"音不多但很丰富"的和弦排列。

## 与加音和弦的区别

| | 加音和弦 | 延伸和弦 |
|---|---|---|
| 例 | Cadd9 = C–E–G–D | Cmaj9 = C–E–G–**B**–D |
| 七音 | **不含** | **含** |
| 听感 | 干净、开阔 | 更厚、更复杂 |

再提一次那个实用结论：**跳过七音就避开了一层不稳定**（见 [[concept:added-tone-chord|加音和弦]]）。

## 图示：叠到第六层，再减回去

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">左：理论上的十三和弦 · 右：实际弹奏时通常只留四个音</text>
  </g>

  <g transform="translate(48,50)">
    <g font-family="Georgia,serif" font-size="11.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="22">E</text><text x="0" y="44">G</text>
      <text x="0" y="66">B</text><text x="0" y="88">D</text><text x="0" y="110">F</text><text x="0" y="132">A</text>
    </g>
    <g stroke="#6E6A64" stroke-width="1.2"><line x1="14" y1="0" x2="14" y2="132"/></g>
    <text x="-34" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">根音</text>
    <text x="-34" y="44" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="end">五音</text>
    <text x="-34" y="66" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="end">七音</text>
    <text x="-34" y="110" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="end">十一音</text>
    <text x="-34" y="132" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="end">十三音</text>

    <g transform="translate(250,14)">
      <g font-family="Georgia,serif" font-size="11.5" text-anchor="middle">
        <text x="0" y="0" fill="#F2EEE6">C</text><text x="0" y="30" fill="#5B7FA8">E</text>
        <text x="0" y="60" fill="#E8C547">B♭</text><text x="0" y="90" fill="#6E6A64">A</text>
      </g>
      <g stroke="#E8C547" stroke-width="1.2"><line x1="14" y1="0" x2="14" y2="90"/></g>
      <text x="30" y="30" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">三音：明暗</text>
      <text x="30" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">七音：张力</text>
      <text x="30" y="90" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">十三音：色彩</text>
      <text x="30" y="116" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">五音最先省 · 十一音常省</text>
    </g>
  </g>
</svg>
```

## 听一听：延伸和弦

先听九和弦，再听加音和弦 —— 差别就在有没有七音那一层。

```audiolab
{"type":"chord","root":"C4","quality":"dom9","inversion":0,"label":"属九和弦（C–E–G–B♭–D）","label_en":"Dominant ninth (C–E–G–B♭–D)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「延伸和弦音越多越高级」** → 实际演奏里它们**音更少**：高叠和弦必须做减法，否则低音区糊成一团。
- **「九和弦就是加音和弦」** → 九和弦含七音，add9 不含（见上表）。
- **「十一和弦不能用」** → 能用，但十一音与三音相隔半音，通常要省掉三音或把十一音抬高。
- **「十三和弦有十三个音」** → 只有七个（根、三、五、七、九、十一、十三），而且常用省音后只剩四个。
:::

::: en
A seventh chord **stacks three thirds**. Keep going and you get the extended chords:

| Layers | Name | From C | Status |
|---|---|---|---|
| 3 | seventh chord | C–E–G–B (or B♭) | everyday |
| 4 | **ninth chord** | C–E–G–B–D | common |
| 5 | **eleventh chord** | C–E–G–B–D–F | conditional |
| 6 | **thirteenth chord** | C–E–G–B–D–F–A | conditional |

The pattern is simple: **the higher you stack, the more notes exist — and the fewer you actually play**, because
subtraction becomes mandatory.

## Why notes get omitted

| Clash | Solution |
|---|---|
| the eleventh (F) sits a semitone from the third (E) | **often omit the third** (the chord then sounds close to a suspended fourth) |
| the ninth is a second above the octave of the root, muddy low down | **raise it an octave**, or drop the root and let the bass supply it |
| a thirteenth chord has seven notes, more than the ear can separate | **omit the fifth and the eleventh**, keeping root, third, seventh and thirteenth |

The fifth is dropped most often: it decides the least (the third sets brightness, the seventh sets tension, the
root fixes identity).

## A useful rule of thumb

> **Third for brightness, seventh for tension, ninth for colour — the fifth goes first.**

Do the subtraction in that order and you arrive at the "few notes, rich sound" voicings typical of jazz and pop.

## How it differs from an added-tone chord

| | Added tone | Extension |
|---|---|---|
| Example | Cadd9 = C–E–G–D | Cmaj9 = C–E–G–**B**–D |
| Seventh | **absent** | **present** |
| Sound | clean, open | thicker, more complex |

One practical conclusion again: **skipping the seventh skips a layer of instability** (see
[[concept:added-tone-chord|added-tone chord]]).

## Diagram: stack to six layers, then subtract

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Left: a thirteenth chord on paper. Right: what is usually played — four notes</text>
  </g>

  <g transform="translate(48,50)">
    <g font-family="Georgia,serif" font-size="11.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="22">E</text><text x="0" y="44">G</text>
      <text x="0" y="66">B</text><text x="0" y="88">D</text><text x="0" y="110">F</text><text x="0" y="132">A</text>
    </g>
    <g stroke="#6E6A64" stroke-width="1.2"><line x1="14" y1="0" x2="14" y2="132"/></g>
    <text x="-34" y="0" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="end">root</text>
    <text x="-34" y="44" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="end">fifth</text>
    <text x="-34" y="66" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="end">seventh</text>
    <text x="-34" y="110" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="end">eleventh</text>
    <text x="-34" y="132" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="end">thirteenth</text>

    <g transform="translate(250,14)">
      <g font-family="Georgia,serif" font-size="11.5" text-anchor="middle">
        <text x="0" y="0" fill="#F2EEE6">C</text><text x="0" y="30" fill="#5B7FA8">E</text>
        <text x="0" y="60" fill="#E8C547">B♭</text><text x="0" y="90" fill="#6E6A64">A</text>
      </g>
      <g stroke="#E8C547" stroke-width="1.2"><line x1="14" y1="0" x2="14" y2="90"/></g>
      <text x="30" y="30" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">third: brightness</text>
      <text x="30" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">seventh: tension</text>
      <text x="30" y="90" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">thirteenth: colour</text>
      <text x="30" y="116" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">fifth goes first; eleventh usually goes too</text>
    </g>
  </g>
</svg>
```

## Listen: extended chords

Hear the ninth chord, then the added-tone chord — the difference is whether that seventh layer is present.

```audiolab
{"type":"chord","root":"C4","quality":"dom9","inversion":0,"label":"属九和弦（C–E–G–B♭–D）","label_en":"Dominant ninth (C–E–G–B♭–D)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"More notes means a more advanced chord."** In practice extensions are played with **fewer** notes: high stacks demand subtraction, or the low register turns to mud.
- **"A ninth chord equals an added ninth."** The ninth chord contains a seventh; add9 does not (see the table above).
- **"Eleventh chords are unusable."** They are usable, but the eleventh sits a semitone from the third, so the third is usually omitted or the eleventh raised.
- **"A thirteenth chord has thirteen notes."** It has seven (root, third, fifth, seventh, ninth, eleventh, thirteenth), and after the usual omissions four remain.
:::
