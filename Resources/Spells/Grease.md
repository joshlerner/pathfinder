---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Primal]]"
spell_type: Spell
spell_rank: 1
traits:
- "[[Concentrate]]"
- "[[Manipulate]]"
---
# Grease `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 333<sup>2.0</sup>*
**Traditions** `=this.traditions`
**Range** 30 feet; **Area** 4 contiguous 5 foot squares or; **Targets** 1 object of 1 Bulk or less
**Duration** 1 minute
___
You conjure grease, choosing an area or target.
- **Area** All solid ground in the area is covered with grease. Each creature standing on the greasy surface must succeed at a Reflex save or an [[Acrobatics]] chekc against your spell DC or fall [[prone]]. Creatures using an action to move onto the greasy surface during the spell's duration must attempt either a Reflex save or an Acrobatics check to [[Balance]]. A creature that Steps or [[Crawls]] doesn't have to attempt a check or save.
- **Target** If you Cast the Spell on an unattended object, anyone trying to pick up the object must succeed at an Acrobatics check or Reflex save. On a failure, the holder or wielder takes a -2 circumstance penalty to all checks that involve using the object; on a critical failure, the holder or wielder releases the item. The object lands in an adjacent square of the GM's choice. If you Cast this Spell on a worn object, the wearer gains a  +2 circumstance bonus to Fortitude saves against attempts to grapple them.

