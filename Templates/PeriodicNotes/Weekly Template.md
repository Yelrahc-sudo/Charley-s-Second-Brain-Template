---
Class: Note
Updated: 2023-12-10 11:19:15
Created: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
Links: "[[🔁My Periodic Reviews]]"
tags:
  - note/weekly
priority: Medium
due: 
finished: 
started: 
project: 
resource: 
area: 
archived: 
last-review: 
status: Not Started
favorite: 
level: Raw Materials
para: Project
---


# <% tp.file.title %>


## Next Week Plan
### Action Items

- [ ] 
- [ ] 
- [ ] 

## Daily Habits

## Projects
```dataview
table started, finished, due, area
from #project 
where !contains(file.name, "Template")
where date(today) - started <= dur(7 days)
```
### Reflection
#### Learning

## Recap

### Days
```dataview
LIST
FROM #note/daily 
where date(today) - date(file.name) <= dur(7 days)
where !contains(file.name, "Template")
```
