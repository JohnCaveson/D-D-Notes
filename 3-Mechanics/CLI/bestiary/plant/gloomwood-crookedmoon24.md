---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gloomwood
---
# [Gloomwood](3-Mechanics\CLI\bestiary\plant/gloomwood-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 504*  

---

*Blighted Treant*

---

Gloomwoods were once treants in service to an archfey, but they were corrupted by a supernatural fungal blight. The growth bores through their trunks and into their souls, making the gloomwoods cruel and vicious, interested only in spreading more decay. Fungal spores drift from their trunks and branches, rotting any flesh and digging into the ground around them to spread the blight.

## Secret

Carving the Sylvan name of the forest the gloomwood once called home into the creature's trunk quells its aggression.

```statblock
"name": "Gloomwood (CrookedMoon24)"
"size": "Huge"
"type": "plant"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "161"
"hit_dice": "17d12 + 51"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "8"
  - !!int "17"
  - !!int "12"
  - !!int "16"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
"damage_resistances": "bludgeoning, piercing"
"damage_immunities": "necrotic"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 17"
"languages": "Common, Sylvan"
"cr": "10"
"traits":
  - "desc": "The ground in a 20-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the gloomwood is <span title=\"Player's Handbook (2024)\"\
      >Difficult Terrain</span> from mushrooms and fungus that grow in the area. A\
      \ creature that ends its turn in the <span title=\"Player's Handbook (2024)\"\
      >Emanation</span> takes 5 (1d10) Necrotic damage."
    "name": "Blighted Aura"
  - "desc": "As an action, a creature can use a Dagger or Woodcarver's Tools to carve\
      \ the name in Sylvan of the ancient home of the gloomwoods into the gloomwood's\
      \ trunk. Until the gloomwood finishes a <span title=\"Player's Handbook (2024)\"\
      >Long Rest</span>, it can't use its Fungal Fling or Spore Stomp actions."
    "name": "Carved Past"
  - "desc": "The gloomwood ignores <span title=\"Player's Handbook (2024)\">Difficult\
      \ Terrain</span> caused by plants or fungi."
    "name": "Fungal Step"
"actions":
  - "desc": "The gloomwood makes two attacks, using Slam or Fungal Fling in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 10 ft. *Hit:* 13 (2d6 + 6) Bludgeoning\
      \ damage plus 7 (2d6) Necrotic damage. If the target is a Medium or smaller\
      \ creature, it has the Grappled condition (escape DC 16) from one of two branches.\
      \ Until the grapple ends, the target has the Restrained condition."
    "name": "Slam"
  - "desc": "*Ranged Attack Roll:* +10, range 60/180 ft. *Hit:* 23 (5d6 + 6) Bludgeoning\
      \ damage plus 10 (3d6) Necrotic damage."
    "name": "Fungal Fling"
  - "desc": "*Melee Attack Roll:* +10, reach 5 ft. *Hit:* 17 (2d10 + 6) Bludgeoning\
      \ damage. *Hit or Miss:* Each creature within a 20-foot <span title=\"Player's\
      \ Handbook (2024)\">Sphere</span> centered on the target must make the following\
      \ saving throw. *Constitution Saving Throw:* DC 15. *Failure:* 36 (8d8) Poison\
      \ damage, and the target has the Poisoned condition until the end of its next\
      \ turn. *Success:* Half damage only."
    "name": "Spore Stomp (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Gloomwood.webp"
```
^statblock

## Environment

forest, swamp