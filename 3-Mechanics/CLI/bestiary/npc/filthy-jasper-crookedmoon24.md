---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Filthy Jasper
---
# [Filthy Jasper](3-Mechanics\CLI\bestiary\npc/filthy-jasper-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 216*  

Filthy Jasper is an abominable Monstrosity, weasel-like but disturbingly human in his features, with unsettling hands that mimic those of a man. Formed from [Vessla Browntooth's](/3-Mechanics/CLI/bestiary/npc/vessla-browntooth-crookedmoon24.md) nightmarish magic, Filthy Jasper obeys her every whim and leads the swarming weasels through the Crooked House and Wickermoor Village.

As wicked as his creator, Filthy Jasper revels in human suffering, particularly that of children. An eager collector of humanoid teeth for Vessla's rituals, he savors the act of tearing them from skulls with his own hands.

```statblock
"name": "Filthy Jasper (CrookedMoon24)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "31"
"hit_dice": "7d4 + 14"
"modifier": !!int "4"
"stats":
  - !!int "6"
  - !!int "19"
  - !!int "14"
  - !!int "6"
  - !!int "16"
  - !!int "15"
"speed": "30 ft., burrow 30 ft., climb 30 ft."
"saves":
  - "strength": !!int "0"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": "Common, Sylvan"
"cr": "2"
"traits":
  - "desc": "If Filthy Jasper can see a dog, wolf, or other canine at the start of\
      \ its turn, it has the Frightened condition until the start of its next turn.\
      \ While Frightened in this way, it has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on saving throws."
    "name": "Fear of Canines"
  - "desc": "Filthy Jasper can magically control Beasts and swarms that match its\
      \ incarnation (centipedes, pigeons, weasels, giant versions of each, as well\
      \ as [Boogleswarms](/3-Mechanics/CLI/bestiary/fey/boogleswarm-crookedmoon24.md),\
      \ [Skitterswarms](/3-Mechanics/CLI/bestiary/fey/skitterswarm-crookedmoon24.md),\
      \ and [Squabswarms](/3-Mechanics/CLI/bestiary/fey/squabswarm-crookedmoon24.md))\
      \ within 120 feet of itself, using a special telepathy."
    "name": "Vermin Telepathy"
"actions":
  - "desc": "Filthy Jasper makes two Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage\
      \ plus 3 (1d6) Psychic damage."
    "name": "Rend"
  - "desc": "Filthy Jasper uses the option that matches its incarnation."
    "name": "Incarnated Assault (Recharge 5-6)"
  - "desc": "*Charisma Saving Throw:* DC 12, one creature Filthy Jasper can see within\
      \ 5 feet. *Failure:* 21 (6d6) Necrotic damage, and the target is affected by\
      \ the Confusion spell until the start of Filthy Jasper's next turn. *Success:*\
      \ Half damage only."
    "name": "Confounding Scratch"
  - "desc": "Filthy Jasper casts Invisibility on itself, requiring no spell components\
      \ and using Wisdom as the spellcasting ability.\n"
    "name": "Invisibility"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Vermin%20Familiar-Filthy%20Jasper.webp"
```
^statblock