---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Occult]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Attack]]"
- "[[Cantrip]]"
- "[[Evocation]]"
---
# Phase Bolt `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Dark Archive pg. 106*
**Traditions** `=this.traditions`
**Cast** `pf2:2` [[somatic]], [[verbal]]
**Range** 30 feet **Target** 1 creature
___
