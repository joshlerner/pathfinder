---
cssclasses: pf2e
traditions:
  - "[[Divine]]"
spell_type: Spell
spell_rank: 5
traits:
  - "[[Concentrate]]"
  - "[[Fire]]"
  - "[[Manipulate]]"
  - "[[Sanctified]]"
  - "[[Spirit]]"
---
# Divine Immolation `pf2:0` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 325 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Bloodline** [[angelic]]
**Range** 120 feet; **Area** 20-foot burst
**Defense** Reflex
___
Divine flames scour creatures within the area. Creatures take 6d6 (`dice: 6d6`) fire damage and 2d6 (`dice: 2d6`) persistent fire damage. The divine power within the flames scorches the spirit as well; a creature takes spirit damage instead of fire damage from divine immolation if that would be more detrimental to the creature (as determined by the GM).  
  
**Critical Success** The creature is unaffected.  
**Success** The creature takes half damage and no persistent damage.  
**Failure** The creature takes full damage and persistent damage.  
**Critical Failure** The creature takes double damage and double persistent damage.
___
**Heightened (+1)** The damage increases by 1d6 and persistent damage increases by 1d6.
