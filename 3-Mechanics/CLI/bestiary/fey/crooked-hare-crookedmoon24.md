---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/planar-fey
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Crooked Hare
---
# [Crooked Hare](3-Mechanics\CLI\bestiary\fey/crooked-hare-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 582*  

---

*Crooked Trickster (Anything stolen or gained by trickery)*

---

Crooked hares look like rabbits at first glance, but their true nature is given away by the antlers and wings they grow and the cunning gleam in their eyes. They are mischievous tricksters that delight in stealing things from unsuspecting travelers and hiding them in amusing, slightly dangerous, or just unlikely places. If roused to anger or cornered, crooked hares deliver a bite that carries an unsettling—if minor—curse. Despite their troublesome nature, crooked hares might serve as companions for woods-crafty folk who have a good sense of humor.

```statblock
"name": "Crooked Hare (CrookedMoon24)"
"size": "Tiny"
"type": "fey"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"hp": !!int "21"
"hit_dice": "6d4 + 6"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "16"
  - !!int "13"
  - !!int "10"
  - !!int "14"
  - !!int "16"
"speed": "30 ft., fly 50 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+2"
  - "name": "[Sleight of Hand](/3-Mechanics/CLI/skills.md#Sleight%20of%20Hand)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Common, Sylvan"
"cr": "1"
"traits":
  - "desc": "The crooked hare leaves no tracks, or it leaves the tracks of a Large\
      \ or smaller creature of its choice. If it doesn't have the Incapacitated condition,\
      \ it can share the effects of this trait with another creature within 5 feet\
      \ (no action required)."
    "name": "Trackless Step"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing damage\
      \ plus 7 (2d6) Poison damage, and if the target is a creature, it must succeed\
      \ on a DC 11 Charisma saving throw or become cursed for 24 hours. The cursed\
      \ creature's limbs sporadically twist and move in unnatural ways, giving the\
      \ creature <span title=\"Player's Handbook (2024)\">Disadvantage</span> on attack\
      \ rolls and on ability checks that rely on Charisma."
    "name": "Twisting Bite"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Crooked%20Hare.webp"
```
^statblock

## Environment

forest, hill, planar (fey)