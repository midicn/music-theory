---
id: harmonic-minor
site: theo
cat: T3
title: 和声小调
title_en: Harmonic Minor Scale
summary: 自然小调升第七级——只为把导音找回来，代价是增二度
summary_en: Natural minor with a raised seventh — restoring the leading tone at the price of an augmented second
level: standard
tags: [乐理, 音阶, 小调]
tags_en: [theory, scale, minor]
alias: [和声小调, harmonic minor]
order: 36
links:
  - "[[concept:minor-scale]]"
  - "[[concept:melodic-minor]]"
  - "[[concept:augmented-diminished]]"
  - "[[concept:cadence]]"
  - "[[concept:triad]]"
instances:
  - giantmidi-006222 | 音阶练习可按需弹出和声小调，是把第 6–7 级之间那个增二度听清楚的最直接方式 | Scale exercises play the harmonic minor directly — the clearest way to hear the augmented second between steps 6 and 7
  - atepp-000318 | a 小调奏鸣曲：属和弦里出现的升七级音正是和声小调升上去的那一个 | A sonata in A minor — the raised seventh appearing in dominant harmony is exactly the note harmonic minor raises
  - atepp-001114 | g 小调叙事曲：小调作品里属—主关系之所以能成立，靠的就是这一处升高 | A ballade in G minor — the dominant-to-tonic relation in minor keys depends on that one raised degree
sources:
  - 和声小调 = 自然小调升第 7 级；升 7 级用于属功能，属乐理通则
  - 由此产生的第 6–7 级增二度是小调写作的常见技术问题，为通行和声学表述
updated: 2026-09-23
---

::: zh
和声小调是一次**功能性的修补**：自然小调的属和弦是小三和弦，没有导音，
"属 → 主"的引力太弱，和声因此立不住。补法很简单 —— **把第 7 级升上去**。

> 自然小调（C）：C D E♭ F G A♭ **B♭**
> 和声小调（C）：C D E♭ F G A♭ **B**  ← 只动这一个音

升起的第 7 级就是**导音**：它与主音只隔半音，属和弦随之变成**大**三和弦，
"属→主"的推进力立刻回来了。这是小调作品里最常见的一处变化音 ——
你在一首 a 小调曲子里听到 G♯，来源就在这里。

## 代价：一个增二度

改动带来一个副作用：第 6 级与第 7 级之间原来是全音，现在变成了**增二度**（A♭–B，三个半音）。
这个音程在听觉上接近小三度，很难唱准，在旋律里也显得"异域"。
于是产生了 [[concept:melodic-minor|旋律小调]] 这一层再修补 —— 上行时把第 6 级也升上去。

## 结构

| 级数 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| 相对自然小调 | 同 | 同 | 同 | 同 | 同 | 同 | **升** |
| 相对大调 | 同 | 同 | **降** | 同 | 同 | **降** | 同 |

## 图示：升一处，回来一处，又丢掉一处

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">第 7 级升上去（找回导音），第 6–7 级之间却多出一个增二度</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">自然小调</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="56">C</text><text x="64" y="56">D</text><text x="128" y="56">E♭</text>
      <text x="192" y="56">F</text><text x="256" y="56">G</text><text x="320" y="56">A♭</text>
      <text x="384" y="56">B</text><text x="448" y="56">C</text>
    </g>
    <text x="458" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">和声小调</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="384" y1="42" x2="384" y2="6"/>
      <line x1="378" y1="42" x2="390" y2="42"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="320" y1="76" x2="384" y2="76"/>
      <line x1="320" y1="72" x2="320" y2="80"/><line x1="384" y1="72" x2="384" y2="80"/>
    </g>
    <text x="392" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">增二度（A♭–B，三个半音）</text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      和声上的收益：属和弦从小三和弦变成大三和弦，导音回来了 → 属—主关系成立
    </text>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      旋律上的代价：第 6–7 级难唱，故有了旋律小调的上行补法
    </text>
  </g>
</svg>
```

## 听一听：增二度

先听整条和声小调，重点在第 6 到第 7 音 —— 那一步比别的步子宽，正是"异域感"的来源。

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","Ab4","B4","C5"],"label":"C 和声小调","label_en":"C harmonic minor","hint":"点「上行」听第 6–7 音之间那一步","hint_en":"Try Up and listen to the step between the 6th and 7th","gap":0.38}
```

## 常见误解

- **「和声小调是一条独立的音阶」** → 它是自然小调为**和声需要**做的一次调整，常用于属和弦与终止式，不一定贯穿全曲。
- **「临时的升号是写错了」** → 小调作品里升第 7 级是最常规的变化音，来自和声小调。
- **「增二度听起来像小三度，是不是一回事」** → 听感接近，记谱与功能完全不同：增二度是两个音级名，小三度是三个。
- **「三种小调必须选一种用」** → 实际作品里常混用：旋律走自然小调，属和弦用和声小调，上行经过句用旋律小调。
:::

::: en
Harmonic minor is a **functional repair**. In natural minor the dominant chord is a minor triad with no leading
tone, so its pull to the tonic is weak and the harmony cannot stand. The fix is simple —
**raise the seventh degree**.

> natural minor (C): C D E♭ F G A♭ **B♭**
> harmonic minor (C): C D E♭ F G A♭ **B**  ← one note moves

The raised seventh is the **leading tone**: a semitone below the tonic, which turns the dominant chord into a
**major** triad and restores the push toward home. It is the most common accidental in minor-key writing — hear
a G♯ in a piece in A minor and this is where it comes from.

## The price: an augmented second

The change has a side effect: the sixth-to-seventh step, formerly a whole tone, becomes an
**augmented second** (A♭–B, three semitones). That interval sounds close to a minor third, is hard to sing in
tune, and gives a melody an exotic tinge. Hence the further repair of
[[concept:melodic-minor|melodic minor]] — raising the sixth as well when ascending.

## Structure

| Degree | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| vs. natural minor | = | = | = | = | = | = | **raised** |
| vs. major | = | = | **lowered** | = | = | **lowered** | = |

## Diagram: one note restored, one interval broken

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The seventh rises (the leading tone returns), but an augmented second appears between 6 and 7</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">natural minor</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="56">C</text><text x="64" y="56">D</text><text x="128" y="56">E♭</text>
      <text x="192" y="56">F</text><text x="256" y="56">G</text><text x="320" y="56">A♭</text>
      <text x="384" y="56">B</text><text x="448" y="56">C</text>
    </g>
    <text x="458" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">harmonic minor</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="384" y1="42" x2="384" y2="6"/>
      <line x1="378" y1="42" x2="390" y2="42"/>
    </g>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="320" y1="76" x2="384" y2="76"/>
      <line x1="320" y1="72" x2="320" y2="80"/><line x1="384" y1="72" x2="384" y2="80"/>
    </g>
    <text x="392" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">augmented second (A♭–B, three semitones)</text>
    <text x="0" y="108" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Harmonic gain: the dominant becomes major and the leading tone returns, so dominant-to-tonic works
    </text>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Melodic cost: steps 6 to 7 are awkward to sing — hence melodic minor's ascending fix
    </text>
  </g>
</svg>
```

## Listen: the augmented second

Hear the whole scale, and pay attention to the step from the sixth to the seventh. It is wider than the others,
and that step is where the exotic tinge lives.

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","Ab4","B4","C5"],"label":"C 和声小调","label_en":"C harmonic minor","hint":"点「上行」听第 6–7 音之间那一步","hint_en":"Try Up and listen to the step between the 6th and 7th","gap":0.38}
```

## Common misconceptions

- **"Harmonic minor is a separate scale."** It is one adjustment of natural minor for **harmonic** needs, used at dominant chords and cadences rather than necessarily throughout a piece.
- **"A written sharp must be an error."** A raised seventh is the most routine accidental in minor-key music, and harmonic minor is where it comes from.
- **"An augmented second sounds like a minor third, so it is the same thing."** Similar sound, entirely different spelling and function: three semitones spanning two letter names, not three.
- **"You must choose one of the three minors."** Real pieces mix them — natural minor in the melody, harmonic minor at the dominant, melodic minor in ascending runs.
:::
