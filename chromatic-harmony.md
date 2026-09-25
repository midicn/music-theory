---
id: chromatic-harmony
site: theo
cat: T5
title: 半音化和声
title_en: Chromatic Harmony
summary: 当每个半音都能被说成"某个调的导音"，调性中心就开始松动了
summary_en: When every semitone can be read as somebody's leading tone, the tonal centre starts to slip
level: standard
tags: [乐理, 和声, 调性]
tags_en: [theory, harmony, tonality]
alias: [半音化和声, 半音化, chromatic harmony]
order: 38
links:
  - "[[concept:chromatic]]"
  - "[[concept:secondary-dominant]]"
  - "[[concept:modulation]]"
  - "[[concept:enharmonic]]"
  - "[[concept:diminished-seventh]]"
instances:
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：半音化和声贯穿全曲，调性被不断牵引，是这一手法的集中展示 | Liszt's transcription of Danse macabre — chromatic harmony runs throughout, pulling the tonality about
  - atepp-000195 | 德彪西《月光》：半音化的和声不再服务于"走向某个调"，而是作为色彩本身存在 | Debussy's Clair de lune — chromatic harmony serves not as a route to a key but as colour in itself
  - cyberhymnal-000695 | 管风琴圣咏作对照：传统写法中变化音稀少而克制，与上述两条形成鲜明差异 | An organ hymn as a control — accidentals are rare and restrained in traditional writing, a sharp contrast
sources:
  - 半音化和声指变化音成为和声的常规材料（副属、半音经过和弦、增六和弦、等音重解等），属和声学通则
  - 半音化的累积与调性中心的弱化、最终走向无调性的历史线索，为音乐史通行记载
updated: 2026-09-24
---

::: zh
半音化和声不是"用了变化音"，而是**变化音成了和声的常规材料** ——
它从装饰变成了结构的一部分。

差别可以这么看：

| | 调内和声 | 半音化和声 |
|---|---|---|
| 变化音的身份 | 例外、装饰 | **常规素材** |
| 和声来源 | 音阶内叠三度 | 音阶外借入、重解、叠加 |
| 中心 | 稳定清晰 | **被不断牵引** |

## 它为什么有那么大的破坏力

这是本条最值得理解的一点。机制只有一句话：

> **十二个半音里的任何一个，都可以被解释成"某个调的导音"。**

所以每一个半音都可能意味着"指向某处"。当它们密集出现时，
听觉就会**不断被推向不同的方向** —— 中心不是被打倒的，是被**拉扯到失去重心**的。

这也解释了为什么半音化的历史终点是无调性：**不是有人突然宣布废除调性，
而是半音化用到极致后，中心自己站不住了。**

## 四种常见手段

| 手段 | 做法 | 效果 |
|---|---|---|
| **副属和弦** | 给某一级临时配属（见 [[concept:secondary-dominant|副属和弦]]） | 短暂指向别的级 |
| **半音经过和弦** | 两个和弦之间插入半音化的过渡和弦 | 平滑但持续的位移 |
| **增六和弦** | 含增六度的变化和弦（其增六度向外扩张到八度） | 强烈指向属和弦 |
| **等音重解** | 把减七、增三等**对称结构**换个写法（见 [[concept:enharmonic|等音]]、[[concept:diminished-seventh|减七和弦]]） | 一次换一个调，最突然 |

第四种最"危险"：因为对称结构没有唯一的根音，**解释方向一换，调就换了**。

## 它不等于无调性

这里要说清一个常见混淆：**半音化和声仍然可以是调性的。**
瓦格纳的《特里斯坦》半音化程度极高，但音乐仍有中心、仍有解决（只是被极度推迟）。

| | 半音化和声 | 无调性 |
|---|---|---|
| 有没有中心 | **有**，但被拉扯、被推迟 | 有意取消 |
| 是否仍用属→主 | 用，只是绕得更远 | 不用 |
| 和声的功能性 | 仍成立 | 不再成立 |

一句话：**半音化是把调性拉到极限，无调性是放弃调性。**

## 图示：中心被拉扯的过程

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">变化音越密，指向的方向越多，中心就越不稳</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="0">调内和声</text>
      <text x="0" y="46">半音化初期</text>
      <text x="0" y="92">半音化后期</text>
      <text x="0" y="138">无调性</text>
    </g>

    <g>
      <circle cx="200" cy="-6" r="0" fill="none"/>
      <circle cx="200" cy="-6" r="9" fill="#5B7FA8"/>
      <text x="222" y="-2" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">中心明确，指向单一</text>

      <circle cx="200" cy="40" r="9" fill="#E8C547"/>
      <g stroke="#E8C547" stroke-width="1.2">
        <line x1="212" y1="36" x2="262" y2="24"/><line x1="212" y1="44" x2="262" y2="56"/>
      </g>
      <text x="270" y="32" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">开始指向别的级</text>

      <circle cx="200" cy="86" r="9" fill="#E07A3F"/>
      <g stroke="#E07A3F" stroke-width="1.2">
        <line x1="212" y1="80" x2="266" y2="62"/><line x1="212" y1="90" x2="266" y2="90"/>
        <line x1="212" y1="82" x2="262" y2="108"/><line x1="212" y1="94" x2="258" y2="122"/>
      </g>
      <text x="274" y="76" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">指向四面，中心被拉扯</text>

      <circle cx="200" cy="132" r="9" fill="#C0504A" opacity=".5"/>
      <path d="M192,132 L208,132" stroke="#C0504A" stroke-width="1.6"/>
      <text x="222" y="136" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">中心被有意取消</text>
    </g>
    <text x="0" y="168" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      关键：十二个半音里任何一个都能被当作"某调的导音" —— 所以每个半音都是一次指向
    </text>
  </g>
</svg>
```

## 听一听：半音化的牵引感

先听一段完全调内的进行（中心稳固），再想象同样的功能骨架里插入多个副属与半音经过和弦 ——
差别不在于"多了几个音"，而在于**你的耳朵每次都不知道下一个会去哪**。

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"调内和声（中心稳固）","label_en":"Diatonic harmony, a firm centre","hint":"逐个和弦依次听，留意每次落点是否可预期","hint_en":"Hear each chord in turn and notice whether each arrival is predictable"}
```

## 常见误解

- **「半音化和声就是无调性」** → 不是。半音化**仍有中心**，只是被拉扯、被推迟；无调性是主动取消中心。
- **「变化音用得多就是半音化」** → 关键在**身份**：作为装饰的偶发变化音不是半音化和声，只有成了常规和声材料才是。
- **「半音化是近代才有」** → 文艺复兴末期已有（如杰苏阿尔多），巴赫的半音阶幻想曲也很极端；近代的是**密度与系统化**。
- **「半音化听起来一定刺耳」** → 德彪西恰恰相反 —— 同样是半音材料，可以做成柔和的色彩，取决于和声的构成方式。
:::

::: en
Chromatic harmony is not "using accidentals". It is **accidentals becoming the ordinary material of harmony** —
moving from decoration to structure.

| | Diatonic harmony | Chromatic harmony |
|---|---|---|
| Status of accidentals | exception, decoration | **standard material** |
| Source of chords | thirds stacked within the scale | borrowed, reinterpreted, piled up from outside it |
| Centre | stable and clear | **constantly pulled about** |

## Why it is so corrosive

This is the part worth grasping, and it reduces to one sentence:

> **Any of the twelve semitones can be read as "some key's leading tone".**

So every semitone can mean "pointing somewhere". When they come thick and fast, the ear is **pushed in one
direction after another** — the centre is not knocked down, it is **pulled until it loses its balance**.

That also explains where chromaticism historically ends: **nobody abruptly abolished tonality; the centre simply
could not hold once chromaticism was taken to its limit.**

## Four common devices

| Device | Method | Effect |
|---|---|---|
| **secondary dominant** | give a degree its own dominant (see [[concept:secondary-dominant|secondary dominant]]) | brief pointing elsewhere |
| **chromatic passing chord** | insert a chromatic connector between two chords | smooth but continuous drift |
| **augmented sixth** | a chromatic chord containing an augmented sixth, which expands outward to an octave | strongly points at the dominant |
| **enharmonic reinterpretation** | respell a **symmetrical** structure such as a diminished seventh or augmented triad (see [[concept:enharmonic|enharmonic]], [[concept:diminished-seventh|diminished seventh]]) | the most abrupt: a key change in one move |

The fourth is the most destabilising: a symmetrical structure has no single root, so **change the interpretation
and you change the key**.

## It is not the same as atonality

One confusion worth clearing up: **chromatic harmony can still be tonal.** Wagner's Tristan is intensely
chromatic, yet it still has centres and still resolves — just extremely delayed.

| | Chromatic harmony | Atonality |
|---|---|---|
| Is there a centre? | **yes**, but stretched and postponed | deliberately abolished |
| Is dominant to tonic still used? | yes, only by a longer route | no |
| Does harmonic function still work? | yes | no |

In one line: **chromaticism stretches tonality to its limit; atonality abandons it.**

## Diagram: the centre being pulled

```svg
<svg viewBox="0 0 640 204" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The denser the accidentals, the more directions they point, and the less stable the centre</text>
  </g>

  <g transform="translate(56,56)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="0">diatonic</text>
      <text x="0" y="46">early chromatic</text>
      <text x="0" y="92">late chromatic</text>
      <text x="0" y="138">atonal</text>
    </g>

    <g>
      <circle cx="200" cy="-6" r="9" fill="#5B7FA8"/>
      <text x="222" y="-2" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">a clear centre, one direction</text>

      <circle cx="200" cy="40" r="9" fill="#E8C547"/>
      <g stroke="#E8C547" stroke-width="1.2">
        <line x1="212" y1="36" x2="262" y2="24"/><line x1="212" y1="44" x2="262" y2="56"/>
      </g>
      <text x="270" y="32" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">begins pointing elsewhere</text>

      <circle cx="200" cy="86" r="9" fill="#E07A3F"/>
      <g stroke="#E07A3F" stroke-width="1.2">
        <line x1="212" y1="80" x2="266" y2="62"/><line x1="212" y1="90" x2="266" y2="90"/>
        <line x1="212" y1="82" x2="262" y2="108"/><line x1="212" y1="94" x2="258" y2="122"/>
      </g>
      <text x="274" y="76" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">many directions, the centre is stretched</text>

      <circle cx="200" cy="132" r="9" fill="#C0504A" opacity=".5"/>
      <path d="M192,132 L208,132" stroke="#C0504A" stroke-width="1.6"/>
      <text x="222" y="136" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">the centre is deliberately removed</text>
    </g>
    <text x="0" y="168" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Key point: any of the twelve semitones can serve as one key's leading tone, so every one of them points somewhere
    </text>
  </g>
</svg>
```

## Listen: the pull of chromaticism

Hear a fully diatonic progression first (a firm centre), then imagine the same functional skeleton with several
secondary dominants and chromatic passing chords inserted. The difference is not "a few extra notes" but that
**your ear stops being able to predict where the next arrival will be.**

```audiolab
{"type":"progression","key":"C4","degrees":["I","IV","V","I"],"label":"调内和声（中心稳固）","label_en":"Diatonic harmony, a firm centre","hint":"逐个和弦依次听，留意每次落点是否可预期","hint_en":"Hear each chord in turn and notice whether each arrival is predictable"}
```

## Common misconceptions

- **"Chromatic harmony means atonality."** It does not. Chromatic writing **still has a centre**, only stretched
  and delayed; atonality abolishes the centre on purpose.
- **"Lots of accidentals means chromatic harmony."** What matters is **status**: an occasional decorative
  accidental is not chromatic harmony; it becomes so only when accidentals are ordinary harmonic material.
- **"Chromaticism is modern."** It appears at the end of the Renaissance (Gesualdo) and Bach's Chromatic Fantasia
  is extreme; what is modern is its **density and systematisation**.
- **"Chromaticism must sound harsh."** Debussy shows the opposite — the same chromatic material can be made into
  soft colour, depending on how the chords are built.
:::
