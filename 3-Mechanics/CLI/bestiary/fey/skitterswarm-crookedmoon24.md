---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Skitterswarm
---
# [Skitterswarm](3-Mechanics\CLI\bestiary\fey/skitterswarm-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 531*  

---

*Fetid Fey Centipedes*

---

Disgusting Fey who delight in warping flesh and spreading sickness can gather into squirming masses of centipedes known as skitterswarms. These swarms lurk in places where foulness accumulates and often serve centipede hags.

## Secret

Skitterswarms can't resist dead bodies and are drawn to the corpses of Humanoids.

```statblock
"name": "Skitterswarm (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "14"
  - !!int "7"
  - !!int "10"
  - !!int "8"
"speed": "30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 20 ft., passive Perception\
  \ 10"
"languages": "understands Common and Sylvan but can't speak"
"cr": "1/2"
"traits":
  - "desc": "If the swarm can see the corpse of a Humanoid at the start of its turn,\
      \ it must move up to its <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ toward the corpse. Once it enters the corpse's space, it must remain there\
      \ for 1 hour, after which time the corpse's flesh putrefies."
    "name": "Body Burrowing"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny centipede. The\
      \ swarm can't regain <span title=\"Player's Handbook (2024)\">Hit Points</span>\
      \ or gain <span title=\"Player's Handbook (2024)\">Temporary Hit Points</span>."
    "name": "Swarm"
  - "desc": "*Constitution Saving Throw:* DC 12, any creature that starts its turn\
      \ in the swarm's space. *Failure:* The target contracts a magical contagion.\
      \ While afflicted, the target can't regain <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span>, and it repeats the save when it finishes a <span title=\"\
      Player's Handbook (2024)\">Long Rest</span> or when targeted by an effect that\
      \ ends the Poisoned condition, recovering from the contagion on a success. *Success:*\
      \ The target is immune to the Vile Vermin trait of all skitterswarms for 24\
      \ hours."
    "name": "Vile Vermin"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 7 (2d6) Piercing damage,\
      \ or 3 (1d6) Piercing damage if the swarm is Bloodied. If the target is a creature,\
      \ a centipede infests its body. While infested, the target takes 3 (1d6) Necrotic\
      \ damage at the start of each of its turns. The infestation ends when the target\
      \ regains <span title=\"Player's Handbook (2024)\">Hit Points</span> or is targeted\
      \ by an effect that ends the Poisoned condition."
    "name": "Infesting Bite"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Skitterswarm.webp"
```
^statblock

## Environment

planar (fey), underground, urban