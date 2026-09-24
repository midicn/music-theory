---
id: sound
site: theo
cat: T1
title: 音是什么
title_en: What Is a Musical Sound
summary: 声音是空气的振动，乐音是其中音高可辨的那一类
summary_en: Sound is vibrating air; a musical tone is the kind whose pitch can be named and repeated
level: core
tags: [乐理, 声学, 基础]
tags_en: [theory, acoustics, basics]
alias: [乐音, 噪音, 音的性质, sound]
order: 10
links:
  - "[[concept:pitch]]"
  - "[[concept:timbre]]"
  - "[[concept:harmonic-series]]"
  - "[[concept:scale]]"
instances:
  - mutopia-000049 | 单声部旋律，能听见一个个界限分明的乐音 | A single-line melody — you can hear one clearly bounded tone after another
  - groove-000000 | 打击乐：音高不固定，却有清晰可辨的节奏与强弱，正好拿来对照「乐音与噪音」 | Percussion — no fixed pitch, yet rhythm and dynamics are unmistakable — the perfect control case for tone versus noise
  - cyberhymnal-000695 | 管风琴圣咏：若干音同时发声，说明一个「音」可以叠成和声 | An organ hymn — several tones sounding at once, showing how single tones stack into harmony
sources:
  - 声音由振动产生、人耳可听频率范围、乐音与噪音的区分，属声学与音乐声学通则
  - 音的四项属性（音高 / 音长 / 力度 / 音色）为通行表述，本文行文为原创
updated: 2026-09-23
---

::: zh
声音是空气被推了一下。这一下推得多快，决定音高；推得多重，决定强弱；推成什么形状，决定音色。
音乐里所有能描述出来的听感，最后都回到这三件事上。

## 振动怎么变成音

物体振动，空气被反复挤压与松开，这种疏密变化传到耳膜，被听成声音。每秒钟来回振动的次数叫**频率**，
单位是赫兹。人耳能听到的频率范围是 20 Hz 到 20 kHz，上限随年龄增长而下降。

能听到，不等于能当音乐素材。音乐用的音还有三个条件：**音高能辨、能够保持、能够重复**。
敲一下铁皮发出的声音同样在可听范围内，但它每次都不一样，也就无法记谱、无法排练、无法和别人合上。

## 乐音与噪音

| | 乐音 | 噪音 |
|---|---|---|
| 振动 | 有规则、周期性 | 无规则、非周期 |
| 听感 | 有明确的音高 | 音高模糊，只剩下音色与强弱 |
| 常见来源 | 弦、管、簧、人声 | 鼓、钹、沙锤、拍手 |

这里的「噪音」不是贬义。打击乐整类建立在噪音上，而且鼓的音高模糊恰恰是它适合打拍子的原因 ——
音高太明确的乐器一敲下去盖住了旋律，反而添乱。

还有一类两边都占：木鱼、三角铁、锣有音高但不稳定，记谱时通常只写节奏、不写音高。

## 图示：两种振动

```svg
<svg viewBox="0 0 640 226" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同样的时长里，振动的规则程度不同 → 听感完全不同</text>
  </g>

  <g transform="translate(24,40)">
    <rect x="0" y="0" width="592" height="74" rx="3" fill="#17171A" stroke="#343439"/>
    <polyline points="16,37 28,12 40,62 52,12 64,62 76,12 88,62 100,12 112,62 124,12 136,62 148,12 160,62 172,12 184,62 196,12 208,62 220,12 232,62 244,12 256,62 268,12 280,62 292,12 304,62 316,12 328,62 340,12 352,62 364,12 376,62 388,12 400,62 412,12 424,62 436,12 448,62 460,12 472,62 484,12 496,62 508,12 520,62 532,12 544,62 556,12 568,62"
      fill="none" stroke="#5B7FA8" stroke-width="1.4"/>
    <text x="16" y="-6" font-family="system-ui,sans-serif" font-size="12" fill="#5B7FA8">乐音 · 周期性振动（这里画的是方波）</text>
    <line x1="16" y1="68" x2="76" y2="68" stroke="#5B7FA8" stroke-width="1"/>
    <line x1="16" y1="64" x2="16" y2="72" stroke="#5B7FA8" stroke-width="1"/>
    <line x1="76" y1="64" x2="76" y2="72" stroke="#5B7FA8" stroke-width="1"/>
    <text x="84" y="72" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">一个周期</text>
  </g>

  <g transform="translate(24,140)">
    <rect x="0" y="0" width="592" height="74" rx="3" fill="#17171A" stroke="#343439"/>
    <polyline points="16,47 30,18 44,58 58,26 72,64 86,14 100,52 114,33 128,60 142,21 156,49 170,29 184,63 198,16 212,55 226,36 240,44 254,24 268,61 282,19 296,50 310,31 324,57 338,23 352,46 366,28 380,62 394,17 408,53 422,34 436,42 450,25 464,59 478,20 492,51 506,32 520,56 534,22 548,48 562,30 576,45"
      fill="none" stroke="#E07A3F" stroke-width="1.4"/>
    <text x="16" y="-6" font-family="system-ui,sans-serif" font-size="12" fill="#E07A3F">噪音 · 非周期振动（同一时长里找不到重复的形状）</text>
  </g>
</svg>
```

## 音的四项属性

| 属性 | 由什么决定 | 听感上怎么描述 |
|---|---|---|
| 音高 | 频率 | 高 / 低 |
| 音长 | 持续时长 | 长 / 短 |
| 力度 | 振动幅度 | 强 / 弱 |
| 音色 | 泛音构成与起音包络 | 亮 / 暗、厚 / 薄 |

这四项彼此独立：同一个音高可以弹得很轻也可以砸得很重，可以拖成长音也可以点一下就收。
练耳之所以吃力，正因为在真实演奏里这四项在同时变化。而记谱、唱名这两套系统，
本质上就是把这四个变量**拆开分别记录**——五线谱的位置管音高，符头形状管音长，
力度记号管强弱，乐器与演奏法标注管音色。

## 听一听：一串乐音

下面这五个音各自独立、界限分明，而且每一个都能被准确重复出来 ——
这正是「乐音」区别于「声响」的地方。

```audiolab
{"type":"scale","notes":["C4","D4","E4","G4","C5"],"label":"五个乐音","label_en":"Five musical tones","hint":"逐个听：每个音都有稳定、可复述的音高","hint_en":"One by one — every tone has a steady, repeatable pitch","gap":0.42}
```

## 常见误解

- **「声音越大音就越高」** → 不会。音量由振动幅度决定，音高由频率决定，两者互不干涉。把音量拧大，音高一个赫兹都不动。
- **「噪音是形容难听的声音」** → 这里是振动分类，不是审美评价。军鼓打一整个乐章，从头到尾都是噪音。
- **「低音听起来就是音量大」** → 低音指的是频率低，与力度无关。低音区乐器需要更大的振幅才能被听清，那是另一件事。
- **「有音高就能写进谱子」** → 写谱还要音高稳定到能被重复。锣、木鱼因此通常只记节奏。
:::

::: en
A sound is air being pushed. How fast you push decides the pitch; how hard you push decides the loudness;
the shape of the push decides the timbre. Every sensation music can describe comes back to these three things.

## How vibration becomes sound

An object vibrates, air is squeezed and released again and again, and that ripple reaches the eardrum,
where it is heard as sound. The number of back-and-forth cycles per second is the **frequency**, measured in hertz.
Human hearing spans roughly 20 Hz to 20 kHz, with the upper limit falling as we age.

Being audible is not the same as being usable as musical material. A musical tone must also satisfy three
conditions: its **pitch can be identified, held, and repeated**. A scrap of sheet metal struck once is
perfectly audible, but it never sounds the same twice — so it cannot be notated, rehearsed, or played in tune
with anyone else.

## Tones and noise

| | Musical tone | Noise |
|---|---|---|
| Vibration | Regular, periodic | Irregular, aperiodic |
| Perception | A definite pitch | Pitch is blurred; only timbre and loudness remain |
| Typical sources | Strings, pipes, reeds, the voice | Drums, cymbals, shakers, clapping |

"Noise" here is not a value judgement. An entire family of instruments is built on it, and the blurred pitch
of a drum is exactly why it works as a timekeeper: an instrument with a strong, definite pitch would smear
the melody instead.

A third category sits in between. Wood blocks, triangles and gongs have a pitch of sorts, but not a stable one,
so notation for them usually records rhythm and leaves pitch out.

## Diagram: two kinds of vibration

```svg
<svg viewBox="0 0 640 226" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Same duration, different regularity of vibration — completely different results</text>
  </g>

  <g transform="translate(24,40)">
    <rect x="0" y="0" width="592" height="74" rx="3" fill="#17171A" stroke="#343439"/>
    <polyline points="16,37 28,12 40,62 52,12 64,62 76,12 88,62 100,12 112,62 124,12 136,62 148,12 160,62 172,12 184,62 196,12 208,62 220,12 232,62 244,12 256,62 268,12 280,62 292,12 304,62 316,12 328,62 340,12 352,62 364,12 376,62 388,12 400,62 412,12 424,62 436,12 448,62 460,12 472,62 484,12 496,62 508,12 520,62 532,12 544,62 556,12 568,62"
      fill="none" stroke="#5B7FA8" stroke-width="1.4"/>
    <text x="16" y="-6" font-family="system-ui,sans-serif" font-size="12" fill="#5B7FA8">Musical tone — periodic vibration (drawn here as a square wave)</text>
    <line x1="16" y1="68" x2="76" y2="68" stroke="#5B7FA8" stroke-width="1"/>
    <line x1="16" y1="64" x2="16" y2="72" stroke="#5B7FA8" stroke-width="1"/>
    <line x1="76" y1="64" x2="76" y2="72" stroke="#5B7FA8" stroke-width="1"/>
    <text x="84" y="72" font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">one period</text>
  </g>

  <g transform="translate(24,140)">
    <rect x="0" y="0" width="592" height="74" rx="3" fill="#17171A" stroke="#343439"/>
    <polyline points="16,47 30,18 44,58 58,26 72,64 86,14 100,52 114,33 128,60 142,21 156,49 170,29 184,63 198,16 212,55 226,36 240,44 254,24 268,61 282,19 296,50 310,31 324,57 338,23 352,46 366,28 380,62 394,17 408,53 422,34 436,42 450,25 464,59 478,20 492,51 506,32 520,56 534,22 548,48 562,30 576,45"
      fill="none" stroke="#E07A3F" stroke-width="1.4"/>
    <text x="16" y="-6" font-family="system-ui,sans-serif" font-size="12" fill="#E07A3F">Noise — aperiodic vibration (no repeating shape within the same span)</text>
  </g>
</svg>
```

## The four properties of a tone

| Property | Determined by | How we describe it |
|---|---|---|
| Pitch | Frequency | High / low |
| Duration | How long it lasts | Long / short |
| Loudness | Amplitude of vibration | Strong / weak |
| Timbre | Harmonic content and attack envelope | Bright / dark, thick / thin |

These four are independent. The same pitch can be struck gently or hammered; it can be held for bars or
clipped short. Ear training feels hard precisely because in real playing all four move at once.
Notation and solfège exist to **separate the variables**: staff position tracks pitch, note shape tracks
duration, dynamic marks track loudness, and instrument and playing-technique labels track timbre.

## Listen: a row of musical tones

The five tones below are separate, sharply bounded, and each one can be reproduced exactly.
That is what makes them tones rather than mere sounds.

```audiolab
{"type":"scale","notes":["C4","D4","E4","G4","C5"],"label":"五个乐音","label_en":"Five musical tones","hint":"逐个听：每个音都有稳定、可复述的音高","hint_en":"One by one — every tone has a steady, repeatable pitch","gap":0.42}
```

## Common misconceptions

- **"Louder means higher."** No. Loudness comes from amplitude, pitch from frequency; they do not interact. Turn the volume up and the pitch does not move by a single hertz.
- **"Noise means an ugly sound."** It is a classification of vibration, not an aesthetic verdict. A snare drum plays noise for an entire movement.
- **"Bass sounds like it is just louder."** Bass means low frequency, which has nothing to do with loudness. Low instruments need a larger amplitude to be heard clearly — a different matter entirely.
- **"If it has a pitch, it can be notated."** Notation also demands that the pitch be stable enough to repeat, which is why gongs and wood blocks usually get rhythm only.
:::
