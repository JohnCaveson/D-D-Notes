---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/environment/planar-lower-planes
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Brimstone Behemoth
---
# [The Brimstone Behemoth](3-Mechanics\CLI\bestiary\npc/the-brimstone-behemoth-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 546*  

---

*Apocalyptic Colossus of Hellfire*

---

The emergence of the Brimstone Behemoth means armageddon for whatever realm it erupts into. A Fiend as old as time itself, it is made of hellfire, brimstone, and dying worlds. It has a malevolent will that seeks only to bring about mass extinction and apocalypse. The only hope for many civilizations has been through the regular willing sacrifice of citizens to slow or delay the inevitable doom to come.

## Secret

If a soul willingly perishes in flame or lava to ensure the behemoth's demise, the Fiend will find its flame quenched.

## Brimstone Behemoth's Lair

The Brimstone Behemoth's lair is a vast underground cavern filled with magma, flames, and smoke. Once this colossus awakens, the crater that its cavern becomes serves as its lair.

```statblock
"name": "The Brimstone Behemoth (CrookedMoon24)"
"size": "Gargantuan"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "22"
"hp": !!int "468"
"hit_dice": "24d20 + 216"
"modifier": !!int "16"
"stats":
  - !!int "30"
  - !!int "10"
  - !!int "28"
  - !!int "18"
  - !!int "16"
  - !!int "26"
"speed": "60 ft., burrow 60 ft."
"saves":
  - "intelligence": !!int "12"
  - "dexterity": !!int "8"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+11"
"damage_resistances": "cold, lightning"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 21"
"languages": "all; telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "If a creature willingly sacrifices its life in fire or lava for the purpose\
      \ of defeating the behemoth, the creature can't be returned to life by any means.\
      \ For the next 24 hours, the behemoth has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on <span title=\"Player's Handbook (2024)\">D20 Tests</span>,\
      \ its <span title=\"Player's Handbook (2024)\">Speed</span> is halved, it has\
      \ <span title=\"Player's Handbook (2024)\">Vulnerability</span> to Radiant damage,\
      \ and it loses its Legendary <span title=\"Player's Handbook (2024)\">Resistance</span>\
      \ trait."
    "name": "Burning Sacrifice"
  - "desc": "When the behemoth deals Fire damage, it can choose to deal Necrotic damage\
      \ instead."
    "name": "Consuming Flame"
  - "desc": "If the behemoth fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
  - "desc": "The behemoth has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The behemoth deals double damage to objects and structures."
    "name": "Siege Monster"
  - "desc": "The behemoth can burrow through solid rock at half its <span title=\"\
      Player's Handbook (2024)\">Burrow Speed</span> and leaves a 20-foot-diameter\
      \ tunnel in its wake."
    "name": "Tunneler"
"actions":
  - "desc": "The behemoth makes one Bite attack, and it makes two Claw or Blazing\
      \ Boulder attacks in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +18, reach 15 ft. *Hit:* 26 (3d10 + 10) Slashing\
      \ damage plus 11 (2d10) Fire damage, and the target has the Grappled condition\
      \ (escape DC 20). Until the grapple ends, the target has the Restrained condition."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +18, reach 15 ft. *Hit:* 23 (3d8 + 10) Slashing\
      \ damage plus 5 (1d10) Fire damage."
    "name": "Claw"
  - "desc": "*Ranged Attack Roll:* +18, range 150 ft. *Hit:* 15 (1d10 + 10) Bludgeoning\
      \ damage plus 7 (2d6) Fire damage, and the target has the Prone condition."
    "name": "Blazing Boulder"
  - "desc": "The Brimstone Behemoth casts Earthquake and Meteor Swarm, requiring no\
      \ Material components and using Charisma as the spellcasting ability (spell\
      \ save DC 24).\n"
    "name": "Cataclysmic Spellcasting (1/Day)"
"reactions":
  - "desc": "The behemoth casts Hellish Rebuke in response to that spell's trigger,\
      \ using the same spellcasting ability as Cataclysmic Spellcasting."
    "name": "Hellish Rebuke"
"regional_effects":
  - "desc": "The region containing the Brimstone Behemoth's lair is changed by its\
      \ presence, creating the following effects:\n\n- **Relentless Blaze.** Within\
      \ 10 miles of the lair, flames become driven to spread and consume. Every hour,\
      \ contained fires in that area have a 10 percent chance of spreading to a flammable\
      \ object within 10 feet. Uncontained fires spread out of control in 10 minutes.\
      \  \n- **Tenacious Lava.** A creature that takes damage from lava within 1 mile\
      \ of the lair starts burning, and it takes 1d6 Fire damage instead of 1d4 when\
      \ it burns.  \n\nIf the Brimstone Behemoth dies or moves its lair elsewhere,\
      \ these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, The can expend a use to take one of the following actions.\
  \ The regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The behemoth makes one Blazing Boulder attack."
    "name": "Fire Rain"
  - "desc": "The behemoth causes lava to cover the ground in its space and in any\
      \ unoccupied spaces in any tunnels it left by burrowing within 100 feet. A creature\
      \ that touches the lava for the first time on a turn or starts its turn in the\
      \ lava takes 55 (10d10) Fire damage. A creature takes this damage only once\
      \ per round.\n\nThe lava cools and hardens after 1 hour or when the behemoth\
      \ uses this action again. The behemoth can't take this action again until the\
      \ start of its next turn."
    "name": "Lava Well"
  - "desc": "The behemoth moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span>, and it makes one Claw attack. On a hit, if the target is a creature,\
      \ it has the Prone condition."
    "name": "Trample"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Brimstone%20Behemoth.webp"
```
^statblock

## Environment

planar (lower planes), underground