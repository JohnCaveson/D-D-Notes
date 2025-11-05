---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/planar-lower-planes
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Reveler of Song (Drone)
---
# [Reveler of Song (Drone)](3-Mechanics\CLI\bestiary\fiend/reveler-of-song-drone-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 525*  

```statblock
"name": "Reveler of Song (Drone) (CrookedMoon24)"
"size": "Medium"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "14"
  - !!int "11"
  - !!int "12"
  - !!int "20"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+11"
"damage_resistances": "cold, fire"
"damage_immunities": "poison, thunder"
"condition_immunities": "[deafened](/3-Mechanics/CLI/conditions.md#Deafened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., [blindsight](/3-Mechanics/CLI/senses.md#Blindsight)\
  \ 10 ft., passive Perception 14"
"languages": "Common; telepathy 120 ft."
"cr": "6"
"traits":
  - "desc": "The reveler can't refuse a contest of skill with Musical Instruments.\
      \ As an Influence action, a creature can make a Charisma (Performance) check\
      \ using a Musical Instrument. The reveler must succeed on a Charisma saving\
      \ throw with a DC equal to the check's total or take 20 Psychic damage and have\
      \ the Stunned condition until the end of the creature's next turn."
    "name": "Compelled Contest"
  - "desc": "The reveler doesn't provoke Opportunity Attacks when it leaves an enemy's\
      \ reach."
    "name": "Dancing Step"
  - "desc": "The reveler takes on a specific form: Drone, Drum, or Bell. The form\
      \ determines certain traits and actions, as well as the instrument the reveler\
      \ plays (hurdy gurdy, frame drum, or handbells, respectively)."
    "name": "Ensemble Form"
  - "desc": "A droning swarm of bees surrounds the reveler. *Constitution Saving Throw:*\
      \ DC 16, each creature that ends its turn in a 10-foot <span title=\"Player's\
      \ Handbook (2024)\">Emanation</span> originating from the reveler. *Failure:*\
      \ The target has the Poisoned condition until the end of its next turn."
    "name": "Droning Swarm"
"actions":
  - "desc": "The reveler makes two Instrumental Blast attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +8, reach 5 ft. or range 90 ft. *Hit:*\
      \ 14 (2d8 + 5) Thunder damage."
    "name": "Instrumental Blast"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Reveler%20of%20Song%20Droning.webp"
```
^statblock

## Environment

planar (lower planes), urban