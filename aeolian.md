---
id: aeolian
site: theo
cat: T3
title: 爱奥尼亚调式
title_en: Aeolian Mode
summary: 与自然小调同构——六个调式里的"小调那一格"
summary_en: Structurally identical to natural minor — the minor slot among the six modes
level: standard
tags: [乐理, 调式, 教会调式]
tags_en: [theory, mode, church modes]
alias: [Aeolian, 爱奥尼亚, 爱奥利亚]
order: 28
links:
  - "[[concept:minor-scale]]"
  - "[[concept:dorian]]"
  - "[[concept:mixolydian]]"
  - "[[concept:scale]]"
instances:
  - giantmidi-001413 | 曲名直接标出 Aeolian，可听"不带任何改动的小调底色" | The title names Aeolian outright — minor colour with no adjustment at all
  - atepp-000318 | a 小调奏鸣曲：以 a 为主音的调号与 C 大调共用，正是爱奥尼亚的结构 | A sonata in A minor — the signature of A shares C major's, exactly the Aeolian structure
  - giantmidi-006222 | 音阶练习里的小调片段，可把这条调式单独走一遍 | The minor fragments in scale exercises let you play the mode on its own
sources:
  - 爱奥尼亚调式 = 自然小调（大调音阶自第 6 级起的排列），属乐理通则
  - 中世纪理论将调式归为八种（含正格与变格），后简化为六种，为通行乐史记载
updated: 2026-09-23
---

::: zh
爱奥尼亚是六个调式里**最不需要记的一个**：它**就是自然小调**，一个音都不用改。

> 自然小调（C）：C D E♭ F G A♭ B♭
> 爱奥尼亚（C）：C D E♭ F G A♭ B♭  ← 完全相同

所以这一条的价值不在"新结构"，而在**两个名字的对照**：

| 语境 | 说法 | 含义 |
|---|---|---|
| 讲**调性** | a 小调 | 有一个主音、有和声功能、有属—主关系 |
| 讲**调式** | a 爱奥尼亚 | 只是"从 A 开始的一条白键序列"，不强调功能 |

同一个结构，两种说法各有各的用法：说到"转调到属调"时用调性语言，
说到"这条旋律停在第六级上"时用调式语言。

## 它在六个调式里的位置

| 调式 | 相对自然小调 |
|---|---|
| [[concept:dorian|多里亚]] | 升第 6 级 |
| **爱奥尼亚** | **不改** |
| [[concept:phrygian|弗里吉亚]] | 降第 2 级 |
| [[concept:locrian|洛克里亚]] | 降第 2、5 级 |

也就是说：**把爱奥尼亚的第 6 级升起来就是多里亚，把第 2 级降下去就是弗里吉亚。**
调式之间的差别往往只有一处，这正是它们能构成一个"家族"的原因。

## 图示：它就是自然小调

```svg
<svg viewBox="0 0 640 172" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">两条音阶的每一个音都重合，爱奥尼亚没有任何改动</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">自然小调 = 爱奥尼亚</text>
    <g stroke="#5B7FA8" stroke-width="1.4">
      <line x1="0" y1="20" x2="448" y2="20"/>
      <line x1="0" y1="16" x2="0" y2="24"/><line x1="448" y1="16" x2="448" y2="24"/>
    </g>
    <text x="0" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      全半全全半全全 —— 与自然小调的音程结构一字不差
    </text>
    <text x="0" y="72" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      另记法：C 爱奥尼亚与 E♭ 大调同音 —— 从大调第 6 级起弹到下一个第 6 级
    </text>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      家族关系：升第 6 级 → 多里亚；降第 2 级 → 弗里吉亚；再降第 5 级 → 洛克里亚
    </text>
  </g>
</svg>
```

## 听一听：爱奥尼亚

结构与自然小调完全相同，听的时候请留意它与多里亚、弗里吉亚的**一处之差**：
把第 6 级升起来、或把第 2 级降下去，色彩就换了。

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","Ab4","Bb4","C5"],"label":"C 爱奥尼亚调式（= 自然小调）","label_en":"C Aeolian mode (= natural minor)","hint":"点「上行」；与多里亚只差第 6 级","hint_en":"Try Up — only the sixth separates it from Dorian","gap":0.38}
```

## 常见误解

- **「爱奥尼亚和自然小调是不同的音阶」** → 结构完全相同，区别只在称呼的语境（调式语言 vs 调性语言）。
- **「六个调式各有专属名字，所以是六条音阶」** → 它们共用同一批音，只是主音不同。以 C 为主音时六条都从白键起。
- **「爱奥尼亚比小调"早"」** → 调式命名体系成型于中世纪理论，"小调"是后来调性实践的产物，两者是分析视角的差别，不是先后关系。
- **「叫爱奥尼亚就没有调性功能了」** → 功能照样存在；换名字不改变和声怎么运作，只改变你从哪个角度描述它。
:::

::: en
Aeolian is the mode that needs no memorising: it **is** the natural minor, with not one note changed.

> natural minor (C): C D E♭ F G A♭ B♭
> Aeolian (C): C D E♭ F G A♭ B♭  ← identical

So the value of this entry lies not in a new structure but in **two names for one thing**:

| Context | Wording | Meaning |
|---|---|---|
| **Tonal** language | A minor | one tonic, harmonic function, dominant-to-tonic relations |
| **Modal** language | A Aeolian | simply "the white-key series starting on A", without emphasis on function |

One structure, two ways of speaking, each useful in its place: reach for tonal language when talking about
modulating to the dominant, and modal language when pointing out that a melody keeps resting on the sixth degree.

## Where it sits among the six

| Mode | Relative to natural minor |
|---|---|
| [[concept:dorian|Dorian]] | raise the 6th |
| **Aeolian** | **no change** |
| [[concept:phrygian|Phrygian]] | lower the 2nd |
| [[concept:locrian|Locrian]] | lower the 2nd and 5th |

In other words: **raise Aeolian's sixth and you have Dorian; lower its second and you have Phrygian.** Modes
often differ by a single note, which is exactly why they form a family rather than six strangers.

## Diagram: it is the natural minor

```svg
<svg viewBox="0 0 640 172" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Every note coincides; Aeolian changes nothing</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">natural minor = Aeolian</text>
    <g stroke="#5B7FA8" stroke-width="1.4">
      <line x1="0" y1="20" x2="448" y2="20"/>
      <line x1="0" y1="16" x2="0" y2="24"/><line x1="448" y1="16" x2="448" y2="24"/>
    </g>
    <text x="0" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      W H W W H W W — the interval pattern matches natural minor exactly
    </text>
    <text x="0" y="72" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Another way to see it: C Aeolian holds the notes of E♭ major, played from its 6th degree
    </text>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">
      Family relations: raise the 6th for Dorian; lower the 2nd for Phrygian; lower the 5th as well for Locrian
    </text>
  </g>
</svg>
```

## Listen: Aeolian

The structure is identical to natural minor. As you listen, watch for the single-note difference from Dorian
and Phrygian: raise the sixth, or lower the second, and the colour changes.

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","Ab4","Bb4","C5"],"label":"C 爱奥尼亚调式（= 自然小调）","label_en":"C Aeolian mode (= natural minor)","hint":"点「上行」；与多里亚只差第 6 级","hint_en":"Try Up — only the sixth separates it from Dorian","gap":0.38}
```

## Common misconceptions

- **"Aeolian and natural minor are different scales."** The structure is identical; only the context of the name differs.
- **"Six modes must mean six different scales."** They share one set of notes and differ only in tonic. With C as tonic all six start on white keys.
- **"Aeolian is older than minor."** The modal naming system was formalised in medieval theory, "minor" arose from later tonal practice — two analytical viewpoints, not a sequence in time.
- **"Calling it Aeolian removes tonal function."** Function still operates; a name changes how you describe it, not how harmony behaves.
:::
