---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/24
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Dusk Mother
---
# [The Dusk Mother](3-Mechanics\CLI\bestiary\npc/the-dusk-mother-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 552*  

---

*Shade of Motherly Anguish*

---

The keening wail of a mother is unmistakable and haunting, and the legends that tell of the Dusk Mother barely scratch the surface of her terrifying existence. She carries a pair of oversized shears and a great bell she tolls to accompany her wailing. Her eternal torment stems from her children, who met their fate due to the Dusk Mother's negligence—or perhaps her wrath. Now she cries in shame for that loss as she searches for her children, or for souls to claim and fashion into dolls in a futile attempt to fill the void in her doomed soul.

## Secret

The Dusk Mother's only true weakness or fear is the remnants of her children—some trinket or toy they played with in life or, more chillingly, their spirits, which also wander the world, but never in the same place as their mother's shade.

## Dusk Mother's Lair

The Dusk Mother's lair is a home or other place in a settlement where tragedy struck, most often those involving children or families broken by loss.

```statblock
"name": "The Dusk Mother (CrookedMoon24)"
"size": "Large"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "19"
"hp": !!int "315"
"hit_dice": "30d10 + 150"
"modifier": !!int "16"
"stats":
  - !!int "1"
  - !!int "14"
  - !!int "20"
  - !!int "12"
  - !!int "14"
  - !!int "24"
"speed": "5 ft., fly 50 ft. (hover)"
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "9"
  - "charisma": !!int "14"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+14"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "acid, bludgeoning, cold, fire, lightning, piercing, slashing,\
  \ thunder"
"damage_immunities": "necrotic, poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 19"
"languages": "understands all but can't speak"
"cr": "24"
"traits":
  - "desc": "The mother always has the Invisible condition. Blindsight, Truesight,\
      \ and other effects that allow a creature to see Invisible creatures don't reveal\
      \ the mother. A creature that has been reduced to 0 <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> at least once in its life can see her normally."
    "name": "Death's Shroud"
  - "desc": "The mother can move through other creatures and objects as if they were\
      \ <span title=\"Player's Handbook (2024)\">Difficult Terrain</span>. She takes\
      \ 5 (1d10) Force damage if she ends her turn inside an object."
    "name": "Incorporeal Movement"
  - "desc": "If the mother fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
  - "desc": "The mother has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "Undead creatures of the mother's choice in a 60-foot <span title=\"Player's\
      \ Handbook (2024)\">Emanation</span> originating from her (excluding herself)\
      \ have <span title=\"Player's Handbook (2024)\">Advantage</span> on saving throws.\
      \ She can't use this trait if she has the Incapacitated condition."
    "name": "Steadfast Matron"
  - "desc": "At the start of her turn, if the mother can see a possession once owned\
      \ by her living children, or if she can see or hear the spirits of her children,\
      \ she has the Incapacitated condition until the start of her next turn, and\
      \ she must move as far from the object or spirits as possible."
    "name": "Undeniable Guilt"
"actions":
  - "desc": "The mother makes three Shears attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +14, reach 5 ft. *Hit:* 25 (4d8 + 7) Force damage.\
      \ If the target is a creature and is hit with two or more Shears attacks in\
      \ the same turn, it gains 1 Exhaustion level."
    "name": "Shears"
  - "desc": "The mother focuses her wail into her bell. *Wisdom Saving Throw:* DC\
      \ 22, each creature in a 30-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the mother (Constructs, Undead, and creatures that have ever\
      \ been raised from the dead succeed automatically). *Failure:* 77 (14d10) Psychic\
      \ damage that ignores the target's Resistance, if any, and the target has the\
      \ Stunned condition until the end of the mother's next turn. *Success:* Half\
      \ damage only."
    "name": "Mournful Tolling (1/Day)"
"bonus_actions":
  - "desc": "The mother targets the corpse of a creature she killed within the last\
      \ minute. The target's soul is drawn out and transforms into a ceramic doll\
      \ of the creature. The doll is a Tiny object with AC 15, HP equal to half the\
      \ creature's maximum <span title=\"Player's Handbook (2024)\">Hit Points</span>,\
      \ <span title=\"Player's Handbook (2024)\">Vulnerability</span> to Thunder damage,\
      \ and <span title=\"Player's Handbook (2024)\">Immunity</span> to Poison damage.\n\
      \nThe soul can dimly see and hear its surroundings, and creatures with telepathy\
      \ can communicate with the soul.\n\nIf the doll is destroyed, the soul arises\
      \ from the doll as a Shadow under the mother's control. The creature can't be\
      \ returned to life unless its soul is freed from the doll by a Wish spell, or\
      \ by destroying the shadow it spawned."
    "name": "Soul Doll"
"regional_effects":
  - "desc": "The region containing the Dusk Mother's lair is changed by her presence,\
      \ creating the following effects:\n\n- **Enduring Dirge.** Within 1 mile of\
      \ the lair, creatures with an Intelligence score higher than 4 who can speak\
      \ at least one language absently sing nursery rhymes or funeral songs without\
      \ intending to.  \n- **Thoughts of Loss.** Whenever a living creature within\
      \ 1 mile of the lair finishes a <span title=\"Player's Handbook (2024)\">Short\
      \ Rest</span>, it must succeed on a DC 15 Charisma saving throw or it gains\
      \ no benefit from the rest.  \n\nIf the Dusk Mother dies or moves her lair elsewhere,\
      \ these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, The can expend a use to take one of the following actions.\
  \ The regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The mother moves up to her <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ without provoking Opportunity Attacks. When she enters a creature's space\
      \ during this move, that creature takes 16 (3d10) Cold damage and has <span\
      \ title=\"Player's Handbook (2024)\">Disadvantage</span> on the next attack\
      \ roll it makes before the end of its next turn. A creature takes this damage\
      \ only once per turn. The mother can't take this action again until the start\
      \ of her next turn."
    "name": "Drift"
  - "desc": "*Constitution Saving Throw:* DC 22, each creature without the Deafened\
      \ condition in a 30-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the mother (Constructs, Undead, and creatures that have ever\
      \ been raised from the dead succeed automatically). *Failure:* 28 (8d6) Necrotic\
      \ damage that ignores the target's Resistance, if any. Failure by 5 or More:\
      \ The creature is reduced to 0 <span title=\"Player's Handbook (2024)\">Hit\
      \ Points</span>. *Success:* Half damage. *Failure or Success:* The mother can't\
      \ take this action again until the start of her next turn."
    "name": "Endless Keening"
  - "desc": "The mother makes one Shears attack."
    "name": "Snip"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Dusk%20Mother.webp"
```
^statblock

## Environment

any