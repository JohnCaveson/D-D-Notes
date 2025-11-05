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
- Sister Rain
---
# [Sister Rain](3-Mechanics\CLI\bestiary\npc/sister-rain-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 208*  

Sister Rain travels throughout the hollow espousing the bountiful blessings of the Patient Lady. She has no official residence in the village and instead lives in the natural environments outside of town.

She also sometimes stays with her congregants and preaches in the Founder's Round (area V9). Sister Rain's moods and demeanor are as fickle as the weather and nature that she reveres, often living a nomadic lifestyle travelling between the various communes dedicated to the Patient Lady that dot Wickermoor Hollow.

Sister Rain is a slight woman in her mid-thirties. She wears a green floral print dress that sets off her long, flowing, flaming-red hair. Her green eyes are bright with the fervor of her faith, and her features can flash between joy and anger in a moment. She wears a plain silver necklace with a pendant in the shape of a blossoming sunflower.

Sister Rain is the leader of the Fold of the Patient Lady, and she espouses the need to accept and protect the bounties of nature. Her presence is anathema to the most zealous and evil followers of the Crooked Queen.

```statblock
"name": "Sister Rain (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric"
"alignment": "Neutral Good"
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
  - "desc": "Sister Rain makes two attacks, using Mace or Radiant Flame in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Bludgeoning damage\
      \ plus 5 (2d4) Radiant damage."
    "name": "Mace"
  - "desc": "*Ranged Attack Roll:* +5, range 60 ft. *Hit:* 11 (2d10) Radiant damage."
    "name": "Radiant Flame"
  - "desc": "Sister Rain casts one of the following spells, using Wisdom as the spellcasting\
      \ ability:\n\n**At will:** Light, Thaumaturgy\n\n**1/day:** Spirit Guardians"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Sister Rain casts Bless, Dispel Magic, Healing Word, or Lesser Restoration,\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Divine Aid (3/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Sister%20Rain.webp"
```
^statblock