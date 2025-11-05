---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- Golub Graygullet
---
# [Golub Graygullet](3-Mechanics\CLI\bestiary\npc/golub-graygullet-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 206*  

[Golub Graygullet](/3-Mechanics/CLI/bestiary/npc/golub-graygullet-crookedmoon24.md) ([Pigeon Hag](/3-Mechanics/CLI/bestiary/fey/pigeon-hag-crookedmoon24.md)) is the leader of the Vermintoll Coven, as well as the eldest and most powerful of the three hags. Her short and stout body resembles the pigeons she adores, with taloned fingers, a beak-like nose, a puffed-up neck, and mauve skin.

Just as it was her sisters' roles to corrupt the soul and body of sacrifices to the Crooked Queen, Golub corrupts her victims' minds through the control of information and magical enchantments she weaves. A malignantly proud creature, Golub views every mortal as merely a pawn, tool, or puppet to help advance her own aims, viewing her tactics of seeking, manipulating, and distributing information as far more tasteful than the more uncouth methods favored by her sisters.

Golub is obsessed with not merely acquiring information, which she primarily gathers through the eyes and ears of her pigeon spies, but in controlling its flow. Every written communication in Wickermoor Village passes through her hands, and she alone decides what is passed on, withheld, or altered. She listens, watches, and whispers from her perch in the Walking Dovecote, choosing whether to deliver truths or lies that aid in her grand designs, even among the Vermintoll Coven and cult of the Crooked Queen.

Preferring the comforts of town and leveraging the close proximity to the victims of her mental corruption, Golub lives among the people of Wickermoor Village disguised as Theodora Mayville, the postmaster. To ensure a more reliable and long-term disguise, she wears the skin of the person she impersonates, needing to change bodies every decade or so to avoid drawing suspicion. The one thing she cannot change between personas is the vibrant lilac eyes cast by her bewitching enchantment. When Golub uses a victim's skin, the disguise is flawless and can't be perceived as false, even through magical means, which detect her as a Humanoid. Golub also has <span title="Player's Handbook (2024)">Advantage</span> on Charisma (Deception) checks while in this disguise.

```statblock
"name": "Golub Graygullet (CrookedMoon24)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "18"
"hp": !!int "228"
"hit_dice": "24d8 + 120"
"modifier": !!int "7"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "20"
  - !!int "19"
  - !!int "18"
  - !!int "22"
"speed": "30 ft., fly 60 ft. (hover)"
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+11"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
  - "name": "[Sleight of Hand](/3-Mechanics/CLI/skills.md#Sleight%20of%20Hand)"
    "desc": "+7"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 19"
"languages": "Common, Primordial (Avian), Sylvan"
"cr": "13"
"traits":
  - "desc": "While within 30 feet of at least two hag allies, Golub can cast one of\
      \ the following spells, requiring no Material components, using the spell's\
      \ normal casting time, and using Intelligence as the spellcasting ability: Augury,\
      \ Find Familiar, Identify, Locate Object, [Lucky Charm](/3-Mechanics/CLI/spells/lucky-charm-crookedmoon24.md)\
      \ (lasts until Golub casts it again, or chooses to end it with no action required),\
      \ or Unseen Servant. Golub must finish a <span title=\"Player's Handbook (2024)\"\
      >Long Rest</span> before using this trait to cast that spell again.\n"
    "name": "Coven Magic"
  - "desc": "As an Influence action, a creature that flatters Golub forces it to succeed\
      \ on a DC 17 Charisma saving throw or have the Incapacitated condition until\
      \ the end of Golub's next turn."
    "name": "Disarming Vanity"
  - "desc": "When Golub rolls <span title=\"Player's Handbook (2024)\">Initiative</span>,\
      \ it is surrounded by fey spirits in the form of angry pigeons.\n\nGolub's enemies\
      \ within a 10-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from it have <span title=\"Player's Handbook (2024)\">Disadvantage</span>\
      \ on ability checks and attack rolls. This trait doesn't function if Golub has\
      \ the Incapacitated condition."
    "name": "Harrying Wings"
"actions":
  - "desc": "Golub makes three Claw attacks. It can replace one attack with a use\
      \ of Spellcasting (at will spells only)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +10, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing damage\
      \ plus 10 (3d6) Psychic damage."
    "name": "Claw"
  - "desc": "*Wisdom Saving Throw:* DC 19, each creature in a 60-foot <span title=\"\
      Player's Handbook (2024)\">Cone</span>. *Failure:* A target takes 45 (10d8)\
      \ Psychic damage and has the Incapacitated condition until the start of Golub's\
      \ next turn. *Success:* Half damage only."
    "name": "Agonizing Cackle (1/Day)"
  - "desc": "Golub casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 19):\n\n**At\
      \ will:** Command (level 2 version), Hold Person, Minor Illusion, Stinking Cloud\n\
      \n**1/day each:** Befuddlement, Dominate Person, Scrying, Word of Recall (lair\
      \ as sanctuary)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Golub shape-shifts into a Small or Medium Humanoid, or it returns to\
      \ its true form. Other than its size, its game statistics are the same in each\
      \ form. Any equipment it is wearing or carrying isn't transformed."
    "name": "Shape-Shift"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Golub%20Graygullet.webp"
```
^statblock