---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Jinxed Leviathan
---
# [The Jinxed Leviathan](3-Mechanics\CLI\bestiary\npc/the-jinxed-leviathan-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 564*  

---

*Curse-Wrought Swamp Monster*

---

Once a normal alligator that dwelled in a cursed swamp, the Jinxed Leviathan was warped by the strange hexes and twisted spells of nefarious magicians who sought to defeat the deathly spirit known as Snake Eye Jack. Growing to colossal proportions and infusing with the essence of misfortune itself, the Monstrosity could not be controlled and devoured its makers. Now, it lurks in the still, black water of hexed bayous, always seeking its next meal, upon which it unleashes its jinxcraft before feasting.

## Secret

An idol of the fabled deal maker Snake Eye Jack that has been blessed by one of Jack's followers can turn the Jinxed Leviathan's own cursed power against it.

## Jinxed Leviathan's Lair

The Jinxed Leviathan's lair is a cursed swamp steeped in confounding magic.

```statblock
"name": "The Jinxed Leviathan (CrookedMoon24)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "21"
"hp": !!int "437"
"hit_dice": "25d20 + 175"
"modifier": !!int "16"
"stats":
  - !!int "30"
  - !!int "14"
  - !!int "25"
  - !!int "6"
  - !!int "12"
  - !!int "21"
"speed": "40 ft., swim 80 ft."
"saves":
  - "strength": !!int "17"
  - "wisdom": !!int "8"
  - "constitution": !!int "14"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "force, necrotic"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 18"
"languages": "understands Draconic but can't speak"
"cr": "23"
"traits":
  - "desc": "The leviathan can breathe air and water."
    "name": "Amphibious"
  - "desc": "If the leviathan fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
  - "desc": "If the leviathan curses a creature holding an idol of Snake Eye Jack\
      \ blessed by one of his devoted followers, the creature is unaffected by the\
      \ curse. The leviathan then takes 20 Radiant damage and has <span title=\"Player's\
      \ Handbook (2024)\">Disadvantage</span> on <span title=\"Player's Handbook (2024)\"\
      >D20 Tests</span> until the end of its next turn."
    "name": "Returned Curse"
"actions":
  - "desc": "The leviathan makes one Bite attack and one Tail attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +17, reach 15 ft. *Hit:* 23 (2d12 + 10) Piercing\
      \ damage plus 13 (3d8) Force damage. The target has the Grappled condition (escape\
      \ DC 20), and until the grapple ends, the target has the Restrained condition."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +17, reach 20 ft. *Hit:* 23 (3d8 + 10) Bludgeoning\
      \ damage, and if the target is a Huge or smaller creature, it has the Prone\
      \ condition and is pushed up to 20 feet straight away from the leviathan."
    "name": "Tail"
  - "desc": "*Dexterity Saving Throw:* DC 22, each creature in a 120-foot-long, 10-foot-wide\
      \ <span title=\"Player's Handbook (2024)\">Line</span>. *Failure:* 78 (12d12)\
      \ Necrotic damage, and the target is cursed. The cursed target has <span title=\"\
      Player's Handbook (2024)\">Disadvantage</span> on <span title=\"Player's Handbook\
      \ (2024)\">D20 Tests</span> and can't regain <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span>. The target can end the curse early if it voluntarily\
      \ fails a saving throw forced by one of its enemies. *Success:* Half damage\
      \ only."
    "name": "Accursed Breath (Recharge 5-6)"
  - "desc": "*Dexterity Saving Throw:* DC 25, one Large or smaller creature Grappled\
      \ by the leviathan (it can have up to four creatures swallowed at a time). *Failure:*\
      \ The target is swallowed and no longer Grappled. A swallowed creature has the\
      \ Blinded and Restrained conditions, has <span title=\"Player's Handbook (2024)\"\
      >Total Cover</span> against attacks and other effects outside the leviathan,\
      \ and takes 24 (7d6) Force damage at the start of each of its turns.\n\nIf the\
      \ leviathan takes 50 damage or more on a single turn from a creature inside\
      \ it, the leviathan must succeed on a DC 25 Constitution saving throw at the\
      \ end of that turn or regurgitate all swallowed creatures, each of which falls\
      \ in a space within 10 feet of the leviathan and has the Prone condition. If\
      \ the leviathan dies, any swallowed creature no longer has the Restrained condition\
      \ and can escape from the corpse using 15 feet of movement, exiting Prone."
    "name": "Swallow"
"reactions":
  - "desc": "Trigger: A creature within 60 feet of the leviathan hits it with an attack\
      \ roll or targets it with a spell. _Response:_ The triggering creature must\
      \ succeed on a DC 20 Wisdom saving throw or become cursed until the end of its\
      \ next turn. The cursed creature has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on <span title=\"Player's Handbook (2024)\">D20 Tests</span>\
      \ and can't regain <span title=\"Player's Handbook (2024)\">Hit Points</span>."
    "name": "Jinxed Hide"
"regional_effects":
  - "desc": "The region containing the Jinxed Leviathan's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Hanging Hex.** Within 1 mile of the\
      \ lair, when a creature other than the Jinxed Leviathan rolls a 1 or a 20 on\
      \ a <span title=\"Player's Handbook (2024)\">D20 Test</span>, the next <span\
      \ title=\"Player's Handbook (2024)\">D20 Test</span> the creature makes has\
      \ <span title=\"Player's Handbook (2024)\">Disadvantage</span>, and it can't\
      \ have <span title=\"Player's Handbook (2024)\">Advantage</span>.  \n- **Murky\
      \ Waters.** Within 1 mile of the lair, swamp water is cloudy and shows fleeting\
      \ faces in the murk. Creatures in the water have <span title=\"Player's Handbook\
      \ (2024)\">Advantage</span> on Dexterity (Stealth) checks.  \n\nIf the Jinxed\
      \ Leviathan dies or moves its lair elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, The can expend a use to take one of the following actions.\
  \ The regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The leviathan uses Swallow."
    "name": "Devour"
  - "desc": "The leviathan causes a swell of muddy water and grasping roots. *Strength\
      \ Saving Throw:* DC 20, each creature in a 20-foot <span title=\"Player's Handbook\
      \ (2024)\">Emanation</span> originating from the leviathan. *Failure:* 21 (6d6)\
      \ Bludgeoning damage, and the target's <span title=\"Player's Handbook (2024)\"\
      >Speed</span> is 0 until the end of its next turn. *Success:* Half damage only.\
      \ *Failure or Success:* The leviathan can't take this action again until the\
      \ start of its next turn."
    "name": "Swamp Surge"
  - "desc": "The leviathan moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span> without provoking Opportunity Attacks and makes one Tail attack."
    "name": "Tail Sweep"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Jinxed%20Leviathan.webp"
```
^statblock

## Environment

coastal, swamp