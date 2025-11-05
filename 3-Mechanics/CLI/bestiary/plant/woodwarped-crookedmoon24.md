---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Woodwarped
---
# [Woodwarped](3-Mechanics\CLI\bestiary\plant/woodwarped-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 540*  

---

*Facsimile Grown of Root and Vine*

---

Whispered among forest dwellers is the tale of a cursed vine, said to creep into the bodies of the living or the dead, twisting them into woodwarped. These wooden creations of tangled roots and bark take shape into a crude yet eerily familiar imitation of their hosts. Those that slay their hosts are sometimes clad in the stolen clothing and armor of their victims, silently wandering the woods with hollow eyes that reflect the unnatural force that binds them to the forest. Cutting pieces from their bodies is a dangerous proposition, as the fragments quickly grow into new woodwarped.

## Secret

Woodwarped possess a deep fear of axes—tools capable of severing not only their bodies but their bond to the forest. The mere sight of an axe is enough to hold the creatures at bay, and the bite of its blade slices them like smoke.

```statblock
"name": "Woodwarped (CrookedMoon24)"
"size": "Medium"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "8"
  - !!int "17"
  - !!int "1"
  - !!int "10"
  - !!int "3"
"speed": "30 ft."
"damage_vulnerabilities": "slashing from Battleaxes; Handaxes"
"damage_resistances": "bludgeoning, piercing"
"condition_immunities": "[deafened](/3-Mechanics/CLI/conditions.md#Deafened), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened) (except by creatures holding\
  \ an axe)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 10"
"languages": ""
"cr": "4"
"traits":
  - "desc": "At the start of the woodwarped's turn, if it can see a creature holding\
      \ a Battleaxe, a Greataxe, or a Handaxe, it has the Frightened condition until\
      \ the start of its next turn."
    "name": "Aversion to Axes"
  - "desc": "At the start of each of its turns, the woodwarped deals 5 (2d4) Piercing\
      \ damage to any creature it is grappling or any creature grappling it."
    "name": "Thorns"
"actions":
  - "desc": "The woodwarped makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing damage\
      \ plus 4 (1d8) Poison damage. If the target is a Medium or smaller creature,\
      \ it has the Grappled condition (escape DC 14) from one of two claws."
    "name": "Claw"
  - "desc": "*Dexterity Saving Throw:* DC 13, each creature in a 15-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from the woodwarped,\
      \ with <span title=\"Player's Handbook (2024)\">Disadvantage</span> if Grappled\
      \ by it. *Failure:* 14 (4d6) Piercing damage, and the target has the Poisoned\
      \ condition. At the end of each of its turns, the target repeats the save, ending\
      \ the effect on itself on a success. After 1 minute, it succeeds automatically.\
      \ *Success:* Half damage only."
    "name": "Thorn Spray (Recharge 5-6)"
"reactions":
  - "desc": "Trigger: The woodwarped takes Slashing damage that isn't from a Battleaxe,\
      \ Greataxe, or Handaxe. _Response:_ A fragment of the woodwarped breaks off\
      \ and rapidly grows into a new Woodwarped in an unoccupied space within 5 feet\
      \ of the original. The new woodwarped is Small, has 10 <span title=\"Player's\
      \ Handbook (2024)\">Hit Points</span>, only has the Claw action, lacks this\
      \ <span title=\"Player's Handbook (2024)\">Reaction</span>, and takes its turn\
      \ on the original woodwarped's <span title=\"Player's Handbook (2024)\">Initiative</span>."
    "name": "Splintered Propagation (1/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Woodwarped.webp"
```
^statblock

## Environment

forest