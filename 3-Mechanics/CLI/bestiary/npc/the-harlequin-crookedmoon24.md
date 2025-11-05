---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Harlequin
---
# [The Harlequin](3-Mechanics\CLI\bestiary\npc/the-harlequin-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 186*  

Hanging upside down from a dangling trapeze bar fastened to the ceiling is a [Wayward Haint](/3-Mechanics/CLI/bestiary/undead/wayward-haint-crookedmoon24.md) of a woman dressed as a jester with a harlequin cap covered in jingling bells. Her face is wracked with shame as she dramatically tugs on her hat and performs acrobatic but painful-looking tumbles and pratfalls.

When encountered, she mostly bemoans her own foolishness and wishes she hadn't made such a terrible mistake that hurt so many people. When pressed, she explains that she accidentally opened the cage of a vicious tiger that went on a rampage and killed dozens throughout the carnival, including herself. She wishes she could be certain it could never harm anyone again.

Giving her the iron ring that had been around the tail of the wildpyre found in the Baggage Car (area G6) fills her with immeasurable relief. The shame leaves her face, and she leaps across the room to do a cartwheel as she is freed and fades away.

Alternatively, below are suggested resolution proficiencies:

- **Animal Handling or Survival.** Muse on the essence of the wild animal's danger and the insufficient security measures used to contain it.  
- **Deception or Nature.** Suggest the tiger must have lived its life and died of natural causes by now, so no harm can come from it ever again.  
- **Investigation or Persuasion.** Help her come to terms with the accident and recognize other factors out of her control.  

```statblock
"name": "The Harlequin (CrookedMoon24)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral"
"ac": !!int "11"
"hp": !!int "13"
"hit_dice": "3d8"
"modifier": !!int "1"
"stats":
  - !!int "9"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "14"
  - !!int "14"
"speed": "5 ft., fly 30 ft. (hover)"
"saves":
  - "charisma": !!int "4"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
"damage_resistances": "acid, bludgeoning, cold, fire, lightning, piercing, slashing,\
  \ thunder"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 14"
"languages": "Common plus one other language"
"cr": "1"
"traits":
  - "desc": "A haint that enters the space of an upright, empty bottle must succeed\
      \ on a DC 16 Charisma saving throw or be drawn into the bottle, and a cork or\
      \ stopper appears to close the bottle. The trapped haint can see and hear through\
      \ the bottle out to 10 feet, and any creature in that range can hear the haint.\
      \ The haint is released if the bottle breaks or another creature opens it."
    "name": "Bottle Trap"
  - "desc": "The haint can move through other creatures and objects as if they were\
      \ <span title=\"Player's Handbook (2024)\">Difficult Terrain</span>. It takes\
      \ 5 (1d10) Force damage if it ends its turn inside a solid object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 10 (3d6) Psychic damage,\
      \ and the target gains 1 Exhaustion level. This can't raise the target's Exhaustion\
      \ level above 5, and all Exhaustion levels gained from this action end when\
      \ the target finishes a <span title=\"Player's Handbook (2024)\">Short</span>\
      \ or <span title=\"Player's Handbook (2024)\">Long Rest</span>, or if it receives\
      \ a Lesser Restoration spell or similar magic."
    "name": "Draining Regret"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/The%20Harlequin.webp"
```
^statblock