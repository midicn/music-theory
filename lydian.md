---
id: lydian
site: theo
cat: T3
title: 利底亚调式
title_en: Lydian Mode
summary: 大调升第四级——最"悬浮"的一个调式，主音上方是个增四度
summary_en: Major with a raised fourth — the most suspended of the modes, with a tritone sitting above the tonic
level: standard
tags: [乐理, 调式, 教会调式]
tags_en: [theory, mode, church modes]
alias: [Lydian, 利底亚]
order: 24
links:
  - "[[concept:major-scale]]"
  - "[[concept:mixolydian]]"
  - "[[concept:augmented-diminished]]"
  - "[[concept:scale]]"
instances:
  - giantmidi-000486 | 曲名标出 Lydian，可直接听"升四级"带来的悬浮感 | The title marks it Lydian — hear the floating quality a raised fourth produces
  - giantmidi-008074 | 另一首标题点明利底亚的前奏曲，可与上一条对照不同的织体 | Another prelude whose title names Lydian — a different texture for comparison
  - thesession-007687 | 曲名含 Lydian 的传统曲调，用于对照民间语境下的同一调式 | A traditional tune whose title carries Lydian — the same mode in a folk setting
sources:
  - 利底亚调式 = 大调音阶升第 4 级；亦等于大调音阶自第 4 级起的排列，属乐理通则
  - 主音上方为增四度、因而缺乏下属方向的稳定支撑，为通行理论表述
updated: 2026-09-23
---

::: zh
利底亚是六个调式里**唯一比大调更亮**的一个，也是唯一"悬浮"的一个：**大调，把第 4 级升上去**。

> C 大调：C D E **F** G A B
> 利底亚（C）：C D E **F♯** G A B

升起的第 4 级带来两个后果：

1. **主音到第 4 级变成增四度**（C–F♯，六个半音）。这是所有音阶里唯一以三全音作为特征音的
   形态 —— 难怪它听起来不安定（见 [[concept:augmented-diminished|增音程与减音程]]）。
2. **失去了下属方向的支撑**。大调里第 4 级是下属音，是主音的"下方支点"；升上去之后这支点消失了。

## 结构

| 参照 | 改动 | 结果 |
|---|---|---|
| 大调音阶 | 第 4 级升半音 | 利底亚 |
| 大调音阶 | 从第 4 级起排列 | 同样是利底亚 |

| 级数 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| 相对大调 | 同 | 同 | 同 | **升** | 同 | 同 | 同 |

特征音是**第 4 级**（增四度）。与 [[concept:mixolydian|混合利底亚]] 只差一处：**第 4 级是升的还是不动的？**
升的是利底亚，不动而第 7 级降的是混合利底亚。

## 图示：升起的第四级

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">只有第 4 级动了一下，主音上方就从纯四度变成了增四度</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">大调</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="56">C</text><text x="64" y="56">D</text><text x="128" y="56">E</text>
      <text x="192" y="56">F♯</text><text x="256" y="56">G</text><text x="320" y="56">A</text>
      <text x="384" y="56">B</text><text x="448" y="56">C</text>
    </g>
    <text x="458" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">利底亚</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="76" x2="192" y2="76"/>
      <line x1="0" y1="72" x2="0" y2="80"/><line x1="192" y1="72" x2="192" y2="80"/>
    </g>
    <text x="200" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">C–F♯：增四度，六个半音</text>
    <text x="0" y="104" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      另记法：C 利底亚与 G 大调同音 —— 从大调第 4 级起弹到下一个第 4 级
    </text>
  </g>
</svg>
```

## 听一听：升四级

先听利底亚，再听大调。差别只在第 4 音的高度 —— 一个悬浮，一个落地。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F#4","G4","A4","B4","C5"],"label":"C 利底亚调式","label_en":"C Lydian mode","hint":"点「上行」听第 4 音比大调高出半个音","hint_en":"Try Up and hear the fourth sitting a semitone higher than in major","gap":0.38}
```

## 常见误解

- **「升四级是写错了」** → 它是利底亚的定义。写成 F 就变成大调了。
- **「利底亚就是大调换了个起点」** → 结构上确实可以从大调第 4 级起得到，但听感重心完全不同：主音换了，悬浮感是主音与第 4 级之间那个增四度造成的。
- **「增四度必然刺耳」** → 在利底亚里它常被处理成柔和的悬浮而非尖锐的紧张，取决于和声与配器。
- **「利底亚很少见」** → 在电影配乐与后摇滚里它是制造"辽阔、悬浮"的常用工具。
:::

::: en
Lydian is the only one of the six modes that is **brighter than major**, and the only one that hovers:
**major with a raised fourth.**

> C major: C D E **F** G A B
> Lydian (C): C D E **F♯** G A B

The raised fourth has two consequences:

1. **The tonic to the fourth becomes a tritone** (C–F♯, six semitones). It is the only scale whose
   characteristic note is that interval — no wonder it sounds unsettled (see
   [[concept:augmented-diminished|augmented and diminished]]).
2. **The subdominant support disappears.** In major, the fourth degree is the lower prop under the tonic; raise
   it and the prop is gone.

## Structure

| Reference | Change | Result |
|---|---|---|
| major scale | raise the 4th | Lydian |
| major scale | start on the 4th degree | also Lydian |

| Degree | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| vs. major | = | = | = | **raised** | = | = | = |

The characteristic note is the **fourth** (a tritone above the tonic). Its only difference from
[[concept:mixolydian|Mixolydian]] is one thing: **is the fourth raised, or untouched?** Raised means Lydian;
untouched with a lowered seventh means Mixolydian.

## Diagram: the raised fourth

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One degree moves, and the fourth above the tonic turns from perfect into augmented</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">major</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="56">C</text><text x="64" y="56">D</text><text x="128" y="56">E</text>
      <text x="192" y="56">F♯</text><text x="256" y="56">G</text><text x="320" y="56">A</text>
      <text x="384" y="56">B</text><text x="448" y="56">C</text>
    </g>
    <text x="458" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Lydian</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="76" x2="192" y2="76"/>
      <line x1="0" y1="72" x2="0" y2="80"/><line x1="192" y1="72" x2="192" y2="80"/>
    </g>
    <text x="200" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">C–F♯: augmented fourth, six semitones</text>
    <text x="0" y="104" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Another way to see it: C Lydian holds the notes of G major, played from its 4th degree
    </text>
  </g>
</svg>
```

## Listen: the raised fourth

Hear Lydian, then major. The only difference is the height of the fourth — one hovers, the other lands.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F#4","G4","A4","B4","C5"],"label":"C 利底亚调式","label_en":"C Lydian mode","hint":"点「上行」听第 4 音比大调高出半个音","hint_en":"Try Up and hear the fourth sitting a semitone higher than in major","gap":0.38}
```

## Common misconceptions

- **"A raised fourth is a mistake."** It is the definition of Lydian. Write F instead and you have major again.
- **"Lydian is just major started elsewhere."** Structurally it can be derived that way, but the centre of gravity moves: the hovering comes from the tritone between the new tonic and its fourth.
- **"A tritone must sound harsh."** In Lydian it is usually handled as a soft suspension rather than a bite, depending on harmony and scoring.
- **"Lydian is rare."** In film scoring and post-rock it is a standard tool for a wide, floating atmosphere.
:::
