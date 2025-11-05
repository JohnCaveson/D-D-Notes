---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey/druid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Keeper of the Blight
---
# [Keeper of the Blight](3-Mechanics\CLI\bestiary\fey/keeper-of-the-blight-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 512*  

---

*Druid Transformed by Blight*

---

Keepers of the blight arise from Fey beings that dwell in a natural region that becomes overtaken by a supernatural or spiritual rot. Where they once tended the balance and cycles of their home, keepers are consumed by the blight and channel their magic through fungus, mold, and rot, pushing the cycle of life toward death, decay, and the flourishing of things that thrive in gloom.

## Secret

The fungus growing throughout keepers of the blight empowers and sustains them, and killing that growth diminishes their power.

```statblock
"name": "Keeper of the Blight (CrookedMoon24)"
"size": "Large"
"type": "fey"
"subtype": "Druid"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "97"
"hit_dice": "13d10 + 26"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "16"
  - !!int "14"
  - !!int "11"
  - !!int "20"
  - !!int "12"
"speed": "50 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": "Common, Sylvan"
"cr": "6"
"traits":
  - "desc": "If the keeper is targeted by an effect that ends the Poisoned condition,\
      \ it takes 10 (3d6) Force damage and has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on <span title=\"Player's Handbook (2024)\">D20 Tests</span>\
      \ until the end of its next turn."
    "name": "Blight Dependent"
  - "desc": "The keeper ignores <span title=\"Player's Handbook (2024)\">Difficult\
      \ Terrain</span> caused by plants or fungi."
    "name": "Fungal Step"
"actions":
  - "desc": "The keeper makes two attacks, using Blight Staff or Spore Spray in any\
      \ combination, and it uses Rotting Ritual."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 9 (1d8 + 5) Bludgeoning damage\
      \ plus 7 (2d6) Necrotic damage."
    "name": "Blight Staff"
  - "desc": "*Ranged Attack Roll:* +8, range 60 ft. *Hit:* 9 (2d8) Poison damage.\
      \ If the target is a creature, it has the Poisoned condition until the end of\
      \ the keeper's next turn."
    "name": "Spore Spray"
  - "desc": "The keeper magically creates one of the following effects of its choice.\
      \ It can't use the same effect twice in a row."
    "name": "Rotting Ritual"
  - "desc": "*Wisdom Saving Throw:* DC 16, a creature the keeper can see within 30\
      \ feet. *Failure:* 10 (3d6) Psychic damage, and the target must immediately\
      \ take a <span title=\"Player's Handbook (2024)\">Reaction</span> to make a\
      \ melee or ranged attack against a creature of the keeper's choice that is within\
      \ reach or range of the attack. *Success:* Half damage only."
    "name": "Frenzying Spores"
  - "desc": "The keeper magically summons a Rotweaver (lacks a Hunting Horn) in an\
      \ unoccupied space within 30 feet of itself. The rotweaver takes its turn immediately\
      \ after the keeper on the same <span title=\"Player's Handbook (2024)\">Initiative</span>\
      \ count, and it obeys the keeper. The rotweaver vanishes after 1 minute, or\
      \ when it or the keeper dies."
    "name": "Blight Spawn"
  - "desc": "Life-sapping fungus sprouts from the ground in a 60-foot radius centered\
      \ on the keeper.\n\nThe area is <span title=\"Player's Handbook (2024)\">Difficult\
      \ Terrain</span>, and a creature has the Poisoned condition while within the\
      \ area. The fungus remains for 1 minute, until the keeper uses this effect again,\
      \ or until it dies."
    "name": "Devouring Fungus"
  - "desc": "The keeper casts one of the following spells, requiring no Material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 16, +8 to hit\
      \ with spell attacks):\n\n**At will:** Druidcraft, Ray of Sickness\n\n**1/day:**\
      \ Blight"
    "name": "Spellcasting"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Keeper%20of%20the%20Blight.webp"
```
^statblock

## Environment

forest, swamp, underground