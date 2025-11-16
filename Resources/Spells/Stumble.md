---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Cantrip]]"
- "[[Concentrate]]"
- "[[Manipulate]]"
---
# Stumble `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Starfinder Player Core pg. 363*
**Traditions** `=this.traditions`
**Range** 100 feet; **Targets** 1 creature
**Defense** Reflex
___
A burst of microgravity causes a tremor around the target, pulling it toward the ground. The target must attempt a Reflex save.
**Failure** The target becomes [[off-guard]] for 1 round. If the target was flying, swimming, or floating, it falls 10 feet downward.
**Critical Failure** The target falls prone. If the target was flying, swimming, or floating, it falls 20 feet downward.
___
**Heightened (+1)** If the target falls, it falls an additional 5 feet on a failure and 10 feet on a critical failure.

