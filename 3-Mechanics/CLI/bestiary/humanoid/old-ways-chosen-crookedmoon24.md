---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Old Ways Chosen
---
# [Old Ways Chosen](3-Mechanics\CLI\bestiary\humanoid/old-ways-chosen-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 520*  

---

*Devout Follower of Old Gods*

---

Venerating old and forgotten gods who once held sway over the remote places of the world, the Old Ways chosen keep the last embers of belief and tradition burning. Many of the chosen are insular, keeping to the communities they foster. Some are more open to contact with outsiders, whether to be a beneficent presence or to draw in potential sacrifices to the Old Ways.

## Secret

Old Ways chosen bind their power into a mask they use as a focus. Without the mask, their magic unravels.

```statblock
"name": "Old Ways Chosen (CrookedMoon24)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "13"
  - !!int "8"
  - !!int "18"
  - !!int "16"
"speed": "40 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+6"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+2"
"senses": "passive Perception 14"
"languages": "Common"
"cr": "5"
"traits":
  - "desc": "The chosen wears the mask of an animal, imbuing it with the strength\
      \ of the old gods. When a creature is grappling the chosen, the creature can\
      \ remove the mask as an action, or as an attack during the Attack action, with\
      \ a successful DC 12 Strength (Athletics) check. Without its mask, the chosen\
      \ can't cast spells, its Concentration on any existing spells ends, and the\
      \ save DC of Song of the Old Ways is reduced by 4."
    "name": "Animal Mask"
"actions":
  - "desc": "The chosen makes three <span title=\"Player's Handbook (2024)\">Ritual</span>\
      \ Dagger attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +7, reach 5 ft. or range 20/60 ft. *Hit:*\
      \ 6 (1d4 + 4) Piercing damage plus 7 (2d6) Radiant or Necrotic damage (the chosen's\
      \ choice)."
    "name": "Ritual Dagger"
  - "desc": "The chosen sings one of the following songs:"
    "name": "Songs of the Old Ways (Recharge 5-6)"
  - "desc": "Each creature of the chosen's choice in a 30-foot <span title=\"Player's\
      \ Handbook (2024)\">Emanation</span> originating from the chosen regains 14\
      \ (4d4 + 4) <span title=\"Player's Handbook (2024)\">Hit Points</span>."
    "name": "Blessing of the Harvest"
  - "desc": "*Constitution Saving Throw:* DC 14, one creature within 30 feet. *Failure:*\
      \ 40 (9d8) Necrotic damage, and the target has the Paralyzed condition until\
      \ the end of the chosen's next turn. *Success:* Half damage only."
    "name": "Song of Sacrifice"
  - "desc": "*Dexterity Saving Throw:* DC 14, each creature of the chosen's choice\
      \ in a 20-foot <span title=\"Player's Handbook (2024)\">Emanation</span> originating\
      \ from the chosen. *Failure:* 31 (9d6) Fire damage. *Success:* Half damage."
    "name": "Wicker Chant"
  - "desc": "The chosen casts one of the following spells, requiring no Material components\
      \ other than its Animal Mask and using Wisdom as the spellcasting ability (spell\
      \ save DC 15, +7 to hit with spell attacks):\n\n**At will:** Druidcraft, Minor\
      \ Illusion\n\n**2/day each:** Entangle, Scorching Ray (level 4 version)"
    "name": "Spellcasting (Requires Animal Mask)"
"bonus_actions":
  - "desc": "The chosen casts Jump, using the same spell components and spellcasting\
      \ ability as Spellcasting."
    "name": "Jump (Requires Animal Mask)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Old%20Ways%20Chosen.webp"
```
^statblock

## Environment

any