---
Class: Default
Updated: 2023-12-08 17:36:36
Created: 2023-12-07 16:23:28
Links: "[[🏡My Home]]"
tags:
  - ⚒
---

# ⚒My Projects

```button
name Create New Project
type command
action QuickAdd: Project
color green
```
^button-4xtt
## Backlog ⚪

```dataview
table due, area
from #project
where status = "⚪" and !contains(file.name, "Template")
sort due asc
```

## Active 🟢
```dataview
table due, area
from #project 
where status = "🟢"  and !contains(file.name, "Template")
sort due asc
```
## Paused  🔴
```dataview
table due, area
from #project 
where status = "🔴"  AND !contains(file.name, "Template")
sort due asc
```
## Finished 🔵
```dataview
table due, area
from #project 
where status = "🔵"  AND !contains(file.name, "Template")
sort due asc
```
## Archived ⚫
```dataview
table due, area
from #project 
where status = "⚫"  AND !contains(file.name, "Template")
sort due asc
```
