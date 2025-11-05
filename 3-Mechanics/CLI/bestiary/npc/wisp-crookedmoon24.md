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
- Wisp
---
# [Wisp](3-Mechanics\CLI\bestiary\npc/wisp-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 219*  

The estate's gray cat has earned [Walter's](/3-Mechanics/CLI/bestiary/npc/walter-jenkin-crookedmoon24.md) affection but terrifies [Dani](/3-Mechanics/CLI/bestiary/npc/dani-jenkin-crookedmoon24.md). The cat is no ordinary feline; it is a shapeshifted [Ketgrinn](/3-Mechanics/CLI/bestiary/fey/ketgrinn-crookedmoon24.md), a Fey in service to [Vessla Browntooth](/3-Mechanics/CLI/bestiary/npc/vessla-browntooth-crookedmoon24.md). Wisp stole Walter's voice and torments Dani by speaking to her when they are alone. [Shuck](/3-Mechanics/CLI/bestiary/npc/shuck-crookedmoon24.md) loathes Wisp, sensing his true nature, and stays close to protect Dani from the lurking evil. If the ketgrinn's true form is exposed and slain, Walter's ability to speak is restored.

```statblock
"name": "Wisp (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "17"
  - !!int "14"
  - !!int "16"
  - !!int "10"
  - !!int "18"
"speed": "40 ft., climb 40 ft."
"saves":
  - "dexterity": !!int "5"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Common, Sylvan; telepathy 100 ft."
"cr": "4"
"traits":
  - "desc": "Wisp has <span title=\"Player's Handbook (2024)\">Advantage</span> on\
      \ saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "Wisp can mimic any voice it has heard, or a voice it has stolen (see\
      \ Consume Voice below). A creature that hears the voice can tell it's an imitation\
      \ with a successful DC 14 Wisdom (Insight) check. The DC increases to 19 for\
      \ a voice Wisp has stolen."
    "name": "Mimicry"
  - "desc": "As an Influence action, a creature that poses a riddle to Wisp and succeeds\
      \ on a DC 16 Charisma (Deception) check gives Wisp the Incapacitated condition\
      \ until the start of the creature's next turn. Each riddle posed increases the\
      \ DC for future riddles by 1 for 24 hours."
    "name": "Riddle Bound"
"actions":
  - "desc": "Wisp makes two Claw attacks. It can replace one attack with a use of\
      \ Consume Voice."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 9 (2d4 + 4) Slashing damage\
      \ plus 7 (2d6) Psychic damage, and if the target is a creature, it has <span\
      \ title=\"Player's Handbook (2024)\">Disadvantage</span> on the next saving\
      \ throw Wisp forces it to make before the end of Wisp's next turn."
    "name": "Claw"
  - "desc": "*Charisma Saving Throw:* DC 14, one creature within 5 feet. *Failure:*\
      \ 18 (4d8) Psychic damage, and Wisp steals the target's voice. The target can't\
      \ speak or make any verbal sound while its voice is stolen.\n\nThe target repeats\
      \ the saving throw at the end of each of its turns, ending the effect on itself\
      \ on a success. If it fails three of these saving throws, the loss is permanent,\
      \ and its voice only returns when Wisp dies. *Success:* Half damage only."
    "name": "Consume Voice"
  - "desc": "Wisp casts Invisibility on itself, requiring no spell components and\
      \ using Charisma as the spellcasting ability.\n"
    "name": "Invisibility"
"bonus_actions":
  - "desc": "Wisp teleports up to 40 feet to an unoccupied space it can see."
    "name": "Teleport"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Wisp.webp"
```
^statblock