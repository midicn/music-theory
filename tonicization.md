---
id: tonicization
site: theo
cat: T5
title: 离调
title_en: Tonicization
summary: 临时把某个级当成主音——借一下中心，随即归还
summary_en: Treat another degree as the tonic for a moment — borrow a centre, then hand it back
level: standard
tags: [乐理, 和声, 调性]
tags_en: [theory, harmony, tonality]
alias: [离调, 临时中心, tonicization]
order: 26
links:
  - "[[concept:secondary-dominant]]"
  - "[[concept:modulation]]"
  - "[[concept:tonal-center]]"
  - "[[concept:chromatic-harmony]]"
  - "[[concept:harmonic-function]]"
instances:
  - atepp-000318 | a 小调奏鸣曲：内声部的临时强调让局部短暂"换中心"，但整段仍属于原调 | A sonata in A minor — local emphases briefly shift the centre while the passage stays in the original key
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：密集的临时中心让调性感不断被扰动，是离调的高级用法 | Liszt's transcription of Danse macabre — dense temporary centres keep disturbing the sense of key, tonicization at an advanced level
  - cyberhymnal-000695 | 管风琴圣咏作对照：传统写法里离调克制且有准备，几乎都出现在句子的中间部分 | An organ hymn as a control — traditional writing tonicizes sparingly and with preparation, almost always mid-phrase
sources:
  - 离调指某一级被短暂处理成临时主音，与转调以是否真正建立新中心区分，属和声学通则
  - 副属和弦与临时导音是造成离调的主要手段，为通行和声学表述
updated: 2026-09-24
---

::: zh
离调可以理解为"**借用一下别人的家**"：把某个级数临时当成主音来强调，
但不会住下来 —— 很快又回到原来的中心。

## 它的手段与转调完全一样

这点常让人困惑：离调和转调用的是**同一套工具**（[[concept:secondary-dominant|副属和弦]]、
临时导音、共同和弦）。区别**不在怎么走，而在走到哪一步**：

| | 离调 | 转调 |
|---|---|---|
| 临时中心持续 | **一到两个和弦** | 一整段 |
| 有没有新调号 | 没有 | 常有 |
| 临时中心是否被"确认" | 不确认（没有完整的属→主） | 被确认 |
| 回到原调 | 立刻 | 需要另一次转调 |

一句话：**离调是"路过"，转调是"搬家"。**

## 怎么识别

遇到一段音乐，判断它是不是离调，按三个问题依次问：

1. **变化音出现了吗？** 有，说明可能在指向别的级；
2. **它解决到哪里？** 落到哪个和弦上，那个和弦就是"临时中心"；
3. **接下来呢？** 如果立刻回到原调的逻辑（原调的音阶、原调的终止式），就是离调。

第三条是关键。**只要没有建立完整的属→主关系，就还只是路过。**

## 它在写作里的用处

| 用处 | 说明 |
|---|---|
| **延长乐句** | 在句子的中间借一下别的中心，避免一直待在原调显得单调 |
| **制造色彩** | 变化音带来的"亮一下"，比转调轻，比不变好 |
| **准备转调** | 连续几次离调指向同一方向，最后真正转过去（离调 → 转调的连续过渡） |

第三行是常见手法：**转调往往不是一步到位，而是先离调几次"试水"**。

## 图示：路过与搬家

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">相同的手段，不同的结果 —— 区别只在"停多久"</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="0">离调</text>
      <text x="0" y="96">转调</text>
    </g>

    <g>
      <line x1="60" y1="-4" x2="500" y2="-4" stroke="#343439" stroke-width="1.2"/>
      <rect x="60" y="-10" width="60" height="12" rx="2" fill="#5B7FA8"/>
      <rect x="120" y="-10" width="40" height="12" rx="2" fill="#E8C547"/>
      <rect x="160" y="-10" width="340" height="12" rx="2" fill="#5B7FA8"/>
      <text x="130" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="middle">借一下</text>
      <text x="330" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">仍在原调</text>
    </g>

    <g transform="translate(0,100)">
      <line x1="60" y1="-4" x2="500" y2="-4" stroke="#343439" stroke-width="1.2"/>
      <rect x="60" y="-10" width="140" height="12" rx="2" fill="#5B7FA8"/>
      <rect x="200" y="-10" width="300" height="12" rx="2" fill="#E07A3F"/>
      <text x="130" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">原调</text>
      <text x="350" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">新调（建立起新的中心）</text>
    </g>

    <text x="0" y="152" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      判断标准只有一条：临时中心有没有被"确认"（完整的属→主）
    </text>
    <text x="0" y="174" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      转调常常先离调几次试水，再真正转过去 —— 是连续过渡，不是一步到位
    </text>
  </g>
</svg>
```

## 听一听：离调的色彩

用进行播放器对比两条：**I → vi → IV → V → I**（全在原调）与
**I → V/vi → vi → IV → V → I**（中途把 vi 临时当了一次中心）。

```audiolab
{"type":"progression","key":"C4","degrees":["I","vi","IV","V","I"],"label":"原调内：I → vi → IV → V → I","label_en":"All diatonic: I-vi-IV-V-I","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["I","iii","vi","IV","V","I"],"label":"离调色彩：III 级借着用一下","label_en":"With tonicization: the mediant borrowed briefly","hint":"与上一条对比：中途多出的和弦带来短暂的“另一处中心”","hint_en":"Compare with the item above — the extra chord suggests another centre for a moment"}
```

## 常见误解

- **「离调就是小型转调」** → 手段相同，但**没有建立新中心**。这不是"规模小"，而是"性质不同"。
- **「离调一定要用副属和弦」** → 副属是最常用的手段，但共同和弦、临时导音也可以造成离调。
- **「离调越多越好」** → 传统写法里它克制且有准备；过度使用会让中心听不清（那就接近无调性了）。
- **「离调只出现在中间声部」** → 它常出现在内声部，但旋律与低音同样可以承担。
:::

::: en
Tonicization is best understood as "**borrowing someone else's home**": a degree is briefly treated as the
tonic, but you do not move in — the music soon returns to the original centre.

## Its devices are identical to modulation

This is where students get confused: tonicization and modulation use **the same toolkit** (a
[[concept:secondary-dominant|secondary dominant]], a temporary leading tone, a common chord). The difference is
**not how you travel but how far you go**:

| | Tonicization | Modulation |
|---|---|---|
| Duration of the temporary centre | **one or two chords** | a whole passage |
| New key signature | none | usually appears |
| Is the temporary centre "confirmed"? | no (no complete dominant to tonic) | yes |
| Return to the original key | immediate | requires a further modulation |

In one line: **tonicization passes through; modulation moves house.**

## How to recognise it

Faced with a passage, ask three questions in order:

1. **Are there accidentals?** If so, they may be pointing at another degree;
2. **Where do they resolve?** The chord they land on is the temporary centre;
3. **What happens next?** If the music immediately returns to the original key's logic (its scale, its cadences),
   it was tonicization.

The third question is decisive. **Without a complete dominant-to-tonic relationship, no centre has been
established** — the music was merely passing through.

## What it is good for

| Use | Explanation |
|---|---|
| **extending phrases** | borrow another centre mid-phrase so the music is not stuck in one key |
| **colour** | the "brightening" from an accidental is lighter than a modulation, stronger than nothing |
| **preparing a modulation** | several tonicizations pointing one way, then a real move (a continuous transition) |

The third row is a common technique: **modulation rarely happens in one step — composers often tonicize a few
times first, testing the water.**

## Diagram: passing through versus moving house

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same devices, different outcome — the only variable is how long the stay lasts</text>
  </g>

  <g transform="translate(52,56)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="0">tonicization</text>
      <text x="0" y="96">modulation</text>
    </g>

    <g>
      <line x1="60" y1="-4" x2="500" y2="-4" stroke="#343439" stroke-width="1.2"/>
      <rect x="60" y="-10" width="60" height="12" rx="2" fill="#5B7FA8"/>
      <rect x="120" y="-10" width="40" height="12" rx="2" fill="#E8C547"/>
      <rect x="160" y="-10" width="340" height="12" rx="2" fill="#5B7FA8"/>
      <text x="130" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="middle">a brief borrow</text>
      <text x="330" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">still the original key</text>
    </g>

    <g transform="translate(0,100)">
      <line x1="60" y1="-4" x2="500" y2="-4" stroke="#343439" stroke-width="1.2"/>
      <rect x="60" y="-10" width="140" height="12" rx="2" fill="#5B7FA8"/>
      <rect x="200" y="-10" width="300" height="12" rx="2" fill="#E07A3F"/>
      <text x="130" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8" text-anchor="middle">original key</text>
      <text x="350" y="-18" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F" text-anchor="middle">new key, new centre established</text>
    </g>

    <text x="0" y="152" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      One criterion decides it: was the temporary centre confirmed by a complete dominant to tonic?
    </text>
    <text x="0" y="174" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Modulation often arrives gradually, after several tonicizations — a transition, not a jump
    </text>
  </g>
</svg>
```

## Listen: the colour of tonicization

Compare two progressions: **I → vi → IV → V → I** (all diatonic) and **I → iii → vi → IV → V → I** (with the
mediant briefly treated as a centre).

```audiolab
{"type":"progression","key":"C4","degrees":["I","vi","IV","V","I"],"label":"原调内：I → vi → IV → V → I","label_en":"All diatonic: I-vi-IV-V-I","hint":"逐个和弦依次听，最后整体再听一遍","hint_en":"Hear each chord in turn, then the whole thing"}
```

```audiolab
{"type":"progression","key":"C4","degrees":["I","iii","vi","IV","V","I"],"label":"离调色彩：III 级借着用一下","label_en":"With tonicization: the mediant borrowed briefly","hint":"与上一条对比：途中的和弦带来短暂的“另一处中心”","hint_en":"Compare with the item above — the extra chord suggests another centre for a moment"}
```

## Common misconceptions

- **"Tonicization is a small-scale modulation."** The devices match, but **no new centre is established**. It is not smaller; it is different in kind.
- **"Tonicization always uses secondary dominants."** That is the commonest device, but common chords and temporary leading tones also produce it.
- **"The more tonicization the better."** Traditional writing uses it sparingly and with preparation; overuse blurs the centre (which approaches atonality).
- **"It happens only in inner voices."** It appears there often, but melody and bass can carry it too.
:::
