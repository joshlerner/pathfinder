---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Acid]]"
- "[[Cantrip]]"
- "[[Concentrate]]"
- "[[Manipulate]]"
---
# Caustic Blast `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 319 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Bloodline** [[Demonic]]
**Mystery** [[Blight]]
**Range** 30 feet **Area** 5-foot burst
**Defense** basic Reflex
___
You fling a large glob of acid that immediately detonates, spraying nearby creatures. Creatures in the area take 1d8 acid damage with a basic Reflex save; on a critical failure, the creature also takes 1 persistent acid damage.
___
**Heightened (+2)** The initial damage increases by 1d8, and the persistent damage on a critical failure increases by 1.