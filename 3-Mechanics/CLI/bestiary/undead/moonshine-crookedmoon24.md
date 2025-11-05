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
- Moonshine
---
# [Moonshine](3-Mechanics\CLI\bestiary\undead/moonshine-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 589*  

---

*Lingering Soul Guide (Broken glass and powdered onyx)*

---

When a person dies with unfinished business, their soul can remain shackled to the living world as an Undead spirit. Usually such spirits rest and move on when their business is concluded, but some remain as companions, guides, and helpers for the living. Moonshines are spirits who resolved their emotional tethers but have chosen to linger on. They often take a liking to a living person and choose to help them through their life's journey.

```statblock
"name": "Moonshine (CrookedMoon24)"
"size": "Tiny"
"type": "undead"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "5d4 + 10"
"modifier": !!int "3"
"stats":
  - !!int "1"
  - !!int "16"
  - !!int "14"
  - !!int "11"
  - !!int "13"
  - !!int "9"
"speed": "5 ft., fly 30 ft. (hover)"
"damage_resistances": "acid, bludgeoning, cold, fire, lightning, necrotic, piercing,\
  \ slashing, thunder"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., Detect Life\
  \ (see below), passive Perception 11"
"languages": "Common plus one other language"
"cr": "1"
"traits":
  - "desc": "The moonshine magically senses the direction of creatures up to 60 feet\
      \ away that aren't Constructs or Undead."
    "name": "Detect Life"
  - "desc": "The moonshine can't wear or carry anything."
    "name": "Ephemeral"
  - "desc": "The moonshine sheds <span title=\"Player's Handbook (2024)\">Bright Light</span>\
      \ in a 15-foot radius and <span title=\"Player's Handbook (2024)\">Dim Light</span>\
      \ for an additional 15 feet."
    "name": "Illumination"
  - "desc": "The moonshine can move through other creatures and objects as if they\
      \ were <span title=\"Player's Handbook (2024)\">Difficult Terrain</span>. It\
      \ takes 5 (1d10) Force damage if it ends its turn inside an object."
    "name": "Incorporeal Movement"
  - "desc": "It takes 5 (1d10) Force damage if it ends its turn inside an object."
    "name": "Difficult Terrain"
"actions":
  - "desc": "The moonshine makes two Gloomy Touch attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Psychic damage."
    "name": "Gloomy Touch"
  - "desc": "*Constitution Saving Throw:* DC 11, one creature that isn't a Construct\
      \ or Undead the moonshine can see within 5 feet. *Failure:* The target has the\
      \ Stunned condition until the end of the moonshine's next turn, and the moonshine\
      \ or a creature of its choice within 30 feet regains 3 (1d6) <span title=\"\
      Player's Handbook (2024)\">Hit Points</span>."
    "name": "Siphon Life (2/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Moonshine.webp"
```
^statblock

## Environment

any