---
tags:
  - Location
  - City
Government:
  - Autocracy
type:
  - Settlement
politics: Lordship
leader: []
guildsgroups:
  - Thieves Guild 1
  - Cult 1
  - Guiled 1
region:
  - This area
  - Of this area
size: Small city
population: 0
commonraces:
  - Humans
  - Elves
  - Dwarves
religion:
  - Lathander
exports:
  - Something
imports:
  - Something Else
---
<% await tp.file.move("/1. World/Cities/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewLocation");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Settlement Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


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
Placeholder

### Placeholder Map
![[z_Assets/Misc/MapPlaceholder.png|Placeholder Map]]

### Placeholder Picture
![[z_Assets/Misc/ImagePlaceholder.png|Placeholder Picture]]

Placeholder

## Notable NPCs
Placeholder

## Profile
Placeholder

## Story
Placeholder

## Points of Interest
Placeholder

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