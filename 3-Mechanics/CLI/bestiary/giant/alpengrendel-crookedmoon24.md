---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/arctic
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Alpengrendel
---
# [Alpengrendel](3-Mechanics\CLI\bestiary\giant/alpengrendel-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 487*  

---

*Brute Born of Mountain Ice*

---

Alpengrendel are hulking creatures covered in bluish white fur, with great tusks and horns. They were born of the ice and darkness of their mountaintop homes, shaped by the unseen hands of a deity of cold stone and gloam. The bitter cold of the mountain peaks infuses both their touch and their breath. Alpengrendel draw upon the timelessness of the mountains, healing from otherwise lethal wounds in the blink of an eye. They fear only the power of lightning, which can slay them, and the power of the gods, whom they bitterly resent.

## Secret

Their disdain for deities runs so deep that alpengrendel are enraged and unnerved by the trappings of faith.

```statblock
"name": "Alpengrendel (CrookedMoon24)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "85"
"hit_dice": "9d10 + 36"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "18"
  - !!int "9"
  - !!int "14"
  - !!int "10"
"speed": "40 ft., climb 40 ft."
"saves":
  - "dexterity": !!int "4"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+5"
"damage_resistances": "fire"
"damage_immunities": "cold"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": "Common, giant"
"cr": "6"
"traits":
  - "desc": "The alpengrendel has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on attack rolls while in a consecrated area or on attack rolls against a creature\
      \ holding or wearing a Holy Symbol."
    "name": "Aversion to Faith"
  - "desc": "The alpengrendel regains 10 <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span> at the start of each of its turns. If the alpengrendel takes\
      \ Acid or Lightning damage, this trait doesn't function at the start of its\
      \ next turn. The alpengrendel dies only if it starts its turn with 0 <span title=\"\
      Player's Handbook (2024)\">Hit Points</span> and doesn't regenerate."
    "name": "Regeneration"
"actions":
  - "desc": "The alpengrendel makes one Claws attack and one Tusks attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing damage\
      \ plus 5 (1d10) Cold damage."
    "name": "Claws"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 9 (1d8 + 5) Piercing damage\
      \ plus 5 (1d10) Cold damage. If the target is a Medium or smaller creature,\
      \ it has the Prone condition."
    "name": "Tusks"
  - "desc": "*Constitution Saving Throw:* DC 15, each creature in a 30-foot <span\
      \ title=\"Player's Handbook (2024)\">Cone</span>. *Failure:* 21 (6d6) Cold damage.\
      \ Until the start of the alpengrendel's next turn, the target's <span title=\"\
      Player's Handbook (2024)\">Speed</span> is halved, and it has <span title=\"\
      Player's Handbook (2024)\">Disadvantage</span> on attack rolls. *Success:* Half\
      \ damage only."
    "name": "Frost Breath (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Alpengrendel.webp"
```
^statblock

## Environment

arctic, mountain