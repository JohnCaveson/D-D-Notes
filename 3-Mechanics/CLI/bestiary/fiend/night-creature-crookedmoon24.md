---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Night Creature
---
# [Night Creature](3-Mechanics\CLI\bestiary\fiend/night-creature-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 519*  

---

*Bestial Blood Hunter*

---

Night creatures are fiendish spirits bound into vampire-blood-tainted corpses through profane rituals. The hulking brutes are fanatically loyal to their creators, a fact some vampire overlords learn too late when those they employ to create the night creatures develop ambitions of their own.

## Secrets

Night creatures are quickly undone by the purity of salt if wiped on a weapon and driven into a wound.

```statblock
"name": "Night Creature (CrookedMoon24)"
"size": "Large"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "14"
  - !!int "8"
  - !!int "12"
  - !!int "14"
"speed": "40 ft., climb 40 ft."
"saves":
  - "strength": !!int "6"
"skillsaves":
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+5"
"damage_vulnerabilities": "Damage from weapons wiped with salt"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed) (except\
  \ from its creator); [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion); [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 11"
"languages": "Common plus one other language"
"cr": "4"
"traits":
  - "desc": "The night creature has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on Wisdom checks made to find or track a creature that is missing any <span\
      \ title=\"Player's Handbook (2024)\">Hit Points</span>."
    "name": "Blood Stalker"
  - "desc": "The night creature has <span title=\"Player's Handbook (2024)\">Vulnerability</span>\
      \ to damage from weapons wiped with salt. A creature can take a <span title=\"\
      Player's Handbook (2024)\">Bonus Action</span> to wipe salt onto a weapon, which\
      \ remains coated for 1 minute, or until it hits a creature."
    "name": "Salt Susceptibility"
  - "desc": "The night creature can climb difficult surfaces, including along ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The night creature takes 20 Radiant damage if it starts its turn in sunlight.\
      \ While in sunlight, it has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on attack rolls and ability checks."
    "name": "Sunlight Hypersensitivity"
"actions":
  - "desc": "The night creature makes one Claw attack and uses Bite."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing damage.\
      \ If the target is a Medium or smaller creature, it has the Grappled condition\
      \ (escape DC 14) from one of two claws."
    "name": "Claw"
  - "desc": "*Constitution Saving Throw:* DC 14, one creature within 5 feet that is\
      \ willing or that has the Grappled, Incapacitated, or Restrained condition.\
      \ *Failure:* 6 (1d4 + 4) Piercing damage plus 7 (2d6) Necrotic damage. The target's\
      \ <span title=\"Player's Handbook (2024)\">Hit Point</span> maximum decreases\
      \ by an amount equal to the Necrotic damage taken, and the night creature regains\
      \ <span title=\"Player's Handbook (2024)\">Hit Points</span> equal to that amount."
    "name": "Bite"
"bonus_actions":
  - "desc": "If the night creature isn't in sunlight, it shape-shifts into a Medium\
      \ Humanoid or returns to its true form. Its game statistics, other than its\
      \ size, are the same in each form. Any equipment it is wearing or carrying isn't\
      \ transformed."
    "name": "Shape-Shift"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Night%20Creature.webp"
```
^statblock

## Environment

any