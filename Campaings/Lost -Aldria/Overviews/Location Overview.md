---
tags:
  - overview
---
# Location Overview
### All Locations
```dataview
table type as "Type"
from #Location and !"z_templates"
where !contains(file.name, "Template")
sort name 
```

### Cities
```dataview
table type as "Type"
from #City  and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### Countries
```dataview
table type as "Type"
from #Country and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### Continnents
```dataview
table type as "Type"
from #Continent and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### Geological Landmarks
```dataview
table type as "Type"
from #GeologicalLandmark and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```

### Planes
```dataview
table type as "Type"
from #Plane and !"Obsidian"
where !contains(file.name, "Template")
sort name 
```
