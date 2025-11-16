---
cssclasses: pf2e
traditions:
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
# Know the Way `pf2:2` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Player Core pg. 340 <sup>2.0</sup>*
**Traditions** `=this.traditions`
___
In your mind's eye, you magically reorient yourself. You immediately know which direction is north (if it exists at your current location), and you can choose a location you were at within the last 24 hours and learn what direction it lies.
___
**Heightened (3rd)** You can choose a location you were at within the last week.  
**Heightened (7th)** You can choose a location you were at regardless of how long ago you were there.