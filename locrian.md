---
id: locrian
site: theo
cat: T3
title: 洛克里亚调式
title_en: Locrian Mode
summary: 主音上方只有半音、五度又是减五度——六个调式里唯一站不住的
summary_en: A semitone above the tonic and a diminished fifth above it — the one mode that cannot stand still
level: standard
tags: [乐理, 调式, 教会调式]
tags_en: [theory, mode, church modes]
alias: [Locrian, 洛克里亚]
order: 30
links:
  - "[[concept:phrygian]]"
  - "[[concept:minor-scale]]"
  - "[[concept:augmented-diminished]]"
  - "[[concept:scale]]"
instances:
  - giantmidi-006222 | 音阶练习可按需弹出这条音阶，是听"没有稳定五度"的最直接方式 | Scale exercises let you play the mode itself — the most direct way to hear the missing stable fifth
  - pdmx-000607 | 大调主题的第七级起就是一条洛克里亚：用它把"从哪一级起"这件事听清楚 | Starting on the seventh degree of a major theme gives a Locrian — hear where the mode actually begins
  - mutopia-000522 | 仍以这个主题作对照：同样的音，主音换成第七级后立刻失去落脚点 | The same theme as a control — with the tonic moved to the seventh degree it instantly loses its foothold
sources:
  - 洛克里亚调式 = 自然小调降第 2 级与第 5 级；亦等于大调音阶自第 7 级起的排列，属乐理通则
  - 主音上方为减五度、缺乏稳定的五度支撑，故极少独立成曲，为通行理论表述
updated: 2026-09-23
---

::: zh
洛克里亚是六个调式里**唯一几乎不独立存在**的一个。原因很直接：

> 自然小调（C）：C D E♭ F G A♭ B♭
> 洛克里亚（C）：C **D♭** E♭ F **G♭** A♭ B♭

它把自然小调的两个音都降了：

| 级数 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| 相对大调 | 同 | **降** | **降** | 同 | **降** | **降** | **降** |

两处降音合起来造成两个后果：

1. **第 2 级是半音** → 主音上方紧贴一个半音（与 [[concept:phrygian|弗里吉亚]] 相同）；
2. **第 5 级是减五度** → **主音上方没有稳定的五度**。

第 2 条是致命的。调性音乐的立足点就是主音与五度（主—属）这根支柱，
而洛克里亚的主三和弦是**减三和弦**（C–E♭–G♭）。没有稳定的五度，就没有可以"到达"的和弦 ——
所以它极少单独成曲，通常只作为 **大调音阶的第 7 级起**这一结构现象被讨论。

## 怎么听它

由于库里没有明确标为洛克里亚的曲目，最有用的做法是**自己推出来听**：

1. 找一条大调音阶或大调主题（下面三个实例都是 C1 的大调材料）；
2. **从第 7 级（导音）起，往上走到下一个第 7 级**；
3. 你会立刻听到：主音上方的半音让起点不稳，而上面那个减五度让整条线一直"悬着"。

这正好把 [[concept:scale|音阶]] 里"同一批音、主音不同"这件事听成了实感。

## 图示：为什么它站不住

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">主音上方的五度被降成了减五度 —— 支柱消失</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D♭</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G♭</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">洛克里亚</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="18" x2="64" y2="18"/>
      <line x1="0" y1="14" x2="0" y2="22"/><line x1="64" y1="14" x2="64" y2="22"/>
    </g>
    <text x="72" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">① 主音上方：半音</text>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="0" y1="42" x2="256" y2="42"/>
      <line x1="0" y1="38" x2="0" y2="46"/><line x1="256" y1="38" x2="256" y2="46"/>
    </g>
    <text x="264" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">② 主音上方：减五度（不是纯五度）</text>
    <text x="0" y="72" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      主三和弦 = 减三和弦（C–E♭–G♭）：和声里没有可"到达"的稳定落点
    </text>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      另记法：C 洛克里亚与 D♭ 大调同音 —— 从大调第 7 级起弹到下一个第 7 级
    </text>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      曲目现状：midi-lib 133,667 首中标题含 locrian 的为 0 —— 它主要是理论现象，不是曲目体裁
    </text>
  </g>
</svg>
```

## 听一听：悬着的一条音阶

先听主音上方的半音（第 1–2 音），再留意第 5 音是减五度。
整条音阶听起来会一直"没有落点"——这就是它极少独立成曲的原因。

```audiolab
{"type":"scale","notes":["C4","Db4","Eb4","F4","Gb4","Ab4","Bb4","C5"],"label":"C 洛克里亚调式","label_en":"C Locrian mode","hint":"点「上行」：第 1–2 音是半音，第 5 音是减五度","hint_en":"Try Up — a semitone at the start and a diminished fifth at the fifth degree","gap":0.38}
```

## 常见误解

- **「六个调式都同等常用」** → 洛克里亚远少于其他五个，"稀有"是它结构决定的，不是偏见。
- **「它不存在，只是理论上的一行」** → 它确实出现在实践中（如某些重金属、爵士的局部用法），只是极少作为整曲的调性中心。
- **「减五度听起来就是走音」** → 它是音阶内的合法音；问题不在音准，而在它无法承担"主音上方稳定五度"这一功能。
- **「洛克里亚与弗里吉亚一样」** → 弗里吉亚的第 5 级是**纯五度**，因此它有稳定的属和弦，是能站住的调式。
:::

::: en
Locrian is the one mode among the six that **almost never stands alone**, for a plain reason:

> natural minor (C): C D E♭ F G A♭ B♭
> Locrian (C): C **D♭** E♭ F **G♭** A♭ B♭

It lowers two notes of natural minor:

| Degree | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| vs. major | = | **lowered** | **lowered** | = | **lowered** | **lowered** | **lowered** |

Together the two lowered notes produce two consequences:

1. **The second is a semitone** — a semitone sits directly above the tonic (as in
   [[concept:phrygian|Phrygian]]);
2. **The fifth is diminished** — **there is no stable fifth above the tonic.**

The second point is fatal. Tonal music stands on the prop of tonic and fifth, and Locrian's tonic triad is a
**diminished triad** (C–E♭–G♭). Without a stable fifth there is no chord one can arrive at, so Locrian almost
never carries a piece by itself. It is usually discussed as the structural fact of
**starting a major scale on its seventh degree**.

## How to hear it

Since the library holds no piece labelled Locrian, the useful method is **to derive it and listen**:

1. Take a major scale or major-key theme (all three instances below are major-key C1 material);
2. **Start on the seventh degree and climb to the next seventh**;
3. You will hear at once that the semitone above the tonic makes the starting point unsteady, and the diminished
   fifth above keeps the whole line hanging.

That is the selection-versus-tonic point from [[concept:scale|scale]] turned into something audible.

## Diagram: why it cannot stand still

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The fifth above the tonic is lowered to a diminished fifth — the prop is gone</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D♭</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G♭</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Locrian</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="18" x2="64" y2="18"/>
      <line x1="0" y1="14" x2="0" y2="22"/><line x1="64" y1="14" x2="64" y2="22"/>
    </g>
    <text x="72" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">1: a semitone above the tonic</text>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="0" y1="42" x2="256" y2="42"/>
      <line x1="0" y1="38" x2="0" y2="46"/><line x1="256" y1="38" x2="256" y2="46"/>
    </g>
    <text x="264" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">2: a diminished fifth, not a perfect one</text>
    <text x="0" y="72" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Tonic triad = diminished (C–E♭–G♭): no stable chord to arrive on
    </text>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Another way to see it: C Locrian holds the notes of D♭ major, played from its 7th degree
    </text>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Repertoire note: of 133,667 tracks in midi-lib, zero titles mention locrian
    </text>
  </g>
</svg>
```

## Listen: a scale that hangs

Hear first the semitone above the tonic (steps 1–2), then notice that the fifth is diminished. The scale never
seems to find a resting point — which is why it hardly ever carries a piece.

```audiolab
{"type":"scale","notes":["C4","Db4","Eb4","F4","Gb4","Ab4","Bb4","C5"],"label":"C 洛克里亚调式","label_en":"C Locrian mode","hint":"点「上行」：第 1–2 音是半音，第 5 音是减五度","hint_en":"Try Up — a semitone at the start and a diminished fifth at the fifth degree","gap":0.38}
```

## Common misconceptions

- **"All six modes are equally common."** Locrian is far rarer than the other five, and its rarity follows from its structure rather than from prejudice.
- **"It does not exist; it is only a line in a textbook."** It does appear in practice (passages in metal and jazz), but hardly ever as the tonal centre of a whole piece.
- **"A diminished fifth just sounds out of tune."** It is a legal scale tone; the problem is not intonation but that it cannot serve as the stable fifth above a tonic.
- **"Locrian and Phrygian are much the same."** Phrygian's fifth is **perfect**, so it has a stable dominant chord and can stand. That is the difference.
:::
