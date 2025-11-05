---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Phantom Hearse
---
# [Phantom Hearse](3-Mechanics\CLI\bestiary\undead/phantom-hearse-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 521*  

---

*Ghostly Coach of the Dead*

---

Phantom hearses are ghostly carriages complete with horses and coachmen—amalgamations of tormented souls driven to claim the living and drag them to the land of the dead.

The spirit coachmen strike with phantom whips and weapons, and even fly out to harry foes at a distance, while the ghostly horses drive the hearse in a crushing charge that gathers victims and seals them into a spectral coffin that drains the warmth and vitality from flesh and bone. The tolling bell on the carriage precedes the apparition's appearance, and its sepulchral sound has caused more than a few witnesses to drop dead on the spot.

## Secret

Phantom hearses are driven to collect the living, and they can't see a living creature that holds its breath.

```statblock
"name": "Phantom Hearse (CrookedMoon24)"
"size": "Huge"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "110"
"hit_dice": "13d12 + 26"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "15"
  - !!int "14"
  - !!int "3"
  - !!int "12"
  - !!int "18"
"speed": "60 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"damage_resistances": "acid, bludgeoning, cold, fire, lightning, piercing, slashing,\
  \ thunder"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": "Common plus one other language"
"cr": "9"
"traits":
  - "desc": "A creature holding its breath has the Invisible condition to the hearse.\
      \ If the creature takes damage while holding its breath, it must succeed on\
      \ a DC 15 Constitution saving throw or let out its breath and become visible\
      \ to the hearse until the start of the creature's next turn, when it can hold\
      \ its breath again."
    "name": "Breathless Warding"
  - "desc": "The hearse can move through other creatures and objects as if they were\
      \ difficult terrain. It takes 5 (1d10) Force damage if it ends its turn inside\
      \ an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "The hearse makes two Ghostly Coachman attacks. It can replace one of\
      \ the attacks with a use of Trample, if available."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +8, reach 10 ft. or range 60 ft. *Hit:*\
      \ 13 (2d8 + 4) Cold damage. If the target is a creature, it can't regain <span\
      \ title=\"Player's Handbook (2024)\">Hit Points</span> until the start of the\
      \ hearse's next turn."
    "name": "Ghostly Coachman"
  - "desc": "The hearse moves in a straight line up to its <span title=\"Player's\
      \ Handbook (2024)\">Speed</span>. *Dexterity Saving Throw:* DC 16, each creature\
      \ whose space the hearse enters during this action. *Failure:* 10 (3d6) Cold\
      \ damage. If the target is Medium or smaller, it has the Grappled condition\
      \ (escape DC 14), and it has the Restrained condition until the grapple ends.\
      \ *Success:* Half damage only."
    "name": "Trample (Recharge 5-6)"
  - "desc": "*Wisdom Saving Throw:* DC 16, each creature of the hearse's choice that\
      \ it can see in a 30-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the hearse. *Failure:* 44 (8d10) Psychic damage, and the\
      \ creature's <span title=\"Player's Handbook (2024)\">Speed</span> is halved\
      \ until the start of the hearse's next turn. *Success:* Half damage only."
    "name": "Tolling Bell (1/Day)"
"bonus_actions":
  - "desc": "*Strength Saving Throw:* DC 16, one creature Grappled by the hearse (it\
      \ can have up to three creatures entombed at a time). *Failure:* The target\
      \ is entombed in a coffin in the hearse, and the Grappled condition ends.\n\n\
      An entombed target has the Blinded and Restrained conditions, has <span title=\"\
      Player's Handbook (2024)\">Total Cover</span> against attacks and other effects\
      \ outside the hearse, and at the start of each of the hearse's turns it takes\
      \ 21 (6d6) Necrotic damage and gains 1 Exhaustion level.\n\nIf the hearse takes\
      \ 20 damage or more on a single turn from a creature inside a coffin, the hearse\
      \ must succeed on a DC 12 Constitution saving throw at the end of that turn\
      \ or release all entombed creatures, each of which falls in a space within 5\
      \ feet of the hearse and has the Prone condition. If the hearse dies, any entombed\
      \ creature falls to the ground with the Prone condition in the hearse's former\
      \ space."
    "name": "Entomb"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Phantom%20Hearse.webp"
```
^statblock

## Environment

any