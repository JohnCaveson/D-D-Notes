---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/planar-lower-planes
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Reveler of Stories (Witch)
---
# [Reveler of Stories (Witch)](3-Mechanics\CLI\bestiary\fiend/reveler-of-stories-witch-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 527*  

```statblock
"name": "Reveler of Stories (Witch) (CrookedMoon24)"
"size": "Large"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "127"
"hit_dice": "15d10 + 45"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "16"
  - !!int "14"
  - !!int "15"
  - !!int "20"
"speed": "40 ft."
"saves":
  - "wisdom": !!int "6"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+13"
"damage_resistances": "cold, fire"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., [truesight](/3-Mechanics/CLI/senses.md#Truesight)\
  \ 120 ft., passive Perception 16"
"languages": "Common; telepathy 120 ft."
"cr": "9"
"traits":
  - "desc": "As a <span title=\"Player's Handbook (2024)\">Bonus Action</span>, a\
      \ creature can recite the moral of a story using the same theme as the reveler's\
      \ Storied Form to weaken it for 1 hour. While weakened, the reveler can't take\
      \ <span title=\"Player's Handbook (2024)\">Reactions</span>, and its AC is reduced\
      \ by 4."
    "name": "Moral Quandary"
  - "desc": "The reveler takes on a specific form: Great Beast, Hero, or Witch. The\
      \ form determines certain traits and the theme of stories the reveler embodies\
      \ (powerful monsters, brave heroes, or wicked magicians, respectively)."
    "name": "Storied Form"
  - "desc": "If there is at least one creature with the Frightened condition within\
      \ 30 feet of the reveler at the end of its turn, the reveler gains 15 <span\
      \ title=\"Player's Handbook (2024)\">Temporary Hit Points</span>."
    "name": "Terror Feeding"
"actions":
  - "desc": "The reveler makes three Thrash attacks. It can replace one attack with\
      \ a use of Fabled Assault if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 10 ft. *Hit:* 18 (3d8 + 5) Force damage."
    "name": "Thrash"
  - "desc": "The reveler uses the option determined by its Storied Form:"
    "name": "Fabled Assault (Recharge 5-6)"
  - "desc": "*Dexterity Saving Throw:* DC 17, each creature in a 60-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 27 (6d8) Lightning damage,\
      \ and the target has the Frightened condition. While Frightened in this way,\
      \ the target's <span title=\"Player's Handbook (2024)\">Speed</span> is 0. A\
      \ Frightened target repeats the saving throw at the end of each of its turns,\
      \ ending the effect on itself on a success. After 1 minute, it succeeds automatically.\
      \ *Success:* Half damage only."
    "name": "Wicked Storm"
"reactions":
  - "desc": "Trigger: The reveler is hit by an attack roll. _Response:_ The reveler\
      \ adds 4 to its AC against that attack, possibly causing it to miss."
    "name": "Dramatic Reversal"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Reveler%20of%20Stories%20Witch.webp"
```
^statblock

## Environment

planar (lower planes), urban