---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/environment/planar-lower-levels
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Lord of Fools
---
# [The Lord of Fools](3-Mechanics\CLI\bestiary\npc/the-lord-of-fools-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 566*  

---

*Fiendish Master of Revels*

---

The Lord of Fools is the embodiment of revelry, cherishing amusement at any cost. He most often leads a procession of revelers of song, revelers of stories, and heralds of fools, compelling townsfolk and travelers to join their celebration to the exclusion of all other concerns. Many of these celebrants dance, drink, and make merry until they drop—sometimes dead! The Lord of Fools laughs all the louder and longer at their demise.

## Secret

The Lord of Fools thrives on laughter and amusement, so when someone doesn't react accordingly to one of his japes, he becomes enraged at that creature to the exclusion of others.

## Lord of Fools' Lair

The Lord of Fools' lair is the Fool's Revel carnival.

```statblock
"name": "The Lord of Fools (CrookedMoon24)"
"size": "Huge"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "190"
"hit_dice": "20d12 + 60"
"modifier": !!int "13"
"stats":
  - !!int "20"
  - !!int "16"
  - !!int "20"
  - !!int "16"
  - !!int "14"
  - !!int "23"
"speed": "50 ft."
"saves":
  - "wisdom": !!int "7"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+11"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+11"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+11"
"damage_immunities": "poison"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 17"
"languages": "all; telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "As a <span title=\"Player's Handbook (2024)\">Bonus Action</span>, a\
      \ creature can dismiss or belittle the lord's attempts at humor. If the creature\
      \ succeeds on a DC 16 Charisma (Deception) check, the lord has <span title=\"\
      Player's Handbook (2024)\">Disadvantage</span> on attack rolls against any target\
      \ other than that creature until the start of the creature's next turn."
    "name": "Bitter Medicine"
  - "desc": "The lord creates an illusion of a Small Humanoid jester in his space.\
      \ While he doesn't have the Incapacitated condition, the lord can move the image\
      \ up to 60 feet during his turn (no action required). The lord can perceive\
      \ and speak through this image as if he were in the image's space. The image\
      \ is insubstantial, but it can manipulate objects as if it has a Strength of\
      \ 10."
    "name": "Infinite Jest"
  - "desc": "If the lord fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The lord can take one <span title=\"Player's Handbook (2024)\">Reaction</span>\
      \ on every turn of combat."
    "name": "Reactive"
"actions":
  - "desc": "The lord makes two attacks, using Ribbon or Joy Buzzer in any combination.\
      \ If the lord has cast Project Image, he can make melee Joy Buzzer attacks from\
      \ the image's space."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 15 ft. *Hit:* 12 (2d6 + 5) Slashing damage.\
      \ If the target is a Large or smaller creature, it has the Grappled condition\
      \ (escape DC 15) from one of six ribbons. It has the Restrained condition until\
      \ the grapple ends."
    "name": "Ribbon"
  - "desc": "The lord's Infinite Jest illusion moves to a target within range. Melee\
      \ or Ranged <span title=\"Player's Handbook (2024)\">Attack Roll</span>: +10,\
      \ reach 5 ft. or range 60 ft. *Hit:* 24 (3d12 + 5) Lightning damage, and the\
      \ target can't take <span title=\"Player's Handbook (2024)\">Reactions</span>\
      \ until the end of the lord's next turn. *Hit or Miss:* The jester vanishes\
      \ and reappears in the lord's space."
    "name": "Joy Buzzer"
  - "desc": "The lord throws a massive pie that explodes in corrosive custard. *Dexterity\
      \ Saving Throw:* DC 18, each creature in a 20-foot-radius <span title=\"Player's\
      \ Handbook (2024)\">Sphere</span> centered on a point the lord can see within\
      \ 100 feet. *Failure:* 16 (3d10) Acid damage, and the target has the Blinded\
      \ condition until the end of the lord's next turn. *Success:* Half damage only."
    "name": "Exploding Pie (Recharge 5-6)"
  - "desc": "The lord casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 19):\n\n**At\
      \ will:** Tasha's Hideous Laughter, Project Image (appears as a Small Humanoid\
      \ jester), Vicious Mockery (4d6 Psychic damage)\n\n**1/day each:** Otto's Irresistible\
      \ Dance, Mordenkainen's Magnificent Mansion"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The lord vanishes in a burst of confetti and ribbons and teleports to\
      \ an unoccupied space he can see within 30 feet."
    "name": "Ribbon Step"
"regional_effects":
  - "desc": "The region containing the Lord of Fools' lair is changed by its presence,\
      \ creating the following effects:\n\n- **Empty Treats.** Within 1 mile of the\
      \ lair, carnival snack food is abundant even in unlikely places. The food is\
      \ delicious but offers no sustenance. A creature that eats the food can't feel\
      \ the effects of starvation (though they still suffer the effects) for 24 hours.\
      \  \n- **Pratfalls.** Within 1 mile of the lair, ability checks or saving throws\
      \ made to avoid the Prone condition have <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span>.  \n\nIf the Lord of Fools dies or moves his lair elsewhere,\
      \ these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The lord moves up to half his <span title=\"Player's Handbook (2024)\"\
      >Speed</span> without provoking Opportunity Attacks, during which he can move\
      \ through other creature's spaces without expending extra movement to do so.\
      \ A creature whose space the lord enters takes 7 (2d6) Psychic damage. A creature\
      \ takes this damage only once per turn."
    "name": "Frolic"
  - "desc": "The lord uses Spellcasting to cast either Irresistible Dance or Vicious\
      \ Mockery."
    "name": "Joke's on You"
  - "desc": "*Strength Saving Throw:* DC 18, each creature the lord is grappling.\
      \ *Failure:* 22 (4d10) Bludgeoning damage. *Success:* Half damage. *Failure\
      \ or Success:* The lord can't take this action again until the start of its\
      \ next turn."
    "name": "Ribbon Dance"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/The%20Lord%20of%20Fools.webp"
```
^statblock

## Environment

planar (lower levels), urban