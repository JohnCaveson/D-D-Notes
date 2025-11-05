---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Serum Brute
---
# [Serum Brute](3-Mechanics\CLI\bestiary\giant/serum-brute-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 529*  

---

*Cursed Giant Enhanced by Alchemy*

---

Serum brutes are descended from giants who suffered an enduring curse when they failed to take over a Fey domain. They have third eyes, usually in their foreheads, which channel the giants' curse into the world around them. All three of their eyes are sewn or otherwise sealed shut to contain the curse. Serum brutes are further enhanced with—and get their name from—a series of alchemical infusions, often delivered through implanted vessels and tubes, which seek to deaden their sorrow and pain, as well as the disturbing power of their third eyes. They form deep emotional bonds with any who offer them comfort and an escape from the pain of their curse, and they are often willing to die for those allies.

## Secret

Serum brutes are dependent upon their curse, and magic that breaks curses can leave the giants debilitated and bereft.

```statblock
"name": "Serum Brute (CrookedMoon24)"
"size": "Large"
"type": "giant"
"alignment": "Neutral"
"ac": !!int "16"
"hp": !!int "115"
"hit_dice": "11d10 + 55"
"modifier": !!int "4"
"stats":
  - !!int "21"
  - !!int "19"
  - !!int "20"
  - !!int "9"
  - !!int "14"
  - !!int "9"
"speed": "40 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (blind beyond\
  \ this radius unless Unleashed Eyes is active), passive Perception 15"
"languages": "Common, giant, Sylvan"
"cr": "6"
"traits":
  - "desc": "If the brute is targeted by a Remove Curse spell or similar magic, until\
      \ it finishes a <span title=\"Player's Handbook (2024)\">Long Rest</span>, the\
      \ brute loses its Blindsight, its Withering Eye trait, and its Cursed Gaze action."
    "name": "Curse Dependent"
  - "desc": "At the start of its turn, the brute must choose one of the following\
      \ options (it can't use that option twice in a row):"
    "name": "Stimulant Rush"
  - "desc": "Until the start of its next turn, the brute's <span title=\"Player's\
      \ Handbook (2024)\">Speed</span> increases to 50 feet, it doesn't provoke an\
      \ Opportunity Attack when it leaves an enemy's reach, and its <span title=\"\
      Player's Handbook (2024)\">Long Jump</span> is up to 30 feet and its <span title=\"\
      Player's Handbook (2024)\">High Jump</span> is up to 15 feet with or without\
      \ a running start."
    "name": "Catalyst Infusion"
  - "desc": "Until the start of its next turn, its Fist attack deals an extra 11 (2d10)\
      \ Acid damage (included in the Fist attack below)."
    "name": "Caustic Secretion"
  - "desc": "Gain 10 <span title=\"Player's Handbook (2024)\">Temporary Hit Points</span>."
    "name": "Stim Boost"
  - "desc": "When the brute is Bloodied, its sealed eyes rip open and unleash its\
      \ curse. It is no longer blind beyond 60 feet, and it can use its Withering\
      \ Eye trait and Cursed Gaze action until it finishes a <span title=\"Player's\
      \ Handbook (2024)\">Long Rest</span>, whereupon its eyes seal shut again."
    "name": "Unleashed Eyes (1/Day)"
  - "desc": "When the brute moves to within 5 feet of a creature, the creature takes\
      \ 4 (1d8) Psychic damage. A creature takes this damage only once per turn."
    "name": "Withering Eye (Unleashed Eyes Only)"
"actions":
  - "desc": "The brute makes two Fist attacks and can use Cursed Gaze if available."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 10 ft. *Hit:* 9 (1d8 + 5) Bludgeoning\
      \ damage. If Caustic Secretion is active, the target takes an extra 11 (2d10)\
      \ Acid damage."
    "name": "Fist"
  - "desc": "*Wisdom Saving Throw:* DC 16, each creature in a 30-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 9 (2d8) Psychic damage, and\
      \ the target has the Frightened condition until the start of the brute's next\
      \ turn. *Success:* Half damage only."
    "name": "Cursed Gaze (Unleashed Eyes Only)"
"reactions":
  - "desc": "Trigger: An ally within 5 feet takes damage. _Response:_ The ally gains\
      \ <span title=\"Player's Handbook (2024)\">Resistance</span> to the triggering\
      \ damage, and the brute takes an amount of Psychic damage equal to the damage\
      \ the ally takes."
    "name": "Devotion"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Serum%20Brute.webp"
```
^statblock

## Environment

underground, urban