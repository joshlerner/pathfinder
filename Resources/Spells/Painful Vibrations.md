---
cssclasses: pf2e
traditions:
  - "[[Divine]]"
  - "[[Occult]]"
spell_type: Spell
spell_rank: 4
traits:
  - "[[Evocation]]"
  - "[[Sonic]]"
---
# Painful Vibrations `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Secrets of Magic pg. 120 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Cast** `pf2:2` [[somatic]], [[verbal]]
**Range** 100 feet; **Targets** 1 living creature
**Saving Throw** Fortitude
___
You send powerful sound waves through an opponent's body, vibrating its bones and internal organs painfully. The creature takes 8d6 (`dice: 8d6`) sonic damage and must attempt a Fortitude save.  
  
**Critical Success** The target is unaffected.  
**Success** The target takes half damage.  
**Failure** The target takes full damage, is [[sickened|sickened 1]], and is [[deafened]] for 1 round.  
**Critical Failure** The target takes double damage, is sickened 2, and is deafened for 1 minute.
___
**Heightened (+1)** The damage increases by 2d6.
