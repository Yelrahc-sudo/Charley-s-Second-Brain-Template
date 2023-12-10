---
Class: Default
Updated: 2023-12-10 11:19:37
Created: 2023-12-10 17:23:03
Links: "[[⛰My Areas]]"
tags:
  - area
---


# area2
## Queries
### Projects
```dataview
table due
from #project
where !contains(file.name, "Template")
where area = "area2"
```
### Inputs
```dataview
table status, author
from #note/input 
where !contains(file.name, "Template")
where area = "area2"
```
### Notes
```dataview
table without id tags, rows.file.link as File
from #note and !#note/input 
where !contains(file.name, "Template")
where area = "area2"
flatten tags
group by tags
```

