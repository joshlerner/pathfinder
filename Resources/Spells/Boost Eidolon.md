---
cssclasses:
  - pf2e
traditions:
  - "[[Arcane]]"
  - "[[Divine]]"
  - "[[Occult]]"
  - "[[Primal]]"
spell_type: Cantrip
spell_rank: 1
traits: 
- "[[Uncommon]]"
- "[[Cantrip]]"
- "[[Evocation]]"
- "[[Resources/Reference/Traits/Summoner|Summoner]]"
---
# Boost Eidolon `pf2:1` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Secrets of Magic pg. 144 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Cast** `pf2:1` [[verbal]]
**Range** 100 feet **Targets** your [[eidolon]]
**Duration** 1 round
___
You focus deeply on the link between you and your eidolon and boost the power of your eidolon's attacks. Your eidolon gains a +2 status bonus to damage rolls with its [[Unarmed|unarmed]] attacks. If your eidolon's [[Strike|Strikes]] deal more than one weapon damage die, the status bonus increases to 2 per weapon damage die, to a maximum of +8 with four weapon damage dice.

