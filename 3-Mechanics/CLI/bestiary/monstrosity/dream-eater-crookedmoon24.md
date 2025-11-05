---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crookedmoon24
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/environment/swamp
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Dream Eater
---
# [Dream Eater](3-Mechanics\CLI\bestiary\monstrosity/dream-eater-crookedmoon24.md)
*Source: The Crooked Moon (2024) p. 500*  

---

*Devourer of Nightmares*

---

Dream eaters are horrors that feed  on the dreams, sense of identity, and some say the very souls of other creatures. Dream eaters have the bodies and wings of great owls, while their beaks are filled with blunt, humanlike teeth and hide long snaking tongues. Their feathers are drab colors on the exterior, but their wings display a dazzling cascade of rainbow hues on the undersides when unfurled.

These colors flow and shift, mesmerizing the dream eater's prey and leaving them helpless. A creature whose dreams are devoured is left in a listless, near-blank state. Without help, their victims waste away.

## Secret

Dream eaters are confused by the intricate patterns on moth wings, and it disrupts their own colorful hypnosis.

```statblock
"name": "Dream Eater (CrookedMoon24)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "180"
"hit_dice": "19d10 + 76"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "8"
  - !!int "16"
  - !!int "19"
"speed": "30 ft., climb 30 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 17"
"languages": "understands Common but can't speak"
"cr": "10"
"traits":
  - "desc": "The dream eater doesn't provoke an Opportunity Attack when it flies out\
      \ of an enemy's reach."
    "name": "Flyby"
  - "desc": "A creature holding a moth's wing automatically succeeds on saving throws\
      \ against the dream eater's Hypnotic Wings."
    "name": "Moth Ward"
  - "desc": "The dream eater can climb difficult surfaces, including along ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The dream eater makes two Talons attacks and can use Devour Dreams."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +8, reach 5 ft. *Hit:* 11 (2d6 + 4) Slashing damage.\
      \ If the target is a Medium or smaller creature, it has the Grappled condition\
      \ (escape DC 14) from one of two talons, and it has the Restrained condition\
      \ until the grapple ends."
    "name": "Talons"
  - "desc": "The dream eater unfurls its tongue and devours the dreams from a creature's\
      \ mind. *Charisma Saving Throw:* DC 16, a creature the dream eater is grappling,\
      \ or a creature within 5 feet of it that has the Incapacitated condition (Incapacitated\
      \ creatures fail automatically). *Failure:* 18 (4d8) Psychic damage, and the\
      \ creature's Charisma score decreases by 1d6. A creature reduced to 0 Charisma\
      \ by this effect doesn't recover lost Charisma when it finishes a <span title=\"\
      Player's Handbook (2024)\">Long Rest</span>, and it has the Incapacitated condition\
      \ until its mind is restored with a Greater Restoration, Heal, or Wish spell.\
      \ *Success:* Half damage only."
    "name": "Devour Dreams"
"bonus_actions":
  - "desc": "The dream eater's wings shine with dazzling rainbow colors until the\
      \ start of its next turn, emitting <span title=\"Player's Handbook (2024)\"\
      >Bright Light</span> in a 30-foot <span title=\"Player's Handbook (2024)\">Emanation</span>\
      \ originating from the dream eater and <span title=\"Player's Handbook (2024)\"\
      >Dim Light</span> for an additional 30 feet. *Wisdom Saving Throw:* DC 16, each\
      \ creature in the dream eater's <span title=\"Player's Handbook (2024)\">Bright\
      \ Light</span>. *Failure:* Until the start of the dream eater's next turn, the\
      \ target has the Incapacitated condition, and its <span title=\"Player's Handbook\
      \ (2024)\">Speed</span> is 0."
    "name": "Hypnotic Wings"
"source":
  - "CrookedMoon24"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/CrookedMoon24/Creatures/Tokens/Flat/Dream%20Eater.webp"
```
^statblock

## Environment

forest, hill, mountain, swamp