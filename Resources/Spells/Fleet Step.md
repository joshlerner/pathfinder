---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Primal]]"
spell_type: Spell
spell_rank: 1
traits:
- "[[Concentrate]]"
- "[[Manipulate]]"
---
# Fleet Step `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 332 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Duration** 1 minute
___
You gain a +30 foot status bonus to your Speed.

