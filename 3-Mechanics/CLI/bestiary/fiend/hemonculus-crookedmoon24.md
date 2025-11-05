---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/planar-lower-planes
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hemonculus
---
# [Hemonculus](3-Mechanics\CLI\bestiary\fiend/hemonculus-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 587*  

---

*Sanguine Servitor (Fresh blood and gem dust)*

---

Hemonculus are servitors created by a blood magic ritual that binds a fiendish spirit into a blood-formed body. For the cost of a small sacrifice in blood (the creator's own or otherwise), the creatures serve as spies and assist in procuring further blood for magical use.

```statblock
"name": "Hemonculus (CrookedMoon24)"
"size": "Tiny"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "6d4 + 12"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "16"
  - !!int "14"
  - !!int "7"
  - !!int "10"
  - !!int "6"
"speed": "20 ft., fly 40 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "cold, fire"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 10"
"languages": "Common"
"cr": "1"
"traits":
  - "desc": "The hemonculus knows the location of any Bloodied creature within 60\
      \ feet of it, unless the creature is a Construct or Undead."
    "name": "Blood Sense"
  - "desc": "The hemonculus doesn't provoke an Opportunity Attack when it flies out\
      \ of an enemy's reach."
    "name": "Flyby"
  - "desc": "The hemonculus has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Slashing damage\
      \ plus 3 (1d6) Necrotic damage, and the hemonculus attaches to the target. While\
      \ attached, the hemonculus automatically hits the target with its Claw attacks.\n\
      \nThe hemonculus can detach itself by spending 5 feet of its movement. The target\
      \ or a creature within 5 feet of it can detach the hemonculus as an action."
    "name": "Claw"
  - "desc": "The hemonculus magically draws blood from nearby creatures. *Constitution\
      \ Saving Throw:* DC 13, each creature of the hemonculus' choice in a 15-foot\
      \ <span title=\"Player's Handbook (2024)\">Emanation</span> originating from\
      \ the hemonculus. *Failure:* 10 (3d6) Necrotic damage, and the target can't\
      \ regain <span title=\"Player's Handbook (2024)\">Hit Points</span> until the\
      \ start of the hemonculus's next turn. *Success:* Half damage only. *Failure\
      \ or Success:* If the hemonculus is attached to a creature, the hemonculus regains\
      \ <span title=\"Player's Handbook (2024)\">Hit Points</span> equal to the Necrotic\
      \ damage taken by that target."
    "name": "Exsanguinate (1/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Hemonculus.webp"
```
^statblock

## Environment

planar (lower planes)