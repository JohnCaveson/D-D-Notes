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
- Baltus Tolliver
---
# [Baltus Tolliver](3-Mechanics\CLI\bestiary\npc/baltus-tolliver-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 199*  

Baltus Tolliver left Wickermoor Village and traveled across Druskenvald as a young man. He returned a decade later with some wealth, a whole lot of lavish goods, and the contacts to find any strange oddity across the domain. Using a blend of charm and intimidation, Baltus established the largest trading post in the hollow. He sells everything from basic goods to rare trinkets.

He is a slender man who wears the same gray suit every night, making sure it is meticulously cleaned every evening. He's clean-shaven, and his thinning black hair betrays his upper middle age. He wears plain silver rings and smokes a decoratively carved mahogany pipe.

Although he spent his youth away from Wickermoor Hollow, Baltus is a Follower of the Old Ways that serves in the cult of the Crooked Queen. He was called home by the ever-growing strength of Kehlenn, and his wealth and trading power help fund and coordinate efforts to unleash her. His guards revere the Old Ways and the Green Queen, but they are unaware of Baltus's allegiance to the wicked cult.

```statblock
"name": "Baltus Tolliver (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+3"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+3"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Slashing damage\
      \ plus 7 (2d6) Necrotic damage."
    "name": "Pact Blade"
  - "desc": "Baltus casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 12, +4 to hit with spell attacks):\n\n**At will:**\
      \ Light, Thaumaturgy\n\n**2/day:** Command\n\n**1/day:** Hold Person"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Baltus casts the Spiritual Weapon spell, using the same spellcasting\
      \ ability as Spellcasting.\n"
    "name": "Spiritual Weapon (2/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Baltus%20Tolliver.webp"
```
^statblock