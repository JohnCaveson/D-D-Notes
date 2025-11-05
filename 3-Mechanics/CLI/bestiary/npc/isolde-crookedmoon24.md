---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Isolde
---
# [Isolde](3-Mechanics\CLI\bestiary\npc/isolde-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 369*  

After isolating himself, Yorgrim found companionship in Isolde (ih-ZOAL-duh), a type of guardian spirit known as a grim. These spectral watchers guard cemeteries, graveyards, and other burial sites and can take the form of any animal. Isolde (Neutral Good Ghost) manifests as a black hound with bright white eyes. She is deeply loyal to Yorgrim, and carries in her mouth a Hooded Lantern lit with a spark of the gravedigger's soul.

While Isolde is similarly bound to Maidenmist Cemetery like her master, she is able to exit its cold iron gates and walk beyond its borders. In recent years, she has served as the primary messenger between Yorgrim and Mori Shade, the undertaker of Wickermoor Village. With a supernatural intuition that only a dog can possess, she can sense that Yorgrim is suffering from the gibbering of the Shroud and is close to breaking.

```statblock
"name": "Isolde (CrookedMoon24)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral"
"ac": !!int "11"
"hp": !!int "45"
"hit_dice": "10d8"
"modifier": !!int "1"
"stats":
  - !!int "7"
  - !!int "13"
  - !!int "10"
  - !!int "10"
  - !!int "12"
  - !!int "17"
"speed": "5 ft., fly 40 ft. (hover)"
"damage_resistances": "acid, bludgeoning, cold, fire, lightning, piercing, slashing,\
  \ thunder"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[Darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 11"
"languages": "Common plus one other language"
"cr": "4"
"traits":
  - "desc": "Isolde can see 60 feet into the Ethereal Plane when it is on the Material\
      \ Plane."
    "name": "Ethereal Sight"
  - "desc": "Isolde can move through other creatures and objects as if they were <span\
      \ title=\"Player's Handbook (2024)\">Difficult Terrain</span>. It takes 5 (1d10)\
      \ Force damage if it ends its turn inside an object."
    "name": "Incorporeal Movement"
"actions":
  - "desc": "Isolde makes two Withering Touch attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 19 (3d10 + 3) Necrotic damage."
    "name": "Withering Touch"
  - "desc": "*Wisdom Saving Throw:* DC 13, each creature in a 60-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span> that can see Isolde and isn't an Undead.\
      \ *Failure:* 10 (2d6 + 3) Psychic damage, and the target has the Frightened\
      \ condition until the start of Isolde's next turn. *Success:* The target is\
      \ immune to this ghost's Horrific Visage for 24 hours."
    "name": "Horrific Visage"
  - "desc": "*Charisma Saving Throw:* DC 13, one Humanoid Isolde can see within 5\
      \ feet. *Failure:* The target is possessed by Isolde; Isolde disappears, and\
      \ the target has the Incapacitated condition and loses control of its body.\
      \ Isolde now controls the body, but the target retains awareness. Isolde can't\
      \ be targeted by any attack, spell, or other effect, except ones that specifically\
      \ target Undead. Isolde's game statistics are the same, except it uses the possessed\
      \ target's <span title=\"Player's Handbook (2024)\">Speed</span>, as well as\
      \ the target's Strength, Dexterity, and Constitution modifiers.\n\nThe possession\
      \ lasts until the body drops to 0 <span title=\"Player's Handbook (2024)\">Hit\
      \ Points</span> or Isolde leaves as a <span title=\"Player's Handbook (2024)\"\
      >Bonus Action</span>. When the possession ends, Isolde appears in an unoccupied\
      \ space within 5 feet of the target, and the target is immune to this ghost's\
      \ <span title=\"Player's Handbook (2024)\">Possession</span> for 24 hours. *Success:*\
      \ The target is immune to this ghost's <span title=\"Player's Handbook (2024)\"\
      >Possession</span> for 24 hours."
    "name": "Possession (Recharge 6)"
  - "desc": "Isolde casts the Etherealness spell, requiring no spell components and\
      \ using Charisma as the spellcasting ability. Isolde is visible on the Material\
      \ Plane while on the Border Ethereal and vice versa, but it can't affect or\
      \ be affected by anything on the other plane.\n"
    "name": "Etherealness"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Isolde.webp"
```
^statblock