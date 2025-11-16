---
cssclasses: pf2e
statblock: true
player: true
dice: true
columnWidth: 600px
layout: Custom Pathfinder 2e Layout
name: <% tp.file.title %>
level:
identity:
  - name: Ancestry
    desc: <br>
  - name: Background
    desc: <br>
  - name: Class
    desc: <br>
size:
trait_01: ""
trait_02: ""
trait_03: ""
trait_04: ""
trait_05: ""
trait_06: ""
trait_07: ""
languages:
  - Common
modifier:
senses:
dc:
ac:
fortitude:
Reflex:
Will:
hp:
speeds:
  - type:
    value:
abilityMods:
  - ""
  - ""
  - ""
  - ""
  - ""
  - ""
Acrobatics:
Arcana:
Athletics:
Crafting:
Deception:
Diplomacy:
Intimidation:
Lore:
Medicine:
Nature:
Occultism:
Performance:
Religion:
Society:
Stealth:
Survival:
Thievery:
attacks:
  - name:
    desc: "<br> &nbsp +x (`dice: 1d20 + x`) xdx (`dice: xdx`)"
actions:
  - name: ""
spell_modifier:
spellcasting:
spell_list:
  - name: Cantrips
    desc:
      - ""
  - name: 1st Rank
    slots:
    desc:
      - ""
  - name: Focus
    slots:
    desc:
      - ""
inventory_items:
current_hp:
current_temp_hp: ""
health:
  - name: Hit Points
    desc: <br> `INPUT[number(class(hp-input), placeholder(HP)):current_hp]` / `=this.hp` <br> `INPUT[number(class(hp-input), placeholder(––)):current_temp_hp]` Temp
  - name: Resistances
    desc: 
  - name: Weaknesses
    desc:
perception:
  - name: Perception
    desc: |-
      +`=this.modifier` (`dice: 1d20 + modifier`) 
       `=this.senses`
movement:
  - name: Speed
    desc: '`=map(this.speeds, (x) => "<br>" + x.value + replace(" feet " + x.type, " Normal", ""))`'
language:
  - name: Languages
    desc: <br> `=join(this.languages, "<br>")`
class_dc:
  - name: Class DC
    desc: "`=this.dc`"
armorclass:
  - name: AC
    desc: "`=this.ac`"
  - name: Fortitude &nbsp;
    desc: "<span style='float: right;'> +`=this.fortitude` (`dice: 1d20 + fortitude`)"
  - name: Reflex &nbsp;
    desc: "<span style='float: right;'> +`=this.Reflex` (`dice: 1d20 + Reflex`)"
  - name: Will &nbsp;
    desc: "<span style='float: right;'> +`=this.Will` (`dice: 1d20 + Will`)"
skills:
  - name: "[[Acrobatics]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Acrobatics` (`dice: 1d20 + Acrobatics`) </span>"
  - name: "[[Arcana]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Arcana` (`dice: 1d20 + Arcana`)"
  - name: "[[Athletics]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Athletics` (`dice: 1d20 + Athletics`)"
  - name: "[[Crafting]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Crafting` (`dice: 1d20 + Crafting`)"
  - name: "[[Deception]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Deception` (`dice: 1d20 + Deception`)"
  - name: "[[Diplomacy]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Diplomacy` (`dice: 1d20 + Diplomacy`)"
  - name: "[[Intimidation]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Intimidation` (`dice: 1d20 + Intimidation`)"
  - name: "[[Lore|Lore]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Lore` (`dice: 1d20 + Lore`)"
  - name: "[[Medicine]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Medicine` (`dice: 1d20 + Medicine`)"
  - name: "[[Nature]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Nature` (`dice: 1d20 + Nature`)"
  - name: "[[Occultism]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Occultism` (`dice: 1d20 + Occultism`)"
  - name: "[[Performance]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Performance` (`dice: 1d20 + Performance`)"
  - name: "[[Religion]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Religion` (`dice: 1d20 + Religion`)"
  - name: "[[Society]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Society` (`dice: 1d20 + Society`)"
  - name: "[[Stealth]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Stealth` (`dice: 1d20 + Stealth`)"
  - name: "[[Survival]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Survival` (`dice: 1d20 + Survival`)"
  - name: "[[Thievery]]  &nbsp;"
    desc: "<span style='float: right;'> +`=this.Thievery` (`dice: 1d20 + Thievery`)"
spell_attack: "+`=this.spell_modifier` (`dice: 1d20 + spell_modifier`)"
spell_slots:
  - - ""
inventory: "`INPUT[inlineList():inventory_items]`"
---
```statblock
creature: <% tp.file.title %>
```