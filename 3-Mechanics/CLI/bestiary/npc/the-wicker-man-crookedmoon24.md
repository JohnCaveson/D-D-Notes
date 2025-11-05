---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Wicker Man
---
# [The Wicker Man](3-Mechanics\CLI\bestiary\npc/the-wicker-man-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 576*  

---

*Blazing Sacrificial Colossus*

---

The ultimate expression of a cult's dedication to its patron is the Wicker Man. This massive Construct is woven from wicker and bound with wire and iron bands in the shape of a great bipedal effigy. The chest cavity and limbs are hollow where sacrifices can be secured, with the wicker skin forming cage-like bars and gaps. Celebrated and protected with a cult's very existence, the Wicker Man stands silent and impassive until it is ignited while filled with living sacrifices. Then it comes to life and seeks to consume any nonbelievers—and sometimes even the faithful.

## Wicker Man's Lair

The Wicker Man's lair is the hilltop where it is constructed and venerated.

```statblock
"name": "The Wicker Man (CrookedMoon24)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "155"
"hit_dice": "10d20 + 50"
"modifier": !!int "12"
"stats":
  - !!int "22"
  - !!int "14"
  - !!int "20"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "7"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [stunned](/3-Mechanics/CLI/conditions.md#Stunned),\
  \ [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 15"
"languages": "understands all but can't speak"
"cr": "15"
"traits":
  - "desc": "At the end of the each of the Wicker Man's turns, each creature of its\
      \ choice in a 15-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the Wicker Man takes 5 (1d10) Fire damage. Creatures and\
      \ flammable objects in the <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ start burning."
    "name": "Burning Aura"
  - "desc": "If the Wicker Man fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
  - "desc": "The Wicker Man has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "The Wicker Man can take a <span title=\"Player's Handbook (2024)\">Reaction</span>\
      \ on every turn of combat."
    "name": "Reactive"
  - "desc": "The Wicker Man has 3 Soul Motes. It gains 1 Soul Mote when a creature\
      \ that isn't a Construct or Undead dies within 30 feet of it. The Wicker Man\
      \ can expend Soul Motes to fuel Soul Mote <span title=\"Player's Handbook (2024)\"\
      >Reactions</span>. When the Wicker Man finishes a <span title=\"Player's Handbook\
      \ (2024)\">Long Rest</span>, its Soul Mote total resets to 3."
    "name": "Soul Motes"
"actions":
  - "desc": "The Wicker Man makes two Blazing Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +11, reach 15 ft.  *Hit:* 15 (2d8 + 6) Bludgeoning\
      \ damage plus 9 (2d8) Fire damage."
    "name": "Blazing Slam"
  - "desc": "*Dexterity Saving Throw:* DC 18, each creature in a 60-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 35 (10d6) Fire damage. *Success:*\
      \ Half damage. *Failure or Success:* A creature reduced to 0 <span title=\"\
      Player's Handbook (2024)\">Hit Points</span> by this damage is reduced to ash,\
      \ and its soul is absorbed into the Wicker Man. The creature can't be restored\
      \ to life by any means until the wicker man is destroyed."
    "name": "Cremating Flame (Recharge 6)"
"reactions":
  - "desc": "Trigger: The Wicker Man hits with an attack roll. _Response:_ The Wicker\
      \ Man expends 1 Soul Mote, and the hit becomes a <span title=\"Player's Handbook\
      \ (2024)\">Critical Hit</span>."
    "name": "Crushing Blow (Soul Mote)"
  - "desc": "Trigger: The Wicker Man starts its turn. _Response:_ The Wicker Man expends\
      \ 1 Soul Mote and regains 20 <span title=\"Player's Handbook (2024)\">Hit Points</span>."
    "name": "Repair (Soul Mote)"
"regional_effects":
  - "desc": "The region containing the Wicker Man's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Biting Flames.** Within 1 mile of the\
      \ lair, when Fire damage is dealt to a creature outside the Wicker Man's dedicated\
      \ cult that has <span title=\"Player's Handbook (2024)\">Resistance</span> or\
      \ <span title=\"Player's Handbook (2024)\">Immunity</span> to Fire damage, the\
      \ creature takes an extra 1d6 Necrotic damage.  \n- **Endless Praise.** Within\
      \ 1 mile of the lair, cultists of the Wicker Man who sing their cult's praises\
      \ or hymns can be heard up to 300 feet away, even through a Silence spell. \
      \ \n\nIf the Wicker Man dies or moves its lair elsewhere, these effects end\
      \ immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "*Strength Saving Throw:* DC 19, one creature within 15 feet. *Failure:*\
      \ The target has the Grappled condition (escape DC 16) from one of two hands,\
      \ and it has the Restrained condition until the grapple ends. At the start of\
      \ the Wicker Man's turn, the Grappled creature takes 10 (3d6) Fire damage. *Failure\
      \ or Success:* The Wicker Man can't take this action again until the start of\
      \ its next turn."
    "name": "Burning Clutch"
  - "desc": "The Wicker Man makes one Blazing Slam attack. The Wicker Man can't take\
      \ this action again until the start of its next turn."
    "name": "Slam"
  - "desc": "The Wicker Man moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span> without provoking Opportunity Attacks."
    "name": "Stride"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Wickerman.webp"
```
^statblock

## Environment

any