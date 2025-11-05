---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/unknown
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wildpyre
---
# [Wildpyre](3-Mechanics\CLI\bestiary\undead/wildpyre-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 539*  

---

*Spectral Blazing Beast*

---

When animals perish in flames, their escaping spirits can cling to the fire that took their lives and arise as wildpyres. These Undead resemble the kind of animal they were in life, though made of ghostly flames. They lash out at anything in their vicinity, fanning the flames that consumed them.

## Secret

Water can extinguish the undying flames of wildpyres, despite their ephemeral existence.

```statblock
"name": "Wildpyre (CrookedMoon24)"
"size": "Unknown"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "4"
"stats":
  - !!int "6"
  - !!int "18"
  - !!int "14"
  - !!int "4"
  - !!int "12"
  - !!int "7"
"speed": "5 ft., fly 60 ft. (hover)"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "acid, bludgeoning, lightning, piercing, slashing, thunder"
"damage_immunities": "fire, necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 17"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The wildpyre can move through other creatures and objects as if they\
      \ were <span title=\"Player's Handbook (2024)\">Difficult Terrain</span>. It\
      \ takes 5 (1d10) Force damage if it ends its turn inside an object."
    "name": "Incorporeal Movement"
  - "desc": "Any water affects the wildpyre as if it were Holy Water."
    "name": "Quenching Water"
"actions":
  - "desc": "The wildpyre makes two Blazing Rend attacks and uses Flame Bind if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 8 (1d8 + 4) Necrotic damage\
      \ plus 7 (2d6) Fire damage, and the target begins burning. If the target is\
      \ a creature no larger than the wildpyre, it has the Prone condition."
    "name": "Blazing Rend"
  - "desc": "*Dexterity Saving Throw:* DC 15, one creature the wildpyre can see within\
      \ 60 feet. *Failure:* The target has the Restrained condition. At the end of\
      \ each of the target's turns, it repeats the saving throw, ending the effect\
      \ on itself on a success. During the target's turn, it can choose to end the\
      \ Restrained condition by taking 6 (1d12) Fire damage plus 6 (1d12) Necrotic\
      \ damage."
    "name": "Flame Bind (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Wildpyre.webp"
```
^statblock

## Environment

any