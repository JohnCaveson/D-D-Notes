---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Pumpkin Head
---
# [Pumpkin Head](3-Mechanics\CLI\bestiary\fiend/pumpkin-head-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 523*  

---

*Fiendish Effigy of the Fields*

---

Pumpkin heads are scarecrows  of straw, sticks, and clothing topped with a carved pumpkin for  a head and animated by a fiendish spirit. They are crafted by demons  to resemble their Humanoid victims and returned to wherever  the unfortunate souls had been snatched from.

These living effigies speak  with the voice of whomever  they replaced, often repeating phrases and behaviors that the missing person said or did in life while stalking and killing new prey.

## Secret

Pumpkin heads hold a shred of memory from the people they replaced. The sight of a keepsake or memento from a pumpkin head's victim confuses the creature.

```statblock
"name": "Pumpkin Head (CrookedMoon24)"
"size": "Medium"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "14"
  - !!int "13"
  - !!int "6"
  - !!int "10"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_vulnerabilities": "fire"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "understands Common plus one other language but only speaks using Mimicry"
"cr": "3"
"traits":
  - "desc": "The pumpkin head can mimic the voice of the person it replaced or someone\
      \ it used Personality Consumption on. A creature that hears the voice can tell\
      \ it's an imitation only with a successful DC 14 Wisdom (Insight) check."
    "name": "Mimicry"
  - "desc": "If the pumpkin head can see a creature holding a possession of the person\
      \ the pumpkin head replaced, it has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on <span title=\"Player's Handbook (2024)\">D20 Tests</span>."
    "name": "Sorrowful Memento"
"actions":
  - "desc": "The pumpkin head makes one Claw attack and one Pitchfork attack, and\
      \ it can use Personality Consumption if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing damage\
      \ plus 7 (2d6) Necrotic damage."
    "name": "Claw"
  - "desc": "*Melee Attack Roll:* +5, reach 10 ft. *Hit:* 7 (1d8 + 3) Piercing damage,\
      \ and if the target is a Medium or smaller creature, the pumpkin head can push\
      \ or pull it 5 feet."
    "name": "Pitchfork"
  - "desc": "The pumpkin head consumes a victim's memories. *Intelligence Saving Throw:*\
      \ DC 12, one creature the pumpkin head can see within 30 feet. *Failure:* The\
      \ target has the Stunned condition until the end of its next turn, and its Intelligence\
      \ score decreases by 1d4. The target dies if this reduces that score to 0. A\
      \ Humanoid slain in this way is replaced by a [Pumpkin Head](/3-Mechanics/CLI/bestiary/fiend/pumpkin-head-crookedmoon24.md)\
      \ 1d8 hours later unless its body is burned."
    "name": "Personality Consumption (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Pumpkin%20Head.webp"
```
^statblock

## Environment

any