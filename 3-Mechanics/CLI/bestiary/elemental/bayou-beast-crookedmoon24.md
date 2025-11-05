---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bayou Beast
---
# [Bayou Beast](3-Mechanics\CLI\bestiary\elemental/bayou-beast-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 489*  

---

*Spirit Hex-Bound to the Swamp*

---

Bayou beasts are elemental spirits bound into great mounds of swamp plant matter through jinxcraft magic. These hulks obey their creators unfailingly, often lingering long after their death and carrying out their final orders. The hexed seals, fashioned from carved trinkets and masks, that trap the spirit in its form impart their curse on the creature's enemies.

## Secret

The jinxcraft seals can be washed away with alcohol, hindering and even destroying the bayou beast.

```statblock
"name": "Bayou Beast (CrookedMoon24)"
"size": "Large"
"type": "elemental"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "105"
"hit_dice": "10d10 + 50"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "20"
  - !!int "5"
  - !!int "10"
  - !!int "6"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "fire"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "understands Primordial (Aquan) but can't speak"
"cr": "6"
"traits":
  - "desc": "The elemental takes 9 (2d8) Force damage for every bottle of alcohol\
      \ splashed onto it, and its <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ is reduced to 0 until the end of its next turn."
    "name": "Spirits Susceptibility"
"actions":
  - "desc": "The elemental makes two Hexed Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 10 ft. *Hit:* 18 (3d8 + 5) Bludgeoning\
      \ damage. If the target is a creature, it must succeed on a DC 16 Wisdom saving\
      \ throw or be cursed until the start of the elemental's next turn. While cursed,\
      \ the creature subtracts 1d4 from its attack rolls and saving throws."
    "name": "Hexed Slam"
  - "desc": "Swamp water and plants roil around the elemental. *Strength Saving Throw:*\
      \ DC 16, each creature on the ground in a 20-foot <span title=\"Player's Handbook\
      \ (2024)\">Emanation</span> originating from the elemental. *Failure:* 11 (2d10)\
      \ Poison damage, and the target has the Restrained condition for 1 minute, until\
      \ the elemental has the Incapacitated condition, or until the elemental dies.\
      \ The target or a creature within 5 feet of it can take an action to make a\
      \ DC 16 Strength (Athletics) check, ending the Restrained condition on the target\
      \ on a success."
    "name": "Swamp Grasp (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Bayou%20Beast.webp"
```
^statblock

## Environment

Swamp