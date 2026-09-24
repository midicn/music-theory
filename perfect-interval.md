---
id: perfect-interval
site: theo
cat: T2
title: 纯音程
title_en: Perfect Intervals
summary: 一、四、五、八度不叫大小而叫纯，因为它们的频率比最简
summary_en: Unisons, fourths, fifths and octaves are perfect rather than major or minor — their ratios are the simplest
level: core
tags: [乐理, 音程, 和声]
tags_en: [theory, interval, harmony]
alias: [纯四度, 纯五度, 纯八度, perfect fifth]
order: 18
links:
  - "[[concept:interval]]"
  - "[[concept:major-minor-interval]]"
  - "[[concept:harmonic-series]]"
  - "[[concept:consonance]]"
  - "[[concept:circle-of-fifths]]"
instances:
  - thesession-019704 | 《小星星》开头就是一次纯五度下行，整首曲子由它起头 | Twinkle Little Star opens with a descending perfect fifth that sets up the whole tune
  - mutopia-001727 | 《奇异恩典》开头的纯四度跳进：与五度只差一个转位方向 | Amazing Grace opens with a perfect fourth — a fifth seen from the other side
  - giantmidi-006222 | 音阶练习走完一轮，末音与首音之间就是纯八度 | A scale exercise ends where the first note returns an octave higher — the perfect octave
sources:
  - 纯音程的频率比（1:1 / 4:3 / 3:2 / 2:1）与泛音列中的位置，属音乐声学通则
  - 纯音程只有增减、不加大小的命名规则，为通行乐理表述
updated: 2026-09-23
---

::: zh
一、四、五、八度这四种音程不分大、小，而用另一个字：**纯**。这不是命名上的例外，
而是它们**在物理上确实属于另一类**。

## 频率比最简的四个

[[concept:harmonic-series|泛音列]]里，最早出现的几个比例就是这四个：

| 音程 | 频率比 | 泛音列中的位置 |
|---|---|---|
| 纯一度 | 1 : 1 | 同一个音 |
| 纯八度 | 2 : 1 | 第 1 与第 2 分音 |
| 纯五度 | 3 : 2 | 第 2 与第 3 分音 |
| 纯四度 | 4 : 3 | 第 3 与第 4 分音 |

比例越简单，两个音的泛音重合越多，听起来越"空"、越没有色彩倾向。
[[concept:major-minor-interval|三度、六度、七度]]之所以有大小之分，就是因为它们的比例
（如 5:4、6:5）复杂一些，才有了"性格"。**纯音程没有性格**，这正是它们的特征。

## 纯音程的增减规则

纯音程不能变大变小，但可以变宽变窄：

| 变化 | 名称 | 例 |
|---|---|---|
| 宽一个半音 | 增音程 | 纯五度 → 增五度 |
| 窄一个半音 | 减音程 | 纯五度 → 减五度 |

一个小陷阱：**纯四度宽一个半音是增四度**，而这个音程与**减五度**音数相同（都是 6 个半音），
只是写法与倾向不同。这一点见 [[concept:augmented-diminished|增音程与减音程]] 与
[[concept:enharmonic|等音]]。

## 五度为什么支配着调性

纯五度的比例 3:2 是所有简单比例里**唯一的"非八度"成员**。往上叠五度，
12 次之后几乎回到出发点（这就是 [[concept:circle-of-fifths|五度圈]]），
调性体系里的近关系调、调号顺序、属功能全部建立在这条链上。

## 图示：四个纯音程在泛音列上的位置

```svg
<svg viewBox="0 0 640 226" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">分音序号越大，与相邻分音构成的音程比例越复杂</text>
  </g>

  <g transform="translate(48,52)">
    <line x1="0" y1="96" x2="520" y2="96" stroke="#343439" stroke-width="1.2"/>
    <g>
      <rect x="-12" y="76" width="24" height="20" rx="2" fill="#E07A3F"/>
      <rect x="116" y="52" width="24" height="44" rx="2" fill="#5B7FA8"/>
      <rect x="244" y="40" width="24" height="56" rx="2" fill="#5B7FA8"/>
      <rect x="372" y="32" width="24" height="64" rx="2" fill="#5B7FA8"/>
      <rect x="500" y="26" width="24" height="70" rx="2" fill="#5B7FA8"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="70">C3</text><text x="128" y="46">C4</text>
      <text x="256" y="34">G4</text><text x="384" y="26">C5</text><text x="512" y="20">E5</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="114">1</text><text x="128" y="114">2</text><text x="256" y="114">3</text>
      <text x="384" y="114">4</text><text x="512" y="114">5</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="134" x2="128" y2="134"/>
      <line x1="0" y1="130" x2="0" y2="138"/><line x1="128" y1="130" x2="128" y2="138"/>
    </g>
    <text x="138" y="138" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">1–2：纯八度（2:1）</text>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
      <line x1="128" y1="158" x2="256" y2="158"/>
      <line x1="128" y1="154" x2="128" y2="162"/><line x1="256" y1="154" x2="256" y2="162"/>
    </g>
    <text x="138" y="162" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">2–3：纯五度（3:2）　3–4：纯四度（4:3）</text>
  </g>
</svg>
```

## 听一听：纯五度

纯五度听起来"空"，因为它几乎没有需要解决的张力。这种"空"正是它在世界各地的乐器定弦、
调音与和声骨架里被反复使用的原因。

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"纯五度 C–G（7 个半音）","label_en":"Perfect fifth C–G (7 semitones)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 F4 就是纯四度（5 个半音）—— 五度的转位。","hint2_en":"Set b to F4 for a perfect fourth (5 semitones) — the inversion of a fifth."}
```

```notation
{"clef":"treble","notes":["C4","G4","C5"],"caption":"C–G 纯五度，再上行到 C5 补成一个八度","caption_en":"C–G, a perfect fifth, then up to C5 to complete the octave"}
```

## 常见误解

- **「纯的意思是音准很准」** → 这里的"纯"指频率比最简（2:1、3:2、4:3），与演奏音准无关。
- **「纯音程没有增减」** → 有。纯五度宽一个半音是增五度，窄一个是减五度。
- **「纯四度听起来比纯五度更协和，因为它更窄」** → 更窄不等于更协和。协和度由比例简单程度决定，四度与五度地位相当，只是方向相反。
- **「三度也是纯的才更协和」** → 三度的比例是 5:4 与 6:5，本来就复杂于四度五度，所以才有大小之分与色彩差异。
:::

::: en
Unisons, fourths, fifths and octaves take neither major nor minor but a different word: **perfect**. This is
not a naming quirk; they genuinely belong to **a different physical class**.

## The four simplest ratios

In the [[concept:harmonic-series|harmonic series]], these are the first ratios to appear:

| Interval | Ratio | Position in the series |
|---|---|---|
| perfect unison | 1 : 1 | the same tone |
| perfect octave | 2 : 1 | partials 1 and 2 |
| perfect fifth | 3 : 2 | partials 2 and 3 |
| perfect fourth | 4 : 3 | partials 3 and 4 |

The simpler the ratio, the more the two tones' partials overlap, and the emptier and more colourless the sound.
Thirds, sixths and sevenths have **major and minor** forms precisely because their ratios (5:4, 6:5) are more
complex — complexity is what gives them character. **Perfect intervals have no character**, and that is their
defining feature.

## Augmented and diminished

Perfect intervals cannot become major or minor, but they can widen or narrow:

| Change | Name | Example |
|---|---|---|
| one semitone wider | augmented | perfect fifth → augmented fifth |
| one semitone narrower | diminished | perfect fifth → diminished fifth |

One trap: **a perfect fourth widened by a semitone is an augmented fourth**, and that interval has the same
size as a **diminished fifth** (6 semitones each) while being spelled and tending differently — see
[[concept:augmented-diminished|augmented and diminished]] and [[concept:enharmonic|enharmonic]].

## Why the fifth governs tonality

The perfect fifth's 3:2 is the only non-octave member among the simplest ratios. Stack fifths and after twelve
steps you arrive almost back where you started — that is the [[concept:circle-of-fifths|circle of fifths]], and
the whole key system (related keys, the order of key signatures, dominant function) is built on that chain.

## Diagram: where the perfect intervals sit

```svg
<svg viewBox="0 0 640 226" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The higher the partial number, the more complex the ratio between neighbours</text>
  </g>

  <g transform="translate(48,52)">
    <line x1="0" y1="96" x2="520" y2="96" stroke="#343439" stroke-width="1.2"/>
    <g>
      <rect x="-12" y="76" width="24" height="20" rx="2" fill="#E07A3F"/>
      <rect x="116" y="52" width="24" height="44" rx="2" fill="#5B7FA8"/>
      <rect x="244" y="40" width="24" height="56" rx="2" fill="#5B7FA8"/>
      <rect x="372" y="32" width="24" height="64" rx="2" fill="#5B7FA8"/>
      <rect x="500" y="26" width="24" height="70" rx="2" fill="#5B7FA8"/>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#F2EEE6" text-anchor="middle">
      <text x="0" y="70">C3</text><text x="128" y="46">C4</text>
      <text x="256" y="34">G4</text><text x="384" y="26">C5</text><text x="512" y="20">E5</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="114">1</text><text x="128" y="114">2</text><text x="256" y="114">3</text>
      <text x="384" y="114">4</text><text x="512" y="114">5</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="3 3">
      <line x1="0" y1="134" x2="128" y2="134"/>
      <line x1="0" y1="130" x2="0" y2="138"/><line x1="128" y1="130" x2="128" y2="138"/>
    </g>
    <text x="138" y="138" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">1–2: perfect octave (2:1)</text>
    <g stroke="#5B7FA8" stroke-width="1" stroke-dasharray="3 3">
      <line x1="128" y1="158" x2="256" y2="158"/>
      <line x1="128" y1="154" x2="128" y2="162"/><line x1="256" y1="154" x2="256" y2="162"/>
    </g>
    <text x="138" y="162" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">2–3: perfect fifth (3:2)   3–4: perfect fourth (4:3)</text>
  </g>
</svg>
```

## Listen: the perfect fifth

A fifth sounds hollow because it carries almost no tension that wants resolving. That hollowness is exactly
why it turns up everywhere, in tuning, stringing and harmonic scaffolding across the world.

```audiolab
{"type":"interval","a":"C4","b":"G4","label":"纯五度 C–G（7 个半音）","label_en":"Perfect fifth C–G (7 semitones)","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 F4 就是纯四度（5 个半音）—— 五度的转位。","hint2_en":"Set b to F4 for a perfect fourth (5 semitones) — the inversion of a fifth."}
```

```notation
{"clef":"treble","notes":["C4","G4","C5"],"caption":"C–G 纯五度，再上行到 C5 补成一个八度","caption_en":"C–G, a perfect fifth, then up to C5 to complete the octave"}
```

## Common misconceptions

- **"Perfect means in tune."** Here it means the simplest ratio (2:1, 3:2, 4:3), nothing about intonation.
- **"Perfect intervals cannot be augmented or diminished."** They can. A fifth widened by a semitone is augmented; narrowed, diminished.
- **"The fourth sounds more consonant than the fifth because it is narrower."** Narrower is not more consonant. Consonance follows ratio simplicity; fourth and fifth rank alike, just pointing opposite ways.
- **"Thirds would be more consonant if they were perfect."** Their ratios (5:4 and 6:5) are already more complex than the fourth and fifth, which is why they split into major and minor and carry colour.
:::
