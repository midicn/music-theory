---
id: articulation
site: theo
cat: T10
title: 演奏法记号
title_en: Articulation Marks
summary: 它决定音与音"怎么连接"——与"多响"是两个维度
summary_en: It decides how notes connect — a different dimension from how loud they are
level: standard
tags: [乐理, 记谱, 实践]
tags_en: [theory, notation, practice]
alias: [演奏法记号, 连奏, 断奏, 弓法, 吐音]
order: 30
links:
  - "[[concept:ties-slurs]]"
  - "[[concept:dynamics]]"
  - "[[concept:breath-phrasing]]"
  - "[[concept:timbre]]"
  - "[[concept:historical-performance]]"
instances:
  - mutopia-000522 | 《欢乐颂》主题：圆滑线与分句标记展示了"音的连接方式"如何塑造乐句 | The Ode of Joy shows how slurs and phrasing marks shape a melody's articulation
  - cyberhymnal-000695 | 管风琴圣咏：圣咏式写法以连奏为主，可作"少断奏"的对照 | An organ hymn is largely legato, a control case with little staccato
  - giantmidi-006222 | 音阶练习：同一串音用连奏或断奏演奏，性格立刻不同，最便于对照 | Scale exercises — the same run played legato or staccato changes character immediately
sources:
  - 演奏法记号（连奏 / 断奏 / 顿音 / 重音 / 保持音）及其在不同乐器上的实现（弓法 / 吐音），为通行记谱与演奏教学表述
  - 演奏法记号的实际处理随时代与乐器变化，为历史演奏法通行研究结论
updated: 2026-09-25
---

::: zh
演奏法记号管的是一个独立维度：

> **它决定音与音之间"怎么连接"** —— 不是"多响"（那是 [[concept:dynamics|力度记号]] 的事）。

## 基本记号

| 记号 | 名称 | 效果 |
|---|---|---|
| **圆滑线**（弧线） | 连奏（legato） | 音之间**不断开** |
| **·**（点） | 断奏（staccato） | 音**明显分开**，但保留部分时值 |
| **▾**（尖点） | 顿音（staccatissimo） | 更短的断奏 |
| **—**（短横） | 保持音（tenuto） | 时值**拉满**，略强调 |
| **>**（楔形） | 重音（accent） | **瞬间**加强 |
| **^** | 强跳音（marcato） | 短且强 |

**注意**：`>`（重音）与渐弱记号外形相近，但含义完全不同（见 [[concept:dynamics|力度记号]]）。

## 它在不同乐器上的名称

同一件事，不同乐器有不同的说法：

| 乐器 | 术语 | 说明 |
|---|---|---|
| **弦乐** | **弓法** | 连弓（一弓多音）/ 分弓（一弓一音）/ 顿弓 / 跳弓 |
| **管乐** | **吐音** | 单吐 / 双吐 / 三吐 —— 用舌头的不同动作控制音头 |
| **键盘** | 触键方式 | 手指的离键高度与速度 |
| **声乐** | 咬字与连断 | 与歌词音节配合 |

**所以"演奏法"是跨乐器的通用概念，而"弓法""吐音"是它在具体乐器上的实现方式。**

## 为什么它值得单列

因为**同一串音，不同演奏法就是不同性格** ——

| 同一串音 | 连奏 | 断奏 |
|---|---|---|
| 听感 | 歌唱、连贯、抒情 | 轻快、颗粒感、生机 |
| 常见场合 | 慢乐章、旋律主题 | 谐谑曲、舞曲、快速段落 |

**这与"改节奏型就改性格"是同一类现象**（见 [[concept:rhythmic-pattern|节奏型]]）：
**音高和时值都没变，性格却完全不同** ——
说明演奏法是**独立的表达维度**，不是"音高与时值的附属"。

## 一个历史要点

与力度记号一样（见 [[concept:dynamics|力度记号]]），演奏法记号的**实际处理也随时代变化**：

| 时期 | 情况 |
|---|---|
| **巴洛克** | 标记较少；连断处理常需从**乐器特性与时代惯例**推断 |
| **古典** | 标记逐渐细化，但仍有大量惯例（如"不标圆滑线时的默认连断"） |
| **浪漫以后** | 标记极其详尽 |

**所以"照谱面直译"往往不是正确读法** ——
不标圆滑线的巴洛克段落，**并不意味着要断奏**，而要看当时的惯例（见
[[concept:historical-performance|历史演奏法]]）。

## 图示：三个维度互不替代

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">音高 · 时值 · 连断 · 力度是四个独立维度，各由不同记号管</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">音高</text>
      <text x="-20" y="34" text-anchor="end">时值</text>
      <text x="-20" y="68" text-anchor="end">连断</text>
      <text x="-20" y="102" text-anchor="end">力度</text>
    </g>

    <g font-family="system-ui,sans-serif" font-size="10.5">
      <text x="0" y="4" fill="#5B7FA8">由符头位置 / 数字 / 汉字（视记谱体系而定）</text>
      <text x="0" y="38" fill="#E8C547">由符尾 / 符点 / 增时线 / 延音线</text>
      <text x="0" y="72" fill="#E07A3F">由圆滑线 · 点 · 短横 · 楔形记号</text>
      <text x="0" y="106" fill="#C0504A">由 p f 与渐强渐弱记号</text>
    </g>

    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="-190" y1="16" x2="300" y2="16"/>
      <line x1="-190" y1="50" x2="300" y2="50"/>
      <line x1="-190" y1="84" x2="300" y2="84"/>
    </g>

    <text x="0" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      同一串音：连奏 → 歌唱连贯；断奏 → 轻快有颗粒 —— 音高与时值都没变
    </text>
    <text x="0" y="156" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      巴洛克"不标圆滑线"不等于要断奏 —— 照谱直译往往不是正确读法
    </text>
  </g>
</svg>
```

## 听一听：连奏与断奏的性格

用 `rhythm` 组件对比两种时值形态 —— **后面的"留白"就相当于断奏的效果**（音与音之间出现空隙）。
请留意性格如何立刻改变。

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":92,"label":"连奏感（音之间没有空隙）","label_en":"Legato feel — no gaps between notes","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q h","bpm":92,"label":"断奏感（后半出现空隙）","label_en":"Staccato feel — a gap opens in the second half","hint":"与上一条对比：音高与时值理念未变，性格不同","hint_en":"Against the item above: same pitches and values, different character"}
```

## 常见误解

- **「演奏法是"小细节"」** → 它是**独立的表达维度**：同一串音换演奏法，性格完全改变。
- **「不标圆滑线就是断奏」** → 尤其在巴洛克作品里，**默认连断要看时代惯例**，不能照谱直译。
- **「断奏就是把音弹短」** → 断奏是**音之间分开**（保留部分时值）；把音压得极短是**顿音**，两者不同。
- **「重音记号与渐弱记号差不多」** → 完全不同：`>` 是**瞬间强调**，渐弱是**一段时间内的下降**。
:::

::: en
Articulation governs an independent dimension:

> **It decides how notes connect** — not how loud they are (that is [[concept:dynamics|dynamics]]).

## The basic marks

| Mark | Name | Effect |
|---|---|---|
| **slur** (arc) | legato | notes are **not separated** |
| **·** (dot) | staccato | notes **clearly separated**, part of the value retained |
| **▾** (wedge) | staccatissimo | a shorter staccato |
| **—** (short line) | tenuto | the full value, slightly emphasised |
| **>** (wedge) | accent | a **momentary** emphasis |
| **^** | marcato | short and strong |

**Note**: `>` (accent) looks like a diminuendo but means something entirely different (see
[[concept:dynamics|dynamics]]).

## What it is called on different instruments

One idea under different names:

| Instrument | Term | Explanation |
|---|---|---|
| **strings** | **bowing** | slurred bow (several notes per bow), separate bows, détaché, spiccato |
| **winds** | **tonguing** | single, double and triple tonguing — the tongue controls the attack |
| **keyboard** | touch | how high and how fast the finger leaves the key |
| **voice** | diction and connection | coordinated with the syllables of the text |

**So "articulation" is an instrument-neutral concept, while "bowing" and "tonguing" are its realisation on a
particular instrument.**

## Why it deserves its own entry

Because **the same run of notes under different articulation is a different character**:

| Same run | Legato | Staccato |
|---|---|---|
| Sound | singing, connected, lyrical | light, granular, lively |
| Typical use | slow movements, melodic themes | scherzos, dances, fast passages |

**This is the same kind of phenomenon as "change the rhythmic pattern and the character changes"** (see
[[concept:rhythmic-pattern|rhythmic pattern]]): **neither pitch nor duration changes, yet the character does** —
which shows articulation is an **independent expressive dimension**, not an appendage of pitch and duration.

## One historical point

Like dynamic markings (see [[concept:dynamics|dynamics]]), **the practical handling of articulation marks changes
with the era**:

| Period | Situation |
|---|---|
| **Baroque** | few marks; legato and detachment must often be inferred from **instrumental characteristics and period convention** |
| **Classical** | marks become more detailed, but many conventions remain (for instance the default when no slur is written) |
| **after the Romantic era** | extremely detailed marking |

**So "translating the page literally" is often not the right reading** — a Baroque passage with no slurs **does not
imply staccato**; the convention of the time must be consulted (see
[[concept:historical-performance|historical performance]]).

## Diagram: four dimensions, none replacing another

```svg
<svg viewBox="0 0 640 208" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Pitch, duration, connection and loudness are four independent dimensions with their own signs</text>
  </g>

  <g transform="translate(52,58)">
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="-20" y="0" text-anchor="end">pitch</text>
      <text x="-20" y="34" text-anchor="end">duration</text>
      <text x="-20" y="68" text-anchor="end">connection</text>
      <text x="-20" y="102" text-anchor="end">loudness</text>
    </g>

    <g font-family="system-ui,sans-serif" font-size="10.5">
      <text x="0" y="4" fill="#5B7FA8">by note head position, digits or characters, depending on the system</text>
      <text x="0" y="38" fill="#E8C547">by flags, dots, dashes and ties</text>
      <text x="0" y="72" fill="#E07A3F">by slurs, dots, short lines and wedges</text>
      <text x="0" y="106" fill="#C0504A">by p, f, crescendo and diminuendo</text>
    </g>

    <g stroke="#343439" stroke-width="1" stroke-dasharray="3 3">
      <line x1="-190" y1="16" x2="300" y2="16"/>
      <line x1="-190" y1="50" x2="300" y2="50"/>
      <line x1="-190" y1="84" x2="300" y2="84"/>
    </g>

    <text x="0" y="134" font-family="system-ui,sans-serif" font-size="11" fill="#E8C547">
      One run: legato sings, staccato sparkles — with pitch and duration unchanged
    </text>
    <text x="0" y="156" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      A Baroque passage without slurs does not mean staccato; the page cannot simply be translated literally
    </text>
  </g>
</svg>
```

## Listen: the character of legato and staccato

Use `rhythm` to compare two shapes — **the gap in the second stands for staccato** (a space opens between notes).
Notice how fast the character changes.

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q q q","bpm":92,"label":"连奏感（音之间没有空隙）","label_en":"Legato feel — no gaps between notes","hint":"先听这一档","hint_en":"Hear this setting first"}
```

```audiolab
{"type":"rhythm","sig":"4/4","pattern":"q q h","bpm":92,"label":"断奏感（后半出现空隙）","label_en":"Staccato feel — a gap opens in the second half","hint":"与上一条对比：音高与时值未变，性格不同","hint_en":"Against the item above: same pitches and values, different character"}
```

## Common misconceptions

- **"Articulation is a small detail."** It is an **independent expressive dimension**: change it and the character
  changes completely.
- **"No slur means staccato."** Especially in Baroque music, **the default connection follows period convention**;
  the page cannot be translated literally.
- **"Staccato just means playing short."** Staccato **separates** notes (part of the value retained); squeezing notes
  to their shortest is **staccatissimo**, a different thing.
- **"An accent and a diminuendo are much the same."** Different entirely: `>` is **momentary**, a diminuendo a
  **decline over time**.
:::
