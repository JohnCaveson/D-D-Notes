---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Maidenwood
---
# [Maidenwood](3-Mechanics\CLI\bestiary\plant/maidenwood-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 516*  

---

*Twitch-Warped Ambushing Tree*

---

Maidenwoods are creatures birthed from tree stumps by old magics, often arising from curses that turn the forest against a transgressor. They scuttle on roots like legs, and the broken trunk becomes a fierce, grinding maw. The maidenwood's tendrils blossom into lifelike figures it uses to lure its prey close.

## Secret

The curse that maintains a maidenwood unravels if one is offered an apple—an ancient trick used by witches turned against them.

```statblock
"name": "Maidenwood (CrookedMoon24)"
"size": "Huge"
"type": "plant"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "103"
"hit_dice": "9d12 + 45"
"modifier": !!int "-1"
"stats":
  - !!int "22"
  - !!int "8"
  - !!int "20"
  - !!int "10"
  - !!int "12"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 11"
"languages": "Common, Druidic, Sylvan"
"cr": "9"
"traits":
  - "desc": "The maidenwood must accept and eat an apple offered to it or to its lure.\
      \ The maidenwood then takes 55 (10d10) Poison damage and has the Poisoned condition\
      \ for 1 minute."
    "name": "Undoing Gift (1/Day)"
"actions":
  - "desc": "The maidenwood makes two Tendril attacks. It can replace one attack with\
      \ a Chew attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 10 ft. *Hit:* 15 (2d8 + 6) Bludgeoning\
      \ damage. If the target is a Large or smaller creature, it has the Grappled\
      \ condition (escape DC 16) from one of two tendrils. Until the grapple ends,\
      \ it has the Restrained condition."
    "name": "Tendril"
  - "desc": "*Melee Attack Roll:* +10, reach 5 ft. *Hit:* 11 (1d10 + 6) Piercing damage.\
      \ If the target has the Restrained condition, it takes an extra 18 (4d8) Piercing\
      \ damage."
    "name": "Chew"
"bonus_actions":
  - "desc": "The maidenwood shapes its lure into a Small or Medium Humanoid, or it\
      \ retracts the lure. The maidenwood can speak through the lure and move it anywhere\
      \ within reach of its tendrils, and it causes the following effect—*Intelligence\
      \ Saving Throw:* DC 15, one creature within 30 feet of the lure. *Failure:*\
      \ The target has the Charmed condition until the start of the maidenwood's next\
      \ turn. The Charmed target must approach the lure as closely as it can. The\
      \ maidenwood has <span title=\"Player's Handbook (2024)\">Advantage</span> on\
      \ attack rolls against the Charmed target. If the target takes damage, the Charmed\
      \ condition ends at the end of the current turn."
    "name": "Lure"
"reactions":
  - "desc": "Trigger: The maidenwood succeeds on a saving throw against a spell or\
      \ other magical effect, or a spell attack roll misses it. _Response:_ The maidenwood\
      \ gains 10 <span title=\"Player's Handbook (2024)\">Temporary Hit Points</span>."
    "name": "Absorb Magic"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Maidenwood.webp"
```
^statblock

## Environment

forest, swamp