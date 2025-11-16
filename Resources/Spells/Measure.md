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
---
# Measure `pf2:1` <span class="right-side"> `=this.spell_type + " " + this.spell_rank`</span>

`=join(map(this.traits, (x) => "==" + x + "=="), " ")`
**Source** *Starfinder Player Core pg. 344*
**Traditions** `=this.traditions`
**Area** 200-foot emanation
**Duration** sustained up to 1 minute
___
You learn the approximate measurements of creatures and objects you can observe in the area. If an object or creature extends out of the area, you learn only the measurements within the area, but nothing about what you can't observe. For example, you can't determine the thickness or weight of a wall you can observe only one side of, or the depth of water that extends beyond the spell's range. Each time you [[Sustain]] the spell, you learn the exact measurements of one creature or object in the area, including imprecisions or anomalies that might indicate structural weakness. Magically altered targets give you information that reflects what you observe rather than accurate measurements.
___
**Heightened (+1)** Extend the range of measure by 100 feet.

