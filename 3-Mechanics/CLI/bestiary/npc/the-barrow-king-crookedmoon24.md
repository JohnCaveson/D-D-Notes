---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Barrow King
---
# [The Barrow King](3-Mechanics\CLI\bestiary\npc/the-barrow-king-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 542*  

---

*Undying Monarch of the Damned*

---

The Barrow King is known only by the armies of Undead he commands, which all slumber in tombs and burial mounds. Wights and their zombie conscripts arise when trespassers violate the resting place of the king's army, and tales speak of a tide of death that will sweep across the world if the king himself should awaken. Records of the king's living exploits and identity are near nonexistent, but rumors abound, and the storm of stories and myths may conceal grains of truth.

## Secret

The Barrow King's only true weakness is his name, written in the runic form of his lost native language. A weapon inscribed with his runic name becomes his bane.

## Barrow King's Lair

The Barrow King's lair is his burial mound and the surrounding region of resting places for his vast army.

```statblock
"name": "The Barrow King (CrookedMoon24)"
"size": "Large"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "20"
"hp": !!int "414"
"hit_dice": "36d10 + 216"
"modifier": !!int "16"
"stats":
  - !!int "24"
  - !!int "14"
  - !!int "22"
  - !!int "16"
  - !!int "18"
  - !!int "24"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+14"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+11"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 21"
"languages": "Common"
"cr": "22"
"traits":
  - "desc": "If the king fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
  - "desc": "The king has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "Undead creatures of the king's choice (excluding himself) in a 60-foot\
      \ <span title=\"Player's Handbook (2024)\">Emanation</span> originating from\
      \ him have <span title=\"Player's Handbook (2024)\">Advantage</span> on attack\
      \ rolls and saving throws. He can't use this trait if he has the Incapacitated\
      \ condition."
    "name": "Marshall Undead"
  - "desc": "The king has AC 10 against attack rolls made with a weapon inscribed\
      \ with the runic form of his original name, and the king has <span title=\"\
      Player's Handbook (2024)\">Disadvantage</span> on attack rolls made against\
      \ a creature holding such a weapon."
    "name": "Name of Rest"
"actions":
  - "desc": "The king makes three Soul Blade attacks. He can replace one attack with\
      \ a use of Life Drain."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +14, reach 5 ft. or range 40/80 ft. *Hit:*\
      \ 17 (3d6 + 7) Slashing damage plus 13 (3d8) Necrotic damage. *Hit or Miss:*\
      \ The blade magically returns to the king's hand immediately after a ranged\
      \ attack."
    "name": "Soul Blade"
  - "desc": "*Constitution Saving Throw:* DC 22, one creature within 5 feet. *Failure:*\
      \ 16 (2d8 + 7) Necrotic damage, and the target's <span title=\"Player's Handbook\
      \ (2024)\">Hit Point</span> maximum decreases by an amount equal to the damage\
      \ taken.\n\nA Humanoid slain by this attack rises 24 hours later as a Wight\
      \ under the king's control, unless the Humanoid is restored to life or its body\
      \ is destroyed."
    "name": "Life Drain"
  - "desc": "The king's blade flies in a deadly arc around him. *Dexterity Saving\
      \ Throw:* DC 22, each creature of the king's choice in a 20-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from him. *Failure:*\
      \ A creature takes 35 (10d6) Force damage and has the Prone condition. *Success:*\
      \ Half damage only."
    "name": "Blade Storm (Recharge 5-6)"
"bonus_actions":
  - "desc": "The king casts Phantom Steed, requiring no spell components and using\
      \ Charisma as the spellcasting ability. The conjured steed takes no damage from\
      \ areas of effect. The spell ends early if the king casts it again.\n"
    "name": "Undying Mount (Recharge 5-6)"
"reactions":
  - "desc": "Trigger: The king is hit by an attack roll while holding a weapon or\
      \ shield. _Response:_ The king adds 7 to his AC against that attack, possibly\
      \ causing it to miss."
    "name": "Parry"
"regional_effects":
  - "desc": "The region containing the Barrow King's lair is changed by his presence,\
      \ creating the following effects:\n\n- **Empire of Desecration.** A Hallow spell\
      \ cast within 1 mile of the lair fails, but any resources used to cast it aren't\
      \ wasted.  \n- **Necrotic Shroud.** When a living creature within 1 mile of\
      \ the lair regains <span title=\"Player's Handbook (2024)\">Hit Points</span>\
      \ as part of finishing a <span title=\"Player's Handbook (2024)\">Long Rest</span>,\
      \ it can only regain up to half its <span title=\"Player's Handbook (2024)\"\
      >Hit Point</span> maximum.  \n\nIf the Barrow King dies or moves his lair elsewhere,\
      \ these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, The can expend a use to take one of the following actions.\
  \ The regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "*Strength Saving Throw:* DC 22, one creature the king can see within\
      \ 100 feet. *Failure:* A ghostly, skeletal arm pulls the target up to 40 feet\
      \ closer to the king, and the target's <span title=\"Player's Handbook (2024)\"\
      >Speed</span> is halved until the end of its next turn."
    "name": "Death Grasp"
  - "desc": "The king moves up to his <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ (or commands his mount to move up to its <span title=\"Player's Handbook (2024)\"\
      >Speed</span>) and makes one Soul Blade attack."
    "name": "Grim Charge"
  - "desc": "The king magically summons two Wights into unoccupied spaces he can see\
      \ within 30 feet of himself.\n\nThe wights obey the king and take their turn\
      \ immediately after him on the same <span title=\"Player's Handbook (2024)\"\
      >Initiative</span> count. A wight vanishes after 1 hour, when it or the king\
      \ dies, or when the king uses this action again. A creature that starts its\
      \ turn within 5 feet of a wight must succeed on a DC 15 Wisdom saving throw\
      \ or have the Frightened condition until the start of its next turn. The king\
      \ can't use this action again until the start of his next turn."
    "name": "Lord's Call"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Barrow%20King.webp"
```
^statblock

## Environment

any