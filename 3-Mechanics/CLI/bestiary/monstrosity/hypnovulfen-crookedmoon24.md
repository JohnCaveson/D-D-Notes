---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hypnovulfen
---
# [Hypnovulfen](3-Mechanics\CLI\bestiary\monstrosity/hypnovulfen-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 509*  

---

*Hungry Hypnotizing Wolf*

---

Hypnovulfen resemble massive wolves with unnaturally large orange eyes and wide, crooked maws. Despite their size, hypnovulfen are shockingly stealthy, able to stalk their prey and snare them with a hypnotic gaze from the shadows. The gaze beguiles victims into seeing a loved one beckoning them closer for a warm embrace. All the better for a hypnovulfen to feed and consume the unfortunate morsel's memories.

## Secret

Hypnovulfen have no power to mesmerize anyone holding a keepsake or memento received from a loved one, as it overpowers the false beckoning of the monster's gaze.

```statblock
"name": "Hypnovulfen (CrookedMoon24)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "253"
"hit_dice": "22d10 + 132"
"modifier": !!int "3"
"stats":
  - !!int "24"
  - !!int "16"
  - !!int "22"
  - !!int "14"
  - !!int "16"
  - !!int "22"
"speed": "60 ft."
"saves":
  - "dexterity": !!int "8"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 18"
"languages": "Common, Sylvan"
"cr": "15"
"traits":
  - "desc": "The hypnovulfen has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The hypnovulfen makes one Bite attack and one Claw attack, and it can\
      \ use Swallow."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +12, reach 5 ft. *Hit:* 18 (2d10 + 7) Piercing damage\
      \ plus 7 (2d6) Psychic damage. If the target is a Medium or smaller creature,\
      \ it has the Grappled condition (escape DC 17), and it has the Restrained condition\
      \ until the grapple ends."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +12, reach 5 ft. *Hit:* 14 (2d6 + 7) Piercing damage\
      \ plus 7 (2d6) Psychic damage. If the target is a Large or smaller creature,\
      \ it has the Prone condition."
    "name": "Claw"
  - "desc": "*Strength Saving Throw:* DC 20, one Medium or smaller creature Grappled\
      \ by the hypnovulfen (the hypnovulfen can have only one creature swallowed at\
      \ a time). *Failure:* The hypnovulfen swallows the target, which is no longer\
      \ Grappled. While swallowed, a creature has the Blinded and Restrained conditions,\
      \ has <span title=\"Player's Handbook (2024)\">Total Cover</span> against attacks\
      \ and other effects outside the hypnovulfen, and takes 21 (6d6) Psychic damage\
      \ at the start of each of the hypnovulfen's turns. If the creature dies from\
      \ this damage, the hypnovulfen absorbs its memories and regains 25 <span title=\"\
      Player's Handbook (2024)\">Hit Points</span>.\n\nIf the hypnovulfen takes 30\
      \ damage or more on a single turn from the swallowed creature, the hypnovulfen\
      \ must succeed on a DC 16 Constitution saving throw at the end of that turn\
      \ or regurgitate the creature, which falls in a space within 10 feet of the\
      \ hypnovulfen and has the Prone condition. If the hypnovulfen dies, a swallowed\
      \ creature is no longer Restrained and can escape from the corpse by using 15\
      \ feet of movement, exiting Prone."
    "name": "Swallow"
"bonus_actions":
  - "desc": "*Wisdom Saving Throw:* DC 19, each creature in a 30-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. A creature holding a keepsake from a\
      \ loved one succeeds automatically. *Failure:* The creature has the Charmed\
      \ condition until it takes damage. While [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ it has the Incapacitated condition and must move as close to the hypnovulfen\
      \ as possible by the safest route. The creature repeats the saving throw at\
      \ the end of each of its turns, ending the effect on itself on a success. After\
      \ 1 minute, it succeeds automatically."
    "name": "Hypnotic Gaze (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Hypnovulfen.webp"
```
^statblock

## Environment

forest, hill