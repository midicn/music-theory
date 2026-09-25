---
id: suspended-chord
site: theo
cat: T4
title: 挂留和弦
title_en: Suspended Chord
summary: 把三音换成二度或四度——大小不明，因而悬而未决
summary_en: Replace the third with a second or a fourth — neither major nor minor, so it hangs
level: standard
tags: [乐理, 和弦, 和声]
tags_en: [theory, chord, harmony]
alias: [挂留和弦, sus4, sus2, 挂四和弦]
order: 34
links:
  - "[[concept:triad]]"
  - "[[concept:major-triad]]"
  - "[[concept:minor-triad]]"
  - "[[concept:non-chord-tone]]"
  - "[[concept:cadence]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：挂留音来自声部延留，在传统和声里是常规写法 | An organ hymn — suspensions arise from a held voice and are routine in traditional writing
  - mutopia-000287 | 巴赫第八首二部创意曲：两声部交错时常出现挂留式的和声，可听它如何被解决 | Bach's eighth two-part invention — the interweaving voices repeatedly produce suspended sonorities, and their resolution is audible
  - giantmidi-006222 | 琶音练习可弹出挂留和弦，用于听它与大小三和弦的差别 | Scale exercises can sound suspended chords, showing how they differ from major and minor triads
sources:
  - 挂留和弦 = 将三和弦的三音替换为二度或四度（sus2 / sus4），属和声学通则
  - 挂留音（suspension）源自对位法中的延留音，挂留和弦是它的和声化结果，为通行表述
updated: 2026-09-24
---

::: zh
挂留和弦只做一件事：**把三和弦的三音换掉**。

> 大三：C–**E**–G　　挂四：C–**F**–G（三音换成四度）
> 　　　　　　　　　挂二：C–**D**–G（三音换成二度）

换掉的这个音恰好是**决定大小调色彩的那个音**（见 [[concept:major-triad|大三和弦]]、
[[concept:minor-triad|小三和弦]]）。所以挂留和弦最要紧的特征是：

> **它既不是大也不是小。**

这带来一种特殊的听感：和弦本身是协和的（纯四度、纯五度都在），
**但缺少"明暗"这条信息，于是悬着** —— 这正是"挂留"（suspended）一词的本义。

## 它来自对位，不是一个"新和弦"

挂留和弦的历史来源是**延留音**：一个声部在前一个和弦里是小音，进入下一个和弦时**没有动**，
于是暂时变成了一个不属于该和弦的音；等到下一步它再落下来，就解决了。

| 阶段 | 状态 | 例 |
|---|---|---|
| 准备 | 该音是前一和弦的和弦音 | 前和弦含 F |
| **挂留** | 该音被"留"住，形成不协和 | C–F–G（F 挂四） |
| 解决 | 该音下行（或上行）落到和弦音 | C–E–G |

所以挂留和弦在传统和声里是**过程性的**：出现即为解决做准备。

## 现代用法

到了流行与爵士，挂留和弦获得了新的身份：**可以独立停留的和弦**。

- **sus4** 常用于段落开头，制造"悬而未决"的开场感；
- **sus2** 听感更空旷（因为二度与根音相撞，但被上方五度撑开）；
- 两者都常用来**推迟**大小色彩的确定，让音乐多悬一会儿。

## 图示：换掉的那个音

```svg
<svg viewBox="0 0 640 188" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">三音是"明暗开关"；把它换掉，和弦就没有明暗了</text>
  </g>

  <g transform="translate(48,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="70" y="0" fill="#E07A3F">E</text><text x="150" y="0" fill="#E07A3F">G</text>
      <text x="260" y="0" fill="#5B7FA8">C</text><text x="330" y="0" fill="#5B7FA8">F</text><text x="410" y="0" fill="#5B7FA8">G</text>
      <text x="520" y="0" fill="#E8C547">C</text><text x="590" y="0" fill="#E8C547">D</text><text x="660" y="0" fill="#E8C547">G</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="26" fill="#E07A3F">大三和弦</text>
      <text x="0" y="44" fill="#6E6A64">三音 = E（明确"大"）</text>
      <text x="260" y="26" fill="#5B7FA8">挂四 sus4</text>
      <text x="260" y="44" fill="#6E6A64">三音 → 四度 F</text>
      <text x="520" y="26" fill="#E8C547">挂二 sus2</text>
      <text x="520" y="44" fill="#6E6A64">三音 → 二度 D</text>
    </g>
    <g stroke="#C0504A" stroke-width="1.2" stroke-dasharray="3 2">
      <line x1="330" y1="8" x2="410" y2="8"/>
      <line x1="590" y1="8" x2="660" y2="8"/>
    </g>
    <text x="0" y="76" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      注意：挂留和弦里仍保留纯五度（C–G）—— 骨架还在，缺的只是"明暗"
    </text>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      传统用法：四度（或二度）下行落到三音 → 解决；现代用法：让"悬着"本身成为效果
    </text>
  </g>
</svg>
```

## 听一听：挂留和弦

先听 sus4，再听 sus2，最后听大三和弦 —— 三者的差别不在协和度，而在"明暗是否确定"。

```audiolab
{"type":"chord","root":"C4","quality":"sus4","inversion":0,"label":"挂四和弦（C–F–G）","label_en":"Suspended fourth (C–F–G)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"sus2","inversion":0,"label":"挂二和弦（C–D–G）","label_en":"Suspended second (C–D–G)","hint":"与挂四对比：空旷感的差别","hint_en":"Compare with sus4 — the openness differs"}
```

## 常见误解

- **「挂留和弦是"没有解决的"和弦」** → 传统和声里它是过程；现代用法里它可以就是终点。
- **「sus4 与 sus2 只是记法不同」** → 换掉的音不同（四度 vs 二度），听感也不同：sus4 更紧、sus2 更空。
- **「挂留和弦是近代发明的」** → 它来自对位法的延留音，几百年前就是常规写法。
- **「挂留和弦仍分大小」** → 不分。三音被换掉之后，大与小这条信息就不存在了 —— 这正是它悬着的原因。
:::

::: en
A suspended chord does one thing only: **it removes the third of a triad.**

> major: C–**E**–G　　 sus4: C–**F**–G (third replaced by the fourth)
> 　　　　　　　　　　 sus2: C–**D**–G (third replaced by the second)

The note removed happens to be **the one that decides major or minor** (see [[concept:major-triad|major triad]]
and [[concept:minor-triad|minor triad]]). So the defining property is:

> **It is neither major nor minor.**

That produces a peculiar effect: the chord itself is consonant (the perfect fourth and fifth are both there),
**but the information about brightness is missing, so it hangs.** That is exactly what "suspended" means.

## It comes from counterpoint, not from a new chord

Historically the suspended chord came from the **suspension**: a voice stays put while the harmony changes, so
it briefly becomes a note foreign to the new chord, and then steps down to resolve.

| Stage | State | Example |
|---|---|---|
| preparation | the note belongs to the previous chord | the previous chord contains F |
| **suspension** | the note is held, creating dissonance | C–F–G (a suspended fourth) |
| resolution | the note steps down (or up) to a chord tone | C–E–G |

So in traditional harmony a suspended chord is **a process**: its appearance prepares its own resolution.

## Modern use

In pop and jazz the suspended chord acquired a new identity: **a chord that may simply stay.**

- **sus4** is commonly used at the start of a section to create anticipation;
- **sus2** sounds more open (the second collides with the root but the fifth above holds it apart);
- both are often used to **postpone** the arrival of major or minor, letting the music hang a while longer.

## Diagram: the note that got replaced

```svg
<svg viewBox="0 0 640 188" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The third is the bright-dark switch; take it away and the chord has no brightness</text>
  </g>

  <g transform="translate(48,52)">
    <g font-family="Georgia,serif" font-size="12" text-anchor="middle">
      <text x="0" y="0" fill="#E07A3F">C</text><text x="70" y="0" fill="#E07A3F">E</text><text x="150" y="0" fill="#E07A3F">G</text>
      <text x="260" y="0" fill="#5B7FA8">C</text><text x="330" y="0" fill="#5B7FA8">F</text><text x="410" y="0" fill="#5B7FA8">G</text>
      <text x="520" y="0" fill="#E8C547">C</text><text x="590" y="0" fill="#E8C547">D</text><text x="660" y="0" fill="#E8C547">G</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="11">
      <text x="0" y="26" fill="#E07A3F">major triad</text>
      <text x="0" y="44" fill="#6E6A64">third = E, clearly major</text>
      <text x="260" y="26" fill="#5B7FA8">sus4</text>
      <text x="260" y="44" fill="#6E6A64">third to the fourth, F</text>
      <text x="520" y="26" fill="#E8C547">sus2</text>
      <text x="520" y="44" fill="#6E6A64">third to the second, D</text>
    </g>
    <g stroke="#C0504A" stroke-width="1.2" stroke-dasharray="3 2">
      <line x1="330" y1="8" x2="410" y2="8"/>
      <line x1="590" y1="8" x2="660" y2="8"/>
    </g>
    <text x="0" y="76" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Note that the perfect fifth (C–G) remains — the frame is intact, only the brightness is missing
    </text>
    <text x="0" y="98" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Traditional: the fourth (or second) steps down to the third to resolve. Modern: hanging becomes the effect
    </text>
  </g>
</svg>
```

## Listen: suspended chords

Hear sus4, then sus2, then the major triad. The difference is not consonance but whether the brightness is
settled.

```audiolab
{"type":"chord","root":"C4","quality":"sus4","inversion":0,"label":"挂四和弦（C–F–G）","label_en":"Suspended fourth (C–F–G)","hint":"整体 / 分解 / 宽排列","hint_en":"Block, arpeggio, open"}
```

```audiolab
{"type":"chord","root":"C4","quality":"sus2","inversion":0,"label":"挂二和弦（C–D–G）","label_en":"Suspended second (C–D–G)","hint":"与挂四对比：空旷感的差别","hint_en":"Compare with sus4 — the openness differs"}
```

## Common misconceptions

- **"A suspended chord is an unresolved chord."** Traditional writing treats it as a process; modern writing lets it be the destination.
- **"sus4 and sus2 differ only in notation."** A different note is replaced (fourth versus second) and the sound differs: sus4 tighter, sus2 more open.
- **"Suspended chords are a modern invention."** They come from contrapuntal suspensions and have been standard for centuries.
- **"A suspended chord is still major or minor."** It is neither. Once the third is gone, major and minor no longer exist — which is precisely why it hangs.
:::
