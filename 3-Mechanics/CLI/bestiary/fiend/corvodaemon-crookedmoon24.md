---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/planar-abyss
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Corvodaemon
---
# [Corvodaemon](3-Mechanics\CLI\bestiary\fiend/corvodaemon-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 493*  

---

*Demon of Hunger and Secrets*

---

Resembling a monstrous crow, the corvodaemon's sleek and twisted form soars on elongated wings tipped with razor-sharp, finger-like claws, its six amber eyes constantly seeking for prey.

Insatiable hunger for both flesh and souls—along with their accumulated secrets—gnaws at these Fiends. Their mimicry lets them take on the voice of those known and trusted by their would-be meals, luring the hapless mortals to their doom.

## Secret

Savvy demon hunters bar corvodaemons with warding lines of ash prepared from feathers.

```statblock
"name": "Corvodaemon (CrookedMoon24)"
"size": "Medium"
"type": "fiend"
"subtype": "Demon"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "15"
  - !!int "19"
  - !!int "12"
  - !!int "11"
  - !!int "19"
"speed": "20 ft., fly 60 ft."
"saves":
  - "strength": !!int "5"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "acid, fire"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 12"
"languages": "Abyssal, Common; telepathy 90 ft."
"cr": "4"
"traits":
  - "desc": "The corvodaemon can't cross a line of ashes created by burning feathers\
      \ sprinkled with Holy Water."
    "name": "Ashen Forbiddance"
  - "desc": "If the corvodaemon dies outside the Abyss, its body dissolves into ichor,\
      \ and it gains a new body instantly, reviving with all its <span title=\"Player's\
      \ Handbook (2024)\">Hit Points</span> somewhere in the Abyss."
    "name": "Demonic Restoration"
  - "desc": "A creature the corvodaemon reduced to 0 <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> is cursed until it regains any <span title=\"Player's\
      \ Handbook (2024)\">Hit Points</span>. When the cursed creature fails a <span\
      \ title=\"Player's Handbook (2024)\">Death Saving Throw</span> at the start\
      \ of its turn, it dies regardless of how many failures it has."
    "name": "Devour Anima"
  - "desc": "The corvodaemon can mimic the voice of any creature it has heard, or\
      \ of a creature known to one of the creatures within range of its telepathy.\
      \ A hearer can discern the voices are imitations with a successful DC 14 Wisdom\
      \ (Insight) check."
    "name": "Mimicry"
"actions":
  - "desc": "The corvodaemon can use Feeding Frenzy if available. It then makes one\
      \ Beak attack and one Claws attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing damage\
      \ plus 7 (2d6) Psychic damage."
    "name": "Beak"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 8 (2d4 + 3) Slashing damage.\
      \ If the target is a Medium or smaller creature, it has the Prone condition."
    "name": "Claws"
  - "desc": "The corvodaemon enters a voracious feeding frenzy, driven by its insatiable\
      \ hunger for souls. Until the start of its next turn, the corvodaemon's <span\
      \ title=\"Player's Handbook (2024)\">Speed</span> doubles, and when it damages\
      \ a creature, it gains <span title=\"Player's Handbook (2024)\">Temporary Hit\
      \ Points</span> equal to half the damage taken."
    "name": "Feeding Frenzy (Recharge 5-6)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Corvodeamon.webp"
```
^statblock

## Environment

grassland, planar (abyss)