---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Divine]]"
  - "[[Occult]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits:
- "[[Abjuration]]"
- "[[Cantrip]]"
---
# Protect Companion `pf2:1` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Secrets of Magic pg. 123 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Cast** `pf2:1` [[verbal]]
**Range** 30 feet
**Target** your [[eidolon]], or a creature with the [[minion]] trait under your control
**Duration** until the start of your next turn
___
You extend your aura, as a magical shield that protects your eidolon or minion. The target gains a +1 circumstance bonus to AC until the start of your next turn. You gain the following reaction; after using the reaction, the spell ends and you can't cast _protect companion_ again for 10 minutes.  
  
**Life Block** `pf2:r` **Trigger** The spell's target would take damage; **Effect** Reduce the triggering damage by 10, but you lose 5 Hit Points. Even if this reduces the damage to 0, the target still takes any effects that would come with the damage, such as the poison on a viper's fangs [[Strike]].
___
**Heightened (+2)** The reaction reduces the damage by another 10, and you lose 5 more Hit Points. If you want to lose fewer Hit Points, you can choose to lower the damage reduction and HP lost to what any lower-level version of the spell could do without lowering the spell's actual level.