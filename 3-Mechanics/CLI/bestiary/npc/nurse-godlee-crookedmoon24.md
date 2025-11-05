---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Nurse Godlee
---
# [Nurse Godlee](3-Mechanics\CLI\bestiary\npc/nurse-godlee-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 321*  

Nurse Sarah Godlee was one of the first to accept the Lethic Serum and serves as the second-in-command to Matron Lethica. Unlike the other orderlies, she wears no mask, as her form was only mildly contorted by the serum. Freed of the troubles that hindered her former life, she now runs the sanatorium's night-to-night operations as its undisputed enforcer. While Matron Lethica cloaks her methods in gentleness, Godlee prefers intimidation, control, and cruelty.

Godlee thrives on power, both over the orderlies under her command and the patients she claims to care for. She sometimes pilfers valuables from the patients to indulge her sense of authority.

```statblock
"name": "Nurse Godlee (CrookedMoon24)"
"size": "Medium"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "63"
"hit_dice": "14d8"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "11"
  - !!int "14"
  - !!int "17"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "strength": !!int "4"
  - "wisdom": !!int "5"
  - "charisma": !!int "2"
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "poison, psychic"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 30 ft., passive Perception\
  \ 17"
"languages": "Common, Deep Speech"
"cr": "3"
"traits":
  - "desc": "Godlee has a porcelain mask (AC 15; HP 15; <span title=\"Player's Handbook\
      \ (2024)\">Immunity</span> to Poison and Psychic damage). If Godlee starts its\
      \ turn and isn't wearing its mask, it must move as far as possible to retrieve\
      \ its mask if possible, or to reach the closest creature it can see or hear,\
      \ and it must attack that creature. If it can't see or hear any other creatures,\
      \ it either stands still and does nothing, or it destroys any objects in its\
      \ vicinity (50 percent chance of either)."
    "name": "Anchoring Mask"
"actions":
  - "desc": "Godlee makes two Stab attacks. If it hits a creature with a Stab attack,\
      \ it can use Inject if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing damage\
      \ plus 3 (1d6) Poison damage."
    "name": "Stab"
  - "desc": "*Constitution Saving Throw:* DC 13, a creature Godlee hit with a Stab\
      \ attack this turn. *Failure:* 10 (3d6) Psychic damage, and the target has the\
      \ Poisoned condition for 1 hour. Failure by 5 or More: The Poisoned target also\
      \ has the Unconscious condition until it takes damage or a creature within 5\
      \ feet of it takes an action to shake it awake. *Success:* Half damage only."
    "name": "Inject (Recharge 5-6)"
  - "desc": "Godlee has one of the following mutation action options:\n\n- **Cerebral\
      \ Graft.** Part of a psionic creature's brain is grafted to Godlee's own. *Intelligence\
      \ Saving Throw:* DC 13, one creature within 30 feet. *Failure:* 11 (2d10) Psychic\
      \ damage, and the target has the Stunned condition until the end of its next\
      \ turn. *Success:* Half damage only.  \n- **Tentacle Lash.** A tentacle writhes\
      \ beneath Godlee's skin or clothes. *Dexterity Saving Throw:* DC 13, each creature\
      \ in a 30-foot <span title=\"Player's Handbook (2024)\">Cone</span>. *Failure:*\
      \ 10 (3d6) Bludgeoning damage, and the target has the Prone condition. *Success:*\
      \ Half damage only.  "
    "name": "Mutation"
"bonus_actions":
  - "desc": "Godlee injects itself with a stimulant. Until the start of Godlee's next\
      \ turn, its <span title=\"Player's Handbook (2024)\">Speed</span> is doubled,\
      \ it can make one extra Stab attack when it takes the Multiattack action, and\
      \ it gains a +2 bonus to AC."
    "name": "Catalyst (Recharge after Short or Long Rest)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Sarah%20Godlee.webp"
```
^statblock