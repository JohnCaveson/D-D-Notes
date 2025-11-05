---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Doris Squire
---
# [Doris Squire](3-Mechanics\CLI\bestiary\npc/doris-squire-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 197*  

Constable Doris Squire is pragmatic, laconic, and plainly dressed. She's tall and stocky, wearing her graying hair under a cap. Her steely gray eyes are alert and seem capable of peering through one's soul.

She makes a habit of speaking only when necessary, using the fewest words possible to get her point across. She leaves the niceties of community relations to her more affable deputy.

Doris openly enforces the laws of the Old Ways, but in her heart, she is one of the Fold of the Patient Lady, enjoying and maintaining a cordial relationship with the wonders of nature. Despite her stoic guise, she is a sensitive soul and secretly writes poetry to express her feelings.

```statblock
"name": "Doris Squire (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "14"
  - !!int "11"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "2"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "passive Perception 10"
"languages": "Common plus one other language"
"cr": "3"
"actions":
  - "desc": "Doris makes two attacks, using Greatsword or Heavy Crossbow in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage\
      \ plus 4 (1d8) Radiant damage."
    "name": "Greatsword"
  - "desc": "*Ranged Attack Roll:* +2, range 100/400 ft. *Hit:* 11 (2d10) Piercing\
      \ damage plus 4 (1d8) Radiant damage."
    "name": "Heavy Crossbow"
"reactions":
  - "desc": "Trigger: Doris is hit by a melee attack roll while holding a weapon.\
      \ _Response:_ Doris adds 2 to its AC against that attack, possibly causing it\
      \ to miss."
    "name": "Parry"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Doris%20Squire.webp"
```
^statblock