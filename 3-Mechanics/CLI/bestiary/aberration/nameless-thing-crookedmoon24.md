---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Nameless Thing
---
# [Nameless Thing](3-Mechanics\CLI\bestiary\aberration/nameless-thing-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 590*  

---

*Unknowable Lifeform from Beyond (Meteorite fragments)*

---

Nameless things are alien minds bound into physical vessels, most often diminutive animals, objects, or pieces of monsters. These creatures can creep into the world when outer influence seeps into existence but are usually deliberately invited.

```statblock
"name": "Nameless Thing (CrookedMoon24)"
"size": "Tiny"
"type": "aberration"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "17"
"hit_dice": "5d4 + 5"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "12"
  - !!int "16"
  - !!int "10"
  - !!int "9"
"speed": "10 ft., fly 40 ft. (hover)"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft., passive Perception\
  \ 12"
"languages": "Deep Speech; telepathy 30 ft."
"cr": "1"
"traits":
  - "desc": "The nameless thing doesn't provoke an Opportunity Attack when it flies\
      \ out of an enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 9 (1d12 + 3) Psychic damage,\
      \ and if the target is a creature, it has the Frightened condition until the\
      \ start of the nameless thing's next turn."
    "name": "Psychic Strike"
  - "desc": "The nameless thing casts Invisibility on itself, requiring no spell components\
      \ and using Intelligence as the spellcasting ability.\n\nWhen it casts the spell,\
      \ the nameless thing can extend the effect of the spell to a creature it is\
      \ touching. The spell ends early if either creature breaks the spell on itself\
      \ or if the nameless thing stops touching the other creature. Once the nameless\
      \ thing extends the spell in this way, it can't do so again until it finishes\
      \ a <span title=\"Player's Handbook (2024)\">Long Rest</span>.\n"
    "name": "Invisibility"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Nameless%20Thing.webp"
```
^statblock

## Environment

any