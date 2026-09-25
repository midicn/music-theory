---
id: concert-pitch
site: theo
cat: T1
title: 标准音高
title_en: Concert Pitch
summary: A4 定为 440 Hz 是近代的约定，音高标准本来一直在浮动
summary_en: A4 at 440 Hz is a recent agreement; pitch standards used to float from place to place
level: standard
tags: [乐理, 声学, 标准]
tags_en: [theory, acoustics, standard]
alias: [A440, 标准音, 音乐会音高, 定音]
order: 80
links:
  - "[[concept:pitch]]"
  - "[[concept:octave]]"
  - "[[concept:note-name]]"
  - "[[concept:historical-performance]]"
instances:
  - cyberhymnal-000695 | 管风琴圣咏：管风琴的音高由管长决定，一旦建成几乎无法改动，是音高标准最顽固的载体 | An organ hymn — pipe lengths fix the pitch permanently once built — the most stubborn carrier of any standard
  - giantmidi-006222 | 音阶与琶音练习：键盘按十二平均律调音，各调之间的等距关系依赖统一的标准音高 | Scale and arpeggio exercises — a keyboard tuned in equal temperament needs one agreed pitch for its equal spacing to mean anything
  - mutopia-000046 | 圣咏曲调《Old 100th》的人声版：人声自身没有固定音高，起唱前必须先取得一个外来参照 | The hymn tune Old 100th sung by voices — the voice has no fixed pitch of its own, so an outside reference has to be taken before it starts
sources:
  - A4 = 440 Hz 的国际标准由 1939 年伦敦国际会议建议、后经 ISO 16 确立，为公认事实
  - 1859 年法国确立 435 Hz、巴洛克时期常用 415 Hz，均为乐律史通行记载
updated: 2026-09-23
---

::: zh
「标准音高」这个词容易让人以为音高标准自古就有。事实相反：**它是晚近的产物，而且是被迫定下来的**。
在此之前，每一座教堂、每一个城镇的音高都可以不一样。

## A4 = 440 Hz 是怎么来的

音高必须统一，是因为**乐器要一起演奏**。管风琴、木管、铜管这类乐器的音高在制造时就被定死了，
一支在 A=435 的城镇里造出来的笛子，搬去 A=450 的乐团就整支偏高。

混乱在十九世纪达到顶点：乐队音高被一路抬高，因为更亮的音色更好卖票，
而歌手与弦乐器的负担随之加重。于是有了定标准的压力：

| 年份 | 事件 | 音高 |
|---|---|---|
| — | 巴洛克时期常用的音高标准 | A4 = 415 Hz |
| 1859 | 法国确立「diapason normal」 | A4 = 435 Hz |
| 1939 | 伦敦国际会议建议统一 | A4 = 440 Hz |

此后 A4 = 440 Hz 被写进国际标准，成为今天通行的**音乐会音高**。
今天说"这个音是 A"，默认指 440 Hz 那个 A。

## 图示：三个音高标准的位置

```svg
<svg viewBox="0 0 640 260" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">同一根弦在三种标准下要求的位置不同 · 415 到 440 的差距接近一个半音</text>
  </g>

  <g transform="translate(120,48)">
    <line x1="0" y1="104" x2="420" y2="104" stroke="#343439" stroke-width="1.2"/>
    <g stroke="#343439">
      <line x1="0" y1="104" x2="0" y2="110"/><line x1="105" y1="104" x2="105" y2="110"/>
      <line x1="210" y1="104" x2="210" y2="110"/><line x1="315" y1="104" x2="315" y2="110"/>
      <line x1="420" y1="104" x2="420" y2="110"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="126">410</text><text x="105" y="126">420</text><text x="210" y="126">430</text>
      <text x="315" y="126">440</text><text x="420" y="126">450 Hz</text>
    </g>

    <g>
      <rect x="46" y="26" width="10" height="78" rx="2" fill="#9C7A3C"/>
      <text x="0" y="18" font-family="system-ui,sans-serif" font-size="11.5" fill="#9C7A3C">415</text>

      <rect x="250" y="52" width="10" height="52" rx="2" fill="#E8C547"/>
      <text x="228" y="44" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">435</text>

      <rect x="303" y="66" width="10" height="38" rx="2" fill="#5B7FA8"/>
      <text x="318" y="58" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">440</text>
    </g>

    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="152">巴洛克音高：本地惯例，各地不一</text>
      <text x="0" y="170">1859 · 法国 diapason normal</text>
      <text x="0" y="188">1939 · 伦敦会议建议 → 今天的音乐会音高</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="3 3">
      <line x1="51" y1="-6" x2="303" y2="-6"/>
      <line x1="51" y1="-10" x2="51" y2="-2"/>
      <line x1="303" y1="-10" x2="303" y2="-2"/>
    </g>
    <text x="120" y="-10" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">415 → 440：接近半音</text>
  </g>
</svg>
```

## 它为什么值得单独记一条

因为音高标准是**演奏实践的前提**，也是历史演奏的分水岭。

- **合奏要先定音**。乐团开场时的对音，就是全体向同一个参照靠拢。参照对了，之后才可能谈音准。
- **移调乐器要换算**。写的是同一个音名，实际发声高度取决于乐器自身的构造与标准音高。见 [[concept:note-name|音名]]。
- **古乐演奏会换标准**。今天用 415 Hz 演奏巴洛克作品，是为了让当年的乐器构造、弦张力、人声负担回到原来的状态。
  这属于演奏实践问题，见 [[concept:historical-performance|历史演奏法]]。
- **键盘的等距依赖它**。十二平均律把八度切成十二份，切完之后每一份的绝对频率由标准音高确定。
  标准音高一变，整套键位的频率整体平移。

## 听一听：A4 与它的八度

```audiolab
{"type":"interval","a":"A4","b":"A5","label":"A4 → A5（都以 A4 = 440 Hz 为基准）","label_en":"A4 to A5, both referred to A4 = 440 Hz","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"这个组件按十二平均律发声。历史上乐团的实际音高在 415 到 445 Hz 之间浮动 —— 整个浮动范围还不到一个半音。","hint2_en":"This component sounds in twelve-tone equal temperament. Historically orchestras have tuned anywhere from 415 to 445 Hz — a spread of less than a semitone."}
```

## 常见误解

- **「A 就是 440 Hz」** → A 是音名，440 Hz 是近代给 A4 这个音名配的频率。"A"这个字母本身不含数字。
- **「音高越统一越好，所以古人很落后」** → 各地音高不同在过去是常态而非失误；统一是为了合奏，不是为了正确。
- **「调音器显示 440 就说明音准完美」** → 它只说明这一个参照音对上了。整场演奏的音准还要看乐器构造、演奏法与平均律的取舍。
- **「古乐就是音更低」** → 打巴洛克作品用 415 Hz 是常见做法，但历史上各地音高有高有低，并不单调地"更低"。
:::

::: en
The phrase "standard pitch" suggests pitch standards have always existed. The opposite is true:
**it is a recent invention, and it was forced on musicians.** Before it, every church and every town could keep
its own pitch.

## How A4 = 440 Hz came about

Pitch has to be unified because **instruments have to play together**. Organs, woodwinds and brass are fixed
to a pitch at the moment of manufacture. A flute built in a town at A = 435 is entirely sharp the day it joins
an ensemble playing at A = 450.

The chaos peaked in the nineteenth century: orchestras kept raising pitch because a brighter sound sold more
tickets, while the burden on singers and string players grew with it. That created pressure to standardise.

| Year | Event | Pitch |
|---|---|---|
| — | Pitch commonly used in the Baroque era | A4 = 415 Hz |
| 1859 | France establishes the "diapason normal" | A4 = 435 Hz |
| 1939 | London international conference recommends unification | A4 = 440 Hz |

A4 = 440 Hz was written into international standards afterwards and is today's **concert pitch**. When someone
says "this note is A", the default meaning is that 440 Hz A.

## Diagram: where the three standards sit

```svg
<svg viewBox="0 0 640 260" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">The same string needs a different position under each standard · 415 to 440 is close to one semitone</text>
  </g>

  <g transform="translate(120,48)">
    <line x1="0" y1="104" x2="420" y2="104" stroke="#343439" stroke-width="1.2"/>
    <g stroke="#343439">
      <line x1="0" y1="104" x2="0" y2="110"/><line x1="105" y1="104" x2="105" y2="110"/>
      <line x1="210" y1="104" x2="210" y2="110"/><line x1="315" y1="104" x2="315" y2="110"/>
      <line x1="420" y1="104" x2="420" y2="110"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#6E6A64" text-anchor="middle">
      <text x="0" y="126">410</text><text x="105" y="126">420</text><text x="210" y="126">430</text>
      <text x="315" y="126">440</text><text x="420" y="126">450 Hz</text>
    </g>

    <g>
      <rect x="46" y="26" width="10" height="78" rx="2" fill="#9C7A3C"/>
      <text x="0" y="18" font-family="system-ui,sans-serif" font-size="11.5" fill="#9C7A3C">415</text>

      <rect x="250" y="52" width="10" height="52" rx="2" fill="#E8C547"/>
      <text x="228" y="44" font-family="system-ui,sans-serif" font-size="11.5" fill="#E8C547">435</text>

      <rect x="303" y="66" width="10" height="38" rx="2" fill="#5B7FA8"/>
      <text x="318" y="58" font-family="system-ui,sans-serif" font-size="11.5" fill="#5B7FA8">440</text>
    </g>

    <g font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      <text x="0" y="152">Baroque pitch: a local habit, differing from town to town</text>
      <text x="0" y="170">1859 · France, diapason normal</text>
      <text x="0" y="188">1939 · London conference recommends it — today's concert pitch</text>
    </g>
    <g stroke="#E07A3F" stroke-width="1" stroke-dasharray="3 3">
      <line x1="51" y1="-6" x2="303" y2="-6"/>
      <line x1="51" y1="-10" x2="51" y2="-2"/>
      <line x1="303" y1="-10" x2="303" y2="-2"/>
    </g>
    <text x="120" y="-10" font-family="system-ui,sans-serif" font-size="11" fill="#E07A3F">415 to 440: close to a semitone</text>
  </g>
</svg>
```

## Why it deserves an entry of its own

Because pitch standard is the precondition of performance practice, and the dividing line in historical playing.

- **Ensembles tune first.** The tuning moment at the start of a concert brings everyone toward one reference. Only after that can intonation mean anything.
- **Transposing instruments need conversion.** The written name may be the same, but the sounding pitch depends on the instrument's construction and on the standard. See [[concept:note-name|note name]].
- **Period performances change standard.** Playing Baroque music at 415 Hz today restores the original instrument build, string tension and vocal burden. That is a performance-practice question — see [[concept:historical-performance|historical performance]].
- **Equal spacing on a keyboard depends on it.** Equal temperament cuts the octave into twelve; where those twelve then sit in absolute frequency is decided by the standard. Shift the standard and the whole keyboard shifts.

## Listen: A4 and its octave

```audiolab
{"type":"interval","a":"A4","b":"A5","label":"A4 → A5（都以 A4 = 440 Hz 为基准）","label_en":"A4 to A5, both referred to A4 = 440 Hz","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"这个组件按十二平均律发声。历史上乐团的实际音高在 415 到 445 Hz 之间浮动 —— 整个浮动范围还不到一个半音。","hint2_en":"This component sounds in twelve-tone equal temperament. Historically orchestras have tuned anywhere from 415 to 445 Hz — a spread of less than a semitone."}
```

## Common misconceptions

- **"A means 440 Hz."** A is a note name; 440 Hz is the frequency assigned to the name A4 in modern practice. The letter itself contains no number.
- **"Unified pitch is better, so earlier musicians were backward."** Differing local pitches were the norm rather than a mistake. Unification serves ensemble playing, not correctness.
- **"A tuner reading 440 means perfect intonation."** It means this one reference matches. Overall intonation still depends on instrument build, technique and the temperament chosen.
- **"Period performance simply means lower pitch."** 415 Hz is a common choice for Baroque repertoire, but historically pitch ran both high and low, not consistently lower.
:::
