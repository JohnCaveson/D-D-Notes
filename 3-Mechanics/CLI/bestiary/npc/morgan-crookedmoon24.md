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
- Morgan
---
# [Morgan](3-Mechanics\CLI\bestiary\npc/morgan-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 199*  

Morgan does not remember their childhood. They awoke one night in Wickermoor Village as a youngster before being taken in by a goatherd and raised by his family. Morgan found their affinity for alchemy along the way, and they now act as the village's apothecary. They are friendly and kind, but they also suffer from blackouts and occasional lost time.

Morgan has a slight frame, with reddish-blonde hair that hangs over a thin face and green eyes that have a faraway look, even when they are Concentrating on a task.

> [!note] Morgan's Mystery
> 
> Morgan's mysterious past and periods of lost time are left for you to use as needed. Morgan could be a servant of one of the powers of the hollow, a reincarnation of a former powerful NPC or creature, a polymorphed monster who has forgotten their true form, or just a typical apothecary. Use Morgan as a wildcard as befits your story. If you use this advice, the alignment and statistics indicated in Morgan's description are for their apparent guise.
^morgans-mystery

```statblock
"name": "Morgan (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "12"
  - !!int "16"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+5"
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Common, Druidic, Sylvan"
"cr": "2"
"actions":
  - "desc": "Morgan makes two attacks, using Vine Staff or Verdant Wisp in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning damage\
      \ plus 2 (1d4) Poison damage."
    "name": "Vine Staff"
  - "desc": "*Ranged Attack Roll:* +5, range 90 ft. *Hit:* 10 (3d6) Radiant damage."
    "name": "Verdant Wisp"
  - "desc": "Morgan casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 13):\n\n**At will:** Druidcraft, Speak with Animals\n\
      \n**2/day each:** Entangle, Thunderwave\n\n**1/day each:** Animal Messenger,\
      \ Longstrider, Moonbeam"
    "name": "Spellcasting"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Morgan.webp"
```
^statblock