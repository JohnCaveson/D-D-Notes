---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lake Dredger
---
# [Lake Dredger](3-Mechanics\CLI\bestiary\undead/lake-dredger-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 514*  

---

*Undead Aquatic Monster*

---

Lake dredgers are Undead water behemoths, such as whales, giant fish, or dinosaurs. These creatures are reanimated through the deep, primal fear of the unknown horrors that lurk in the murky depths. They dwell in the beds of lakes, rivers, or oceans, dredging up the detritus to replenish their ever-rotting mass.

They also add to their decaying bulk by feeding on living creatures, especially drawn to those who exhibit fear of the deep. Once prey is devoured, it is impaled on its cracked ribs until the waterlogged flesh becomes one with the beast's.

## Secret

Lake dredgers exist because of the fear of the unknown, and their essence is undone in the presence of a captured or crafted depiction of themselves, such as a drawing or carving.

```statblock
"name": "Lake Dredger (CrookedMoon24)"
"size": "Huge"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "157"
"hit_dice": "15d12 + 60"
"modifier": !!int "0"
"stats":
  - !!int "22"
  - !!int "10"
  - !!int "18"
  - !!int "4"
  - !!int "12"
  - !!int "4"
"speed": "20 ft., swim 50 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_resistances": "necrotic, psychic"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 11"
"languages": ""
"cr": "9"
"traits":
  - "desc": "The lake dredger takes 20 Force damage at the start of its turn if it\
      \ can see a creature holding a created depiction (such as a drawing, painting,\
      \ or carving) of the lake dredger."
    "name": "Depicted Demise"
  - "desc": "The lake dredger has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on Dexterity (Stealth) checks made when in an area with aquatic plants or\
      \ seaweed."
    "name": "Silt Stealth"
"actions":
  - "desc": "The lake dredger makes one Bite attack and one Tail attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 10 ft. *Hit:* 15 (2d8 + 6) Piercing damage\
      \ plus 4 (1d8) Necrotic damage. If the target is a Large or smaller creature,\
      \ it has the Grappled condition (escape DC 16), and it has the Restrained condition\
      \ until the grapple ends."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +10, reach 15 ft. *Hit:* 24 (4d8 + 6) Bludgeoning\
      \ damage. If the target is a Huge or smaller creature, it has the Prone condition."
    "name": "Tail"
"bonus_actions":
  - "desc": "*Dexterity Saving Throw:* DC 18, one Large or smaller creature Grappled\
      \ by the lake dredger (the lake dredger can only have one creature swallowed\
      \ at a time). *Failure:* The lake dredger swallows the target, which is no longer\
      \ Grappled. While swallowed, the creature has the Restrained condition, has\
      \ <span title=\"Player's Handbook (2024)\">Three-Quarters Cover</span> against\
      \ attacks and other effects outside the lake dredger, and takes 21 (6d6) Necrotic\
      \ damage at the start of each of the lake dredger's turns.\n\nAs an action,\
      \ the swallowed creature can escape through the lake dredger's ribcage. The\
      \ creature takes 11 (2d10) Piercing damage and emerges in a space within 5 feet\
      \ of the lake dredger. If the lake dredger dies, a swallowed creature is no\
      \ longer Restrained and can escape from the corpse by using 15 feet of movement,\
      \ exiting Prone."
    "name": "Swallow"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Lake%20Dredger.webp"
```
^statblock

## Environment

coastal, swamp, underwater