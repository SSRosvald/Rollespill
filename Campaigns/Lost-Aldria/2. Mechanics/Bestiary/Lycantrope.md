---
tags:
  - Creature
Challenge: CR 1
Type:
  - Humanoid
Creature-Tags:
  - Shapechanger
hp: 
modifier: 
Experience: 
Maneuver-DC:
---
# `=this.file.name`

## Overview
### Placeholder Portrait
![[z_Assets/Misc/ImagePlaceholder.png|Placeholder Portrait]]
[[z_Assets/Misc/ImagePlaceholder.png|open outside]]

**Challenge**: `=this.challenge`

**Experience**: `=this.experience`

Placeholder

### Legends and Lore

### Encounter

### Signs

### Behavior

## Werebear

```statblock
image: [[Wikilink To Image]]
creature: string
name: Template - Creature
source: 
layout: a5e basic layout
size: string
type: string
subtype: string
ac: number
hp: number
hit_dice: string
speed: string
stats: [number, number, number, number, number, number]
maneuver: number
saves:
  - <ability-score>: number
skillsaves:
  - <skill-name>: number
damage_vulnerabilities: string
damage_resistances: string
damage_immunities: string
condition_immunities: string
senses: string
languages: string
cr: number
spells:
  - <description>
  - <spell level>: <spell-list>
traits:
  - name: <trait-name>
    desc: <trait-description>
  - ...
actions:
  - name: <trait-name>
    desc: <trait-description>
  - ...
legendary_actions:
  - name: <legendary_actions-name>
    desc: <legendary_actions-description>
  - ...
bonus_actions:
  - name: <trait-name>
    desc: <trait-description>
  - ...
reactions:
  - name: <reaction-name>
    desc: <reaction-description>
  - ...
```

## Wereboar

```statblock
image: [[Wikilink To Image]]
creature: string
name: Template - Creature
source: 
layout: a5e basic layout
size: string
type: string
subtype: string
ac: number
hp: number
hit_dice: string
speed: string
stats: [number, number, number, number, number, number]
maneuver: number
saves:
  - <ability-score>: number
skillsaves:
  - <skill-name>: number
damage_vulnerabilities: string
damage_resistances: string
damage_immunities: string
condition_immunities: string
senses: string
languages: string
cr: number
spells:
  - <description>
  - <spell level>: <spell-list>
traits:
  - name: <trait-name>
    desc: <trait-description>
  - ...
actions:
  - name: <trait-name>
    desc: <trait-description>
  - ...
legendary_actions:
  - name: <legendary_actions-name>
    desc: <legendary_actions-description>
  - ...
bonus_actions:
  - name: <trait-name>
    desc: <trait-description>
  - ...
reactions:
  - name: <reaction-name>
    desc: <reaction-description>
  - ...
```

## Wererat

```statblock
image: [[Wikilink To Image]]
creature: string
name: Template - Creature
source: 
layout: a5e basic layout
size: string
type: string
subtype: string
ac: number
hp: number
hit_dice: string
speed: string
stats: [number, number, number, number, number, number]
maneuver: number
saves:
  - <ability-score>: number
skillsaves:
  - <skill-name>: number
damage_vulnerabilities: string
damage_resistances: string
damage_immunities: string
condition_immunities: string
senses: string
languages: string
cr: number
spells:
  - <description>
  - <spell level>: <spell-list>
traits:
  - name: <trait-name>
    desc: <trait-description>
  - ...
actions:
  - name: <trait-name>
    desc: <trait-description>
  - ...
legendary_actions:
  - name: <legendary_actions-name>
    desc: <legendary_actions-description>
  - ...
bonus_actions:
  - name: <trait-name>
    desc: <trait-description>
  - ...
reactions:
  - name: <reaction-name>
    desc: <reaction-description>
  - ...
```

## Weretiger
Lone weretigers live in solitude on the edges of settlements, hiding their identities. Many resist their bloodthirsty urges and hunt alone in the wilderness. Others fall prey to temptation and stalk humanoids for sport. 
There are entire tribes of weretigers who accept their lycanthropy as a gift. These natural-born weretigers can control their instincts more than most lycanthropes.

```statblock
image: [[Wikilink To Image]]
creature: 
name: Weretiger
source: a5e MM
layout: a5e basic layout
size: Medium
type: Humanoid
subtype: Shapechanger
ac: 13
hp: 90
hit_dice: 12d8+36
speed: 30 ft. (40 ft in tiger form)
stats: [16, 16, 16, 10, 12, 10]
maneuver: 13
skillsaves:
  - Perception: +3 (+1d4)
  - Stealth: +5
damage_vulnerabilities: 
damage_resistances: 
damage_immunities: damage from nonmagical, non-silvered weapons
condition_immunities: 
senses: darkvision 60 ft (tiger form or hybrid form only), passive Perception 15
languages: Common
cr: 4
traits:
  - name: Keen Hearing and Smell.
    desc: "The weretiger has advantage on Perception checks that rely on hearing or smell."
actions:
  - name: Multiattack (Humanoid or Hybrid Form Only).
    desc: "The weretiger makes two attacksw neither of which can be a bite."
  - name: Longsword (Humanoid or Hybrid Form Only).
    desc: "Melee Weapon Attack: +5 to hit, reach 5ft., one target. Hit: 7 (1d8+3) slashing damage."
  - name: Longbow (Humanoid or Hybrid Form Only).
    desc: "Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. Hit: 7 (1d8+3) piercing damage."
  - name: Claw (Tiger or Hybrid Form Only).
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8+3) slashing damage. If the weretiger moves at least 20 feet straight towards a target before the attak, the target makes a DC 13 Strngth saving throw, falling [[Conditions#Prone|prone]] on a failiure."
  - name: Bite (Tiger or Hybrid Form Only).
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit 8 (1d10+3) piercing damage. If the target is a humanoid, th makes a DC 13 Constitution saving throw. On a failiure, it is cursed with [[Weretiger]] [[Lycanthropy]]."
bonus_actions:
  - name: Shapeshift.
    desc: "The weretiger changes its form to a Large tiger, a tiger-humanoid hybrid, or into its true form, which is a humanoid. While shapeshifted, its statistics are unchanged except for its size. It can't speak in tiger form. Its equipment is not transformed. It reverts to its true form if it dies."
  - name: Opportune Bite (Tiger or Hybrid Form Only).
    desc: "The weretiger makes a bite attack against a prone creature."
  - name: Frenzied Bite (While Bloodied, Tiger or Hybrid Form Only).
    desc: The weretiger makes a bite attack.
```
#### Combat
The weretiger prefers to fight in either humanoid or tiger form, but it may switch to hybrid form and use Frenzied Bite when bloodied. It resists this urge if hiding its identity or trying to avoid spreading lycanthropy.

## Werewolf
A lone werewolf that stalks its fellow villagers can terrorize an entire community. The lycanthrope might be unaware of its true nature, writing off its bloody memories as bad dreams. 
Werewolf lycanthropy runs in some prominent families, with generation after generation struggling to keep their curse a secret.

```statblock
image: [[Wikilink To Image]]
creature: 
name: Werewolf
source: a5e MM
layout: a5e basic layout
size: Medium
type: Humanoid
subtype: Shapechanger
ac: 12
hp: 58
hit_dice: 9d8 + 18
speed: 30 ft. (40 ft. in wolf form)
stats: [14, 14, 14, 10, 10, 10]
maneuver: 12
skillsaves:
  - Perception: +2 (+1d4)
  - Stealth: +4
  - Survival: +2
damage_vulnerabilities: 
damage_resistances: 
damage_immunities: damage from nonmagical, non-silvered weapons
condition_immunities: 
senses: darkvision 30 ft. (wolf or hybrid form only), passive Perception 14
languages: Common
cr: 3
traits:
  - name: Keen Hearing and Smell
    desc: "The werewolf has advantage on Perception checks that rely on hearing and smell."
  - name: Pack Tactics.
    desc: "The werewolf has advantage on attack rolls against a creature if at least one of the werewolf's allies is within 5 feet of the creature and not incapacitated."
actions:
  - name: Multiattack.
    desc: "The werewolf makes two melee attacks, only one of which can be with its bite."
  - name: Greatclub (Humanoid or Hybrid Form Only).
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8+2) bludgeoning damage."
  - name: Claw (Wolf Hybrid Form Only).
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8+2) slashing damage."
  - name: Bite (Wolf Hybrid Form Only).
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8+2) piercing damage. If the target is humanoid, it makes a DC 12 Constitution saving throw. On a failiure, it is cursed with [[Werewolf]] [[Lycanthropy]]."
bonus_actions:
  - name: Shapeshift
    desc: "The werewolf changes its form to a wolf, a wolf-humanoid hybrid, or into its true form, which is a humanoid. While shapeshifted, its statistics are unchanged. It can't speak in wolf form. Its equipment is not transformed. It reverts to its true form if it dies."
  - name: Frenzied Bite (While Bloodied, Wolf or Hybrid Form Only).
    desc: "The werewolf makes a bite attack."
```

#### Combat
Most werewolves prefer to fight in humanoid or wolf form, but some fight openly in hybrid form. The werewolf prefers to attack with surprise or alongside allies. When bloodied, a werewolf lacking self-control instinctively switches to hybrid form and uses Frenzied Bite. A werewolf flees when reduced to 15 hit points or fewer

### Variant: Alpha Werewolf
Some werewolves have fully mastered their curse and use it to prey on innocents, often leading a pack of lesser werewolves.

```statblock
image: [[Wikilink To Image]]
creature: 
name: Alpha Werewolf
source: a5e MM
layout: a5e basic layout
size: Medium
type: Humanoid
subtype: Shapechanger
ac: 12
hp: 104
hit_dice: 16d8 + 32
speed: 30 ft. (40 ft. in wolf form)
stats: [14, 14, 14, 10, 10, 10]
maneuver: 12
skillsaves:
  - Perception: +2 (+1d4)
  - Stealth: +4
  - Survival: +2
damage_vulnerabilities: 
damage_resistances: 
damage_immunities: damage from nonmagical, non-silvered weapons
condition_immunities: 
senses: darkvision 30 ft. (wolf or hybrid form only), passive Perception 14
languages: Common
cr: 6
traits:
  - name: Keen Hearing and Smell
    desc: "The werewolf has advantage on Perception checks that rely on hearing and smell."
  - name: Pack Tactics.
    desc: "The werewolf has advantage on attack rolls against a creature if at least one of the werewolf's allies is within 5 feet of the creature and not incapacitated."
  - name: Cursed Wounds.
    desc: "Each of the werewolf’s claw and bite attacks deals an additional 7 (2d6) necrotic damage, and the target’s hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0."
actions:
  - name: Multiattack.
    desc: "The werewolf makes two melee attacks, only one of which can be with its bite."
  - name: Greatclub (Humanoid or Hybrid Form Only).
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8+2) bludgeoning damage."
  - name: Claw (Wolf Hybrid Form Only).
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8+2) slashing damage."
  - name: Bite (Wolf Hybrid Form Only).
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8+2) piercing damage. If the target is humanoid, it makes a DC 12 Constitution saving throw. On a failiure, it is cursed with [[Werewolf]] [[Lycanthropy]]."
bonus_actions:
  - name: Shapeshift
    desc: "The werewolf changes its form to a wolf, a wolf-humanoid hybrid, or into its true form, which is a humanoid. While shapeshifted, its statistics are unchanged. It can't speak in wolf form. Its equipment is not transformed. It reverts to its true form if it dies."
  - name: Frenzied Bite (While Bloodied, Wolf or Hybrid Form Only).
    desc: "The werewolf makes a bite attack."
```