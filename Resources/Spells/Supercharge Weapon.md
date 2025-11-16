---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
spell_type: Spell
spell_rank: 1
traits:
- "[[Concentrate]]"
- "[[Manipulate]]"
---
# Supercharge Weapon `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Starfinder Player Core pg. 365*
**Traditions** `=this.traditions`
**Range** 30 feet; **Targets** 1 weapon held by you or a willing ally
**Duration** 1 minute or until discharged
___
You draw in and condense ambient magical energy from around you to power up a weapon. The next [[Strike]] made using that weapon is supercharged. That Strike deals an additional 1d6 damage of the same type as the weapon's normal damage.
___
**Heightened (+2)** The extra damage increases by 1d6.

