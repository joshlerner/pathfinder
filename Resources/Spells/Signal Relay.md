---
cssclasses: pf2e
traditions:
  -
spell_type: Focus
spell_rank: 1
traits:
  - Uncommon
  - Concentrate
  - Focus
  - Spellshape
  - Technomancer
---
# Signal Relay `pf2:1` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Starfinder Tech Class pg. 32*
**Requirements** You have line of effect to a tech minion under your control.
___
If the next action you use is to Cast a Spell that only affects you, the spell affects your minion instead.
**Jailbreak** If you use Jailbreak Spell to use this spellshape with a harmless spell, the spell affects the minion in addition to its original target.
___
