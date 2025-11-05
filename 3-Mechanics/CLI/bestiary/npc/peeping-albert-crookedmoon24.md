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
- Peeping Albert
---
# [Peeping Albert](3-Mechanics\CLI\bestiary\npc/peeping-albert-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 206*  

[Peeping Albert](/3-Mechanics/CLI/bestiary/npc/peeping-albert-crookedmoon24.md) ([Vermin Familiar (Pigeon)](/3-Mechanics/CLI/bestiary/fey/vermin-familiar-pigeon-crookedmoon24.md)) is Golub's pigeon familiar, a pudgy bird that eerily resembles a person, with a wrinkled bald head, human-like ears, and hands instead of talons. He serves as Golub's most precious child and her chief spy. Albert gains a sick satisfaction from peeping on the townsfolk of Wickermoor Village and listening in on their conversations, eagerly awaiting the praise he'll receive when he reports back to his mother.

Sharing Golub's distaste for the weasel hag and centipede hag, Albert has a puffed-up superiority complex and looks down on his counterparts Filthy Jasper and Slippery Oswald. When the vile pigeon familiar is not spying on the villagers, he is always seeking new young women with lilac eyes so that Golub can prepare her next disguise.

[Peeping Albert](/3-Mechanics/CLI/bestiary/npc/peeping-albert-crookedmoon24.md) ([Vermin Familiar (Pigeon)](/3-Mechanics/CLI/bestiary/fey/vermin-familiar-pigeon-crookedmoon24.md)) is a grotesque pigeon with human-like ears and human hands for talons serving as the familiar of the hag Golub Graygullet. Albert acts as the hag's eyes and ears both in town and over the length and breadth of Wickermoor Hollow. The presence of the songbirds, which arrived shortly after Weston Murdoch and the rest of the Brightsinger worshipers, has made Peeping Albert particularly cross.

```statblock
"name": "Peeping Albert (CrookedMoon24)"
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
"speed": "30 ft., climb 30 ft., fly 60 ft."
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
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., [blindsight](/3-Mechanics/CLI/senses.md#Blindsight)\
  \ 30 ft., passive Perception 15"
"languages": "Common, Sylvan"
"cr": "2"
"traits":
  - "desc": "If Peeping Albert can see a dog, wolf, or other canine at the start of\
      \ its turn, it has the Frightened condition until the start of its next turn.\
      \ While Frightened in this way, it has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on saving throws."
    "name": "Fear of Canines"
  - "desc": "Peeping Albert doesn't provoke an Opportunity Attack when it flies out\
      \ of an enemy's reach."
    "name": "Flyby"
  - "desc": "Peeping Albert can magically control Beasts and swarms that match its\
      \ incarnation (centipedes, pigeons, weasels, giant versions of each, as well\
      \ as [Boogleswarms](/3-Mechanics/CLI/bestiary/fey/boogleswarm-crookedmoon24.md),\
      \ [Skitterswarms](/3-Mechanics/CLI/bestiary/fey/skitterswarm-crookedmoon24.md),\
      \ and [Squabswarms](/3-Mechanics/CLI/bestiary/fey/squabswarm-crookedmoon24.md))\
      \ within 120 feet of itself, using a special telepathy."
    "name": "Vermin Telepathy"
"actions":
  - "desc": "Peeping Albert makes two Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage\
      \ plus 3 (1d6) Psychic damage."
    "name": "Rend"
  - "desc": "Peeping Albert uses the option that matches its incarnation."
    "name": "Incarnated Assault (Recharge 5-6)"
  - "desc": "*Wisdom Saving Throw:* DC 12, one creature Peeping Albert can see within\
      \ 5 feet. *Failure:* 21 (6d6) Psychic damage, and the target has the Frightened\
      \ condition until the end of Peeping Albert's next turn. The Frightened target\
      \ uses its movement on its turn to get as far away as possible from Peeping\
      \ Albert, moving by the safest route. *Success:* Half damage only."
    "name": "Terrifying Flutter"
  - "desc": "Peeping Albert casts Invisibility on itself, requiring no spell components\
      \ and using Wisdom as the spellcasting ability.\n"
    "name": "Invisibility"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Vermin%20Familiar-Peeping%20Albert.webp"
```
^statblock