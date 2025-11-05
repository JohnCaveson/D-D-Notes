---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/planar-lower-planes
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Herald of Fools
---
# [Herald of Fools](3-Mechanics\CLI\bestiary\fiend/herald-of-fools-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 506*  

---

*Leader of Fiendish Revels*

---

Heralds of fools lead troupes of fiendish revelers in service to the enigmatic Lord of Fools, a clown or jester entity who is a curious mix of levity and cruelty (though always with a sense of irony). The heralds are agile and graceful, every movement a dance, spinning their banner poles in intricate displays that can swiftly turn from entertainment to death.

## Secret

Heralds of fools are wonderful dancers, and they must never stop dancing, or they quickly perish.

```statblock
"name": "Herald of Fools (CrookedMoon24)"
"size": "Medium"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"modifier": !!int "6"
"stats":
  - !!int "10"
  - !!int "22"
  - !!int "18"
  - !!int "13"
  - !!int "15"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "strength": !!int "4"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+10"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+7"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Abyssal, Common"
"cr": "10"
"traits":
  - "desc": "When the herald's <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ is 0, attack rolls made against it have <span title=\"Player's Handbook (2024)\"\
      >Advantage</span>, and if its <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ is 0 at the start of its turn, it takes 20 Necrotic damage."
    "name": "Endless Footwork"
  - "desc": "The herald doesn't provoke an Opportunity Attack when it leaves an enemy's\
      \ reach."
    "name": "Perfect Grace"
"actions":
  - "desc": "The herald makes three Banner Pole attacks. It can replace one attack\
      \ with a use of Lethal Jape."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10 (with <span title=\"Player's Handbook (2024)\"\
      >Advantage</span> if the target's <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ is 0), reach 10 ft. *Hit:* 11 (1d10 + 6) Slashing damage plus 13 (3d8) Thunder\
      \ damage, and if the target is a Large or smaller creature, the herald can move\
      \ it to any other unoccupied space within the Banner Pole's reach."
    "name": "Banner Pole"
  - "desc": "*Wisdom Saving Throw:* DC 15, a creature the herald can see within 60\
      \ feet. *Failure:* 24 (7d6) Psychic damage, and the target's <span title=\"\
      Player's Handbook (2024)\">Speed</span> is 0 until the end of its next turn.\
      \ *Success:* Half damage only."
    "name": "Lethal Jape"
"reactions":
  - "desc": "Trigger: An ally of the herald's within 60 feet misses with an attack\
      \ roll or fails a saving throw. _Response:_ The ally can reroll the d20 and\
      \ must use the new roll."
    "name": "Wave the Banner"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Herald%20of%20Fools.webp"
```
^statblock

## Environment

planar (lower planes), urban