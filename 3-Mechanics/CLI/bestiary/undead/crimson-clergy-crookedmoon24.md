---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/undead/cleric
- ttrpg-cli/monster/type/undead/vampire
statblock: inline
statblock-link: "#^statblock"
aliases:
- Crimson Clergy
---
# [Crimson Clergy](3-Mechanics\CLI\bestiary\undead/crimson-clergy-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 494*  

---

*Vampiric Zealot*

---

Crimson clergy are Undead cultists, often created, led, and taught by a more powerful vampire. Crimson clergy view the consumption of blood—and in its use during their rituals and when casting spells—not only as necessary but sacred. Their hunger reaches beyond the limits of their fangs and claws, calling to the blood of their victims and drawing it out in scarlet ribbons.

## Secret

Crimson clergy struggle to accept how monstrous they have become. They can't stand the sight of themselves and see their true visage in their reflection.

```statblock
"name": "Crimson Clergy (CrookedMoon24)"
"size": "Small or Medium"
"type": "undead"
"subtype": "Cleric, Vampire"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "15"
  - !!int "15"
  - !!int "10"
  - !!int "16"
  - !!int "14"
"speed": "30 ft., climb 30 ft."
"saves":
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+4"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": "Common plus one other language"
"cr": "3"
"traits":
  - "desc": "The clergy can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The clergy has the following weaknesses:\n\n- **Self-Loathing.** The\
      \ clergy has <span title=\"Player's Handbook (2024)\">Disadvantage</span> on\
      \ <span title=\"Player's Handbook (2024)\">D20 Tests</span> if it can see its\
      \ reflection.  \n- **Sunlight Hypersensitivity.** The clergy takes 20 Radiant\
      \ damage if it starts its turn in sunlight. While in sunlight, it has <span\
      \ title=\"Player's Handbook (2024)\">Disadvantage</span> on attack rolls and\
      \ ability checks.  "
    "name": "Vampire Weakness"
"actions":
  - "desc": "*Melee  or Ranged Attack Roll:* +5, reach 5 ft. or range 60 ft. *Hit:*\
      \ 10 (2d6 + 3) Necrotic damage. The target's <span title=\"Player's Handbook\
      \ (2024)\">Hit Point</span> maximum decreases by an amount equal to the damage\
      \ taken, and the clergy regains <span title=\"Player's Handbook (2024)\">Hit\
      \ Points</span> equal to that amount."
    "name": "Consume"
  - "desc": "The clergy casts one of the following spells, requiring no Material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 13):\n\n**At will:**\
      \ Disguise Self, Thaumaturgy"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The clergy casts Bless using the same spellcasting ability as Spellcasting.\n"
    "name": "Crimson Blessing (1/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Crimson%20Clergy.webp"
```
^statblock

## Environment

any