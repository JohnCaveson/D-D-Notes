---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/cleric
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wendel Somerton
---
# [Wendel Somerton](3-Mechanics\CLI\bestiary\npc/wendel-somerton-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 198*  

Mayor Somerton is an officious, self-important man of 50 years. His short, wide frame is constantly clad in finely tailored suits that barely hold his ever-growing girth. He wears a matching bowler hat on his bald head, and his bushy gray eyebrows and handlebar mustache are waxed to maintain their shapes. His cravats are decorated with a jeweled pin in the form of an oak leaf. He does not need, but always carries, a mahogany cane with an emerald handle.

While he is tolerant and even welcoming to people of all ideologies, Mayor Somerton strongly believes in the Old Ways along with his family. However, he is completely ignorant of the wicked intentions of the cult of the Crooked Queen and only knows Kehlenn as the Green Queen, whom he deeply reveres. He serves as the leader of the Followers of the Old Ways, leading worship of the Green Queen and heading the rituals and rites to harness her power.

This has made him a useful pawn of the nefarious cult of the Crooked Queen, unknowingly enacting the plans of her servants. The most impactful of these decisions was the gifting of the Lockwood Estate to [Phillip Druskenvald](/3-Mechanics/CLI/bestiary/npc/phillip-druskenvald-crookedmoon24.md) and preparing for his potential arrival. While most townsfolk, and even Wendel himself, viewed the move as a political maneuver, the idea was planted in his head by [Randall Graham](/3-Mechanics/CLI/bestiary/npc/randall-graham-crookedmoon24.md) (see area V7), who knows that [Phillip](/3-Mechanics/CLI/bestiary/npc/phillip-druskenvald-crookedmoon24.md) is the critical piece of the final ritual to free the Crooked Queen and unleash the Horned King.

```statblock
"name": "Wendel Somerton (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric"
"alignment": "Lawful Neutral"
"ac": !!int "13"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "16"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Common plus one other language"
"cr": "2"
"actions":
  - "desc": "Wendel makes two attacks, using Mace or Radiant Flame in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Bludgeoning damage\
      \ plus 5 (2d4) Radiant damage."
    "name": "Mace"
  - "desc": "*Ranged Attack Roll:* +5, range 60 ft. *Hit:* 11 (2d10) Radiant damage."
    "name": "Radiant Flame"
  - "desc": "Wendel casts one of the following spells, using Wisdom as the spellcasting\
      \ ability:\n\n**At will:** Light, Thaumaturgy\n\n**1/day:** Spirit Guardians"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Wendel casts Bless, Dispel Magic, Healing Word, or Lesser Restoration,\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Divine Aid (3/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Wendel%20Somerton.webp"
```
^statblock