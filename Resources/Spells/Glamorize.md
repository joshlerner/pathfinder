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
- "[[Manipulate]]"
---
# Glamorize `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Divine Mysteries pg. 258*
**Traditions** `=this.traditions`
**Duration** 1 hour
___
