---
id: mixolydian
site: theo
cat: T3
title: 混合利底亚调式
title_en: Mixolydian Mode
summary: 大调降第七级——有大调的亮，却少了那股必须回家的力
summary_en: Major with a lowered seventh — major brightness, but without that compulsion to go home
level: standard
tags: [乐理, 调式, 教会调式]
tags_en: [theory, mode, church modes]
alias: [Mixolydian, 混合利底亚, 蓝调大调]
order: 26
links:
  - "[[concept:major-scale]]"
  - "[[concept:lydian]]"
  - "[[concept:aeolian]]"
  - "[[concept:blues-scale]]"
  - "[[concept:scale]]"
instances:
  - giantmidi-008642 | 曲名直接标出 mixolydian，可用于听"大调底色 + 降七级"的整体效果 | The title names mixolydian outright — good for hearing major colour with a lowered seventh
  - pdmx-000607 | 同一套主题的大调版本，可与此处对照：把第 7 级降下去就得到混合利底亚 | The major-key version of a theme, useful as a control — lower its seventh and you have Mixolydian
  - giantmidi-006222 | 音阶练习可按需弹出该调式，用于把结构听一遍 | Scale exercises can be used to play the mode itself and hear the structure
sources:
  - 混合利底亚调式 = 大调音阶降第 7 级；亦等于大调音阶自第 5 级起的排列，属乐理通则
  - 混合利底亚在民间音乐、摇滚与蓝调中广泛使用，为通行表述
updated: 2026-09-23
---

::: zh
混合利底亚的记忆法：**大调，把第 7 级降下来**。

> C 大调：C D E F G A **B**
> 混合利底亚（C）：C D E F G A **B♭**

降下去的第 7 级，恰好是**调性音乐里最重要的一股力** —— 导音。
大调的第 7 级与主音只隔半音，制造出"必须回家"的强烈倾向；把它降下半音，
这股力就消失了：**底色仍是大调的明亮，但不再有收束的冲动**。

## 结构

| 参照 | 改动 | 结果 |
|---|---|---|
| 大调音阶 | 第 7 级降半音 | 混合利底亚 |
| 大调音阶 | 从第 5 级起排列 | 同样是混合利底亚 |

| 级数 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| 相对大调 | 同 | 同 | 同 | 同 | 同 | 同 | **降** |

特征音是**第 7 级**（小七度）。它与 [[concept:lydian|利底亚]] 的区分见上一条；
与 [[concept:aeolian|爱奥尼亚]] 的区分则看第 3 级：**第 3 级是大的 → 混合利底亚；小的 → 爱奥尼亚。**

## 为什么它在民间与摇滚里这么常见

因为它在**不缺调性感**的前提下**去掉了导音的强制力**：旋律可以长时间停在第 7 级上而不显得"没解决"，
也可以靠它反复回到主音而不显得"太古典"。[[concept:blues-scale|蓝调音阶]]的小七度与之同源。

## 图示：把导音降下去

```svg
<svg viewBox="0 0 640 188" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">降下第 7 级，导音的半音引力随之消失</text>
  </g>

  <g transform="translate(40,50)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">大调（B 是导音）</text>
    <g stroke="#6E6A64" stroke-width="1.2" stroke-dasharray="3 2">
      <line x1="384" y1="12" x2="448" y2="12"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="56">C</text><text x="64" y="56">D</text><text x="128" y="56">E</text>
      <text x="192" y="56">F</text><text x="256" y="56">G</text><text x="320" y="56">A</text>
      <text x="384" y="56">B♭</text><text x="448" y="56">C</text>
    </g>
    <text x="458" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">混合利底亚</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="384" y1="42" x2="384" y2="6"/>
      <line x1="378" y1="42" x2="390" y2="42"/>
    </g>
    <text x="0" y="84" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      B → B♭：第 7 级降到主音下方一整个全音，回到主音的拉力因此减弱
    </text>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      另记法：C 混合利底亚与 F 大调同音 —— 从大调第 5 级起弹到下一个第 5 级
    </text>
  </g>
</svg>
```

## 听一听：降七级

先听混合利底亚，再听大调。第 7 音的高度不同，一个可以停在那里，一个非回家不可。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","Bb4","C5"],"label":"C 混合利底亚调式","label_en":"C Mixolydian mode","hint":"点「上行」听第 7 音比大调低半个音","hint_en":"Try Up and hear the seventh sitting a semitone lower than in major","gap":0.38}
```

## 常见误解

- **「降七级就是蓝调音」** → 蓝调音阶还含降三度与降五度，是另一条音阶（见 [[concept:blues-scale|蓝调音阶]]）。
- **「混合利底亚没有调性」** → 有明确主音，只是缺少导音的强制力，收束更自由。
- **「都一样，只是记法不同」** → 听感差别很实：大调第 7 级是小二度（紧张），混合利底亚是大二度（松弛）。
- **「只在民间音乐里用」** → 摇滚、放克、爵士的标准语汇，也是即兴独奏最常用的调式之一。
:::

::: en
How to remember Mixolydian: **major, with the seventh lowered.**

> C major: C D E F G A **B**
> Mixolydian (C): C D E F G A **B♭**

The lowered seventh happens to be **the single most important force in tonal music** — the leading tone. In
major it sits a semitone below the tonic and creates a strong compulsion to go home. Lower it and the compulsion
is gone: **the major brightness stays, the urge to close does not.**

## Structure

| Reference | Change | Result |
|---|---|---|
| major scale | lower the 7th | Mixolydian |
| major scale | start on the 5th degree | also Mixolydian |

| Degree | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| vs. major | = | = | = | = | = | = | **lowered** |

The characteristic note is the **seventh** (a minor seventh). Its difference from [[concept:lydian|Lydian]] was
covered above; from [[concept:aeolian|Aeolian]] the deciding question is the third: **major third means
Mixolydian, minor third means Aeolian.**

## Why folk and rock use it so much

Because it **removes the leading tone's compulsion without losing a tonal centre**. A melody can rest on the
seventh without sounding unresolved, or lean on it to return to the tonic without sounding classical. The minor
seventh of the [[concept:blues-scale|blues scale]] comes from the same place.

## Diagram: lowering the leading tone

```svg
<svg viewBox="0 0 640 188" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Lower the seventh and the semitone pull of the leading tone disappears</text>
  </g>

  <g transform="translate(40,50)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">major (B leads)</text>
    <g stroke="#6E6A64" stroke-width="1.2" stroke-dasharray="3 2">
      <line x1="384" y1="12" x2="448" y2="12"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="56">C</text><text x="64" y="56">D</text><text x="128" y="56">E</text>
      <text x="192" y="56">F</text><text x="256" y="56">G</text><text x="320" y="56">A</text>
      <text x="384" y="56">B♭</text><text x="448" y="56">C</text>
    </g>
    <text x="458" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Mixolydian</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="384" y1="42" x2="384" y2="6"/>
      <line x1="378" y1="42" x2="390" y2="42"/>
    </g>
    <text x="0" y="84" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      B becomes B♭: a whole tone below the tonic now, so the pull home weakens
    </text>
    <text x="0" y="106" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Another way to see it: C Mixolydian holds the notes of F major, played from its 5th degree
    </text>
  </g>
</svg>
```

## Listen: the lowered seventh

Hear Mixolydian, then major. The seventh differs in height: one can rest there, the other insists on coming home.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","Bb4","C5"],"label":"C 混合利底亚调式","label_en":"C Mixolydian mode","hint":"点「上行」听第 7 音比大调低半个音","hint_en":"Try Up and hear the seventh sitting a semitone lower than in major","gap":0.38}
```

## Common misconceptions

- **"A lowered seventh is the blues note."** The blues scale also lowers the third and fifth — it is a different scale (see [[concept:blues-scale|blues scale]]).
- **"Mixolydian has no tonal centre."** It has a clear tonic; it simply lacks the leading tone's compulsion, so closure is freer.
- **"It is only a notational difference."** The heard difference is real: major's seventh is a minor second from the tonic (tense), Mixolydian's is a whole tone (relaxed).
- **"Only folk music uses it."** It is standard vocabulary in rock, funk and jazz, and one of the most common modes for soloing.
:::
