---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/planar-lower-planes
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Crowstorm
---
# [Crowstorm](3-Mechanics\CLI\bestiary\fiend/crowstorm-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 497*  

---

*Fiendish Murder*

---

A crowstorm is a great, swirling mass of dark feathers accompanied constant, harshly malevolent crow calls. Hundreds of fiendish birds fly in unison, their beady eyes dripping blood as they swoop down to tear at the flesh of their victims. A crowstorm's horrific caws mingle into an eerie cacophony of pleading whispers, and it robs the gift of flight from anything that draws too close.

## Secret

While they might take the form of crows or possess crow bodies, crowstorms are held at bay by drawn images or crafted effigies of crows.

```statblock
"name": "Crowstorm (CrookedMoon24)"
"size": "Large"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d6 + 16"
"modifier": !!int "5"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "15"
  - !!int "14"
  - !!int "16"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "bludgeoning, cold, fire, piercing, slashing"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 14"
"languages": "Abyssal, Common; telepathy 120 ft."
"cr": "3"
"traits":
  - "desc": "The swarm can't enter a space with a drawn or painted image or crafted\
      \ effigy of a crow. A creature holding such an icon has <span title=\"Player's\
      \ Handbook (2024)\">Advantage</span> on saving throws the swarm forces it to\
      \ make."
    "name": "False Crows"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny crow. The swarm\
      \ can't regain <span title=\"Player's Handbook (2024)\">Hit Points</span> or\
      \ gain <span title=\"Player's Handbook (2024)\">Temporary Hit Points</span>."
    "name": "Swarm"
  - "desc": "*Wisdom Saving Throw:* DC 13, any creature (other than a Fiend) with\
      \ a <span title=\"Player's Handbook (2024)\">Fly Speed</span> that starts its\
      \ turn in a 30-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the swarm. *Failure:* The target's <span title=\"Player's\
      \ Handbook (2024)\">Fly Speed</span> is 0 until the start of its next turn."
    "name": "Wing Bind"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 12 (2d8 + 3) Piercing damage,\
      \ or 7 (1d8 + 3) Piercing damage if the swarm is Bloodied. If the target is\
      \ a creature, it has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on attack rolls until the start of the swarm's next turn."
    "name": "Peck"
  - "desc": "*Wisdom Saving Throw:* DC 13, each creature in a 30-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from the swarm. *Failure:*\
      \ 10 (3d6) Psychic damage, and the target has the Frightened condition until\
      \ the start of the swarm's next turn. *Success:* Half damage only."
    "name": "Cacophony (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Crowstorm.webp"
```
^statblock

## Environment

grassland, planar (lower planes), urban