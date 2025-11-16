---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Attack]]"
- "[[Cantrip]]"
- "[[Concentrate]]"
- "[[Manipulate]]"
- "[[Morph]]"
---
# Gouging Claw `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 333 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Range** touch **Target** 1 creature
**Defense** AC
___
You temporarily morph your limb into a clawed appendage. Make a melee spell attack roll against your target's AC. If you hit, you deal your choice of 2d6 slashing damage or 2d6 piercing damage, plus 2 persistent bleed damage. On a critical success, you deal double damage and double bleed damage.
___
**Heightened (+1)** The damage increases by 1d6 and the persistent bleed damage increases by 1.
