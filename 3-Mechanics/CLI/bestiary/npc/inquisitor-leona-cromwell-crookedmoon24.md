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
- Inquisitor Leona Cromwell
---
# [Inquisitor Leona Cromwell](3-Mechanics\CLI\bestiary\npc/inquisitor-leona-cromwell-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 267*  

Leona Cromwell was once a child of Dawn's Gate, learning her letters and numbers under the shadow of Friar Olaf. Yet, over the years, her contempt for the pompous friar festered, driving her away from the monastery. She wandered to Wickermoor Village, picking up odd jobs and eventually working as a town guard. Her fate changed course when a group of highwaymen took her captive. Marius Renathyr came to her rescue and drove the bandits to the marshes south of Moonsong Lake. Rather than flee, she used her skills with a blade to slay their leader and demanded obedience from the weakened crew.

For years, she was known as Leona the Relentless, leading raids through Wickermoor Hollow. But the guilt of her deeds gnawed at her soul. She learned that the great Sir Marius who saved her life years prior had hung up his sword, and she traveled to his Crimson Monastery to repent. Father Renathyr, a twisted reflection of the knight he once was, spoke of the Crimson Rose, offering redemption for her tarnished soul. Stricken with guilt but unwilling to let go of the power she craved as a bandit queen, Leona accepted his gift.

```statblock
"name": "Inquisitor Leona Cromwell (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
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
  - "desc": "Cromwell makes two attacks, using Greatsword or Heavy Crossbow in any\
      \ combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Slashing damage\
      \ plus 4 (1d8) Radiant damage."
    "name": "Greatsword"
  - "desc": "*Ranged Attack Roll:* +2, range 100/400 ft. *Hit:* 11 (2d10) Piercing\
      \ damage plus 4 (1d8) Radiant damage."
    "name": "Heavy Crossbow"
"reactions":
  - "desc": "Trigger: Cromwell is hit by a melee attack roll while holding a weapon.\
      \ _Response:_ Cromwell adds 2 to its AC against that attack, possibly causing\
      \ it to miss."
    "name": "Parry"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Leona%20Cromwell.webp"
```
^statblock