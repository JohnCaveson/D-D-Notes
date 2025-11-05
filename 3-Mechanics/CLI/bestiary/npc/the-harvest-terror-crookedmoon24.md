---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/planar-abyss
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Harvest Terror
---
# [The Harvest Terror](3-Mechanics\CLI\bestiary\npc/the-harvest-terror-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 560*  

---

*Demon of Secrets and Despair*

---

Once a jovial soul imbued into the body of a scarecrow called Ol' Jericho Sticks, the Harvest Terror is now a nightmarish abomination. It is a mockery of demonic flesh molded in the shape of a crow-like scarecrow. Its twisted body is made of molding wicker with four tattered, blackfeathered wings sprouting from its back. An oversized corvid head with amber eyes sits upon its broad shoulders, its dark beak a jagged mess, and it wields a chipped, wicked scythe covered in old blood. Forever hungry, the Harvest Terror feeds on secrets and those that keep them.

## Secret

The soul of Ol' Jericho Sticks still exists in the dark recesses of the Harvest Terror's mind. Singing or playing Jericho's favorite song tips the balance of control over Jericho's stolen body.

## Harvest Terror's Lair

The Harvest Terror's lair is the extraplanar corn mazeknown as the Fields of the Crow.

```statblock
"name": "The Harvest Terror (CrookedMoon24)"
"size": "Large"
"type": "fiend"
"subtype": "Demon"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "105"
"hit_dice": "10d10 + 50"
"modifier": !!int "10"
"stats":
  - !!int "19"
  - !!int "19"
  - !!int "20"
  - !!int "13"
  - !!int "15"
  - !!int "18"
"speed": "30 ft., fly 90 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "8"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
  \ (except for its Unraveling Song trait)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 120 ft., passive Perception 18"
"languages": "all; telepathy 120 ft."
"cr": "6"
"traits":
  - "desc": "The terror can mimic voices and sounds it has heard. A listener can discern\
      \ the mimicry for what it is with a successful DC 18 Wisdom (Insight) check."
    "name": "Demonic Mimicry"
  - "desc": "If the terror fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The terror has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "As an Influence action, a creature can play or sing Jericho Sticks' favorite\
      \ song, \"Coal-Eyed Birds,\" to give the terror the Charmed condition until\
      \ the end of the creature's next turn. The condition ends early if the creature\
      \ damages the terror or forces it to make a saving throw."
    "name": "Unraveling Song"
"actions":
  - "desc": "The terror makes one Claw attack and one Scythe attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 8 (1d8 + 4) Slashing damage.\
      \ If the target is a Medium or smaller creature, it has the Prone condition."
    "name": "Claw"
  - "desc": "*Melee Attack Roll:* +7, reach 10 ft. *Hit:* 9 (1d10 + 4) Slashing damage\
      \ plus 4 (1d8) Psychic damage."
    "name": "Scythe"
  - "desc": "*Wisdom Saving Throw:* DC 15, each creature within a 30-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from the terror. *Failure:*\
      \ The creature takes 11 (2d10) Psychic damage and has <span title=\"Player's\
      \ Handbook (2024)\">Disadvantage</span> on ability checks and attack rolls.\
      \ At the end of each of its turns, it repeats the save, ending the effect on\
      \ itself on a success.\n\nAfter 1 minute, it succeeds automatically. *Success:*\
      \ Half damage only."
    "name": "Dirge of Secrets (Recharge 5-6)"
"regional_effects":
  - "desc": "The region containing the Harvest Terror's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Amber Eyes.** Within 1 mile of the\
      \ lair, amber-eyed crows watch everything. Enemies of the Harvest Terror have\
      \ <span title=\"Player's Handbook (2024)\">Disadvantage</span> on Dexterity\
      \ (Stealth) checks in the region.  \n- **Spilled Secrets.** Within 1 mile of\
      \ the lair, creatures other than the Harvest Terror have <span title=\"Player's\
      \ Handbook (2024)\">Disadvantage</span> on Charisma (Deception) checks made\
      \ to keep secrets.  \n\nIf the Harvest Terror dies or moves its lair elsewhere,\
      \ these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The terror moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span> without provoking Opportunity Attacks."
    "name": "Crow's Swoop"
  - "desc": "The terror's beak gapes and devours secrets. *Wisdom Saving Throw:* DC\
      \ 15, each creature in a 20-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the terror (with <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> if the target has given up one of its secrets to the terror).\
      \ *Failure:* 7 (2d6) Psychic damage, and the target's <span title=\"Player's\
      \ Handbook (2024)\">Speed</span> is 0 until the end of its next turn. *Success:*\
      \ Half damage only. *Failure or Success:* The terror can't take this action\
      \ again until the start of its next turn."
    "name": "Devour Secrets"
  - "desc": "The terror casts the Wind Wall spell (which can't appear in a creature's\
      \ space), requiring no spell components and using Charisma as the spellcasting\
      \ ability.\n"
    "name": "Averting Winds"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Harvest%20Terror.webp"
```
^statblock

## Environment

grassland, planar (abyss)