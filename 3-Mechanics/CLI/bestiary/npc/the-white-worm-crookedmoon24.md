---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/19
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/environment/underwater
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- The White Worm
---
# [The White Worm](3-Mechanics\CLI\bestiary\npc/the-white-worm-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 574*  

---

*Eldritch Devourer of Memories*

---

Born of a forgotten realm beyond the stars, the White Worm is an eldritch horror resembling a humungous, pallid grub that ravenously hungers for memory. Greedily consuming the memories of any beings capable of remembering, its mere existence sends out shockwaves of alien psychic energy. It also serves as the queen of a hivemind colony of infinite wormlike spawn that seek mortal hosts to feast upon and control.

## Secret

A specific series of constellations and star paths through the heavens is a deadly poison to the White Worm if it consumes that memory.

## White Worm's Lair

The White Worm's lair is a secluded lake and the shores surrounding it.

```statblock
"name": "The White Worm (CrookedMoon24)"
"size": "Gargantuan"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "330"
"hit_dice": "20d20 + 120"
"modifier": !!int "10"
"stats":
  - !!int "28"
  - !!int "7"
  - !!int "22"
  - !!int "7"
  - !!int "19"
  - !!int "21"
"speed": "50 ft., burrow 30 ft., swim 50 ft."
"saves":
  - "wisdom": !!int "10"
  - "constitution": !!int "12"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "tremorsense 60 ft., [truesight](/3-Mechanics/CLI/senses.md#Truesight) 60\
  \ ft., passive Perception 14"
"languages": "understands all but can't speak; telepathy 120 ft."
"cr": "19"
"traits":
  - "desc": "If a creature tries to read the worm's mind, that creature must succeed\
      \ on a DC 19 Intelligence saving throw or have the Stunned condition. The creature\
      \ repeats the save at the end of each of its turns, ending the effect on itself\
      \ on a success. After 1 minute, it succeeds automatically."
    "name": "Inscrutable Mind"
  - "desc": "If the worm fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day, or 4/Day in Lair)"
  - "desc": "If the worm uses Devour Mind on a creature that knows a special sequence\
      \ of constellations and their path through the sky, at the start of the target's\
      \ next turn, the worm takes 50 Psychic damage and Devour Mind ends."
    "name": "Poisoned Knowledge"
  - "desc": "The worm can burrow through solid rock at half its <span title=\"Player's\
      \ Handbook (2024)\">Burrow Speed</span> and leaves a 10-foot-diameter tunnel\
      \ in its wake."
    "name": "Tunneler"
"actions":
  - "desc": "The worm makes one Bite attack and uses Psychic Caress on one or two\
      \ creatures."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +15, reach 10 ft. *Hit:* 25 (3d10 + 9) Piercing\
      \ damage plus 7 (2d6) Force damage. If the target is a Large or smaller creature,\
      \ it has the Grappled condition (escape DC 19)."
    "name": "Bite"
  - "desc": "*Intelligence Saving Throw:* DC 19, one creature the worm can see within\
      \ 60 feet. *Failure:* 17 (5d6) Psychic damage, and the target has the Frightened\
      \ condition until the start of the worm's next turn. *Success:* Half damage\
      \ only."
    "name": "Psychic Caress"
  - "desc": "The worm vanishes and magically enters the mind of a creature it can\
      \ see within 60 feet of it. The worm can't target a creature under the effect\
      \ of  the Mind Blank or Protection from Evil and Good spells. While in the target's\
      \ mind, the worm can't take actions, and the target experiences the worm appearing\
      \ in its memories as it devours each one. At the end of each of the target's\
      \ turns, it takes 88 (16d10) Psychic damage. If this damage reduces the target\
      \ to 0 <span title=\"Player's Handbook (2024)\">Hit Points</span>, the target\
      \ is <span title=\"Player's Handbook (2024)\">Stable</span> but loses all its\
      \ memories permanently. Only a Wish spell can restore the lost memories.\n\n\
      Devour Mind ends if the target is reduced to 0 <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> and the worm appears in an unoccupied space within\
      \ 60 feet of the target. Devour Mind can also be ended in the following ways:\n\
      \n- As an action, the target mentally duels the worm  and makes a DC 20 ability\
      \ check using Intelligence, Wisdom, or Charisma (its choice). On a success,\
      \ the worm must succeed on a Charisma saving throw with a DC equal to the check's\
      \ total or Devour Mind ends.  \n- Devour Mind ends if the target receives an\
      \ effect  that ends possession, including the Dispel Evil and Good spell.  \n\
      - If the target takes damage, the worm takes Psychic damage equal to half that\
      \ amount. It must succeed on a Charisma saving throw with a DC equal to the\
      \ Psychic damage taken, or Devour Mind ends.  "
    "name": "Devour Mind (1/Day)"
"regional_effects":
  - "desc": "The region containing the White Worm's lair is changed by its presence,\
      \ creating the following effects:\n\n- **Alien Growth.** Strange life grows\
      \ rampant within 1 mile of the lair. In that region, Grick, Purple Worm, and\
      \ [Wormhost Surgeons](/3-Mechanics/CLI/bestiary/aberration/wormhost-surgeon-crookedmoon24.md)\
      \ are common.  \n- **Psychic Phantoms.** Within 1 mile of the lair, creatures\
      \ are plagued by horrid nightmares. When a creature sleeps or enters a Trance\
      \ and finishes a <span title=\"Player's Handbook (2024)\">Long Rest</span> in\
      \ that area, it must succeed on a DC 15 Wisdom saving throw or gain no benefit\
      \ from finishing the rest.  \n\nIf the White Worm dies or moves its lair elsewhere,\
      \ these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, The can expend a use to take one of the following actions.\
  \ The regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The worm moves up to its <span title=\"Player's Handbook (2024)\">Speed</span>\
      \ without provoking Opportunity Attacks."
    "name": "Slither"
  - "desc": "The worm disgorges a slimy spray of pale, parasitic worms. *Constitution\
      \ Saving Throw:* DC 20, each creature in a 60-foot <span title=\"Player's Handbook\
      \ (2024)\">Cone</span>. *Failure:* The target is infested with parasitic worms\
      \ and has the Poisoned condition. At the start of the Poisoned target's turn,\
      \ it takes 7 (2d6) Necrotic plus 7 (2d6) Psychic damage as the worms burrow\
      \ toward its brain. A creature reduced to 0 <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> by this damage dies and then rises 24 hours later\
      \ as a [Wormhost Surgeon](/3-Mechanics/CLI/bestiary/aberration/wormhost-surgeon-crookedmoon24.md).\
      \ The infesting worms are killed by any effect that ends the Poisoned condition\
      \ on the target, or if 10 Poison damage or more is dealt to it. *Failure or\
      \ Success:* The worm can't take this action again until the start of its next\
      \ turn."
    "name": "Spawn Parasites"
  - "desc": "The worm makes one Bite attack. It can't take this action again until\
      \ the start of its next turn."
    "name": "Strike"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/White%20Worm.webp"
```
^statblock

## Environment

coastal, underground, underwater