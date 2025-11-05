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
- The Songstress
---
# [The Songstress](3-Mechanics\CLI\bestiary\npc/the-songstress-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 180*  

Sitting in one of the velvet chairs is a [Wayward Haint](/3-Mechanics/CLI/bestiary/undead/wayward-haint-crookedmoon24.md) of a beautiful woman in a long, silky dress, smoking a cigarette while glumly looking out the window. Her whole being seems hollow. She only knows herself as a songstress who wished to be a famous singer in life.

When encountered, she feels empty, having never been able to find the perfect song that inspired her to give the performance of a lifetime for an audience that truly appreciated her talent. Her tastes are jazzy and romantic, and she wishes she could give one last soulful performance.

Bringing her the phonograph found in the Sleeper Car (area G2) and turning it on inspires her to sing the perfect final song. She stands at the center of the lounge and croons a love song that spurs Phillip and Adela to embrace and slowly dance to the performance. When the song concludes, she is freed, closing her eyes contentedly and fading away in peace.

When the song concludes, she is freed, closing her eyes contentedly and fading away in peace. The lyrics are as follows:

> Impossible to think at all, without the thought of you  and me.
> 
> It all would fall, nothing left to hold the stars and seas apart.
> 
> Ridiculous, there ever was a world without a 'you and me.'
> 
> To not recall a 'you' at all would send it all crashing down.
> 
> Floating over the storm, love as soft as a cloud.
> 
> Incredible that through it all, the dashed and broken stardust fell,
> 
> And settled into 'you and me,' and all the time we need.

Alternatively, below are suggested resolution proficiencies:

- **Musical Instrument or Performance.** Join the Songstress in a duet for an emotional swan song.  
- **Arcana or Insight.** Consider cosmic or philosophical topics that speak to inspiration and creativity.  
- **History or Investigation.** Explore examples of artistic work that help inspire the Songstress.  

```statblock
"name": "The Songstress (CrookedMoon24)"
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
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/The%20Songstress.webp"
```
^statblock