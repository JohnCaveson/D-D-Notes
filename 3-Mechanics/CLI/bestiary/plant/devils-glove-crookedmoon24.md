---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/environment/underground
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Devil's Glove
---
# [Devil's Glove](3-Mechanics\CLI\bestiary\plant/devils-glove-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 583*  

---

*Five-Fingered Fungus (Rare wood chips)*

---

Comprised of five twitching, blood-red tendrils lined with black slime, the devil's glove fungus feeds voraciously off decaying matter, unwary insects, and small creatures. Resembling a long-fingered hand, they grow from bulbous roots that look like leathery, white eggs and constantly emit an overpowering scent of death and rot. Despite their unpleasant aura, these fungus creatures can form beneficial relationships with others, providing nourishment and resilience in exchange for protection and a ready supply of decaying material to feed upon.

```statblock
"name": "Devil's Glove (CrookedMoon24)"
"size": "Tiny"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "6d4 + 12"
"modifier": !!int "0"
"stats":
  - !!int "14"
  - !!int "10"
  - !!int "15"
  - !!int "3"
  - !!int "8"
  - !!int "4"
"speed": "30 ft., climb 30 ft."
"condition_immunities": "[deafened](/3-Mechanics/CLI/conditions.md#Deafened), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 9"
"languages": "understands Common but can't speak"
"cr": "1"
"traits":
  - "desc": "Creatures that can smell have <span title=\"Player's Handbook (2024)\"\
      >Advantage</span> on Wisdom (Perception) checks made to find the devil's glove."
    "name": "Scent of Death"
  - "desc": "The devil's glove can climb difficult surfaces, including along ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Bludgeoning damage\
      \ plus 7 (2d6) Necrotic damage, and the devil's glove attaches to the target.\
      \ While attached, the devil's glove can't make Tendril attacks against other\
      \ targets, and if the target is a creature, the target has the Poisoned condition\
      \ until the start of its next turn if it can smell the devil's glove.\n\nThe\
      \ devil's glove can detach itself by spending 5 feet of its movement. The target\
      \ or a creature within 5 feet of it can detach the devil's glove as an action."
    "name": "Tendril"
  - "desc": "*Constitution Saving Throw:* DC 12, each creature in a 10-foot <span\
      \ title=\"Player's Handbook (2024)\">Emanation</span> originating from the devil's\
      \ glove. *Failure:* 9 (2d8) Necrotic damage, and the target can't regain <span\
      \ title=\"Player's Handbook (2024)\">Hit Points</span> until the start of the\
      \ devil's glove's next turn. *Success:* Half damage only."
    "name": "Decaying Bloom (2/Day)"
"bonus_actions":
  - "desc": "The devil's glove forms a magical bond with a willing creature it touches.\
      \ The bonded creature doesn't need to eat or drink, and the creature has <span\
      \ title=\"Player's Handbook (2024)\">Advantage</span> on saving throws to avoid\
      \ or end the Poisoned condition. The bond ends when the creature dies, the devil's\
      \ glove dies, the devil's glove ends the bond (no action required), or when\
      \ the devil's glove uses this <span title=\"Player's Handbook (2024)\">Bonus\
      \ Action</span> again."
    "name": "Symbiosis"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Devil%27s%20Glove.webp"
```
^statblock

## Environment

forest, swamp, underground