---
cssclasses: pf2e
traditions:
  - "[[Divine]]"
spell_type: Spell
spell_rank: 4
traits:
  - "[[Concentrate]]"
  - "[[Manipulate]]"
  - "[[Sanctified]]"
  - "[[Spirit]]"
---
# Divine Wrath `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 326 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Bloodlines** [[angelic]], [[demonic]]
**Range** 120 feet; **Area** 20-foot burst
**Defense** Fortitude
___
You channel the fury of divinity against your foes. You deal 4d10 (`dice: 4d10`) spirit damage to enemies in the area, depending on their Fortitude save.

**Critical Success** The creature is unaffected.
**Success** The creature takes half damage.
**Failure** The creature takes full damage and is sickened 1.
**Critical Failure** The creature takes full damage and is sickened 2; while it's sickened, it's also slowed 1.
___
**Heightened (+1)** The damage increases by 1d10.
