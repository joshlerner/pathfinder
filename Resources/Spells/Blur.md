---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Occult]]"
spell_type: Spell
spell_rank: 2
traits:
- "[[Concentrate]]"
- "[[Illusion]]"
- "[[Manipulate]]"
- "[[Visual]]"
---
# Blur `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 318 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Range** touch; **Targets** 1 creature
**Duration** 1 minute
___
The target's form appears blurry. It becomes [[concealed]]. As the nature of this effect still leaves the target's location obvious, the target can't use this concealment to [[Hide]] or [[Sneak]].

