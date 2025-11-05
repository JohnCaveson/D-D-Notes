---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Stonoga Blackstinger
---
# [Stonoga Blackstinger](3-Mechanics\CLI\bestiary\npc/stonoga-blackstinger-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 306*  

Stonoga Blackstinger ([Centipede Hag](/3-Mechanics/CLI/bestiary/fey/centipede-hag-crookedmoon24.md)) is the middle sister of the Vermintoll Coven. Her unnaturally tall and lanky body has morphed overthe years to more closely resemble the centipedes she favors, losing her nose and most of her toes and stretching her neck out by several feet.

Just as it was her sister Vessla's role in the coven to twist souls in preparation for sacrifice to the Crooked Queen, Stonoga is tasked with corrupting bodies. She cares not for the matters of mind and spirit, as all life to her is simply meat to be molded beneath her jagged fingers. But despite this, she has a jovial disposition, taking glee in savoring the suffering of her victims.

Unlike her sisters, she prefers to hide away in the deepest, darkest holes in the earth where she can be embraced by the squirming swarms of her beloved centipedes. It is in these places that never see the light of the moon where she conducts her alchemy, witchcraft, and fleshcrafting.

Stonoga has been waiting for the night that her younger sister Vessla is slain, a moment foreseen and deemed a necessary sacrifice by her older sister Golub. The two older hags conspired to allow the weasel hag to be butchered in the Crooked House, but Stonoga has no idea that she herself was deceived. Golub Graygullet believed the middle sister needed to die too, as whispered by the Crooked Queen with the promise of being elevated within the inevitable crooked court of Kehlenn. Golub will aid the characters in hunting down Stonoga if she can.

```statblock
"name": "Stonoga Blackstinger (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "178"
"hit_dice": "21d8 + 84"
"modifier": !!int "7"
"stats":
  - !!int "20"
  - !!int "16"
  - !!int "18"
  - !!int "16"
  - !!int "18"
  - !!int "21"
"speed": "30 ft., climb 30 ft."
"saves":
  - "intelligence": !!int "7"
  - "constitution": !!int "8"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+9"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+9"
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 18"
"languages": "Common, Deep Speech, Sylvan"
"cr": "10"
"traits":
  - "desc": "While within 30 feet of at least two hag allies, Stonoga can cast one\
      \ of the following spells, requiring no Material components, using the spell's\
      \ normal casting time, and using Intelligence as the spellcasting ability: Augury,\
      \ Find Familiar, Identify, Locate Object, [Lucky Charm](/3-Mechanics/CLI/spells/lucky-charm-crookedmoon24.md)\
      \ (lasts until Stonoga casts it again, or chooses to end it with no action required),\
      \ or Unseen Servant. Stonoga must finish a <span title=\"Player's Handbook (2024)\"\
      >Long Rest</span> before using this trait to cast that spell again.\n"
    "name": "Coven Magic"
  - "desc": "Stonoga is burned by soapy water. Treat a bucket or flask of it splashed\
      \ on Stonoga as a vial of Acid. If Stonoga is fully immersed in soapy water\
      \ at the start of its turn, it takes 20 Acid damage."
    "name": "Scoured Filth"
  - "desc": "Stonoga can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "Stonoga makes two Bite attacks or uses Spellcasting to cast Contagion.\
      \ It can also use Warping Caress."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 14 (2d8 + 5) Piercing damage\
      \ plus 4 (1d8) Necrotic damage, and the target has the Poisoned condition until\
      \ the start of Stonoga's next turn."
    "name": "Bite"
  - "desc": "*Constitution Saving Throw:* DC 17, one creature within 5 feet. *Failure:*\
      \ 19 (4d6 + 5) Necrotic damage, and the target gains 1 Exhaustion level. Until\
      \ the target's Exhaustion level is reduced to 0, its body is warped and twisted,\
      \ and it has <span title=\"Player's Handbook (2024)\">Disadvantage</span> on\
      \ ability checks and saving throws that use Strength or Dexterity. *Success:*\
      \ Half damage only. *Failure or Success:* If a Humanoid dies from this action,\
      \ Stonoga can spend 2 days of work to shape its corpse into a [Deepdreck](/3-Mechanics/CLI/bestiary/monstrosity/deepdreck-crookedmoon24.md),\
      \ or it can combine it with the corpse of a horse to create a [Fleshdobbin](/3-Mechanics/CLI/bestiary/monstrosity/fleshdobbin-crookedmoon24.md)."
    "name": "Warping Caress"
  - "desc": "Stonoga casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 17):\n\n**At\
      \ will:** Contagion, Disguise Self (24-hour duration), Hold Person, Invisibility\
      \ (self only)\n\n**1/day each:** Insect Plague (level 8 version), Polymorph"
    "name": "Spellcasting"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Stonoga%20Blackstinger.webp"
```
^statblock