---
id: note-name
site: theo
cat: T1
title: 音名
title_en: Note Name
summary: 把连续的音高切成可命名的点，字母、唱名、律名各管一件事
summary_en: Cutting continuous pitch into nameable points — letters, solfège syllables and Chinese pitch names
level: standard
tags: [乐理, 记谱, 基础]
tags_en: [theory, notation, basics]
alias: [音名体系, CDEFGA, do-re-mi, 唱名, 十二律]
order: 30
links:
  - "[[concept:pitch]]"
  - "[[concept:octave]]"
  - "[[concept:semitone]]"
  - "[[concept:scale]]"
  - "[[concept:key-signature]]"
instances:
  - giantmidi-006222 | 音阶与琶音练习：逐音按音名顺序上行，是把名字和听感对上的最直接材料 | Scales and arpeggio exercises — step up in note-name order and link the names to what you hear
  - aria-011398 | 哈农钢琴练习：五指位置内固定的音名序列反复出现，适合一句一句对照 | A Hanon piano exercise — a fixed note-name sequence inside one hand position, easy to check phrase by phrase
  - mutopia-000046 | 圣咏曲调《Old 100th》：全曲只用调内七个音名，没有变化音 | The hymn tune "Old 100th" — only the seven note names of the key, with no accidentals
sources:
  - 字母音名、唱名体系、中国十二律名的名称与排列，属通行乐理与律学常识
  - 唱名法（首调 / 固定调）的区分依通行教学体系表述，本文行文为原创
updated: 2026-09-23
---

::: zh
音高是一条连续的坡，音名是在坡上打的桩。打桩的目的只有一个：**让不同的人能在不同的时间说同一个音**。
所以「音名」从来不是一套，而是三套并行的命名系统。

## 三套叫法各管什么

| 体系 | 用于 | 例子 | 特点 |
|---|---|---|---|
| 字母音名 | 记谱、乐器谱、国际交流 | C D E F G A B | 与调性无关，一个音永远一个名 |
| 唱名 | 视唱、教学、练耳 | do re mi fa sol la si | 可固定、可移动，随用法而变 |
| 中国律名 | 律学、传统乐学表述 | 黄钟、大吕、太簇、夹钟…… | 出自十二律体系，与律管长度相关 |

字母音名是国际通用的一套。唱名则分两种用法：**固定唱名法**把 do 永远钉在 C 上，
**首调唱名法**把 do 钉在当前调的主音上 —— 同一段旋律，用这两种方法唱，唱名会完全不同。

中国十二律名（黄钟、大吕、太簇、夹钟、姑洗、仲吕、蕤宾、林钟、夷则、南吕、无射、应钟）
是另一条脉络：它由律管的长度推算而来，起源与西方十二音体系不同。站内的
[[concept:pentatonic|五声音阶]]与 [[concept:scale|音阶]]条目会用到其中几个名称；
乐种与用法层面的内容不在本站范围。

## 半音藏在两对字母之间

七个字母里，只有两对相邻字母之间**天然**是半音：

```
C — D — E ⌒ F — G — A — B ⌒ C
      全音   半音   全音  全音   半音
```

E–F 与 B–C 之间没有黑键，它们本身就是半音。剩下的 C–D、D–E、F–G、G–A、A–B 各是一个全音。
记住这两处"缺口"，键盘上所有音的位置就都能推出来：**C–D–E 三个白键挤在一起，左边就是 E–F 这处缺口；
B–C 这处缺口在三个一组的左侧**。

## 图示：字母、唱名与键盘的对应

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">一组内的七个字母音名 · 黑键位置决定全音还是半音</text>
  </g>

  <g transform="translate(48,44)">
    <g stroke="#343439">
      <rect x="0" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="38" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="76" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="114" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="152" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="190" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="228" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="266" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="304" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="342" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="380" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="418" y="0" width="34" height="86" rx="2" fill="#17171A"/>
    </g>
    <g fill="#070706" stroke="#343439">
      <rect x="24" y="0" width="22" height="52" rx="2"/>
      <rect x="62" y="0" width="22" height="52" rx="2"/>
      <rect x="138" y="0" width="22" height="52" rx="2"/>
      <rect x="176" y="0" width="22" height="52" rx="2"/>
      <rect x="214" y="0" width="22" height="52" rx="2"/>
      <rect x="290" y="0" width="22" height="52" rx="2"/>
      <rect x="328" y="0" width="22" height="52" rx="2"/>
      <rect x="404" y="0" width="22" height="52" rx="2"/>
      <rect x="442" y="0" width="22" height="52" rx="2"/>
      <rect x="480" y="0" width="22" height="52" rx="2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="17" y="102">C</text><text x="55" y="102">D</text><text x="93" y="102">E</text>
      <text x="131" y="102">F</text><text x="169" y="102">G</text><text x="207" y="102">A</text>
      <text x="245" y="102">B</text><text x="283" y="102">C</text><text x="321" y="102">D</text>
      <text x="359" y="102">E</text><text x="397" y="102">F</text><text x="435" y="102">G</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64" text-anchor="middle">
      <text x="17" y="122">do</text><text x="55" y="122">re</text><text x="93" y="122">mi</text>
      <text x="131" y="122">fa</text><text x="169" y="122">sol</text><text x="207" y="122">la</text>
      <text x="245" y="122">si</text><text x="283" y="122">do</text><text x="321" y="122">re</text>
      <text x="359" y="122">mi</text><text x="397" y="122">fa</text><text x="435" y="122">sol</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="93" y1="126" x2="131" y2="126"/>
      <line x1="93" y1="122" x2="93" y2="130"/>
      <line x1="131" y1="122" x2="131" y2="130"/>
      <line x1="245" y1="126" x2="283" y2="126"/>
      <line x1="245" y1="122" x2="245" y2="130"/>
      <line x1="283" y1="122" x2="283" y2="130"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      <text x="96" y="146">mi–fa 是半音</text>
      <text x="248" y="146">si–do 是半音</text>
    </g>
  </g>
</svg>
```

## 听一听：音名与听感对上

按音名顺序走一遍，注意每个音名对应的是一个**固定的高度**，而唱名会随着调移动。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"C 大调音阶（do re mi fa sol la si do）","label_en":"C major scale (do re mi fa sol la si do)","hint":"第三到第四个音只差半音，比其余相邻音明显更近","hint_en":"The third-to-fourth step is only a semitone — noticeably closer than the rest","gap":0.4}
```

## 常见误解

- **「do re mi 就是 C D E」** → 只在 C 调里临时成立。首调唱名法下，F 大调的 do 是 F；固定唱名法下，F 大调的 do 仍是 C。
- **「音名有 12 个，所以有 12 个字母」** → 只有 7 个字母。12 个音高位置是用**变音记号**（升、降）在字母上造出来的，字母本身不增加。
- **「中国十二律就是十二平均律」** → 不是。十二律是有 12 个律名的体系，与"每个半音等距"不是同一件事。
- **「E–F 之间有个被省略的黑键」** → 不是省略。七个字母的音高关系本来就不是等距的，键盘只是照实画出来。
:::

::: en
Pitch is a continuous slope; note names are posts driven into it. The posts exist for one purpose:
**so that different people, at different times, can refer to the same pitch.** Which is why "note name"
is never one system but three running in parallel.

## What each system is for

| System | Used for | Example | Property |
|---|---|---|---|
| Letter names | Notation, instrumental parts, international exchange | C D E F G A B | Independent of key; one pitch, one name, always |
| Solfège syllables | Sight-singing, teaching, ear training | do re mi fa sol la si | Fixed or movable depending on the method |
| Chinese pitch names | Tuning theory, traditional music scholarship | Huangzhong, Dalü, Taicu, Jiazhong … | From the twelve-lü system, derived from pipe lengths |

Letter names are the international set. Solfège splits into two practices: **fixed do** nails do permanently
to C, while **movable do** nails do to the tonic of the current key. The same melody sung both ways produces
completely different syllables.

The Chinese twelve pitch names — Huangzhong, Dalü, Taicu, Jiazhong, Guxian, Zhonglü, Ruibin, Linzhong,
Yize, Nanlü, Wuyi, Yingzhong — are a separate lineage, derived from the lengths of pitch pipes rather than
from the Western twelve-tone system. A few of these names appear again in [[concept:pentatonic|pentatonic scale]]
and [[concept:scale|scale]]. Genre-level usage belongs to a different site.

## The semitones hide between two letter pairs

Among the seven letters, only two adjacent pairs are **naturally** a semitone apart:

```
C — D — E ⌒ F — G — A — B ⌒ C
    whole   half   whole  whole  half
```

There is no black key between E and F, or between B and C — those pairs are semitones in themselves.
The remaining steps, C–D, D–E, F–G, G–A and A–B, are whole tones. Remember these two gaps and every key
position follows: **the three-white-key cluster C–D–E has the E–F gap on its left; the B–C gap sits on the
left of the two-black-key group.**

## Diagram: letters, syllables and the keyboard

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The seven letter names within one group · black-key positions decide whole tone or semitone</text>
  </g>

  <g transform="translate(48,44)">
    <g stroke="#343439">
      <rect x="0" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="38" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="76" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="114" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="152" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="190" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="228" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="266" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="304" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="342" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="380" y="0" width="34" height="86" rx="2" fill="#17171A"/>
      <rect x="418" y="0" width="34" height="86" rx="2" fill="#17171A"/>
    </g>
    <g fill="#070706" stroke="#343439">
      <rect x="24" y="0" width="22" height="52" rx="2"/>
      <rect x="62" y="0" width="22" height="52" rx="2"/>
      <rect x="138" y="0" width="22" height="52" rx="2"/>
      <rect x="176" y="0" width="22" height="52" rx="2"/>
      <rect x="214" y="0" width="22" height="52" rx="2"/>
      <rect x="290" y="0" width="22" height="52" rx="2"/>
      <rect x="328" y="0" width="22" height="52" rx="2"/>
      <rect x="404" y="0" width="22" height="52" rx="2"/>
      <rect x="442" y="0" width="22" height="52" rx="2"/>
      <rect x="480" y="0" width="22" height="52" rx="2"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="17" y="102">C</text><text x="55" y="102">D</text><text x="93" y="102">E</text>
      <text x="131" y="102">F</text><text x="169" y="102">G</text><text x="207" y="102">A</text>
      <text x="245" y="102">B</text><text x="283" y="102">C</text><text x="321" y="102">D</text>
      <text x="359" y="102">E</text><text x="397" y="102">F</text><text x="435" y="102">G</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64" text-anchor="middle">
      <text x="17" y="122">do</text><text x="55" y="122">re</text><text x="93" y="122">mi</text>
      <text x="131" y="122">fa</text><text x="169" y="122">sol</text><text x="207" y="122">la</text>
      <text x="245" y="122">si</text><text x="283" y="122">do</text><text x="321" y="122">re</text>
      <text x="359" y="122">mi</text><text x="397" y="122">fa</text><text x="435" y="122">sol</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="93" y1="126" x2="131" y2="126"/>
      <line x1="93" y1="122" x2="93" y2="130"/>
      <line x1="131" y1="122" x2="131" y2="130"/>
      <line x1="245" y1="126" x2="283" y2="126"/>
      <line x1="245" y1="122" x2="245" y2="130"/>
      <line x1="283" y1="122" x2="283" y2="130"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      <text x="96" y="146">mi–fa is a semitone</text>
      <text x="248" y="146">si–do is a semitone</text>
    </g>
  </g>
</svg>
```

## Listen: matching names to what you hear

Walk up in note-name order. Each name corresponds to a **fixed height**, while solfège syllables move with
the key.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"C 大调音阶（do re mi fa sol la si do）","label_en":"C major scale (do re mi fa sol la si do)","hint":"第三到第四个音只差半音，比其余相邻音明显更近","hint_en":"The third-to-fourth step is only a semitone — noticeably closer than the rest","gap":0.4}
```

## Common misconceptions

- **"do re mi just means C D E."** Only inside C major, and only temporarily. In movable do, F major starts on do = F; in fixed do, F major still has do = C.
- **"Twelve pitches, so twelve letters."** There are only seven letters. The twelve pitch positions are built on those letters with **accidentals** (sharps and flats); the alphabet itself never grows.
- **"The Chinese twelve-lü are equal temperament."** They are not. Twelve-lü is a system of twelve named pitches, which is a different claim from "every semitone is equal."
- **"A black key was left out between E and F."** Nothing was left out. The seven letters were never evenly spaced; the keyboard simply draws that honestly.
:::
