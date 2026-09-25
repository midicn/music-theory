---
id: rhythmic-pattern
site: theo
cat: T7
title: 节奏型
title_en: Rhythmic Pattern
summary: 一段反复出现的长短组合——最省力的性格工具
summary_en: A recurring combination of durations — the cheapest tool for character
level: standard
tags: [乐理, 节奏, 旋律]
tags_en: [theory, rhythm, melody]
alias: [节奏型, 固定音型, ostinato, rhythmic pattern]
order: 28
links:
  - "[[concept:rhythm]]"
  - "[[concept:dance-rhythm]]"
  - "[[concept:motive]]"
  - "[[concept:theme-variations]]"
  - "[[concept:sequence]]"
instances:
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：全曲建立在一个反复出现的舞曲节奏型上，性格由它塑造 | Liszt's transcription of Danse macabre is built on one recurring dance pattern which supplies its character
  - thesession-019704 | 《小星星》：节奏型极简（两个同音 + 一个短音）却立住了整首曲子，是最小的样本 | Twinkle Little Star's pattern is minimal — two repeated notes then a short one — yet carries the tune
  - giantmidi-006222 | 音阶与终止练习：本身就是一个固定节奏型的反复，最便于观察"同一个型换高度"的效果 | Scale and cadence exercises are a single pattern repeated, ideal for watching one figure transposed
sources:
  - 节奏型指反复出现的时值组合；固定音型（ostinato）为反复的节奏型（常带固定音高），属乐理通则
  - 节奏型与动机的区别在于是否包含音高信息，为通行乐理表述
updated: 2026-09-25
---

::: zh
节奏型（rhythmic pattern）是**一段反复出现的长短组合**。它值得单列，原因很实际：

> **它是改变性格最省力的工具** —— 因为不必动音高，只改长短。

## 与动机、固定音型的区别

三者常被混为一谈，但各自的"信息量"不同：

| 名称 | 包含 | 例 |
|---|---|---|
| **节奏型** | 只有**时值**（纯时间轮廓） | `♩ ♩ ♪♪` |
| **动机** | 时值 **+ 音高** | `C C E♭` 加上述节奏（见 [[concept:motive|动机与主题]]） |
| **固定音型**（ostinato） | 反复的节奏型，通常**带固定音高与声部** | 低音上循环的 `C–G–C` |

**判断方法**：把音高全部换成同一个音，还能认出来的是**节奏型**；
认不出来（必须靠音高才成立）的是**动机**。

## 节奏型如何塑造性格

这一点可以自己验证 —— 取一条熟悉的旋律，只改节奏型、不动音高：

| 节奏型 | 同一旋律的听感 |
|---|---|
| 全部均分（均等四分） | 方正、进行曲感 |
| 长—短—长—短 | 摇摆、口语化 |
| 短—短—长 | 急促后舒展 |
| 长音为主 | 宽广、抒情 |

（具体舞曲的典型节奏型见 [[concept:dance-rhythm|舞曲节奏型]]。）

## 固定音型：反复到"变成背景"

当一个节奏型反复足够多次，它会发生一个有趣的变化：**听者不再把它当"素材"，而当成背景**。

> 于是上方的一切（旋律、和声、配器）都可以在它之上自由变化 ——
> 这正是 [[concept:theme-variations|变奏曲式]] 与 [[concept:pedal-point|持续低音]] 的运作方式。

这条机制解释了两种看起来相反的做法其实是同一个：

| 做法 | 结果 |
|---|---|
| 固定音型 + 在上方写新内容 | 变化感（下方不变） |
| 固定音型 + 不加任何新内容 | 催眠感、机械感（如极简主义） |

**差别不在固定音型，而在上方有没有变化。**

## 图示：去掉音高，还认得出吗

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">把音高换掉、只留时值：还能认出来的，才是真正的"节奏型"</text>
  </g>

  <g transform="translate(52,52)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-22" y="0" text-anchor="end">原型</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">G</text><text x="40" y="0">G</text><text x="80" y="0">E</text>
    </g>
    <g fill="#E07A3F">
      <rect x="-16" y="14" width="32" height="12" rx="2"/>
      <rect x="24" y="14" width="32" height="12" rx="2"/>
      <rect x="64" y="14" width="32" height="12" rx="2"/>
    </g>
    <text x="110" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">这是一个动机（有音高）</text>

    <g transform="translate(0,58)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-22" y="0" text-anchor="end">去掉音高</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">C</text><text x="40" y="0">C</text><text x="80" y="0">C</text>
      </g>
      <g fill="#5B7FA8">
        <rect x="-16" y="14" width="32" height="12" rx="2"/>
        <rect x="24" y="14" width="32" height="12" rx="2"/>
        <rect x="64" y="14" width="32" height="12" rx="2"/>
      </g>
      <text x="110" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">同音重复 + 短音收尾：节奏型仍成立</text>
    </g>

    <g transform="translate(0,120)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        节奏型反复足够多次后，听者会把它当"背景"而非"素材" → 上方可以自由变化
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        固定音型 + 上方新内容 = 变化感；固定音型 + 上方不动 = 催眠感（差别不在下方）
      </text>
    </g>
  </g>
</svg>
```

## 听一听：同一个型，换高度

用 `scale` 组件听一组**同一节奏型、不同高度**的音（走一遍音阶）。
听觉上"型"没变，只有高度在变 —— 与 [[concept:sequence|模进]] 是同一个机制。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"音阶：同一节奏型换高度","label_en":"A scale: one rhythmic pattern at changing pitches","hint":"点「上行」，留意“型”始终没变","hint_en":"Try Up and notice the pattern never changes","gap":0.34}

```

## 常见误解

- **「节奏型就是动机」** → 动机含音高，节奏型只有时值。判据：把音高全换成同一个音，还认得出的是节奏型。
- **「固定音型只是伴奏」** → 它是结构手段：变奏曲式、持续低音、极简主义都建立在它上面。
- **「反复会让音乐无聊」** → 反复使下方变成背景，**上方获得自由**；无聊只发生在上方也不动的时候。
- **「节奏型必须完全重复」** → 严格重复与自由变化（改一两个音、移位）都常见，后者更耐听。
:::

::: en
A rhythmic pattern is **a recurring combination of durations**. It deserves its own entry for a practical reason:

> **It is the cheapest tool for changing character** — no pitch needs to change, only the durations.

## How it differs from a motive and an ostinato

The three are often conflated, but they carry different amounts of information:

| Name | Contains | Example |
|---|---|---|
| **rhythmic pattern** | **durations only** (a pure time outline) | `♩ ♩ ♪♪` |
| **motive** | durations **plus pitch** | `C C E♭` with the rhythm above (see [[concept:motive|motive and subject]]) |
| **ostinato** | a repeated pattern, usually **with fixed pitches and a fixed voice** | `C–G–C` looping in the bass |

**The test**: replace every pitch with the same note. If you still recognise it, it is a **rhythmic pattern**; if
not (it needs the pitches to exist), it is a **motive**.

## How a pattern shapes character

Verifiable on your own — take a familiar melody and change only its rhythm:

| Pattern | The same melody sounds |
|---|---|
| all even quarters | square, march-like |
| long-short-long-short | swinging, conversational |
| short-short-long | urgent then released |
| mostly long notes | broad, lyrical |

(For the standard patterns of specific dances, see [[concept:dance-rhythm|dance rhythms]].)

## The ostinato: repetition until it becomes background

When a pattern repeats often enough, something interesting happens: **the listener stops hearing it as material
and starts hearing it as background.**

> Everything above it — melody, harmony, orchestration — is then free to vary. This is exactly how
> [[concept:theme-variations|variation form]] and the [[concept:pedal-point|pedal point]] operate.

The mechanism explains why two opposite-sounding practices are really one:

| Practice | Result |
|---|---|
| fixed pattern + new material above | a sense of change (the lower layer stays) |
| fixed pattern + nothing new above | hypnosis, mechanism (as in minimalism) |

**The difference is not in the fixed pattern but in whether anything above it changes.**

## Diagram: remove the pitches — is it still recognisable?

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Replace the pitches and keep only the durations: what survives is a true rhythmic pattern</text>
  </g>

  <g transform="translate(52,52)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-22" y="0" text-anchor="end">original</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">G</text><text x="40" y="0">G</text><text x="80" y="0">E</text>
    </g>
    <g fill="#E07A3F">
      <rect x="-16" y="14" width="32" height="12" rx="2"/>
      <rect x="24" y="14" width="32" height="12" rx="2"/>
      <rect x="64" y="14" width="32" height="12" rx="2"/>
    </g>
    <text x="110" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">this is a motive (it has pitches)</text>

    <g transform="translate(0,58)">
      <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        <text x="-22" y="0" text-anchor="end">pitches removed</text>
      </g>
      <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
        <text x="0" y="0">C</text><text x="40" y="0">C</text><text x="80" y="0">C</text>
      </g>
      <g fill="#5B7FA8">
        <rect x="-16" y="14" width="32" height="12" rx="2"/>
        <rect x="24" y="14" width="32" height="12" rx="2"/>
        <rect x="64" y="14" width="32" height="12" rx="2"/>
      </g>
      <text x="110" y="24" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">repeated notes plus a short ending: a pattern still stands</text>
    </g>

    <g transform="translate(0,120)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        Repeat a pattern enough and it becomes background rather than material, freeing everything above it
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        Fixed pattern plus new material above gives change; with nothing above it gives hypnosis
      </text>
    </g>
  </g>
</svg>
```

## Listen: one pattern at changing heights

Use `scale` to hear **one rhythmic pattern at different pitches** (a scale walked through). The pattern never
changes; only the height does — the same mechanism as a [[concept:sequence|sequence]].

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"音阶：同一节奏型换高度","label_en":"A scale: one rhythmic pattern at changing pitches","hint":"点「上行」，留意型始终没变","hint_en":"Try Up and notice the pattern never changes","gap":0.34}
```

## Common misconceptions

- **"A rhythmic pattern is a motive."** A motive contains pitch; a pattern contains only durations. The test:
  flatten every pitch to one note — if it survives, it is a pattern.
- **"An ostinato is just an accompaniment."** It is a structural device: variation form, the pedal point and
  minimalism all rest on it.
- **"Repetition makes music boring."** Repetition turns the lower layer into background and **frees the upper
  layers**; boredom only arises when nothing above changes either.
- **"A pattern must repeat exactly."** Both strict repetition and free variation (changing a note or two,
  transposing) are common, and the latter wears better.
:::
