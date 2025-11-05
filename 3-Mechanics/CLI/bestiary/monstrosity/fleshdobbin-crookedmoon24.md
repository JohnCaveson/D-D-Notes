---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Fleshdobbin
---
# [Fleshdobbin](3-Mechanics\CLI\bestiary\monstrosity/fleshdobbin-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 503*  

---

*Flesh-Crafted Amalgam of Knight and Horse*

---

Fleshdobbins are abominations created when a horse and its rider are horrifically melded through fleshcrafting magic. Their limbs stretch and deform, though afterward, their bodies resist further transformation.

Fitted with saddles and bearing savage weaponry, these monsters may look like riderless horses from a distance, but each leg culminates in oddly human-looking gnarled hands with fingers ending in wicked claws. Their voices are the comingled shrieks of human and horse.

## Secret

Affixing a bridle to a fleshdobbin causes the instincts of the horse within the amalgam to take over, becoming a loyal steed once more.

```statblock
"name": "Fleshdobbin (CrookedMoon24)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "104"
"hit_dice": "11d10 + 44"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "15"
  - !!int "19"
  - !!int "7"
  - !!int "14"
  - !!int "10"
"speed": "50 ft."
"saves":
  - "strength": !!int "8"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"damage_immunities": "psychic"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 15"
"languages": "Common"
"cr": "6"
"traits":
  - "desc": "If a creature puts a bridle on the fleshdobbin (treat as securing Manacles),\
      \ the fleshdobbin has the Charmed condition while it wears the bridle, and it\
      \ can't take the bridle off on its own."
    "name": "Bridle Binding"
  - "desc": "The fleshdobbin can't shape-shift."
    "name": "Immutable Form"
"actions":
  - "desc": "The fleshdobbin makes one Claw attack and one Wailing Halberd attack."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 10 ft. *Hit:* 8 (1d6 + 5) Piercing damage.\
      \ If the target is a Large or smaller creature, it has the Prone condition."
    "name": "Claw"
  - "desc": "*Melee Attack Roll:* +8, reach 15 ft. *Hit:* 10 (1d10 + 5) Slashing damage\
      \ plus 5 (1d10) Psychic damage."
    "name": "Wailing Halberd"
  - "desc": "*Wisdom Saving Throw:* DC 15, each creature in a 30-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 28 (8d6) Psychic damage.\
      \ In addition, the target has the Frightened condition and repeats the save\
      \ at the end of each of its turns, ending the effect on itself on a success.\
      \ After 1 minute, it succeeds automatically. *Success:* Half damage only."
    "name": "Shriek (Recharge 5-6)"
"reactions":
  - "desc": "Trigger: A creature the fleshdobbin can see hits it with a melee attack\
      \ roll while the fleshdobbin is wielding a Melee weapon. _Response:_ The fleshdobbin\
      \ adds 3 to its AC against that attack, possibly causing it to miss."
    "name": "Parry"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Fleshdobbin.webp"
```
^statblock

## Environment

grassland, hill, underground, urban