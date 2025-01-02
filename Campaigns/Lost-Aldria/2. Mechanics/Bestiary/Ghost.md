---
tags:
  - Creature
Challenge: CR 1
Size: Medium
Type:
  - Humanoid
Creature-Tags:
  - Aarakocra
hp: 
ac: 
modifier: 
Experience: 
Maneuver-DC:
---
# `=this.file.name`

## Overview
### Placeholder Portrait
![[z_Assets/Misc/ImagePlaceholder.png|Placeholder Portrait]]
[[z_Assets/Misc/ImagePlaceholder.png|open outside]]

**Armor Class**: `=this.ac`

**Hit Points**: `=this.hp`

**Speed**: - 

**Challenge**: `=this.challenge`

**Experience**: `=this.experience`

Placeholder

## Other Details
**Ability Scores**: | STR | DEX | CON | WIS | INT | CHA |
|---|---|---|---|---|---|
| 0(+0) | 0(+0) | 0(+0) | 0(+0) | 0(+0) | 0(+0) |

**Saving Throws**: Placeholder

**Skills**: Placeholder

**Damage Vulnerabilities**: Placeholder

**Damage Resistances**: Placeholder

**Damage Immunities**: Placeholder

**Condition Immunities**: Placeholder

**Maneuver DC**: `=this.maneuver-dc`

**Senses**: Placeholder

**Languages**: Placeholder

**Size**: `=this.Size`

**Type**: `=this.Type`

**Creature Tags**: `=this.creature-tags`

Placeholder

## Special Traits
Placeholder

## Actions
Placeholder

## Reactions
Placeholder

## Legendary Actions
Placeholder

## Description
Placeholder

## Additional Details

```statblock
name: Ghost
source: a5e MM
layout: a5e basic layout
size: Medium
type: undead
subtype: ""
ac: 11
hp: 58
hit_dice: 13d8
speed: 0 ft., fly 40 ft. It can hover.
stats:
  - 8
  - 12
  - 10
  - 10
  - 12
  - 16
maneuver: 11
damage_vulnerabilities: ""
damage_resistances: acid, fire, lightning, thunder; damage from nonmagical weapons
damage_immunities: cold, necrotic, poison
condition_immunities: charmed, fatigue, frightened, grappled, paralyzed, petrified, poisoned, prone, restrained
senses: darkvision 60 ft., passive Perception 11
languages: any languages it knew in life
cr: "4"
bestiary: true
traits:
  - name: Ethereal Sight
    desc: The ghost can see into both the Material and Etheral Plane.
    attack_bonus: 0
  - name: Incorporeal
    desc: The ghost can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.
    attack_bonus: 0
  - name: Undead Nature
    desc: A ghost doesn't require air, sustenance, or sleep.
    attack_bonus: 0
  - name: Unquiet Spirit
    desc: If defeated in combat, the ghost returns in 24 hours. It can be put to rest permanently only by finding and casting remove curse on it's remains or by resolving the unfinished business that keeps it from journeying to the afterlife.
actions:
  - name: Withering Touch
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 17 (4d6 + 3) necrotic damage. If the target is frightened, it is magically aged 1d4 x 10 years. The aging effects can be reversed with a greater restoration spell."
    attack_bonus: 5
    damage_dice: 4d6
    damage_bonus: 3
  - name: Etheral Jaunt
    desc: The ghost magically shifts from the Material Plane to the Etheral Plane or vice versa. If it wishes, it can be visible to creatures on one plane while on the other.
    attack_bonus: 0
  - name: Horrifying Visage
    desc: Each non-undead creature within 60 ft. of the ghost that can see it must succeed on a DC 13 Wisdom saving throw. On a failure, a creature is frightened for 1 minute. A frightened creature repeats the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, it is imune to this ghost's Horrifying Visage for 24 hours.
    attack_bonus: 0
  - name: Possession (Recharge 6)
    desc: |-
      One humanoid that the ghost can see within 5 ft. of it must succeed on a DC 13 Charisma saving throw or be possessed by the ghost; the ghost then disappears, and the target is incapacitated and loses control of its body. The ghost now controls the body but doesn't deprive the target of awareness. The ghost can't be targeted by any attack, spell, or other effect, except ones that turn undead, and it retains its alignment, Intelligence, Wisdom, Charisma, and immunity to being charmed and frightened. It otherwise uses the possessed target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.
      The possession lasts until the body drops to 0 hit points, the ghost ends it as a bonus action, or the ghost is turned or forced out by an effect like the dispel evil and good spell. When the possession ends, the ghost reappears in an unoccupied space within 5 ft. of the body. The target is immune to this ghost's Possession for 24 hours after succeeding on the saving throw or after the possession ends.
    attack_bonus: 0
reactions:
  - name: Horrifying Visage
    desc: If the ghost takes damage from an attack or spell, it uses Horrifying Visage.

```

