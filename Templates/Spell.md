---
cssclasses: pf2e
traditions:
  - "[[Arcane]]"
  - "[[Divine]]"
  - "[[Occult]]"
  - "[[Primal]]"
spell_type:
spell_rank:
traits:
- 
---
# <% tp.file.title %> `pf2:0` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Book pg. # <sup>0.0</sup>*
**Traditions** `=this.traditions`
___
