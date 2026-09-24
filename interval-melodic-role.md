---
id: interval-melodic-role
site: theo
cat: T2
title: 音程在旋律中的作用
title_en: Intervals in Melody
summary: 级进与跳进决定旋律的呼吸，音程宽度就是旋律的语气
summary_en: Steps and leaps set a melody's breathing; interval width is its tone of voice
level: standard
tags: [乐理, 音程, 旋律]
tags_en: [theory, interval, melody]
alias: [旋律音程, 跳进与级进, melodic interval]
order: 32
links:
  - "[[concept:interval]]"
  - "[[concept:melody]]"
  - "[[concept:interval-number]]"
  - "[[concept:consonance]]"
  - "[[concept:interval-ear-training]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题几乎全是级进，旋律因此平稳、易记、好齐唱 | The Ode to Joy theme moves almost entirely by step — steady, memorable, easy for a crowd to sing
  - mutopia-000049 | 《绿袖子》以小音程与级进为主，旋律线条平缓下行，抒情性由此而来 | Greensleeves leans on small intervals and steps, its line easing downward — that is where its lyricism comes from
  - giantmidi-004040 | 李斯特改编的《骷髅之舞》：大跳与增四度密集，旋律轮廓尖锐、不安定 | Liszt's transcription of Danse macabre is dense with leaps and tritones, its outline sharp and unsettled
sources:
  - 级进与跳进的划分、跳进后反向级进填充的写作惯例，属旋律写作通行表述
  - 各实例的旋律走向依通行乐谱（均为公有领域作品的结构性描述）
updated: 2026-09-23
---

::: zh
同一条旋律，把音程改小或改大，气质立刻改变。**音程是旋律的语气**：
它决定这句话是平稳地说出来，还是忽然扬起、猛然落下。

## 两种基本运动，两种语气

| 运动 | 音程 | 听感 | 作曲上常用来 |
|---|---|---|---|
| **级进** | 二度为主 | 平稳、连贯、易唱 | 陈述主题、铺垫、合唱 |
| **跳进** | 三度以上 | 有冲击、有指向 | 强调、高潮、转折 |

两类不是好坏的差别，而是**分工**。真正成熟的旋律通常以级进为底、
在关键处用跳进点一下 —— 通篇跳进会失去轮廓，通篇级进则会显得平淡。

## 跳进之后通常要回来

旋律写作里有一条沿用数百年的经验：**大跳之后，反向级进填充**。
跳上去之后往回走一点，听觉才觉得这条线被"接住"了。原因不难理解：
大跳制造张力，反向级进是释放张力的最自然方式，这与 [[concept:consonance|协和与不协和]] 的机制同源。

## 三度的特殊地位

在跳进里，**三度是最"像唱歌"的一种**。它足够宽，能让人听出轮廓；又足够窄，不会打断线条。
大量民歌与艺术歌曲的骨干都是三度连接，这一点在
[[concept:interval-ear-training|听辨练习]]里也值得优先攻克。

## 图示：级进与跳进的轮廓差别

```svg
<svg viewBox="0 0 640 232" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样的起止高度，走法不同，语气完全不同</text>
  </g>

  <g transform="translate(40,50)">
    <g transform="translate(0,0)">
      <rect x="0" y="0" width="256" height="64" rx="3" fill="#17171A" stroke="#343439"/>
      <polyline points="16,50 48,42 80,34 112,26 144,18 176,26 208,34 240,42"
        fill="none" stroke="#5B7FA8" stroke-width="1.8"/>
      <text x="16" y="82" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">级进：平稳上行后回落</text>
    </g>
    <g transform="translate(288,0)">
      <rect x="0" y="0" width="256" height="64" rx="3" fill="#17171A" stroke="#343439"/>
      <polyline points="16,52 60,14 104,46 148,12 192,44 236,20"
        fill="none" stroke="#E07A3F" stroke-width="1.8"/>
      <text x="16" y="82" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">跳进：上下起伏，轮廓尖锐</text>
    </g>
    <g transform="translate(0,110)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        大跳之后反向级进填充：跳上去（↓）再走回来（↘）—— 听觉上这条线才被"接住"
      </text>
      <rect x="0" y="14" width="544" height="52" rx="3" fill="#17171A" stroke="#343439"/>
      <polyline points="24,54 96,18 132,30 168,40 204,48 240,54 276,58"
        fill="none" stroke="#E8C547" stroke-width="1.8"/>
      <g stroke="#E8C547" stroke-width="1" stroke-dasharray="3 3">
        <line x1="96" y1="18" x2="96" y2="66"/>
      </g>
      <text x="104" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">跳进顶点</text>
      <text x="212" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">反向级进填充</text>
    </g>
  </g>
</svg>
```

## 听一听：级进与跳进

先听级进（相邻音来回），再听大跳 —— 差别不在音高范围，而在"这条线愿不愿意停"。

```audiolab
{"type":"interval","a":"C4","b":"D4","label":"级进：二度","label_en":"Step: a second","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 G4 就是跳进（五度）：同样的起点，线条立刻有了指向。","hint2_en":"Set b to G4 for a leap of a fifth: same starting note, and the line suddenly points somewhere."}
```

## 常见误解

- **「跳进比级进更高级」** → 是分工不同。合唱与齐唱几乎都靠级进，因为级进最好唱准。
- **「旋律好听靠音程越新奇越好」** → 绝大多数被记住的旋律都以级进为骨架，跳进只是点缀。
- **「大跳之后必须解决」** → 是惯例而非硬规则；现代写作常刻意反着来，制造悬置感。
- **「音程决定旋律的风格」** → 音程影响轮廓，风格还取决于节奏、调式与和声。本站只讲结构层，风格层见流派站。
:::

::: en
Change the intervals in a melody and its character changes at once. **Intervals are a melody's tone of voice**:
they decide whether a phrase speaks evenly, or suddenly rises and falls.

## Two kinds of motion, two tones of voice

| Motion | Intervals | Impression | Typically used for |
|---|---|---|---|
| **step** | mostly seconds | smooth, connected, singable | stating a theme, groundwork, choral writing |
| **leap** | thirds and wider | impact, direction | emphasis, climax, turning points |

Neither is superior; they are a **division of labour**. Mature melodies usually keep steps as their base and
touch a leap at the decisive moment. All leaps and the outline disappears; all steps and the line goes flat.

## A leap usually comes back

A rule of thumb several centuries old: **after a wide leap, fill in with a step in the opposite direction.**
Come back a little after jumping up, and the ear feels the line has been caught. The reason is not mysterious —
a leap creates tension, and a counter-step is the most natural way to release it, the same mechanism as
[[concept:consonance|consonance and dissonance]].

## Why the third matters most

Among leaps, **the third is the one that "sings"**. It is wide enough to make an outline audible and narrow
enough not to break the line. Thirds carry the backbone of countless folk songs and art songs, and they are
worth attacking early in [[concept:interval-ear-training|ear training]] too.

## Diagram: step contours against leap contours

```svg
<svg viewBox="0 0 640 232" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same starting and ending height, different route, entirely different tone</text>
  </g>

  <g transform="translate(40,50)">
    <g transform="translate(0,0)">
      <rect x="0" y="0" width="256" height="64" rx="3" fill="#17171A" stroke="#343439"/>
      <polyline points="16,50 48,42 80,34 112,26 144,18 176,26 208,34 240,42"
        fill="none" stroke="#5B7FA8" stroke-width="1.8"/>
      <text x="16" y="82" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">Steps: rises gently, then eases back</text>
    </g>
    <g transform="translate(288,0)">
      <rect x="0" y="0" width="256" height="64" rx="3" fill="#17171A" stroke="#343439"/>
      <polyline points="16,52 60,14 104,46 148,12 192,44 236,20"
        fill="none" stroke="#E07A3F" stroke-width="1.8"/>
      <text x="16" y="82" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">Leaps: up and down, a sharp outline</text>
    </g>
    <g transform="translate(0,110)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        After a leap, fill in with a counter-step: jump up, then walk back down — that is how the ear catches the line
      </text>
      <rect x="0" y="14" width="544" height="52" rx="3" fill="#17171A" stroke="#343439"/>
      <polyline points="24,54 96,18 132,30 168,40 204,48 240,54 276,58"
        fill="none" stroke="#E8C547" stroke-width="1.8"/>
      <g stroke="#E8C547" stroke-width="1" stroke-dasharray="3 3">
        <line x1="96" y1="18" x2="96" y2="66"/>
      </g>
      <text x="104" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">the peak of the leap</text>
      <text x="212" y="80" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">counter-step filling</text>
    </g>
  </g>
</svg>
```

## Listen: step against leap

Hear a step (neighbouring notes back and forth), then a wide leap. The difference is not range but whether the
line wants to settle.

```audiolab
{"type":"interval","a":"C4","b":"D4","label":"级进：二度","label_en":"Step: a second","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 G4 就是跳进（五度）：同样的起点，线条立刻有了指向。","hint2_en":"Set b to G4 for a leap of a fifth: same starting note, and the line suddenly points somewhere."}
```

## Common misconceptions

- **"Leaps are more advanced than steps."** It is a division of labour. Choral and communal singing runs on steps because steps stay in tune.
- **"A melody is better the more novel its intervals."** Almost every memorable melody has steps as its skeleton; leaps are accents.
- **"A leap must be resolved."** Convention, not law. Modern writing often does the opposite on purpose, for a suspended feel.
- **"Intervals decide a melody's style."** They shape the contour; style also depends on rhythm, mode and harmony. This entry stays on the structural layer — genre-level questions belong elsewhere.
:::
