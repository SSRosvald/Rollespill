```dataview
TABLE WITHOUT ID link(file.name) AS "Session #", players, OneLiner
from "Sessions"
where (type = "Session Journal")
SORT file.name DESC
```
