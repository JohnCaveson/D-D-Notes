---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/planar-shadow
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Necrolisk
---
# [Necrolisk](3-Mechanics\CLI\bestiary\dragon/necrolisk-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 518*  

---

*Subterranean Spirit-Devouring Drake*

---

Necrolisks are subterranean dragons that feed on the essence of spirits. Tunneling through the ground in search of corpses, especially those buried in graveyards and crypts, they defile the graves and feed on the bodies in an effort to stir up restless spirits, which are then snared in the necrolisks' ephemeral saliva and devoured. Creatures of flesh and blood that disturb the dragons might also find themselves as a less preferred, but passable, meal.

## Secret

Necrolisks are severely allergic to a concoction of lavender, nightshade, and lilies, which causes them to vomit uncontrollably—a boon to anyone swallowed by the monsters.

```statblock
"name": "Necrolisk (CrookedMoon24)"
"size": "Huge"
"type": "dragon"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "178"
"hit_dice": "17d12 + 68"
"modifier": !!int "1"
"stats":
  - !!int "22"
  - !!int "13"
  - !!int "19"
  - !!int "7"
  - !!int "13"
  - !!int "10"
"speed": "40 ft., burrow 40 ft., climb 40 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "necrotic"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., tremorsense\
  \ 120 ft., passive Perception 15"
"languages": "understands Draconic but can't speak"
"cr": "10"
"traits":
  - "desc": "The necrolisk ignores <span title=\"Player's Handbook (2024)\">Immunity</span>\
      \ to the Grappled and Restrained conditions of a creature with the Incorporeal\
      \ Movement trait. Creatures swallowed by the necrolisk can't pass through it\
      \ using Incorporeal Movement or through the Ethereal Plane, and creatures can't\
      \ teleport out of its stomach."
    "name": "Entrapping Saliva"
  - "desc": "If the necrolisk eats a specific concoction of herbs worth 25 GP (such\
      \ as if a swallowed creature pours them into its stomach as a Utilize action),\
      \ at the end of the turn, the necrolisk regurgitates anything in its stomach\
      \ as if it failed the saving throw described in its Swallow <span title=\"Player's\
      \ Handbook (2024)\">Bonus Action</span>."
    "name": "Herb Allergy"
  - "desc": "The necrolisk can climb difficult surfaces, including along ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The necrolisk can burrow through solid rock at half its <span title=\"\
      Player's Handbook (2024)\">Burrow Speed</span> and leaves a 10-foot-diameter\
      \ tunnel in its wake."
    "name": "Tunneler"
"actions":
  - "desc": "The necrolisk makes one Bite attack and one Claws attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 15 ft. *Hit:* 15 (2d8 + 6) Piercing damage\
      \ plus 3 (1d6) Force damage. If the target is a Large or smaller creature, it\
      \ has the Grappled condition (escape DC 16). Until the grapple ends, it has\
      \ the Restrained condition."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +10, reach 10 ft. *Hit:* 9 (1d6 + 6) Slashing damage\
      \ plus 4 (1d8) Force damage."
    "name": "Claws"
  - "desc": "*Dexterity Saving Throw:* DC 16, each creature in a 60-foot-long, 5-foot-wide\
      \ <span title=\"Player's Handbook (2024)\">Line</span>. *Failure:* 42 (12d6)\
      \ Force damage, and the target has the Restrained condition until the end of\
      \ its next turn. *Success:* Half damage only."
    "name": "Ephemeral Spit (Recharge 5-6)"
"bonus_actions":
  - "desc": "*Dexterity Saving Throw:* DC 18, one Large or smaller creature Grappled\
      \ by the necrolisk (the necrolisk can only have one creature swallowed at a\
      \ time). *Failure:* The necrolisk swallows the target, which is no longer Grappled.\
      \ While swallowed, the creature has the Blinded and Restrained conditions, has\
      \ <span title=\"Player's Handbook (2024)\">Total Cover</span> against attacks\
      \ and other effects outside the necrolisk, and takes 21 (6d6) Force damage at\
      \ the start of each of the necrolisk's turns.\n\nIf the necrolisk takes 30 damage\
      \ or more on a single turn from the swallowed creature, the necrolisk must succeed\
      \ on a DC 14 Constitution saving throw at the end of that turn or regurgitate\
      \ the creature, which falls in a space within 10 feet of the necrolisk and has\
      \ the Prone condition. If the necrolisk dies, a swallowed creature is no longer\
      \ Restrained and can escape from the corpse by using 15 feet of movement, exiting\
      \ Prone."
    "name": "Swallow"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Necrolisk.webp"
```
^statblock

## Environment

planar (shadow), underground