---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Vessla Browntooth
---
# [Vessla Browntooth](3-Mechanics\CLI\bestiary\npc/vessla-browntooth-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 216*  

Vessla Browntooth is the youngest of the three hags that form the Vermintoll Coven (see chapter 8). As with her sisters, she is a crooked Fey from the primeval times of Kehlenn's reign, becoming more crooked with every passing year. She delights in the vermin that earned the coven its names, particularly favoring the weasels that scurry and scrape throughout walls of the Crooked House.

Vessla is the shortest and meanest of the trio, with a nose that is as long and pointed as her teeth and many other unsavory features that evoke the weasels she cherishes and commands.

Her witchcraft specializes in the corruption and siphoning of mortal souls, which manifests through horrific nightmares and phantasmal visions. This power is enhanced by the hoard of humanoid teeth, collected by her loyal weasels and her beloved familiar, [Filthy Jasper](/3-Mechanics/CLI/bestiary/npc/filthy-jasper-crookedmoon24.md).

Recently, she captured [Phillip](/3-Mechanics/CLI/bestiary/npc/phillip-druskenvald-crookedmoon24.md) and [Adela Druskenvald](/3-Mechanics/CLI/bestiary/npc/adela-druskenvald-crookedmoon24.md) after they settled into the manor home, and she began performing an elaborate ritual to prepare their souls for sacrifice. What she doesn't know is that the sacrificial lamb is Vessla herself, as planned by her sisters, [Golub](/3-Mechanics/CLI/bestiary/npc/golub-graygullet-crookedmoon24.md) and [Stonoga](/3-Mechanics/CLI/bestiary/npc/stonoga-blackstinger-crookedmoon24.md), as part of the long-term machinations of the Crooked Queen.

```statblock
"name": "Vessla Browntooth (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "5"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "psychic"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 14"
"languages": "Common, Infernal, Sylvan"
"cr": "4"
"traits":
  - "desc": "While within 30 feet of at least two hag allies, Vessla can cast one\
      \ of the following spells, requiring no Material components, using the spell's\
      \ normal casting time, and using Intelligence as the spellcasting ability: Augury,\
      \ Find Familiar, Identify, Locate Object, [Lucky Charm](/3-Mechanics/CLI/spells/lucky-charm-crookedmoon24.md)\
      \ (lasts until Vessla casts it again, or chooses to end it with no action required),\
      \ or Unseen Servant. Vessla must finish a <span title=\"Player's Handbook (2024)\"\
      >Long Rest</span> before using this trait to cast that spell again.\n"
    "name": "Coven Magic"
  - "desc": "If a creature willingly offers one of its teeth to Vessla, Vessla must\
      \ accept it and has the Charmed condition for 24 hours, or until the creature\
      \ or its allies deal damage to Vessla or force it to make a saving throw."
    "name": "Biting Gift"
  - "desc": "Vessla has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Vessla makes one Bite attack and uses Spellcasting (at will spells only)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 8 (1d8 + 4) Piercing damage\
      \ plus 10 (3d6) Psychic damage."
    "name": "Bite"
  - "desc": "*Wisdom Saving Throw:* DC 13, one creature Vessla can see within 30 feet.\
      \ If Vessla has one of the target's teeth, the target has Disadavantage on the\
      \ save. *Failure:* 21 (6d6) Psychic damage, and the target has the Frightened\
      \ condition.\n\nWhile Frightened in this way, the target perceives its allies\
      \ as enemies born from its nightmares, but it isn't compelled to act against\
      \ or harm them. At the end of each of its turns, the target repeats the save,\
      \ ending the effect on itself on a success. After 1 minute, it succeeds automatically.\
      \ *Success:* Half damage only."
    "name": "Waking Terrors (Recharge 5-6)"
  - "desc": "Vessla casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 13):\n\n**At\
      \ will:** Blindness/Deafness, Detect Magic, Ray of Enfeeblement\n\n**1/day each:**\
      \ Confusion, Dream"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Vessla shape-shifts to resemble a Tiny weasel (<span title=\"Player's\
      \ Handbook (2024)\">Speed</span> 30 ft., Climb 30 ft.) or a Small or Medium\
      \ Humanoid, or back into her true form. Her game statistics, other than her\
      \ <span title=\"Player's Handbook (2024)\">Speed</span> as a weasel and her\
      \ size, are the same in each form. Any equipment she is wearing or carrying\
      \ isn't transformed."
    "name": "Shape-Shift"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Vessla%20Browntooth.webp"
```
^statblock