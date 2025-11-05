---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/planar-shadow
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lurker in the Dark
---
# [Lurker in the Dark](3-Mechanics\CLI\bestiary\fey/lurker-in-the-dark-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 515*  

---

*Thing That Goes Bump in the Night*

---

Lurkers in the dark are wicked Fey creatures who prey upon the fearful, vulnerable, and alone. They resemble nightmarishly distorted people with gray skin, lank hair, and three-fingered, clawed hands. Their limbs move in impossible ways, allowing them to slip through and hide within spaces that seem far too small. They delight in stoking their victim's fears by whispering from spaces a person couldn't fit. When the terror crests, the lurkers strike, drag their victims into the dark, and vanish with them.

## Secret

Frightened children know that lurkers in the dark can be held at bay by clutching a beloved stuffed animal.

```statblock
"name": "Lurker in the Dark (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "13"
  - !!int "16"
"speed": "30 ft., climb 30 ft."
"saves":
  - "dexterity": !!int "4"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "bludgeoning"
"condition_immunities": "[grappled](/3-Mechanics/CLI/conditions.md#Grappled), [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": "Common plus one other language"
"cr": "4"
"traits":
  - "desc": "The lurker can fit into a space as small as a 1-foot <span title=\"Player's\
      \ Handbook (2024)\">Cube</span> and can pass through a space as narrow as 1\
      \ inch without expending extra movement to do so."
    "name": "Nightmarish Contortion"
  - "desc": "The lurker can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The lurker can't attack or willingly move to a space within 10 feet of\
      \ a creature holding a stuffed animal once owned by a child."
    "name": "Ward of Innocence"
"actions":
  - "desc": "The lurker makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 10 ft. *Hit:* 9 (1d10 + 4) Slashing damage,\
      \ and if the target is a Medium or smaller creature, it has the Grappled condition\
      \ (escape DC 14) from one of two claws. Until the grapple ends, the target has\
      \ the Restrained condition."
    "name": "Claw"
"bonus_actions":
  - "desc": "While the lurker isn't in <span title=\"Player's Handbook (2024)\">Bright\
      \ Light</span>, it teleports up to 120 feet to an unoccupied space it can see.\
      \ If the destination space isn't in <span title=\"Player's Handbook (2024)\"\
      >Bright Light</span>, the lurker doesn't need to see it. A creature the lurker\
      \ is grappling must succeed on a DC 13 Charisma saving throw or teleport with\
      \ the lurker to an unoccupied space closest to the lurker's destination."
    "name": "Dark Teleport"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Lurker%20in%20the%20Dark.webp"
```
^statblock

## Environment

planar (shadow), urban