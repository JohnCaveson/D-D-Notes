---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Chained Reaper
---
# [The Chained Reaper](3-Mechanics\CLI\bestiary\npc/the-chained-reaper-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 548*  

---

*Burdened Harbinger of Death*

---

The Chained Reaper is all that remains of a once-noble orc caretaker of the departed called Yorgrim. Having been corrupted by the mists of death known as the Shroud, the Chained Reaper is a being of hatred and bitterness, striving to cremate all living things in its balefire before binding them in chains of anguish.

## Secret

The Chained Reaper carries a memorial stone upon its back. If one can read aloud the names inscribed there, their purity will burn away the reaper's fury.

## Chained Reaper's Lair

The Chained Reaper's lair is a mausoleum holding its own empty grave and those of its former companions.

```statblock
"name": "The Chained Reaper (CrookedMoon24)"
"size": "Gargantuan"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "201"
"hit_dice": "13d20 + 65"
"modifier": !!int "10"
"stats":
  - !!int "6"
  - !!int "15"
  - !!int "20"
  - !!int "10"
  - !!int "16"
  - !!int "20"
"speed": "5 ft., fly 60 ft. (hover)"
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+7"
"damage_resistances": "acid, bludgeoning, cold, fire, lightning, piercing, slashing,\
  \ thunder"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 17"
"languages": "Common, Orc"
"cr": "11"
"traits":
  - "desc": "If a creature that can speak Orc within 30 feet of the reaper takes an\
      \ action to read aloud the names carved in the stone on the reaper's back, the\
      \ reaper takes 20 Radiant damage."
    "name": "Ancestral Shame"
  - "desc": "The reaper can see 60 feet into the Ethereal Plane when it is on the\
      \ Material Plane."
    "name": "Ethereal Sight"
  - "desc": "The reaper can move through other creatures and objects as if they were\
      \ <span title=\"Player's Handbook (2024)\">Difficult Terrain</span>. It takes\
      \ 5 (1d10) Force damage if it ends its turn inside an object."
    "name": "Incorporeal Movement"
  - "desc": "If the reaper fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The reaper makes one Balefire Scythe attack and one Chain attack, and\
      \ it uses either Chain Slam or Fling."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 15 ft. *Hit:* 14 (2d8 + 5) Necrotic damage,\
      \ and the target begins burning. It takes Necrotic damage instead of Fire damage\
      \ while burning in this way."
    "name": "Balefire Scythe"
  - "desc": "*Melee Attack Roll:* +9, reach 20 ft. *Hit:* 16 (2d10 + 5) Piercing damage.\
      \ If the target is a Large or smaller creature, it has the Grappled condition\
      \ (escape DC 15) from one of four chains."
    "name": "Chain"
  - "desc": "*Constitution Saving Throw:* DC 17, each creature Grappled by the reaper.\
      \ *Failure:* 9 (1d8 + 5) Bludgeoning damage, and the target has the Stunned\
      \ condition until the start of the reaper's next turn. *Success:* Half damage\
      \ only."
    "name": "Chain Slam"
  - "desc": "The reaper throws a Large or smaller creature Grappled by it to a space\
      \ it can see within 30 feet of itself that isn't in the air. *Dexterity Saving\
      \ Throw:* DC 17, the creature thrown and each creature in the destination space.\
      \ *Failure:* 9 (2d8) Bludgeoning damage, and the target has the Prone condition.\
      \ *Success:* Half damage only."
    "name": "Fling"
  - "desc": "The reaper casts the Etherealness spell, requiring no spell components\
      \ and using Charisma as the spellcasting ability. The reaper is visible on the\
      \ Material Plane while on the Border Ethereal and vice versa, but it can't affect\
      \ or be affected by anything on the other plane.\n"
    "name": "Etherealness"
"regional_effects":
  - "desc": "The region containing the Chained Reaper's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Chained Vitality.** A creature that\
      \ isn't a Construct or Undead that finishes a <span title=\"Player's Handbook\
      \ (2024)\">Long Rest</span> within 1 mile of the lair must succeed on a DC 15\
      \ Constitution saving throw or have its <span title=\"Player's Handbook (2024)\"\
      >Hit Point</span> maximum reduced by 5 (to a minimum of 1 HP).  \n- **Falling\
      \ Shroud.** Thin mist arises within 1 mile of the lair. Undead with the Incorporeal\
      \ Movement trait in that area have <span title=\"Player's Handbook (2024)\"\
      >Advantage</span> on Dexterity (Stealth) checks.  \n\nIf the Chained Reaper\
      \ dies or moves its lair elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The reaper makes one Balefire Scythe attack. The reaper can't take this\
      \ action again until the start of its next turn."
    "name": "Balefire Scythe"
  - "desc": "The reaper moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span> without provoking Opportunity Attacks."
    "name": "Drift"
  - "desc": "*Wisdom Saving Throw:* DC 17, each creature of the reaper's choice in\
      \ a 20-foot <span title=\"Player's Handbook (2024)\">Emanation</span> originating\
      \ from it. *Failure:* The target has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on ability checks and attack rolls until the end of its\
      \ next turn."
    "name": "Lantern Flare"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Chained%20Reaper.webp"
```
^statblock

## Environment

any