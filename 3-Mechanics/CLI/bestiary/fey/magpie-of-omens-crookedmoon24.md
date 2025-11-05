---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Magpie of Omens
---
# [Magpie of Omens](3-Mechanics\CLI\bestiary\fey/magpie-of-omens-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 588*  

---

*Bird of Fate and Fortune (Crystal or gemstone shards)*

---

To those who respect the Old Ways, this bird of black and white brings tidings both fair and foul. Although the omens the magpie delivers can bring joy and grief in equal measure, they are always trustworthy.

```statblock
"name": "Magpie of Omens (CrookedMoon24)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "25"
"hit_dice": "10d4"
"modifier": !!int "3"
"stats":
  - !!int "2"
  - !!int "17"
  - !!int "10"
  - !!int "5"
  - !!int "12"
  - !!int "6"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The magpie doesn't provoke an Opportunity Attack when it flies out of\
      \ an enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "The magpie makes two Beak attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing damage\
      \ plus 3 (1d6) Radiant damage."
    "name": "Beak"
"bonus_actions":
  - "desc": "The magpie can form or dissolve a magical bond with a willing creature\
      \ within 5 feet. While the bond lasts, the bonded creature can speak through\
      \ the magpie using the creature's own voice and language, but with a birdlike\
      \ lilt. The bond ends when the creature dies or if the magpie creates a new\
      \ bond."
    "name": "Bonded Voice"
"reactions":
  - "desc": "Trigger: A creature within 30 feet of the magpie makes a <span title=\"\
      Player's Handbook (2024)\">D20 Test</span> with <span title=\"Player's Handbook\
      \ (2024)\">Advantage</span>. _Response:_ The target rolls 1d6 and subtracts\
      \ it from the total."
    "name": "One for Sorrow (1/Day)"
  - "desc": "Trigger: The magpie or another creature within 30 feet makes an ability\
      \ check or a saving throw. _Response:_ The target rolls 1d4 and adds it to the\
      \ total."
    "name": "Two for Joy (2/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Magpie%20of%20Omens.webp"
```
^statblock

## Environment

forest, grassland, planar (fey)