---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Weeping Widow
---
# [The Weeping Widow](3-Mechanics\CLI\bestiary\npc/the-weeping-widow-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 572*  

---

*Matron of Malevolent Medicine*

---

Once a priestess committed to healing the sick through divine rites, the Weeping Widow abandoned the gods after a personal tragedy and turned to sinister science. Believing she knows how to best treat the suffering and make them stronger, she employs a harrowing regimen of alchemical and medical experimentation to wipe minds and alter bodies, whether the patient wants the treatment or not.

## Secret

The only way to force the Weeping Widow to live up to her moniker is to remind her of the family she lost, such as her husband's sword or portrait, which forces her to confront what she has become.

## Weeping Widow's Lair

The Weeping Widow's lair is the sanitorium where she conducts her horrific experiments.

```statblock
"name": "The Weeping Widow (CrookedMoon24)"
"size": "Medium"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "15"
"hp": !!int "104"
"hit_dice": "19d8 + 19"
"modifier": !!int "8"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "20"
  - !!int "16"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+8"
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+9"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+8"
"damage_resistances": "poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": "Common, Elvish, Giant; telepathy 120 ft."
"cr": "8"
"traits":
  - "desc": "If the widow fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "At the start of her turn, if the widow can see a memento of her husband\
      \ or some other reminder that forces her to realize what she's lost, she has\
      \ <span title=\"Player's Handbook (2024)\">Disadvantage</span> on <span title=\"\
      Player's Handbook (2024)\">D20 Tests</span> and can only expend 2 uses of her\
      \ Legendary Actions until the start of her next turn."
    "name": "Reopened Memories"
"actions":
  - "desc": "The widow makes two Injection attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +8, reach 5 ft. or range 60 ft. *Hit:*\
      \ 1 Piercing damage plus 10 (3d6) Poison damage. If the target is a creature,\
      \ it has the Poisoned condition until the end of its next turn. While Poisoned,\
      \ the target suffers one of the following effects of the widow's choice (each\
      \ option can only be used once per turn):\n\n- **Hyperphobic Stimulant.** The\
      \ target has the Frightened condition. At the start of its turn, the target\
      \ must succeed on a DC 16 Wisdom saving throw or take the Dash action and move\
      \ away from the widow by the safest and shortest available route, unless there\
      \ is nowhere to move.  \n- **Soporific Infusion.** *Constitution Saving Throw:*\
      \ DC 16, the target hit by Injection. *Failure:* The target's <span title=\"\
      Player's Handbook (2024)\">Speed</span> is halved. On its turn, it can take\
      \ either an action or a <span title=\"Player's Handbook (2024)\">Bonus Action</span>,\
      \ but not both, and it can make only one attack if it takes the Attack action.\
      \ Failure by 5 or More: The target has the Unconscious condition for 1 minute,\
      \ until it takes damage, or until a creature takes an action to shake it awake.\
      \  \n- **Thaumaturgic Inhibitor.** If the target casts a spell, it must succeed\
      \ on a DC 16 Constitution saving throw or the spell fails, but a spell slot\
      \ used to cast the spell isn't expended.  "
    "name": "Injection"
"regional_effects":
  - "desc": "The region containing the Weeping Widow's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Dulled Memories.** Within 1 mile of\
      \ the lair, creatures have <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on Intelligence checks made to recall information related to painful or emotional\
      \ memories.  \n- **Faded Dreams.** Within 1 mile of the lair, creatures who\
      \ sleep or Trance have only vague impressions of dreams and recall no details.\
      \  \n\nIf the Weeping Widow dies or moves her lair elsewhere, these effects\
      \ end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The widow or a creature she is riding moves up to half its <span title=\"\
      Player's Handbook (2024)\">Speed</span> without provoking Opportunity Attacks.\
      \ Dose. The widow makes one Injection attack. She can't take this action again\
      \ until the start of her next turn."
    "name": "Alacrity"
  - "desc": "The widow targets herself or an ally within 5 feet and grants the target\
      \ one of the following effects of her choice; she can't take this action again\
      \ until the start of her next turn:\n\n- **Aggression.** The target has <span\
      \ title=\"Player's Handbook (2024)\">Advantage</span> on attack rolls until\
      \ the end of its next turn.  \n- **Fortitude.** One of the following conditions\
      \ of the widow's choice ends on the target: Charmed, Frightened, Grappled, Paralyzed,\
      \ Poisoned, Restrained, Stunned.  \n- **Vigor.** The target regains 10 <span\
      \ title=\"Player's Handbook (2024)\">Hit Points</span>.  "
    "name": "Hypertrophic Injections"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Weeping%20Widow.webp"
```
^statblock

## Environment

underground, urban