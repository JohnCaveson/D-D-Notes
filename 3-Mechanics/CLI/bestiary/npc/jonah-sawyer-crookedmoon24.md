---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Jonah Sawyer
---
# [Jonah Sawyer](3-Mechanics\CLI\bestiary\npc/jonah-sawyer-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 243*  

Jonah has a reputation as a rugged, broad-shouldered man with a humor as hefty as his sinewed frame. As Foxwillow's butcher, he's often seen in a bloodstained apron striding through town. His signature platform shoes, worn to keep his feet dry from pigs' blood, earned him the nickname "Heels." His only daughter, Liza, has gone missing in recent nights.

Though he's truly not responsible for all Foxwillow's ills, Jonah has been on edge lately, burdened by guilt over the town's curse and the disappearance of his daughter. In a fit of rage, he cursed William Lodge, and his shame has made him antagonistic toward his neighbors (see "Foxwillow in Flames" later in this chapter).

## Changing Jonah's Attitude

Suspicious by nature, Jonah is difficult to befriend. If characters talk with him about breaking the curse, he asks if they think whoever caused the curse was evil, or just misguided. His attitude increases one step to <span title="Player's Handbook (2024)">Friendly</span> if they say they'll be sympathetic to the curse-maker or that they'll keep an eye out for Liza.

If they suggest that they'll kill the person who cursed Foxwillow, he becomes fearful and <span title="Player's Handbook (2024)">Hostile</span>, refusing to speak at length.

## Jonah's Secret

Jonah has harbored resentment for [William Lodge](/3-Mechanics/CLI/bestiary/npc/william-lodge-crookedmoon24.md) for years, though he no longer recalls why. By all accounts, William is well-liked and even sells livestock to the butcher. But Jonah recently discovered William had been selling him scrawnier stock than he sells to Siv Harga in Wickermoor Village, who pays a higher price for well-cared-for prize beasts.

In a fit of ire, Jonah slaughtered a lamb and invoked an old folk hex his grandmother once whispered about. He cursed William's fields and herds and—to his horror—the curse took root. Now, Foxwillow's crops and livestock wither—save for the demon-infested cornfield, which thrives unnaturally. Jonah, wracked with guilt, grows defensive, fearing the town's ruin rests on his shoulders.

## Learning His Secret

As an Influence action, characters convince Jonah to reveal this secret with a successful DC 15 Charisma (Intimidation or Persuasion) check.

```statblock
"name": "Jonah Sawyer (CrookedMoon24)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Good"
"ac": !!int "12"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "11"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "Jonah has <span title=\"Player's Handbook (2024)\">Advantage</span> on\
      \ an attack roll against a creature if at least one of Jonah's allies is within\
      \ 5 feet of the creature and the ally doesn't have the Incapacitated condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Bludgeoning damage."
    "name": "Mace"
  - "desc": "*Ranged Attack Roll:* +3, range 100/400 ft. *Hit:* 6 (1d10 + 1) Piercing\
      \ damage."
    "name": "Heavy Crossbow"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/NPCs/Tokens/Jonah%20Sawyer.webp"
```
^statblock