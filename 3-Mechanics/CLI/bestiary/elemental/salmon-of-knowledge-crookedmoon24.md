---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/planar-elemental-plane-of-water
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Salmon of Knowledge
---
# [Salmon of Knowledge](3-Mechanics\CLI\bestiary\elemental/salmon-of-knowledge-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 592*  

---

*Elemental Font of Wisdom (Crushed opal)*

---

Legends speak of the salmon of knowledge—shimmering fish said to embody the wisdom of the ages. Their scales gleam with an iridescent light, and they are forever enveloped in a sphere of gently flowing water that defies gravity. This magical orb is said to carry the essence of the sacred Current of Wisdom—where knowledge of all time and space flows through the rivers of the cosmos.

```statblock
"name": "Salmon of Knowledge (CrookedMoon24)"
"size": "Tiny"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "25"
"hit_dice": "10d4"
"modifier": !!int "3"
"stats":
  - !!int "5"
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "18"
  - !!int "10"
"speed": "5 ft., fly 30 ft. (hover; Orb of Water Only), swim 30 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+6"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "fire (Orb of Water only); psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 16"
"languages": "understands all but can't speak; telepathy 60 ft."
"cr": "1"
"traits":
  - "desc": "The salmon is surrounded by a sphere of flowing water that moves with\
      \ it. While inside of the sphere, the salmon has <span title=\"Player's Handbook\
      \ (2024)\">Resistance</span> to Fire damage. A creature that grapples the salmon\
      \ can choose to pull it out of the orb of water. The orb of water moves up to\
      \ 20 feet toward the salmon at the start of each of the salmon's turns. If it\
      \ enters the salmon's space, the Grappled condition ends on the salmon."
    "name": "Orb of Water"
  - "desc": "The salmon can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "The salmon makes two Water Spray attacks. It can replace one attack with\
      \ a use of Prophetic Guidance."
    "name": "Multiattack"
  - "desc": "*Ranged Attack Roll:* +5, range 20/60 ft. *Hit:* 6 (1d6 + 3) Cold damage."
    "name": "Water Spray"
  - "desc": "A creature the salmon can see within 30 feet gains a flash of foresight.\
      \ Once in the next minute, when the creature fails a <span title=\"Player's\
      \ Handbook (2024)\">D20 Test</span>, it can roll 1d4 and add it to the total,\
      \ potentially turning the failure into a success."
    "name": "Prophetic Guidance (2/Day)"
"reactions":
  - "desc": "Trigger: A creature within 5 feet makes an Intelligence or Wisdom check.\
      \ _Response:_ The creature can use the salmon's Wisdom modifier (+4) in place\
      \ of its own ability modifier for the check."
    "name": "Echo from the Current"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Salmon%20of%20Knowledge.webp"
```
^statblock

## Environment

coastal, planar (elemental plane of water), underwater