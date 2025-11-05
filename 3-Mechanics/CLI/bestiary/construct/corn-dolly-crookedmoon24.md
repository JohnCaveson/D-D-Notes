---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/any
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- Corn Dolly
---
# [Corn Dolly](3-Mechanics\CLI\bestiary\construct/corn-dolly-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 581*  

---

*Grain Husk Companion (Curved blade plated in gold)*

---

Crafted from dried husks and bound with twine, corn dollies' delicate forms are stitched together with rustic care. Their faces are ink-brushed with simple, childlike expressions—smiling mouths that curve a bit too wide and hollow eyes that seem to stare far beyond the physical world. The Constructs are spirits of deceased Humanoids drawn to the hollow corn husk shell, seeking refuge. These spirits retain faint traces of who they once were—a protective instinct entwined with a simmering fury. Once animated, the dolls reflect this dual nature: acting as silent guardians one moment and vengeful specters the next.

```statblock
"name": "Corn Dolly (CrookedMoon24)"
"size": "Tiny"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "10"
"hp": !!int "38"
"hit_dice": "11d4 + 11"
"modifier": !!int "0"
"stats":
  - !!int "3"
  - !!int "10"
  - !!int "12"
  - !!int "12"
  - !!int "8"
  - !!int "16"
"speed": "20 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "passive Perception 11"
"languages": "understands Common but can't speak"
"cr": "1"
"traits":
  - "desc": "The corn dolly can move through a space as narrow as 1 inch without expending\
      \ extra movement to do so."
    "name": "Husk Body"
  - "desc": "The strange, childlike inked face unnerves onlookers. While a creature\
      \ is holding the corn dolly, creatures within 10 feet of it have <span title=\"\
      Player's Handbook (2024)\">Disadvantage</span> on Wisdom (Insight) checks made\
      \ against the creature."
    "name": "Uneasy Visage"
"actions":
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 1 Slashing damage plus 4\
      \ (1d8) Psychic damage."
    "name": "Husk Cut"
  - "desc": "*Wisdom Saving Throw:* DC 13, one creature the corn dolly can see within\
      \ 30 feet. *Failure:* 10 (3d6) Psychic damage. *Success:* Half damage."
    "name": "Blank Stare"
  - "desc": "*Wisdom Saving Throw:* DC 13, each creature of the corn dolly's choice\
      \ in a 15-foot <span title=\"Player's Handbook (2024)\">Cone</span>. *Failure:*\
      \ The target has the Frightened condition until the end of its next turn."
    "name": "Sowing Dread (2/Day)"
"reactions":
  - "desc": "Trigger: A creature within 60 feet fails a saving throw against an effect\
      \ that doesn't deal damage. _Response:_ The corn dolly suffers the effects of\
      \ the failure instead of the creature."
    "name": "Silent Protector (Recharge after a Short or Long Rest)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Corn%20Dolly.webp"
```
^statblock

## Environment

any