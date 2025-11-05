---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- Dingpot
---
# [Dingpot](3-Mechanics\CLI\bestiary\construct/dingpot-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 584*  

---

*Jovial Cauldron Helper (Spices and rose quartz)*

---

Dingpots are animated objects created to assist in magical and alchemical research—or simply to help in the kitchen. Often cheerful, dingpots delight in serving up delicious meals, soothing tea, and the occasional magical draught.

```statblock
"name": "Dingpot (CrookedMoon24)"
"size": "Tiny"
"type": "construct"
"alignment": "Neutral Good"
"ac": !!int "15"
"hp": !!int "22"
"hit_dice": "4d4 + 12"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "12"
"speed": "10 ft., fly 20 ft. (hover)"
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft., passive Perception\
  \ 13"
"languages": "Common plus one other language"
"cr": "1"
"traits":
  - "desc": "While the dingpot doesn't have the Incapacitated condition, it can provide\
      \ enough heat to boil water within its vessel."
    "name": "Boil and Bubble"
"actions":
  - "desc": "*Ranged Attack Roll:* +4, range 60 ft. *Hit:* 7 (2d4 + 2) Fire damage,\
      \ and the target has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on the next attack roll it makes before the start of the dingpot's next turn.\
      \ Being underwater doesn't grant <span title=\"Player's Handbook (2024)\">Resistance</span>\
      \ to this Fire damage."
    "name": "Steam Spray"
  - "desc": "The dingpot produces a magical elixir within its vessel. The elixir remains\
      \ potent for 24 hours. It can choose from the following brews:"
    "name": "Brew (1/Day)"
  - "desc": "As a <span title=\"Player's Handbook (2024)\">Bonus Action</span>, a\
      \ creature can drink the elixir to regain 4 (1d6 + 1) <span title=\"Player's\
      \ Handbook (2024)\">Hit Points</span>."
    "name": "Healing Draught"
  - "desc": "As a <span title=\"Player's Handbook (2024)\">Bonus Action</span>, a\
      \ creature can drink the elixir to gain startling luck for 10 minutes. When\
      \ the creature fails an ability check or a saving throw, it can reroll the d20\
      \ and use the new roll. Once this causes a roll to succeed, the effects of the\
      \ elixir end early."
    "name": "Lucky Draught"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Dingpot.webp"
```
^statblock

## Environment

any