---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Doctor Belkin
---
# [Doctor Belkin](3-Mechanics\CLI\bestiary\npc/doctor-belkin-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 321*  

Doctor Belkin is the architect of Memory's Rest's most horrifying experiments. When Belkin was first exposed to the Lethic Serum, its effects on him were unique. His mind opened to [The White Worm's](/3-Mechanics/CLI/bestiary/npc/the-white-worm-crookedmoon24.md) influence, and he was found the following night in the caverns below the hospital having removed the top of his own skull—a colony of pale, writhing larvae now burrow within, driving his every thought. The White Worm had revealed the "truth": salvation lies not in erasing trauma but in perfect symbiosis with the worm's parasitic gifts.

```statblock
"name": "Doctor Belkin (CrookedMoon24)"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"modifier": !!int "1"
"stats":
  - !!int "8"
  - !!int "13"
  - !!int "16"
  - !!int "13"
  - !!int "18"
  - !!int "10"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., passive Perception\
  \ 17"
"languages": "Common, Deep Speech"
"cr": "5"
"traits":
  - "desc": "Belkin regains 10 <span title=\"Player's Handbook (2024)\">Hit Points</span>\
      \ at the start of each of its turns. If it takes Poison damage, this trait doesn't\
      \ function at the start of its next turn. Belkin dies only if it starts its\
      \ turn with 0 <span title=\"Player's Handbook (2024)\">Hit Points</span> and\
      \ doesn't regenerate."
    "name": "Regeneration"
  - "desc": "A creature whose mind can't be read, or that is under the effect of a\
      \ Mind Blank or Nondetection spell, has the Invisible condition toward Belkin\
      \ (this ignores Belkin's Blindsight)."
    "name": "Veiled Ignorance"
"actions":
  - "desc": "Belkin makes two Bone Saw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Slashing damage\
      \ plus 4 (1d8) Psychic damage.\n\nCritical *Hit:* If the target is a creature,\
      \ its Intelligence score decreases by 1d4. The target dies if this reduces that\
      \ score to 0."
    "name": "Bone Saw"
  - "desc": "Belkin unleashes a spray of worm-ridden cerebral fluid. *Dexterity Saving\
      \ Throw:* DC 14, each creature in a 20-foot <span title=\"Player's Handbook\
      \ (2024)\">Cone</span>. *Failure:* 17 (5d6) Psychic damage, and the target is\
      \ infested with larval parasitic worms. The target takes 7 (2d6) Psychic damage\
      \ at the end of each of its turns as the worms burrow toward its brain. The\
      \ ongoing damage ends when the target takes Poison damage or is targeted by\
      \ an effect that ends the Poisoned condition. *Success:* Half damage only. *Failure\
      \ or Success:* If the target is reduced to 0 <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span> by this Psychic damage, the worms reach its brain\
      \ and it dies. A Humanoid slain in this way rises 24 hours later as a wormhost\
      \ surgeon."
    "name": "Infested Spray (Recharge 5-6)"
"reactions":
  - "desc": "Trigger: Belkin is reduced to 0 <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span>. _Response:_ The parasite worm emerges from Belkin's exposed\
      \ brain and spits acid—*Dexterity Saving Throw:* DC 14, each creature in a 20-foot-long,\
      \ 5-foot-wide <span title=\"Player's Handbook (2024)\">Line</span>. *Failure:*\
      \ 10 (3d6) Acid damage. *Success:* Half damage."
    "name": "Protective Parasite"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Doctor%20Belkin.webp"
```
^statblock