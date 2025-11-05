---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead/paladin
- ttrpg-cli/monster/type/undead/vampire
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Crimson Abbot
---
# [The Crimson Abbot](3-Mechanics\CLI\bestiary\npc/the-crimson-abbot-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 550*  

---

*Unholy Crusader of Blood*

---

In life, the Crimson Abbot was a virtuous crusader named Sir Marius Renathyr but was seduced by the sweet whispers of an archdevil of deceit and pride who masqueraded as a goddess of righteousness. On the brink of death, the abbot accepted the whispered offer for eternal life, and in so doing, was transformed into a creature of unbearable pride with an unquenchable thirst for blood. He continues to work in the name of his "goddess" and has gathered a fanatically loyal congregation eager for his promise of pure, everlasting life.

## Secret

The Crimson Abbot's pride is nearly unshakable, but seeing a true reminder of the righteous man he once was can crack his façade.

## Crimson Abbot's Lair

The Crimson Abbot's lair is a blood-soaked monastery where unworthy mortals are burned in sacrifice, and vampire minions study truths hidden in blood.

```statblock
"name": "The Crimson Abbot (CrookedMoon24)"
"size": "Large"
"type": "undead"
"subtype": "Paladin, Vampire"
"alignment": "Lawful Evil"
"ac": !!int "17"
"hp": !!int "85"
"hit_dice": "9d10 + 36"
"modifier": !!int "8"
"stats":
  - !!int "22"
  - !!int "15"
  - !!int "18"
  - !!int "11"
  - !!int "12"
  - !!int "18"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  - "strength": !!int "9"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"damage_immunities": "necrotic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 17"
"languages": "Common, Elvish"
"cr": "8"
"traits":
  - "desc": "If a creature takes a <span title=\"Player's Handbook (2024)\">Bonus\
      \ Action</span> to present a memento or recite a reminder of the abbot's past\
      \ and succeeds on a DC 15 Charisma (Persuasion) check, the abbot has <span title=\"\
      Player's Handbook (2024)\">Disadvantage</span> on the next <span title=\"Player's\
      \ Handbook (2024)\">D20 Test</span> he makes before the start of the creature's\
      \ next turn."
    "name": "Honor Lost"
  - "desc": "If the abbot fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The abbot can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The abbot takes 20 Radiant damage if he starts his turn in sunlight.\
      \ While in sunlight, he has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on attack rolls and ability checks."
    "name": "Sunlight Hypersensitivity"
"actions":
  - "desc": "The abbot makes two Sanguine Blade attacks. He can replace one attack\
      \ with a use of Blood Call."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 11 (1d10 + 6) Slashing damage\
      \ plus 7 (2d6) Necrotic damage."
    "name": "Sanguine Blade"
  - "desc": "*Constitution Saving Throw:* DC 15, one creature other than a Construct\
      \ or Undead within 30 feet. *Failure:* 7 (2d6) Necrotic damage, and the target's\
      \ <span title=\"Player's Handbook (2024)\">Hit Point</span> maximum is reduced\
      \ by the damage taken. *Success:* Half damage only. *Failure or Success:* The\
      \ abbot regains <span title=\"Player's Handbook (2024)\">Hit Points</span> equal\
      \ to the damage taken. A Humanoid reduced to 0 <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> by this damage and then buried rises the following\
      \ sunset as a [Crimson Clergy](/3-Mechanics/CLI/bestiary/undead/crimson-clergy-crookedmoon24.md)\
      \ under the abbot's control."
    "name": "Blood Call"
  - "desc": "The abbot casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 15):\n\n**At\
      \ will:** Command, Disguise Self (can appear as a Medium Humanoid, 24-hour duration),\
      \ Thaumaturgy\n\n**1/day:** Word of Recall (to lair only)"
    "name": "Spellcasting"
"reactions":
  - "desc": "Trigger: The abbot is hit by an attack roll while holding a weapon. _Response:_\
      \ The abbot adds 3 to his AC against that attack, possibly causing it to miss."
    "name": "Parry"
"regional_effects":
  - "desc": "The region containing the Crimson Abbot's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Fresh Blood.** Within 1 mile of the\
      \ lair, spilled blood  doesn't dry out or coagulate, instead remaining fresh\
      \ for 24 hours.  \n- **Incinerate Heresy.** Within 1 mile of the lair, when\
      \ an enemy of the abbot's takes Fire damage, that creature starts burning until\
      \ the end of its next turn.  \n\nIf the Crimson Abbot dies or moves his lair\
      \ elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The abbot moves up to half his <span title=\"Player's Handbook (2024)\"\
      >Speed</span> and makes one Sanguine Blade attack."
    "name": "Bloody Strike"
  - "desc": "*Wisdom Saving Throw:* DC 15, one creature within 60 feet. *Failure:*\
      \ The target has the Frightened condition and repeats the saving throw at the\
      \ end of each of its turns, ending the effect on itself on a success.\n\nAfter\
      \ 1 minute, it succeeds automatically."
    "name": "Castigate"
  - "desc": "The abbot casts Command. He can't take this action again until the start\
      \ of his next turn."
    "name": "Overwhelm"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Crimson%20Abbot.webp"
```
^statblock

## Environment

hill, mountain, urban