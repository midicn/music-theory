---
id: fourth-species
site: theo
cat: T6
title: 第四类对位
title_en: Fourth Species
summary: 切分对位——用延留音把重音错开，挂留和弦就是这么来的
summary_en: Syncopated counterpoint — suspensions displace the accents, and the suspended chord comes from here
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [第四类对位, 切分对位, 延留音对位, fourth species]
order: 20
links:
  - "[[concept:third-species]]"
  - "[[concept:fifth-species]]"
  - "[[concept:suspended-chord]]"
  - "[[concept:non-chord-tone-treatment]]"
  - "[[concept:second-species]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：两声部之间的错位让延留音清晰可辨，是切分对位的典型织体 | Bach's first two-part invention — the offset between the voices makes suspensions clearly audible
  - cyberhymnal-000695 | 管风琴圣咏：传统和声里延留音的"准备—挂留—解决"三步非常规范，可用作标准样本 | An organ hymn — the prepare-suspend-resolve pattern of suspensions is entirely regular here
  - mutopia-000049 | 《绿袖子》加固定低音：低音与旋律的错位经常造成挂留式音响，可听三者如何依次发生 | Greensleeves to a Ground — the offset between bass and melody repeatedly produces suspended sonorities
sources:
  - 第四类对位（切分对位）以延留音为核心：须经"准备—挂留—解决"三步，属对位学通则
  - 挂留和弦（sus2/sus4）即来源于延留音的和声化，为通行和声学表述
updated: 2026-09-24
---

::: zh
第四类对位换了思路：不再增加音符数量，而是**改变音符的位置**。

> 对位声部**晚半步**进入每个音，于是它总在强拍上"还停在上一个音" —— 这就是**延留音**。

## 延留音的三步

延留音不是"某个音没动"，它有严格的三个阶段：

| 阶段 | 状态 | 要求 |
|---|---|---|
| **准备** | 这个音在前一个和弦里是**协和音** | 必须先站住，才有资格被"留" |
| **挂留** | 和弦换了，它**留下来**，于是变成不协和 | 张力在这一步产生 |
| **解决** | 它**级进下行**（通常向下）到新的和弦音 | 不协和在此释放 |

三步缺一不可。特别是**第一步**：没有"准备"的延留音，在听感上就是"一个错音"，
而不是"一处被延后的张力"。

## 为什么它值得单列一类

因为它揭示了一件和声学里极其重要的事：

> **不协和是可以被"计划"的。**

第二类与第三类里的不协和音是**经过性**的（快速掠过）；第四类的延留音是**结构性**的 ——
它占据强拍、有明确的准备与解决，是**精心安排的张力**。

[[concept:suspended-chord|挂留和弦]]（sus4 / sus2）正是这一手法的和声化结果：
把"延留音 + 它的解决"压进一个和弦里，就成了一个"悬而未决"的和弦。

## 它的写作难点：错位会让纵向关系全部改变

切分对位最难的地方在于：**每个音的纵向关系都被"错开"了**。

| 时刻 | 与固定旋律的关系 |
|---|---|
| 延留音落在强拍时 | 它与固定旋律形成**不协和**（这是正常的） |
| 解决之后 | 又回到协和 |

所以要检查的不是"每个时刻都协和"，而是**"不协和的时刻是否恰好是延留音，且即将解决"**。
这把判断标准从"结果"推向了"**过程**"—— 这也是它最接近真实和声写作的地方
（见 [[concept:non-chord-tone-treatment|和弦外音处理]]）。

## 与第二类的区别（容易混）

| | 第二类 | 第四类 |
|---|---|---|
| 错位方式 | 插入**额外**的音 | **不插入**，只是把音往后挪 |
| 不协和位置 | 弱拍 | **强拍**（这是关键差别） |
| 不协和性质 | 经过 | **结构性的延留** |

一句话：**第二类的错位是为了填充，第四类的错位是为了延后。**

## 图示：准备 → 挂留 → 解决

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">三步缺一不可：没有"准备"的延留音听起来就是错音</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-30" y="60" text-anchor="end">对位</text>
      <text x="-30" y="0" text-anchor="end">固定</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="120" y="0">C</text><text x="240" y="0">C</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="60" fill="#5B7FA8">E</text>
      <text x="120" y="60" fill="#C0504A">F</text>
      <text x="240" y="60" fill="#5B7FA8">E</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="54"/>
      <line x1="120" y1="8" x2="120" y2="54"/>
      <line x1="240" y1="8" x2="240" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
      <text x="0" y="82" fill="#5B7FA8">① 准备（协和）</text>
      <text x="120" y="82" fill="#C0504A">② 挂留（不协和）</text>
      <text x="240" y="82" fill="#5B7FA8">③ 解决（级进下行）</text>
    </g>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="120" y1="46" x2="120" y2="30"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.4">
      <line x1="120" y1="74" x2="200" y2="66"/>
      <polygon points="200,60 210,66 200,72" fill="#5B7FA8" stroke="none"/>
    </g>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      与第二类的关键差别：不协和落在强拍上，而且它是被"计划"出来的
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      挂留和弦（sus4 / sus2）= 把"延留音 + 解决"压进一个和弦的和声化结果
    </text>
  </g>
</svg>
```

## 听一听：协和与不协和的推迟

第四类是两声部练习，本站放不出两声部。这里用 `interval` 听**延留音形成的那一刻**：
三度（协和）变成二度（不协和）再回到三度 —— 这正是"准备—挂留—解决"的纵向听感。

```audiolab
{"type":"interval","a":"C4","b":"F4","label":"挂留的瞬间：四度（需解决）","label_en":"The suspended moment: a fourth, needing resolution","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E4 就是解决后的三度 —— 协和与不协和之间那次级进下行，就是解决。","hint2_en":"Set b to E4 for the resolved third — that stepwise descent between them is the resolution."}
```

## 常见误解

- **「延留音就是"不改音"」** → 它必须经过**准备—挂留—解决**三步。缺少准备只是错音。
- **「延留音必须下行解决」** → 绝大多数情况如此；上行解决的延留音存在但罕见，且需要特殊处理。
- **「它其实就是第二类换了个写法」** → 关键差别在**不协和落在强拍**，且是**结构性**的而非经过性的。
- **「挂留和弦与延留音无关」** → 挂留和弦正是延留音的和声化：把"准备 + 挂留 + 解决"压成一个和弦。
:::

::: en
Fourth species changes tack: instead of adding notes, it **changes where they sit**.

> The counterpoint enters **half a step late** on each note, so it is still holding the previous pitch on the
> strong beat — that is a **suspension**.

## The three stages of a suspension

A suspension is not "a note that failed to move". It has three strict stages:

| Stage | State | Requirement |
|---|---|---|
| **preparation** | the note was **consonant** in the previous chord | it must have been established before it can be held |
| **suspension** | the chord changes and the note **stays**, becoming dissonant | the tension is created here |
| **resolution** | it moves **down by step** (usually) to a new chord tone | the dissonance is released |

All three are required. The first especially: without preparation a suspension simply sounds like a wrong note, not
like postponed tension.

## Why it deserves a species of its own

Because it reveals something fundamental in harmony:

> **Dissonance can be planned.**

In second and third species the dissonances are **passing** (quickly passed over). A suspension is
**structural** — it occupies a strong beat, has an explicit preparation and resolution, and is **deliberate
tension**.

The [[concept:suspended-chord|suspended chord]] (sus4 / sus2) is this device harmonised: compress "suspension and
its resolution" into a single chord and you get a chord that hangs unresolved.

## The difficulty: displacement changes every vertical relation

What makes syncopated counterpoint hard is that **every vertical relation is offset**.

| Moment | Relation to the cantus firmus |
|---|---|
| the suspension lands on the strong beat | it forms a **dissonance** with the cantus (as intended) |
| after resolution | consonant again |

So what must be checked is not "consonant at every moment" but **"is each dissonant moment precisely a suspension
about to resolve?"** That shifts judgement from **result** to **process** — which is also what makes it the
closest of the species to real harmonic writing (see [[concept:non-chord-tone-treatment|treating non-chord
tones]]).

## How it differs from second species (easily confused)

| | Second species | Fourth species |
|---|---|---|
| Method of displacement | **inserts** extra notes | **inserts nothing**; only shifts notes later |
| Where dissonance lands | weak beat | **strong beat** — the key difference |
| Nature of the dissonance | passing | **structural suspension** |

In one line: **second species displaces in order to fill; fourth species displaces in order to delay.**

## Diagram: preparation, suspension, resolution

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">All three stages required: an unprepared suspension simply sounds wrong</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-30" y="60" text-anchor="end">counterpoint</text>
      <text x="-30" y="0" text-anchor="end">cantus</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="120" y="0">C</text><text x="240" y="0">C</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="60" fill="#5B7FA8">E</text>
      <text x="120" y="60" fill="#C0504A">F</text>
      <text x="240" y="60" fill="#5B7FA8">E</text>
    </g>
    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="8" x2="0" y2="54"/>
      <line x1="120" y1="8" x2="120" y2="54"/>
      <line x1="240" y1="8" x2="240" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
      <text x="0" y="82" fill="#5B7FA8">1 preparation (consonant)</text>
      <text x="120" y="82" fill="#C0504A">2 suspension (dissonant)</text>
      <text x="240" y="82" fill="#5B7FA8">3 resolution (down by step)</text>
    </g>
    <g stroke="#C0504A" stroke-width="1.4">
      <line x1="120" y1="46" x2="120" y2="30"/>
    </g>
    <g stroke="#5B7FA8" stroke-width="1.4">
      <line x1="120" y1="74" x2="200" y2="66"/>
      <polygon points="200,60 210,66 200,72" fill="#5B7FA8" stroke="none"/>
    </g>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      The key difference from second species: the dissonance lands on a strong beat, and it is planned
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Sus4 and sus2 chords are suspensions harmonised into a single chord
    </text>
  </g>
</svg>
```

## Listen: postponed consonance

Fourth species is a two-voice exercise and cannot be played here. Use `interval` to hear **the moment the
suspension forms**: a third (consonant) becomes a fourth (dissonant) and returns to a third — exactly the vertical
sound of prepare-suspend-resolve.

```audiolab
{"type":"interval","a":"C4","b":"F4","label":"挂留的瞬间：四度（需解决）","label_en":"The suspended moment: a fourth, needing resolution","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E4 就是解决后的三度 —— 两者之间那次级进，就是解决。","hint2_en":"Set b to E4 for the resolved third — the step between them is the resolution."}
```

## Common misconceptions

- **"A suspension is just a note that did not change."** It must pass through **preparation, suspension and
  resolution**. Without preparation it is merely a wrong note.
- **"A suspension always resolves downward."** Almost always; upward resolutions exist but are rare and need
  special handling.
- **"It is second species by another name."** The decisive difference is that the dissonance lands on a **strong
  beat** and is **structural**, not passing.
- **"The suspended chord has nothing to do with suspensions."** It is the suspension harmonised: preparation,
  suspension and resolution compressed into one chord.
:::
