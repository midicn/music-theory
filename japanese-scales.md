---
id: japanese-scales
site: theo
cat: T3
title: 日本音阶
title_en: Japanese Scales
summary: 五声但含半音——都节与琉球，靠半音位置造出独特色彩
summary_en: Pentatonic but with semitones — insen and ryukyu build their colour from where the semitones fall
level: standard
tags: [乐理, 音阶, 五声]
tags_en: [theory, scale, pentatonic]
alias: [都节音阶, 琉球音阶, 日本音阶]
order: 50
links:
  - "[[concept:pentatonic]]"
  - "[[concept:chinese-pentatonic]]"
  - "[[concept:semitone]]"
  - "[[concept:scale]]"
instances:
  - giantmidi-006222 | 音阶练习可按需弹出五声音阶，用于与都节、琉球的半音位置做对照 | Scale exercises play pentatonic scales, useful for comparing where the semitones fall in insen and ryukyu
  - mutopia-000522 | 七声材料作对照：把这五个音抽出来、调整半音位置，就能得到日本五声 | Seven-note material as a control — pull five notes out and move the semitones to build the Japanese forms
  - thesession-019704 | 另一条五声材料，用于听"同样的五个音、半音位置不同则色彩全变" | A further pentatonic item, for hearing how the same five-note pool turns into a different colour when the semitones move
sources:
  - 都节音阶（insk/insen）与琉球音阶的五音构成与半音位置，属日本传统音乐理论的通行表述
  - 日本音阶与雅乐、俗乐诸种调式的区别属专门领域，本站只讲最常被引用的两条五声形态
updated: 2026-09-23
---

::: zh
日本音乐里最常被音乐理论教材引用的两条五声音阶，特点都是**含半音**——
这与 [[concept:chinese-pentatonic|中国五声]]（无半音）形成鲜明对照。

## 两条五声形态

| 名称 | 音（以 C 起为例） | 半音位置 |
|---|---|---|
| **都节音阶**（insen） | C D♭ F G A♭ | 第 1–2 音、第 3–4 音之间 |
| **琉球音阶** | C E F G B | 第 2–3 音之间 |

对照点很清楚：

- **都节**在**开头**就有半音（C–D♭）→ 立刻带出阴郁、紧缩的色彩；
- **琉球**的半音在中段（E–F）→ 色彩更开阔，常用于冲绳民谣。

同样是五个音、同样没有三全音，**只因半音落在不同位置，色彩就完全不同** ——
这正是 [[concept:semitone|半音与全音]] 那一节说的"音阶的性格写在哪里"的实例。

## 和中国五声的关系

| | 中国五声 | 都节 | 琉球 |
|---|---|---|---|
| 音数 | 5 | 5 | 5 |
| 半音 | 无 | 有（两处） | 有（一处） |
| 音程骨架 | 全音 + 小三度 | 半音 + 大三度 | 半音 + 大三度 |

最要紧的一点：**"五声"只说明音的数量，不说明色彩。** 半音在哪里，才是决定性的。

> **取材说明**：本站实例池里没有标记为日本音阶的曲目，本条改用**可听可验证的推导法** ——
> 用库内五声/七声材料，把半音位置移到位，对比听辨。这一做法与 [[concept:locrian|洛克里亚]] 一致。

## 图示：同样的五个音，半音换位置

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">半音落在开头（都节）与落在中段（琉球）——色彩完全不同</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">D♭</text><text x="160" y="0">F</text>
      <text x="240" y="0">G</text><text x="320" y="0">A♭</text><text x="400" y="0">C</text>
    </g>
    <text x="412" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">都节音阶</text>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="16" x2="80" y2="16"/>
      <line x1="0" y1="12" x2="0" y2="20"/><line x1="80" y1="12" x2="80" y2="20"/>
    </g>
    <text x="88" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">开头就撞半音</text>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="62">C</text><text x="80" y="62">E</text><text x="160" y="62">F</text>
      <text x="240" y="62">G</text><text x="320" y="62">B</text><text x="400" y="62">C</text>
    </g>
    <text x="412" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">琉球音阶</text>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="80" y1="78" x2="160" y2="78"/>
      <line x1="80" y1="74" x2="80" y2="82"/><line x1="160" y1="74" x2="160" y2="82"/>
    </g>
    <text x="168" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">半音在中段</text>
    <text x="0" y="112" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      对照：中国五声没有半音 —— 因此"五声"这个说法本身不决定色彩
    </text>
  </g>
</svg>
```

## 听一听：半音位置决定色彩

先听都节的半音关系（C–C♯ 紧贴），再听琉球的（E–F）。同样的五个音，色彩完全不同。

```audiolab
{"type":"interval","a":"C4","b":"C#4","label":"都节的核心：开头的半音","label_en":"The core of insen — a semitone at the start","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把两个音换成 E4–F4，就是琉球的半音位置 —— 同一个半音，落在中段时听感更开阔。","hint2_en":"Set them to E4–F4 for ryukyu's semitone — the same interval, further along, sounds more open."}
```

## 常见误解

- **「五声音阶都一样」** → 数量相同不等于结构相同。半音的有无与位置才是决定性的。
- **「日本音阶只有两条」** → 那是最常被引用的两条。雅乐与俗乐中的调式体系要复杂得多，属专门领域。
- **「都节听起来就是"日本味"」** → 那种听感来自半音位置与旋法习惯，不来自"日本"这个概念本身。
- **「它们属于中国五声的分支」** → 音数相同但结构不同（中国五声无半音），是各自独立发展的体系。
:::

::: en
Two pentatonic scales from Japanese music are quoted most often in theory teaching, and both contain
**semitones** — a sharp contrast with the semitone-free [[concept:chinese-pentatonic|Chinese pentatonic]].

## The two forms

| Name | Notes (starting on C) | Semitones |
|---|---|---|
| **insen** | C D♭ F G A♭ | between steps 1–2 and 3–4 |
| **ryukyu** | C E F G B | between steps 2–3 |

The comparison is clear:

- **insen** has a semitone at the **start** (C–D♭), which immediately produces a dark, constricted colour;
- **ryukyu** puts its semitone **mid-scale** (E–F), which reads as more open and is common in Okinawan song.

Same five notes, no tritone in either — **only the position of the semitones differs, and the colour is
completely different**. This is precisely the "a scale's character is written where the semitones land" point
from [[concept:semitone|semitones and whole tones]].

## How they relate to the Chinese pentatonic

| | Chinese pentatonic | insen | ryukyu |
|---|---|---|---|
| Notes | 5 | 5 | 5 |
| Semitones | none | two | one |
| Skeleton | whole tones + minor thirds | semitones + major thirds | semitones + major thirds |

The essential point: **"pentatonic" only states how many notes there are, not what colour they make.** Where
the semitones sit decides everything.

> **Sourcing note**: this library holds no material labelled as a Japanese scale, so this entry uses an
> **audible, verifiable derivation** — pentatonic and seven-note material from the library, with the semitones
> moved into place for comparison. The same approach is used for [[concept:locrian|Locrian]].

## Diagram: the same five notes, the semitone relocated

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">A semitone at the start (insen) versus mid-scale (ryukyu) — entirely different colours</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">D♭</text><text x="160" y="0">F</text>
      <text x="240" y="0">G</text><text x="320" y="0">A♭</text><text x="400" y="0">C</text>
    </g>
    <text x="412" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">insen</text>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="16" x2="80" y2="16"/>
      <line x1="0" y1="12" x2="0" y2="20"/><line x1="80" y1="12" x2="80" y2="20"/>
    </g>
    <text x="88" y="20" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">a semitone at the outset</text>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="62">C</text><text x="80" y="62">E</text><text x="160" y="62">F</text>
      <text x="240" y="62">G</text><text x="320" y="62">B</text><text x="400" y="62">C</text>
    </g>
    <text x="412" y="66" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">ryukyu</text>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="80" y1="78" x2="160" y2="78"/>
      <line x1="80" y1="74" x2="80" y2="82"/><line x1="160" y1="74" x2="160" y2="82"/>
    </g>
    <text x="168" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">a semitone in the middle</text>
    <text x="0" y="112" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Contrast: the Chinese pentatonic has no semitone — so "pentatonic" alone decides nothing
    </text>
  </g>
</svg>
```

## Listen: the semitone's position decides the colour

Hear the insen semitone (C–C♯, tight) and then ryukyu's (E–F). Same five notes, entirely different colour.

```audiolab
{"type":"interval","a":"C4","b":"C#4","label":"都节的核心：开头的半音","label_en":"The core of insen — a semitone at the start","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把两个音换成 E4–F4，就是琉球的半音位置 —— 同一个半音，落在中段时听感更开阔。","hint2_en":"Set them to E4–F4 for ryukyu's semitone — the same interval, further along, sounds more open."}
```

## Common misconceptions

- **"All pentatonic scales are alike."** The same count is not the same structure; whether semitones exist and where they sit decides everything.
- **"Japanese music has only two scales."** These are the two most quoted. The modal systems of gagaku and folk practice are far richer and belong to specialist study.
- **"Insen simply sounds Japanese."** That impression comes from the semitone placement and melodic habit, not from the label.
- **"They are branches of the Chinese pentatonic."** The note count matches but the structure differs (no semitones in the Chinese form); they are separately developed systems.
:::
