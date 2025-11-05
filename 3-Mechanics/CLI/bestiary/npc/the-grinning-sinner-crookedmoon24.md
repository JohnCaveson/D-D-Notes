---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/humanoid/lizardfolk
- ttrpg-cli/monster/type/humanoid/warlock
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Grinning Sinner
---
# [The Grinning Sinner](3-Mechanics\CLI\bestiary\npc/the-grinning-sinner-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 558*  

---

*Dealer of Jinxes*

---

Once the dashing pirate captain Briggsy Kratch, the crocodile-folk now known as the Grinning Sinner made a bargain for power with a spirit known as Snake Eye Jack. The sinner grew discontent with the power he was gifted and tricked Jack into a coffin before sealing him inside. Now the Grinning Sinner siphons his trapped patron's cursed power and makes bargains of his own to snare the souls of the desperate and foolish.

## Secret

The Grinning Sinner holds his prowess and reputation as a fearsome and successful pirate captain above all; causing him to doubt his renown can turn his hexed magic against him.

## Grinning Sinner's Lair

The Grinning Sinner's lair is the derelict riverboat casino, the *Dead Man's Hand*.

```statblock
"name": "The Grinning Sinner (CrookedMoon24)"
"size": "Large"
"type": "humanoid"
"subtype": "Lizardfolk, Warlock"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "152"
"hit_dice": "16d10 + 64"
"modifier": !!int "11"
"stats":
  - !!int "19"
  - !!int "16"
  - !!int "19"
  - !!int "14"
  - !!int "16"
  - !!int "20"
"speed": "30 ft. (60 ft. while on coffin)"
"saves":
  - "strength": !!int "8"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+10"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+9"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+9"
"damage_resistances": "necrotic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft. (unimpeded\
  \ by magical <span title=\"Player's Handbook (2024)\">Darkness</span>), passive\
  \ Perception 13"
"languages": "Common, Infernal, Primordial (Aquan)"
"cr": "9"
"traits":
  - "desc": "The sinner has a magic coffin that has <span title=\"Player's Handbook\
      \ (2024)\">Immunity</span> to all damage. While standing on the coffin, the\
      \ sinner rides it on a ghostly wave of swamp water with a <span title=\"Player's\
      \ Handbook (2024)\">Speed</span> of 60 feet and can move over liquids as if\
      \ they were solid."
    "name": "Coffin Rider"
  - "desc": "The sinner has a bottle that holds cursed magic. The bottle has AC 15,\
      \ HP 25, and <span title=\"Player's Handbook (2024)\">Immunity</span> to all\
      \ damage except Force. If the bottle is destroyed, the sinner can magically\
      \ create a new one when he finishes a <span title=\"Player's Handbook (2024)\"\
      >Long Rest</span>."
    "name": "Curse Bottle"
  - "desc": "If the sinner fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "As a <span title=\"Player's Handbook (2024)\">Bonus Action</span>, a\
      \ creature can insult the sinner's skill and renown as a pirate captain. The\
      \ sinner must succeed on a DC 15 Wisdom saving throw or take 10 Psychic damage\
      \ and have <span title=\"Player's Handbook (2024)\">Disadvantage</span> on attack\
      \ rolls against any target other than the creature."
    "name": "Overweening Pride"
"actions":
  - "desc": "The sinner makes two attacks, using Hex Grasp or Blunderbuss in any combination.\
      \ He can replace one attack with a use of Spellcasting to cast Bane."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 12 (2d6 + 5) Necrotic damage.\
      \ If the target is a creature, it is cursed until the start of the sinner's\
      \ next turn, or until the sinner curses it in this way again. While cursed,\
      \ the target has <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on attack rolls and on ability checks that rely on an ability of the sinner's\
      \ choice."
    "name": "Hex Grasp"
  - "desc": "*Ranged Attack Roll:* +9, range 30/90 ft. *Hit:* 18 (3d8 + 5) Force damage.\
      \ If the target is a Large or smaller creature, it is pushed up to 10 feet straight\
      \ away."
    "name": "Blunderbuss"
  - "desc": "The sinner unleashes one of the following curses from his blunderbuss:\n\
      \n- **Jack's Anguish.** A magenta wave fires out with a deep, wailing moan.\
      \ *Wisdom Saving Throw:* DC 17, each creature in a 30-foot <span title=\"Player's\
      \ Handbook (2024)\">Cone</span>. *Failure:* 11 (2d10) Psychic damage, and the\
      \ target has the Frightened condition.  \n\n    The target repeats the saving\
      \ throw at the end of each of its turns, ending the effect on itself on a success.\
      \  \n\n    After 1 minute, it automatically succeeds. *Success:* Half damage\
      \ only.  \n- **Shadowy Friends.** A wave of shadow coughs forth and wraps around\
      \ foes. *Dexterity Saving Throw:* DC 17, each creature in a 15-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* The target has the Paralyzed\
      \ condition until the end of the sinner's next turn. If a Paralyzed target takes\
      \ damage, the condition ends early.  "
    "name": "Curse Blast (Recharge 5-6)"
  - "desc": "The sinner casts one of the following spells using his <span title=\"\
      Player's Handbook (2024)\">Curse</span> Bottle (and no other Material components)\
      \ and using Charisma as the spellcasting ability (spell save DC 17):\n\n**At\
      \ will:** Bane, Bestow Curse, Major Image, Remove Curse\n\n**1/day each:** Animate\
      \ Dead, Creation, Darkness"
    "name": "Spellcasting (Requires Curse Bottle)"
"regional_effects":
  - "desc": "The region containing the Grinning Sinner's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Fate's Wheel.** Within 1 mile of the\
      \ lair, if the number rolled on a die to restore <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> is even, increase the number rolled by 1. If the\
      \ number rolled is odd, reduce it by 1.  \n- **Run of Bad Luck.** Within 1 mile\
      \ of the lair, a creature that rolls a 1 on a <span title=\"Player's Handbook\
      \ (2024)\">D20 Test</span> must subtract 1d4 from its next <span title=\"Player's\
      \ Handbook (2024)\">D20 Test</span>.  \n\nIf the Grinning Sinner dies or moves\
      \ his lair elsewhere, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "*Wisdom Saving Throw:* DC 17, one creature cursed by the sinner or affected\
      \ by his Bane spell within 30 feet. *Failure:* 6 (1d12) Force damage."
    "name": "Barbed Curse"
  - "desc": "The sinner teleports to an unoccupied space he can see within 30 feet.\
      \ He makes one Hex Grasp attack before or after teleporting and can't take this\
      \ action again until the start of his next turn."
    "name": "Grinning Grasp"
  - "desc": "*Charisma Saving Throw:* DC 17, each creature within a 20-foot <span\
      \ title=\"Player's Handbook (2024)\">Emanation</span> originating from the sinner.\
      \ *Failure:* The target has the Prone condition. *Failure or Success:* The sinner\
      \ can't take this action again until the start of his next turn."
    "name": "Jinxed Ground"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Grinning%20Sinner.webp"
```
^statblock

## Environment

coastal, swamp