---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Weasel Hag
---
# [Weasel Hag](3-Mechanics\CLI\bestiary\fey/weasel-hag-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 537*  

---

*Hag of Soul Twisting and Terror*

---

Covetous and bedecked in stolen and gifted teeth, weasel hags are Fey creatures that sow nightmares and temptation to wickedness. They often surround themselves with weasels and boogleswarms, using them as spies, thieves to steal trinkets (especially lost teeth), and to spread their malign influence.

## Secret

Weasel hags' love of teeth goes beyond a mere quirk. They can't refuse a tooth willingly given by its owner and can't harm the owner for a time.

```statblock
"name": "Weasel Hag (CrookedMoon24)"
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
  - "desc": "While within 30 feet of at least two hag allies, the hag can cast one\
      \ of the following spells, requiring no Material components, using the spell's\
      \ normal casting time, and using Intelligence as the spellcasting ability: Augury,\
      \ Find Familiar, Identify, Locate Object, [Lucky Charm](/3-Mechanics/CLI/spells/lucky-charm-crookedmoon24.md)\
      \ (lasts until the hag casts it again, or chooses to end it with no action required),\
      \ or Unseen Servant. The hag must finish a <span title=\"Player's Handbook (2024)\"\
      >Long Rest</span> before using this trait to cast that spell again.\n"
    "name": "Coven Magic"
  - "desc": "If a creature willingly offers one of its teeth to the hag, the hag must\
      \ accept it and has the Charmed condition for 24 hours, or until the creature\
      \ or its allies deal damage to the hag or force it to make a saving throw."
    "name": "Biting Gift"
  - "desc": "The hag has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The hag makes one Bite attack and uses Spellcasting (at will spells only)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 8 (1d8 + 4) Piercing damage\
      \ plus 10 (3d6) Psychic damage."
    "name": "Bite"
  - "desc": "*Wisdom Saving Throw:* DC 13, one creature the hag can see within 30\
      \ feet. If the hag has one of the target's teeth, the target has Disadavantage\
      \ on the save. *Failure:* 21 (6d6) Psychic damage, and the target has the Frightened\
      \ condition.\n\nWhile Frightened in this way, the target perceives its allies\
      \ as enemies born from its nightmares, but it isn't compelled to act against\
      \ or harm them. At the end of each of its turns, the target repeats the save,\
      \ ending the effect on itself on a success. After 1 minute, it succeeds automatically.\
      \ *Success:* Half damage only."
    "name": "Waking Terrors (Recharge 5-6)"
  - "desc": "The hag casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 13):\n\n**At\
      \ will:** Blindness/Deafness, Detect Magic, Ray of Enfeeblement\n\n**1/day each:**\
      \ Confusion, Dream"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The hag shape-shifts to resemble a Tiny weasel (<span title=\"Player's\
      \ Handbook (2024)\">Speed</span> 30 ft., Climb 30 ft.) or a Small or Medium\
      \ Humanoid, or back into her true form. Her game statistics, other than her\
      \ <span title=\"Player's Handbook (2024)\">Speed</span> as a weasel and her\
      \ size, are the same in each form. Any equipment she is wearing or carrying\
      \ isn't transformed."
    "name": "Shape-Shift"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Weasel%20Hag.webp"
```
^statblock

## Environment

forest, planar (fey)