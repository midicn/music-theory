---
id: timbre
site: theo
cat: T1
title: 音色
title_en: Timbre
summary: 同一个音高，音色由分音的强弱分布与起音的形状决定
summary_en: At the same pitch, timbre comes from how strong each partial is and how the attack is shaped
level: core
tags: [乐理, 音色, 配器]
tags_en: [theory, timbre, orchestration]
alias: [音色与波形, timbre, 音质]
order: 70
links:
  - "[[concept:harmonic-series]]"
  - "[[concept:sound]]"
  - "[[concept:register]]"
  - "[[concept:pitch]]"
instances:
  - mutopia-001732 | 同一支《绿袖子》，吉他独奏版：拨弦的起音干脆，余音短 | The same Greensleeves on solo guitar — a crisp plucked attack and a short decay
  - pdmx-000181 | 同一支《绿袖子》，钢琴改编版：敲击起音更硬，中音区饱满 | The same Greensleeves arranged for piano — a harder percussive attack and a fuller middle register
  - mutopia-001682 | 同一支《绿袖子》，合奏版：多个音色叠在一起，得到第三种既非吉他亦非钢琴的质地 | The same Greensleeves in ensemble — several colours stacked into a third texture that is neither guitar nor piano
sources:
  - 音色的三个物理构成（分音构成、起音包络、共鸣体特性）属音乐声学通行表述
  - 波形（正弦 / 方波 / 锯齿波）与分音构成的关系属信号与声学常识
updated: 2026-09-23
---

::: zh
同一个音高，钢琴弹出是"叮"，小提琴拉出是"呜"，长笛吹出是"呼"。
频率一样、力度一样、时值一样，差别只剩一个词：音色。它是四要素里唯一无法用一个轴描述的属性。

## 音色由三件事决定

**一、分音的强弱分布。** 一个音实际是基音加一串 [[concept:harmonic-series|分音]]。
各次分音谁强谁弱，直接画出音色的轮廓：高次分音强，听起来就亮、就尖、就有"金属感"；
高次分音被压下去，听起来就圆、就软、就"闷"。

**二、起音包络。** 声音从无到有、从有到无的过程。三段时间很关键：

- **起音**：从静音爬到最大音量用了多久。极短 = 敲击感（钢琴、鼓），较长 = 吹奏感（长笛、弦乐）。
- **衰减**：从峰值落下来的形状。落得快 = 颗粒分明，落得慢 = 连绵。
- **收尾**：放开之后余音怎么消失。

**三、共鸣体与辐射方式。** 同一个激励方式配上不同的箱体，音色会差出十万八千里。
钢琴的铸铁框架与音板、小提琴的拱形面板、管风琴的金属与木管，本质都是"给振动选一个放大与过滤的形状"。

## 图示：三段起音包络

```svg
<svg viewBox="0 0 640 250" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">横轴 = 时间 · 纵轴 = 音量 · 同样的音高与时长，包络不同，音色印象就不同</text>
  </g>

  <g transform="translate(24,44)">
    <rect x="0" y="0" width="592" height="170" rx="3" fill="#17171A" stroke="#343439"/>

    <g transform="translate(40,14)">
      <polyline points="0,118 6,12 22,64 120,104 150,118" fill="none" stroke="#E07A3F" stroke-width="1.8"/>
      <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">敲击型（钢琴 / 鼓）</text>
      <text x="0" y="166" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">起音极短，随后一路衰减，没有稳定段</text>
    </g>

    <g transform="translate(248,14)">
      <polyline points="0,118 14,40 34,30 100,34 132,118" fill="none" stroke="#5B7FA8" stroke-width="1.8"/>
      <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">吹奏型（长笛 / 弦乐）</text>
      <text x="0" y="166" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">起音较缓，中段稳定，收尾平顺</text>
    </g>

    <g transform="translate(456,14)">
      <polyline points="0,118 10,18 26,20 90,22 118,118" fill="none" stroke="#E8C547" stroke-width="1.8"/>
      <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">持续型（管风琴）</text>
      <text x="0" y="166" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">起音后几乎不衰减，按住多久响多久</text>
    </g>
  </g>
</svg>
```

## 为什么"波形"这个名字有用

把一次振动画成一条曲线，就得到波形。几种基础波形对应不同的分音构成：

| 波形 | 分音构成 | 听感 |
|---|---|---|
| 正弦波 | 只有基音 | 纯净、无色彩 |
| 方波 | 奇次分音，衰减较慢 | 空旷、带"电子味" |
| 锯齿波 | 全部整数次分音 | 明亮、粗糙、像弦乐 |

真实的乐器音色都是这些基础形状的**混合加变化**，而且变化过程随起音段在动 ——
所以音色无法用一条静态曲线写完。

## 听一听：音色的"对照组"

下面这些音全部由站内合成器发出，**音色完全一致**。
把它当作一条基准线：换一件乐器演奏同样的音，你听到的全部差别就是音色本身。

```audiolab
{"type":"scale","notes":["G3","B3","D4","G4"],"label":"同一种音色的四个音","label_en":"Four tones, one single timbre","hint":"四个音的音色完全相同，只有音高在变——这就是对照组","hint_en":"Identical timbre from top to bottom; only the pitch moves — that is the control","gap":0.36,"dur":0.34}
```

## 音色在写作里怎么用

- **换人说话**：主题交给不同乐器，等于换了一个叙述者，结构与旋律不必改。
- **混合成新色**：两件乐器齐奏时，分音互相补足，会得到一个"既不是甲也不是乙"的第三音色。木管与弦乐的混合是配器里最常用的一招。
- **音区即音色**：同一件乐器在不同 [[concept:register|音区]] 里音色差别极大，所以"哪件乐器"和"哪个音区"其实是同一个决定。

## 常见误解

- **「音色是主观的，没法讨论」** → 印象确实主观，但成因完全客观：分音构成与包络都能被测量。
- **「音色就是乐器的牌子」** → 同一件乐器在不同音区、不同力度、不同奏法下音色各不相同。牌子只是其中一个变量。
- **「音色和音高无关」** → 相关。音高变了，分音的绝对频率跟着变，共鸣体的响应也随之改变，音色必然一起变。
- **「正弦波听起来最好」** → 它只是信息最少。旋律用纯正弦波演奏会显得寡淡，正因为缺少分音带来的辨识度。
:::

::: en
Play one pitch on a piano and you get a ping; on a violin, a wail; on a flute, a breath. Same frequency, same
loudness, same duration — the only thing left to name is timbre. Of the four properties of a tone, it is the one
that cannot be plotted on a single axis.

## Three things determine timbre

**One: how strong each partial is.** A tone is a fundamental plus a stack of
[[concept:harmonic-series|partials]]. Their relative strengths draw the outline of the timbre: strong upper
partials sound bright, sharp, metallic; suppressed upper partials sound round, soft, muffled.

**Two: the attack envelope.** How the sound arrives and leaves. Three stretches matter:

- **Attack**: how long it takes to climb from silence to full level. Very short reads as percussion (piano,
  drums); longer reads as blowing or bowing (flute, strings).
- **Decay**: the shape of the fall from the peak. A fast fall gives articulation; a slow one gives continuity.
- **Release**: how the tail disappears once you let go.

**Three: the resonator and how it radiates.** The same excitation through a different body changes everything.
A piano's cast-iron frame and soundboard, a violin's arched belly, an organ's metal and wooden pipes — all are
ways of choosing a shape to amplify and filter the vibration.

## Diagram: three attack envelopes

```svg
<svg viewBox="0 0 640 250" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Horizontal axis = time · vertical = level · same pitch and duration, different envelope, different timbre</text>
  </g>

  <g transform="translate(24,44)">
    <rect x="0" y="0" width="592" height="170" rx="3" fill="#17171A" stroke="#343439"/>

    <g transform="translate(40,14)">
      <polyline points="0,118 6,12 22,64 120,104 150,118" fill="none" stroke="#E07A3F" stroke-width="1.8"/>
      <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">Percussive (piano, drums)</text>
      <text x="0" y="166" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">very short attack, then decay all the way, no sustain</text>
    </g>

    <g transform="translate(248,14)">
      <polyline points="0,118 14,40 34,30 100,34 132,118" fill="none" stroke="#5B7FA8" stroke-width="1.8"/>
      <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">Blown or bowed (flute, strings)</text>
      <text x="0" y="166" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">softer attack, steady middle, smooth release</text>
    </g>

    <g transform="translate(456,14)">
      <polyline points="0,118 10,18 26,20 90,22 118,118" fill="none" stroke="#E8C547" stroke-width="1.8"/>
      <text x="0" y="150" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">Sustained (organ)</text>
      <text x="0" y="166" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">almost no decay; it sounds as long as you hold it</text>
    </g>
  </g>
</svg>
```

## Why the word "waveform" is useful

Draw one cycle of a vibration as a curve and you have a waveform. A few basic shapes correspond to particular
partial patterns:

| Waveform | Partials | Impression |
|---|---|---|
| Sine | fundamental only | pure, colourless |
| Square | odd partials, decaying slowly | hollow, electronic |
| Sawtooth | all integer partials | bright, rough, string-like |

Real instrument timbres are **mixtures of these shapes that change over time**, and the change is fastest during
the attack — which is why a single static curve can never describe a timbre completely.

## Listen: the control case for timbre

Every tone below comes from the same in-page synth and therefore has **exactly the same timbre**.
Treat it as a baseline: play the same notes on an instrument and everything you hear differently is timbre.

```audiolab
{"type":"scale","notes":["G3","B3","D4","G4"],"label":"同一种音色的四个音","label_en":"Four tones, one single timbre","hint":"四个音的音色完全相同，只有音高在变——这就是对照组","hint_en":"Identical timbre from top to bottom; only the pitch moves — that is the control","gap":0.36,"dur":0.34}
```

## How timbre is used in writing

- **A change of narrator.** Give the theme to another instrument and you have a new speaker without altering a single note of structure or melody.
- **Blending into a third colour.** Two instruments in unison fill in each other's partials and produce a sound that is neither. Mixing woodwind with strings is the most common trick in orchestration.
- **Register is timbre.** One instrument changes character drastically across [[concept:register|register]], so "which instrument" and "which register" are really the same decision.

## Common misconceptions

- **"Timbre is subjective, so it cannot be discussed."** The impression is subjective; the causes are entirely objective, since both partial content and envelope can be measured.
- **"Timbre means the maker's name on the instrument."** One instrument changes timbre by register, dynamic and technique. The maker is only one variable.
- **"Timbre has nothing to do with pitch."** It does. Change the pitch and every partial's absolute frequency changes with it, which changes how the resonator responds.
- **"Sine waves sound best."** They simply carry the least information. A melody on pure sine tones sounds bland precisely because nothing distinguishes one from another.
:::
