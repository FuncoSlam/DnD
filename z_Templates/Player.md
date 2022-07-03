---
aliases: 
tags: Player
player: {{title}}
created: {{date}}
---
# {{title}}

## Characters:
```dataview
TABLE class as "Class", race as "Race", created as "Created" 
FROM -"z_Templates" AND #PC 
WHERE player = "{{title}}" 
SORT created asc
```
