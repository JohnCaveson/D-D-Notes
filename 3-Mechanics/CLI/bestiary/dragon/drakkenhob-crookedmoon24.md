---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/environment/grasslands
- ttrpg-cli/monster/environment/hills
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Drakkenhob
---
# [Drakkenhob](3-Mechanics\CLI\bestiary\dragon/drakkenhob-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 499*  

---

*Dragon Disguised as a Festival Horse*

---

The drakkenhob is a draconic monster with a sinister disguise, presenting itself as an actor wearing a horse costume, such as a mounted knight or a festively clad rider. Its draconic head resembles a decorated or armored horse's head, and its sharp teeth fit together to appear like blunt, harmless decorations. The drakkenhob uses this benign guise to get close to its prey, which are typically within crowds near festivals or parades, before it summons its similarly garbed hunting hounds and strikes. Its breath is a blood-curdling wave of terror that makes lesser victims drop dead from fright alone.

## Secret

Unable to resist revelry and merriment, drakkenhob are driven away by payment offered in gold or alcohol.

```statblock
"name": "Drakkenhob (CrookedMoon24)"
"size": "Large"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "2"
"stats":
  - !!int "21"
  - !!int "14"
  - !!int "16"
  - !!int "11"
  - !!int "16"
  - !!int "11"
"speed": "50 ft."
"saves":
  - "dexterity": !!int "6"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6 resistances fire"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 17"
"languages": "Common, Draconic"
"cr": "9"
"traits":
  - "desc": "As an Influence action, a creature that offers the drakkenhob alcohol\
      \ or any amount of gold and succeeds on a DC 16 Charisma (Persuasion) check\
      \ forces the drakkenhob to accept the offer and immediately take a <span title=\"\
      Player's Handbook (2024)\">Reaction</span> to move up to half its <span title=\"\
      Player's Handbook (2024)\">Speed</span> to get away from the creature by the\
      \ safest route possible."
    "name": "Irresistible Payment"
"actions":
  - "desc": "The drakkenhob makes two Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +9, reach 5 ft. *Hit:* 12 (2d6 + 5) Piercing damage\
      \ plus 11 (2d10) Psychic damage."
    "name": "Rend"
  - "desc": "*Wisdom Saving Throw:* DC 15, each creature in a 30-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 14 (4d6) Psychic damage,\
      \ and the target drops whatever it is holding and has the Frightened condition.\
      \ A Frightened target takes the Dash action and moves away from the drakkenhob\
      \ by the safest route on each of its turns unless there's nowhere to move. It\
      \ repeats the save at the end of each of its turns, ending the effect on itself\
      \ on a success. After 1 minute, it succeeds automatically. *Success:* Half damage\
      \ only."
    "name": "Terrifying Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "The drakkenhob lets out a wolf-like howl and magically summons three\
      \ hunting hounds (use the Wolf stat block) that appear in unoccupied spaces\
      \ within 60 feet of it. The hounds take their turn immediately after the drakkenhob\
      \ on the same <span title=\"Player's Handbook (2024)\">Initiative</span> count,\
      \ and they obey the drakkenhob's mental commands. The hounds vanish when they\
      \ or the drakkenhob drop to 0 <span title=\"Player's Handbook (2024)\">Hit Points</span>,\
      \ or when the drakkenhob uses this <span title=\"Player's Handbook (2024)\"\
      >Bonus Action</span> again."
    "name": "Call the Hounds"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Drakkenhob.webp"
```
^statblock

## Environment

grasslands, hills, urban