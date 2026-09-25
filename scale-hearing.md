---
id: scale-hearing
site: theo
cat: T11
title: 调性与音阶听辨
title_en: Hearing Key and Scale
summary: 判据是"中心在哪"，不是"用了哪些音"
summary_en: The test is where the centre is, not which notes are used
level: standard
tags: [乐理, 练耳, 调性]
tags_en: [theory, ear training, tonality]
alias: [调性听辨, 音阶听辨, 大小调听辨]
order: 16
links:
  - "[[concept:ear-training]]"
  - "[[concept:tonal-center]]"
  - "[[concept:scale]]"
  - "[[concept:key-signature]]"
  - "[[concept:dorian]]"
instances:
  - giantmidi-006222 | 音阶与终止练习：终止式明确给出中心感，是练"听主音"最直接的材料 | Scale and cadence exercises state the centre clearly, the most direct material for hearing the tonic
  - mutopia-000522 | 《欢乐颂》主题：句末明确回到主音，可用来练"哪一句落定了" | The Ode of Joy returns clearly to the tonic at phrase ends, useful for hearing which phrase has settled
  - thesession-019704 | 《小星星》：五声性写法清楚，可用来对照"中心明确"与"中心模糊"的差别 | Twinkle Little Star has a clear pentatonic shape, a contrast between a firm centre and a vague one
sources:
  - 调性中心感由终止式、重复与强调共同建立；大小调最省力的判据为主音上的三度性质，为通行练耳教学表述
  - 关系大小调共用同一音集，故"音集"不能判定调性，为通行乐理表述
updated: 2026-09-25
---

::: zh
调性听辨最容易走错的一步，是先去找"用了哪些音"。正确的第一步是另一个问题：

> **中心在哪？**

因为**音集不能判定调**：C 大调与 a 小调**共用同一批音**（见 [[concept:key-signature|调号]] 那条的核心结论）——
所以"听出用了哪些音"并不能回答"这是什么调"。

## 最省力的判据：主音上的三度

| 判据 | 结论 |
|---|---|
| 主音上方是**大三度** | **大调式** |
| 主音上方是**小三度** | **小调式** |

**为什么这条最省力**：它只需要确认**两个音**（主音与三音），
而这两个音决定了调式的基本色彩。其他音级（六度、七度）的变化是在这个基础上的**变体**：

| 变体 | 变化 |
|---|---|
| **和声小调** | 升高第 7 级（为取得属功能） |
| **旋律小调** | 上行再升高第 6 级 |
| **多利亚 / 混合利底亚等** | 六度或七度按调式调整 |

**所以听辨顺序是**：**先定主音 → 再听三度 → 最后注意六七度的变化**。

## 怎么找到"中心"

中心不是靠"感觉"，它由三件事建立：

| 建立中心的方式 | 说明 |
|---|---|
| **终止式** | 最强的中心确立手段（见 [[concept:cadence\|终止式]]） |
| **反复强调** | 某个音出现得最多、时值最长，常是主音 |
| **开头与结尾** | 绝大多数作品**结束在主音**上 |

**第三行是最实用的捷径**：**先听最后一个音** ——
它大概率就是主音（见 [[concept:tonal-center|调性中心]]）。

**第一行是根本**：如果一段音乐没有终止式，中心就会模糊 ——
这正是许多现代作品"听不出调"的原因。

## 三种"听不出调"的情况

| 情况 | 原因 | 能不能判断 |
|---|---|---|
| **中心模糊**（如印象派） | 避免传统终止式 | 常能听出"大致以某音为中心"，但不明确 |
| **频繁转调** | 中心不断更换 | 可以逐段判断 |
| **无调性** | 有意取消中心 | **不能判** —— 因为它没有中心 |

**第二行是常见情况**：浪漫派作品常在一分钟内经过好几个调。
**这时不要问"这是什么调"，而要问"这一段是什么调"** ——
判断的单位要跟着音乐的规模变化。

## 图示：判据是中心，不是音集

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一批音可以属于两个调 —— 所以"音集"不能判定调性，"中心"才能</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">音集</text>
    </g>
    <g fill="#343439">
      <rect x="0" y="-10" width="300" height="20" rx="3"/>
    </g>
    <text x="150" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      C D E F G A B（同一批音）
    </text>

    <g transform="translate(0,44)">
      <g fill="#5B7FA8"><rect x="0" y="-10" width="140" height="20" rx="3"/></g>
      <text x="70" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">中心 = C → 大调</text>
      <g fill="#E07A3F"><rect x="160" y="-10" width="140" height="20" rx="3"/></g>
      <text x="230" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">中心 = A → 小调</text>
      <g stroke="#343439" stroke-width="1.2" stroke-dasharray="3 2">
        <line x1="150" y1="-24" x2="70" y2="-12"/><line x1="150" y1="-24" x2="230" y2="-12"/>
      </g>
    </g>

    <g transform="translate(0,92)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        最省力的判据：主音上的三度 —— 大三度 = 大调式，小三度 = 小调式（只需确认两个音）
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        最实用的捷径：先听最后一个音（绝大多数作品结束在主音）；中心由终止式与反复强调建立
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        频繁转调时不要问"这是什么调"，要问"这一段是什么调" —— 判断单位跟着音乐规模变
      </text>
    </g>
  </g>
</svg>
```

## 听一听：同一批音、两个中心

用 `scale` 听两条音阶 —— **音集完全相同**（C D E F G A B），
但一条以 C 为中心、一条以 A 为中心。**请留意"落定感"落在哪个音上。**

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"中心 = C（大调式）","label_en":"Centre on C — major","hint":"点「上行」，注意结束感落在 C","hint_en":"Try Up and notice the sense of arrival on C","gap":0.34}
```

```audiolab
{"type":"scale","notes":["A3","B3","C4","D4","E4","F4","G4","A4"],"label":"中心 = A（小调式，同一批音）","label_en":"Centre on A — minor, the same notes","hint":"与上一条对比：音相同，中心与色彩不同","hint_en":"Against the item above: same notes, different centre and colour","gap":0.34}
```

## 常见误解

- **「听出用了哪些音就知道是什么调」** → 不能。关系大小调**共用音集**，必须判中心。
- **「调性要靠"感觉"」** → 有具体手段：**终止式、反复强调、开头与结尾**。
- **「小调就是"悲伤"」** → 那是刻板印象。小调与情绪没有固定对应（见 [[concept:minor-scale|小调音阶]]）。
- **「听不出调就是耳朵不行」** → 有些音乐**本来就没有中心**（无调性），**判不出来是正常的**。
:::

::: en
The step where key hearing most easily goes wrong is looking for "which notes are used". The right first question is
another one:

> **Where is the centre?**

Because **a pitch set cannot determine a key**: C major and A minor **share the same notes** (the core conclusion
under [[concept:key-signature|key signature]]) — so "hearing which notes are used" does not answer "what key is
this".

## The cheapest test: the third above the tonic

| Test | Conclusion |
|---|---|
| a **major third** above the tonic | **major mode** |
| a **minor third** above the tonic | **minor mode** |

**Why it is the cheapest**: it requires confirming only **two notes** (the tonic and the third), and those two decide
the mode's basic colour. The other degrees (sixth, seventh) are **variants** on that basis:

| Variant | Change |
|---|---|
| **harmonic minor** | the seventh degree raised (to obtain dominant function) |
| **melodic minor** | the sixth also raised going up |
| **Dorian, Mixolydian and others** | the sixth or seventh adjusted to the mode |

**So the order is**: **find the tonic → hear the third → then note the sixth and seventh.**

## How to find the centre

The centre is not a "feeling"; it is established by three things:

| How | Explanation |
|---|---|
| **cadences** | the strongest means of establishing a centre (see [[concept:cadence\|cadence]]) |
| **repetition and emphasis** | the note that occurs most, and longest, is often the tonic |
| **the beginning and the end** | the overwhelming majority of works **end on the tonic** |

**The third row is the most practical shortcut**: **listen to the last note** — it is most likely the tonic (see
[[concept:tonal-center|tonal centre]]).

**The first is fundamental**: without a cadence the centre becomes vague — which is exactly why much modern music
"has no audible key".

## Three cases of "no audible key"

| Case | Cause | Can you judge? |
|---|---|---|
| **vague centre** (e.g. Impressionist) | traditional cadences avoided | often "roughly centred on some note", but not definite |
| **frequent modulation** | the centre keeps changing | yes, section by section |
| **atonality** | the centre deliberately removed | **no** — there is no centre to find |

**The second is common**: Romantic works often pass through several keys within a minute. **Then do not ask "what key
is this" but "what key is this passage in"** — the unit of judgement follows the scale of the music.

## Diagram: the test is the centre, not the pitch set

```svg
<svg viewBox="0 0 640 210" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One set of notes can belong to two keys — so the set cannot decide, only the centre can</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">pitch set</text>
    </g>
    <g fill="#343439">
      <rect x="0" y="-10" width="300" height="20" rx="3"/>
    </g>
    <text x="150" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      C D E F G A B — the same notes
    </text>

    <g transform="translate(0,44)">
      <g fill="#5B7FA8"><rect x="0" y="-10" width="140" height="20" rx="3"/></g>
      <text x="70" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">centre C — major</text>
      <g fill="#E07A3F"><rect x="160" y="-10" width="140" height="20" rx="3"/></g>
      <text x="230" y="4" font-family="system-ui,sans-serif" font-size="10.5" fill="#F2EEE6" text-anchor="middle">centre A — minor</text>
      <g stroke="#343439" stroke-width="1.2" stroke-dasharray="3 2">
        <line x1="150" y1="-24" x2="70" y2="-12"/><line x1="150" y1="-24" x2="230" y2="-12"/>
      </g>
    </g>

    <g transform="translate(0,92)">
      <text x="0" y="0" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
        Cheapest test: the third above the tonic — major third means major, minor third means minor
      </text>
      <text x="0" y="22" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
        Practical shortcut: listen to the last note; the centre is built by cadences and emphasis
      </text>
      <text x="0" y="44" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
        With frequent modulation ask "what key is this passage in", not "what key is this"
      </text>
    </g>
  </g>
</svg>
```

## Listen: one pitch set, two centres

Use `scale` on two scales — **the same notes** (C D E F G A B) but one centred on C and one on A. **Notice which note
carries the sense of arrival.**

```audiolab
{"type":"scale","notes":["C4","D4","E4","F4","G4","A4","B4","C5"],"label":"中心 = C（大调式）","label_en":"Centre on C — major","hint":"点「上行」，注意结束感落在 C","hint_en":"Try Up and notice the sense of arrival on C","gap":0.34}
```

```audiolab
{"type":"scale","notes":["A3","B3","C4","D4","E4","F4","G4","A4"],"label":"中心 = A（小调式，同一批音）","label_en":"Centre on A — minor, the same notes","hint":"与上一条对比：音相同，中心与色彩不同","hint_en":"Against the item above: same notes, different centre and colour","gap":0.34}
```

## Common misconceptions

- **"Knowing the notes tells you the key."** It does not. Relative major and minor **share a pitch set**; the centre
  must be judged.
- **"Key is a matter of feeling."** There are concrete means: **cadences, emphasis, and the beginning and end**.
- **"Minor means sad."** That is a stereotype. Minor keys have no fixed emotional meaning (see
  [[concept:minor-scale|the minor scale]]).
- **"Not hearing a key means poor ears."** Some music **has no centre** (atonality); **failing to find one is
  correct**.
:::
