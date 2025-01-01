---
tags:
  - Creature
Challenge: CR 1/4
Size: Small
Type:
  - Construct
Creature-Tags:
  - Animated Object
hp: 10
ac: "17"
modifier: 1
Experience: 50
Maneuver-DC: 11
---
# `=this.file.name`
A weapon dances in the air as if wielded by a skilled invisible warrior. It can be defeated by magic or by damaging the weapon itself. Flying swords are often found crossed on walls, in the hands of animated armor, or in the scabbards of inanimate skeletons. Most wait to attack travelers by surprise, but some clash and clatter endlessly through sword drills and mock battles. 
Swords are the most common animated weapons, although other flying weapons exist, differing in their damage type and damage dealt.
## Overview
### Placeholder Portrait
![[z_Assets/Misc/ImagePlaceholder.png|Placeholder Portrait]]
[[z_Assets/Misc/ImagePlaceholder.png|open outside]]

**Armor Class**: `=this.ac`

**Hit Points**: `=this.hp`

**Speed**: 0 ft., fly 30 ft.

**Challenge**: `=this.challenge`

**Experience**: `=this.experience`

Placeholder

## Other Details
**Ability Scores**: | STR | DEX | CON | WIS | INT | CHA |
|---|---|---|---|---|---|
| 12(+1) | 12(+1) | 10(+0) | 1(-5) | 10(+0) | 1(-5) |

**Damage Resistances**: Piercing
**Damage Immunities**: Poison, psychic
**Condition Immunities**: blinded, charmed, deafened, fatigue, frightened, paralyzed, petrified, poisoned
**Maneuver DC**: `=this.maneuver-dc`
**Senses**: Blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages**: 
**Size**: `=this.Size`
**Type**: `=this.Type`
**Creature Tags**: `=this.creature-tags`
## Special Traits
***Spell-created.*** The DC for dispel magic to destroy this creature is 19. 
***False Appearance.*** While motionless, the sword is indistinguishable from a normal sword

## Actions
***Longsword.*** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8 + 1) slashing damage
```statblock
image: [[Wikilink To Image]]
creature: string
name: Flying Sword
size: Small
type: Construct
subtype: Animated Object
ac: 17
hp: 10
hit_dice: 3d6
speed: 0 ft., fly 30 ft.
stats: [12, 12, 10, 1, 10, 1]
damage_resistances: Piercing
damage_immunities: Poison, psychic
condition_immunities: blinded, charmed, deafened, fatigue, frightened, paralyzed, petrified, poisoned
senses: Blindsight 60 ft. (blind beyond this radius), passive Perception 10
languages: -
cr: 1/4
traits:
  - name: Maneuver DC
    desc: "11"
  - name: Spell Created
    desc: "The DC for dispel magic to destroy this creature is 19."
  - name: False Appearance
    desc: "While motionless, the sword is indistinguishable from a normal sword"
actions:
  - name: Longsword
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8 + 1) slashing damage"
```

