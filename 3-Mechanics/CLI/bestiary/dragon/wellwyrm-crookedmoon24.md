---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wellwyrm
---
# [Wellwyrm](3-Mechanics\CLI\bestiary\dragon/wellwyrm-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 538*  

---

*Serpent Lurking Beneath the Surface*

---

Wellwyrms are serpents originally touched by cruel Fey masters. The wyrms live in shallow waters where land-dwelling creatures frequent, such as wells and watering holes, lying in wait to coil around unsuspecting victims. Wellwyrms then drag their prey into water, or into burrows they dig under seemingly safe ground, to drown or suffocate.

## Secret

The sound of a hunting horn drives wellwyrms into a panicked frenzy.

```statblock
"name": "Wellwyrm (CrookedMoon24)"
"size": "Large"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "153"
"hit_dice": "18d10 + 54"
"modifier": !!int "3"
"stats":
  - !!int "19"
  - !!int "16"
  - !!int "17"
  - !!int "5"
  - !!int "14"
  - !!int "9"
"speed": "40 ft., burrow 40 ft., swim 60 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "bludgeoning, piercing"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 10 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 60 ft., passive Perception 16"
"languages": "understands Sylvan but can't speak"
"cr": "9"
"traits":
  - "desc": "The wellwyrm can breathe air and water."
    "name": "Amphibious"
  - "desc": "If the wellwyrm hears a creature play a horn or similar Musical Instrument,\
      \ it has the Frightened condition until the end of its next turn."
    "name": "Hunting Terror"
"actions":
  - "desc": "The wellwyrm makes one Bite attack and uses Constrict."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 10 ft. *Hit:* 15 (2d10 + 4) Piercing damage\
      \ plus 21 (6d6) Poison damage."
    "name": "Bite"
  - "desc": "*Strength Saving Throw:* DC 16, one Medium or smaller creature the wellwyrm\
      \ can see within 5 feet. *Failure:* 13 (2d8 + 4) Bludgeoning damage. The target\
      \ has the Grappled condition (escape DC 14), and it has the Restrained condition\
      \ until the grapple ends. The wellwyrm needn't spend extra movement to move\
      \ during this grapple."
    "name": "Constrict"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Wellwyrm.webp"
```
^statblock

## Environment

coastal, underground, swamp