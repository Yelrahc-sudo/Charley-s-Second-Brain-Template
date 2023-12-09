---
Class: Note
Updated: 2023-12-08 23:10:03
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


## Future Plan
### Action Items

- [ ] 
- [ ] 
- [ ] 

## Daily Habits

## Projects
- dataview project
### Reflection
#### Learning

## Recap

## Days
```dataview
LIST
FROM #note/daily 
where date(today) - date(file.name) <= dur(14 days)
where !contains(file.name, "Template")
```
