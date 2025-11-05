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
- Slippery Oswald
---
# [Slippery Oswald](3-Mechanics\CLI\bestiary\npc/slippery-oswald-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 306*  

[Slippery Oswald](/3-Mechanics/CLI/bestiary/npc/slippery-oswald-crookedmoon24.md) ([Vermin Familiar (Centipede)](/3-Mechanics/CLI/bestiary/fey/vermin-familiar-centipede-crookedmoon24.md)) is a rough approximation of a centipede the size of a hound, with grotesquely human-like hands at the end of each appendage and an unsettling human grin. The familiar of Stonoga Blackstinger, he shares his mistress's glee in the horrid reshaping of flesh into new forms. He can command the squirming hordes of centipedes that crawl throughout Wickermoor Hollow.

Rather than being a collector of body parts like his weasel counterpart Filthy Jasper, Oswald prefers to create grotesque homes out of his master's victims. He burrows deep into Humanoid carcasses and rearranges the rotting innards to his liking, often lurking within for weeks at a time. Sometimes, he even digs into a healthy person to corrupt and prime their body for flesh shaping while they still live.

```statblock
"name": "Slippery Oswald (CrookedMoon24)"
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
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., tremorsense\
  \ 30 ft., passive Perception 15"
"languages": "Common, Sylvan"
"cr": "2"
"traits":
  - "desc": "If Slippery Oswald can see a dog, wolf, or other canine at the start\
      \ of its turn, it has the Frightened condition until the start of its next turn.\
      \ While Frightened in this way, it has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on saving throws."
    "name": "Fear of Canines"
  - "desc": "Slippery Oswald can climb difficult surfaces, including along ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "Slippery Oswald can magically control Beasts and swarms that match its\
      \ incarnation (centipedes, pigeons, weasels, giant versions of each, as well\
      \ as [Boogleswarms](/3-Mechanics/CLI/bestiary/fey/boogleswarm-crookedmoon24.md),\
      \ [Skitterswarms](/3-Mechanics/CLI/bestiary/fey/skitterswarm-crookedmoon24.md),\
      \ and [Squabswarms](/3-Mechanics/CLI/bestiary/fey/squabswarm-crookedmoon24.md))\
      \ within 120 feet of itself, using a special telepathy."
    "name": "Vermin Telepathy"
"actions":
  - "desc": "Slippery Oswald makes two Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage\
      \ plus 3 (1d6) Psychic damage."
    "name": "Rend"
  - "desc": "Slippery Oswald uses the option that matches its incarnation."
    "name": "Incarnated Assault (Recharge 5-6)"
  - "desc": "*Constitution Saving Throw:* DC 12, one creature Slippery Oswald can\
      \ see within 5 feet. *Failure:* 10 (3d6) Poison damage, and the target has the\
      \ Poisoned condition until the end of Slippery Oswald's next turn. While Poisoned\
      \ in this way, the target has the Paralyzed condition. *Success:* Half damage\
      \ only."
    "name": "Infectious Sting"
  - "desc": "Slippery Oswald casts Invisibility on itself, requiring no spell components\
      \ and using Wisdom as the spellcasting ability.\n"
    "name": "Invisibility"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Vermin%20Familiar-Slippery%20Oswald.webp"
```
^statblock