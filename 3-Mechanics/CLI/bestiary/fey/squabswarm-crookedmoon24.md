---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Squabswarm
---
# [Squabswarm](3-Mechanics\CLI\bestiary\fey/squabswarm-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 533*  

---

*Peeping Fey Pigeons*

---

Fey messengers that take the form of pigeons can gather into flocks, or squabswarms. Hags and other influential Fey use squabswarms as spies and messengers—and sometimes as unerring trackers to locate any who flee responsibility or judgement.

## Secret

Squabswarms' drive to deliver letters or parcels is overwhelming, and they can be confused by delivery requests.

```statblock
"name": "Squabswarm (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "14"
  - !!int "5"
  - !!int "13"
  - !!int "8"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+5"
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": "understands Common and Sylvan but can't speak"
"cr": "1/2"
"traits":
  - "desc": "As an Influence action, a creature can direct the swarm to deliver a\
      \ letter or parcel (which the creature must provide) to a recipient the creature\
      \ knows. The swarm has the Charmed condition until it delivers the item to the\
      \ specified recipient or until it takes damage. While Charmed in this way, the\
      \ swarm must deliver the item to the specified recipient if it knows where the\
      \ recipient is."
    "name": "Compelled Delivery"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny pigeon. The swarm\
      \ can't regain <span title=\"Player's Handbook (2024)\">Hit Points</span> or\
      \ gain <span title=\"Player's Handbook (2024)\">Temporary Hit Points</span>."
    "name": "Swarm"
  - "desc": "If the swarm is tasked to deliver an item to a creature, the swarm knows\
      \ the distance and direction to the creature while they are on the same plane."
    "name": "Unerring Delivery"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (2d4) Piercing damage,\
      \ or 2 (1d4) Piercing damage if the swarm is Bloodied. If the swarm isn't Bloodied\
      \ and the target is a creature, the target has the Charmed condition until the\
      \ start of the swarm's next turn."
    "name": "Peck"
"reactions":
  - "desc": "Trigger: A creature who tasked the swarm to deliver an item and is on\
      \ the same plane as the swarm takes an action to see through the swarm. _Response:_\
      \ The swarm becomes a scrying sensor as if the creature cast Scrying. For the\
      \ duration, the creature can speak through the swarm."
    "name": "Many Eyes, One Voice (1/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Squabswarm.webp"
```
^statblock

## Environment

mountain, planar (fey), urban