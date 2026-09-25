---
id: contrapuntal-devices
site: theo
cat: T6
title: 对位变形手法
title_en: Contrapuntal Devices
summary: 倒影、逆行、扩大、缩小——同一素材的四种变形，只改一个维度
summary_en: Mirror, retrograde, augmentation, diminution — four transformations that each change one dimension
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [对位变形手法, 倒影, 逆行, 扩大, 缩小, contrapuntal devices]
order: 28
links:
  - "[[concept:imitation]]"
  - "[[concept:canon]]"
  - "[[concept:fugue]]"
  - "[[concept:interval-inversion]]"
  - "[[concept:motive]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：主题以不同形态反复出现，可听到素材被"改造"的过程 | Bach's first two-part invention — the subject returns in altered forms, showing the material being worked on
  - mutopia-000287 | 巴赫第八首二部创意曲：与上一条对照同一批变形手法在另一主题上的处理 | Bach's eighth two-part invention — the same devices applied to a different subject
  - atepp-002452 | 巴赫《哥德堡变奏曲》第 12 变奏：明确标为 Canon，是变形手法在整段结构中的用法 | Bach's Goldberg Variations, Variation 12, marked Canon — these devices at work across a whole section
sources:
  - 对位变形手法（倒影 / 逆行 / 扩大 / 缩小）各自的定义与保持音程结构的性质，属对位学通则
  - 四种形态在十二音技法中构成"原型—倒影—逆行—逆行倒影"关系，为通行现代作曲技法表述
updated: 2026-09-24
---

::: zh
变形手法的思路是：**不写新素材，而是把已有的素材"改一个维度"。**

| 手法 | 改哪个维度 | 做法 |
|---|---|---|
| **倒影** | **方向** | 上行变下行，下行变上行（音程宽度保持不变） |
| **逆行** | **时间顺序** | 从最后一个音走回第一个音 |
| **扩大** | **速度** | 每个音的时值加倍（听起来慢一倍） |
| **缩小** | **速度** | 每个音的时值减半（听起来快一倍） |

四者有一个共同点，也是它们能在复调里成立的原因：

> **音程结构不变。** 改的只是方向、顺序或速度 ——
> 所以听者仍然认得出"这是同一个素材"。

**这正是复调"经济性"的极致**：素材写了一次，却能产生四种听起来不同、却同源的东西。

## 倒影：与音程转位是同一件事的另一面

倒影保持音程的**宽度**、反转它的**方向**。这与 [[concept:interval-inversion|音程转位]] 是同一套逻辑
（都关心"距离与方向"），只是作用对象不同：一个作用在两个音之间，一个作用在整条旋律上。

倒影会让调式发生变化（大调片段倒影后可能变成小调味道），所以实际写作时常需要调整个别音来适应和声。

## 逆行：最难的一种

逆行的规则最简单，做起来最难：

> **旋律倒着走时，和声也倒着走了。**

而和声进行是**有方向**的（属→主有效，主→属没效果）。所以严格逆行经常会产出怪异的和声，
实际作品里通常**只逆行短小片段**，或做局部调整。

这也是一个很好的提醒：**对位手法的难度不只来自"音符能不能对上"，还来自"和声方向是否还说得通"。**

## 扩大与缩小：改变时间尺度

| 手法 | 效果 | 常见用法 |
|---|---|---|
| **扩大** | 素材变成"慢动作"，其他声部照常流动 | 常用于**结尾**：素材以庄严的形态最后一次出现 |
| **缩小** | 素材变密，节奏加快 | 常用于**推进段**：把进入压紧，制造紧迫感 |

巴赫《哥德堡变奏曲》与赋格中大量使用这一对，因为它们**不需要新素材就能改变音乐的密度**。

## 与十二音技法的关系

20 世纪勋伯格建立的十二音技法，把变形手法提升为**整套音高组织原则**。
一条序列有四副面孔：

| 形态 | 说明 |
|---|---|
| **原型**（O） | 原始序列 |
| **倒影**（I） | 上下颠倒 |
| **逆行**（R） | 从尾到头 |
| **逆行倒影**（RI） | 两者同时 |

值得注意的是：**这套思路并不是 20 世纪的发明**，而是把复调几百年的变形手法
**系统化、并把它变成"必须使用"的规则**。区别在强制性：巴洛克是"可用的手法"，十二音是"组织的原则"。

## 图示：四种变形

```svg
<svg viewBox="0 0 640 214" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一个素材（上行四音），四种改法：只改方向、顺序或速度</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-30" y="0" text-anchor="end">原型</text>
      <text x="-30" y="34" text-anchor="end">倒影</text>
      <text x="-30" y="68" text-anchor="end">逆行</text>
      <text x="-30" y="102" text-anchor="end">扩大</text>
    </g>
    <g>
      <polyline points="0,0 40,-16 80,-32 120,-48" fill="none" stroke="#E07A3F" stroke-width="2"/>
      <text x="130" y="-44" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">方向：向上</text>

      <polyline points="0,34 40,50 80,66 120,82" fill="none" stroke="#5B7FA8" stroke-width="2"/>
      <text x="130" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">方向：向下（宽度不变）</text>

      <polyline points="0,68 40,84 80,52 120,68" fill="none" stroke="#E8C547" stroke-width="2"/>
      <text x="130" y="72" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">顺序：从尾到头</text>

      <polyline points="0,102 80,70 160,38 240,6" fill="none" stroke="#C0504A" stroke-width="2"/>
      <text x="250" y="10" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">速度：时值加倍（更慢）</text>
    </g>
    <text x="0" y="136" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      共同点：音程结构不变 —— 所以听者仍认得出"这是同一个素材"
    </text>
    <text x="0" y="158" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      逆行最难：旋律倒着走时和声也倒着走，而和声有方向性（属→主有效，反之无效）
    </text>
  </g>
</svg>
```

## 听一听：方向反转的关系

变形手法作用于整条旋律，本站的听辨件放不出多声部的运用。这里用 `interval` 看**倒影的逻辑**：
三度上行（C→E）与三度下行（C→A）在宽度上相同、方向相反 —— 这就是倒影在两个音上的样子。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"原型方向：上行三度","label_en":"Original direction: a rising third","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 A3（低八度）就是下行三度 —— 宽度不变、方向相反，正是倒影的关系。","hint2_en":"Set b to a lower A for a falling third — same width, opposite direction, exactly the mirror relation."}
```

## 常见误解

- **「倒影与音程转位是一回事」** → 逻辑同源但对象不同：音程转位作用在两个音之间，倒影作用在整条旋律上。
- **「逆行只是把谱子倒着抄」** → 技术上是的，但**和声会跟着倒流**，因此通常只用于短片段或需局部调整。
- **「扩大与缩小只是改速度」** → 它们改变的是**音乐的密度**，是结构手段，不是演奏提示。
- **「这些手法是十二音技法发明的」** → 恰恰相反：复调用了几百年，十二音只是把它**变成了必须使用的规则**。
:::

::: en
The idea behind these devices is: **write no new material — change one dimension of what you already have.**

| Device | Dimension changed | Method |
|---|---|---|
| **mirror (inversion)** | **direction** | rising becomes falling and vice versa (interval widths unchanged) |
| **retrograde** | **order in time** | walk from the last note back to the first |
| **augmentation** | **speed** | double every note value (sounds half as fast) |
| **diminution** | **speed** | halve every note value (sounds twice as fast) |

All four share one property, and it is what makes them usable in polyphony:

> **The interval structure is unchanged.** Only direction, order or speed moves —
> so the ear still recognises "this is the same material".

**This is polyphonic economy at its extreme**: write the material once and get four things that sound different
yet come from one source.

## Mirror: the other face of interval inversion

Mirror keeps an interval's **width** and reverses its **direction**. That is the same logic as
[[concept:interval-inversion|interval inversion]] — both concern distance and direction — applied to a different
object: one works between two notes, the other across a whole melody.

Mirroring changes the mode (a major passage may come out with a minor flavour), so individual notes often need
adjusting to fit the harmony.

## Retrograde: the hardest of the four

Its rule is the simplest and its execution the hardest:

> **When the melody runs backwards, so does the harmony.**

And harmony has **direction** (dominant to tonic works; tonic to dominant does not). So strict retrograde often
produces strange harmony, and in practice it is applied to **short passages**, or adjusted locally.

It is a useful reminder: **the difficulty of a contrapuntal device is not only whether the notes fit, but whether
the harmonic direction still makes sense.**

## Augmentation and diminution: changing the time scale

| Device | Effect | Typical use |
|---|---|---|
| **augmentation** | the material becomes slow motion while other voices flow normally | often at a **close**: the material appears one last time in solemn form |
| **diminution** | the material becomes dense and faster | often at a **build-up**: entries squeezed tighter for urgency |

Bach uses this pair heavily in the Goldberg Variations and the fugues, because they **change the density of the
music without new material**.

## Its relation to twelve-tone technique

The twelve-tone method Schoenberg established in the twentieth century raised these devices into **a complete
principle of pitch organisation**. A row has four faces:

| Form | Description |
|---|---|
| **prime** (O) | the original row |
| **inversion** (I) | turned upside down |
| **retrograde** (R) | back to front |
| **retrograde inversion** (RI) | both at once |

Worth noting: **this is not a twentieth-century invention** but the systematisation of devices polyphony had used
for centuries — and then made compulsory. The difference is obligation: in the Baroque they were available
devices; in twelve-tone writing they are the organising principle.

## Diagram: four transformations

```svg
<svg viewBox="0 0 640 214" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One figure (four rising notes), four treatments: only direction, order or speed changes</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="-30" y="0" text-anchor="end">prime</text>
      <text x="-30" y="34" text-anchor="end">mirror</text>
      <text x="-30" y="68" text-anchor="end">retrograde</text>
      <text x="-30" y="102" text-anchor="end">augmented</text>
    </g>
    <g>
      <polyline points="0,0 40,-16 80,-32 120,-48" fill="none" stroke="#E07A3F" stroke-width="2"/>
      <text x="130" y="-44" font-family="system-ui,sans-serif" font-size="10.5" fill="#E07A3F">direction: rising</text>

      <polyline points="0,34 40,50 80,66 120,82" fill="none" stroke="#5B7FA8" stroke-width="2"/>
      <text x="130" y="86" font-family="system-ui,sans-serif" font-size="10.5" fill="#5B7FA8">direction: falling, same widths</text>

      <polyline points="0,68 40,84 80,52 120,68" fill="none" stroke="#E8C547" stroke-width="2"/>
      <text x="130" y="72" font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547">order: last note first</text>

      <polyline points="0,102 80,70 160,38 240,6" fill="none" stroke="#C0504A" stroke-width="2"/>
      <text x="250" y="10" font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A">speed: note values doubled (slower)</text>
    </g>
    <text x="0" y="136" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Shared property: the interval structure is unchanged, so the ear still recognises the material
    </text>
    <text x="0" y="158" font-family="system-ui,sans-serif" font-size="11" fill="#C0504A">
      Retrograde is hardest: the harmony runs backwards too, and harmony has direction
    </text>
  </g>
</svg>
```

## Listen: the logic of mirroring in two notes

These devices act on whole melodies and their polyphonic use cannot be played here. Use `interval` to see **the
logic of mirroring**: a rising third (C–E) and a falling third (C down to A) share a width and reverse the
direction — mirroring, reduced to two notes.

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"原型方向：上行三度","label_en":"Original direction: a rising third","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成低八度的 A 就是下行三度 —— 宽度不变、方向相反，正是倒影的关系。","hint2_en":"Set b to a lower A for a falling third — same width, opposite direction, exactly the mirror relation."}
```

## Common misconceptions

- **"Mirror and interval inversion are the same."** Related logic, different objects: interval inversion acts
  between two notes, mirroring acts across a melody.
- **"Retrograde is just copying the page backwards."** Technically yes, but **the harmony runs backwards with
  it**, so it is usually confined to short passages or adjusted locally.
- **"Augmentation and diminution only change speed."** They change the **density of the music** — a structural
  device, not a performance instruction.
- **"Twelve-tone technique invented these devices."** The reverse: polyphony used them for centuries, and
  twelve-tone writing made them compulsory.
:::
