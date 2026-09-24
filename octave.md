---
id: octave
site: theo
cat: T1
title: 八度
title_en: Octave
summary: 频率翻倍的那两个音，被听成同一类音的高低两级
summary_en: Two tones a frequency doubling apart are heard as the same class of note, one level higher
level: core
tags: [乐理, 音程, 基础]
tags_en: [theory, interval, basics]
alias: [八度音, octave]
order: 40
links:
  - "[[concept:pitch]]"
  - "[[concept:note-name]]"
  - "[[concept:harmonic-series]]"
  - "[[concept:register]]"
  - "[[concept:perfect-interval]]"
instances:
  - giantmidi-006222 | 音阶练习：上行到第八个音名，就是同一个音名的高八度，能直接听到「回来了」 | A scale exercise — walking up to the eighth name brings the same name back an octave higher — you hear the return
  - mutopia-000287 | 巴赫第八首二部创意曲：两个声部先后陈述同一条主题，高低两层分得清楚 | Bach's eighth two-part invention — the same subject stated in turn by two voices, the two levels clearly separated
  - cyberhymnal-000695 | 管风琴圣咏：管风琴同时拉出 8′ 与 4′ 音栓，就是两个八度同时发声 | An organ hymn — pulling the 8-foot and 4-foot stops sounds two octaves at once
sources:
  - 八度频率比 2:1、泛音列中八度重合、八度叠奏的用法，属通行乐理与配器常识
  - 本文行文为原创，未采用参考源句式
updated: 2026-09-23
---

::: zh
八度是乐理里唯一一个**同时属于物理和心理**的概念：物理上它就是频率翻倍；
心理上它听起来像"同一个音，只是高了一层"。这条双重身份，直接解释了为什么音名只有七个字母却够用。

## 频率翻倍

给出一个音，把一个音放在它频率的两倍处，得到的音与原来相差一个八度。
A4 是 440 Hz，A5 就是 880 Hz，A3 就是 220 Hz。

八度之上再翻倍是第二个八度，往下除以 2 同理。所以严格说，八度不只指"相邻的那两个"——
A2 与 A6 相隔四个八度，它们仍互为八度关系。

## 为什么听起来像"同一个音"

因为两个音的泛音列**大面积重合**。假设低音的基频是 100 Hz，它的泛音是 200、300、400、500……
高音（200 Hz）的基频正好落在低音的第一个泛音上，而高音的泛音 400、600、800……也全是低音泛音里的成员。

听同一个声音的重合部分，自然觉得"是一家的"。反过来，纯五度（频率比 3:2）的重合度也很高，
所以它听起来也干净 —— 但五度不会让人觉得是同一个音，因为它的重合不如八度彻底。

八度是所有音程里重合最彻底的关系，没有比它更彻底的。

## 图示：泛音列里的八度相遇

```svg
<svg viewBox="0 0 640 268" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">以 C2 为基音的泛音列（只画前 8 个分音）· 高八度的基音正好落在低音的第二个分音上</text>
  </g>

  <g transform="translate(48,46)">
    <line x1="0" y1="150" x2="544" y2="150" stroke="#343439" stroke-width="1.2"/>
    <g stroke="#343439">
      <line x1="0" y1="150" x2="0" y2="156"/><line x1="78" y1="150" x2="78" y2="156"/>
      <line x1="156" y1="150" x2="156" y2="156"/><line x1="234" y1="150" x2="234" y2="156"/>
      <line x1="312" y1="150" x2="312" y2="156"/><line x1="390" y1="150" x2="390" y2="156"/>
      <line x1="468" y1="150" x2="468" y2="156"/>
    </g>
    <g>
      <rect x="-14" y="90" width="28" height="60" rx="2" fill="#5B7FA8" opacity=".9"/>
      <rect x="64" y="62" width="28" height="88" rx="2" fill="#E07A3F" opacity=".9"/>
      <rect x="142" y="74" width="28" height="76" rx="2" fill="#5B7FA8" opacity=".45"/>
      <rect x="220" y="96" width="28" height="54" rx="2" fill="#5B7FA8" opacity=".45"/>
      <rect x="298" y="106" width="28" height="44" rx="2" fill="#5B7FA8" opacity=".45"/>
      <rect x="376" y="112" width="28" height="38" rx="2" fill="#5B7FA8" opacity=".45"/>
      <rect x="454" y="118" width="28" height="32" rx="2" fill="#5B7FA8" opacity=".45"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="82">C2</text><text x="78" y="54">C3</text><text x="156" y="66">G3</text>
      <text x="234" y="88">C4</text><text x="312" y="98">E4</text><text x="390" y="104">G4</text>
      <text x="468" y="110">B♭4</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="172">1</text><text x="78" y="172">2</text><text x="156" y="172">3</text>
      <text x="234" y="172">4</text><text x="312" y="172">5</text><text x="390" y="172">6</text>
      <text x="468" y="172">7</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="184" x2="78" y2="184"/>
      <line x1="0" y1="180" x2="0" y2="188"/>
      <line x1="78" y1="180" x2="78" y2="188"/>
    </g>
    <text x="88" y="188" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">C2 → C3：一个八度，频率 ×2</text>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="204" x2="234" y2="204"/>
      <line x1="234" y1="200" x2="234" y2="208"/>
    </g>
    <text x="244" y="208" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C2 → C4：两个八度，频率 ×4</text>
  </g>
</svg>
```

## 音名为什么只要七个字母

因为八度之上的音名会**原样重复**：C D E F G A B 走完一轮，下一个音又叫 C。
如果没有这条约定，字母早就用光了。所以严格说，音名要配合**八度编号**才能唯一确定一个音高
（C4 与 C5 是不同的音），但**音名本身只有一个**。

这也解释了为什么调性、和弦、音阶的名称通常只写音名而不写八度：
它们描述的是"结构"，结构在哪个八度都成立。

## 八度在写作里的三个用途

- **加厚**：同一旋律用八度叠奏（钢琴双手差八度、弦乐组高低八度齐奏），音量变大而旋律轮廓不变，这是最常见的手法。
- **分层**：把一条旋律分给不同八度，用来区分"谁在说"——低八度像旁白，高八度像提问。
- **逼近极限**：极端音区里八度是唯一的扩张手段，因为在那个高度上再往上已经听不出明确音高了。

## 听一听：八度

先听下面这个音，再听它上面八度的音，最后听两个一起响 —— 第三下听起来最"空"，
因为两个音之间几乎没有需要融合的东西可融合。

```audiolab
{"type":"interval","a":"C4","b":"C5","label":"纯八度 C4–C5","label_en":"Perfect octave C4–C5","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E4 再听一次：间隔变小了，融合感反而下降，那正是三度带进来的色彩。","hint2_en":"Now swap b to E4: the gap shrinks, yet the blend weakens — that is the colour a third brings in."}
```

```notation
{"clef":"treble","notes":["C4","C5"],"caption":"C4 与 C5：频率比 2:1，八度","caption_en":"C4 and C5: a 2:1 frequency ratio, one octave"}
```

## 常见误解

- **「八度是最远的音程」** → 单音程里它确实是最大的（八度），但它是最容易辨认的之一，因为它听起来像同一个音。
- **「所有八度听起来都差不多」** → 结构相同、听感不同。低音区的八度厚实、容易糊在一起，高音区的八度会只剩两片细线。
- **「八度音程只有一种」** → 纯八度只有一种，但"跨越一个八度"可以指任何八度关系的两个音；它们全部属于 [[concept:perfect-interval|纯音程]]。
- **「八度就是十二个半音」** → 只在十二平均律下成立。八度的定义始终是频率比 2:1，十二个半音是把这个比例切开的**一种**方式。
:::

::: en
The octave is the one concept in music theory that belongs to **physics and psychology at once**: physically it
is a doubling of frequency, perceptually it sounds like "the same note, one level up". That double identity
explains why seven letters are enough for an entire naming system.

## A doubling of frequency

Take a tone and place another at exactly twice its frequency: the two are an octave apart. A4 is 440 Hz,
so A5 is 880 Hz and A3 is 220 Hz.

Double again for the next octave up, halve for the next down. Strictly speaking, then, an octave is not only
"the neighbouring pair": A2 and A6 are four octaves apart and still stand in an octave relationship.

## Why it sounds like "the same note"

Because the two tones' harmonic series **overlap heavily**. Give the lower tone a fundamental of 100 Hz; its
harmonics are 200, 300, 400, 500 and so on. The upper tone's fundamental at 200 Hz lands exactly on the lower
tone's first harmonic, and the upper tone's own harmonics — 400, 600, 800 — are all members of the lower set.

Hearing so much shared material, the ear concludes "same family". A perfect fifth (ratio 3:2) also overlaps
strongly and sounds clean for the same reason, but nobody mistakes a fifth for one note, because its overlap
is less complete than the octave's.

The octave is the most complete overlap any interval can have.

## Diagram: where octaves meet in the harmonic series

```svg
<svg viewBox="0 0 640 268" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Harmonic series on C2 (first 8 partials) · the upper octave's fundamental lands on the second partial</text>
  </g>

  <g transform="translate(48,46)">
    <line x1="0" y1="150" x2="544" y2="150" stroke="#343439" stroke-width="1.2"/>
    <g stroke="#343439">
      <line x1="0" y1="150" x2="0" y2="156"/><line x1="78" y1="150" x2="78" y2="156"/>
      <line x1="156" y1="150" x2="156" y2="156"/><line x1="234" y1="150" x2="234" y2="156"/>
      <line x1="312" y1="150" x2="312" y2="156"/><line x1="390" y1="150" x2="390" y2="156"/>
      <line x1="468" y1="150" x2="468" y2="156"/>
    </g>
    <g>
      <rect x="-14" y="90" width="28" height="60" rx="2" fill="#5B7FA8" opacity=".9"/>
      <rect x="64" y="62" width="28" height="88" rx="2" fill="#E07A3F" opacity=".9"/>
      <rect x="142" y="74" width="28" height="76" rx="2" fill="#5B7FA8" opacity=".45"/>
      <rect x="220" y="96" width="28" height="54" rx="2" fill="#5B7FA8" opacity=".45"/>
      <rect x="298" y="106" width="28" height="44" rx="2" fill="#5B7FA8" opacity=".45"/>
      <rect x="376" y="112" width="28" height="38" rx="2" fill="#5B7FA8" opacity=".45"/>
      <rect x="454" y="118" width="28" height="32" rx="2" fill="#5B7FA8" opacity=".45"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="82">C2</text><text x="78" y="54">C3</text><text x="156" y="66">G3</text>
      <text x="234" y="88">C4</text><text x="312" y="98">E4</text><text x="390" y="104">G4</text>
      <text x="468" y="110">B♭4</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="172">1</text><text x="78" y="172">2</text><text x="156" y="172">3</text>
      <text x="234" y="172">4</text><text x="312" y="172">5</text><text x="390" y="172">6</text>
      <text x="468" y="172">7</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="184" x2="78" y2="184"/>
      <line x1="0" y1="180" x2="0" y2="188"/>
      <line x1="78" y1="180" x2="78" y2="188"/>
    </g>
    <text x="88" y="188" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">C2 to C3: one octave, frequency x2</text>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="204" x2="234" y2="204"/>
      <line x1="234" y1="200" x2="234" y2="208"/>
    </g>
    <text x="244" y="208" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">C2 to C4: two octaves, frequency x4</text>
  </g>
</svg>
```

## Why seven letters are enough

Because above an octave the names **repeat unchanged**: C D E F G A B runs out and the next note is called C
again. Without this convention the alphabet would have been exhausted long ago. Strictly, a note name needs an
**octave number** to pin down a single pitch (C4 and C5 are different pitches), but there is still only **one
name** for the letter.

This is also why keys, chords and scales are normally named without octave numbers: they describe structure,
and structure holds at any octave.

## Three uses of the octave in writing

- **Thickening**: doubling a melody at the octave (piano hands an octave apart, string sections in parallel).
  The volume grows while the melodic outline stays identical — the most common device of all.
- **Layering**: giving a melody to different octaves to distinguish who is speaking — the lower octave reads
  as narration, the upper as a question.
- **Pushing the limits**: at extreme registers the octave is the only way to expand, because higher than that
  the ear stops hearing a definite pitch at all.

## Listen: the octave

Hear the lower tone, then the tone an octave above, then both together. The third one sounds emptiest, because
there is almost nothing between the two tones that needs blending.

```audiolab
{"type":"interval","a":"C4","b":"C5","label":"纯八度 C4–C5","label_en":"Perfect octave C4–C5","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 E4 再听一次：间隔变小了，融合感反而下降，那正是三度带进来的色彩。","hint2_en":"Now swap b to E4: the gap shrinks, yet the blend weakens — that is the colour a third brings in."}
```

```notation
{"clef":"treble","notes":["C4","C5"],"caption":"C4 与 C5：频率比 2:1，八度","caption_en":"C4 and C5: a 2:1 frequency ratio, one octave"}
```

## Common misconceptions

- **"The octave is the farthest interval."** It is the largest simple interval, yet one of the easiest to identify — precisely because it sounds like the same note.
- **"All octaves sound alike."** Same structure, different impression. Low octaves are thick and smear together easily; high octaves thin out into two fine lines.
- **"There is only one kind of octave interval."** There is only one perfect octave, but "spanning an octave" can describe any pair in that relationship; they all belong to [[concept:perfect-interval|perfect intervals]].
- **"An octave is twelve semitones."** Only in twelve-tone equal temperament. The octave is always the 2:1 ratio; twelve semitones are **one** way of slicing it up.
:::
