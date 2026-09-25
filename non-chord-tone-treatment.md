---
id: non-chord-tone-treatment
site: theo
cat: T5
title: 和弦外音处理
title_en: Treating Non-Chord Tones
summary: 外音本身不难，难的是让它"听起来像故意写的"——四条处理规矩
summary_en: The note is easy; making it sound intentional is not — four rules of treatment
level: standard
tags: [乐理, 和声, 声部写作]
tags_en: [theory, harmony, part writing]
alias: [和弦外音处理, 外音处理, 不协和音处理]
order: 40
links:
  - "[[concept:non-chord-tone]]"
  - "[[concept:voice-leading]]"
  - "[[concept:harmonic-rhythm]]"
  - "[[concept:consonance]]"
  - "[[concept:counterpoint]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：外音出现的位置与解决都非常规整，是处理外音的入门样本 | The Ode of Joy theme places and resolves its foreign notes very regularly — a beginner's sample of treatment
  - mutopia-000049 | 《绿袖子》加固定低音：旋律线与低音的和声不完全重合，外音的处理因此可以逐句检查 | Greensleeves to a Ground — melody and bass harmony do not coincide exactly, so each foreign note can be checked
  - giantmidi-006222 | 音阶与琶音练习：级进走法天然产生经过音，可对照"外音"与"和弦音"两种写法的差别 | Scale and arpeggio exercises generate passing notes naturally, contrasting foreign notes with chord tones
sources:
  - 外音处理惯例（级进解决、短时值、弱拍优先、与和声节奏配合）为和声学与对位学通则
  - 强拍外音须明确解决、且以倚音与延留音为主要类型，为通行表述
updated: 2026-09-24
---

::: zh
[[concept:non-chord-tone|和弦外音]] 讲的是"外音**是什么**"（经过音、辅助音、倚音、延留音……）；
这一条讲的是"外音**怎么处理**" —— 这是写作层面的事，也是判断写作水平的地方。

**为什么处理比分类难？** 因为外音天然是一处**不协和**。不协和本身不是问题，
问题是它必须**听起来像故意写的**。同一处外音，处理得当是"味道"，处理不当是"错误"——
而两者的音符完全一样。

## 四条处理规矩

| # | 规矩 | 道理 |
|---|---|---|
| **1** | **级进解决** | 外音要按级进离开（到相邻的和弦音），跳进离开会让它听起来像和弦音 |
| **2** | **时值短于两侧** | 外音通常比它前后的和弦音短，长度一长就会"变成"和弦音 |
| **3** | **弱拍优先** | 强拍上的外音需要明确解决、且写作上更受限（所以倚音与延留音是"有身份的"强拍外音，不是随便放的） |
| **4** | **与和声节奏配合** | 外音落在**哪个和弦**上是可选的 —— 这决定了它是"装饰"还是"重新解释" |

第 4 条最容易被忽略，也最有用：

> **同一个音，落在不同的和弦上，身份完全不同。**
> 在 C 和弦上出现的 D，可能是经过音；在小节线另一侧的 G 和弦上出现的 D，却是**和弦音**。
> 所以外音处理的第一步不是"怎么写这个音"，而是"**它落在哪个和弦上**"。

## 一个常见的处理错误

**把外音放在低音区。** 低音是全曲最被注意的位置（见 [[concept:chord-voicing|和弦排列]]），
外音放在那里会立刻变成"突出的不协和"，听感上像错音。

同样，**外音最好不要与低音形成强冲突**（如小二度、三全音）。传统写作里低音几乎总是和弦音 ——
这就是原因。例外是**延留音**：低音延留恰恰是最有力的收束手段之一
（见 [[concept:pedal-point|持续低音]] 与 [[concept:cadence|终止式]] 里的挂留解决）。

## 同一处外音的两种命运

| 写法 | 结果 |
|---|---|
| 外音 → 级进 → 和弦音（短时值、弱拍） | 听成**装饰**，乐句更连贯 |
| 外音停留、跳进离开、或在低音 | 听成**错误**，即使音符完全相同 |

## 图示：同一个音，两种身份

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">能不能解决，决定同一个音是"味道"还是"错音"</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#5B7FA8">C</text><text x="70" y="0" fill="#E07A3F">D</text>
      <text x="140" y="0" fill="#5B7FA8">E</text>
      <text x="240" y="0" fill="#5B7FA8">C</text><text x="310" y="0" fill="#C0504A">D</text>
      <text x="380" y="0" fill="#C0504A">B</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="70" y="20" text-anchor="middle">外音</text>
      <text x="310" y="20" text-anchor="middle">外音</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.3">
      <line x1="0" y1="-12" x2="140" y2="-12"/>
    </g>
    <text x="0" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">C 和弦</text>
    <g stroke="#343439" stroke-width="1.3" stroke-dasharray="4 3">
      <line x1="240" y1="-12" x2="380" y2="-12"/>
    </g>
    <text x="240" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">G 和弦（此时 D 是它的五音）</text>

    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="48" fill="#5B7FA8">左：外音 D 级进到 E —— 听成经过音（装饰）</text>
      <text x="240" y="48" fill="#C0504A">右：同样的 D 落在 G 和弦上 —— 它是和弦音，不是外音</text>
    </g>
    <text x="0" y="74" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      四条规矩：① 级进解决 ② 时值短于两侧 ③ 弱拍优先 ④ 与和声节奏配合（落在哪个和弦上）
    </text>
    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      最常见的处理错误：把外音放在低音区 —— 低音最显眼，外音在那里会立刻变成"突出的错音"
    </text>
  </g>
</svg>
```

## 听一听：外音落点的影响

用进行播放器听一段进行，留意每个和弦的落点。**同一个旋律音，落在这一个和弦上是装饰，
落在下一个和弦上就是和弦音** —— 判断外音的第一步不是听音，而是听它落在哪个和声上。

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"I → IV → V → I（观察落点）","label_en":"I-IV-V-I — watch where each note lands","hint":"逐个和弦依次听，留意和声节奏如何决定外音的身份","hint_en":"Hear each chord in turn and notice how harmonic rhythm decides a note's identity"}
```

## 常见误解

- **「外音处理就是"写完之后检查一下"」** → 它是**写作时的第一步判断**：先定它落在哪个和弦上，再决定怎么写。
- **「外音越少越安全」** → 恰恰相反：外音让旋律不必被和弦锁死（见 [[concept:non-chord-tone|和弦外音]]）。关键是处理，不是回避。
- **「只要解决就没错」** → 还要看**时值**与**声部位置**。低音区的外音即使解决了，听起来仍像撞了一下。
- **「外音规则是古典时代的教条」** → 现代音乐中外音更自由，但"想让不协和听起来是故意的"这一目标没变，判断标准也没变。
:::

::: en
[[concept:non-chord-tone|Non-chord tones]] covered **what they are** (passing, neighbour, appoggiatura,
suspension…). This entry covers **how to treat them** — the compositional level, and the place where writing
skill shows.

**Why is treatment harder than classification?** Because a foreign note is by nature a **dissonance**. The
dissonance is not the problem; the problem is that it must **sound intentional**. The same foreign note handled
well is flavour, handled badly is an error — with identical pitches.

## Four rules of treatment

| # | Rule | Reasoning |
|---|---|---|
| **1** | **resolve by step** | a foreign note should leave by step to a neighbouring chord tone; leaving by leap makes it sound like a chord tone |
| **2** | **shorter than its neighbours** | it is normally shorter than the chord tones either side; held long it *becomes* a chord tone |
| **3** | **prefer weak beats** | a foreign note on a strong beat needs explicit resolution and is more constrained (which is why appoggiaturas and suspensions are "licensed" strong-beat types, not free ones) |
| **4** | **align with the harmonic rhythm** | which **chord** it falls on is a choice — and that choice decides whether it is decoration or reinterpretation |

The fourth is the most overlooked and the most useful:

> **The same note landing on a different chord is a different thing entirely.**
> A D over a C chord may be a passing note; the identical D on the far side of a barline over a G chord is a
> **chord tone**. So the first step in treating a foreign note is not "how do I write this note" but "**which
> chord does it fall on**".

## A common treatment error

**Putting foreign notes in the bass.** The bass is the most attended-to register (see
[[concept:chord-voicing|chord voicing]]), so a foreign note there instantly becomes a protruding dissonance that
sounds like a wrong note.

For the same reason, **a foreign note should not form a strong clash with the bass** (a minor second or a
tritone). In traditional writing the bass is almost always a chord tone — and that is why. The exception is the
**suspension**: a suspended bass is one of the most forceful closing devices (see
[[concept:pedal-point|pedal point]] and the suspension resolutions in [[concept:cadence|cadence]]).

## Two fates for one foreign note

| Treatment | Result |
|---|---|
| foreign note → step → chord tone (short, weak beat) | heard as **decoration**; the phrase flows |
| foreign note held, left by leap, or in the bass | heard as an **error**, even with identical pitches |

## Diagram: one note, two identities

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Whether it can resolve decides whether the same note is flavour or a mistake</text>
  </g>

  <g transform="translate(56,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#5B7FA8">C</text><text x="70" y="0" fill="#E07A3F">D</text>
      <text x="140" y="0" fill="#5B7FA8">E</text>
      <text x="240" y="0" fill="#5B7FA8">C</text><text x="310" y="0" fill="#C0504A">D</text>
      <text x="380" y="0" fill="#C0504A">B</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="70" y="20" text-anchor="middle">foreign</text>
      <text x="310" y="20" text-anchor="middle">foreign?</text>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.3">
      <line x1="0" y1="-12" x2="140" y2="-12"/>
    </g>
    <text x="0" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">C chord</text>
    <g stroke="#343439" stroke-width="1.3" stroke-dasharray="4 3">
      <line x1="240" y1="-12" x2="380" y2="-12"/>
    </g>
    <text x="240" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">G chord — where D is the fifth</text>

    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="48" fill="#5B7FA8">Left: D steps on to E — heard as a passing note, i.e. decoration</text>
      <text x="240" y="48" fill="#C0504A">Right: the same D over a G chord is a chord tone, not foreign</text>
    </g>
    <text x="0" y="74" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Four rules: resolve by step, keep it short, prefer weak beats, align with the harmonic rhythm
    </text>
    <text x="0" y="96" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      The commonest error: a foreign note in the bass — the most exposed register makes it sound simply wrong
    </text>
  </g>
</svg>
```

## Listen: how placement changes everything

Use the progression player and watch where each chord lands. **The same melodic note is decoration over one
chord and a chord tone over the next** — so the first step in judging a foreign note is not hearing the note but
hearing which harmony it lands on.

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"I → IV → V → I（观察落点）","label_en":"I-IV-V-I — watch where each note lands","hint":"逐个和弦依次听，留意和声节奏如何决定外音的身份","hint_en":"Hear each chord in turn and notice how harmonic rhythm decides a note's identity"}
```

## Common misconceptions

- **"Treating foreign notes is a check you run afterwards."** It is the **first decision while writing**: settle
  which chord the note falls on, then decide how to write it.
- **"Fewer foreign notes is safer."** The opposite: they free a melody from the chord (see
  [[concept:non-chord-tone|non-chord tones]]). The issue is treatment, not avoidance.
- **"If it resolves, it is correct."** Duration and voice position matter too. A foreign note in the bass still
  sounds like a collision even when it resolves.
- **"The rules are classical dogma."** Modern music treats foreign notes far more freely, but the goal — making a
  dissonance sound intentional — has not changed, and neither has the test.
:::
