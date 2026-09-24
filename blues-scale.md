---
id: blues-scale
site: theo
cat: T3
title: 蓝调音阶
title_en: Blues Scale
summary: 小调五声加一个降五度——一个音把它从柔变冲
summary_en: Minor pentatonic plus a lowered fifth — one note that turns smooth into gritty
level: standard
tags: [乐理, 音阶, 五声]
tags_en: [theory, scale, pentatonic]
alias: [蓝调音阶, 布鲁斯音阶, blues scale]
order: 42
links:
  - "[[concept:pentatonic]]"
  - "[[concept:chromatic]]"
  - "[[concept:consonance]]"
  - "[[concept:augmented-diminished]]"
instances:
  - abcmisc-000701 | 曲名带 Blues 的民间材料，可直接听蓝调音阶在旋律里的实际走法 | Folk material titled Blues — hear how the scale actually moves in a melody
  - giantmidi-003471 | 同样以布鲁斯为题，编制与上一条不同，可对照同一音阶在钢琴上的处理 | Also titled for the blues, on a different instrument — the same scale handled on piano
  - giantmidi-004403 | 布鲁斯语境下的长篇幅作品，可听降五度这一音在长时间里被反复强调的效果 | A longer work in a blues idiom — hear that lowered fifth being stressed over a whole piece
sources:
  - 蓝调音阶 = 小调五声音阶加降五度音（"蓝调音"），属通行乐理与流行音乐教材表述
  - 蓝调音在演唱与演奏中常做微分音滑移，为民族音乐学与爵士研究通行表述
updated: 2026-09-23
---

::: zh
蓝调音阶的定义短到一句话：**小调五声音阶，再加一个降五度**。

> 小调五声（C）：C E♭ F G B♭
> 蓝调音阶（C）：C E♭ F **G♭** G B♭

加进来的 **G♭（降五度）** 就是"蓝调音"。它的作用方式很特别：
它**不是一条稳定的音阶音**，而是一个**经过性的、需要滑进去滑出来的音**。
演奏者通常在 G♭ 与 G 之间来回滑动，或让它在长音上"弯"一下 ——
这种微小的音高游移，正是蓝调味道的核心，也是它无法用十二平均律完全记下来的原因。

## 结构上的三个要点

| 要点 | 说明 |
|---|---|
| **它是六声的** | 虽然叫"五声 + 一个音"，实际是六个音；谱面上常写成五声加一个变化音 |
| **降五度与纯五度并存** | G♭ 与 G 同时在音阶里，二者构成**减五度/增四度**的关系（见 [[concept:augmented-diminished|增程与减程]]） |
| **它天然带张力** | 降五度是全音阶里最不安定的音之一，这正是蓝调"粗粝"的来源（见 [[concept:consonance|协和与不协和]]） |

## 大调蓝调

还有一条常被并列的形态：**大调蓝调音阶** —— 大调五声加**降三度**。
它保留了小调蓝调的"蓝调音"逻辑（把一个音降下来造成冲突），但底色是大的，
听起来更接近欢快与顽皮的混合。

## 图示：五声 + 一个音

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">插进去的降五度与原有纯五度并存 —— 这一对冲突就是蓝调音</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">E♭</text><text x="160" y="0">F</text>
      <text x="240" y="0">G</text><text x="320" y="0">B♭</text><text x="400" y="0">C</text>
    </g>
    <text x="412" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">小调五声</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="52">C</text><text x="80" y="52">E♭</text><text x="160" y="52">F</text>
      <text x="200" y="52">G♭</text><text x="280" y="52">G</text><text x="360" y="52">B♭</text>
      <text x="440" y="52">C</text>
    </g>
    <text x="452" y="56" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">蓝调音阶</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="200" y1="38" x2="200" y2="6"/>
      <line x1="194" y1="38" x2="206" y2="38"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.2">
      <line x1="200" y1="70" x2="280" y2="70"/>
      <line x1="200" y1="66" x2="200" y2="74"/><line x1="280" y1="66" x2="280" y2="74"/>
    </g>
    <text x="288" y="74" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      减五度（G♭–G 之间只隔一个半音，实为等音程关系）
    </text>
    <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      演奏方式：在 G♭ 与 G 之间滑移，或把 G♭ 唱得比谱面略低 —— 这种游移无法被十二平均律完全记下
    </text>
  </g>
</svg>
```

## 听一听：降五度加入前后

先听小调五声（圆润、稳定），再听蓝调音阶 —— 加入的那个音立刻让色彩变得粗糙。

```audiolab
{"type":"scale","notes":["C4","Eb4","F4","Gb4","G4","Bb4","C5"],"label":"C 蓝调音阶","label_en":"C blues scale","hint":"点「上行」留意第 4–5 音之间那个降五度","hint_en":"Try Up — the lowered fifth sits between the fourth and fifth","gap":0.36}
```

## 常见误解

- **「蓝调音阶是七声的」** → 六声（五声 + 降五度）。它的"第五个音"与"降五度"是两个不同音。
- **「降五度就是走音」** → 它是音阶内的固定成员，只是常被处理成滑移，所以听感上游移。
- **「蓝调音阶只能即兴用」** → 它同样是大量旋律写作的素材，也被写进成文作品。
- **「蓝调音阶=小调五声」** → 差一个音，但那一个音承载了全部"蓝调味"。
:::

::: en
The blues scale can be defined in one line: **the minor pentatonic, plus a lowered fifth.**

> minor pentatonic (C): C E♭ F G B♭
> blues scale (C): C E♭ F **G♭** G B♭

The added **G♭ (the lowered fifth)** is the "blue note", and it behaves in a special way: it is **not a stable
scale degree** but a passing note that has to be slid into and out of. Players move back and forth between G♭
and G, or bend it on a long note. That small pitch instability is the heart of the blues sound — and the reason
it cannot be fully written down in equal temperament.

## Three structural points

| Point | Explanation |
|---|---|
| **It has six notes** | "Pentatonic plus one" adds up to six; notation usually writes five plus an accidental |
| **Lowered and perfect fifth coexist** | G♭ and G both belong, standing to each other as a **diminished fifth / augmented fourth** (see [[concept:augmented-diminished|augmented and diminished]]) |
| **It carries built-in tension** | The lowered fifth is one of the least settled notes available, which is exactly where the gritty blues colour comes from (see [[concept:consonance|consonance and dissonance]]) |

## The major blues scale

A companion form is often mentioned alongside: the **major blues scale** — the major pentatonic plus a
**lowered third**. It keeps the same logic (lower one note to create a clash) but on a major base, which reads
as a mix of cheerful and mischievous.

## Diagram: five notes plus one

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The inserted lowered fifth sits alongside the perfect fifth — that clash is the blue note</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">E♭</text><text x="160" y="0">F</text>
      <text x="240" y="0">G</text><text x="320" y="0">B♭</text><text x="400" y="0">C</text>
    </g>
    <text x="412" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">minor pentatonic</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="52">C</text><text x="80" y="52">E♭</text><text x="160" y="52">F</text>
      <text x="200" y="52">G♭</text><text x="280" y="52">G</text><text x="360" y="52">B♭</text>
      <text x="440" y="52">C</text>
    </g>
    <text x="452" y="56" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">blues scale</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="200" y1="38" x2="200" y2="6"/>
      <line x1="194" y1="38" x2="206" y2="38"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.2">
      <line x1="200" y1="70" x2="280" y2="70"/>
      <line x1="200" y1="66" x2="200" y2="74"/><line x1="280" y1="66" x2="280" y2="74"/>
    </g>
    <text x="288" y="74" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      G♭ to G is only a semitone — the two fifths compete
    </text>
    <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Performance: slide between G♭ and G, or sing G♭ slightly flat — that drift cannot be fully notated
    </text>
  </g>
</svg>
```

## Listen: before and after the lowered fifth

Hear the minor pentatonic (round, stable), then the blues scale. The added note roughens the colour at once.

```audiolab
{"type":"scale","notes":["C4","Eb4","F4","Gb4","G4","Bb4","C5"],"label":"C 蓝调音阶","label_en":"C blues scale","hint":"点「上行」留意第 4–5 音之间那个降五度","hint_en":"Try Up — the lowered fifth sits between the fourth and fifth","gap":0.36}
```

## Common misconceptions

- **"The blues scale has seven notes."** It has six (pentatonic plus a lowered fifth). Its "fifth note" and its "lowered fifth" are two different pitches.
- **"A lowered fifth is out of tune."** It is a fixed member of the scale, just usually handled as a slide, which is why it sounds unstable.
- **"The blues scale is only for improvising."** It is equally a source for composed melodies and appears in written works.
- **"Blues scale means minor pentatonic."** One note differs — and that note carries the entire blues flavour.
:::
