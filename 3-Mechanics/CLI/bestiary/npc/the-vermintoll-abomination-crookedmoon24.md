---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Vermintoll Abomination
---
# [The Vermintoll Abomination](3-Mechanics\CLI\bestiary\npc/the-vermintoll-abomination-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 570*  

---

*Verminous Coven Amalgamation*

---

The magic that binds hag covens together is far more powerful than many spellcasters can fully comprehend. Vermintoll abominations come about when the magics of a centipede hag, a pigeon hag, and a weasel hag enmesh and fuse the witches into one mass, bound to their cauldron.

## Vermintoll Abomination's Lair

The Vermintoll Abomination's lair is a decrepit hideaway, often hidden in plain sight such as an attic, basement, or a seized home.

```statblock
"name": "The Vermintoll Abomination (CrookedMoon24)"
"size": "Large"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "178"
"hit_dice": "21d10 + 63"
"modifier": !!int "12"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "16"
  - !!int "17"
  - !!int "12"
  - !!int "20"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+10"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "psychic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 16"
"languages": "Common, Deep Speech, Infernal, Primordial (Auran), Sylvan"
"cr": "14"
"traits":
  - "desc": "If the abomination fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
  - "desc": "The abomination has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The abomination has three heads: a centipede hag's, a pigeon hag's, and\
      \ a weasel hag's. Whenever the abomination takes 50 damage or more on a single\
      \ turn, one of its heads dies (determined randomly). The abomination dies if\
      \ all its heads are dead. At the end of each of its turns, if it has at least\
      \ 1 <span title=\"Player's Handbook (2024)\">Hit Point</span> and any of its\
      \ heads are dead, the abomination regains 20 <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> and one of its dead heads returns to life."
    "name": "Multiple Heads"
"actions":
  - "desc": "The abomination makes three attacks, using Cauldron Slam or Brew Spray\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 11 (2d6 + 4) Bludgeoning\
      \ damage plus 9 (2d8) Acid damage."
    "name": "Cauldron Slam"
  - "desc": "*Ranged Attack Roll:* +7, range 90 ft. *Hit:* 20 (4d8 + 2) Acid damage,\
      \ and the target takes a -2 penalty to AC until the end of the abomination's\
      \ next turn."
    "name": "Brew Spray"
  - "desc": "The abomination casts one of the following spells, requiring no Material\
      \ components and using Charisma as the spellcasting ability (spell save DC 18):\n\
      \n**At will:** Dispel Magic, Hypnotic Pattern\n\n**1/day each:** Contagion,\
      \ Dream, Dominate Person"
    "name": "Spellcasting"
"regional_effects":
  - "desc": "The region containing the Vermintoll Abomination's lair is changed by\
      \ its presence, creating the following effects:\n\n- **Endless Vermin.** Within\
      \ 1 mile of the lair, Giant Centipedes, Giant Weasels, and pigeons (use the\
      \ Raven stat block) are common nuisances. They steal Tiny objects and befoul\
      \ food.  \n- **Loyal Dwelling.** The lair itself, including any greater structure\
      \ or complex it resides within, rejects intruders. Ability checks to pick locks\
      \ or find secret doors have <span title=\"Player's Handbook (2024)\">Disadvantage</span>.\
      \  \n\nIf the Vermintoll Abomination dies or moves its lair elsewhere, these\
      \ effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The abomination teleports up to 60 feet to an unoccupied space it can\
      \ see. *Dexterity Saving Throw:* DC 18, each creature in a 10-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from the abomination\
      \ at its destination space. *Failure:* 7 (2d6) Acid damage. *Success:* Half\
      \ damage."
    "name": "Corrosive Teleport"
  - "desc": "The abomination jumps to a space within 30 feet that contains one or\
      \ more Large or smaller creatures. *Dexterity Saving Throw:* DC 17, each creature\
      \ in the abomination's destination space. *Failure:* 15 (2d10 + 4) Bludgeoning\
      \ damage, and the target has the Prone condition. *Success:* Half damage only,\
      \ and the target is pushed 5 feet straight away from the abomination. *Failure\
      \ or Success:* The abomination can't take this action again until the start\
      \ of its next turn."
    "name": "Crushing Leap"
  - "desc": "The abomination uses one of the following options (if the necessary head\
      \ is alive); it can't use that option again until the start of its next turn:\n\
      \n- **Contagious Miasma (Centipede Hag Head).** *Constitution Saving Throw:*\
      \ DC 18, one creature the abomination can see within 5 feet. *Failure:* The\
      \ target takes 13 (3d8) Poison damage and has the Poisoned condition. While\
      \ Poisoned, it can't regain <span title=\"Player's Handbook (2024)\">Hit Points</span>.\
      \ The target repeats the saving throw when it finishes a <span title=\"Player's\
      \ Handbook (2024)\">Long Rest</span>, ending the effect on itself on a success.\
      \ *Success:* Half damage only.  \n- **Overwhelming Doubt (Pigeon Hag Head).**\
      \ *Wisdom Saving Throw:* DC 18, one creature the abomination can see within\
      \ 30 feet. *Failure:* 10 (3d6) Psychic damage, and the target has the Incapacitated\
      \ condition until the end of its next turn. *Success:* Half damage only.  \n\
      - **Waking Nightmare (Weasel Hag Head).** *Charisma Saving Throw:* DC 18, one\
      \ creature the abomination can see within 30 feet. *Failure:* 11 (2d10) Psychic\
      \ damage, and the target has the Frightened condition. While Frightened, the\
      \ target perceives its allies as enemies but isn't compelled to act in a specific\
      \ way. The target repeats the saving throw at the end of each of its turns,\
      \ ending the effect on itself on a success. After 1 minute, it succeeds automatically.\
      \ *Success:* Half damage only.  "
    "name": "Hag's Head"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Vermintol%20Abomination.webp"
```
^statblock

## Environment

forest, planar (fey), mountain, urban