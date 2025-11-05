---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Elias Greaves
---
# [Elias Greaves](3-Mechanics\CLI\bestiary\npc/elias-greaves-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 285*  

Elias *(eh-LYE-us)* Greaves was a gambler from the world of the living who dreamt of wealth and influence far beyond his station. Seemingly blessed by Lady Luck herself, he won big at every gambling hall he visited, eventually growing bored and craving a new challenge. He found a way to board the *Ghostlight Express* and travel to Druskenvald, where he met Phillip and Adela.

Despite his powerful new friends, his luck ran out in the lands of death, and his fortune was quickly spent. Soon, he was stuck playing low stakes games aboard the*Laughlin Lullaby*, a riverboat that traveled up and down the Silverbell River in Wickermoor Hollow. In desperation, he made a deal with Mister Crossroads to turn his luck around.

After shaking the croc-folk's hand, his luck instantly turned around, and he even won ownership of the riverboat in a poker bet. He renamed it *Dead Man's Hand* in reference to the skeletal left hand of his new patron. The gambler enjoyed years of prosperity, but as always, [The Grinning Sinner](/3-Mechanics/CLI/bestiary/npc/the-grinning-sinner-crookedmoon24.md) exploited the man's greed and the fine print in the deal, and it all came crashing down.

```statblock
"name": "Elias Greaves (CrookedMoon24)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral"
"ac": !!int "8"
"hp": !!int "15"
"hit_dice": "2d8 + 6"
"modifier": !!int "-2"
"stats":
  - !!int "13"
  - !!int "6"
  - !!int "16"
  - !!int "3"
  - !!int "6"
  - !!int "5"
"speed": "20 ft."
"saves":
  - "wisdom": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[Darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 8"
"languages": "understands Common plus one other language but can't speak"
"cr": "1/4"
"traits":
  - "desc": "If damage reduces Elias to 0 <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span>, it makes a Constitution saving throw (DC 5 plus the damage\
      \ taken) unless the damage is Radiant or from a <span title=\"Player's Handbook\
      \ (2024)\">Critical Hit</span>. On a successful save, Elias drops to 1 <span\
      \ title=\"Player's Handbook (2024)\">Hit Point</span> instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "*Melee Attack Roll:* +3, reach 5 ft. *Hit:* 5 (1d8 + 1) Bludgeoning damage."
    "name": "Slam"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Elias%20Greaves.webp"
```
^statblock