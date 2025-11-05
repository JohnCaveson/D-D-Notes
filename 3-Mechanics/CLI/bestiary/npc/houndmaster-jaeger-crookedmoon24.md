---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Houndmaster Jaeger
---
# [Houndmaster Jaeger](3-Mechanics\CLI\bestiary\npc/houndmaster-jaeger-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 264*  

Sigmund Jaeger served Father Renathyr as a squire during Renathyr's time as a knight, raising hunting dogs to track down men and monsters alike.

When the knight founded the Crimson Faith, Jaeger was the first Renathyr sought and the first to convert. The houndmaster had a loving family once, but—like Renathyr—he abandoned them, tempted by the promises of the Crimson Rose. He took only his hounds with him, which he turned into batlike hybrids using blood magic. Now a prior of the Crimson Monastery, Jaeger rears and trains the [Bat Hounds](/3-Mechanics/CLI/bestiary/monstrosity/bat-hound-crookedmoon24.md) and Warhorses used to track down the faithless.

```statblock
"name": "Houndmaster Jaeger (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "strength": !!int "4"
  - "dexterity": !!int "5"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+4"
"senses": "passive Perception 10"
"languages": "Common, Thieves' cant"
"cr": "2"
"actions":
  - "desc": "Jaeger makes two attacks, using Scimitar and Pistol in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing damage."
    "name": "Scimitar"
  - "desc": "*Ranged Attack Roll:* +5, range 30/90 ft. *Hit:* 8 (1d10 + 3) Piercing\
      \ damage."
    "name": "Pistol"
"reactions":
  - "desc": "Trigger: Jaeger is hit by a melee attack roll while holding a weapon.\
      \ _Response:_ Jaeger adds 2 to its AC against that attack, possibly causing\
      \ it to miss."
    "name": "Parry"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Sigmund%20Jaeger.webp"
```
^statblock