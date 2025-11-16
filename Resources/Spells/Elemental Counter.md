---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Uncommon]]"
- "[[Cantrip]]"
- "[[Concentrate]]"
---
# Elemental Counter `pf2:r` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Rage of Elements pg. 222 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Spell Lists** [[Elemental]]
**Trigger** You or a creature within 60 feet rolls a saving throw against a spell with the [[earth]], [[fire]],[[metal]], [[plant]], [[water]], or [[wood]] trait, or are targeted by a spell attack with such a trait.
**Requirements** You have a spell slot from which you could Cast a Spell of the triggering spell's countering element.
___
