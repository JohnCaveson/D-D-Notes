---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Boneflayer
---
# [Boneflayer](3-Mechanics\CLI\bestiary\monstrosity/boneflayer-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 490*  

---

*Voracious Carrion Eater*

---

Boneflayers are cruel, vulture-like creatures that originated from a broken fey pact. The creatures aren't content to wait for something to die and instead make their own carrion to gorge upon—they delight in snatching prey in their talons, carrying it into the air, and dropping it to its death. Boneflayers earn their name by using their sizeable, filth-riddled beaks to cleave flesh from bone and hoard the meat until it ages enough for them to enjoy.

Cults sometimes use boneflayer killing grounds as a source of bones to burn in ritual bonfires, occasionally making pacts with the creatures to pay or trade for the creature's castoffs. Villages that fear boneflayer attacks ward them off with thundering drums or gongs whenever they circle overhead.

## Secret

A lingering result of the fey bargain that created them, boneflayers are disoriented and diminished by loud, thunderous noises.

```statblock
"name": "Boneflayer (CrookedMoon24)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"hp": !!int "94"
"hit_dice": "9d10 + 45"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "20"
  - !!int "8"
  - !!int "16"
  - !!int "6"
"speed": "10 ft., fly 80 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+6"
"damage_resistances": "fire, necrotic"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 16"
"languages": "Sylvan; understands Common but can't speak it"
"cr": "6"
"traits":
  - "desc": "The boneflayer doesn't provoke an Opportunity Attack when it flies out\
      \ of an enemy's reach."
    "name": "Flyby"
  - "desc": "When the boneflayer hears a drum or gong, or takes Thunder damage, it\
      \ has <span title=\"Player's Handbook (2024)\">Disadvantage</span> on <span\
      \ title=\"Player's Handbook (2024)\">D20 Tests</span> until the end of its next\
      \ turn."
    "name": "Thunderous Ward"
"actions":
  - "desc": "The boneflayer makes one Beak attack and one Talons attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing damage,\
      \ and the target has the Poisoned condition until the end of its next turn."
    "name": "Beak"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Piercing damage.\
      \ If the target is a Medium or smaller creature, it has the Grappled condition\
      \ (escape DC 14) from both talons. While Grappled, the target has the Restrained\
      \ condition."
    "name": "Talons"
"bonus_actions":
  - "desc": "If the boneflayer has a creature Grappled, the boneflayer flies up to\
      \ half its <span title=\"Player's Handbook (2024)\">Fly Speed</span> without\
      \ provoking Opportunity Attacks and drops that creature."
    "name": "Swoop (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Bone%20Flayer.webp"
```
^statblock

## Environment

desert, forest, grassland, mountain