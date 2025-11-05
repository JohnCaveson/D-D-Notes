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
- The Sweetheart
---
# [The Sweetheart](3-Mechanics\CLI\bestiary\npc/the-sweetheart-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 179*  

Within the third cabin is a [Wayward Haint](/3-Mechanics/CLI/bestiary/undead/wayward-haint-crookedmoon24.md) of a weeping young woman, looking wistful as she longingly stares at a locket of a handsome mustachioed man with the initials J.B. underneath the portrait. She only knows herself as his sweetheart.

She is lovesick and lonely, only barely registering the characters and bemoaning having to travel to the afterlife alone. She isn't complete without her dear love, and she doesn't want to spend an eternity without him.

Giving her the love letter from Jakob Braun found in the Mail Car (area G5) makes her realize that her love is already on the other side and is waiting for her in the afterlife. She weeps with joy, hugging the tear-stained letter and her locket as she is freed and fades from view.

Alternative resolution proficiencies are:

- **Calligrapher's Supplies or Performance.** Help her compose a poem or song about her love so she has something to soothe her longing for him.  
- **History or Persuasion.** Commiserate with her with personal tales of lost and regained love or recite legends or tales of the same.  
- **Investigation or Religion.** Steer her to remember details of her love's qualities in a real and practical way, suggesting they will be reunited when she reaches her destination.  

```statblock
"name": "The Sweetheart (CrookedMoon24)"
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
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/The%20Sweetheart.webp"
```
^statblock