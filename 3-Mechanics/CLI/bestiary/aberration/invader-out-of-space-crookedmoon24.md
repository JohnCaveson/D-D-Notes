---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Invader Out of Space
---
# [Invader Out of Space](3-Mechanics\CLI\bestiary\aberration/invader-out-of-space-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 510*  

---

*Intruder From Beyond the Stars*

---

Invaders out of space appeared after a falling star blazed down from the cosmos. These alien beings have an unsettling habit of appearing between glances and silently watching. Invaders stand upright like a biped, shrouded in what are either voluminous robes or draping folds of skin.

Observers who are lucky find the invaders gone in a blink, and those who aren't so fortunate hear the bloodcurdling hiss these things from beyond the stars emit as they attack. All that remains of their victims is a spray of gray powder amid crumpled clothing.

## Secret

The invaders have little resilience to the toxic and virulent threats of the Material Plane, and they succumb quickly to diseases and poisons.

```statblock
"name": "Invader Out of Space (CrookedMoon24)"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "18"
"hp": !!int "156"
"hit_dice": "24d8 + 48"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "18"
  - !!int "15"
  - !!int "14"
  - !!int "12"
  - !!int "19"
"speed": "40 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "5"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_resistances": "psychic"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 11"
"languages": "Deep Speech; telepathy 120 ft."
"cr": "11"
"traits":
  - "desc": "If a creature tries to read the intruder's mind or deals Psychic damage\
      \ to it, that creature must succeed on a DC 16 Intelligence saving throw or\
      \ have the Stunned condition for 1 minute. It repeats the save at the end of\
      \ each of its turns, ending the effect on itself on a success."
    "name": "Alien Mind"
  - "desc": "The invader hovers 6 inches above the ground and leaves no tracks. It\
      \ ignores <span title=\"Player's Handbook (2024)\">Difficult Terrain</span>\
      \ caused by conditions on the ground, can move over liquids, and takes no damage\
      \ from falling."
    "name": "Gliding Levitation"
  - "desc": "The invader has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The invader has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on saving throws to avoid or end the Poisoned condition. If the invader is\
      \ Poisoned at the start of its turn, it takes 20 Necrotic damage."
    "name": "Weak Constitution"
"actions":
  - "desc": "The invader makes three Disrupting Touch attacks and uses Unnerving Glare\
      \ if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 15 (2d10 + 4) Force damage.\
      \ A creature killed or an object destroyed by this damage is reduced to a fine\
      \ gray dust.\n\nMagic items, and any equipment worn or carried by a disintegrated\
      \ creature, don't disintegrate."
    "name": "Disrupting Touch"
  - "desc": "*Wisdom Saving Throw:* DC 16, one creature the invader can see within\
      \ 60 feet. *Failure:* The target has the Incapacitated condition until the start\
      \ of the invader's next turn."
    "name": "Unnerving Glare (Recharge 5-6)"
"reactions":
  - "desc": "Trigger: The invader takes damage. _Response:_ The invader teleports\
      \ to an unoccupied space it can see within 60 feet and can cause the following—\
      *Intelligence Saving Throw:* DC 16, each creature within a 30-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from the space where\
      \ the invader vanished or appeared (invader's choice). *Failure:* 16 (3d10)\
      \ Psychic damage, and the target's <span title=\"Player's Handbook (2024)\"\
      >Speed</span> is halved until the end of its next turn. *Success:* Half damage\
      \ only."
    "name": "Otherworldly Slip"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Invader%20out%20of%20Space.webp"
```
^statblock

## Environment

any