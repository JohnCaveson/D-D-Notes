---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Pigeon Hag
---
# [Pigeon Hag](3-Mechanics\CLI\bestiary\fey/pigeon-hag-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 522*  

---

*Vermin Hag of Deception and Control*

---

Pigeon hags are vain witches who place themselves above every other being. They seek to reinforce that belief by controlling and undermining the knowledge and relationships of others. Pigeon hags often insinuate themselves into a mortal settlement and walk among the people, usually in a position to hear and spread gossip that they can twist and manipulate to their own ends.

## Secret

The vanity of a pigeon hag is so overwhelming that polishing its ego can leave it flustered and briefly unable to act.

```statblock
"name": "Pigeon Hag (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "18"
"hp": !!int "228"
"hit_dice": "24d8 + 120"
"modifier": !!int "7"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "20"
  - !!int "19"
  - !!int "18"
  - !!int "22"
"speed": "30 ft., fly 60 ft. (hover)"
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+11"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
  - "name": "[Sleight of Hand](/3-Mechanics/CLI/skills.md#Sleight%20of%20Hand)"
    "desc": "+7"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 19"
"languages": "Common, Primordial (Avian), Sylvan"
"cr": "13"
"traits":
  - "desc": "While within 30 feet of at least two hag allies, the hag can cast one\
      \ of the following spells, requiring no Material components, using the spell's\
      \ normal casting time, and using Intelligence as the spellcasting ability: Augury,\
      \ Find Familiar, Identify, Locate Object, [Lucky Charm](/3-Mechanics/CLI/spells/lucky-charm-crookedmoon24.md)\
      \ (lasts until the hag casts it again, or chooses to end it with no action required),\
      \ or Unseen Servant. The hag must finish a <span title=\"Player's Handbook (2024)\"\
      >Long Rest</span> before using this trait to cast that spell again.\n"
    "name": "Coven Magic"
  - "desc": "As an Influence action, a creature that flatters the hag forces it to\
      \ succeed on a DC 17 Charisma saving throw or have the Incapacitated condition\
      \ until the end of the hag's next turn."
    "name": "Disarming Vanity"
  - "desc": "When the hag rolls <span title=\"Player's Handbook (2024)\">Initiative</span>,\
      \ it is surrounded by fey spirits in the form of angry pigeons.\n\nThe hag's\
      \ enemies within a 10-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from it have <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on ability checks and attack rolls. This trait doesn't function if the hag\
      \ has the Incapacitated condition."
    "name": "Harrying Wings"
"actions":
  - "desc": "The hag makes three Claw attacks. It can replace one attack with a use\
      \ of Spellcasting (at will spells only)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing damage\
      \ plus 10 (3d6) Psychic damage."
    "name": "Claw"
  - "desc": "*Wisdom Saving Throw:* DC 19, each creature in a 60-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* A target takes 45 (10d8)\
      \ Psychic damage and has the Incapacitated condition until the start of the\
      \ hag's next turn. *Success:* Half damage only."
    "name": "Agonizing Cackle (1/Day)"
  - "desc": "The hag casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 19):\n\n**At\
      \ will:** Command (level 2 version), Hold Person, Minor Illusion, Stinking Cloud\n\
      \n**1/day each:** Befuddlement, Dominate Person, Scrying, Word of Recall (lair\
      \ as sanctuary)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The hag shape-shifts into a Small or Medium Humanoid, or it returns to\
      \ its true form. Other than its size, its game statistics are the same in each\
      \ form. Any equipment it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Pigeon%20Hag.webp"
```
^statblock

## Environment

mountain, planar (fey)