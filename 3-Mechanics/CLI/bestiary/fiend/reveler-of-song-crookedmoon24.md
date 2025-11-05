---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/planar-lower-planes
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- Reveler of Song
---
# [Reveler of Song](3-Mechanics\CLI\bestiary\fiend/reveler-of-song-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 525*  

---

*Fiend of Music and Dance*

---

Revelers of song are Fiends of music and abandon who turn their art against their foes in destructive reverberation. The revelers dance and play at nearly all times and are known to fly into a murderous rage if their invitations to join the celebration are spurned. A variety of revelers of song exist, depending on the type of instrument a given reveler plays. Drone revelers play the hurdy gurdy and are surrounded by an accompanying swarm of bees. Drum revelers play drums or cymbals, and the world shakes to their beat. Bell revelers play some variety of bell, chime, or gong, and the ringing overtakes all other sounds.

## Secret

Revelers of song can't accept that any creature is more skilled at an instrument than they are and so can't refuse a musical challenge.

```statblock
"name": "Reveler of Song (CrookedMoon24)"
"size": "Medium"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"modifier": !!int "3"
"stats":
  - !!int "15"
  - !!int "16"
  - !!int "14"
  - !!int "11"
  - !!int "12"
  - !!int "20"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+11"
"damage_resistances": "cold, fire"
"damage_immunities": "poison, thunder"
"condition_immunities": "[deafened](/3-Mechanics/CLI/conditions.md#Deafened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 10 ft. (Drone only),\
  \ [darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 14"
"languages": "Common; telepathy 120 ft."
"cr": "6"
"traits":
  - "desc": "The reveler can't refuse a contest of skill with Musical Instruments.\
      \ As an Influence action, a creature can make a Charisma (Performance) check\
      \ using a Musical Instrument. The reveler must succeed on a Charisma saving\
      \ throw with a DC equal to the check's total or take 20 Psychic damage and have\
      \ the Stunned condition until the end of the creature's next turn."
    "name": "Compelled Contest"
  - "desc": "The reveler doesn't provoke Opportunity Attacks when it leaves an enemy's\
      \ reach."
    "name": "Dancing Step"
  - "desc": "The reveler takes on a specific form: Drone, Drum, or Bell. The form\
      \ determines certain traits and actions, as well as the instrument the reveler\
      \ plays (hurdy gurdy, frame drum, or handbells, respectively)."
    "name": "Ensemble Form"
  - "desc": "A droning swarm of bees surrounds the reveler. *Constitution Saving Throw:*\
      \ DC 16, each creature that ends its turn in a 10-foot <span title=\"Player's\
      \ Handbook (2024)\">Emanation</span> originating from the reveler. *Failure:*\
      \ The target has the Poisoned condition until the end of its next turn."
    "name": "Droning Swarm (Drone Only)"
"actions":
  - "desc": "The reveler makes two Instrumental Blast attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +8, reach 5 ft. or range 90 ft. *Hit:*\
      \ 14 (2d8 + 5) Thunder damage."
    "name": "Instrumental Blast"
  - "desc": "*Wisdom Saving Throw:* DC 16, up to two creatures the reveler can see\
      \ within 30 feet. *Failure:* 18 (4d8) Psychic damage, and the target is affected\
      \ by the Irresistible Dance spell (no Concentration required to maintain the\
      \ spell). *Success:* Half damage only."
    "name": "Infectious Rhythm (Drum Only)"
  - "desc": "*Constitution Saving Throw:* DC 16, one creature the reveler can see\
      \ within 60 feet. *Failure:* 40 (9d8) Thunder damage, and the target has the\
      \ Stunned condition until the end of the reveler's next turn. *Success:* Half\
      \ damage only."
    "name": "Stunning Clangor (Bell Only)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Reveler%20of%20Song%20Droning.webp"
```
^statblock

## Environment

planar (lower planes), urban