---
id: chinese-pentatonic
site: theo
cat: T3
title: 中国五声调式
title_en: Chinese Pentatonic Modes
summary: 宫商角徵羽——同一批五声，五个音都能当主音
summary_en: Gong, shang, jiao, zhi, yu — five notes, and any one of them can be the tonic
level: standard
tags: [乐理, 音阶, 五声]
tags_en: [theory, scale, pentatonic]
alias: [宫商角徵羽, 五声调式, 中国五声]
order: 40
links:
  - "[[concept:pentatonic]]"
  - "[[concept:scale]]"
  - "[[concept:major-scale]]"
  - "[[cn:gongshang-jiaozhiyu|宫商角徵羽（中国用法）]]"
  - "[[cn:wusheng-modes|五声调式（中国用法）]]"
instances:
  - chinafolk-000149 | 《茉莉花》：五声骨架清楚、旋法以级进与小跳为主，是最常被引用的五声样本 | Jasmine Flower — a clear pentatonic frame moving in steps and small leaps, the most quoted sample of the five-note set
  - chinafolk-000390 | 《小白菜》：旋律落音与句读都落在五声之内，可听出"少两个音"带来的圆润 | Little Cabbage — cadences and phrasing stay inside the five notes, showing the smoothness that comes from omitting two
  - chinafolk-000077 | 《绣荷包》：同为五声素材，可与上面两首对照不同地区的旋法差别 | Embroidering a Pouch — pentatonic material again, useful for comparing regional turns of phrase
sources:
  - 中国五声调式的五个音级名（宫商角徵羽）与其音程结构，属中国传统乐学通则
  - 各民歌旋律依《中国民间歌曲集成》所收曲目做的结构性描述；本站不转录现代整理谱
updated: 2026-09-23
---

::: zh
中国五声调式用的音与 [[concept:pentatonic|五声音阶]] 完全一样 —— 五个音、没有半音。
它单独成条的理由只有一个：**这五个音在中国音乐里各有一套名字，而且每一个都能当主音。**

## 五个音级名

| 音级名 | 相当于（C 宫） | 现代读法 |
|---|---|---|
| 宫 | C | 主音（当宫为主音时） |
| 商 | D | 上主音 |
| 角 | E | 中音 |
| 徵 | G | 属音 |
| 羽 | A | 下中音 |

**「宫」不等于"主音"。** 宫是五个音级名里的第一个，但一支曲子可以以徵为主音
（称"徵调式"），也可以以羽为主音（"羽调式"）。这就是"**五种调式**"的由来：

| 调式 | 主音 | 常被拿来对照的西方调式 |
|---|---|---|
| 宫调式 | 宫（C） | 大调五声 |
| 商调式 | 商（D） | 多里亚五声 |
| 角调式 | 角（E） | 少见，色彩偏暗 |
| 徵调式 | 徵（G） | 混合利底亚五声 |
| 羽调式 | 羽（A） | 小调五声 |

注意最右一列只是**结构上的类比**，不代表两者用法相同 —— 五声里没有三全音、
没有导音，功能关系与西方大小调并不对应。这一层属于中国音乐的语境，
见 [[cn:wusheng-modes|五声调式（中国用法）]] 与 [[cn:gongshang-jiaozhiyu|宫商角徵羽（中国用法）]]。

## 结构上的两个要点

1. **同一批音、五个主音** —— 与 [[concept:dorian|教会调式]] 的思路一致：
   音相同，重心不同，色彩就不同。
2. **没有半音，所以没有导音** —— 由此带来旋法上的自由：乐句可以停在任何一个音上，
   收束靠的是落音习惯与节奏，而不是和声推进。

## 图示：五个主音

```svg
<svg viewBox="0 0 640 216" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一批五个音，主音换一次，调式名就换一个</text>
  </g>

  <g transform="translate(40,56)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">宫</text><text x="96" y="0">商</text><text x="192" y="0">角</text>
      <text x="288" y="0">徵</text><text x="384" y="0">羽</text><text x="480" y="0">宫</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="20">C</text><text x="96" y="20">D</text><text x="192" y="20">E</text>
      <text x="288" y="20">G</text><text x="384" y="20">A</text><text x="480" y="20">C</text>
    </g>
    <g stroke="#343439" stroke-width="1.2">
      <line x1="0" y1="36" x2="480" y2="36"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="48" y="52">全音</text><text x="144" y="52">全音</text>
      <text x="240" y="52">小三度</text><text x="336" y="52">全音</text>
      <text x="432" y="52">小三度</text>
    </g>
    <g>
      <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">宫调式：从宫起</text>
      <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">商调式：从商起（结构与多里亚五声相同）</text>
      <text x="0" y="122" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">角调式：从角起（最罕见，色彩偏暗）</text>
      <text x="0" y="142" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">徵调式：从徵起（结构与混合利底亚五声相同）</text>
      <text x="0" y="162" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">羽调式：从羽起（结构与小调五声相同）</text>
    </g>
  </g>
</svg>
```

## 听一听：五声骨架

听一条五声旋律时，试着找出每个乐句**落在哪个音上** —— 落音决定主音，
也决定这支曲子在五个调式里的归属。这正是"同一批音、五个主音"的实感。

```audiolab
{"type":"scale","notes":["C4","D4","E4","G4","A4","C5"],"label":"五声（宫调式，从宫起）","label_en":"Pentatonic, gong mode (starting on gong)","hint":"点「上行」先记骨架；再想若从徵起会是什么样","hint_en":"Try Up to fix the frame, then imagine the same notes starting on zhi","gap":0.42}
```

> **取材说明**：本站的实例池里，中国民歌只存在于 `chinafolk` 来源，该来源的曲目
> 属于**仅限学习研究**的许可档位（catalog 分区为 study）。按全库的取材规则，
> 这一条属于"高优先级池内确实没有该主题曲目"的例外情形，故仍取用，
> 并由行内徽标逐曲标注实际档位。

## 常见误解

- **「宫就是主音」** → 宫是音级名之一。主音可以是宫、商、角、徵、羽中的任何一个。
- **「五声调式=中国音乐」** → 五声在多国都有；中国音乐的特点在于五个音的**命名、调式体系与旋法**，不在音阶本身。
- **「五声就是大调去掉两个音」** → 结构上可以这样理解（见 [[concept:pentatonic|五声音阶]]），但它不因此从属于大小调体系。
- **「羽调式就是小调」** → 音程结构相同，但功能与旋法不同 —— 五声里没有导音，也没有属—主的和声推进。
:::

::: en
Chinese pentatonic modes use exactly the same pitches as the [[concept:pentatonic|pentatonic scale]] — five
notes, no semitones. The reason they deserve a separate entry is simple: **these five notes carry their own set
of names in Chinese music, and any one of them can be the tonic.**

## The five degree names

| Name | Equivalent (C gong) | Modern reading |
|---|---|---|
| gong | C | tonic (when gong is the tonic) |
| shang | D | supertonic |
| jiao | E | mediant |
| zhi | G | dominant |
| yu | A | submediant |

**"Gong" does not mean "tonic".** Gong is the first of the five degree names, but a piece can take zhi as its
tonic (the zhi mode) or yu as its tonic (the yu mode). Hence **five modes**:

| Mode | Tonic | The Western mode it resembles structurally |
|---|---|---|
| gong | gong (C) | major pentatonic |
| shang | shang (D) | Dorian pentatonic |
| jiao | jiao (E) | rare, on the dark side |
| zhi | zhi (G) | Mixolydian pentatonic |
| yu | yu (A) | minor pentatonic |

Note that the right-hand column is only a **structural analogy**. It does not mean the usages match: the
pentatonic has no tritone and no leading tone, so its functional relations do not correspond to Western major and
minor. That layer belongs to the Chinese music context — see
[[cn:wusheng-modes|pentatonic modes in Chinese usage]] and
[[cn:gongshang-jiaozhiyu|the five degree names in Chinese usage]].

## Two structural points

1. **One set of notes, five tonics** — the same idea as the [[concept:dorian|church modes]]: identical
   pitches, a different centre of gravity, a different colour.
2. **No semitone, therefore no leading tone** — which frees the melodic writing: a phrase can come to rest on
   any note, and closure is carried by the closing note and the rhythm rather than by harmonic drive.

## Diagram: five tonics

```svg
<svg viewBox="0 0 640 216" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One set of five notes; move the tonic and the mode gets a new name</text>
  </g>

  <g transform="translate(40,56)">
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="0">gong</text><text x="96" y="0">shang</text><text x="192" y="0">jiao</text>
      <text x="288" y="0">zhi</text><text x="384" y="0">yu</text><text x="480" y="0">gong</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="20">C</text><text x="96" y="20">D</text><text x="192" y="20">E</text>
      <text x="288" y="20">G</text><text x="384" y="20">A</text><text x="480" y="20">C</text>
    </g>
    <g stroke="#343439" stroke-width="1.2">
      <line x1="0" y1="36" x2="480" y2="36"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="48" y="52">W</text><text x="144" y="52">W</text>
      <text x="240" y="52">m3</text><text x="336" y="52">W</text>
      <text x="432" y="52">m3</text>
    </g>
    <g>
      <text x="0" y="82" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">gong mode: starts on gong</text>
      <text x="0" y="102" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">shang mode: starts on shang (shaped like Dorian pentatonic)</text>
      <text x="0" y="122" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">jiao mode: starts on jiao (rarest, darker)</text>
      <text x="0" y="142" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">zhi mode: starts on zhi (shaped like Mixolydian pentatonic)</text>
      <text x="0" y="162" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">yu mode: starts on yu (shaped like minor pentatonic)</text>
    </g>
  </g>
</svg>
```

## Listen: the pentatonic frame

As you listen to a pentatonic melody, try to catch **which note each phrase comes to rest on**. The closing note
decides the tonic, and therefore which of the five modes the piece belongs to. That is the felt reality of "one
set of notes, five tonics".

```audiolab
{"type":"scale","notes":["C4","D4","E4","G4","A4","C5"],"label":"五声（宫调式，从宫起）","label_en":"Pentatonic, gong mode (starting on gong)","hint":"点「上行」先记骨架","hint_en":"Try Up to fix the frame first","gap":0.42}
```

> **Sourcing note**: in this library Chinese folk tunes exist only in the `chinafolk` source, whose tracks carry
> a study-and-research-only licence tier (catalog zone `study`). Under the library-wide sourcing rule this is the
> documented exception — the higher-priority pools genuinely hold no material on this topic — so the tracks are
> used, and the inline badge marks each track's actual tier.

## Common misconceptions

- **"Gong means tonic."** Gong is one of the five degree names. The tonic can be any of gong, shang, jiao, zhi or yu.
- **"Pentatonic modes are Chinese music."** Pentatonic material is international; what is Chinese here is the **naming, the modal system and the melodic practice**, not the note set.
- **"It is just a major scale minus two notes."** Structurally it can be described that way (see [[concept:pentatonic|pentatonic scale]]), but that does not place it under the major-minor system.
- **"The yu mode is minor."** Same interval pattern, different function and melodic practice — there is no leading tone and no dominant-to-tonic harmonic drive.
:::
