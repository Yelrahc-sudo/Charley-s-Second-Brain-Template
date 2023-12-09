---
Updated: 2023-12-09 15:54:29
Created: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
Links: "[[⛰My Areas]]"
tags:
  - area
---


# <% tp.file.title %>
## Queries
### Projects
```dataview
table due
from #project
where !contains(file.name, "Template")
where area = "<% tp.file.title %>"
```
### Inputs
```dataview
table status, author
from #note/input 
where !contains(file.name, "Template")
where area = "<% tp.file.title %>"
```
### Notes
```dataview
table without id tags, rows.file.link as File
from #note and !#note/input 
where !contains(file.name, "Template")
where area = "<% tp.file.title %>"
flatten tags
group by tags
```

