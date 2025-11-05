---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- Shuck
---
# [Shuck](3-Mechanics\CLI\bestiary\npc/shuck-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 219*  

A red-furred dog that never leaves [Dani's](/3-Mechanics/CLI/bestiary/npc/dani-jenkin-crookedmoon24.md) side, Shuck was a stray before the Jenkins took him in. Unbeknownst to the family, Shuck is the reincarnated soul of Sally Lockwood, a victim of the Crooked House who escaped just before her death. Shuck guards Dani fiercely. If any of the characters are evil, or if they use supernatural abilities that are in any way associated with the Crooked Queen, Shuck growls at them if they get anywhere near Dani.

```statblock
"name": "Shuck (CrookedMoon24)"
"size": "Medium"
"type": "beast"
"alignment": "Neutral Good"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "15"
  - !!int "12"
  - !!int "3"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"senses": "[Darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "Shuck has <span title=\"Player's Handbook (2024)\">Advantage</span> on\
      \ attack rolls against a creature if at least one of Shuck's allies is within\
      \ 5 feet of the creature and the ally doesn't have the Incapacitated condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage.\
      \ If the target is a Medium or smaller creature, it has the Prone condition."
    "name": "Bite"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Shuck.webp"
```
^statblock