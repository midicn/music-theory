---
id: added-tone-chord
site: theo
cat: T4
title: 加音和弦
title_en: Added-Tone Chord
summary: 在完整三和弦上再加一个音——不替换、不叠三度
summary_en: Add a note to an intact triad — without replacing anything and without stacking another third
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [加音和弦, add9, 加九和弦]
order: 36
links:
  - "[[concept:triad]]"
  - "[[concept:suspended-chord]]"
  - "[[concept:extended-chord]]"
  - "[[concept:major-triad]]"
  - "[[concept:consonance]]"
instances:
  - atepp-000195 | 德彪西《月光》：附加音与九度被当作持续色彩使用，是加音写法最早的成熟样本之一 | Debussy's Clair de lune — added tones and ninths used as sustained colour, one of the earliest mature uses of the device
  - giantmidi-006222 | 琶音练习可弹出加音和弦，用于听三和弦完整保留时多一个音的效果 | Scale exercises can sound added-tone chords, showing the effect of one extra note over an intact triad
  - cyberhymnal-000695 | 管风琴圣咏作对照：传统和声以三和弦为骨架，附加音很少出现 | An organ hymn as a control — traditional harmony keeps triads as the frame and rarely adds notes
sources:
  - 加音和弦 = 在完整三和弦上加入非三度叠置的音（如 add9 = 三和弦 + 九度），属和声学通则
  - 加音写法与"叠三度"的延伸和弦（九和弦）在构造上不同，为通行和声学表述
updated: 2026-09-24
---

::: zh
加音和弦的做法是：**在完整的三和弦上，额外加一个音**。

> Cadd9 = C–E–G–**D**（大三和弦完整保留，另加九度 D）

关键在"完整保留"：三和弦的骨架一点没动。这与 [[concept:suspended-chord|挂留和弦]]
（**替换**三音）和 [[concept:extended-chord|九和弦]]（**继续叠三度**）都不同。

## 三种"多一个音"的区别

| 做法 | 三和弦 | 新音 | 结果 |
|---|---|---|---|
| **挂留** | 三音被换掉 | 二度或四度 | 大小变得不明确 |
| **加音** | **完整保留** | 二度、六度、九度等 | 大小明确，额外多一层色彩 |
| **延伸（九和弦）** | 完整保留 + 加七音 | 九度（第四层三度） | 七音与九音同时在，张力更复杂 |

## 加音与叠三度的差别

**九和弦 = 五音（根三五四七九），加音和弦 = 四个音（根三五四九，跳过七音）。**

| 和弦 | 音（从 C 起） | 是否含七音 |
|---|---|---|
| Cadd9 | C–E–G–D | **不含** |
| Cmaj9 | C–E–G–B–D | 含 B |

这个差别很实用：**跳过七音，就避开了一个不稳定音**。
所以 add9 听起来比 maj9 **更干净、更开阔**，也更容易在流行音乐里当稳定和弦用。

## 为什么附加音不"刺耳"

附加音通常会与三音形成二度或九度的关系，本来应该冲突。但两种做法让它变得柔和：

1. **拉开音区**：把附加音放在高八度（D 与 C 相撞要隔开一个八度以上）；
2. **靠五度撑开**：三和弦的纯五度提供了稳定的框架，附加音被"架"在上面，不与三音直接冲突。

这也说明"协和"不只看音程，也看**排列**（见 [[concept:chord-voicing|和弦排列]]）。

## 图示：加音 vs 叠三度

```svg
<svg viewBox="0 0 640 190" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样多了一个音，一个跳过了七音，一个没有</text>
  </g>

  <g transform="translate(56,50)">
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="24">E</text><text x="0" y="48">G</text><text x="0" y="72">D</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2"><line x1="12" y1="0" x2="12" y2="72"/></g>
    <g stroke="#C0504A" stroke-width="1.2" stroke-dasharray="3 2">
      <line x1="34" y1="48" x2="34" y2="72"/>
    </g>
    <text x="44" y="64" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">此处跳过七音</text>
    <text x="0" y="100" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">Cadd9：四音，干净开阔</text>

    <g transform="translate(300,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="24">E</text><text x="0" y="48">G</text>
        <text x="0" y="72">B</text><text x="0" y="96">D</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.2"><line x1="12" y1="0" x2="12" y2="96"/></g>
      <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Cmaj9：五音，含七音</text>
      <text x="0" y="142" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">多了 B 这一层不稳定</text>
    </g>
  </g>
</svg>
```

## 听一听：加音和弦

先听 Cadd9（干净、开阔），再听 Cmaj9（多一层七音，色彩更厚）。差别就在于有没有那个七音。

```audiolab
{"type":"chord","root":"C4","quality":"add9","inversion":0,"label":"加九和弦（C–E–G–D）","label_en":"Added ninth (C–E–G–D)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## 常见误解

- **「add9 和 maj9 差不多」** → 后者含七音，前者不含。跳过七音让 add9 明显更干净。
- **「加音和弦必须解决」** → 它可以就是稳定和弦；附加音是色彩，不是张力。
- **「附加音会与三音撞车」** → 会，所以要靠排列拉开（通常放高八度），或由纯五度撑开支撑。
- **「加音就是挂留」** → 挂留是**替换**三音，加音是**保留**三音再添加。前者失去大小，后者保留。
:::

::: en
An added-tone chord does this: **keep the triad intact and add one more note.**

> Cadd9 = C–E–G–**D** (the major triad complete, plus a ninth, D)

The key word is "intact": nothing in the triad moves. That distinguishes it from the
[[concept:suspended-chord|suspended chord]] (which **replaces** the third) and from the
[[concept:extended-chord|ninth chord]] (which **keeps stacking thirds**).

## Three ways of "one more note"

| Method | Third | New note | Result |
|---|---|---|---|
| **suspension** | replaced | a second or fourth | major/minor becomes undefined |
| **added tone** | **kept** | a second, sixth or ninth | major/minor stays clear, with an extra layer of colour |
| **extension (ninth)** | kept, plus a seventh | a ninth (the fourth third) | seventh and ninth together, more complex tension |

## Added tone versus stacked third

**A ninth chord = five notes (root, third, fifth, seventh, ninth); an added-tone chord = four notes (root,
third, fifth, ninth, with the seventh skipped).**

| Chord | Notes from C | Contains the seventh? |
|---|---|---|
| Cadd9 | C–E–G–D | **no** |
| Cmaj9 | C–E–G–B–D | yes, B |

That difference is practical: **skip the seventh and you skip an unstable note.** So add9 sounds **cleaner and
more open** than maj9, and is easier to use as a stable chord in popular music.

## Why an added note does not bite

The added note usually forms a second or a ninth against the third, which ought to clash. Two things soften it:

1. **Separation by register** — put the added note an octave higher (D and C colliding need more than an
   octave between them);
2. **The fifth holds things apart** — the triad's perfect fifth frames the chord, so the added note sits
   overhead rather than colliding with the third.

Which shows that consonance depends not only on intervals but on **voicing** (see
[[concept:chord-voicing|chord voicing]]).

## Diagram: added tone versus stacked third

```svg
<svg viewBox="0 0 640 190" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Both add a note; one skips the seventh, the other does not</text>
  </g>

  <g transform="translate(56,50)">
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="0">C</text><text x="0" y="24">E</text><text x="0" y="48">G</text><text x="0" y="72">D</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.2"><line x1="12" y1="0" x2="12" y2="72"/></g>
    <g stroke="#C0504A" stroke-width="1.2" stroke-dasharray="3 2">
      <line x1="34" y1="48" x2="34" y2="72"/>
    </g>
    <text x="44" y="64" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">the seventh is skipped here</text>
    <text x="0" y="100" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">Cadd9: four notes, clean and open</text>

    <g transform="translate(300,0)">
      <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
        <text x="0" y="0">C</text><text x="0" y="24">E</text><text x="0" y="48">G</text>
        <text x="0" y="72">B</text><text x="0" y="96">D</text>
      </g>
      <g stroke="#E07A3F" stroke-width="1.2"><line x1="12" y1="0" x2="12" y2="96"/></g>
      <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Cmaj9: five notes, seventh included</text>
      <text x="0" y="142" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">the B adds a layer of instability</text>
    </g>
  </g>
</svg>
```

## Listen: the added-tone chord

Hear Cadd9 (clean, open), then Cmaj9 (a seventh heavier, thicker). The difference is whether the seventh is
there.

```audiolab
{"type":"chord","root":"C4","quality":"add9","inversion":0,"label":"加九和弦（C–E–G–D）","label_en":"Added ninth (C–E–G–D)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

## Common misconceptions

- **"add9 and maj9 are much the same."** The latter contains a seventh; the former does not. Skipping it makes add9 clearly cleaner.
- **"An added-tone chord must resolve."** It can be perfectly stable; the added note is colour, not tension.
- **"The added note will clash with the third."** It would, so voicing separates them (usually by an octave) or the fifth holds them apart.
- **"Added tone means suspended."** A suspension **replaces** the third; an added tone **keeps** it and adds another note. The first loses major and minor, the second retains them.
:::
