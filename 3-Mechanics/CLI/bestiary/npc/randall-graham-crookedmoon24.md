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
- Randall Graham
---
# [Randall Graham](3-Mechanics\CLI\bestiary\npc/randall-graham-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 200*  

Randall Graham is one of the most trusted folks in Wickermoor Village. Whether it's a haircut, a bothersome tooth, a quick stitch-up, a timely piece of advice, or just a friendly ear, Randall has what you need. His handsome smile, sandy brown hair and matching beard, and burly build are a fixture around town.

Randall's friendly countenance and charming ways are the perfect disguise for the town's leader of the secretive cult of the Crooked Queen that operates among the Followers of the Old Ways. He downplays his true allegiance in casual company, but he longs for Kehlenn's freedom and vengeance.

The hair, teeth, and blood he takes from his clientele are saved in a secret room in the basement of the shop for later use in rituals and spells to gain dominion over the townspeople who oppose the return of the Crooked Queen. The pigeons, centipedes, and weasels of the Vermintoll Coven often linger about the shop, fetching the pieces of the townsfolk for their hag mistresses.

```statblock
"name": "Randall Graham (CrookedMoon24)"
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
  - "desc": "Randall casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 12, +4 to hit with spell attacks):\n\n**At will:**\
      \ Light, Thaumaturgy\n\n**2/day:** Command\n\n**1/day:** Hold Person"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Randall casts the Spiritual Weapon spell, using the same spellcasting\
      \ ability as Spellcasting.\n"
    "name": "Spiritual Weapon (2/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Randall%20Graham.webp"
```
^statblock