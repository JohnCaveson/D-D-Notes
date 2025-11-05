---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bat Hound
---
# [Bat Hound](3-Mechanics\CLI\bestiary\monstrosity/bat-hound-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 488*  

---

*Bloodthirsty Hunter of the Night*

---

Bat hounds are created through blood magic rituals that manipulate the curse of vampirism to transform a hound into a relentless stalker. Unswervingly loyal companions, bat hounds aid vampiric masters in tracking prey, able to outrun horses and their riders once they smell blood. They seek out stragglers or quarry that are escaping during a hunt and drag them back for capture.

## Secret

Running water keeps bat hounds at bay and can destroy them, a lingering remnant from the vampiric curse that spawned them.

```statblock
"name": "Bat Hound (CrookedMoon24)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "4"
  - !!int "12"
  - !!int "15"
  - !!int "13"
  - !!int "10"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+6"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 16"
"languages": "understands Common plus one other language but can't speak"
"cr": "1"
"traits":
  - "desc": "The bat hound can't willingly move into running water or to a space up\
      \ to 20 feet above running water. If it starts its turn in running water, it\
      \ takes 10 Acid damage and has the Frightened condition until the start of its\
      \ next turn."
    "name": "Barred by Water"
  - "desc": "If it doesn't have the Incapacitated condition and isn't wearing heavy\
      \ armor, the bat hound can extend its membranous wings to move up to 5 feet\
      \ horizontally for every 1 foot it descends in the air."
    "name": "Glide"
  - "desc": "The bat hound can climb difficult surfaces, including along ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Piercing damage\
      \ plus 3 (1d6) Necrotic damage. If the target is a creature, the bat hound regains\
      \ a number of <span title=\"Player's Handbook (2024)\">Hit Points</span> equal\
      \ to the Necrotic damage taken, and if the target is a Medium or smaller creature,\
      \ it has the Grappled condition (escape DC 13)."
    "name": "Bite"
"bonus_actions":
  - "desc": "The bat hound takes the Dash and Disengage actions, and until the end\
      \ of the turn, needn't spend extra movement to move a creature it is grappling."
    "name": "Outmaneuver"
"reactions":
  - "desc": "Trigger: The bat hound takes damage from a fall and isn't wearing heavy\
      \ armor. _Response:_ The bat hound extends its wings and reduces the fall's\
      \ damage to 0."
    "name": "Safe Descent"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Bat%20Hound.webp"
```
^statblock

## Environment

forest, mountain, underdark, urban