---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Occult]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Cantrip]]"
- "[[Fire]]"
- "[[Manipulate]]"
---
# Eat Fire `pf2:r` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Rage of Elements pg. 119 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Trigger** You would take fire damage.
**Duration** until the end of your next turn
___
