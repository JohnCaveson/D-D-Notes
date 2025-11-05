---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gobblegeist
---
# [Gobblegeist](3-Mechanics\CLI\bestiary\monstrosity/gobblegeist-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 505*  

---

*Blood-Drinking Avian Predator*

---

Gobblegeists are massive birdlike monsters with earth-toned plumage, reptilian faces and claws, and a metallic beak edged with sharp teeth. These ravenous creatures descend from forest canopies or hilltops to snatch their prey unawares and carry them off to feed on their blood in solitude. Their single, unblinking eye can unnerve and dazzle more alert prey, making would-be threats an easy meal.

## Secret

The folk who venerate the Old Ways believe that a seven-pointed star repels gobblegeists. They keep the monsters at bay by painting or weaving star sigils from wicker to hang from their homes or in trees.

```statblock
"name": "Gobblegeist (CrookedMoon24)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "114"
"hit_dice": "12d12 + 36"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "16"
  - !!int "5"
  - !!int "16"
  - !!int "8"
"speed": "30 ft., fly 80 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 16"
"languages": ""
"cr": "8"
"traits":
  - "desc": "The gobblegeist doesn't provoke an Opportunity Attack when it flies out\
      \ of an enemy's reach."
    "name": "Flyby"
  - "desc": "The gobblegeist can't willingly move to a space within 10 feet of a seven-pointed\
      \ star drawn on a surface or woven from wicker."
    "name": "Repelled by Stars"
"actions":
  - "desc": "The gobblegeist makes two Beak attacks. It can replace one attack with\
      \ a Talons attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 9 (1d8 + 5) Piercing damage\
      \ plus 10 (3d6) Necrotic damage. The target's <span title=\"Player's Handbook\
      \ (2024)\">Hit Point</span> maximum is reduced by an amount equal to the Necrotic\
      \ damage taken, and the gobblegeist regains <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> equal to that amount."
    "name": "Beak"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 14 (2d8 + 5) Piercing damage.\
      \ If the target is a Large or smaller creature, it has the Grappled condition\
      \ (escape DC 15) from both talons, and it has the Restrained condition until\
      \ the grapple ends."
    "name": "Talons"
  - "desc": "*Dexterity Saving Throw:* DC 14, each creature in a 120-foot-long, 5-foot-wide\
      \ line. *Failure:* 6 (1d12) Psychic damage, and the target has the Stunned condition\
      \ until the start of the gobblegeist's next turn."
    "name": "Eye Beam"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Gobblegeist.webp"
```
^statblock

## Environment

forest, hill