---
tags:
  - Creature
Challenge: CR 1
Size: Medium
Type:
  - Construct
Creature-Tags:
  - Animated Object
hp: 31
ac: "18"
modifier: 0
Experience: 200
Maneuver-DC: 11
---
# `=this.file.name`
Only when its visor is lifted can this suit of plate mail be distinguished from a living knight. It clanks and bangs as it patrols, and it sometimes intones hollow battle cries as it attacks, slamming its metal fists into an opponent or wielding a rusty weapon with both hands.
## Overview
### Placeholder Portrait
![[z_Assets/Misc/ImagePlaceholder.png|Placeholder Portrait]]
[[z_Assets/Misc/ImagePlaceholder.png|open outside]]

**Armor Class**: `=this.ac`
**Hit Points**: `=this.hp`
**Speed**: 30 ft
**Challenge**: `=this.challenge`
**Experience**: `=this.experience`
## Other Details
**Ability Scores**: | STR | DEX | CON | WIS | INT | CHA |
|---|---|---|---|---|---|
| 14(+2) | 10(+0) | 10(+0) | 1(-5) | 10(+0) | 1(-5) |

**Damage Resistances**: piercing 
**Damage Immunities**: poison, psychic 
**Condition Immunities**: blinded, charmed, deafened, fatigue, frightened, paralyzed, petrified, poisoned
**Maneuver DC**: `=this.maneuver-dc`
**Senses**: blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages**: -
**Size**: `=this.Size`
**Type**: `=this.Type`
**Creature Tags**: `=this.creature-tags`

Placeholder

## Special Traits
***Spell-created.*** The DC for dispel magic to destroy this creature is 19. 
***False Appearance.*** While motionless, the armor is indistinguishable from normal armor.

## Actions
***Weapon.*** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (1d10 + 2) bludgeoning, piercing, or slashing damage, depending on weapon.



```statblock
image: [[Wikilink To Image]]
creature: string
name: Animated Armor
size: Medium
type: Construct
subtype: Animated object
ac: 18
hp: 31
hit_dice: 7d8
speed: 30 ft.
stats: [14, 10, 10, 1, 10, 1]
damage_resistances: piercing
damage_immunities: poison, psychic
condition_immunities: blinded, charmed, deafened, fatigue, frightened, paralyzed, petrified, poisoned
senses: blindsight 60 ft. (blind beyond this radius), passive Perception 10
languages: -
cr: 1
traits:
  - name: Maneuver DC
    desc: "11"
  - name: Spell-created
    desc: "The DC for dispel magic to destroy this creature is 19."
  - name: False Appearance
    desc: "While motionless, the armor is indistinguishable from normal armor."
actions:
  - name: Weapon
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (1d10 + 2) bludgeoning, piercing, or slashing damage, depending on weapon."
```
