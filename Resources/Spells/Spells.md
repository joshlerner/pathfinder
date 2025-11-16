---
cssclasses:
- pf2e
---

```dataview
TABLE WITHOUT ID file.link as "Name", join(traditions, ", ") as Tradition, join(traits, ", ") as "Traits", spell_type as "Spell Type", spell_rank as "Rank"
FROM "Resources/Spells"
SORT file.name asc
```