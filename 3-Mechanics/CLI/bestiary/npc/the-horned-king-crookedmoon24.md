---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar-lower
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Horned King
---
# [The Horned King](3-Mechanics\CLI\bestiary\npc/the-horned-king-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 562*  

---

*Sin Made Manifest*

---

Every sinful, selfish action in the world pours a fraction of itself into the Horned King, a being composed of every mortal who has surrendered to temptation. Fortunately, under normal circumstances, the Horned King exists as an ephemeral spirit with no physical presence. During times of upheaval, when a great many mortals give in to their selfish desires or when another power—such as a deity, demon lord, or archfey— interferes, the Horned King is made manifest, and with it comes the weight of sin flooding back into the world that created it.

## Horned King's Lair

The Horned King's lair is the forest clearing where a twisted tree focuses the malevolent will that gave rise to the king's physical presence.

```statblock
"name": "The Horned King (CrookedMoon24)"
"size": "Gargantuan"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "19"
"hp": !!int "217"
"hit_dice": "14d20 + 70"
"modifier": !!int "14"
"stats":
  - !!int "22"
  - !!int "14"
  - !!int "20"
  - !!int "10"
  - !!int "10"
  - !!int "22"
"speed": "50 ft., fly 100 ft."
"saves":
  - "strength": !!int "12"
  - "wisdom": !!int "6"
  - "constitution": !!int "11"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+12"
"damage_resistances": "cold, fire"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 22"
"languages": "all; telepathy 120 ft."
"cr": "17"
"traits":
  - "desc": "If the Horned King dies, its body disappears in a cloud of ash. It becomes\
      \ an intangible, Invisible spirit in its home forest, and it can't reform a\
      \ new physical body for 10d10 years."
    "name": "Enduring Restoration"
  - "desc": "If the Horned King fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (5/Day)"
  - "desc": "The Horned King has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The Horned King makes three Cursed Strike attacks. It can replace one\
      \ attack with a use of Terrorizing Breath."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +12 (against a cursed target, scores a <span title=\"\
      Player's Handbook (2024)\">Critical Hit</span> on a 19 or 20 on the d20), reach\
      \ 10 ft. *Hit:* 17 (2d10 + 6) Bludgeoning, Piercing, or Slashing damage (Horned\
      \ King's choice) plus 7 (2d6) Necrotic damage. If the target is a creature,\
      \ it is cursed until the end of the Horned King's next turn. While cursed, it\
      \ must subtract 1d4 from <span title=\"Player's Handbook (2024)\">D20 Tests</span>."
    "name": "Cursed Strike"
  - "desc": "*Dexterity Saving Throw:* DC 19, each creature in a 60-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 21 (6d6) Necrotic damage\
      \ plus 21 (6d6) Psychic damage, and the target gains 1 Exhaustion level that\
      \ ends at the end of the target's next turn. *Success:* Half damage only."
    "name": "Breath of Corruption (Recharge 5-6)"
  - "desc": "*Wisdom Saving Throw:* DC 19, each creature in a 60-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* The target has the Frightened\
      \ condition. It repeats the save at the end of each of its turns, ending the\
      \ effect on itself on a success. After 1 minute, it succeeds automatically."
    "name": "Terrorizing Breath"
"bonus_actions":
  - "desc": "The Horned King casts Detect Thoughts, requiring no spell components\
      \ and using Charisma for the spellcasting ability (spell save DC 20)."
    "name": "Sense Desire"
"regional_effects":
  - "desc": "The region containing the Horned King's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Sweet Temptation.** Within 1 mile of\
      \ the lair, a creature that acts on a sinful impulse to the detriment of a <span\
      \ title=\"Player's Handbook (2024)\">Friendly</span> or <span title=\"Player's\
      \ Handbook (2024)\">Indifferent</span> creature increases its <span title=\"\
      Player's Handbook (2024)\">Hit Point</span> maximum and current <span title=\"\
      Player's Handbook (2024)\">Hit Points</span> by 10 until it finishes a <span\
      \ title=\"Player's Handbook (2024)\">Long Rest</span>. Creatures are aware of\
      \ this effect. This can't occur again until the creature finishes a <span title=\"\
      Player's Handbook (2024)\">Long Rest</span>.  \n- **Tenacious Curses.** Within\
      \ 1 mile of the lair, saving throws against curses have <span title=\"Player's\
      \ Handbook (2024)\">Disadvantage</span>.  \n\nIf the Horned King dies or moves\
      \ its lair elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The Horned King's snakelike tongue whips out hungrily. *Charisma Saving\
      \ Throw:* DC 20, one cursed creature the Horned King can see within 15 feet.\
      \ *Failure:* The target takes 16 (3d10) Psychic damage, the Horned King regains\
      \ <span title=\"Player's Handbook (2024)\">Hit Points</span> equal to the damage\
      \ taken, and one curse of the Horned King's choice affecting the target ends."
    "name": "Taste of Wickedness"
  - "desc": "The Horned King speaks to a creature it can see within 120 feet and offers\
      \ it either <span title=\"Player's Handbook (2024)\">Heroic Inspiration</span>\
      \ or to restore 20 of its <span title=\"Player's Handbook (2024)\">Hit Points</span>.\
      \ If the creature accepts, it gains that benefit but is cursed for 1 minute.\
      \ While cursed, the Horned King has <span title=\"Player's Handbook (2024)\"\
      >Resistance</span> to all damage the target deals. The Horned King can't take\
      \ this action again until the start of its next turn."
    "name": "Temptation"
  - "desc": "The Horned King moves up to half its <span title=\"Player's Handbook\
      \ (2024)\">Speed</span>, and it makes one Cursed Strike attack.The Horned King\
      \ can't take this action again until the start of its next turn."
    "name": "Trample"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Horned%20King.webp"
```
^statblock

## Environment

forest, planar (lower)