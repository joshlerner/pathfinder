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
- "[[Concentrate]]"
- "[[Manipulate]]"
---
# Adhere `pf2:1` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Starfinder Player Core pg. 313*
**Traditions** `=this.traditions`
**Range** touch; **Targets** 1 held or unattended object or a 5-foot square surface
**Duration** 1 minute
___
You create a molecular bond between an unattended object you touch (or an object you're holding) and anothe robject or surface that object is touching. Pulling the object free of that surface requires a successful [[Athletics]] check against your spell DC to [[Force Open]].

