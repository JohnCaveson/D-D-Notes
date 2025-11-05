---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Tall Man
---
# [The Tall Man](3-Mechanics\CLI\bestiary\npc/the-tall-man-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 568*  

---

*Murderous Archfey of the Dark Wood*

---

The Tall Man is a mysterious entity that haunts an accursed forest. Once, he was an archfey who ruled a now-forgotten court, renowned for its dances that lasted for nights on end. Doomed now to walk his rotting forest, the Tall Man finds pleasure where he can by tempting travelers and forest denizens alike to play hide and seek with him—with deadly results.

## Secret

Dancing forgotten steps once performed in the fey court that the Tall Man formerly ruled shreds his being.

## Tall Man's Lair

The Tall Man's lair is the dark forest he now haunts, where his forgotten Fey court once thrived.

```statblock
"name": "The Tall Man (CrookedMoon24)"
"size": "Huge"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "322"
"hit_dice": "28d12 + 140"
"modifier": !!int "18"
"stats":
  - !!int "18"
  - !!int "22"
  - !!int "20"
  - !!int "18"
  - !!int "16"
  - !!int "20"
"speed": "40 ft."
"saves":
  - "strength": !!int "10"
  - "wisdom": !!int "9"
  - "constitution": !!int "11"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+15"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+18"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 25"
"languages": "Common, Sylvan; telepathy 120 ft."
"cr": "20"
"traits":
  - "desc": "If the Tall Man fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
  - "desc": "The Tall Man has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "As a <span title=\"Player's Handbook (2024)\">Bonus Action</span>, a\
      \ creature can perform some steps from a dance of the Tall Man's court and make\
      \ a DC 20 Charisma (Performance) check. On a success, the Tall Man takes 20\
      \ Force damage and has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on <span title=\"Player's Handbook (2024)\">D20 Tests</span> until the start\
      \ of the creature's next turn."
    "name": "Memory's Dance"
"actions":
  - "desc": "The Tall Man makes two Claw attacks and uses Spellcasting to cast Vicious\
      \ Mockery (4d6 Psychic damage)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +12, reach 15 ft. *Hit:* 13 (2d6 + 6) Slashing damage\
      \ plus 14 (4d6) Psychic damage. If the target is a Large or smaller creature,\
      \ it has the Grappled condition (escape DC 14) from one of two claws, and has\
      \ the Restrained condition until the grapple ends."
    "name": "Claw"
  - "desc": "The Tall Man casts one of the following spells, requiring no Material\
      \ components and using Charisma as the spellcasting ability (spell save DC 19):\n\
      \n**At will:** Invisibility, Minor Illusion, Vicious Mockery (4d6 Psychic damage)\n\
      \n**2/day:** Darkness"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The Tall Man magically transforms into a Small or Medium Humanoid, or\
      \ back to his true form. His statistics, other than his size, are the same in\
      \ each form. Any equipment he is wearing or carrying changes to accommodate\
      \ his new form. He can take on any features he chooses, but he is always unnaturally\
      \ tall for whatever guise he takes. He returns to his true form if he dies."
    "name": "Elusive Disguise"
"reactions":
  - "desc": "Trigger: The Tall Man takes damage. _Response:_ The Tall Man has <span\
      \ title=\"Player's Handbook (2024)\">Resistance</span> to the triggering damage\
      \ and teleports up to 30 feet to an unoccupied space he can see."
    "name": "Evasive Blink"
"regional_effects":
  - "desc": "The region containing the Tall Man's lair is changed by his presence,\
      \ creating the following effects:\n\n- **Deepening Shadows.** Within 1 mile\
      \ of the lair, shadows stretch far beyond what they should. Creatures can find\
      \ a sufficiently shadowy spot to hide in, even without cover, 50 percent of\
      \ the time.  \n- **Too Quiet.** Sounds are muffled within 1 mile of the lair,\
      \ halving the distance at which sounds can be heard.  \n\nIf the Tall Man dies\
      \ or moves his lair elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, The can expend a use to take one of the following actions.\
  \ The regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The Tall Man uses Spellcasting."
    "name": "Spellcasting"
  - "desc": "The Tall Man makes one Claw attack, then can't take this action again\
      \ until the start of his next turn."
    "name": "Strike"
  - "desc": "The Tall Man teleports up to 60 feet to an unoccupied space he can see.\
      \ When he teleports, he can force a creature he is grappling to succeed on a\
      \ DC 18 Charisma saving throw or teleport with him, appearing in the closest\
      \ unoccupied space to the Tall Man's destination."
    "name": "Teleport"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/The%20Tall%20Man.webp"
```
^statblock

## Environment

forest, planar (fey)