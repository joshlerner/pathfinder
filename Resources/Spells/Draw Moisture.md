---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Divine]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Cantrip]]" 
- "[[Concentrate]]"
- "[[Manipulate]]"
- "[[Water]]"
---
# Draw Moisture `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Rage of Elements pg. 173 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Range** 10 feet **Target** 1 object up to 10 Bulk
___
