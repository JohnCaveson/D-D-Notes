---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Galloping Headsman
---
# [The Galloping Headsman](3-Mechanics\CLI\bestiary\npc/the-galloping-headsman-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 554*  

---

*Headless Executioner of Vengeance*

---

The Galloping Headsman is a formidable combination of human and horse musculature fused with nightmarish magic and dark revenge. Gouts of flame burst from where its head and tail should be and dance dangerously along the edge of its massive two-headed axe. A burning, skull-shaped pumpkin floats eerily in one hand, its fiery visage a constantly shifting train of agonized faces.

## Secret

The Galloping Headsman's original skull is its greatest weakness, and anyone holding the skull becomes the apparition's bane.

## Galloping Headsman's Lair

The Galloping Headsman's lair is the stretch of road that serves as the anchor point of the creature's search for vengeance.

```statblock
"name": "The Galloping Headsman (CrookedMoon24)"
"size": "Large"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "19"
"hp": !!int "220"
"hit_dice": "21d10 + 105"
"modifier": !!int "15"
"stats":
  - !!int "22"
  - !!int "17"
  - !!int "20"
  - !!int "11"
  - !!int "14"
  - !!int "18"
"speed": "60 ft."
"saves":
  - "wisdom": !!int "8"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
"damage_vulnerabilities": "Damage dealt by a creature holding the headman's original\
  \ skull"
"damage_resistances": "necrotic"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 18"
"languages": "Common; telepathy 120 ft."
"cr": "18"
"traits":
  - "desc": "The headsman has <span title=\"Player's Handbook (2024)\">Vulnerability</span>\
      \ to any damage dealt by a creature holding the headsman's original skull, and\
      \ it has <span title=\"Player's Handbook (2024)\">Disadvantage</span> on ability\
      \ checks and attack rolls made against that creature."
    "name": "Binding Skull"
  - "desc": "If the headsman fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
  - "desc": "The headsman has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The headsman makes two Headsman's Axe attacks and one Hooves attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +12, reach 5 ft. *Hit:* 19 (2d12 + 6) Slashing damage\
      \ plus 16 (3d10) Fire damage. If the target is a creature with at least one\
      \ head and the headsman rolled a 20 on the attack roll, the target must succeed\
      \ on a DC 20 Constitution saving throw or it is decapitated and dies if it can't\
      \ survive without a head. A target is immune to this effect if it takes none\
      \ of the damage, has Legendary Actions, or is Huge or larger. Such a creature\
      \ takes an extra 28 (8d6) Force damage from the hit."
    "name": "Headsman's Axe"
  - "desc": "*Melee Attack Roll:* +12, reach 5 ft. *Hit:* 24 (4d8 + 6) Bludgeoning\
      \ damage. If the headsman moved at least 20 feet immediately before the hit,\
      \ the target takes an extra 9 (2d8) Necrotic damage and has the Prone condition."
    "name": "Hooves"
  - "desc": "The headsman hurls its skull, after which it reappears in the headsman's\
      \ hand. *Dexterity Saving Throw:* DC 20, each creature in a 90-foot-long, 10-foot-wide\
      \ <span title=\"Player's Handbook (2024)\">Line</span>. *Failure:* 63 (14d8)\
      \ Fire damage. *Success:* Half damage. *Failure or Success:* The target starts\
      \ burning."
    "name": "Flaming Skull (Recharge 5-6)"
"regional_effects":
  - "desc": "The region containing the Galloping Headsman's lair is changed by its\
      \ presence, creating the following effects:\n\n- **Encroaching Doom.** Within\
      \ 6 miles of the lair, an air of doom clings to creatures. Creatures have <span\
      \ title=\"Player's Handbook (2024)\">Disadvantage</span> on saving throws made\
      \ to avoid or end the Frightened condition that aren't caused by the Galloping\
      \ Headsman.  \n- **Interminable Journey.** Paths warp and stretch within 6 miles\
      \ of the lair. In that area, travel pace outside of combat is halved.  \n\n\
      If the Galloping Headsman dies or moves its lair elsewhere, these effects end\
      \ immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, The can expend a use to take one of the following actions.\
  \ The regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The headsman moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span> without provoking Opportunity Attacks."
    "name": "Move"
  - "desc": "*Wisdom Saving Throw:* DC 18, one creature the headsman can see within\
      \ 90 feet. *Failure:* The target has the Frightened condition and repeats the\
      \ save at the end of each of its turns, ending the effect on itself on a success.\
      \ After 1 minute, it succeeds automatically. *Failure or Success:* The headsman\
      \ can't take this action again until the start of its next turn."
    "name": "Rancorous Gaze"
  - "desc": "The headsman makes one Headsman's Axe attack with <span title=\"Player's\
      \ Handbook (2024)\">Advantage</span>. If the target has the Frightened condition,\
      \ treat a 19 on the d20 as a 20.\n\nThe headsman can't take this action again\
      \ until the start of its next turn."
    "name": "Relentless Execution"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Galloping%20Horseman.webp"
```
^statblock

## Environment

forest, grassland, hill, urban