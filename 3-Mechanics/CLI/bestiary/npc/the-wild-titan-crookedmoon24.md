---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/giant/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Wild Titan
---
# [The Wild Titan](3-Mechanics\CLI\bestiary\npc/the-wild-titan-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 578*  

---

*Ferocious Giant of the Wilderness*

---

Wandering the most inhospitable mountain ranges, the Wild Titan is the wilderness made manifest, created long ago by a forgotten will for a purpose that none know. Favoring solitude in the most remote places of the world, when it encounters settlements and "civilized" people, it wants only to turn them to primal savagery or crush them beneath its immense bulk.

## Secret

The name of the Wild Titan's forgotten creator is its undoing. Recovering the lost name and carving its glyph form into a stone creates a zone that severs the titan's connection to the wild.

## Wild Titan's Lair

The Wild Titan's lair is a hollowed-out peak in the mountain range the creature stalks.

```statblock
"name": "The Wild Titan (CrookedMoon24)"
"size": "Gargantuan"
"type": "giant"
"subtype": "Titan"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"hp": !!int "350"
"hit_dice": "20d20 + 140"
"modifier": !!int "14"
"stats":
  - !!int "30"
  - !!int "11"
  - !!int "24"
  - !!int "8"
  - !!int "16"
  - !!int "10"
"speed": "50 ft."
"saves":
  - "dexterity": !!int "7"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+17"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+10"
"damage_immunities": "cold"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 120 ft., passive Perception 20"
"languages": "Common, Giant, Primordial (Terran)"
"cr": "21"
"traits":
  - "desc": "If the titan fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day or 5/Day in Lair)"
  - "desc": "The titan has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "If the titan starts its turn within 50 feet of a stone at least 10 feet\
      \ high and 10 feet wide that is carved with the glyph representing its forgotten\
      \ creator, the titan takes 50 Necrotic damage and has the Poisoned condition\
      \ until the start of its next turn."
    "name": "Runic Sever"
  - "desc": "The titan deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The titan makes two Massive Fist attacks. It can replace one or both\
      \ attacks with a use of Thrown Boulder."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +17, reach 20 ft. *Hit:* 28 (4d8 + 10) Bludgeoning\
      \ damage. If the target is a Huge or smaller creature, it has the Grappled condition\
      \ (escape DC 20) from one of two fists, and it has the Restrained condition\
      \ until the grapple ends."
    "name": "Massive Fist"
  - "desc": "The titan hurls a boulder at a point it can see within 150 feet. *Dexterity\
      \ Saving Throw:* DC 25, each creature in a 10-foot radius <span title=\"Player's\
      \ Handbook (2024)\">Sphere</span> centered on that point. *Failure:* 14 (4d6)\
      \ Bludgeoning damage, and the target has the Prone condition. *Success:* Half\
      \ damage only."
    "name": "Thrown Boulder"
  - "desc": "*Wisdom Saving Throw:* DC 19, each of the titan's enemies in a 100-foot\
      \ <span title=\"Player's Handbook (2024)\">Emanation</span> originating from\
      \ the titan. *Failure:* The target has the Charmed condition until the start\
      \ of the titan's next turn. While Charmed in this way, the creature must use\
      \ its action to make its most powerful melee or ranged attacks against the nearest\
      \ creature it can see."
    "name": "Wild Roar (Recharge 5-6)"
"regional_effects":
  - "desc": "The region containing the Wild Titan's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Whiteout.** Within 1 mile of the lair,\
      \ there is a 75 percent chance every day of heavy precipitation.  \n- **Wild\
      \ Hunger.** Within 1 mile of the lair, creatures always feel ravenously hungry,\
      \ no matter how much they've eaten. A creature that finishes a <span title=\"\
      Player's Handbook (2024)\">Long Rest</span> in this area must succeed on a DC\
      \ 15 Constitution saving throw or gain 1 Exhaustion level. A creature that doesn't\
      \ require food succeeds automatically.  \n\nIf the Wild Titan dies or moves\
      \ its lair elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, The can expend a use to take one of the following actions.\
  \ The regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "*Dexterity Saving Throw:* DC 25, each creature in a 20-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 9 (2d8) Bludgeoning damage,\
      \ and the target has the Prone condition. *Success:* Half damage only. *Failure\
      \ or Success:* The titan can't use this action again until the start of its\
      \ next turn."
    "name": "Arm Sweep"
  - "desc": "The titan hurls an object it is holding, a creature it is grappling,\
      \ or a Large clod of earth to a space within 100 feet. *Dexterity Saving Throw:*\
      \ DC 25, each creature in the projectile's space, including a hurled creature.\
      \ *Failure:* 19 (2d8 + 10) Bludgeoning damage, and the target has the Prone\
      \ condition. *Success:* Half damage only. *Failure or Success:* The titan can't\
      \ use this action again until the start of its next turn."
    "name": "Crushing Hurl"
  - "desc": "The titan moves up to its <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ without provoking Opportunity Attacks. It can enter a Huge or smaller creature's\
      \ space, and the creature is pushed to nearest unoccupied space."
    "name": "Stomping Stride"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Wild%20Titan.webp"
```
^statblock

## Environment

arctic, forest, hill, mountain