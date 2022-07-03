---
aliases: 
tags: Player
player: 
created: {{date}}
---
# {{title}}

## Characters:
```dataview
TABLE class as "Class", race as "Race", created as "Created" 
FROM -"z_Templates"
WHERE player = "{{title}}" 
SORT created asc
```
