---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/planar-lower-planes
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Reveler of Stories
---
# [Reveler of Stories](3-Mechanics\CLI\bestiary\fiend/reveler-of-stories-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 527*  

---

*Fiend of Legend and Folklore*

---

Timeless stories have inspired countless mortals, and the echoes of those stories in the Lower Planes have spawned fiendish embodiments of those tales—the revelers of stories. These Fiends twist the themes of their tales, turning inspiration into doom. The revelers' forms and powers change depending on the theme of stories they embody. Great beast revelers of stories rise from tales of terrible monsters. Hero revelers of stories embody the exploits of knights and other mighty heroes. Witch revelers of stories bring to life tales of wicked witches, wizards, and other magicians.

## Secret

Revelers of stories exist because of fables, legends, and other tales, and reciting the moral of a story related to the reveler's theme robs the reveler of its potency.

```statblock
"name": "Reveler of Stories (CrookedMoon24)"
"size": "Large"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac_class": "15; 17 (Hero only)"
"hp": !!int "127"
"hit_dice": "15d10 + 45"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "16"
  - !!int "14"
  - !!int "15"
  - !!int "20"
"speed": "40 ft., 60 ft. (Hero only)"
"saves":
  - "wisdom": !!int "6"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+13"
"damage_resistances": "cold, fire"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., [truesight](/3-Mechanics/CLI/senses.md#Truesight)\
  \ 120 ft. (Witch only), passive Perception 16"
"languages": "Common; telepathy 120 ft."
"cr": "9"
"traits":
  - "desc": "As a <span title=\"Player's Handbook (2024)\">Bonus Action</span>, a\
      \ creature can recite the moral of a story using the same theme as the reveler's\
      \ Storied Form to weaken it for 1 hour. While weakened, the reveler can't take\
      \ <span title=\"Player's Handbook (2024)\">Reactions</span>, and its AC is reduced\
      \ by 4."
    "name": "Moral Quandary"
  - "desc": "The reveler takes on a specific form: Great Beast, Hero, or Witch. The\
      \ form determines certain traits and the theme of stories the reveler embodies\
      \ (powerful monsters, brave heroes, or wicked magicians, respectively)."
    "name": "Storied Form"
  - "desc": "If there is at least one creature with the Frightened condition within\
      \ 30 feet of the reveler at the end of its turn, the reveler gains 15 <span\
      \ title=\"Player's Handbook (2024)\">Temporary Hit Points</span>."
    "name": "Terror Feeding (Witch Only)"
"actions":
  - "desc": "The reveler makes three Thrash attacks. It can replace one attack with\
      \ a use of Fabled Assault if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 10 ft. *Hit:* 18 (3d8 + 5) Force damage."
    "name": "Thrash"
  - "desc": "The reveler uses the option determined by its Storied Form:"
    "name": "Fabled Assault (Recharge 5-6)"
  - "desc": "*Constitution Saving Throw:* DC 17, one creature within 5 feet (with\
      \ <span title=\"Player's Handbook (2024)\">Disadvantage</span> if the reveler\
      \ is grappling the target). *Failure:* 36 (8d8) Necrotic damage. If the target\
      \ is Huge or smaller, it has the Grappled condition (escape DC 15), and it has\
      \ the Restrained condition until the grapple ends. *Success:* Half damage only.\
      \ *Failure or Success:* The reveler gains <span title=\"Player's Handbook (2024)\"\
      >Temporary Hit Points</span> equal to the Necrotic damage taken."
    "name": "Consuming Bite (Great Beast Only)"
  - "desc": "The reveler moves up to its <span title=\"Player's Handbook (2024)\"\
      >Speed</span> in a straight line without provoking Opportunity Attacks, and\
      \ it can move through other creatures without expending extra movement to do\
      \ so. *Strength Saving Throw:* DC 17, each creature whose space the reveler\
      \ enters. *Failure:* 26 (4d12) Force damage, and the target has the Prone condition.\
      \ *Success:* Half damage only."
    "name": "Heroic Charge (Hero Only)"
  - "desc": "*Dexterity Saving Throw:* DC 17, each creature in a 60-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 27 (6d8) Lightning damage,\
      \ and the target has the Frightened condition. While Frightened in this way,\
      \ the target's <span title=\"Player's Handbook (2024)\">Speed</span> is 0. A\
      \ Frightened target repeats the saving throw at the end of each of its turns,\
      \ ending the effect on itself on a success. After 1 minute, it succeeds automatically.\
      \ *Success:* Half damage only."
    "name": "Wicked Storm (Witch Only)"
"reactions":
  - "desc": "Trigger: The reveler is hit by an attack roll. _Response:_ The reveler\
      \ adds 4 to its AC against that attack, possibly causing it to miss."
    "name": "Dramatic Reversal"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Reveler%20of%20Stories%20Great%20Beast.webp"
```
^statblock

## Environment

planar (lower planes), urban