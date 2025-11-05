---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- House of Horror
---
# [House of Horror](3-Mechanics\CLI\bestiary\construct/house-of-horror-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 508*  

---

*Cursed House Brought to Malevolent Life*

---

Houses of horror are living houses, often angry or bitter due to the circumstances of their awakening. They were once mundane buildings or dwellings where powerful magics of life and death took place and infused the stones and timber.

Houses of horror jealously covet the true life that its former inhabitants enjoyed, or they carry echoes of the suffering that bodies and souls experienced within them. The houses vent this fury on any who enter, tormenting and terrifying trespassers. The souls of those who die inside are trapped, waiting to be unleashed upon future victims.

## Secret

While not haunted houses in the traditional sense, houses of horror can have their consciousness quelled by the same exorcism or purification rituals that put unquiet spirits to rest or drive out possessing spirits.

```statblock
"name": "House of Horror (CrookedMoon24)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "217"
"hit_dice": "14d20 + 70"
"modifier": !!int "5"
"stats":
  - !!int "22"
  - !!int "10"
  - !!int "20"
  - !!int "5"
  - !!int "16"
  - !!int "7"
"speed": "10 ft."
"saves":
  - "charisma": !!int "3"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+11"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 13"
"languages": "understands Common plus one other language but can't speak"
"cr": "13"
"traits":
  - "desc": "Creatures can enter the house's space and navigate it as a normal building.\
      \ The house makes attacks from any surface or object that isn't being worn or\
      \ carried within its space. It doesn't have <span title=\"Player's Handbook\
      \ (2024)\">Disadvantage</span> on ranged attack rolls due to an enemy being\
      \ within 5 feet of it.\n\nIf a creature deals 30 or more damage in a single\
      \ turn to a 5-foot section of the house's structure, the house must succeed\
      \ on a DC 18 Constitution saving throw or a 5-foot opening appears in that space\
      \ until the start of the creature's next turn."
    "name": "Construction"
  - "desc": "If the house is targeted by a Dispel Evil and Good spell, it has the\
      \ Stunned condition. At the end of each of its turns, it can make a DC 15 Charisma\
      \ saving throw, ending the condition on itself on a success. After 1 minute,\
      \ it succeeds automatically. As a Magic action, a creature inside the house\
      \ that throws a flask of Holy Water against the house and succeeds on a DC 20\
      \ Charisma check affects the house as above."
    "name": "Exorcism Susceptibility"
  - "desc": "A Humanoid that dies within the house has its soul trapped there until\
      \ the house dies. The creature can't be returned to life by any means short\
      \ of a True Resurrection or Wish spell."
    "name": "Soul Trap"
"actions":
  - "desc": "The house makes three attacks, using Structure Slam or <span title=\"\
      Player's Handbook (2024)\">Object</span> Fling in any combination, and it uses\
      \ Agonized Souls."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +11, reach 5 ft. *Hit:* 15 (2d8 + 6) Bludgeoning\
      \ damage plus 9 (2d8) Force damage. If the target is a Large or smaller creature,\
      \ it has the Grappled condition (escape DC 16). The house can grapple up to\
      \ two creatures at a time, using animated furniture, objects, or fixtures such\
      \ as stair railings."
    "name": "Structure Slam"
  - "desc": "*Ranged Attack Roll:* +11, range 20/60 ft. *Hit:* 11 (2d4 + 6) Bludgeoning\
      \ or Piercing damage (house's choice). If the target is a Large or smaller creature,\
      \ it has the Prone condition."
    "name": "Object Fling"
  - "desc": "The house's stolen souls torment a victim. *Wisdom Saving Throw:* DC\
      \ 16, a creature within 10 feet of the house. *Failure:* 36 (8d8) Necrotic damage.\
      \ *Success:* Half damage."
    "name": "Agonized Souls"
"bonus_actions":
  - "desc": "The house can reshape itself to change the location of walls, doors,\
      \ floors, and other features of its construction. When one of these features\
      \ appears or disappears, a creature within 5 feet of a changing feature can\
      \ make a DC 18 Dexterity saving throw. On a successful save, the creature chooses\
      \ which side of a feature it ends up on, or it moves to the nearest unoccupied\
      \ space to avoid falling."
    "name": "Alter Structure"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/House%20of%20Horror.webp"
```
^statblock

## Environment

any