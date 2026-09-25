---
id: third-species
site: theo
cat: T6
title: 第三类对位
title_en: Third Species
summary: 一音对四音——一个强拍之内，不协和音也能成串出现
summary_en: Four notes against one — within a single beat, dissonances may now come in runs
level: standard
tags: [乐理, 对位, 复调]
tags_en: [theory, counterpoint, polyphony]
alias: [第三类对位, 四音对一音, third species]
order: 18
links:
  - "[[concept:second-species]]"
  - "[[concept:fourth-species]]"
  - "[[concept:non-chord-tone]]"
  - "[[concept:non-chord-tone-treatment]]"
  - "[[concept:first-species]]"
instances:
  - mutopia-000287 | 巴赫第八首二部创意曲：句中的四音组里能听到不协和音成串出现，正是第三类的织体 | Bach's eighth two-part invention — runs of four notes contain strings of dissonance, exactly third-species texture
  - mutopia-000280 | 巴赫二部创意曲第一首：音型化的段落密度更高，可对照第二类与第三类的差别 | Bach's first two-part invention — its figurated passages are denser, showing the difference from second species
  - giantmidi-006222 | 音阶练习本身即四音一组的级进，可用于观察"一串音里哪一个能被听成骨架" | Scale exercises are literally groups of four stepwise notes, useful for spotting which note is heard as the frame
sources:
  - 第三类对位（四音对一音）规则：每组第一音须协和、组内可用不协和音且须级进处理，为通行对位教学体系
  - 一组之内不协和音的处理方式（经过、邻音、以及跳进的例外）为对位学通则
updated: 2026-09-24
---

::: zh
第三类把每一步再拆细：固定旋律一个音，对位声部走**四个音**。

> 织体因此从"一步一顿"变成"一串音" —— 而一串音里，**不协和音可以连续出现**。

## 判断标准从"每个音"变成"每组头一个音"

这是第三类最关键的思维转变：

| | 第二类 | 第三类 |
|---|---|---|
| 检查单位 | **每个音** | **每组的第一音** |
| 不协和位置 | 只能在弱拍 | 组内**任何位置**（除组首） |
| 不协和数量 | 一个 | **可以成串** |

也就是说：**听觉上被"点数"的是每组的第一音**（它落在强拍或次强拍上），
其余三个音只要**级进、快速、不停留**，即使连环不协和也不会被听成落点。

## 组内不协和的三种处理

| 类型 | 形态 | 说明 |
|---|---|---|
| **经过** | 级进填充 | 与第二类相同 |
| **邻音** | 离开又回来 | 绕一下就走 |
| **跳进的例外** | 级进进入、跳进离去（再反向级进回来） | 这是本类**唯一**允许的跳进处理，因为它有明确的进出路径 |

第三条要特别小心：它**只适用于特定形态**。把不协和音随意跳进跳出，在任何一类对位里都是错的
（见 [[concept:non-chord-tone-treatment|和弦外音处理]]）。

## 它离真实写作更近了

第二类的织体还带着"练习感"，第三类的**音型化**（同一时值连成串）则是真实作品里最常见的形态之一 ——
巴赫的二部创意曲、赋格的间插段、古典时期的伴奏音型都属于这一类。

所以从这个训练阶段开始，**判断标准越来越依赖"整体是否像音乐"**，
而不是"每个格子是否合规"。这正是五类对位阶梯的设计意图：
**规则越松，对音乐判断力的要求越高。**

## 图示：检查单位从音变成组

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">每组四音里，被"点数"的只有第一个 —— 其余只要级进掠过</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="120" y="0">E</text><text x="240" y="0">G</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">C</text><text x="40" y="60">D</text><text x="80" y="60">E</text><text x="120" y="60">F</text>
      <text x="160" y="60">E</text><text x="200" y="60">D</text><text x="240" y="60">C</text>
      <text x="280" y="60">B</text><text x="320" y="60">C</text>
    </g>
    <g stroke="#E8C547" stroke-width="2">
      <line x1="0" y1="8" x2="0" y2="54"/>
      <line x1="120" y1="8" x2="120" y2="54"/>
      <line x1="240" y1="8" x2="240" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="middle">
      <text x="0" y="78">组首（协和）</text><text x="120" y="78">组首（协和）</text><text x="240" y="78">组首（协和）</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="middle">
      <text x="40" y="96">经过</text><text x="80" y="96">经过</text>
      <text x="160" y="96">经过</text><text x="200" y="96">经过</text><text x="280" y="96">经过</text>
    </g>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      组内不协和可以成串 —— 只要级进、快速、不停留
    </text>
    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      唯一允许的跳进例外：级进进入 → 跳进离去 → 再反向级进回来（有明确进出路径）
    </text>
  </g>
</svg>
```

## 听一听：组首与组内的差别

第三类是两声部练习，本站放不出两声部。这里用 `interval` 对比**组首可用的音程与组内可用的音程**：
先听三度（可当组首），再听二度（只能组内快速掠过）。

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"组首：三度（可被点数）","label_en":"Group head: a third, countable","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D4 得到二度 —— 一组四音里它可以成串出现，但不能落在组首。","hint2_en":"Set b to D4 for a second — inside a group of four it may come in runs, but must not stand at the head."}
```

## 常见误解

- **「不协和音可以随便放了」** → 只是**位置**放宽到组内，处理方式（级进、不停留）**没有放宽**。
- **「四音一组必须都是同一时值」** → 训练里通常是；实际写作里常有变化，那时已进入第五类（华丽对位）。
- **「第三类比第二类难得多」** → 规则只多一条（组首须协和），难在**判断点从"每个音"变成了"每组音"**。
- **「音型化只是伴奏手法」** → 它也是复调织体的基本形态，巴赫的创意曲与赋格间插段大量使用。
:::

::: en
Third species splits each step further: one note of the cantus firmus against **four notes** in the counterpoint.

> The texture changes from "one step at a time" to **a run of notes** — and within a run, **dissonances may come
> in succession.**

## The unit of judgement moves from note to group

This is the crucial shift in third species:

| | Second species | Third species |
|---|---|---|
| Unit checked | **each note** | **the first note of each group** |
| Where dissonance may sit | weak beats only | **anywhere except the group head** |
| How many | one | **may come in runs** |

The ear **counts the head of each group** (it falls on a strong or secondary strong beat). The remaining three
notes, provided they **move by step, quickly, and without resting**, will not be heard as arrival points even if
they are dissonant in succession.

## Three ways to handle dissonance inside a group

| Type | Shape | Note |
|---|---|---|
| **passing** | stepwise filling | as in second species |
| **neighbour** | leaves and returns | a detour |
| **the leap exception** | entered by step, left by leap (then returning by step) | the **only** permitted leap treatment here, because the entry and exit are both defined |

The third needs care: it applies **only in that specific shape**. Leaping into and out of a dissonance at will is
wrong in every species (see [[concept:non-chord-tone-treatment|treating non-chord tones]]).

## It is closer to real writing

Second-species texture still feels like an exercise; third-species **figuration** (runs at one note value) is one
of the commonest textures in real music — Bach's two-part inventions, fugal episodes and Classical accompaniment
figures all belong to it.

So from this stage onward, **judgement depends increasingly on whether the whole sounds like music**, not on
whether each cell is compliant. That is precisely the design of the species ladder: **the looser the rules, the
more musical judgement is required.**

## Diagram: the unit shifts from note to group

```svg
<svg viewBox="0 0 640 200" xmlns="http://www.w3.org/2000/svg">
  <g font-family="system-ui,sans-serif" font-size="12" fill="#A9A49B">
    <text x="24" y="22">Only the first note of each group of four is counted — the rest pass by step</text>
  </g>

  <g transform="translate(56,54)">
    <g font-family="Georgia,serif" font-size="12" fill="#E07A3F" text-anchor="middle">
      <text x="0" y="0">C</text><text x="120" y="0">E</text><text x="240" y="0">G</text>
    </g>
    <g font-family="Georgia,serif" font-size="12" fill="#5B7FA8" text-anchor="middle">
      <text x="0" y="60">C</text><text x="40" y="60">D</text><text x="80" y="60">E</text><text x="120" y="60">F</text>
      <text x="160" y="60">E</text><text x="200" y="60">D</text><text x="240" y="60">C</text>
      <text x="280" y="60">B</text><text x="320" y="60">C</text>
    </g>
    <g stroke="#E8C547" stroke-width="2">
      <line x1="0" y1="8" x2="0" y2="54"/>
      <line x1="120" y1="8" x2="120" y2="54"/>
      <line x1="240" y1="8" x2="240" y2="54"/>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#E8C547" text-anchor="middle">
      <text x="0" y="78">head (consonant)</text><text x="120" y="78">head</text><text x="240" y="78">head</text>
    </g>
    <g font-family="system-ui,sans-serif" font-size="10.5" fill="#C0504A" text-anchor="middle">
      <text x="40" y="96">passing</text><text x="80" y="96">passing</text>
      <text x="160" y="96">passing</text><text x="200" y="96">passing</text><text x="280" y="96">passing</text>
    </g>
    <text x="0" y="124" font-family="system-ui,sans-serif" font-size="11" fill="#5B7FA8">
      Dissonances may form runs inside a group — provided they pass by step and never rest
    </text>
    <text x="0" y="146" font-family="system-ui,sans-serif" font-size="11" fill="#6E6A64">
      The one leap exception: entered by step, left by leap, then returning by step
    </text>
  </g>
</svg>
```

## Listen: group head versus inside the group

Third species is a two-voice exercise and cannot be played here. Use `interval` to compare **an interval usable at
a group head with one usable only inside**: a third (countable), then a second (a quick pass only).

```audiolab
{"type":"interval","a":"C4","b":"E4","label":"组首：三度（可被点数）","label_en":"Group head: a third, countable","hint":"先各自听，再听合起来","hint_en":"Hear each tone, then both together","hint2":"把 b 换成 D4 得到二度 —— 组内可以成串，但不能落在组首。","hint2_en":"Set b to D4 for a second — it may form runs inside a group, but must not stand at the head."}
```

## Common misconceptions

- **"Dissonances may now go anywhere."** Only their **position** is relaxed, into the group; their **treatment**
  (by step, non-resting) is unchanged.
- **"A group of four must be all the same note value."** In the exercise, usually; in real writing it varies, at
  which point you are in fifth-species territory.
- **"Third species is much harder than second."** Only one rule is added (the head must be consonant); the real
  difficulty is that **the point of judgement moves from note to group.**
- **"Figuration is only an accompaniment device."** It is also a fundamental polyphonic texture — Bach's
  inventions and fugal episodes use it heavily.
:::
