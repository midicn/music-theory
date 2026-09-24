---
id: phrygian
site: theo
cat: T3
title: 弗里吉亚调式
title_en: Phrygian Mode
summary: 自然小调降第二级——主音上方就是一个半音，听感最"异域"
summary_en: Natural minor with a lowered second — a semitone sits right above the tonic, the most "exotic" colour of the modes
level: standard
tags: [乐理, 调式, 教会调式]
tags_en: [theory, mode, church modes]
alias: [Phrygian, 弗里吉亚, 西班牙调式]
order: 22
links:
  - "[[concept:minor-scale]]"
  - "[[concept:dorian]]"
  - "[[concept:locrian]]"
  - "[[concept:scale]]"
instances:
  - pdmx-001470 | 曲名标出 Phrygian，可直接听"主音上方的半音"造成的紧张色彩 | The title marks it Phrygian — hear the tension a semitone above the tonic creates
  - thesession-013800 | 曲名点明弗里吉亚的传统曲调，可对照民间语境里的同一调式 | A traditional tune whose title names Phrygian — the same mode in a folk context
  - thesession-021209 | 另一首曲名点明弗里吉亚的曲调，用于与上两首横向对照 | A further tune named for Phrygian, for comparing the three side by side
sources:
  - 弗里吉亚调式 = 自然小调降第 2 级；亦等于大调音阶自第 3 级起的排列，属乐理通则
  - 弗里吉亚在西班牙、巴尔干与弗拉门戈音乐中常见，为民族音乐学通行表述
updated: 2026-09-23
---

::: zh
弗里吉亚调式最短的记忆法：**自然小调，把第 2 级降下来**。

> 自然小调（C）：C D E♭ F G A♭ B♭
> 弗里吉亚（C）：C **D♭** E♭ F G A♭ B♭

一个音，效果却最强烈：**主音上方只隔一个半音**（C–D♭）。
这个小二度让主音听起来"被压迫"，也让它成为六个调式里最容易辨认的一个 ——
西班牙、巴尔干、弗拉门戈音乐大量使用它，所以常被叫作"西班牙调式"。

## 结构

| 参照 | 改动 | 结果 |
|---|---|---|
| 自然小调 | 第 2 级降半音 | 弗里吉亚 |
| 大调音阶 | 从第 3 级起排列 | 同样是弗里吉亚 |

| 级数 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| 相对大调 | 同 | **降** | **降** | 同 | 同 | **降** | **降** |

特征音是**第 2 级**（小二度）。它与 [[concept:dorian|多里亚]] 的唯一区别就在这一处：
**第 2 级是小的还是大的？小的是弗里吉亚。**

## 图示：主音上方的半音

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">第 2 级降下半个音，主音上方就只剩一个半音</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">自然小调 / 多里亚底</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="56">C</text><text x="64" y="56">D♭</text><text x="128" y="56">E♭</text>
      <text x="192" y="56">F</text><text x="256" y="56">G</text><text x="320" y="56">A♭</text>
      <text x="384" y="56">B♭</text><text x="448" y="56">C</text>
    </g>
    <text x="458" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">弗里吉亚</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="42" x2="64" y2="42"/>
      <line x1="0" y1="38" x2="0" y2="46"/><line x1="64" y1="38" x2="64" y2="46"/>
    </g>
    <text x="72" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">只有半音 —— 这就是全部性格</text>
    <text x="0" y="94" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      另记法：C 弗里吉亚与 A♭ 大调同音 —— 从大调第 3 级起弹到下一个第 3 级
    </text>
    <text x="0" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      常见用法：低音持续在主音上（"弗里吉亚终止"），让那个半音反复被撞响
    </text>
  </g>
</svg>
```

## 听一听：主音上方的半音

先听弗里吉亚音阶，注意第 1–2 音之间的狭窄 —— 那一步就是整套"异域感"的来源。

```audiolab
{"type":"scale","notes":["C4","Db4","Eb4","F4","G4","Ab4","Bb4","C5"],"label":"C 弗里吉亚调式","label_en":"C Phrygian mode","hint":"点「上行」留意第一步只有半音","hint_en":"Try Up and notice the first step is only a semitone","gap":0.38}
```

## 常见误解

- **「弗里吉亚只是小调的一种」** → 它与自然小调差在第 2 级，且这一处差别正是它全部辨识度的来源。
- **「降 2 级就是走音」** → 它是音阶内的合法音，只是不常见于大调体系，故听着"外来的"。
- **「弗里吉亚只有西班牙用」** → 巴尔干、土耳其、犹太与弗拉门戈传统里都有，名称里的"西班牙"只是最广为人知的一处。
- **「弗里吉亚与洛克里亚很像」** → 洛克里亚还多降一个第 5 级（见 [[concept:locrian|洛克里亚]]），主音上方同样只有半音，但缺乏稳定的五度支撑。
:::

::: en
The shortest way to remember Phrygian: **natural minor with the second degree lowered.**

> natural minor (C): C D E♭ F G A♭ B♭
> Phrygian (C): C **D♭** E♭ F G A♭ B♭

One note, and the strongest effect of any mode: **a semitone sits directly above the tonic** (C–D♭). That minor
second makes the tonic sound pressed down, and it makes Phrygian the easiest mode to recognise. Spanish, Balkan
and flamenco music lean on it heavily, which is why it is often called the Spanish mode.

## Structure

| Reference | Change | Result |
|---|---|---|
| natural minor | lower the 2nd | Phrygian |
| major scale | start on the 3rd degree | also Phrygian |

| Degree | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|---|---|---|---|---|---|---|---|
| vs. major | = | **lowered** | **lowered** | = | = | **lowered** | **lowered** |

The characteristic note is the **second**. Its only difference from [[concept:dorian|Dorian]] is right there:
**is the second minor or major? Minor means Phrygian.**

## Diagram: a semitone above the tonic

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Lower the second degree and only a semitone remains above the tonic</text>
  </g>

  <g transform="translate(40,52)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">C</text><text x="64" y="0">D</text><text x="128" y="0">E♭</text>
      <text x="192" y="0">F</text><text x="256" y="0">G</text><text x="320" y="0">A♭</text>
      <text x="384" y="0">B♭</text><text x="448" y="0">C</text>
    </g>
    <text x="458" y="4" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">natural minor</text>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="56">C</text><text x="64" y="56">D♭</text><text x="128" y="56">E♭</text>
      <text x="192" y="56">F</text><text x="256" y="56">G</text><text x="320" y="56">A♭</text>
      <text x="384" y="56">B♭</text><text x="448" y="56">C</text>
    </g>
    <text x="458" y="60" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">Phrygian</text>
    <g stroke="#E07A3F" stroke-width="1.4">
      <line x1="0" y1="42" x2="64" y2="42"/>
      <line x1="0" y1="38" x2="0" y2="46"/><line x1="64" y1="38" x2="64" y2="46"/>
    </g>
    <text x="72" y="46" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">a semitone — that is the whole character</text>
    <text x="0" y="94" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Another way to see it: C Phrygian holds the notes of A♭ major, played from its 3rd degree
    </text>
    <text x="0" y="116" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Common use: a sustained bass on the tonic, so that semitone keeps getting struck
    </text>
  </g>
</svg>
```

## Listen: the semitone above the tonic

Hear the Phrygian scale and notice how narrow the first step is. That single step is the whole source of the
exotic colour.

```audiolab
{"type":"scale","notes":["C4","Db4","Eb4","F4","G4","Ab4","Bb4","C5"],"label":"C 弗里吉亚调式","label_en":"C Phrygian mode","hint":"点「上行」留意第一步只有半音","hint_en":"Try Up and notice the first step is only a semitone","gap":0.38}
```

## Common misconceptions

- **"Phrygian is just a kind of minor."** It differs from natural minor at the second degree, and that one difference is its entire identity.
- **"A lowered second is a wrong note."** It is a legal scale tone, simply rare in the major system, which is why it sounds imported.
- **"Only Spain uses it."** Balkan, Turkish, Jewish and flamenco traditions all use it; "Spanish" is just the best-known home.
- **"Phrygian and Locrian are much alike."** Locrian also lowers the fifth (see [[concept:locrian|Locrian]]): the semitone above the tonic is there too, but the stable fifth is gone.
:::
