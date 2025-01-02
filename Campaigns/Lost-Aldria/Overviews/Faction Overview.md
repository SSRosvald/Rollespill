---
tags:
  - overview
---
# Faction Overview
### All Factions
```dataview
table type as "Type"
from #Faction  and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### Adventuring Groups
```dataview
table type as "Type"
from #AdventuringGroup and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### Political Groups
```dataview
table type as "Type"
from #PoliticalGroup and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### Religious Groups
```dataview
table type as "Type"
from #ReligiousGroup and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```