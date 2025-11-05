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
- Gaston Doray
---
# [Gaston Doray](3-Mechanics\CLI\bestiary\npc/gaston-doray-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 209*  

Gaston Doray is a painter whose works all contain an ethereal quality. He came into town on a fog-shrouded night a few years ago, and no one has been able to determine his history. He's quite young, with just the beginnings of a beard sprouting on his chin and cheeks.

[Adela Druskenvald](/3-Mechanics/CLI/bestiary/npc/adela-druskenvald-crookedmoon24.md) becomes quite taken with Gaston and his dream-like paintings, becoming his patron.

He has a particular candor with friends and strangers alike that some find refreshing, while others find uncomfortable. In all pursuits, he is deeply philosophical and sometimes even nonsensical to the simple folk of Wickermoor Village.

Gaston is a conduit through which Kehlenn expresses visions, which have driven him to very recently begin the initiation into the cult of the Crooked Queen. As the adventure progresses, Gaston's paintings become more and more bizarre and unsettling. By the end of the adventure, Gaston is completely unhinged and does the bidding of the worst of the Crooked Queen's followers.

```statblock
"name": "Gaston Doray (CrookedMoon24)"
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
  - "desc": "Gaston casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 12, +4 to hit with spell attacks):\n\n**At will:**\
      \ Light, Thaumaturgy\n\n**2/day:** Command\n\n**1/day:** Hold Person"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Gaston casts the Spiritual Weapon spell, using the same spellcasting\
      \ ability as Spellcasting.\n"
    "name": "Spiritual Weapon (2/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Gaston%20Doray.webp"
```
^statblock