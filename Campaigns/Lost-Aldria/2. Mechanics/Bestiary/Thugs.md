---
tags:
  - Creature
Challenge: CR 1
Size: Medium
Type:
  - Humanoid
Creature-Tags:
  - Thugs
hp: 
ac: 
modifier: 
Experience: 
Maneuver-DC:
---
# `=this.file.name`
Thugs are tough street brawlers, as deadly with their fists as with weapons. Thieves’ guilds and villainous nobles employ thugs to collect money and exert power. Merchants and nobles hire thugs to guard warehouses and shops.

### Thug Encounters

| CR  | **0 - 2**                         | **3 - 4**                                        | **5 - 10** | **11 - 16** |
| --- | --------------------------------- | ------------------------------------------------ | ---------- | ----------- |
| 1   | `encounter: 1d2: Thug`            | `encounter: 1d2 + 2: Thug`                       |            |             |
| 2   | `encounter: 1: Thug, 1d4: Bandit` | `encounter: 2: Thug, 1d4 + 4: Bandit`            |            |             |
| 3   | `encounter: Thug, Cutthroat`      | `encounter: 2: Thug, Apprentice Mage`            |            |             |
| 4   |                                   | `encounter: Cult Fanatic` `encounter: Cutthroat` |            |             |
|     |                                   | `encounter: Pugilist`                            |            |             |
|     |                                   | `encounter: Hill Dwarf Wrestler`                 |            |             |

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
Placeholder
```statblock
name: Thug
source: a5e MM
size: Medium
type: humanoid
subtype: any race
ac: 14
hp: 32
hit_dice: 5d8 + 10
speed: 30 ft.
stats:
  - 16
  - 12
  - 14
  - 10
  - 10
  - 10
skillsaves:
  - intimidation: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 10
languages: any one language (usually Common)
cr: 1
bestiary: true
traits:
  - name: Maneuver DC
    desc: "13"
actions:
  - name: Multiattack
    desc: The thug makes two melee attacks.
    attack_bonus: 0
  - name: Brass Knukles
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 5 (1d4 + 3) bludgeoning damage. If this damage reduces the target to 0 hit points, it is unconscious and stable."
    attack_bonus: 5
    damage_dice: 1d4
    damage_bonus: 3
  - name: Heavy Crossbow
    desc: "Ranged Weapon Attack: +4 to hit, range 100/400 ft., one target. Hit: 7 (1d10 + 2) piercing damage."
    attack_bonus: 4
    damage_dice: 1d10
    damage_bonus: 2
```
```statblock
name: Bandit
source: a5e MM
size: Medium
type: humanoid
subtype: any race
ac: 12
hp: 9
hit_dice: 2d8
speed: 30 ft.
stats:
  - 12
  - 10
  - 10
  - 10
  - 10
  - 10
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 10
languages: any one language (usually Common)
cr: 1/8
bestiary: true
traits:
  - name: Maneuver DC
    desc: "11"
actions:
  - name: Scimitar
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6 + 1) slashing damage."
    attack_bonus: 3
    damage_dice: 1d6
    damage_bonus: 1
  - name: Light Crossbow
    desc: "Ranged Weapon Attack: +3 to hit, range 80 ft./320 ft., one target. Hit: 5 (1d8 + 1) piercing damage."
    attack_bonus: 3
    damage_dice: 1d8
    damage_bonus: 1
```
```statblock
image: 
name: Cult Fanatic
source: a5e MM
size: Medium
type: humanoid
subtype: 
ac: 12
hp: 39
hit_dice: 6d8 + 12
speed: 30ft.
stats: 
 - 10
 - 14
 - 14
 - 10
 - 14
 - 14
saves:
  - Wis: +4
skillsaves:
  - Deception: +4 
  - Persuasion: +4
  - Religion: +2
damage_vulnerabilities: 
damage_resistances: 
damage_immunities:
condition_immunities: 
senses: passive Perception 12
languages: any one
cr: 2
spells: 
  - The cult fanatic is a 4th level spellcaster. Their spellcasting ability is Wisdom (spell save DC 12, +4 to hit with spell attacks). They have the following cleric spells prepared:
  - Cantrips (at will): [[light]], [[sacred flame]], [[thaumaturgy]]
  -  1st-level (4 slots): [[ceremony]], [[command]], [[detect evil and good]], [[inflict wounds]]
  - 2nd-level (3 slots): [[blindness/deafness]], [[hold person]]
traits:
  - name: Maneuver DC
    desc: "12"
  - name: Fanatic.
    desc: "The cult fanatic has advantage on saving throws against being charmed or frightened."
actions:
  - name: Dagger.
    desc: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  - name: [[Sacred Flame]] (Cantrip; V,S).
    desc: "One creature the cult fanatic can see within 60 feet makes a DC 12 Dexterity saving throw, taking 4 (1d8) radiant damage on a failure. This spell ignores cover."
  - name: [[Command]] (1st-Level; V).
    desc: "One non-undead creature the cult fanatic can see within 60 feet that can hear and understand them makes a DC 12 Wisdom saving throw. On a failure, the target uses its next turn to grovel (falling prone and then ending its turn)."
  - name: [[Inflict Wounds]] (1st-Level; V, S).
    desc: "Melee Spell Attack: +4 to hit, reach 5 ft., one creature. Hit: 16 (3d10) necrotic damage."
  - name: [[Blindness/Deafness]] (2nd-Level; V).
    desc: "One creature the cu'lt fanatic can see within 30 feet makes a DC 12 Constitution saving throw. On a failure, the creature is blinded or deafened (cult fanatic’s choice) for 1 minute. The creature repeats the saving throw at the end of each of its turns, ending the effect on a success."
  - name: [[Hold Person]] (2nd-Level; V, S, M, Consentration).
    desc: "One humanoid the cult fanatic can see within 60 feet makes a DC 12 Wisdom saving throw. On a failure, the target is paralyzed for 1 minute. The target repeats the saving throw at the end of each of its turns, ending the effect on a success."
```

