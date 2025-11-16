---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Occult]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Cantrip]]"
- "[[Concentrate]]"
- "[[Illusion]]"
- "[[Manipulate]]"
- "[[Subtle]]"
---
# Figment `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 331 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Bloodline** [[Fey]]
**Range** 30 feet
**Duration** sustained
___
