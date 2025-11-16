---
cssclasses: pf2e
traditions:
  - "[[Divine]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Cantrip]]"
- "[[Concentrate]]"
- "[[Healing]]"
- "[[Manipulate]]"
- "[[Vitality]]"
---
# Stabilize `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 359 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Range** 30 feet **Target** 1 [[dying]] creature
___
