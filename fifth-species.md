---
id: fifth-species
site: theo
cat: T6
title: 第五类对位
title_en: Fifth Species
summary: 华丽对位——前四类混着用，规则最少，判断最难
summary_en: Florid counterpoint — the first four mixed freely, fewest rules, hardest judgement
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [第五类对位, 华丽对位, florid counterpoint]
order: 22
links:
  - "[[concept:fourth-species]]"
  - "[[concept:first-species]]"
  - "[[concept:counterpoint]]"
  - "[[concept:non-chord-tone-treatment]]"
  - "[[concept:cantus-firmus]]"
instances:
  - mutopia-000280 | 巴赫二部创意曲第一首：时值在句内自由变化，正是一音对一音、经过音与延留音混用的形态 | Bach's first two-part invention — note values change freely within the phrase, mixing one-to-one motion, passing notes and suspensions
  - mutopia-000287 | 巴赫第八首二部创意曲：与上一条对照，可听"自由混用"在同一体裁里的另一套处理 | Bach's eighth two-part invention — the same free mixture handled differently within one genre
  - atepp-001875 | 巴赫三声部创意曲 BWV 787：三个声部各自自由变化时值，是华丽对位的三声部形态 | Bach's three-part invention BWV 787 — three voices each changing note values freely, florid counterpoint in three parts
sources:
  - 第五类对位（华丽对位）自由混合前四类的时值形态，属对位学通则
  - 五类对位由简到繁的训练阶梯中，第五类最接近真实作品写作，为通行对位教学表述
updated: 2026-09-24
---

::: zh
第五类对位不再增加新规则，而是**把前四类混在一起自由使用**：

> 同一句里可以有一音对一音、两只手错开的经过音、串状的音型、以及延留音 ——
> 时值随音乐需要变化，没有预设模式。

## 它是阶梯的最后一格，也是"离开阶梯"的第一步

五类对位的设计逻辑到这里显形：

| 类别 | 新增的变量 | 判断点 |
|---|---|---|
| 一 | 无（每步都查） | 每个音 |
| 二 | 弱拍 | 强拍 + 弱拍 |
| 三 | 组内不协和 | 每组首音 |
| 四 | 强拍延留 | 准备—挂留—解决 |
| **五** | **无（自由混合）** | **整体是否像音乐** |

也就是说：**第五类不再教你"检查哪一格"，它要求你回到最初的标准** ——
每条线单独唱像不像旋律（见 [[concept:counterpoint|对位]]）。

## 为什么自由反而更难

因为**没有格子可以依靠了**。前四类里，每个音的位置都由类型决定；第五类里，
"这里该用一个长音还是两个短音"完全由音乐判断决定 —— 而这恰好是最难教的部分。

实际写作时，第五类的取舍通常围绕三件事：

| 判断 | 依据 |
|---|---|
| **哪里该动、哪里该停** | 呼吸：连续音型太久会失去轮廓，长音太久会失去推进 |
| **不协和放在哪** | 强拍上的不协和必须有准备与解决（第四类规则仍然适用） |
| **两个声部是否错开** | 同步换音过多会退回"单音对位"的僵硬感 |

第二行值得强调：**第五类放开了时值，但没有放开"不协和的处理"**。
规则可以混用，纪律不能丢 —— 这也是本类的核心。

## 它离真实作品只有一步

二部创意曲、赋格的主题与对题、室内乐里的两句对话 —— 全都属于第五类的形态。
所以第五类练习做完，就可以直接进入**真实作品的写作与分析了**。

## 图示：时值自由变化，纪律不变

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">时值随需要变化：一音对一音 → 经过音 → 延留 → 音型，但每条纪律都在</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-26" y="6" text-anchor="end">固定</text>
      <text x="-26" y="60" text-anchor="end">对位</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">D</text><text x="160" y="0">E</text><text x="240" y="0">F</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">C</text>
      <text x="60" y="60">D</text><text x="100" y="60">E</text>
      <text x="140" y="60">F</text><text x="180" y="60">G</text>
      <text x="220" y="60">F</text><text x="260" y="60">E</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
      <text x="30" y="82" fill="#5B7FA8">①一音对一音</text>
      <text x="120" y="82" fill="#E8C547">②经过音</text>
      <text x="240" y="82" fill="#C0504A">③延留（需解决）</text>
    </g>
    <g stroke="#C0504A" stroke-width="1.3">
      <line x1="240" y1="46" x2="240" y2="24"/>
      <line x1="266" y1="74" x2="292" y2="70"/>
      <polygon points="292,64 302,70 292,76" fill="#C0504A" stroke="none"/>
    </g>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      第五类放开了时值，但没有放开"不协和的处理" —— 规则可混用，纪律不能丢
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      判断回到最初的标准：每条线单独唱像不像旋律；两个声部是否错开而非同步
    </text>
  </g>
</svg>
```

## 听一听：自由混用的一串音

第五类是两声部练习，本站放不出两声部。这里用 `scale` 听一组**自由变化的音型**：
它展示的是"时值可以自由，但每一步仍需级进、仍需有骨架音"。

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","E4","D4","C4"],"label":"自由音型（级进往返，骨架音清楚）","label_en":"A free figure — stepwise, with clear skeletal notes","hint":"点「上行」/「下行」听骨架音在哪","hint_en":"Try Up and Down and notice where the skeletal notes fall","gap":0.3}
```

## 常见误解

- **「第五类是"什么都行"」** → 时值自由，但处理不协和的纪律（级进、解决）完全不变。
- **「它比前四类简单」** → 规则最少，判断最难：没有格子可依靠，全靠音乐感。
- **「前四类只是练习，第五类才是写作」** → 前四类练的是第五类要用的每一项能力，跳过它们通常写不好。
- **「华丽对位就是装饰很多」** → "华丽"指时值的自由变化，不指音符多。长音与休止同样是它的手段。
:::

::: en
Fifth species adds no new rules; it **mixes the previous four freely**:

> A single phrase may contain note-against-note motion, passing notes offset between the voices, runs of
> figuration, and suspensions — note values change as the music requires, with no preset pattern.

## The last rung of the ladder — and the first step off it

Here the design of the species ladder becomes visible:

| Species | New variable | Point of judgement |
|---|---|---|
| one | none (check every step) | each note |
| two | the weak beat | strong plus weak beats |
| three | dissonance inside a group | each group head |
| four | strong-beat suspension | prepare, suspend, resolve |
| **five** | **none (free mixture)** | **whether the whole sounds like music** |

In other words: **fifth species stops telling you which cell to check and sends you back to the original test** —
does each line work as a melody when sung alone (see [[concept:counterpoint|counterpoint]]).

## Why freedom is harder

Because **there are no longer any cells to lean on**. In the first four species each note's placement is fixed by
the type; in fifth species "should this be one long note or two short ones" is decided purely by musical
judgement — the hardest thing to teach.

In practice the decisions cluster around three questions:

| Decision | Basis |
|---|---|
| **where to move, where to rest** | breathing: figuration sustained too long loses its outline, long notes sustained too long lose momentum |
| **where the dissonances go** | a strong-beat dissonance still needs preparation and resolution (the fourth-species rule still applies) |
| **whether the voices offset** | too much simultaneous change retreats into the stiffness of note-against-note writing |

The second deserves emphasis: **fifth species frees note values, not the treatment of dissonance.** Rules may be
mixed; discipline may not — that is the core of this species.

## One step from real music

Two-part inventions, the subject and countersubject of a fugue, two voices conversing in chamber music — all are
fifth-species shapes. Once fifth-species work is done, you can go straight into **writing and analysing real
pieces**.

## Diagram: note values free, discipline intact

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Values change as needed: one-to-one, passing note, suspension, figuration — discipline unchanged</text>
  </g>

  <g transform="translate(52,54)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-26" y="6" text-anchor="end">cantus</text>
      <text x="-26" y="60" text-anchor="end">counterpoint</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="0">C</text><text x="80" y="0">D</text><text x="160" y="0">E</text><text x="240" y="0">F</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">C</text>
      <text x="60" y="60">D</text><text x="100" y="60">E</text>
      <text x="140" y="60">F</text><text x="180" y="60">G</text>
      <text x="220" y="60">F</text><text x="260" y="60">E</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" text-anchor="middle">
      <text x="30" y="82" fill="#5B7FA8">1 one-to-one</text>
      <text x="120" y="82" fill="#E8C547">2 passing notes</text>
      <text x="240" y="82" fill="#C0504A">3 suspension, must resolve</text>
    </g>
    <g stroke="#C0504A" stroke-width="1.3">
      <line x1="240" y1="46" x2="240" y2="24"/>
      <line x1="266" y1="74" x2="292" y2="70"/>
      <polygon points="292,64 302,70 292,76" fill="#C0504A" stroke="none"/>
    </g>
    <text x="0" y="110" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Fifth species frees note values, not the handling of dissonance — rules may mix, discipline may not
    </text>
    <text x="0" y="132" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      Judgement returns to the original test: does each line sing, and are the voices offset rather than locked
    </text>
  </g>
</svg>
```

## Listen: a freely mixed run

Fifth species is a two-voice exercise and cannot be played here. Use `scale` to hear **a figure of free rhythm**:
it shows that note values may vary freely while every step still moves by step and skeletal notes remain clear.

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","E4","D4","C4"],"label":"自由音型（级进往返，骨架音清楚）","label_en":"A free figure — stepwise, with clear skeletal notes","hint":"点「上行」/「下行」听骨架音在哪","hint_en":"Try Up and Down and notice where the skeletal notes fall","gap":0.3}
```

## Common misconceptions

- **"Fifth species means anything goes."** Note values are free; the discipline of treating dissonance (by step,
  resolved) is unchanged.
- **"It is easier than the first four."** Fewest rules, hardest judgement: no cells to lean on, only musical
  sense.
- **"The first four are exercises; only the fifth is real writing."** The first four train each ability the fifth
  requires; skipping them usually shows.
- **"Florid means heavily ornamented."** "Florid" refers to freedom of note value, not to number of notes. Long
  notes and rests are equally its tools.
:::
