---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Boogleswarm
---
# [Boogleswarm](3-Mechanics\CLI\bestiary\fey/boogleswarm-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 491*  

---

*Tricksy Fey Weasels*

---

Boogleswarms are mischievous Fey spirits that take the form of weasels gathered into a slinking mob. These spirits covet and collect teeth of all kinds, but they favor the teeth of Humanoids most of all. Tales of tooth faeries might have their origin in boogleswarms, as  they are known to enter into agreements to trade for teeth—such as those lost by children and tucked under a pillow—for rewards, favors, or safety.

## Secret

Boogleswarms go wild for sugar, whether pure or in heavily-sweetened foods like candy, and are compelled to take and consume any they find.

```statblock
"name": "Boogleswarm (CrookedMoon24)"
"size": "Large"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "5d10"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "understands Common but can only speak if the swarm has gathered at least\
  \ one Humanoid tooth"
"cr": "2"
"traits":
  - "desc": "The swarm can speak in the voice of a creature whose tooth it has implanted\
      \ (see the Bite action). Listeners must succeed on a DC 13 Wisdom (Insight)\
      \ check to discern the mimicry."
    "name": "Mimicry (Only if the Swarm Can Speak)"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny weasel. The swarm\
      \ can't regain <span title=\"Player's Handbook (2024)\">Hit Points</span> or\
      \ gain <span title=\"Player's Handbook (2024)\">Temporary Hit Points</span>."
    "name": "Swarm"
  - "desc": "If the swarm can see or smell sugar at the start of its turn, it must\
      \ use all its movement to move closer to the sugar. If it reaches the sugar,\
      \ the swarm has the Incapacitated condition until the start of its next turn\
      \ as it consumes the sugar, and this trait doesn't function again until the\
      \ swarm finishes a <span title=\"Player's Handbook (2024)\">Short</span> or\
      \ <span title=\"Player's Handbook (2024)\">Long Rest</span>."
    "name": "Sweet Tooth"
"actions":
  - "desc": "The swarm makes two Bite attacks that must have different targets."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 10 (4d4) Piercing damage,\
      \ or 5 (2d4) Piercing damage if the swarm is Bloodied. If the target is a creature\
      \ that has teeth, it must succeed on a DC 12 Constitution saving throw or lose\
      \ one of its teeth. The swarm immediately implants the tooth into one of its\
      \ mouths. A creature that has already lost a tooth to this attack automatically\
      \ succeeds on the saving throw."
    "name": "Bite"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Boogle%20Swarm.webp"
```
^statblock

## Environment

forest, planar (fey), urban