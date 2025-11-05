---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Crooked Man
---
# [Crooked Man](3-Mechanics\CLI\bestiary\undead/crooked-man-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 496*  

---

*Broken Spirit of Betrayal*

---

The crooked man is an Undead embodiment of broken trust and the twisting of purpose. Those who die having betrayed what they hold sacred, embracing their treachery to their core, might return in this broken, gnarled form of snapped bones with a crooked grin. The creature's fingers end in curling claws that hook and hold, and the duplicity in its heart bleeds out to twist allies against one another. Despite the creature's name, anyone can become this manifestation of betrayal.

## Secret

The crooked man can't abide self-sacrifice and withers in its presence.

```statblock
"name": "Crooked Man (CrookedMoon24)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "221"
"hit_dice": "26d8 + 104"
"modifier": !!int "9"
"stats":
  - !!int "22"
  - !!int "18"
  - !!int "19"
  - !!int "13"
  - !!int "14"
  - !!int "19"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 17"
"languages": "Common plus one other language"
"cr": "14"
"traits":
  - "desc": "The crooked man takes 20 Necrotic damage if he can see a creature willingly\
      \ take damage or gain a condition in place of someone else, or to someone else's\
      \ benefit."
    "name": "Aversion to Self-Sacrifice"
  - "desc": "The crooked man has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The crooked man makes two Crooked Claw attacks, and he can replace one\
      \ attack with a use of Snap Limb. He can also use Confusion if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +11, reach 5 ft. *Hit:* 15 (2d8 + 6) Slashing damage\
      \ plus 21 (6d6) Psychic damage. If the target is a Medium or smaller creature,\
      \ it has the Grappled condition (escape DC 16) from one of two claws. Until\
      \ the grapple ends, the target has the Restrained condition."
    "name": "Crooked Claw"
  - "desc": "*Constitution Saving Throw:* DC 19, one creature the crooked man is grappling,\
      \ and that has limbs that can break. *Failure:* 35 (10d6) Force damage, and\
      \ the bones (or equivalent) in one of the target's limbs (crooked man's choice)\
      \ breaks, causing an appropriate effect below. A broken limb heals in 40 days,\
      \ or when the creature regains any <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span> from magic or Regeneration. *Success:* Half damage only."
    "name": "Snap Limb"
  - "desc": "<span title=\"Player's Handbook (2024)\">Disadvantage</span> on attack\
      \ rolls. Can't hold anything or manipulate objects with the limb."
    "name": "Broken Arm"
  - "desc": "<span title=\"Player's Handbook (2024)\">Speed</span> halved. If the\
      \ creature takes the Dash action, it must succeed on a DC 15 Dexterity saving\
      \ throw or have the Prone condition."
    "name": "Broken Leg"
  - "desc": "<span title=\"Player's Handbook (2024)\">Fly Speed</span> reduced to\
      \ 0."
    "name": "Broken Wing"
  - "desc": "The crooked man casts Confusion, requiring no Material components and\
      \ using Charisma as the spellcasting ability (spell save DC 17).\n"
    "name": "Confusion (1/Day)"
"bonus_actions":
  - "desc": "The crooked man has the Invisible condition for 1 minute and teleports\
      \ to an unoccupied space he can see within 60 feet. The condition ends immediately\
      \ after the crooked man deals any damage."
    "name": "Blinking Teleport"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Crooked%20Man.webp"
```
^statblock

## Environment

any