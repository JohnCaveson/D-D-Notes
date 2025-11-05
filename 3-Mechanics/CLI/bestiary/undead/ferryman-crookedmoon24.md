---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ferryman
---
# [Ferryman](3-Mechanics\CLI\bestiary\undead/ferryman-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 501*  

---

*Cursed Undead Boatman*

---

Ferrymen are Undead created through the use of curses and jinxcraft and are doomed to ply the waters where they were raised. They pole through the bayous and rivers, and even across land on a wave of swamp water, in coffin boats. They can focus the malice of their curse through the light of their lantern poles, jinxing enemies or those who try to force a ride without payment.

## Secret

Paying a ferryman 3 copper coins lifts any curse the creature placed on the payer, and it entitles one to a single unnerving but safe ride in the ferryman's coffin boat.

```statblock
"name": "Ferryman (CrookedMoon24)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "16"
  - !!int "8"
  - !!int "10"
  - !!int "14"
"speed": "30 ft., 40 ft. with Coffin Boat"
"saves":
  - "wisdom": !!int "3"
  - "charisma": !!int "5"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone) (with Coffin Boat)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Common plus one other language"
"cr": "6"
"traits":
  - "desc": "The ferryman rides an open coffin on a swell of swamp water, allowing\
      \ it to travel with a <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ of 40 feet over any surface, including liquids, ignoring <span title=\"Player's\
      \ Handbook (2024)\">Difficult Terrain</span>. The coffin can hold two other\
      \ Medium creatures. Two Small creatures or four Tiny creatures count as one\
      \ Medium creature.\n\nWhile riding the coffin, the ferryman has <span title=\"\
      Player's Handbook (2024)\">Immunity</span> to the Prone condition, and the coffin\
      \ moves with the ferryman unless the ferryman has the Incapacitated condition.\
      \ The coffin has AC 15; HP 25; <span title=\"Player's Handbook (2024)\">Immunity</span>\
      \ to Necrotic, Poison, and Psychic damage.\n\nIf the coffin is destroyed, the\
      \ ferryman can magically create a new one using a 10-minute ritual."
    "name": "Coffin Boat"
  - "desc": "The ferryman must peacefully offer a ride in its boat to a creature that\
      \ takes the Influence action to offer it 3 CP. If that creature is cursed by\
      \ the ferryman, the curse ends. If the boat is full, the ferryman must return\
      \ to offer the creature a ride once its current passengers leave the boat. If\
      \ the creature or its allies damage the ferryman or force it to make a saving\
      \ throw, this effect ends and the creature can't use that ferryman's Payment\
      \ trait again."
    "name": "Payment"
  - "desc": "The ferryman regains 10 <span title=\"Player's Handbook (2024)\">Hit\
      \ Points</span> at the start of each of its turns if it has at least 1 <span\
      \ title=\"Player's Handbook (2024)\">Hit Point</span>."
    "name": "Regeneration"
"actions":
  - "desc": "The ferryman makes two Lantern Pole attacks and uses Hexed Lantern if\
      \ available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 10 ft. *Hit:* 9 (1d10 + 4) Bludgeoning\
      \ damage plus 7 (2d6) Necrotic damage. If the target is a Medium or smaller\
      \ creature, it has the Prone condition."
    "name": "Lantern Pole"
  - "desc": "*Wisdom Saving Throw:* DC 13, each creature of the ferryman's choice\
      \ in a 30-foot <span title=\"Player's Handbook (2024)\">Cone</span>. *Failure:*\
      \ The creature is cursed for 1 minute and must subtract 1d4 from <span title=\"\
      Player's Handbook (2024)\">D20 Tests</span>."
    "name": "Hexed Lantern (1/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Ferryman.webp"
```
^statblock

## Environment

coastal, swamp