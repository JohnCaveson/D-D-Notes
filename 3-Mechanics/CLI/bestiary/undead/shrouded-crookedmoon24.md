---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Shrouded
---
# [Shrouded](3-Mechanics\CLI\bestiary\undead/shrouded-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 530*  

---

*Soul Corrupted by the Shroud*

---

Shrouded are the spirits of the dead—devoid of any ability to reason and corrupted by the deathly mists known as the Shroud. They are raw emotional energy, unfettered and unleashed, manifested into being. The shrouded are constantly whispering about a victim's incompetencies, weakness, foibles, and failings as they engulf their prey to drain the life from them, corrupting their soul.

## Secret

Shrouded are bound by barriers and lines of iron, which is why cemeteries with iron fences keep them contained.

```statblock
"name": "Shrouded (CrookedMoon24)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "3"
"stats":
  - !!int "5"
  - !!int "14"
  - !!int "12"
  - !!int "6"
  - !!int "12"
  - !!int "16"
"speed": "5 ft., fly 30 ft. (hover)"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "acid, bludgeoning, cold, fire, lightning, piercing, slashing,\
  \ thunder"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 13"
"languages": "Common plus one other language"
"cr": "4"
"traits":
  - "desc": "The shrouded can enter another creature's space and stop there. It can\
      \ move through a space as narrow as 1 inch without spending extra movement to\
      \ do so."
    "name": "Mist Form"
  - "desc": "*Constitution Saving Throw:* DC 13, a creature that starts its turn in\
      \ the shrouded's space. *Failure:* 10 (3d6) Necrotic damage. *Success:* Half\
      \ damage. *Failure or Success:* The soul of a Humanoid that dies from this damage\
      \ becomes a new shrouded at the start of the shrouded's next turn and takes\
      \ its turn on that <span title=\"Player's Handbook (2024)\">Initiative</span>.\n\
      \nThe Humanoid can't be returned to life until the new shrouded is destroyed."
    "name": "Corrupting Mist"
  - "desc": "The shrouded can't move through a space with a barrier or line of iron,\
      \ such as a wrought iron fence or a line of iron filings. This impassible barrier\
      \ rises to a height of 1 mile above the iron."
    "name": "Graveyard Warding"
  - "desc": "The shrouded has one of three variants, which determines a unique action\
      \ option: Devourer, Reaper, or Whisperer."
    "name": "Variation"
"actions":
  - "desc": "The shrouded makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Necrotic damage."
    "name": "Corrupting Touch"
  - "desc": "*Melee Attack Roll:* +5, reach 10 ft. *Hit:* 5 (1d4 + 3) Bludgeoning\
      \ damage. If the target is a Medium or smaller creature, it has the Grappled\
      \ condition (escape DC 13). At the start of a Grappled target's turn, it takes\
      \ 10 (3d6) Necrotic damage, and the shrouded regains <span title=\"Player's\
      \ Handbook (2024)\">Hit Points</span> equal to that amount."
    "name": "Consuming Bite (Devourer Only)"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Slashing damage\
      \ plus 10 (3d6) Necrotic damage. If the target is a creature, it can't regain\
      \ <span title=\"Player's Handbook (2024)\">Hit Points</span> until the start\
      \ of the shrouded's next turn."
    "name": "Scythe (Reaper Only)"
  - "desc": "*Intelligence Saving Throw:* DC 13, each creature that isn't a Construct\
      \ or Undead in a 30-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the shrouded. *Failure:* 7 (2d6) Psychic damage, and the\
      \ target has the Frightened condition until the start of the shrouded's next\
      \ turn. *Success:* Half damage only."
    "name": "Toxic Thoughts (Whisperer Only)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Shrouded.webp"
```
^statblock

## Environment

any