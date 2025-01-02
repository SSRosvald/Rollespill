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
name: Cultist
layout: a5e basic layout
source: a5e MM
size: Medium
type: humanoid
subtype: any race
ac: 12
hp: 9
hit_dice: 2d8
speed: 30 ft.
stats:
  - 10
  - 14
  - 10
  - 10
  - 10
  - 10
skillsaves:
  - deception: 2
  - religion: 2
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 10
languages: any one language (usually Common)
cr: 1/8
bestiary: true
traits:
  - name: Fanatic.
    desc: The cultist has advantage on saving throws against being charmed or frightened by creatures not in their cult.
actions:
  - name: Dagger
    desc: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one creature. Hit: 4 (1d4 + 2) piercing damage."
    attack_bonus: 4
    damage_dice: 1d4
    damage_bonus: 2
```

```statblock
image: 
name: Cult Fanatic
layout: a5e basic layout
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
maneuver: 12
saves:
  - Wis: 4
skillsaves:
  - Deception: 4
  - Persuasion: 4
  - Religion: 2
damage_vulnerabilities: 
damage_resistances: 
damage_immunities: 
condition_immunities: 
senses: passive Perception 12
languages: any one
cr: 2
spells:
  - "The cult fanatic is a 4th level spellcaster. Their spellcasting ability is Wisdom (spell save DC 12, +4 to hit with spell attacks). They have the following cleric spells prepared": 
  - Cantrips (at will): <STATBLOCK-WIKI-LINK>light<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>sacred flame<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>thaumaturgy<STATBLOCK-WIKI-LINK>
  - 1st-level (4 slots): <STATBLOCK-WIKI-LINK>ceremony<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>command<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>detect evil and good<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>inflict wounds<STATBLOCK-WIKI-LINK>
  - 2nd-level (3 slots): <STATBLOCK-WIKI-LINK>blindness/deafness<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>hold person<STATBLOCK-WIKI-LINK>
traits:
  - name: Fanatic.
    desc: The cult fanatic has advantage on saving throws against being charmed or frightened.
actions:
  - name: Dagger.
    desc: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  - name: <STATBLOCK-WIKI-LINK>Sacred Flame<STATBLOCK-WIKI-LINK> (Cantrip; V,S).
    desc: One creature the cult fanatic can see within 60 feet makes a DC 12 Dexterity saving throw, taking 4 (1d8) radiant damage on a failure. This spell ignores cover.
  - name: <STATBLOCK-WIKI-LINK>Command<STATBLOCK-WIKI-LINK> (1st-Level; V).
    desc: One non-undead creature the cult fanatic can see within 60 feet that can hear and understand them makes a DC 12 Wisdom saving throw. On a failure, the target uses its next turn to grovel (falling prone and then ending its turn).
  - name: <STATBLOCK-WIKI-LINK>Inflict Wounds<STATBLOCK-WIKI-LINK> (1st-Level; V, S).
    desc: "Melee Spell Attack: +4 to hit, reach 5 ft., one creature. Hit: 16 (3d10) necrotic damage."
  - name: <STATBLOCK-WIKI-LINK>Blindness - Deafness<STATBLOCK-WIKI-LINK> (2nd-Level; V).
    desc: One creature the cu'lt fanatic can see within 30 feet makes a DC 12 Constitution saving throw. On a failure, the creature is blinded or deafened (cult fanatic’s choice) for 1 minute. The creature repeats the saving throw at the end of each of its turns, ending the effect on a success.
  - name: <STATBLOCK-WIKI-LINK>Hold Person<STATBLOCK-WIKI-LINK> (2nd-Level; V, S, M, Consentration).
    desc: One humanoid the cult fanatic can see within 60 feet makes a DC 12 Wisdom saving throw. On a failure, the target is paralyzed for 1 minute. The target repeats the saving throw at the end of each of its turns, ending the effect on a success.
```
```statblock
image: 
name: Dragon Cultist
layout: a5e basic layout
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
maneuver: 12
saves:
  - Wis: 4
skillsaves:
  - Deception: 4
  - Persuasion: 4
  - Religion: 2
damage_vulnerabilities: 
damage_resistances: 
damage_immunities: One damage type dealt by their draconic master's breath weapon.
condition_immunities: 
senses: passive Perception 12
languages: any one
cr: 2
spells:
  - "The cult fanatic is a 4th level spellcaster. Their spellcasting ability is Wisdom (spell save DC 12, +4 to hit with spell attacks). They have the following cleric spells prepared": 
  - Cantrips (at will): <STATBLOCK-WIKI-LINK>light<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>sacred flame<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>thaumaturgy<STATBLOCK-WIKI-LINK>
  - 1st-level (4 slots): <STATBLOCK-WIKI-LINK>ceremony<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>command<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>detect evil and good<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>inflict wounds<STATBLOCK-WIKI-LINK>
  - 2nd-level (3 slots): <STATBLOCK-WIKI-LINK>blindness/deafness<STATBLOCK-WIKI-LINK>, <STATBLOCK-WIKI-LINK>hold person<STATBLOCK-WIKI-LINK>
traits:
  - name: Fanatic.
    desc: The dragon cultist has advantage on saving throws against being charmed or frightened.
actions:
  - name: Dagger.
    desc: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  - name: <STATBLOCK-WIKI-LINK>Sacred Flame<STATBLOCK-WIKI-LINK> (Cantrip; V,S).
    desc: One creature the dragon Cultist can see within 60 feet makes a DC 12 Dexterity saving throw, taking 4 (1d8) radiant damage on a failure. This spell ignores cover.
  - name: <STATBLOCK-WIKI-LINK>Command<STATBLOCK-WIKI-LINK> (1st-Level; V).
    desc: One non-undead creature the dragon cultist can see within 60 feet that can hear and understand them makes a DC 12 Wisdom saving throw. On a failure, the target uses its next turn to grovel (falling prone and then ending its turn).
  - name: <STATBLOCK-WIKI-LINK>Inflict Wounds<STATBLOCK-WIKI-LINK> (1st-Level; V, S).
    desc: "Melee Spell Attack: +4 to hit, reach 5 ft., one creature. Hit: 16 (3d10) necrotic damage."
  - name: <STATBLOCK-WIKI-LINK>Blindness - Deafness<STATBLOCK-WIKI-LINK> (2nd-Level; V).
    desc: One creature the dragon cultist can see within 30 feet makes a DC 12 Constitution saving throw. On a failure, the creature is blinded or deafened (dragon cultist’s choice) for 1 minute. The creature repeats the saving throw at the end of each of its turns, ending the effect on a success.
  - name: <STATBLOCK-WIKI-LINK>Hold Person<STATBLOCK-WIKI-LINK> (2nd-Level; V, S, M, Consentration).
    desc: One humanoid the dragcon cultist can see within 60 feet makes a DC 12 Wisdom saving throw. On a failure, the target is paralyzed for 1 minute. The target repeats the saving throw at the end of each of its turns, ending the effect on a success.
```
