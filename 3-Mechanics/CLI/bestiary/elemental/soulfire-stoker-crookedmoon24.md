---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/planar-elemental-plane-of-fire
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Soulfire Stoker
---
# [Soulfire Stoker](3-Mechanics\CLI\bestiary\elemental/soulfire-stoker-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 532*  

---

*Engine-Born Spirit of Flame and Death*

---

Soulfire stokers are Elemental spirits of fire who inhabit furnaces, engines, and boilers that burn bodies or souls. The resulting creature is composed of ghostly flames and steam, with swirling plates of phantom iron that resemble the engine or machine that gave it form. A crackling blend of fire and negative energy, soulfire stokers burn away souls as much as flesh.

## Secret

Soulfire stokers are compelled to burn corpses they can see, so dead things can bait the spirits.

```statblock
"name": "Soulfire Stoker (CrookedMoon24)"
"size": "Medium"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "59"
"hit_dice": "7d8 + 28"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "16"
  - !!int "18"
  - !!int "9"
  - !!int "12"
  - !!int "7"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "fire, poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": "Primordial (Ignan)"
"cr": "4"
"traits":
  - "desc": "If the stoker can see a corpse at the start of its turn, it must move\
      \ as far as possible to enter the corpse's space and use its action to incinerate\
      \ the corpse. Medium or smaller corpses are reduced to ash, and larger corpses\
      \ are partially incinerated and decrease one size."
    "name": "Corpse Fuel"
  - "desc": "The stoker can move through a space as narrow as 1 inch without expending\
      \ extra movement to do so, and it can enter a creature's space and stop there.\
      \ The first time it enters a creature's space on a turn, that creature takes\
      \ 4 (1d8) Fire damage."
    "name": "Fire Form"
  - "desc": "The stoker sheds <span title=\"Player's Handbook (2024)\">Dim Light</span>\
      \ in a 30-foot radius."
    "name": "Illumination"
  - "desc": "At the end of each of the stoker's turns, each creature in a 5-foot <span\
      \ title=\"Player's Handbook (2024)\">Emanation</span> originating from the stoker\
      \ takes 4 (1d8) Necrotic damage."
    "name": "Soul Burn"
"actions":
  - "desc": "The stoker makes two Sear attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Fire damage,\
      \ and the target has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on the next attack roll it makes before the start of the elemental's next\
      \ turn."
    "name": "Sear"
"bonus_actions":
  - "desc": "The stoker unleashes a blast of glowing spectral steam. *Dexterity Saving\
      \ Throw:* DC 13, each creature in a 30-foot <span title=\"Player's Handbook\
      \ (2024)\">Cone</span>. *Failure:* For 1 minute, the target sheds <span title=\"\
      Player's Handbook (2024)\">Dim Light</span> in a 10-foot radius and can't benefit\
      \ from the Invisible condition."
    "name": "Spectral Steam (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Soulfire%20Stoker.webp"
```
^statblock

## Environment

planar (elemental plane of fire), urban