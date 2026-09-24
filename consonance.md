---
id: consonance
site: theo
cat: T2
title: 协和与不协和
title_en: Consonance and Dissonance
summary: 协和分层次，不协和是推动力——这套分层撑起了整个和声学
summary_en: Consonance comes in degrees, and dissonance is what drives music forward — harmony rests on this ladder
level: core
tags: [乐理, 音程, 和声]
tags_en: [theory, interval, harmony]
alias: [协和音程, 不协和音程, consonance]
order: 26
links:
  - "[[concept:interval]]"
  - "[[concept:perfect-interval]]"
  - "[[concept:harmonic-series]]"
  - "[[concept:cadence]]"
  - "[[concept:modulation]]"
  - "[[concept:augmented-diminished]]"
instances:
  - atepp-000195 | 德彪西《月光》：七和弦与九和弦被当作色彩持续铺陈，不协和不再急着解决 | Debussy's Clair de lune — sevenths and ninths used as continuous colour, dissonance no longer hurrying to resolve
  - cyberhymnal-000695 | 管风琴圣咏：传统写法里不协和音按规矩解决到协和音，是"张力—解决"最清楚的样子 | An organ hymn — in traditional writing dissonances resolve by rule, the clearest picture of tension and release
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：增四度密集出现，整曲靠不协和维持不安定的势头 | Liszt's transcription of Danse macabre — tritones crowd the texture and dissonance keeps the whole piece restless
sources:
  - 协和分层次（完全协和 / 不完全协和 / 不协和）及与泛音重合度的对应关系，属音乐声学与和声学通则
  - 协和判断随时代与语境变化（如三度从不协和转为协和），为音乐史通行记载
updated: 2026-09-23
---

::: zh
听觉上，音程分成协和与不协和两类。但真正有用的说法不是"两类"，而是**一条分层的楼梯**：

| 层次 | 音程 | 听感 | 在和声里的角色 |
|---|---|---|---|
| 完全协和 | 纯一、纯八、纯五、纯四 | 融合、空、无张力 | 骨架：用来确立调性 |
| 不完全协和 | 大/小三度、大/小六度 | 有色彩，但稳定 | 血肉：决定明暗 |
| 不协和 | 大/小二度、大/小七度、增四减五 | 需要解决、有推动力 | 动力：让音乐往前走 |

注意最上一层的"完全协和"基本都属于 [[concept:perfect-interval|纯音程]]——
这不是巧合，因为协和度由**泛音重合量**决定：比例越简单，重合越多，听起来越"空"。
详见 [[concept:harmonic-series|泛音列]]。

## 不协和不是"难听"

不协和是音乐的动力来源。没有它，音乐只能原地站立：

- **张力—解决**：不协和音出现 → 期待积累 → 解决到协和音 → 释放。这一套是 [[concept:cadence|终止式]] 与整座调性体系的运作方式。
- **推动转调**：把不协和音重新解释成新调里的音，调性就转移了，见 [[concept:modulation|转调]]。
- **当作色彩**：到了近现代，作曲家开始把不协和当成稳定的颜色本身用，而不是必须解决的东西。

## 协和与不协和是历史性的判断

分界线不是固定的。三度在早期曾被归入不协和，后来成为最简单的和声材料；
今天流行音乐里，七和弦已经近似"协和"。同一组音程在不同语境里的地位不同，
所以这条楼梯要当作**倾向**来用，而不是当作法律条文。

## 图示：协和度的分层

```svg
<svg viewBox="0 0 640 232" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">台阶越高 = 越需要用"解决"来收尾 · 台阶越低 = 越能自己站住</text>
  </g>

  <g transform="translate(40,52)">
    <g>
      <rect x="0" y="120" width="150" height="52" rx="3" fill="#5B7FA8" opacity=".85"/>
      <text x="14" y="142" font-family="system-ui,sans-serif" font-size="12" fill="#F2EEE6">完全协和</text>
      <text x="14" y="160" font-family="system-ui,sans-serif" font-size="11" fill="#0B0B0C">纯一/八/五/四 · 无张力</text>

      <rect x="164" y="86" width="150" height="86" rx="3" fill="#E8C547" opacity=".85"/>
      <text x="178" y="108" font-family="system-ui,sans-serif" font-size="12" fill="#1A1508">不完全协和</text>
      <text x="178" y="126" font-family="system-ui,sans-serif" font-size="11" fill="#3A2F10">大小三度 · 大小六度</text>
      <text x="178" y="144" font-family="system-ui,sans-serif" font-size="11" fill="#3A2F10">有色彩，可独立使用</text>

      <rect x="328" y="34" width="150" height="138" rx="3" fill="#E07A3F" opacity=".85"/>
      <text x="342" y="56" font-family="system-ui,sans-serif" font-size="12" fill="#1A0E06">不协和</text>
      <text x="342" y="74" font-family="system-ui,sans-serif" font-size="11" fill="#2A1408">大小二度 · 大小七度</text>
      <text x="342" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#2A1408">增四减五</text>
      <text x="342" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#2A1408">需要解决；</text>
      <text x="342" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#2A1408">也可以当色彩用</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="196">← 泛音重合越多，越能自己站住</text>
      <text x="486" y="20" text-anchor="end">泛音重合越少，越需要解决 →</text>
    </g>
  </g>
</svg>
```

## 听一听：协和与不协和的对照

先听纯净五度（完全协和），再听大七度（不协和），最后听增四度（最有名的刺）。
三者的差别不在音量，而在"是否期待下一件事发生"。

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"纯五度：完全协和","label_en":"Perfect fifth — perfect consonance","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 B4 就是大七度（不协和）：同样两个音，却明显悬着。","hint2_en":"Set b to B4 for a major seventh: same two notes, but unmistakably suspended."}
```

## 常见误解

- **「协和就是好听，不协和就是难听」** → 这是功能分类，不是审美评价。不协和是推动力，缺了它音乐无法前进。
- **「协和与不协和是固定不变的规则」** → 分界线随时代移动。三度从"不协和"变成了最基本的和声材料。
- **「不协和音必须立刻解决」** → 传统写法里通常如此，但印象派与爵士里，不协和可以长时间停留甚至作为终点。
- **「协和度只由音程决定」** → 也受音区、力度、配器影响。低音区的完全协和反而容易糊成一团。
:::

::: en
To the ear, intervals fall into consonant and dissonant. The useful picture, though, is not two boxes but
**a ladder of degrees**:

| Tier | Intervals | Sound | Role in harmony |
|---|---|---|---|
| perfect consonance | unison, octave, fifth, fourth | fused, hollow, no tension | skeleton: it establishes the key |
| imperfect consonance | major/minor thirds and sixths | coloured but stable | flesh: it decides brightness and shade |
| dissonance | major/minor seconds and sevenths, tritone | wants to resolve, drives forward | engine: it makes music move |

Notice that the top tier consists almost entirely of [[concept:perfect-interval|perfect intervals]] — no
coincidence, because consonance follows **how much the harmonic series overlaps**: simpler ratios overlap more,
and sound emptier. See [[concept:harmonic-series|harmonic series]].

## Dissonance is not "ugly"

Dissonance is where musical motion comes from. Without it, music could only stand still:

- **Tension and release**: a dissonance appears, expectation builds, it resolves to a consonance, the tension
  discharges. This is how [[concept:cadence|cadences]] and the whole tonal system work.
- **Modulation**: reinterpret a dissonance as belonging to a new key and the key has shifted — see
  [[concept:modulation|modulation]].
- **Colour**: from the late nineteenth century onward composers began using dissonance as a stable colour in
  itself rather than something that must resolve.

## The line is historical

The boundary is not fixed. Thirds were once classed as dissonant and later became the simplest harmonic
material; in today's popular music a seventh chord is nearly consonant. The same intervals hold different
positions in different contexts, so treat this ladder as a **tendency**, not as a statute.

## Diagram: the ladder of consonance

```svg
<svg viewBox="0 0 640 232" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Higher step = more in need of resolution · lower step = stands on its own</text>
  </g>

  <g transform="translate(40,52)">
    <g>
      <rect x="0" y="120" width="150" height="52" rx="3" fill="#5B7FA8" opacity=".85"/>
      <text x="14" y="142" font-family="system-ui,sans-serif" font-size="12" fill="#F2EEE6">perfect consonance</text>
      <text x="14" y="160" font-family="system-ui,sans-serif" font-size="11" fill="#0B0B0C">unison/octave/fifth/fourth</text>

      <rect x="164" y="86" width="150" height="86" rx="3" fill="#E8C547" opacity=".85"/>
      <text x="178" y="108" font-family="system-ui,sans-serif" font-size="12" fill="#1A1508">imperfect consonance</text>
      <text x="178" y="126" font-family="system-ui,sans-serif" font-size="11" fill="#3A2F10">major/minor thirds and sixths</text>
      <text x="178" y="144" font-family="system-ui,sans-serif" font-size="11" fill="#3A2F10">coloured, usable on its own</text>

      <rect x="328" y="34" width="150" height="138" rx="3" fill="#E07A3F" opacity=".85"/>
      <text x="342" y="56" font-family="system-ui,sans-serif" font-size="12" fill="#1A0E06">dissonance</text>
      <text x="342" y="74" font-family="system-ui,sans-serif" font-size="11" fill="#2A1408">major/minor seconds and sevenths</text>
      <text x="342" y="92" font-family="system-ui,sans-serif" font-size="11" fill="#2A1408">tritone</text>
      <text x="342" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#2A1408">wants resolution;</text>
      <text x="342" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#2A1408">also usable as colour</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="196">← more shared partials, stands on its own</text>
      <text x="486" y="20" text-anchor="end">fewer shared partials, needs resolving →</text>
    </g>
  </g>
</svg>
```

## Listen: consonance against dissonance

Hear a hollow fifth (perfect consonance), then a major seventh (dissonance), then the tritone. The difference
is not loudness; it is whether you expect something to happen next.

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"纯五度：完全协和","label_en":"Perfect fifth — perfect consonance","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 B4 就是大七度（不协和）：同样两个音，却明显悬着。","hint2_en":"Set b to B4 for a major seventh: same two notes, but unmistakably suspended."}
```

## Common misconceptions

- **"Consonant means pleasant, dissonant means unpleasant."** This is a functional classification, not an aesthetic verdict. Dissonance is the engine; without it music cannot move.
- **"The boundary is a fixed rule."** It moves with history. The third travelled from dissonance to the most basic harmonic material.
- **"A dissonance must resolve at once."** Usually true in traditional writing, but in Impressionism and jazz a dissonance can linger or even serve as an endpoint.
- **"Consonance depends only on the interval."** Register, dynamics and orchestration all matter — a perfect consonance in the low register can easily turn to mud.
:::
