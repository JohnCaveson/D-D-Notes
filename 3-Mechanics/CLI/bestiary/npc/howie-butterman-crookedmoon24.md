---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Howie Butterman
---
# [Howie Butterman](3-Mechanics\CLI\bestiary\npc/howie-butterman-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 198*  

Howie Butterman is short and wiry, and his brown hair sticks out from his uniform cap. While he doesn't look imposing, he is quick and deadly in a fight.

Deputy Howie presents himself as the more affable of the law-enforcement duo. His friendly demeanor and helpful attitude make him more suitable than the constable at dealing with the public. He plays "good cop" to [Constable Doris's](/3-Mechanics/CLI/bestiary/npc/doris-squire-crookedmoon24.md) "bad cop" when dealing with lawbreakers.

In reality, Deputy Howie is a fervent cult member who works behind the scenes to bring about the return of the Crooked Queen. He uses his position of authority to move events very subtly toward her return. The arrival of [Phillip](/3-Mechanics/CLI/bestiary/npc/phillip-druskenvald-crookedmoon24.md) and [Adela](/3-Mechanics/CLI/bestiary/npc/adela-druskenvald-crookedmoon24.md) triggers him and the other servants of the Crooked Queen to put their plans into action (see chapter 8).

```statblock
"name": "Howie Butterman (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "6d8"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "10"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Investigation](/3-Mechanics/CLI/skills.md#Investigation)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Sleight of Hand](/3-Mechanics/CLI/skills.md#Sleight%20of%20Hand)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "Common plus one other language"
"cr": "1"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage\
      \ plus 7 (2d6) Poison damage."
    "name": "Shortsword"
  - "desc": "*Ranged Attack Roll:* +4, range 30/120 ft. *Hit:* 5 (1d6 + 2) Piercing\
      \ damage plus 7 (2d6) Poison damage."
    "name": "Hand Crossbow"
"bonus_actions":
  - "desc": "Howie takes the Dash, Disengage, or Hide action."
    "name": "Cunning Action"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Howie%20Butterman.webp"
```
^statblock