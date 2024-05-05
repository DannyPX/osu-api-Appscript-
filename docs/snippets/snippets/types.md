---
outline: deep
---

# Types.gs

::: code-group

```js [Types.gs]
const BeatmapPackType = {
  Standard: 'standard',
  Featured_Artist: 'featured',
  Tournament: 'tournament',
  Project_Loved: 'loved',
  Spotlights: 'chart',
  Theme: 'theme',
  Artist: 'artist'
}

const BeatmapsetStatus = {
  All: 'all',
  Ranked: 'ranked',
  Qualified: 'qualified',
  Disqualified: 'disqualified',
  NeverQualified: 'never_qualified'
}

const DiscussionScore = {
  Up: '1',
  Down: '-1',
}

const DiscussionSort = {
  Descending: 'id_desc',
  Ascending: 'id_asc'
}

const DiscussionTypes = {
  First: 'first',
  Reply: 'reply',
  System: 'system'
}

const MessageTypes = {
  Suggestion: 'suggestion',
  Problem: 'problem',
  MapperNote: 'mapper_note',
  Praise: 'praise',
  Hype: 'hype',
  Review: 'review'
}

const Mod = {
  Easy: 'EZ',
  No_Fail: 'NF',
  Half_Time: 'HT',
  Hard_Rock: 'HR',
  Sudden_Death: 'SD',
  Perfect: 'PF',
  Double_Time: 'DT',
  Nightcore: 'NC',
  Hidden: 'HD',
  Fade_In: 'FI',
  Flashlight: 'FL',
  Relax: 'RL',
  Autopilot: 'AP',
  Spun_Out: 'SO',
  Key_1: '1K',
  Key_2: '2K',
  Key_3: '3K',
  Key_4: '4K',
  Key_5: '5K',
  Key_6: '6K',
  Key_7: '7K',
  Key_8: '8K',
  Key_9: '9K',
  Co_Op: 'CP',
  Mirror: 'MR',
  Random: 'RD',
  Auto: 'AT',
  Cinema: 'CM',
  ScoreV2: 'SV2',
  Target_Practice: 'TP'
}

const Ruleset = {
  Catch: 'fruits',
  Mania: 'mania',
  Standard: 'osu',
  Taiko: 'taiko'
}
:::