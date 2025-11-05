---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/cleric
statblock: inline
statblock-link: "#^statblock"
aliases:
- Weston Murdoch
---
# [Weston Murdoch](3-Mechanics\CLI\bestiary\npc/weston-murdoch-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 205*  

Weston Murdoch had his eyes opened to the power of goodness and forgiveness as a young child. His parents were both criminals who died for their crimes, and Weston was taken in by a loving family who taught him the path of light. He now strives to bring that same hope and redemption to others.

He is a charismatic man in his late twenties with sandy hair, blue eyes, and a personality that lights up a room the moment he enters. His wife and children, equally beaming and exuberant, make a powerful team of missionaries.

Weston is the leader of the Brightsingers in Wickermoor Village. The flocks of beautiful songbirds that congregate around his home are constantly at odds with the pigeons who occupy the Dovecote (area V21).

```statblock
"name": "Weston Murdoch (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric"
"alignment": "Lawful Neutral"
"ac": !!int "13"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "16"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "2"
"actions":
  - "desc": "Weston makes two attacks, using Mace or Radiant Flame in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Bludgeoning damage\
      \ plus 5 (2d4) Radiant damage."
    "name": "Mace"
  - "desc": "*Ranged Attack Roll:* +5, range 60 ft. *Hit:* 11 (2d10) Radiant damage."
    "name": "Radiant Flame"
  - "desc": "Weston casts one of the following spells, using Wisdom as the spellcasting\
      \ ability:\n\n**At will:** Light, Thaumaturgy\n\n**1/day:** Spirit Guardians"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Weston casts Bless, Dispel Magic, Healing Word, or Lesser Restoration,\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Divine Aid (3/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Weston%20Murdoch.webp"
```
^statblock