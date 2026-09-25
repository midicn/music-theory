---
id: secondary-dominant
site: theo
cat: T5
title: 副属和弦
title_en: Secondary Dominant
summary: 给任何一个级数临时配一个属和弦——不用转调也能获得新鲜感
summary_en: Give any degree its own temporary dominant — freshness without modulating
level: standard
tags: [乐理, 和声, 调性]
tags_en: [theory, harmony, tonality]
alias: [副属和弦, 临时属和弦, V/V, applied dominant, secondary dominant]
order: 24
links:
  - "[[concept:harmonic-function]]"
  - "[[concept:tonicization]]"
  - "[[concept:modulation]]"
  - "[[concept:chromatic-harmony]]"
  - "[[concept:key-signature]]"
instances:
  - atepp-000318 | a 小调奏鸣曲：副属和弦把音乐短暂推向别的级数，随即回到原调 | A sonata in A minor — secondary dominants push the music briefly toward another degree before it returns
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：半音化和声里副属和弦密集出现，是"临时中心"的集中用法 | Liszt's transcription of Danse macabre — secondary dominants crowd the chromatic texture, a concentration of temporary centres
  - mutopia-000049 | 《绿袖子》加固定低音：变奏里常见对下属与属的临时强调 | Greensleeves to a Ground — its variations often emphasise the subdominant or dominant temporarily
sources:
  - 副属和弦 = 某级的属和弦（V/x 或 V7/x），其升高的音不属于原调音阶，属和声学通则
  - 副属和弦造成的短暂中心称为离调，与转调以时长与是否建立新中心区分，为通行表述
updated: 2026-09-24
---

::: zh
副属和弦的思路很简单：**既然属和弦能指向主和弦，那它也能指向别的级数。**

> 在 C 大调里，主和弦是 C。那么"**D 的属和弦**"（A–C♯–E）就可以指向 D 小调那个区域 ——
> 这个 A 和弦就叫 **V/V**（"五级的五级"），也就是**副属和弦**。

它带来的新音（C♯）**不属于 C 大调音阶**。所以副属和弦天然是一处变化音，
也是一处**色彩变化点**。

## 常用的一组

| 记号 | 指向 | 在 C 大调里的和弦 | 新出现的音 |
|---|---|---|---|
| **V/ii** | 第 2 级 | A 大三（A–C♯–E） | C♯ |
| **V/IV** | 第 4 级 | C 大三（就是 I —— 因此不构成变化） | 无 |
| **V/V** | 第 5 级 | D 大三（D–F♯–A） | F♯ |
| **V/vi** | 第 6 级 | E 大三（E–G♯–B） | G♯ |

注意第二行：**V/IV 与 I 是同一个和弦**，所以它不产生副属效果 ——
要指向下属，得用 V7/IV（C 属七：C–E–G–B♭），B♭ 才是那个新音。

## 它解决到哪里

副属和弦的"目标"就是它指向的那个级数，而且**优先解决到该级的小三和弦或大三和弦**：

> V/V → V（D 大三 → G 大三）
> V/vi → vi（E 大三 → a 小三）

如果目标级是小三和弦（如 ii、vi），副属和弦里的**升高音**就是一个"临时导音"，
它上行半音进入目标音 —— 与真正的属→主完全同构，只是缩小到了局部。

## 与转调的区别

两者用的是**同一套手段**（都是"给某级配一个属"），区别在**它有没有被确认**：

| | 副属和弦 | 转调 |
|---|---|---|
| 目标级被强调多久 | 一到两个和弦 | 一整段 |
| 新调号 | 不出现 | 常出现 |
| 听感 | 色彩变化 | 中心转移 |

所以副属和弦是**离调**（见 [[concept:tonicization|离调]]）最常用的手段。

## 图示：指向与解决

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">在 C 大调的框架里，临时给 D 配一个属和弦</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#E8C547">A</text><text x="0" y="24" fill="#E8C547">C♯</text><text x="0" y="48" fill="#E8C547">E</text>
      <text x="150" y="0" fill="#5B7FA8">D</text><text x="150" y="24" fill="#5B7FA8">F</text><text x="150" y="48" fill="#5B7FA8">A</text>
      <text x="300" y="0" fill="#E07A3F">G</text><text x="300" y="24" fill="#E07A3F">B</text><text x="300" y="48" fill="#E07A3F">D</text>
      <text x="450" y="0" fill="#5B7FA8">C</text><text x="450" y="24" fill="#5B7FA8">E</text><text x="450" y="48" fill="#5B7FA8">G</text>
    </g>
    <g stroke="#343439" stroke-width="1.2" fill="none">
      <line x1="14" y1="0" x2="136" y2="0"/><polygon points="136,-5 146,0 136,5" fill="#343439" stroke="none"/>
      <line x1="164" y1="0" x2="286" y2="0"/><polygon points="286,-5 296,0 286,5" fill="#343439" stroke="none"/>
      <line x1="314" y1="0" x2="436" y2="0"/><polygon points="436,-5 446,0 436,5" fill="#343439" stroke="none"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="0" y="68" text-anchor="middle">V/V（A 大三）</text>
      <text x="150" y="68" text-anchor="middle">V（D 大三）</text>
      <text x="300" y="68" text-anchor="middle">I（G 大三 · 临时中心）</text>
      <text x="450" y="68" text-anchor="middle">回到 C 大调的 I</text>
    </g>
    <g stroke="#C0504A" stroke-width="1.2">
      <line x1="4" y1="24" x2="4" y2="0"/>
    </g>
    <text x="14" y="-14" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">C♯ 是原调没有的音 → 一处变化音</text>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      整段仍然待在 C 大调里 —— 只是中间"借"了 G 大调的中心一下
    </text>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      判断是离调还是转调：看这个临时中心被强调多久（一两个和弦 = 离调）
    </text>
  </g>
</svg>
```

## 听一听：副属和弦的色彩

用进行播放器对比两条：**I → V → I**（全在原调内）与 **I → V/V → V → I**（中途借了 D 的属）。
后者的"亮一下"就是副属和弦的效果。

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I"],"label":"原调内：I → V → I","label_en":"All diatonic: I-V-I","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","V","I"],"label":"副属走向：I → V/V → V → I","label_en":"With a secondary dominant: I-V/V-V-I","hint":"与上一条对比：中途多出的那个和弦带来色彩变化","hint_en":"Compare with the item above — the extra chord supplies the change of colour"}
```

## 常见误解

- **「副属和弦就是转调」** → 它只是**离调**：借一下中心，随即回来。区别在时长与是否建立新调号。
- **「V/IV 一定带来变化音」** → V/IV 与 I 是同一个和弦，不产生效果；要用 **V7/IV**（含降七音）才有效。
- **「副属和弦可以任意指向任何级」** → 原则上可以，但实际最常用的是指向 **ii、V、vi**；指向 vii° 与 III 的效果很弱或容易听成转调。
- **「副属和弦必须解决」** → 传统写作里通常解决到目标级；也可以不解决而用作色彩，但那样就失去了"指向"的作用。
:::

::: en
The idea behind a secondary dominant is simple: **if a dominant can point at the tonic, it can point at any other
degree too.**

> In C major the tonic is C. So "**the dominant of D**" (A–C♯–E) can point at the D minor area — and that A chord
> is written **V/V** ("five of five"), a **secondary dominant**.

The note it introduces (C♯) **is not in the C major scale**, so a secondary dominant is always an accidental, and
always a **point of colour change**.

## The common set

| Symbol | Points at | Chord in C major | New note |
|---|---|---|---|
| **V/ii** | degree 2 | A major (A–C♯–E) | C♯ |
| **V/IV** | degree 4 | C major — which is simply I, so no effect | none |
| **V/V** | degree 5 | D major (D–F♯–A) | F♯ |
| **V/vi** | degree 6 | E major (E–G♯–B) | G♯ |

Note the second row: **V/IV is the same chord as I**, so it produces no secondary-dominant effect. To point at the
subdominant you need **V7/IV** (C dominant seventh: C–E–G–B♭), where the B♭ is the new note.

## Where it resolves

A secondary dominant's target is the degree it points at, and it normally resolves onto that degree:

> V/V → V (D major → G major)
> V/vi → vi (E major → A minor)

If the target is a minor triad (ii or vi), the **raised note** in the secondary dominant acts as a temporary
leading tone and rises a semitone into the target — exactly the same shape as a real dominant to tonic, simply
localised.

## How it differs from modulation

Both use **the same device** — giving a degree its own dominant. The difference is whether it **gets confirmed**:

| | Secondary dominant | Modulation |
|---|---|---|
| How long the target is emphasised | one or two chords | a whole passage |
| New key signature | does not appear | usually appears |
| Impression | a change of colour | a change of centre |

So the secondary dominant is the commonest means of **tonicization** (see [[concept:tonicization|tonicization]]).

## Diagram: pointing and resolving

```svg
<svg viewBox="0 0 640 196" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Inside C major, D is given a temporary dominant</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#E8C547">A</text><text x="0" y="24" fill="#E8C547">C♯</text><text x="0" y="48" fill="#E8C547">E</text>
      <text x="150" y="0" fill="#5B7FA8">D</text><text x="150" y="24" fill="#5B7FA8">F</text><text x="150" y="48" fill="#5B7FA8">A</text>
      <text x="300" y="0" fill="#E07A3F">G</text><text x="300" y="24" fill="#E07A3F">B</text><text x="300" y="48" fill="#E07A3F">D</text>
      <text x="450" y="0" fill="#5B7FA8">C</text><text x="450" y="24" fill="#5B7FA8">E</text><text x="450" y="48" fill="#5B7FA8">G</text>
    </g>
    <g stroke="#343439" stroke-width="1.2" fill="none">
      <line x1="14" y1="0" x2="136" y2="0"/><polygon points="136,-5 146,0 136,5" fill="#343439" stroke="none"/>
      <line x1="164" y1="0" x2="286" y2="0"/><polygon points="286,-5 296,0 286,5" fill="#343439" stroke="none"/>
      <line x1="314" y1="0" x2="436" y2="0"/><polygon points="436,-5 446,0 436,5" fill="#343439" stroke="none"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="0" y="68" text-anchor="middle">V/V (A major)</text>
      <text x="150" y="68" text-anchor="middle">V (D major)</text>
      <text x="300" y="68" text-anchor="middle">I of G — a temporary centre</text>
      <text x="450" y="68" text-anchor="middle">back to I of C major</text>
    </g>
    <g stroke="#C0504A" stroke-width="1.2">
      <line x1="4" y1="24" x2="4" y2="0"/>
    </g>
    <text x="14" y="-14" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">C♯ is outside the key — an accidental</text>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The passage stays in C major throughout — it merely borrows the centre of G for a moment
    </text>
    <text x="0" y="120" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Tonicization or modulation? Check how long the temporary centre is emphasised
    </text>
  </g>
</svg>
```

## Listen: the colour of a secondary dominant

Compare two progressions: **I → V → I** (entirely diatonic) and **I → V/V → V → I** (borrowing D's dominant). The
brightening in the second is the secondary dominant at work.

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","I"],"label":"原调内：I → V → I","label_en":"All diatonic: I-V-I","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["I","V","V","I"],"label":"副属走向：I → V/V → V → I","label_en":"With a secondary dominant: I-V/V-V-I","hint":"与上一条对比：中途多出的那个和弦带来色彩变化","hint_en":"Compare with the item above — the extra chord supplies the change of colour"}
```

## Common misconceptions

- **"A secondary dominant is a modulation."** It is **tonicization**: the centre is borrowed and returned. The difference is duration and whether a new signature appears.
- **"V/IV always brings an accidental."** V/IV is the same chord as I and has no effect; **V7/IV** (with the lowered seventh) is what works.
- **"It can point at any degree equally well."** In principle yes, but in practice ii, V and vi are the common targets; pointing at vii° or III is weak or easily heard as a modulation.
- **"It must resolve."** Traditional writing resolves it onto the target; it can also be left unresolved as colour, but then it loses its pointing function.
:::
