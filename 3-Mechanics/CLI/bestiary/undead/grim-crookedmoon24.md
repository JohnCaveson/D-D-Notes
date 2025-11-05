---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Grim
---
# [Grim](3-Mechanics\CLI\bestiary\undead/grim-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 85*  

```statblock
"name": "Grim (CrookedMoon24)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral"
"ac_class": "13 plus your Wisdom modifier"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "10"
"speed": "40 ft."
"damage_immunities": "necrotic"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "understands the languages you know"
"traits":
  - "desc": "The grim can move through other creatures and objects as if they were\
      \ <span title=\"Player's Handbook (2024)\">Difficult Terrain</span>. The grim\
      \ takes 1d10 Force damage if it ends its turn inside an object."
    "name": "Incorporeal Movement"
  - "desc": "Add your <span title=\"Player's Handbook (2024)\">Proficiency Bonus</span>\
      \ to any ability check or saving throw the grim makes."
    "name": "Shared Fate"
"actions":
  - "desc": "*Melee Attack Roll:* Bonus equals your spell attack modifier, reach 5\
      \ ft. *Hit:* 1d6 + 3 plus your Wisdom modifier Necrotic damage, and if the target\
      \ is a creature, it has the Frightened condition until the start of your next\
      \ turn."
    "name": "Ominous Rend"
"reactions":
  - "desc": "Trigger: A creature moves out of the grim's reach. _Response—_*Wisdom\
      \ Saving Throw:* Your spell save DC, the triggering creature. *Failure:* The\
      \ target's <span title=\"Player's Handbook (2024)\">Speed</span> is 0 until\
      \ the end of the turn."
    "name": "Baleful Howl"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Grim.webp"
```
^statblock