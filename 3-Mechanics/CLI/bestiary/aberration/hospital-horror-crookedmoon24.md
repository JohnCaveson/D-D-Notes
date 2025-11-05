---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hospital Horror
---
# [Hospital Horror](3-Mechanics\CLI\bestiary\aberration/hospital-horror-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 507*  

---

*Mutated Experiment*

---

Hospital horrors were once people, but now they are repulsive mockeries created through surgical  and magical alteration. They have no memory of  their past lives, existing only within a chemically induced rage. Often, they are conditioned by the use of specific command phrases that allow them  to be controlled.

## Secret

Hospital horrors have spent much of their existence being prodded with needles, so being pierced frays what few wits they retain.

```statblock
"name": "Hospital Horror (CrookedMoon24)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "30"
"hit_dice": "4d8 + 12"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "7"
  - !!int "9"
  - !!int "6"
"speed": "40 ft., climb 30 ft."
"saves":
  - "strength": !!int "6"
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
"damage_resistances": "acid, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 9"
"languages": "understands Common and Deep Speech but can't speak"
"cr": "1"
"traits":
  - "desc": "If the horror takes Piercing damage, it has <span title=\"Player's Handbook\
      \ (2024)\">Disadvantage</span> on attack rolls until the end of its next turn."
    "name": "Aversion to Needles"
  - "desc": "The horror has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on an attack roll against a creature if at least one of the horror's allies\
      \ is within 5 feet of the creature and the ally doesn't have the Incapacitated\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "The horror makes two Graft Blade attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing damage."
    "name": "Graft Blade"
"bonus_actions":
  - "desc": "The horror takes the Dash action and can jump up to 30 feet by spending\
      \ 10 feet of movement."
    "name": "Stim Burst"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Hospital%20Horror.webp"
```
^statblock

## Environment

any