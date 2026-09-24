---
id: major-minor-interval
site: theo
cat: T2
title: 大音程与小音程
title_en: Major and Minor Intervals
summary: 度数相同、音数差一个半音，就分出了大与小
summary_en: Same degree, one semitone apart in size — that is all that separates major from minor
level: core
tags: [乐理, 音程, 基础]
tags_en: [theory, interval, basics]
alias: [大三度, 小三度, 大六度, 小六度, major interval]
order: 16
links:
  - "[[concept:interval]]"
  - "[[concept:interval-number]]"
  - "[[concept:semitone]]"
  - "[[concept:perfect-interval]]"
  - "[[concept:triad]]"
  - "[[concept:scale]]"
instances:
  - mutopia-000049 | 《绿袖子》开头的上行跳进就是小三度，是"小"这一侧最常被引用的实例 | The rising leap that opens Greensleeves is a minor third — the most quoted example on the minor side
  - giantmidi-006222 | 琶音练习把大小三和弦的音逐个弹出，大三度与小三度的差别在同一组材料里直接对照 | Arpeggio exercises spell out major and minor triads, placing major and minor thirds side by side
  - mutopia-001727 | 《奇异恩典》开头的纯四度跳进可作对照：它属于纯音程，不参与大小之分 | The perfect fourth that opens Amazing Grace is the control case — it belongs to the perfect family and takes no major or minor
sources:
  - 大/小音程定义为"同度数下音数相差一个半音"，属乐理通则
  - 大小音程只出现在二、三、六、七度，一、四、五、八度为纯音程，为通行表述
updated: 2026-09-23
---

::: zh
大与小不是形容词，是一次**一分为二的划分**：同一个度数下，音数多的那一个叫**大**，
少一个半音的叫**小**。C–E 是四个半音，叫大三度；C–E♭ 是三个半音，叫小三度。
度数一样，名字只差一个字，听感却几乎相反 —— 这就是大小之分值得单独成条的原因。

## 哪些度数会分大小

不是所有度数都分。规则很干净：

| 度数 | 会分大小吗 | 两个成员 |
|---|---|---|
| 二度 | ✅ | 大二度（2 半音）· 小二度（1 半音） |
| 三度 | ✅ | 大三度（4 半音）· 小三度（3 半音） |
| 六度 | ✅ | 大六度（9 半音）· 小六度（8 半音） |
| 七度 | ✅ | 大七度（11 半音）· 小七度（10 半音） |
| 一 / 四 / 五 / 八度 | ❌ | 只有"纯"，没有大小（见 [[concept:perfect-interval|纯音程]]） |

这四组正好对应 [[concept:scale|音阶]] 里的四个"变数位置"。大调与小调的唯一差别，
就是把其中三组（三、六、七度）从"大"换成"小"。

## 大与小只差一个半音，为什么听起来差那么多

因为**三等分**问题。一个八度被分成三段：主音到三度、三度到五度、五度到八度。
三度落在哪一侧，决定了整个三和弦的明暗：

- 大三度 + 小三度 = **大三和弦**（明亮、稳定）
- 小三度 + 大三度 = **小三和弦**（暗淡、内敛）

两种三和弦用的是同样的三个音级名，唯一的差别就是那一个半音落在哪一段里。
这一层直接通向 [[concept:triad|三和弦]]，也是流行音乐里"换大小调"最直接的开关。

## 图示：大小之别，一个半音

```svg
<svg viewBox="0 0 640 230" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">每格 = 一个半音 · 度数相同，格数差一，就是大与小的全部差别</text>
  </g>

  <g transform="translate(32,52)">
    <g font-family="system-ui,sans-serif" font-size="11.5" fill="#F2EEE6">
      <text x="0" y="0">小三度 C–E♭</text>
      <text x="0" y="52">大三度 C–E</text>
      <text x="0" y="104">小六度 C–A♭</text>
      <text x="0" y="156">大六度 C–A</text>
    </g>
    <g>
      <g transform="translate(150,0)">
        <rect x="0" y="-11" width="84" height="16" rx="2" fill="#5B7FA8" opacity=".85"/>
        <g stroke="#343439">
          <line x1="28" y1="-13" x2="28" y2="7"/><line x1="56" y1="-13" x2="56" y2="7"/>
        </g>
        <text x="90" y="2" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">3 个半音</text>
      </g>
      <g transform="translate(150,52)">
        <rect x="0" y="-11" width="112" height="16" rx="2" fill="#E07A3F" opacity=".85"/>
        <g stroke="#343439">
          <line x1="28" y1="-13" x2="28" y2="7"/><line x1="56" y1="-13" x2="56" y2="7"/>
          <line x1="84" y1="-13" x2="84" y2="7"/>
        </g>
        <text x="118" y="2" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">4 个半音</text>
      </g>
      <g transform="translate(150,104)">
        <rect x="0" y="-11" width="224" height="16" rx="2" fill="#5B7FA8" opacity=".85"/>
        <g stroke="#343439">
          <line x1="28" y1="-13" x2="28" y2="7"/><line x1="56" y1="-13" x2="56" y2="7"/>
          <line x1="84" y1="-13" x2="84" y2="7"/><line x1="112" y1="-13" x2="112" y2="7"/>
          <line x1="140" y1="-13" x2="140" y2="7"/><line x1="168" y1="-13" x2="168" y2="7"/>
          <line x1="196" y1="-13" x2="196" y2="7"/>
        </g>
        <text x="230" y="2" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">8 个半音</text>
      </g>
      <g transform="translate(150,156)">
        <rect x="0" y="-11" width="252" height="16" rx="2" fill="#E07A3F" opacity=".85"/>
        <g stroke="#343439">
          <line x1="28" y1="-13" x2="28" y2="7"/><line x1="56" y1="-13" x2="56" y2="7"/>
          <line x1="84" y1="-13" x2="84" y2="7"/><line x1="112" y1="-13" x2="112" y2="7"/>
          <line x1="140" y1="-13" x2="140" y2="7"/><line x1="168" y1="-13" x2="168" y2="7"/>
          <line x1="196" y1="-13" x2="196" y2="7"/><line x1="224" y1="-13" x2="224" y2="7"/>
        </g>
        <text x="258" y="2" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">9 个半音</text>
      </g>
    </g>
  </g>
</svg>
```

## 听一听：大三度与小三度

只差一个半音，一个是"亮"，一个是"暗"。这一对是全部和声色彩的总开关。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度 C–E（4 个半音）","label_en":"Major third C–E (4 semitones)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E♭4 就是小三度（3 个半音）—— 同一度数，只差一个半音，色彩完全反过来。","hint2_en":"Set b to E♭4 for a minor third (3 semitones) — same degree, one semitone less, opposite colour."}
```

```notation
{"clef":"treble","notes":[["C4","E4"],["C4","Eb4"]],"caption":"左：大三度 C–E　右：小三度 C–E♭","caption_en":"Left: major third C–E. Right: minor third C–E♭"}
```

## 常见误解

- **「大就是音量大」** → 完全无关。这里的"大"指音数多一个半音，与力度没有关系。
- **「所有音程都有大小两种」** → 一、四、五、八度只有"纯"。它们再宽或再窄，用的是增、减，不是大小。
- **「小三度比大三度低」** → 两者起点相同，只是终点低一个半音。大三度听起来更宽，不是更高。
- **「大小调的区别在音阶的调号」** → 更本质的区别是三、六、七度用了"大"还是"小"的那一个。调号只是结果。
:::

::: en
Major and minor are not adjectives but a **two-way split**: at the same degree, the wider version is called
**major**, and the one a semitone narrower is **minor**. C–E spans four semitones and is a major third;
C–E♭ spans three and is a minor third. One letter of the name changes, and the sound almost inverts — which is
why this split deserves its own entry.

## Which degrees split

Not all of them do, and the rule is tidy:

| Degree | Splits? | The two members |
|---|---|---|
| second | yes | major second (2 semitones) · minor second (1) |
| third | yes | major third (4) · minor third (3) |
| sixth | yes | major sixth (9) · minor sixth (8) |
| seventh | yes | major seventh (11) · minor seventh (10) |
| unison / fourth / fifth / octave | no | perfect only — see [[concept:perfect-interval|perfect intervals]] |

Those four groups are exactly the four variable positions in a [[concept:scale|scale]]. The only difference
between a major and a minor scale is that three of them (third, sixth, seventh) switch from major to minor.

## One semitone apart, yet worlds apart

Because of a **three-way division**. An octave splits into three stretches: tonic to third, third to fifth,
fifth to octave. Which side the third falls on decides the whole triad's light or shade:

- major third + minor third = a **major triad** (bright, stable)
- minor third + major third = a **minor triad** (dark, inward)

Both triads use the same three letter names. The only difference is which stretch that one semitone falls into.
This leads straight to [[concept:triad|triads]], and it is the switch behind every key change from major to
minor in popular music.

## Diagram: major and minor, one semitone apart

```svg
<svg viewBox="0 0 640 230" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">One cell = one semitone · same degree, one cell fewer, and that is the whole difference</text>
  </g>

  <g transform="translate(32,52)">
    <g font-family="system-ui,sans-serif" font-size="11.5" fill="#F2EEE6">
      <text x="0" y="0">minor third C–E♭</text>
      <text x="0" y="52">major third C–E</text>
      <text x="0" y="104">minor sixth C–A♭</text>
      <text x="0" y="156">major sixth C–A</text>
    </g>
    <g>
      <g transform="translate(150,0)">
        <rect x="0" y="-11" width="84" height="16" rx="2" fill="#5B7FA8" opacity=".85"/>
        <g stroke="#343439">
          <line x1="28" y1="-13" x2="28" y2="7"/><line x1="56" y1="-13" x2="56" y2="7"/>
        </g>
        <text x="90" y="2" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">3 semitones</text>
      </g>
      <g transform="translate(150,52)">
        <rect x="0" y="-11" width="112" height="16" rx="2" fill="#E07A3F" opacity=".85"/>
        <g stroke="#343439">
          <line x1="28" y1="-13" x2="28" y2="7"/><line x1="56" y1="-13" x2="56" y2="7"/>
          <line x1="84" y1="-13" x2="84" y2="7"/>
        </g>
        <text x="118" y="2" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">4 semitones</text>
      </g>
      <g transform="translate(150,104)">
        <rect x="0" y="-11" width="224" height="16" rx="2" fill="#5B7FA8" opacity=".85"/>
        <g stroke="#343439">
          <line x1="28" y1="-13" x2="28" y2="7"/><line x1="56" y1="-13" x2="56" y2="7"/>
          <line x1="84" y1="-13" x2="84" y2="7"/><line x1="112" y1="-13" x2="112" y2="7"/>
          <line x1="140" y1="-13" x2="140" y2="7"/><line x1="168" y1="-13" x2="168" y2="7"/>
          <line x1="196" y1="-13" x2="196" y2="7"/>
        </g>
        <text x="230" y="2" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">8 semitones</text>
      </g>
      <g transform="translate(150,156)">
        <rect x="0" y="-11" width="252" height="16" rx="2" fill="#E07A3F" opacity=".85"/>
        <g stroke="#343439">
          <line x1="28" y1="-13" x2="28" y2="7"/><line x1="56" y1="-13" x2="56" y2="7"/>
          <line x1="84" y1="-13" x2="84" y2="7"/><line x1="112" y1="-13" x2="112" y2="7"/>
          <line x1="140" y1="-13" x2="140" y2="7"/><line x1="168" y1="-13" x2="168" y2="7"/>
          <line x1="196" y1="-13" x2="196" y2="7"/><line x1="224" y1="-13" x2="224" y2="7"/>
        </g>
        <text x="258" y="2" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">9 semitones</text>
      </g>
    </g>
  </g>
</svg>
```

## Listen: major third against minor third

One semitone apart: one is bright, the other dark. This pair is the master switch of harmonic colour.

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"大三度 C–E（4 个半音）","label_en":"Major third C–E (4 semitones)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E♭4 就是小三度（3 个半音）—— 同一度数，只差一个半音，色彩完全反过来。","hint2_en":"Set b to E♭4 for a minor third (3 semitones) — same degree, one semitone less, opposite colour."}
```

```notation
{"clef":"treble","notes":[["C4","E4"],["C4","Eb4"]],"caption":"左：大三度 C–E　右：小三度 C–E♭","caption_en":"Left: major third C–E. Right: minor third C–E♭"}
```

## Common misconceptions

- **"Major means louder."** Unrelated. Here it means one semitone wider; loudness plays no part.
- **"Every interval comes in major and minor."** Unisons, fourths, fifths and octaves are perfect only. Their wider and narrower forms are augmented and diminished.
- **"A minor third is lower."** Both start on the same note; only the endpoint drops a semitone. The major third sounds wider, not higher.
- **"Major and minor differ by the key signature."** The real difference is whether the third, sixth and seventh use the major or the minor form. The key signature is a consequence.
:::
