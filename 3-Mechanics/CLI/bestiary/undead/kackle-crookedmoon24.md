---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kackle
---
# [Kackle](3-Mechanics\CLI\bestiary\undead/kackle-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 511*  

---

*Laughing Lantern Bearer*

---

Those who were particularly sadistic in life and died consumed by wicked mirth linger as Kackles—ghostly figures that drift above the ground, always flitting just out of sight. Adorned in tattered cloaks and concealing hoods or hats, their hollow laughter echoes through dark places, fading in and out to confuse and terrify their victims. Kackles always carry lanterns lit with ghostly flames, the color of which changes to reflect a kackle's current cruelty of choice.

## Secret

Kackles are bound to their lanterns, and smashing their lights can snuff out the spirits' existence.

```statblock
"name": "Kackle (CrookedMoon24)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "67"
"hit_dice": "15d8"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "17"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "18"
"speed": "5 ft., fly 60 ft. (hover)"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "acid, bludgeoning, cold, fire, lightning, piercing, slashing,\
  \ thunder"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Common plus one other language"
"cr": "7"
"traits":
  - "desc": "The kackle can move through other creatures and objects as if they were\
      \ <span title=\"Player's Handbook (2024)\">Difficult Terrain</span>. It takes\
      \ 5 (1d10) Force damage if it ends its turn inside an object."
    "name": "Incorporeal Movement"
  - "desc": "The kackle's lantern has AC 15 and <span title=\"Player's Handbook (2024)\"\
      >Immunity</span> to Poison and Psychic damage. Any damage the lantern takes\
      \ deals half that amount of Force damage to the kackle."
    "name": "Lantern Vulnerability"
"actions":
  - "desc": "*Melee  or Ranged Attack Roll:* +7, reach 5 ft. or range 90 ft. *Hit:*\
      \ Varies by lantern color (kackle's choice):"
    "name": "Lantern Flame"
  - "desc": "7 (1d6 + 4) Cold damage, and the target has the Restrained condition\
      \ until the end of its next turn."
    "name": "Blue"
  - "desc": "20 (3d10 + 4) Necrotic damage, and the target's <span title=\"Player's\
      \ Handbook (2024)\">Speed</span> is 0 until the end of its next turn."
    "name": "Green"
  - "desc": "10 (1d12 + 4) Psychic damage, and the target has the Frightened condition\
      \ until the end of its next turn."
    "name": "Purple"
  - "desc": "15 (2d10 + 4) Fire damage, and the target starts burning, taking 5 (1d10)\
      \ Fire damage instead of the regular burning damage."
    "name": "Red"
"bonus_actions":
  - "desc": "The kackle teleports up to 60 feet to an unoccupied space it can see.\
      \ The kackle can then change its lantern color, and it can create the following—\
      *Dexterity Saving Throw:* DC 15, each creature in a 5-foot <span title=\"Player's\
      \ Handbook (2024)\">Emanation</span> originating from the kackle's destination\
      \ space. *Failure:* 13 (3d8) damage of the same type as the current Lantern\
      \ Flame color. *Success:* Half damage."
    "name": "Flickering Teleport"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Kackle.webp"
```
^statblock

## Environment

any