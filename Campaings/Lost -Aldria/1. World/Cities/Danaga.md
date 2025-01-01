---
tags:
  - Location
  - Village
Government:
  - Oligarchy
type:
  - Settlement
politics: Priesthood
leader:
  - "[[Bala]]"
guildsgroups:
  - Cult 1
  - Guiled 1
  - Spellbinders
region:
  - This area
  - Of this area
size: Village
population: 770
commonraces:
  - Humans
  - Dwarves
religion:
  - "[[Vishnu the Preserver]]"
exports:
  - Something
imports:
  - Something Else
---


> [!infobox]
> # `=this.file.name`
> ![[z_Assets/Misc/MapPlaceholder.png|cover hsmall]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> Guilds & Groups | `=this.guildsgroups` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |


# `=this.file.name`
## Overview
Danaga is governed by a priest in the local temple.

```leaflet
### Tutorial: https://youtu.be/54EyMzJP5DU
### id must be unique
id: Danaga
### Lock pins so they can't be moved
lock: true
### If true, view of map will recenter as you zoom out. 
recenter: true
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work. 
noScrollZoom: true
image: [[Danaga.png]]
### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)
### Map Pixel Width x 1 / (Pixels between Bar Scale / 100) 
### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit. 
bounds: [[0,0], [112, 112]]
height: 560px
width: 560px
### This sets where the map starts by default. Set it to the middle (half) of your bounds. 
lat: 
long: 
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map. 
minZoom: -1.5
### Max zoom is 18. 
maxZoom: 5
### Hover mouse over the Reset Zoom icon to see your current zoom level. 
defaultZoom: 2.25
### How far it zooms in or out with each step. Can be in decimals. 
zoomDelta: 0.1
### This is a string so can be any text. Change it to match your maps measurement scale. 
unit: miles
scale: 1
darkMode: false
```

Placeholder

## Notable NPCs
- **Santara:** Male Human Assassin, Good. Santara is rugged in appearance, with brown hair and soft hazel eyes. He wears leather armor and wields a poisoned dagger. Santara is guarded and devout.
- **Jaivi:** Female Human Soldier, Evil. Jaivi is overweight, with braided black hair and soft blue eyes. She wears leather armor and wields a mace and shield. Jaivi is flirtatious and irreverent.
- **Bhadra:** Female Dwarf Necromancer, Evil. Bhadra has an angular face, with brown hair and amber eyes. She wears dark robes and wields a long sword and dagger. Bhadra is searching for her missing familiar, a grey rat named Bari.
- **Anish:** Female Human Fighter, Good. Anish has silver hair and amber eyes. She wears banded mail and wields a bastard sword. Anish has an animal companion, a red firedrake named Amurup.
## Profile
Placeholder

## Story
Placeholder

## Points of Interest
**The Crossed Candles:** A grand elven tavern, known for the illusions which entertain its patrons.
**Emen's Carvings:** The workshop of a male elf woodcarver named Emen, known for his staves and wands, favored by the Spellbinders Guild.

## Valuables
Placeholder

## Internal Relationships
Placeholder

## Outward Relationships
Placeholder

## Background
Placeholder

## Additional Details
Placeholder

`=this.region`


`=link(this.region)`
