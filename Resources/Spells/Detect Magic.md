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
- "[[Cantrip]]"
- "[[Concentrate]]"
- "[[Detection]]"
- "[[Manipulate]]"
---
# Detect Magic `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 323 <sup>2.0</sup>*
**Traditions** `=this.traditions`
**Spell Lists** [[Elemental]]
**Bloodline** [[Imperial]]
**Area** 30-foot emanation
___
You send out a pulse that registers the presence of magic. You receive no information beyond the presence or absence of magic. You can choose to ignore magic you're fully aware of, such as the magic items and ongoing spells of you and your allies.  
  
You detect [[Illusion]] magic only if that magic's effect has a lower rank than the rank of your _detect magic_ spell. However, items that have an illusion aura but aren't deceptive in appearance (such as an _invisibility potion_) typically are detected normally.
___
**Heightened (3rd)** You learn the rank or level of the most powerful magical effect the spell detects, as determined by the GM.  
**Heightened (4th)** As 3rd rank, but you also pinpoint the source of the highest-rank magic. Like for an imprecise sense, you don't learn the exact location, but can narrow down the source to within a 5-foot cube (or the nearest if larger than that).