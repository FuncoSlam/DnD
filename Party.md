---
aliases: 
tags: 
created: 2022-06-12
---
# Party
```dataview
TABLE class as "Class", player as "Player", race as "Race", created as "Created" 
FROM -"z_Templates"
WHERE status = "Alive" 
SORT created asc
```
