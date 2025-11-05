---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Ghostlight Locomotive
---
# [The Ghostlight Locomotive](3-Mechanics\CLI\bestiary\npc/the-ghostlight-locomotive-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 556*  

---

*Corrupted Ghost Train*

---

The Ghostlight Locomotive is the engine of a phantom train that travels unseen between the realms of life and death, ferrying souls of the dead to their afterlife. During its normal operation, the locomotive burns doomed spirits for fuel and races along spectral, misty rails that appear as it travels, and it has little awareness beyond its crucial task.

Only a drastic event, such as the corruption of its soul-made fuel source, can turn the Ghostlight Locomotive from its endless duty, whereupon it stokes a consciousness of the innumerable souls it has burned and vents the fury of the damned upon any obstacles in its path. When pressed, the residue of wicked souls left from the burning of its corrupted fuel overwhelms the engine's amoral nature, driving it to malevolent and hateful destruction.

## Ghostlight Locomotive's Lair

The Ghostlight Locomotive's lair is a 1-mile-radius Emanation of shrouding mist originating from the locomotive. This mist doesn't extend within the cars of the *Ghostight Express* that the locomotive pulls.

```statblock
"name": "The Ghostlight Locomotive (CrookedMoon24)"
"size": "Gargantuan"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "94"
"hit_dice": "7d20 + 21"
"modifier": !!int "5"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "17"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "50 ft."
"saves":
  - "wisdom": !!int "2"
  - "charisma": !!int "2"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
"damage_resistances": "fire, necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 10"
"languages": "understands all but can't speak"
"cr": "4"
"traits":
  - "desc": "When the locomotive is Bloodied, it regains all expended uses of Legendary\
      \ <span title=\"Player's Handbook (2024)\">Resistance</span> and enters a malevolent\
      \ form for 12 hours. In this form, it is Chaotic Evil and can use its Multiattack\
      \ action."
    "name": "Crooked Switch (1/Day)"
  - "desc": "If the locomotive fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
"actions":
  - "desc": "The locomotive makes two Rail Slam attacks."
    "name": "Multiattack (Crooked Switch Only)"
  - "desc": "*Melee Attack Roll:* +6, reach 10 ft. *Hit:* 9 (1d10 + 4) Bludgeoning\
      \ damage, and the target is pushed up to 10 feet straight away."
    "name": "Rail Slam"
  - "desc": "*Constitution Saving Throw:* DC 13, each creature in a 30-foot <span\
      \ title=\"Player's Handbook (2024)\">Cone</span>. *Failure:* 10 (3d6) Necrotic\
      \ damage. *Success:* Half damage."
    "name": "Spirit Exhaust (Recharge 6)"
"regional_effects":
  - "desc": "The region containing the Ghostlight Locomotive's lair is changed by\
      \ its presence, creating the following effects:\n\n- **Ghastly Shroud.** When\
      \ a creature that isn't Undead finishes a <span title=\"Player's Handbook (2024)\"\
      >Short</span> or <span title=\"Player's Handbook (2024)\">Long Rest</span> within\
      \ 1 mile of the locomotive, the creature must succeed on a DC 15 Constitution\
      \ saving throw or any time it regains <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span>, it only regains half the amount. This effect ends when the\
      \ creature next finishes a <span title=\"Player's Handbook (2024)\">Long Rest</span>\
      \ or receives a Lesser Restoration spell or similar magic.  \n- **Spirit Calling.**\
      \ Within 1 mile of the locomotive, <span title=\"Player's Handbook (2024)\"\
      >Hostile</span> [Shrouded](/3-Mechanics/CLI/bestiary/undead/shrouded-crookedmoon24.md)\
      \ and Specters are abundant and drawn to any creature that attacks the Ghostlight\
      \  \n\n    Locomotive or that tries to keep pace with, climb, or enter the *Ghostlight\
      \ Express*.  \n\nIf the Ghostlight Locomotive dies, these effects end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The locomotive moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span> in a straight line without provoking Opportunity Attacks.\n\n\
      A Large or smaller creature whose space it passes through has the Grappled condition\
      \ (escape DC 14) from the spectral rails."
    "name": "Ghostly Rails"
  - "desc": "The locomotive blows its wailing steam whistle. *Wisdom Saving Throw:*\
      \ DC 13, one creature within 30 feet. *Failure:* 4 (1d8) Psychic damage, and\
      \ the target has the Frightened condition until the end of its next turn. *Failure\
      \ or Success:* The locomotive can't take this action again until the start of\
      \ its next turn."
    "name": "Haunting Whistle"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Ghostlight%20Locomotive.webp"
```
^statblock

## Environment

any