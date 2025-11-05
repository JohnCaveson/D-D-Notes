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
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ghost Crawler
---
# [Ghost Crawler](3-Mechanics\CLI\bestiary\undead/ghost-crawler-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 585*  

---

*Spirit Spider (Silk threads soaked in wine)*

---

Silent and nearly [invisible](/3-Mechanics/CLI/conditions.md#Invisible), ghost crawlers skitter between the darkest corners, hiding and watching. Their diminutive, ghostly, spider-like bodies are ill-defined and as translucent as a wisp of smoke, while their legs are long, uneven, and jarringly solid. The webs they spin are ephemeral and ghastly, allowing the crawlers to sense through them regardless of the distance.

```statblock
"name": "Ghost Crawler (CrookedMoon24)"
"size": "Tiny"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "25"
"hit_dice": "10d4"
"modifier": !!int "3"
"stats":
  - !!int "2"
  - !!int "16"
  - !!int "10"
  - !!int "1"
  - !!int "10"
  - !!int "2"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 30 ft., Seer's Strand\
  \ (see below), passive Perception 10"
"languages": "understands Common but can't speak"
"cr": "1"
"traits":
  - "desc": "The crawler can move through a space as narrow as 1 inch without expending\
      \ extra movement to do so."
    "name": "Ephemeral Body"
  - "desc": "The crawler can see and hear through the space of its Ether Webs as if\
      \ it were in that space."
    "name": "Seer's Strand"
  - "desc": "The crawler can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The crawler ignores movement restrictions caused by webs, and the crawler\
      \ knows the location of any other creature in contact with the same web."
    "name": "Web Walker"
"actions":
  - "desc": "The crawler makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing damage,\
      \ and if the target is a creature, it has the Poisoned condition until the start\
      \ of the crawler's next turn."
    "name": "Bite"
  - "desc": "The crawler fills a 5-foot <span title=\"Player's Handbook (2024)\">Cube</span>\
      \ with Invisible, ephemeral webs for 8 hours. If the web isn't anchored between\
      \ two solid masses (such as walls or trees) or layered across a floor, wall,\
      \ or ceiling, the web collapses on itself and vanishes. When a creature touches\
      \ the webbing, the crawler knows the location of the creature as long as they\
      \ are on the same plane of existence."
    "name": "Ether Webs (2/Day)"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Ghost%20Crawler.webp"
```
^statblock

## Environment

forest, swamp, underground