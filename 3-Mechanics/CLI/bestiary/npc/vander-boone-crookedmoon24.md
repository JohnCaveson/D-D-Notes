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
- Vander Boone
---
# [Vander Boone](3-Mechanics\CLI\bestiary\npc/vander-boone-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 286*  

Folk often come to Murkwater Bend to trade or scheme, but prize fights draw in the largest crowds. Vander Boone (Chaotic Neutral, human Bandit Captain) was one such prize fighter, a brigand-turned-boxer renowned throughout the swamps. He was popular and successful, but he longed for more. He wanted real power, real control, and real respect.

One night, just short of a year ago, Vander met Mister Crossroads and asked for the power to rule the Drowned Crossroads. All would pay tribute to him and seek his approval. But when [The Grinning Sinner](/3-Mechanics/CLI/bestiary/npc/the-grinning-sinner-crookedmoon24.md) extended his hand, Vander pulled back, shook his head, and told Mister Crossroads he would do it himself. The flabbergasted croc-folk swore that Boone would regret his decision as he walked away.

```statblock
"name": "Vander Boone (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Chaotic Neutral"
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
  - "desc": "Vander makes two attacks, using Scimitar and Pistol in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing damage."
    "name": "Scimitar"
  - "desc": "*Ranged Attack Roll:* +5, range 30/90 ft. *Hit:* 8 (1d10 + 3) Piercing\
      \ damage."
    "name": "Pistol"
"reactions":
  - "desc": "Trigger: Vander is hit by a melee attack roll while holding a weapon.\
      \ _Response:_ Vander adds 2 to its AC against that attack, possibly causing\
      \ it to miss."
    "name": "Parry"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Vander%20Boone.webp"
```
^statblock