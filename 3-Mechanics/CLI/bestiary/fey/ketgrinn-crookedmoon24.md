---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ketgrinn
---
# [Ketgrinn](3-Mechanics\CLI\bestiary\fey/ketgrinn-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 513*  

---

*Voice-Stealing Trickster*

---

Ketgrinn are catlike Fey spirits who delight in puzzles, riddles, and bargains. They have large, bright eyes and too-wide grins that gleam starkly even in shadows. Ketgrinn are tricksters and spies, often sent by those they serve to steal the voices of a rival's minions to sow chaos and confusion.

## Secret

Ketgrinn can't resist a puzzle or riddle, and a difficult one can send a ketgrinn's mind spiraling.

```statblock
"name": "Ketgrinn (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Neutral"
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
  - "desc": "The ketgrinn has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The ketgrinn can mimic any voice it has heard, or a voice it has stolen\
      \ (see Consume Voice below). A creature that hears the voice can tell it's an\
      \ imitation with a successful DC 14 Wisdom (Insight) check. The DC increases\
      \ to 19 for a voice the ketgrinn has stolen."
    "name": "Mimicry"
  - "desc": "As an Influence action, a creature that poses a riddle to the ketgrinn\
      \ and succeeds on a DC 16 Charisma (Deception) check gives the ketgrinn the\
      \ Incapacitated condition until the start of the creature's next turn. Each\
      \ riddle posed increases the DC for future riddles by 1 for 24 hours."
    "name": "Riddle Bound"
"actions":
  - "desc": "The ketgrinn makes two Claw attacks. It can replace one attack with a\
      \ use of Consume Voice."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 9 (2d4 + 4) Slashing damage\
      \ plus 7 (2d6) Psychic damage, and if the target is a creature, it has <span\
      \ title=\"Player's Handbook (2024)\">Disadvantage</span> on the next saving\
      \ throw the ketgrinn forces it to make before the end of the ketgrinn's next\
      \ turn."
    "name": "Claw"
  - "desc": "*Charisma Saving Throw:* DC 14, one creature within 5 feet. *Failure:*\
      \ 18 (4d8) Psychic damage, and the ketgrinn steals the target's voice. The target\
      \ can't speak or make any verbal sound while its voice is stolen.\n\nThe target\
      \ repeats the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success. If it fails three of these saving throws, the loss\
      \ is permanent, and its voice only returns when the ketgrinn dies. *Success:*\
      \ Half damage only."
    "name": "Consume Voice"
  - "desc": "The ketgrinn casts Invisibility on itself, requiring no spell components\
      \ and using Charisma as the spellcasting ability.\n"
    "name": "Invisibility"
"bonus_actions":
  - "desc": "The ketgrinn teleports up to 40 feet to an unoccupied space it can see."
    "name": "Teleport"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Ketgrinn.webp"
```
^statblock

## Environment

forest, hill, planar (fey)