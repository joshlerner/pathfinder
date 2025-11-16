---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Divine]]"
  - "[[Occult]]"
spell_type: Cantrip
spell_rank: 1
traits: 
- "[[Auditory]]"
- "[[Cantrip]]"
- "[[Concentrate]]"
- "[[Illusion]]"
- "[[Linguistic]]"
- "[[Mental]]"
- "[[Subtle]]"
---
# Message `pf2:1` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 343 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Spell Lists** [[Elemental]]
**Range** 120 feet **Target** 1 creature
___
