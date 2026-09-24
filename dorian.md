---
id: dorian
site: theo
cat: T3
title: 多里亚调式
title_en: Dorian Mode
summary: 自然小调升第六级——小调的底色，却比小调明亮一点
summary_en: Natural minor with a raised sixth — a minor colour, one shade brighter
level: standard
tags: [乐理, 调式, 教会调式]
tags_en: [theory, mode, church modes]
alias: [Dorian, 多里亚, 教会调式多里亚]
order: 20
links:
  - "[[concept:minor-scale]]"
  - "[[concept:aeolian]]"
  - "[[concept:phrygian]]"
  - "[[concept:scale]]"
instances:
  - giantmidi-006017 | 曲名直接点明多里亚调式，可用于听"小调底色 + 明亮第六级"的整体效果 | The title names the mode outright — good for hearing the overall effect of a minor colour with a bright sixth
  - norbeck-001428 | 曲名含 Dorian，可作为民间曲调里同一调式的对照材料 | The title carries "Dorian" — useful material for comparing the same mode in a folk setting
  - thesession-010338 | 同样是曲名点明多里亚的传统曲调，与上面两首可作三种语境下的对照 | Another traditional tune whose title names Dorian, a third context alongside the two above
sources:
  - 多里亚调式 = 自然小调升第 6 级；亦等于大调音阶自第 2 级起的排列，属乐理通则
  - 多里亚为教会调式之一，中世纪理论与民间音乐中均常见，为通行表述
updated: 2026-09-23
---

::: zh
多里亚调式有一个最短的记忆法：**自然小调，把第 6 级升上去**。

> 自然小调（C）：C D E♭ F G A♭ B♭
> 多里亚（C）：C D E♭ F G **A** B♭

只动一个音，效果却是双向的：**底色仍是小调的暗，但第 6 级升高带来一丝向上的亮度**。
这就是多里亚听起来既不悲伤也不欢快、而是"开阔而沉着"的原因。

## 结构

| 参照 | 改动 | 结果 |
|---|---|---|
| 自然小调 | 第 6 级升半音 | 多里亚 |
| 大调音阶 | 从第 2 级起排列 | 同样是多里亚 |

后一条很重要：**在大调音阶里从第 2 级起弹到下一个第 2 级，就是多里亚**。
六个教会调式全部可以用这个方式得到（见 [[concept:scale|音阶]] 的"挑选与排列"）。

| 级数 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| 相对大调 | 同 | 同 | **降** | 同 | 同 | 同 | **降** |

特征音是**第 6 级**（大六度）：它是多里亚与爱奥尼亚（[[concept:aeolian|自然小调]]）唯一的分界，
也是与 [[concept:phrygian|弗里吉亚]]（第 2 级降）最容易被混淆的地方 —— 记法上只需问一句：
**第 6 级是大的还是小的？大的是多里亚。**

## 图示：一个音的差别

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一底色，只把第 6 级抬起来</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">自然小调</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="52">C</text><text x="64" y="52">D</text><text x="128" y="52">E♭</text>
      <text x="192" y="52">F</text><text x="256" y="52">G</text><text x="320" y="52">A</text>
      <text x="384" y="52">B♭</text><text x="448" y="52">C</text>
    </g>
    <text x="458" y="56" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">多里亚</text>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="320" y1="40" x2="320" y2="6"/>
      <line x1="314" y1="40" x2="326" y2="40"/>
    </g>
    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      只有这一处不同：A♭ → A。大六度出现，色彩转亮
    </text>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="110" x2="448" y2="110"/>
      <line x1="0" y1="106" x2="0" y2="114"/><line x1="448" y1="106" x2="448" y2="114"/>
    </g>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      另记法：C 多里亚与 B♭ 大调同音 —— 从大调第 2 级起弹到下一个第 2 级
    </text>
  </g>
</svg>
```

## 听一听：多里亚与自然小调

先听多里亚（第 6 级是 A），再听自然小调（第 6 级是 A♭）。
一个音的差别，听感是"开阔"与"收拢"的差别。

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","A4","Bb4","C5"],"label":"C 多里亚调式","label_en":"C Dorian mode","hint":"点「上行」听第 6 级的高度","hint_en":"Try Up and listen to the sixth degree","gap":0.38}
```

## 常见误解

- **「多里亚就是小调」** → 差在第 6 级。多里亚的第 6 级是大六度，自然小调是小六度。
- **「六个教会调式是六条不同的音阶」** → 它们都能从同一条大调音阶的不同级上起，只是主音换人。
- **「调式是古代的东西，现代不用」** → 民谣、摇滚、爵士里大量使用多里亚，因为它既暗又不压抑。
- **「多里亚有一个固定的调号」** → 调号按主音决定（C 多里亚用 B♭ 大调的调号），不是每条音阶配一套专属符号。
:::

::: en
The shortest way to remember Dorian: **natural minor with the sixth degree raised.**

> natural minor (C): C D E♭ F G A♭ B♭
> Dorian (C): C D E♭ F G **A** B♭

One note changes and the effect runs both ways: **the minor darkness stays, but the raised sixth brings a lift**.
That is why Dorian sounds neither sad nor cheerful, but open and level-headed.

## Structure

| Reference | Change | Result |
|---|---|---|
| natural minor | raise the 6th | Dorian |
| major scale | start on the 2nd degree | also Dorian |

That second line matters: **play a major scale from its 2nd degree to the next 2nd and you have Dorian.**
All six church modes can be produced the same way (see the selection-and-ordering section of
[[concept:scale|scale]]).

| Degree | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| vs. major | = | = | **lowered** | = | = | = | **lowered** |

The characteristic note is the **sixth** (a major sixth): it is the only thing separating Dorian from
[[concept:aeolian|Aeolian]], and the easiest way to confuse it with [[concept:phrygian|Phrygian]] (a lowered
2nd) is to forget which degree you are asking about. One question settles it: **is the sixth major or minor?
Major means Dorian.**

## Diagram: one note apart

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same colour, with the sixth degree lifted</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">natural minor</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="52">C</text><text x="64" y="52">D</text><text x="128" y="52">E♭</text>
      <text x="192" y="52">F</text><text x="256" y="52">G</text><text x="320" y="52">A</text>
      <text x="384" y="52">B♭</text><text x="448" y="52">C</text>
    </g>
    <text x="458" y="56" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Dorian</text>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="320" y1="40" x2="320" y2="6"/>
      <line x1="314" y1="40" x2="326" y2="40"/>
    </g>
    <text x="0" y="86" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      One difference only: A♭ becomes A, and the colour brightens
    </text>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="110" x2="448" y2="110"/>
      <line x1="0" y1="106" x2="0" y2="114"/><line x1="448" y1="106" x2="448" y2="114"/>
    </g>
    <text x="0" y="130" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Another way to see it: C Dorian has the notes of B♭ major, played from the 2nd degree
    </text>
  </g>
</svg>
```

## Listen: Dorian against natural minor

Hear Dorian (sixth degree A), then natural minor (A♭). One note apart, the difference is open versus closed.

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","A4","Bb4","C5"],"label":"C 多里亚调式","label_en":"C Dorian mode","hint":"点「上行」听第 6 级的高度","hint_en":"Try Up and listen to the sixth degree","gap":0.38}
```

## Common misconceptions

- **"Dorian is just minor."** The sixth degree differs: major in Dorian, minor in natural minor.
- **"The six church modes are six different scales."** They all come from one major scale started on different degrees; only the tonic changes.
- **"Modes are ancient history."** Folk, rock and jazz use Dorian heavily, precisely because it is dark without being heavy.
- **"Each mode has its own key signature."** The signature follows the tonic (C Dorian uses B♭ major's signature). Modes do not get private symbols.
:::
