---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Vermin Infestation
---
# [Vermin Infestation](3-Mechanics\CLI\bestiary\fey/vermin-infestation-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 535*  

---

*Swarm of Verminous Familiars*

---

A nightmarish amalgamation of centipedes, pigeons, and weasels, vermin infestations are thankfully rare. These swarms of Fey roil and scratch and rend with individual pigeons streaking out to tear at distant foes, becoming a frenzied mass that throws all subtlety and coordination to the wind. At times, the constituent vermin-like Fey seem to be at each other's throats as much as any victims of the swarm.

## Secret

The Fey spirits that make up a vermin infestation loathe one another and can be tricked into fighting among themselves by a clever suggestion.

```statblock
"name": "Vermin Infestation (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "19"
  - !!int "14"
  - !!int "6"
  - !!int "16"
  - !!int "15"
"speed": "30 ft., burrow 30 ft., climb 30 ft."
"saves":
  - "strength": !!int "4"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 60 ft., tremorsense 30 ft., passive Perception 15"
"languages": "Common, Sylvan"
"cr": "3"
"traits":
  - "desc": "As an Influence action, a creature that insinuates that the components\
      \ of the swarm are conspiring against each other and succeeds on a DC 15 Charisma\
      \ (Deception) check deals 10 Necrotic damage to the swarm."
    "name": "Infighting"
  - "desc": "The swarm can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can fit through any opening large enough for a Tiny creature. The swarm\
      \ can't regain <span title=\"Player's Handbook (2024)\">Hit Points</span> or\
      \ gain <span title=\"Player's Handbook (2024)\">Temporary Hit Points</span>."
    "name": "Swarm"
"actions":
  - "desc": "*Melee  or Ranged Attack Roll:* +6, reach 5 ft. or range 20/60 ft., *Hit:*\
      \ 14 (4d4 + 4) Piercing damage, or 9 (2d4 + 4) Piercing damage if the swarm\
      \ is Bloodied. If the target is a Medium or smaller creature in the swarm's\
      \ space, the target has the Grappled condition (escape DC 14). The swarm can\
      \ have one creature Grappled at a time. At the start of each of the Grappled\
      \ target's turns, roll 1d6 to see which of the following effects it suffers:\n\
      \n- **1-2 Centipede Sting.** The target takes 4 (1d8) Poison damage and has\
      \ the Poisoned condition until the start of its next turn.  \n- **3-4 Pigeon\
      \ Cry.** The target takes 10 (3d6) Psychic damage.  \n- **5-6 Weasel Drain.**\
      \ The target takes 5 (1d10) Necrotic damage, and its <span title=\"Player's\
      \ Handbook (2024)\">Hit Point</span> maximum decreases by an amount equal to\
      \ the Necrotic damage taken.  "
    "name": "Shred"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Vermin%20Infestation.webp"
```
^statblock

## Environment

planar (fey), urban