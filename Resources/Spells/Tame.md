---
cssclasses: pf2e
traditions:
  - "[[Occult]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Auditory]]"
- "[[Cantrip]]"
- "[[Enchantment]]"
- "[[Mental]]"
---
# Tame `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Secrets of Magic pg. 135 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Cast** `pf2:2` [[somatic]], [[verbal]]
**Range** 10 feet **Target** 1 non-hostile domesticated [[animal]]
**Saving Throw** Will **Duration** 1 minute
___
