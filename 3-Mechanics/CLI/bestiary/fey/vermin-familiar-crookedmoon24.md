---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Vermin Familiar
---
# [Vermin Familiar](3-Mechanics\CLI\bestiary\fey/vermin-familiar-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 534*  

---

*Infesting Hag Companion*

---

Capricious Fey spirits incarnated into bodies reminiscent of normal pests, vermin familiars serve spellcasters and especially vermin hags. While they are most often drawn to serve wicked masters, they also delight in playing the part of dutiful servants to corrupt spellcasters who aren't evil.

## Secret

Vermin familiars are gripped by deep-seated fears shared by the vermin forms they inhabit, and as such, are terrified of dogs and other canines.

```statblock
"name": "Vermin Familiar (CrookedMoon24)"
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
"speed": "30 ft., burrow 30 ft. (Centipede or Weasel only), climb 30 ft., fly 60 ft.\
  \ (Pigeon only)"
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
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft. (Pigeon only),\
  \ [darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., tremorsense 30 ft.\
  \ (Centipede only), passive Perception 15"
"languages": "Common, Sylvan"
"cr": "2"
"traits":
  - "desc": "The familiar incarnates in a body similar to a pest: Centipede, Pigeon,\
      \ or Weasel, which determines other traits and actions the familiar has."
    "name": "Disparate Incarnation"
  - "desc": "If the familiar can see a dog, wolf, or other canine at the start of\
      \ its turn, it has the Frightened condition until the start of its next turn.\
      \ While Frightened in this way, it has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on saving throws."
    "name": "Fear of Canines"
  - "desc": "The familiar doesn't provoke an Opportunity Attack when it flies out\
      \ of an enemy's reach."
    "name": "Flyby (Pigeon Only)"
  - "desc": "The familiar can climb difficult surfaces, including along ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb (Centipede Only)"
  - "desc": "The familiar can magically control Beasts and swarms that match its incarnation\
      \ (centipedes, pigeons, weasels, giant versions of each, as well as [Boogleswarms](/3-Mechanics/CLI/bestiary/fey/boogleswarm-crookedmoon24.md),\
      \ [Skitterswarms](/3-Mechanics/CLI/bestiary/fey/skitterswarm-crookedmoon24.md),\
      \ and [Squabswarms](/3-Mechanics/CLI/bestiary/fey/squabswarm-crookedmoon24.md))\
      \ within 120 feet of itself, using a special telepathy."
    "name": "Vermin Telepathy"
"actions":
  - "desc": "The familiar makes two Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage\
      \ plus 3 (1d6) Psychic damage."
    "name": "Rend"
  - "desc": "The familiar uses the option that matches its incarnation."
    "name": "Incarnated Assault (Recharge 5-6)"
  - "desc": "*Charisma Saving Throw:* DC 12, one creature the familiar can see within\
      \ 5 feet. *Failure:* 21 (6d6) Necrotic damage, and the target is affected by\
      \ the Confusion spell until the start of the familiar's next turn. *Success:*\
      \ Half damage only."
    "name": "Confounding Scratch (Weasel Only)"
  - "desc": "*Constitution Saving Throw:* DC 12, one creature the familiar can see\
      \ within 5 feet. *Failure:* 10 (3d6) Poison damage, and the target has the Poisoned\
      \ condition until the end of the familiar's next turn. While Poisoned in this\
      \ way, the target has the Paralyzed condition. *Success:* Half damage only."
    "name": "Infectious Sting (Centipede Only)"
  - "desc": "*Wisdom Saving Throw:* DC 12, one creature the familiar can see within\
      \ 5 feet. *Failure:* 21 (6d6) Psychic damage, and the target has the Frightened\
      \ condition until the end of the familiar's next turn. The Frightened target\
      \ uses its movement on its turn to get as far away as possible from the familiar,\
      \ moving by the safest route. *Success:* Half damage only."
    "name": "Terrifying Flutter (Pigeon Only)"
  - "desc": "The familiar casts Invisibility on itself, requiring no spell components\
      \ and using Wisdom as the spellcasting ability.\n"
    "name": "Invisibility"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Vermin%20Familiar-Slippery%20Oswald.webp"
```
^statblock

## Environment

planar (fey), urban