---
Class: Note
Updated: 2023-12-10 11:19:05
Created: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
Links: "[[🔁My Periodic Reviews]]"
tags:
  - note/quarterly
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

## Future Plan
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
where date(today) - started <= dur(14 days)
```
### Reflection
#### Learning

## Recap

## Days
```dataview
LIST
FROM #note/weekly  
where date(today) - date(file.name) <= dur(14 days)
where !contains(file.name, "Template")
```
