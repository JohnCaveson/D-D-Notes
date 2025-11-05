---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Deepdreck
---
# [Deepdreck](3-Mechanics\CLI\bestiary\monstrosity/deepdreck-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 498*  

---

*Poisoned Subterranean Wretch*

---

Deepdrecks were miners long ago who found themselves far too deep beneath the earth, where they were cursed and corrupted by deforming powers. Now they tunnel and dig greedily, bloated with poisonous gases.

Astute observers have noted that these monsters occasionally bear a resemblance to missing loved ones who have long been thought dead.

## Secret

The toxic essence of deepdrecks is disrupted by pleasant scents such as flowers, perfume, spices, or incense.

```statblock
"name": "Deepdreck (CrookedMoon24)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "9"
  - !!int "12"
  - !!int "6"
"speed": "40 ft., burrow 40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., tremorsense\
  \ 120 ft., passive Perception 13"
"languages": "Common plus one other language"
"cr": "4"
"traits":
  - "desc": "The deepdreck explodes when it dies. *Dexterity Saving Throw:* DC 14,\
      \ each creature in a 15-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the deepdreck. *Failure:* 13 (3d8) Poison damage. *Success:*\
      \ Half damage."
    "name": "Explosive Death"
  - "desc": "The deepdreck has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on attack rolls and saving throws while within 10 feet of burning incense\
      \ or a creature wearing Perfume."
    "name": "Fragrance Aversion"
  - "desc": "The deepdreck can burrow through solid rock at half its <span title=\"\
      Player's Handbook (2024)\">Burrow Speed</span> and leaves a 5-foot-diameter\
      \ tunnel in its wake."
    "name": "Tunneler"
"actions":
  - "desc": "The deepdreck makes two attacks, using Claw or Putrid Emission in any\
      \ combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing damage\
      \ plus 7 (2d6) Poison damage."
    "name": "Claw"
  - "desc": "*Ranged Attack Roll:* +6, range 60 ft. *Hit:* 8 (1d8 + 4) Poison damage,\
      \ and the target has the Poisoned condition until the start of the deepdreck's\
      \ next turn."
    "name": "Putrid Emission"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Deepdreck.webp"
```
^statblock

## Environment

underground