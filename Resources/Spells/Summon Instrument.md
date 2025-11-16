---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Divine]]"
  - "[[Occult]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Cantrip]]"
- "[[Concentrate]]"
- "[[Manipulate]]"
---
# Summon Instrument `pf2:3` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 361 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Duration** 1 hour
___
You materialize a handheld musical instrument in your grasp. The instrument is typical for its type, but it plays for only you. It vanishes when the spell ends. If you cast _summon instrument_ again, any instrument you previously summoned disappears.
___
**Heightened (5th)** The instrument is instead a virtuoso handheld instrument.
