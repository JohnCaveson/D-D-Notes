---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/desert
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Goatstealer
---
# [Goatstealer](3-Mechanics\CLI\bestiary\monstrosity/goatstealer-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 586*  

---

*Hungry Livestock Snatcher (Incense and spoiled meat)*

---

The hairless, reeking goatstealers are vicious predators and scavengers that earn their name from their habit of preying upon livestock. They latch onto prey with wicked, needle-like teeth, delivering lethal venom and devouring creatures far larger than its wiry frame would suggest is possible. Especially dangerous in packs, the carrion-yet-peaty stench of goatstealers is the stuff of legend.

```statblock
"name": "Goatstealer (CrookedMoon24)"
"size": "Small"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "4d6 + 8"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "15"
  - !!int "14"
  - !!int "3"
  - !!int "12"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+5"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The goatstealer has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on an attack roll against a creature if at least one of the goatstealer's\
      \ allies is within 5 feet of the creature and the ally doesn't have the Incapacitated\
      \ condition."
    "name": "Pack Tactics"
  - "desc": "*Constitution Saving Throw:* DC 12, any creature that starts its turn\
      \ in a 5-foot <span title=\"Player's Handbook (2024)\">Emanation</span> originating\
      \ from the goatstealer. *Failure:* The target has the Poisoned condition until\
      \ the start of its next turn. *Success:* The target is immune to the Stench\
      \ of all goatstealers for 1 hour."
    "name": "Stench"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage\
      \ plus 3 (1d6) Poison damage. If the target is a Medium or smaller creature,\
      \ it has the Grappled condition (escape DC 12). Until the grapple ends, at the\
      \ start of each of the goatstealer's turns, the target takes 3 (1d6) Poison\
      \ damage."
    "name": "Bite"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Goatstealer.webp"
```
^statblock

## Environment

desert, forest, grassland, hill