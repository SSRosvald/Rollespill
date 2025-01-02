---
tags:
  - Creature
Challenge: CR 1
Type:
  - Humanoid
Creature-Tags:
  - Aarakocra
hp: 
modifier: 
Experience: 
Maneuver-DC:
---
# `=this.file.name`
<% await tp.file.move("/2. Mechanics/Bestiary/" + tp.file.title) %>
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

#### Combat