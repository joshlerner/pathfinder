---
cssclasses: pf2e
traditions:
  - "[[Divine]]"
  - "[[Occult]]"
spell_type: Spell
spell_rank: 2
traits:
- "[[Concentrate]]"
- "[[Curse]]"
- "[[Manipulate]]"
- "[[Mental]]"
---
# Ghoulish Cravings `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core 2 pg. 246 <sup>1.1</sup>*
**Traditions** `=this.traditions`
**Range** touch; **Targets** 1 creature
**Defense** Will; **Duration** varies
___
You touch the target to afflict it with the overwhelming desire to eat raw meat. The target must attempt a Will save.

**Critical Success** The target is unaffected.
**Success** The target is [[sickened| sickened 1]] by its unbidden hunger.
**Failure** The target is sickened 2 and can't reduce this condition below sickened 1 until it first consumes some raw meat; if the creature doesn't have access to raw meat, it can take a bite out of a corpse within reach as an Interact action.
**Critical Failure** As failure, but the target can't reduce the condition below sickened 2 until it consumes raw meat.