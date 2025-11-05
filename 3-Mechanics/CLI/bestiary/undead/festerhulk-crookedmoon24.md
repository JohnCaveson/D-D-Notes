---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Festerhulk
---
# [Festerhulk](3-Mechanics\CLI\bestiary\undead/festerhulk-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 502*  

---

*Fungal Undead Giant*

---

Festerhulks are dead giants whose corpses are infested with fungus engorged by the magic of decay. This fungus has consumed and replaced much of the giant's flesh and now animates the corpse. The heads of these giants are often completely overtaken by repulsive mushrooms and other fungal growths. The spores given off by their infestation can spread to victims killed by festerhulks, giving rise to further Undead.

## Secret

Festerhulks shrink from sunlight, which harms the fungus that animates them.

```statblock
"name": "Festerhulk (CrookedMoon24)"
"size": "Huge"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "207"
"hit_dice": "18d12 + 90"
"modifier": !!int "-1"
"stats":
  - !!int "25"
  - !!int "9"
  - !!int "20"
  - !!int "3"
  - !!int "6"
  - !!int "3"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [stunned](/3-Mechanics/CLI/conditions.md#Stunned),\
  \ [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 12"
"languages": "understands Common and Giant but can't speak"
"cr": "11"
"traits":
  - "desc": "The festerhulk ignores <span title=\"Player's Handbook (2024)\">Difficult\
      \ Terrain</span> caused by plants or fungi."
    "name": "Fungal Step"
  - "desc": "At the end of each of the festerhulk's turns, each creature in a 5-foot\
      \ <span title=\"Player's Handbook (2024)\">Emanation</span> originating from\
      \ the festerhulk takes 10 (3d6) Necrotic damage and has the Poisoned condition\
      \ until the end of its next turn. A Giant or Humanoid killed by this damage\
      \ rises as a new creature 24 hours later: Festerhulk (if a Giant), Zombie (if\
      \ a Humanoid)."
    "name": "Spore Cloud"
  - "desc": "The festerhulk takes 10 Radiant damage if it starts its turn in sunlight.\
      \ While in sunlight, it has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on attack rolls and ability checks."
    "name": "Sunlight Hypersensitivity"
"actions":
  - "desc": "The festerhulk makes two Fetid Slam attacks and uses Slime Mold if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +11, reach 10 ft. Hit:20 (2d12 + 7) Bludgeoning\
      \ damage plus 13 (3d8) Necrotic damage."
    "name": "Fetid Slam"
  - "desc": "The festerhulk disgorges a mass of ravenous slime mold into an unoccupied\
      \ space within 20 feet. This mass uses the Black Pudding stat block except it\
      \ is a Plant, and its size is Medium. The mass acts on the festerhulk's <span\
      \ title=\"Player's Handbook (2024)\">Initiative</span>. It, and any masses it\
      \ Split into, dries up and dies in 1 hour."
    "name": "Slime Mold (1/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Festerhulk.webp"
```
^statblock

## Environment

forest, swamp, underground