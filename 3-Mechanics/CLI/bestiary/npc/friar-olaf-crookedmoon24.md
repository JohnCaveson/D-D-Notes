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
- Friar Olaf
---
# [Friar Olaf](3-Mechanics\CLI\bestiary\npc/friar-olaf-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 264*  

As a young monk, Friar Olaf of the Silver Bells was the leader of the monastery before Renathyr took it over and became his second convert thereafter. In its early years, the cloister was called Silverbell Monastery, for it overlooks the Silverbell River in the valley below, and it was dedicated to the Patient Lady. There, Olaf and his monks tended to the infirm and to outcasts, but he longed in his heart for glory. He demanded payment from his charges and commissioned a great silver bell for the monastery inscribed with his name so that he would be remembered forever.

Renathyr's arrival stoked Olaf's hunger for reverence and immortality. It was simple to urge Olaf onward from stipends of coin to sacrifices of blood.

```statblock
"name": "Friar Olaf (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric"
"alignment": "Neutral Evil"
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
  - "desc": "Friar makes two attacks, using Mace or Radiant Flame in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Bludgeoning damage\
      \ plus 5 (2d4) Radiant damage."
    "name": "Mace"
  - "desc": "*Ranged Attack Roll:* +5, range 60 ft. *Hit:* 11 (2d10) Radiant damage."
    "name": "Radiant Flame"
  - "desc": "Friar casts one of the following spells, using Wisdom as the spellcasting\
      \ ability:\n\n**At will:** Light, Thaumaturgy\n\n**1/day:** Spirit Guardians"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Friar casts Bless, Dispel Magic, Healing Word, or Lesser Restoration,\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Divine Aid (3/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Friar%20Olaf.webp"
```
^statblock