---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Alda Farnum
---
# [Alda Farnum](3-Mechanics\CLI\bestiary\npc/alda-farnum-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 196*  

Alda owns and manages the Green Queen Inn. She comes off as friendly, but everything is a transaction to her, whether the currency is coins, gems, art, skills, or favors. Even the most inattentive person doesn't need much time around Alda to see through her polite façade. Her brown hair is worn up under a hat, and her perfectly tailored outfits exude an air of quiet authority.

As a young woman, Alda became disenfranchised with the Old Ways, favoring the prosperity and comfort that modernity provides. However, when she happened upon an ancient tome filled with primeval rituals that harness Kehlenn's essence, she quickly discovered that she could use such power to grow her wealth and station in life. She has since joined the cult of the Crooked Queen as a means to an end in her constant quest for riches and authority.

```statblock
"name": "Alda Farnum (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "11"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+5"
"senses": "passive Perception 12"
"languages": "Common plus two other languages"
"cr": "1/8"
"actions":
  - "desc": "*Melee Attack Roll:* +3, reach 5 ft. *Hit:* 5 (1d8 + 1) Piercing damage."
    "name": "Rapier"
"reactions":
  - "desc": "Trigger: Alda is hit by a melee attack roll while holding a weapon. _Response:_\
      \ Alda adds 2 to its AC against that attack, possibly causing it to miss."
    "name": "Parry"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Alda%20Farnum.webp"
```
^statblock