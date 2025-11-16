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
- "[[Manipulate]]"
- "[[Water]]"
---
# Spout `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core 2 pg. 252 <sup>1.1</sup>*
**Traditions** `=this.traditions`
**Range** 30 feet **Area** a 5-foot cube
**Defense** basic Reflex
___
