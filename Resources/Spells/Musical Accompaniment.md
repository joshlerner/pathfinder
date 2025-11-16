---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Occult]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Auditory]]"
- "[[Cantrip]]"
- "[[Illusion]]"
---
# Musical Accompaniment `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Firebrands pg. 90 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Cast** `pf2:2` [[somatic]], [[verbal]]
**Duration** 1 minute
___
