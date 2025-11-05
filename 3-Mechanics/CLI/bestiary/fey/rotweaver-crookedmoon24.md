---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Rotweaver
---
# [Rotweaver](3-Mechanics\CLI\bestiary\fey/rotweaver-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 528*  

---

*Fey Thrall of Rot*

---

Rotweavers were Fey caretakers of the natural world or fey planes who've been corrupted by the power of rot. Rotweavers serve powerful beings of withering and blight as minor acolytes and hunters, working to spread the bounds of their beloved decay.

## Secret

The rotweavers' fey nature still holds; binding them with iron, such as manacles or a chain, mutes their strength.

```statblock
"name": "Rotweaver (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "15"
  - !!int "13"
  - !!int "10"
  - !!int "16"
  - !!int "8"
"speed": "40 ft."
"damage_immunities": "necrotic, poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": "Common, Sylvan"
"cr": "1"
"traits":
  - "desc": "The rotweaver ignores <span title=\"Player's Handbook (2024)\">Difficult\
      \ Terrain</span> caused by plants or fungi."
    "name": "Fungal Step"
  - "desc": "The rotweaver carries a hunting horn.\n\nThe horn has AC 16, HP 10, and\
      \ <span title=\"Player's Handbook (2024)\">Immunity</span> to Necrotic, Poison,\
      \ and Psychic damage."
    "name": "Hunting Horn"
  - "desc": "If the rotweaver has iron wrapped around a part of its body, such as\
      \ an iron bracelet, Manacles, or Chain (treat any of them as applying Manacles),\
      \ the rotweaver can move, take an action, or a <span title=\"Player's Handbook\
      \ (2024)\">Bonus Action</span>, but not all three."
    "name": "Iron Binding"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Necrotic damage."
    "name": "Staff"
  - "desc": "*Constitution Saving Throw:* DC 13, each creature in a 30-foot <span\
      \ title=\"Player's Handbook (2024)\">Cone</span>. *Failure:* 11 (2d10) Necrotic\
      \ damage, and the target has the Poisoned condition until the end of its next\
      \ turn. *Success:* Half damage only. *Failure or Success:* The horn call is\
      \ audible out to 300 feet, and any noncreature plants in the <span title=\"\
      Player's Handbook (2024)\">Cone</span> die from fungus and rot."
    "name": "Call the Rot (Requires Hunting Horn; Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Rotweaver.webp"
```
^statblock

## Environment

forest, planar (fey), swamp