---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Divine]]"
  - "[[Occult]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Cantrip]]"
- "[[Concentrate]]"
- "[[Detection]]"
- "[[Manipulate]]"
---
# Read Aura <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 352 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Spell Lists** [[Elemental]]
**Mystery** [[Lore]]
**Cast** 1 minute
**Range** 30 feet **Target** 1 object
___
