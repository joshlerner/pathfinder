---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Cantrip]]"
- "[[Concentrate]]" 
- "[[Electricity]]" 
- "[[Manipulate]]"
---
# Electric Arc `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 328 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Mystery** [[Tempest]]
**Range** 30 feet **Target** 1 or 2 creatures
**Defense** basic Reflex
___
An arc of lightning leaps from one target to another. Each target takes 2d4 (`dice: 2d4`) electricity damage with a basic Reflex save.
___
**Heightened (+1)** The damage increases by 1d4 (`dice: 1d4`)

