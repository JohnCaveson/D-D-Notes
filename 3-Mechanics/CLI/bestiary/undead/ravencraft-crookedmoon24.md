---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ravencraft
---
# [Ravencraft](3-Mechanics\CLI\bestiary\undead/ravencraft-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 591*  

---

*Undead Avian Amalgamation (Silver wire)*

---

Ravencrafts are a grotesque fusion of feathers, sinew, and bone. Their tiny form is a contorted and twisted nightmare carelessly sewn together into the mockery of a bird. The mere presence of a ravencraft is an affront to natural death and can keep further death at bay, or they can chill the hearts of their foes with cries of torment from beyond the grave.

```statblock
"name": "Ravencraft (CrookedMoon24)"
"size": "Tiny"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "30"
"hit_dice": "12d4"
"modifier": !!int "2"
"stats":
  - !!int "2"
  - !!int "14"
  - !!int "11"
  - !!int "8"
  - !!int "12"
  - !!int "4"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": ""
"cr": "1"
"traits":
  - "desc": "If damage reduces the ravencraft to 0 <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span>, it makes a Constitution saving throw (DC 5 plus\
      \ the damage taken) unless the damage is Radiant or from a <span title=\"Player's\
      \ Handbook (2024)\">Critical Hit</span>. On a successful save, the ravencraft\
      \ drops to 1 <span title=\"Player's Handbook (2024)\">Hit Point</span> instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Piercing damage\
      \ plus 3 (1d6) Necrotic damage."
    "name": "Beak"
  - "desc": "The ravencraft lets out a wail of anguish commingling with the croaking\
      \ of ravens. *Wisdom Saving Throw:* DC 11, one creature within 60 feet. *Failure:*\
      \ 5 (1d10) Psychic damage, and the target has the Frightened condition until\
      \ the end of its next turn. *Success:* Half damage only."
    "name": "Harbinger of Doom (2/Day)"
"reactions":
  - "desc": "Trigger: A creature within 30 feet of the ravencraft makes a <span title=\"\
      Player's Handbook (2024)\">Death Saving Throw</span>. _Response:_ The creature\
      \ has <span title=\"Player's Handbook (2024)\">Advantage</span> on the save."
    "name": "Death Veil"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Ravencraft.webp"
```
^statblock

## Environment

any