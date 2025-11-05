---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mori Shade
---
# [Mori Shade](3-Mechanics\CLI\bestiary\npc/mori-shade-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 207*  

Mori Shade deals in death. Rather than making her an outcast in the town, she's earned the respect of the people. They trust her to handle their remains with dignity and respect. She takes an interest in the various beliefs of the people, making her a good source of folklore.

A slight woman of indeterminate age, Mori has a stately, if grim, bearing. Her striking white hair is contrasted by an all-black wardrobe.

Mori does not follow the faiths of Wickermoor Hollow. Instead, she adheres to the spiritual beliefs of the Strangers (see "The Shroud" in chapter 1) who serve as ferrymen of the dead. She learned much of these beliefs from Yorgrim, the gravedigger (see chapter 19), with whom she works closely in giving the dead their proper burial.

```statblock
"name": "Mori Shade (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "11"
  - !!int "13"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "1/2"
"actions":
  - "desc": "Mori makes two attacks, using Shortsword and Longbow in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Attack Roll:* +4, range 150/600 ft. *Hit:* 6 (1d8 + 2) Piercing\
      \ damage."
    "name": "Longbow"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Mori%20Shade.webp"
```
^statblock