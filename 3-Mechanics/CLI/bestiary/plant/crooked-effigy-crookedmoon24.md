---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Crooked Effigy
---
# [Crooked Effigy](3-Mechanics\CLI\bestiary\plant/crooked-effigy-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 495*  

---

*Splinter of Crooked Power*

---

Crooked effigies are servants of a twisted archfey known as the Crooked Queen. They are made of gnarled wood and show some bipedal and feminine features in their queen's image. Crooked effigies impale their enemies with their branch-like arms and drag foes in close, where the thorns on their bodies carry the sting of a victim's own corruption.

## Secret

Crooked effigies are bound to the Old Ways, and they recoil from the tools of forging and tinkering—symbols of a growing civilization.

```statblock
"name": "Crooked Effigy (CrookedMoon24)"
"size": "Medium"
"type": "plant"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "13"
  - !!int "16"
  - !!int "9"
  - !!int "16"
  - !!int "9"
"speed": "30 ft."
"saves":
  - "strength": !!int "5"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+5"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 15"
"languages": "Common, Sylvan"
"cr": "2"
"traits":
  - "desc": "At the start of each of its turns, the effigy deals 5 (1d10) Psychic\
      \ damage to any creature it is grappling or any creature grappling it."
    "name": "Crooked Thorns"
  - "desc": "The effigy takes an extra 10 Force damage if it's hit by an attack roll\
      \ using Smith's Tools or Tinker's Tools (treat as a Club or Light Hammer)."
    "name": "Old Bindings"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Piercing damage.\
      \ If the target is a Medium or smaller creature, it has the Grappled condition\
      \ (escape DC 13) from one of two branch arms. Until the grapple ends, the target\
      \ has the Restrained condition."
    "name": "Impale"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Crooked%20Effigy.webp"
```
^statblock

## Environment

forest, planar (fey)