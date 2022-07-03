---
aliases: 
tags: 
created: 2022-06-12
---
# Party
```dataview
TABLE player as "Player", class as "Class", race as "Race", created as "Created" 
FROM -"z_Templates"
WHERE status = "Alive" 
SORT created asc
```
