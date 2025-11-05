---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- Witchwoven
---
# [Witchwoven](3-Mechanics\CLI\bestiary\construct/witchwoven-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 593*  

---

*Helper Made of Twine and Twigs (Ruby wrapped in a wicker cage)*

---

Witchwoven are little dolls or effigies made of sticks, twine, and other simple materials, then imbued with life. Some happen naturally in places suffused with old nature magic, but most are created to serve as familiars by spellcasters knowledgeable in the Old Ways.

```statblock
"name": "Witchwoven (CrookedMoon24)"
"size": "Tiny"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "21"
"hit_dice": "6d4 + 6"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "17"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "10"
"speed": "20 ft."
"skillsaves":
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_vulnerabilities": "fire"
"damage_immunities": "poison"
"condition_immunities": "[deafened](/3-Mechanics/CLI/conditions.md#Deafened), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 12"
"languages": "understands Sylvan but can't speak"
"cr": "1"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing damage\
      \ plus 3 (1d6) Necrotic damage, and if the target is a creature, it has <span\
      \ title=\"Player's Handbook (2024)\">Disadvantage</span> on attack rolls until\
      \ the start of the witchwoven's next turn."
    "name": "Cursed Scratch"
"reactions":
  - "desc": "Trigger: A creature the witchwoven can see within 60 feet takes damage.\
      \ _Response:_ The creature gains <span title=\"Player's Handbook (2024)\">Resistance</span>\
      \ to the triggering damage, and the witchwoven takes 10 (3d6) Force damage."
    "name": "Protective Bond"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Witchwoven.webp"
```
^statblock

## Environment

any