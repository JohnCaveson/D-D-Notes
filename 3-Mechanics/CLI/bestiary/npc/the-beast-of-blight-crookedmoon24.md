---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- The Beast of Blight
---
# [The Beast of Blight](3-Mechanics\CLI\bestiary\npc/the-beast-of-blight-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 544*  

---

*Manifestation of Rot and Decay*

---

The Beast of Blight was once known as Farryn of the Greenwood, a druidic protector of the natural cycle who delved into forbidden lore to save her dead lover. Her love was virtuous, but in the end, it caused nothing but pain. Rot overtook the druid, and she is now a monstrous being that spreads and thrives on decay. The Beast of Blight moves effortlessly through decay and spews putrid spores when roused to anger.

## Secret

Buried deep within the Beast of Blight, a tiny fragment of Farryn still exists. If shown an image of her lost love, the ignited memory will burn away the rot.

## Beast of Blight's Lair

The Beast of Blight's lair is a cave in the heart of a rottenforest where blight creeps endlessly forth.

```statblock
"name": "The Beast of Blight (CrookedMoon24)"
"size": "Gargantuan"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "155"
"hit_dice": "10d20 + 50"
"modifier": !!int "12"
"stats":
  - !!int "24"
  - !!int "18"
  - !!int "21"
  - !!int "7"
  - !!int "12"
  - !!int "13"
"speed": "60 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+11"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 19"
"languages": "Common, Elvish, Sylvan"
"cr": "10"
"traits":
  - "desc": "While the beast is Bloodied, it has <span title=\"Player's Handbook (2024)\"\
      >Disadvantage</span> on attack rolls, its Spew Blight action recharges at the\
      \ start of its turn, and if it has at least 1 <span title=\"Player's Handbook\
      \ (2024)\">Hit Point</span> at the start of its turn, it regains 20 <span title=\"\
      Player's Handbook (2024)\">Hit Points</span>.\n\nIf it takes Fire damage, it\
      \ doesn't regain <span title=\"Player's Handbook (2024)\">Hit Points</span>\
      \ at the start of its next turn."
    "name": "Blighted Overgrowth"
  - "desc": "The beast ignores <span title=\"Player's Handbook (2024)\">Difficult\
      \ Terrain</span> caused by plants or fungi."
    "name": "Fungal Step"
  - "desc": "If the beast fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "If the beast can see the likeness of its long-lost love at the start\
      \ of its turn, the beast takes 10 Psychic damage and has <span title=\"Player's\
      \ Handbook (2024)\">Disadvantage</span> on <span title=\"Player's Handbook (2024)\"\
      >D20 Tests</span> until the start of its next turn."
    "name": "Unraveled Longing"
"actions":
  - "desc": "The beast makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +11, reach 10 ft. *Hit:* 18 (2d10 + 7) Slashing\
      \ damage. If the target is a Large or smaller creature, it has the Grappled\
      \ condition (escape DC 17) from one of two claws. If the beast moved at least\
      \ 20 feet immediately before the hit, the target takes an extra 7 (2d6) Poison\
      \ damage."
    "name": "Claw"
  - "desc": "*Dexterity Saving Throw:* DC 17, each creature in a 60-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* 18 (4d8) Necrotic damage,\
      \ and the target has the Poisoned condition. The target repeats the saving throw\
      \ at the end of each of its turns, ending the effect on itself on a success.\
      \ After 1 minute, it automatically succeeds. *Success:* Half damage only."
    "name": "Spew Blight (Recharge 5-6)"
  - "desc": "The beast casts the Project Image spell, requiring no spell components\
      \ and using Wisdom as the spellcasting ability. During the spell's duration,\
      \ the beast can use its Spew Blight action and Rot Stride <span title=\"Player's\
      \ Handbook (2024)\">Bonus Action</span> as if it were in the image's space.\n"
    "name": "Project Image"
"bonus_actions":
  - "desc": "The beast teleports to an unoccupied space within 60 feet. Either its\
      \ starting or destination space must contain fungus or rotting organic matter."
    "name": "Rot Stride"
"regional_effects":
  - "desc": "The region containing the Beast of Blight's lair ischanged by its presence,\
      \ creating the following effects:\n\n- **Fouling Blight.** Within 6 miles of\
      \ the lair, ability checks made to forage for food or water have <span title=\"\
      Player's Handbook (2024)\">Disadvantage</span>, and magic that creates food\
      \ or water only produces half the normal amount.  \n- **Rapid Decay.** Within\
      \ 1 mile of the lair, objects that aren't worn or carried have <span title=\"\
      Player's Handbook (2024)\">Vulnerability</span> to Necrotic damage, and the\
      \ length of time in which a dead creature can be brought back to life is halved.\
      \  \n\nIf the Beast of Blight dies or moves its lair elsewhere, these effects\
      \ end immediately."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, The can expend a use to take one of the following actions. The regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The beast exhales hallucinatory spores. *Constitution Saving Throw:*\
      \ DC 17, one creature within 60 feet. *Failure:* The target is affected by the\
      \ Confusion spell until the start of the beast's next turn. *Failure or Success:*\
      \ The beast can't use this action again until the start of its next turn."
    "name": "Hallucinate"
  - "desc": "The beast impales a creature it is grappling on one of its exposed ribs\
      \ (it can have two creatures impaled at a time). *Strength Saving Throw:* DC\
      \ 19, one creature the beast is grappling. *Failure:* 10 (3d6) Piercing damage,\
      \ and the target now has the Grappled condition (escape DC 17) from an impaling\
      \ rib, and it has the Restrained condition until the grapple ends. *Success:*\
      \ Half damage only. *Failure or Success:* The beast can't use this action again\
      \ until the start of its next turn."
    "name": "Impale"
  - "desc": "The beast moves up to half its <span title=\"Player's Handbook (2024)\"\
      >Speed</span> without provoking Opportunity Attacks. A Large or smaller creature\
      \ in a space the beast enters must succeed on a DC 19 Strength saving throw\
      \ or have the Prone condition."
    "name": "Trample"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Beast%20of%20Blight.webp"
```
^statblock

## Environment

forest, swamp