---
tags:
  - overview
---
# Creature Overview
### All Creatures
```dataview
table affiliation as "Affiliation", type as "Type"
from #Creature and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### Players
```dataview
TABLE WITHOUT ID link(file.name) AS "Character Name",  affiliation as "Affiliation", type as "Type"
from #Player and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### NPCs
```dataview
table affiliation as "Affiliation", type as "Type"
from #NPC and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### Monsters
```dataview
table affiliation as "Affiliation", type as "Type"
from #Creature and #Monster and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```