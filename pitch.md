---
id: pitch
site: theo
cat: T1
title: 音高
title_en: Pitch
summary: 频率决定音高，但耳朵听的是比例，不是赫兹数
summary_en: Frequency sets the pitch, but the ear hears ratios, not hertz
level: core
tags: [乐理, 声学, 基础]
tags_en: [theory, acoustics, basics]
alias: [频率与音高, pitch, 音的高低]
order: 20
links:
  - "[[concept:sound]]"
  - "[[concept:note-name]]"
  - "[[concept:octave]]"
  - "[[concept:harmonic-series]]"
  - "[[concept:concert-pitch]]"
instances:
  - atepp-003869 | 右手三连音琶音在固定音型上持续整段，音高有任何漂移都会立刻被听出来 | A triplet arpeggio figure held for the whole movement — any drift in pitch is immediately audible
  - mutopia-000280 | 巴赫第一首二部创意曲：两个声部在不同音高上交替陈述同一条主题，可直接对比高低 | Bach's first two-part invention — two voices state the same subject at different pitches, easy to compare
  - mutopia-001727 | 单声部圣咏曲调：每个音都被稳定保持、可以准确重复，音高作为听感最容易被抓住的情形 | A single-line hymn tune — every note is held steadily and can be repeated exactly, the clearest case of pitch as a perception
sources:
  - 频率与音高的对应关系、听觉的对数特性、A4 = 440 Hz 的近代标准，属音乐声学通则
  - 本文行文为原创，未采用任何参考源句式
updated: 2026-09-23
---

::: zh
音高就是频率的听觉对应。话说得简单，但有两处必须掰开：**频率是物理量，音高是心理量**；
而且耳朵对频率的感知**不是线性的**。

## 频率与音高

振动每秒钟来回的次数就是频率。次数翻倍，音高就升高一个 [[concept:octave|八度]]——
这条关系是整座乐理大厦的第一块砖。

但请注意下一步：从 100 Hz 到 200 Hz，是一次八度；从 200 Hz 到 400 Hz，也是一次八度。
两次的赫兹差完全不同（100 与 200），听感上的"距离"却完全一样。这说明耳朵数的不是赫兹，是**比例**。

| 频率 | 与 A4 的关系 | 听感位置 |
|---|---|---|
| 110 Hz | 低两个八度 | 低音区 |
| 220 Hz | 低一个八度 | 中低音区 |
| 440 Hz | 标准音 A4 | 中音区 |
| 880 Hz | 高一个八度 | 高音区 |

音乐里的所有距离概念（音程、音阶、调）都建立在这个比例尺度上。也因此，音高在纸上是**等距的格子**，
在频率上是**成倍增长的数**——两张图不是同一张，混用就会出错。

## 音高是连续的，音名是离散的

人的听觉能分辨出远小于半音的高低差别。而音名体系把这条连续线**切成了若干固定的点**，
就像在一条斜坡上打桩。演奏时的"音不准"，本质就是落点离桩太远。

这也解释了两件事：

- **为什么弦乐器难**——没有品格，每个音都要自己找落点；
- **为什么钢琴看起来简单**——落点已经被造出来了，按下去就是准确的。

而在这两者之外还有一种情况：**滑音、揉弦、人声的过渡**根本不在桩上，它们是桩与桩之间的那段坡。
记谱系统对这一段几乎没有专门的符号，得靠奏法说明或直接听录音。

## 图示：同样的"一个八度"，两种画法

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">上：频率轴（等距 = 等比，每格翻倍）　下：键盘轴（等距 = 十二平均律的半个音）</text>
  </g>

  <g transform="translate(24,44)">
    <rect x="0" y="0" width="592" height="42" rx="3" fill="#17171A" stroke="#343439"/>
    <g stroke="#343439">
      <line x1="74" y1="0" x2="74" y2="42"/><line x1="148" y1="0" x2="148" y2="42"/>
      <line x1="222" y1="0" x2="222" y2="42"/><line x1="296" y1="0" x2="296" y2="42"/>
      <line x1="370" y1="0" x2="370" y2="42"/><line x1="444" y1="0" x2="444" y2="42"/>
      <line x1="518" y1="0" x2="518" y2="42"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="6" y="26">110</text><text x="80" y="26">220</text><text x="154" y="26">440</text>
      <text x="228" y="26">880</text><text x="302" y="26">1760</text><text x="376" y="26">3520</text>
      <text x="450" y="26">7040</text><text x="524" y="26">14080</text>
    </g>
    <text x="6" y="-6" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">频率轴 · 单位 Hz（每格 = 一次八度 = 频率 ×2）</text>
  </g>

  <g transform="translate(24,116)">
    <rect x="0" y="0" width="592" height="42" rx="3" fill="#17171A" stroke="#343439"/>
    <g stroke="#343439">
      <line x1="49" y1="0" x2="49" y2="42"/><line x1="98" y1="0" x2="98" y2="42"/>
      <line x1="148" y1="0" x2="148" y2="42"/><line x1="197" y1="0" x2="197" y2="42"/>
      <line x1="247" y1="0" x2="247" y2="42"/><line x1="296" y1="0" x2="296" y2="42"/>
      <line x1="345" y1="0" x2="345" y2="42"/><line x1="395" y1="0" x2="395" y2="42"/>
      <line x1="444" y1="0" x2="444" y2="42"/><line x1="494" y1="0" x2="494" y2="42"/>
      <line x1="543" y1="0" x2="543" y2="42"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="4" y="26">A2</text><text x="103" y="26">A3</text><text x="202" y="26">A4</text><text x="301" y="26">A5</text><text x="400" y="26">A6</text>
    </g>
    <line x1="197" y1="0" x2="197" y2="42" stroke="#E07A3F" stroke-width="1.6"/>
    <text x="202" y="-6" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">键盘轴 · 单位半音（每格 = 十二平均律的一个半音，A4 = 440 Hz）</text>
  </g>
</svg>
```

## 听一听：音高是连续的

把 12 个半音连着放，能听出这是一条**平滑上升的坡**，而不是 12 个彼此无关的点。
听觉上"两个音之间还有空间"，正是音准能被听出来的原因。

```audiolab
{"type":"scale","notes":["C4","C#4","D4","D#4","E4","F4","F#4","G4","G#4","A4","A#4","B4","C5"],"label":"半音阶（C4 到 C5）","label_en":"Chromatic scale (C4 to C5)","hint":"点「上行」听连续爬升；点「一起响」则会变成一片浑浊的撞击","hint_en":"Try Up for a smooth climb; All together turns into a muddy cluster","gap":0.26,"dur":0.28}
```

## 常见误解

- **「频率越高音越高，所以是一条直线」** → 听觉上不是直线。等距离的频率增长听起来是**越来越挤**的，
  所以频率轴必须画成等比，才与听感一致。
- **「音高是客观的，音准是主观的」** → 反了。音高是主观听感，频率才是客观量。调音器显示的赫兹数是客观的，
  它只是我们用来近似描述音高的工具。
- **「钢琴上的每个键都对应一个固定频率」** → 只在十二平均律下成立。同一套键位如果按纯律调音，各音的赫兹数会整体改变。
:::

::: en
Pitch is the hearing of frequency. That sentence is easy to say, but two things have to be pulled apart:
**frequency is a physical quantity, pitch is a perceptual one**, and the ear does **not** hear frequency linearly.

## Frequency and pitch

Frequency is the number of cycles per second. Double it and the pitch rises by one
[[concept:octave|octave]] — the first brick of the whole theoretical building.

Then notice the next step. Going from 100 Hz to 200 Hz is one octave. Going from 200 Hz to 400 Hz is also
one octave. The two jumps differ completely in hertz (100 versus 200) yet sound the same distance apart.
The ear is counting **ratios**, not hertz.

| Frequency | Relation to A4 | Perceived position |
|---|---|---|
| 110 Hz | two octaves below | low register |
| 220 Hz | one octave below | low-middle register |
| 440 Hz | the reference A4 | middle register |
| 880 Hz | one octave above | high register |

Every distance concept in music — intervals, scales, keys — is built on this ratio scale. That is why pitch
appears as **evenly spaced steps** on paper but as a **doubling sequence** in frequency. The two pictures are
not the same picture, and mixing them up causes real errors.

## Pitch is continuous, note names are discrete

The ear can distinguish differences far smaller than a semitone. Note names **cut that continuous line into
fixed points**, like driving posts into a slope. What players call "out of tune" is simply a landing point
that falls too far from its post.

This explains two things at once:

- **Why string instruments are hard** — there are no frets, so every note has to find its own landing point;
- **Why the piano looks easy** — the landing points are manufactured. Press the key and the pitch is correct.

And there is a third case that is neither: **glissandi, vibrato, and vocal slides** do not sit on posts at all.
They are the slope between two posts. Notation has almost no dedicated symbol for them, so they are conveyed
by performance instructions or simply by listening to a recording.

## Diagram: the same octave, drawn two ways

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Top: frequency axis (even spacing = geometric, each step doubles)  Bottom: keyboard axis (even spacing = one semitone)</text>
  </g>

  <g transform="translate(24,44)">
    <rect x="0" y="0" width="592" height="42" rx="3" fill="#17171A" stroke="#343439"/>
    <g stroke="#343439">
      <line x1="74" y1="0" x2="74" y2="42"/><line x1="148" y1="0" x2="148" y2="42"/>
      <line x1="222" y1="0" x2="222" y2="42"/><line x1="296" y1="0" x2="296" y2="42"/>
      <line x1="370" y1="0" x2="370" y2="42"/><line x1="444" y1="0" x2="444" y2="42"/>
      <line x1="518" y1="0" x2="518" y2="42"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="6" y="26">110</text><text x="80" y="26">220</text><text x="154" y="26">440</text>
      <text x="228" y="26">880</text><text x="302" y="26">1760</text><text x="376" y="26">3520</text>
      <text x="450" y="26">7040</text><text x="524" y="26">14080</text>
    </g>
    <text x="6" y="-6" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">Frequency axis · Hz (one step = one octave = frequency x2)</text>
  </g>

  <g transform="translate(24,116)">
    <rect x="0" y="0" width="592" height="42" rx="3" fill="#17171A" stroke="#343439"/>
    <g stroke="#343439">
      <line x1="49" y1="0" x2="49" y2="42"/><line x1="98" y1="0" x2="98" y2="42"/>
      <line x1="148" y1="0" x2="148" y2="42"/><line x1="197" y1="0" x2="197" y2="42"/>
      <line x1="247" y1="0" x2="247" y2="42"/><line x1="296" y1="0" x2="296" y2="42"/>
      <line x1="345" y1="0" x2="345" y2="42"/><line x1="395" y1="0" x2="395" y2="42"/>
      <line x1="444" y1="0" x2="444" y2="42"/><line x1="494" y1="0" x2="494" y2="42"/>
      <line x1="543" y1="0" x2="543" y2="42"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64">
      <text x="4" y="26">A2</text><text x="103" y="26">A3</text><text x="202" y="26">A4</text><text x="301" y="26">A5</text><text x="400" y="26">A6</text>
    </g>
    <line x1="197" y1="0" x2="197" y2="42" stroke="#E07A3F" stroke-width="1.6"/>
    <text x="202" y="-6" font-family="system-ui,sans-serif" font-size="11.5" fill="#E07A3F">Keyboard axis · semitones (one step = one semitone; A4 = 440 Hz)</text>
  </g>
</svg>
```

## Listen: pitch is continuous

Play the twelve semitones in a row and you hear **a smooth rising slope**, not twelve unrelated points.
The sense that "there is space between two notes" is exactly why intonation can be heard at all.

```audiolab
{"type":"scale","notes":["C4","C#4","D4","D#4","E4","F4","F#4","G4","G#4","A4","A#4","B4","C5"],"label":"半音阶（C4 到 C5）","label_en":"Chromatic scale (C4 to C5)","hint":"点「上行」听连续爬升；点「一起响」则会变成一片浑浊的撞击","hint_en":"Try Up for a smooth climb; All together turns into a muddy cluster","gap":0.26,"dur":0.28}
```

## Common misconceptions

- **"Higher frequency, so it is a straight line."** Perceptually it is not. Equal frequency steps sound
  **increasingly crowded**, which is why the frequency axis has to be drawn geometric to match hearing.
- **"Pitch is objective, intonation is subjective."** The reverse. Pitch is the perception; frequency is the
  objective quantity. A tuner's hertz reading is objective, but it is only a tool for approximating pitch.
- **"Every key on a piano has one fixed frequency."** That holds only in twelve-tone equal temperament.
  Retune the same keyboard to just intonation and every hertz value shifts.
:::
