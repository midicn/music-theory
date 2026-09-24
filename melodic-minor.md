---
id: melodic-minor
site: theo
cat: T3
title: 旋律小调
title_en: Melodic Minor Scale
summary: 上行升第六、七级，下行还原——一条上下行不一样的音阶
summary_en: Raise the sixth and seventh going up, restore them coming down — a scale that differs by direction
level: standard
tags: [乐理, 音阶, 小调]
tags_en: [theory, scale, minor]
alias: [旋律小调, melodic minor]
order: 38
links:
  - "[[concept:minor-scale]]"
  - "[[concept:harmonic-minor]]"
  - "[[concept:major-scale]]"
  - "[[concept:augmented-diminished]]"
instances:
  - giantmidi-006222 | 音阶练习可按需分别弹出上行与下行，是听"两个方向不一样"的最直接方式 | Scale exercises play the ascending and descending forms separately — the most direct way to hear that the two directions differ
  - atepp-000318 | a 小调奏鸣曲：小调主题上行经过句里的升六级与升七级，正是旋律小调的上行形态 | A sonata in A minor — the raised sixth and seventh in ascending minor-key runs are melodic minor's ascending form
  - atepp-001114 | g 小调叙事曲：下行旋律回到自然小调的高度，与上行形成同一段内的对照 | A ballade in G minor — descending lines drop back to natural minor, contrasting both directions inside one passage
sources:
  - 旋律小调上行为升第 6、7 级、下行还原为自然小调，为通行乐理表述
  - 该做法源于避免和声小调的增二度、同时保留升 7 级的导音功能
updated: 2026-09-23
---

::: zh
旋律小调是三种小调里**唯一"上下行不一样"**的一条：

| 方向 | 结构 | 相对自然小调 |
|---|---|---|
| **上行** | 升第 6、7 级 | A♭→A，B♭→B |
| **下行** | 还原 | 回到 A♭、B♭ |

> C 旋律小调上行：C D E♭ F G **A** **B** C
> C 旋律小调下行：C **B♭** **A♭** G F E♭ D C

## 为什么要这样做

它同时解决两个问题，代价却互相抵消：

| 需求 | 解法 | 副作用 |
|---|---|---|
| 需要导音（第 7 级升）→ 属功能成立 | 升第 7 级 | 第 6–7 级变成增二度，难唱（[[concept:harmonic-minor|和声小调]]的问题） |
| 需要唱得顺 | 上行时连第 6 级一起升 | 升上去之后上下行不一致，记谱要标两遍 |

**旋律小调是"两害相权取其轻"的结果**：既然升了第 6 级之后，上行的第 6–7 级是全音（A–B，好唱），
那就上行全升；而下行时没有导音需求，干脆还原回自然小调，旋律更柔和。

## 一个常见写法上的细节

在实际作品里，这条规则**不是机械执行**的。常见的处理是：

- 下行时，如果后面接的是属和弦，第 7 级仍会保留升高（因为功能和声需要导音）；
- 上行时，如果只是经过而非走向主音，第 6 级有时不升。

所以更准确的说法是：**旋律小调描述的是一种倾向，而不是一条必须逐音遵守的规则。**

## 图示：两个方向

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样的起止音，上行与下行走的是两条不同的路</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">上行：升 6、7 级</text>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="14" x2="448" y2="14"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="58">C</text><text x="64" y="58">B♭</text><text x="128" y="58">A♭</text>
      <text x="192" y="58">G</text><text x="256" y="58">F</text><text x="320" y="58">E♭</text>
      <text x="384" y="58">D</text><text x="448" y="58">C</text>
    </g>
    <text x="458" y="62" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">下行：还原</text>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="72" x2="448" y2="72"/>
    </g>
    <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      上行升 6、7 级 → 第 6–7 级是全音，唱得顺；同时保留导音，属功能成立
    </text>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      下行还原 → 不需要导音，回到自然小调的高度，旋律更柔和
    </text>
  </g>
</svg>
```

## 听一听：上行与下行不一样

先点「上行」，再点「下行」——同一条音阶的两种形态，请留意第 6、7 音的高度变化。

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","A4","B4","C5"],"label":"C 旋律小调（上行形态）","label_en":"C melodic minor (ascending form)","hint":"点「上行」听升 6、7 级；下行形态见正文","hint_en":"Try Up for the raised 6th and 7th; the descending form is described above","gap":0.38}
```

## 常见误解

- **「音阶只能有一个方向」** → 旋律小调是唯一上行下行结构不同的常用音阶，这正是它的定义。
- **「三种小调必须背三条」** → 记住起始点是自然小调、和声小调升 7、旋律小调上行升 6+7，三条就都出来了。
- **「作品里必须严格按规则走」** → 实际写作是灵活的（见上"常见写法"），规则描述的是倾向。
- **「旋律小调没有调号」** → 调号仍按主音决定；升降的音是临时记号，由调号之外单独标出。
:::

::: en
Melodic minor is the only one of the three minors **that differs by direction**:

| Direction | Structure | Relative to natural minor |
|---|---|---|
| **ascending** | raise the 6th and 7th | A♭→A, B♭→B |
| **descending** | restore them | back to A♭, B♭ |

> C melodic minor up: C D E♭ F G **A** **B** C
> C melodic minor down: C **B♭** **A♭** G F E♭ D C

## Why it is built this way

It solves two problems at once, and the costs cancel each other out:

| Requirement | Solution | Side effect |
|---|---|---|
| a leading tone (raise the 7th) so dominant function works | raise the 7th | steps 6–7 become an augmented second, awkward to sing (the problem of [[concept:harmonic-minor|harmonic minor]]) |
| a melody that sings smoothly | raise the 6th too, when ascending | the two directions now differ, so notation must state both |

**Melodic minor is the lesser of two evils.** Once the sixth is raised, the ascending 6–7 step is a whole tone
(A–B, easy to sing), so ascend with both raised; descending has no need of a leading tone, so restore them and
let the line soften back toward natural minor.

## A practical detail

In real music the rule is **not applied mechanically**:

- descending, if a dominant chord follows, the seventh often stays raised, because the harmony needs the
  leading tone;
- ascending, if a line merely passes through rather than heading for the tonic, the sixth is sometimes left
  unraised.

So the more accurate statement is: **melodic minor describes a tendency, not a rule to be obeyed note by note.**

## Diagram: two directions

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same endpoints; ascending and descending take different routes</text>
  </g>

  <g transform="translate(40,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A</text>
      <text x="384" y="0">B</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">ascending: 6th and 7th raised</text>
    <g stroke="#E07A3F" stroke-width="1.2">
      <line x1="0" y1="14" x2="448" y2="14"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="58">C</text><text x="64" y="58">B♭</text><text x="128" y="58">A♭</text>
      <text x="192" y="58">G</text><text x="256" y="58">F</text><text x="320" y="58">E♭</text>
      <text x="384" y="58">D</text><text x="448" y="58">C</text>
    </g>
    <text x="458" y="62" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">descending: restored</text>
    <g stroke="#5B7FA8" stroke-width="1.2">
      <line x1="0" y1="72" x2="448" y2="72"/>
    </g>
    <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Ascending with both raised: 6 to 7 is a whole tone, easy to sing, and the leading tone is kept
    </text>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Descending restored: no leading tone needed, so the line slides back to natural minor
    </text>
  </g>
</svg>
```

## Listen: up and down differ

Press Up, then Down. One scale with two forms — listen to the height of the sixth and seventh.

```audiolab
{"type":"scale","notes":["C4","D4","Eb4","F4","G4","A4","B4","C5"],"label":"C 旋律小调（上行形态）","label_en":"C melodic minor (ascending form)","hint":"点「上行」听升 6、7 级；下行形态见正文","hint_en":"Try Up for the raised 6th and 7th; the descending form is described above","gap":0.38}
```

## Common misconceptions

- **"A scale can only run one way."** Melodic minor is the one common scale whose ascending and descending structures differ; that is its definition.
- **"You must memorise three separate minors."** Start from natural minor, raise the 7th for harmonic minor, raise 6 and 7 going up for melodic minor — all three follow.
- **"Pieces must follow the rule strictly."** Real writing is flexible (see above); the rule describes a tendency.
- **"Melodic minor has no key signature."** The signature still follows the tonic; the raised notes are accidentals marked on top of it.
:::
